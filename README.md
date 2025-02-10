Time Tracker
Time Tracker es una aplicación web simple y funcional diseñada para ayudarte a llevar un registro del tiempo que dedicas a diferentes actividades. Con una interfaz intuitiva, puedes iniciar, detener y reiniciar un cronómetro, y además, cambiar entre un tema claro y oscuro para una mejor experiencia visual.

Características
Cronómetro: Inicia, detén y reinicia el cronómetro con facilidad.
Tema Claro y Oscuro: Cambia entre los temas claro y oscuro con un solo clic.
Diseño Responsivo: La aplicación está optimizada para ser utilizada en dispositivos móviles y de escritorio.
Interfaz Simple: Una interfaz limpia con botones grandes para una fácil interacción.
Funciones Básicas: Incluye botones para iniciar, detener y reiniciar el cronómetro.
Tecnologías Usadas
HTML: Estructura básica de la página web.
CSS: Estilos personalizados, incluidos los de los botones, el cronómetro y los temas.
JavaScript: Funcionalidades del cronómetro y la alternancia de temas.
LocalStorage: Guarda la preferencia de tema del usuario.
Instrucciones de Uso
Para comenzar a usar Time Tracker, sigue estos pasos:

Abre el archivo index.html en tu navegador: Abre el archivo index.html en cualquier navegador moderno para comenzar a usar el cronómetro.

Iniciar el Cronómetro: Haz clic en el botón "Start" para comenzar a contar el tiempo. El cronómetro comenzará desde cero y se actualizará cada segundo.

Detener el Cronómetro: Haz clic en el botón "Stop" para detener el cronómetro en el tiempo actual. Si decides reanudarlo, simplemente haz clic en "Start".

Reiniciar el Cronómetro: Si deseas reiniciar el cronómetro, haz clic en el botón "Reset". Esto restablecerá el tiempo a 00:00:00.

Alternar Tema: Para cambiar entre el tema claro y oscuro, haz clic en el botón de "Toggle Theme" ubicado en la parte superior derecha de la pantalla.

Personalización
Puedes modificar el diseño y los colores de la aplicación editando las variables CSS en la sección :root:

css
Copiar
Editar
:root {
    --primary-bg: #ffffff; /* Fondo principal */
    --primary-color: #333;  /* Color del texto principal */
    --accent-color: #1a75ff; /* Color de acento */
    /* Colores de botones */
    --button-bg-start: #4caf50;
    --button-bg-stop: #f44336;
    --button-bg-reset: #ff9800;
    --button-hover-start: #43a047;
    --button-hover-stop: #e53935;
    --button-hover-reset: #fb8c00;
}
Si deseas cambiar la paleta de colores, simplemente modifica estas variables para que se ajusten a tus preferencias.

Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
