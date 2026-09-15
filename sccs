// Esperar a que el DOM esté completamente cargado
document.addEventListener('DOMContentLoaded', () => {
    
    // Obtener referencias a los elementos del HTML
    const button = document.getElementById('btn-action');
    const message = document.getElementById('message');

    // Contador de clics
    let clickCount = 0;

    // Escuchar el evento de clic en el botón
    button.addEventListener('click', () => {
        clickCount++;
        message.textContent = `¡Has hecho clic ${clickCount} ${clickCount === 1 ? 'vez' : 'veces'}! 🚀`;
        
        // Efecto rápido de animación simple
        message.style.opacity = '0';
        setTimeout(() => {
            message.style.transition = 'opacity 0.3s ease';
            message.style.opacity = '1';
        }, 50);
    });

});
