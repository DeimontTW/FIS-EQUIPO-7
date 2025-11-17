# Requisitos Funcionales # 
- **El mapa debe representar la infraestructura de la facultad de matemáticas (Entrada y Salida de la facultad, Estacionamiento, Centro de Cómputo, Área Administrativa, Cajero, Biblioteca, Cubículos de Maestros, Cafetería, Baños, Edificio F, Edificio C, Escaleras, Edificio D, Edificio H, Canchas, Áreas Comúnes y el CLIR) en un esquema detallado en 2D y un entorno virtual Street view:** 
  La vista 2D será un plano interactivo y la Street View usará imágenes panorámicas (360°) reales de los puntos clave.

- **Mostrar la ubicación del usuario y rastrearla usando el GPS de su dispositivo:** 
  Previa autorización del usuario, se mostrará su ubicación en tiempo real en el mapa 2D mediante un ícono distintivo.

- **Alternar entre la vista en 2D y el entonrno Street View en una transición cuando el usuario así lo desee** 
  Un control claro en la interfaz (un botón) permitirá cambiar de forma fluida entre ambas vistas.

- **El entorno Street View deberá contar con botones de navegación en forma de flechas para permitir la navegación del usuario (arriba, abajo, izquierda, derecha):** 
   El usuario podrá girar la vista 360° y avanzar a otros puntos mediante flechas

- **Mostrará por medio de leyendas y símbolos puntos de interés de la facultad, representados por colores:** 
   Se usarán íconos (explicados en una leyenda) para marcar los puntos de interés, y cada uno tendrá un color diferente.

- **Al elegir un punto de interés, aparecerá un apartado con su información general, horario de atención y contacto.:** 
   Al hacer clic en un punto de interés, se mostrará una ventana emergente con su nombre, descripción, horario y contacto.

- **El mapa enviará notificaciones push sobre el estado de las dependencias, si se encuentra abierto, cerrado, en mantenimiento, si suspende sus actividades o se encuentre ocupada por algún evento:** 
   El sistema cambiara el estado de las dependencias (abierto o cerrado), de acuerdo al horario establecido por cada una, lo que generará una notificación push al usuario.

- **Incluirá una heramienta de búsqueda para puntos de interés y planificar una ruta con punto de inicio y destino.:** 
   La herramienta permitirá buscar puntos de interés por nombre y calculará/dibujará la ruta peatonal más corta entre un inicio y un destino.

- **Opción de traducción de idioma (Español-Inglés).:** 
   Un botón "ES/EN" cambiará todo el texto de la interfaz y el contenido de los puntos de interés entre los dos idiomas.

- **Apartado de configuración para activar o desactivar tooltips y animaciones del mapa:** 
  La sección de "Configuración" tendrá checkboxes para que el usuario pueda activar o desactivar estas funciones.