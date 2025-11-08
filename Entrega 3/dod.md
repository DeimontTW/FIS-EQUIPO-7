# Definition of done

## Funcionalidad
1. El botón o ícono de "Street View" está habilitado y, al activarlo, carga correctamente la vista inmersiva de Google Street View para las calles y caminos del campus universitario que tienen cobertura por el servicio.

2. Tanto la vista de mapa 2D como la vista Street View permiten al usuario la navegación mediante gestos táctiles (en dispositivos móviles) o arrastre del cursor (en desktop), así como zoom para acercar o alejar la vista.

3. El sistema utiliza el GPS del dispositivo (con una precisión mínima de 5 metros) para detectar y marcar la ubicación actual del usuario en el mapa, representada por un pin.

4. El usuario puede seleccionar un Punto de Interés de una lista filtrada o haciendo clic/tap directamente en su icono en el mapa para establecerlo como destino.

5. La ubicación del usuario (el pin) se actualiza en el mapa con una frecuencia mínima de cada 2 segundos mientras este se desplaza físicamente por el campus, reflejando su movimiento en tiempo real.

6. El sistema muestra de forma visible una estimación del tiempo de caminata en minutos, calculada en base a la ruta peatonal más corta y una velocidad de marcha promedio de 5 km/h.

7. Los Puntos de Interese designados (mínimo 20: aulas, bibliotecas, cafeterías, etc.) se muestran en el mapa mediante iconos diferenciados y una leyenda claramente visible.

8. Al seleccionar un Punto de Interés en el mapa, se despliega un tooltip o ventana modal que muestra su nombre, horario de atención y una breve descripción o imagen.


9. El sistema calcula y dibuja automáticamente en el mapa la ruta peatonal más corta (en distancia metros) desde la ubicación actual del usuario hasta el destino seleccionado, representándola con una línea sólida.

## Diseño y experiencia de usuario
1. La interfaz del mapa es 100% responsiva y se adapta correctamente a las ventanas gráficas de los celulares inteligentes, tabletas y ordenadores, manteniendo la funcionalidad completa y la legibilidad de los elementos en todos ellos.

2. La navegación por el mapa (arrastre, zoom, cambio de vistas) es intuitiva para un usuario promedio sin necesidad de instrucciones previas.

3. La interfaz de usuario del mapa (botones, paleta de colores, tipografía) sigue consistentemente la guía de estilos del sitio web de la universidad, integrándose visualmente con el resto de los componentes de la página.

## Rendimiento
1. El mapa base (vista 2D con los Puntos de Interés) se carga completamente y es interactivo en menos de 3 segundos, simulando una conexión a Internet de 4G LTE (5 Mbps de descarga).

2. La transición entre la vista de mapa 2D y la vista Street View se completa en menos de 3 segundo, sin congelamientos o pantallas en blanco perceptibles para el usuario.

3. La función de geolocalización obtiene una primera lectura de la posición del usuario con una precisión mínima de 10 metros en menos de 5 segundos desde que se concede el permiso.