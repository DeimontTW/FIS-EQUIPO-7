# **Descripción y Diseño de Pruebas de Usuario** 

## **Prueba Aspirante: Reconocimiento de Ruta**

* **Descripción:** Validar que el aspirante pueda utilizar la vista Street View, para familiarizarse visualmente con el recorrido desde la entrada de la facultad (después del estacionamiento) hasta su salón D4, donde presentará su exámen de admisión .  
* **Tipo de Usuario:** Aspirante (ej. estudiante de preparatoria que presentará el examen de admisión).  
* **Escenario:** La prueba se realiza en un lugar neutral y externo a la facultad (ej. una cafetería, centro comercial, tienda de conveniencia, parque, etc.), utilizando una computadora.  
* **Flujo Positivo:**  
* El usuario puede encontrar y activar la función "Street View" desde la vista principal.  
* El usuario puede iniciar la vista Street View desde la entrada de la FMAT(Después del estacionamiento).  
* La vista inmersiva (360°) se carga correctamente  
* El usuario puede navegar entre los diferentes puntos panorámicos usando los controles (flechas).  
* El usuario logra localizar visualmente el "Salón D4" por fuera, comprende y conoce la ruta que debe seguir.

## **Prueba Estudiante: Consulta de Información de un Aula** 

* **Descripción:** Validar que un estudiante, pueda encontrar un salón específico (H5) mediante la herramienta de buscador y consultar su información detallada, incluyendo el horario de eventos (clases, seminarios, titulaciones, etc.) del día 17/11/2025.  
* **Tipo de Usuario:** Estudiante de la facultad.  
* **Escenario:** La prueba se realiza en un área común dentro de la FMAT (centro de cómputo, cafetería, biblioteca, etc.) utilizando un dispositivo móvil.  
* **Flujo Positivo:**  
* El usuario encuentra exitosamente el "Aula H5" utilizando la herramienta de búsqueda.  
* El buscador del mapa muestra correctamente el salón buscado.  
* El usuario puede abrir la ventana de "Aula H5" haciendo clic en él..  
* El usuario visualiza el apartado de "Eventos de hoy" y “Clases programadas” dentro de esa ventana.  
* El usuario puede determinar correctamente la disponibilidad del salón a una hora específica basándose en la lista de eventos.

## **Prueba Visitante: Planificación de Ruta**

* **Descripción:** Validar que un visitante ajeno a la facultad, pueda trazar exitosamente una ruta peatonal desde su ubicación actual, hasta un punto de interés administrativo (Control Escolar).  
* **Tipo de Usuario:** Visitante (padre de familia, proveedor, repartidor).  
* **Escenario:** La prueba se realiza en la entrada de la facultad (después del estacionamiento), utilizando un dispositivo móvil.  
* **Flujo Positivo:**  
* El usuario encuentra el planificador de ruta  
* El usuario selecciona la opción "Estacionamiento" como punto de inicio, y selecciona la opción “Control Escolar” como punto de destino.  
* Un ícono rojo (que representa al usuario), y un ícono azul (que representa el destino)  aparecen en la posición correcta en el mapa 2D.  
* El sistema calcula y dibuja una ruta peatonal lógica y correcta en el mapa 2D.

