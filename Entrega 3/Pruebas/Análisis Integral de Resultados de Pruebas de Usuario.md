**Análisis Integral de Resultados de Pruebas de Usuario**

## 1\. Metodología y Muestra

### 1.1 Distribución por Perfil

| Perfil | Número de Usuarios | Dispositivo Principal | Edad Promedio |
| :---- | :---- | :---- | :---- |
| Estudiante | 6 | Móvil (100%) | 21.3 años |
| Aspirante | 6 | Escritorio (67%) / Móvil (33%) | 17.8 años |
| Visitante | 4 | Móvil (100%) | 51.3 años |

---

## 2\. Resultados Estadísticos por Perfil

### 2.1 Prueba Estudiante \- Búsqueda Aula H5

| Métrica | Promedio | Desviación Estándar | Mejor/Peor Caso |
| :---- | :---- | :---- | :---- |
| Tasa Finalización | 100% | ±0% | 100%/100% |
| Tareas Completadas sin Ayuda | 83.3% | ±16.3% | 100%/60% |
| Número de Errores | 1.0 | ±1.4 | 0/4 |
| Pasos Totales | 4.2 | ±1.2 | 3/6 |
| Satisfacción | 4.3/5 | ±0.5 | 5/4 |

### 2.2 Prueba Aspirante \- Street View Salón D4

| Métrica | Promedio | Desviación Estándar | Mejor/Peor Caso |
| :---- | :---- | :---- | :---- |
| Tasa Finalización | 100% | ±0% | 100%/100% |
| Tareas Completadas sin Ayuda | 61.1% | ±22.9% | 100%/20% |
| Número de Errores | 26.0 | ±35.8 | 2/96 |
| Pasos Totales | 41.5 | ±37.2 | 20/113 |
| Satisfacción | 3.5/5 | ±0.8 | 5/2 |

### 2.3 Prueba Visitante \- Ruta Control Escolar

| Métrica | Promedio | Desviación Estándar | Mejor/Peor Caso |
| :---- | :---- | :---- | :---- |
| Tasa Finalización | 100% | ±0% | 100%/100% |
| Tareas Completadas sin Ayuda | 66.7% | ±23.6% | 100%/33% |
| Número de Errores | 4.0 | ±1.6 | 3/5 |
| Pasos Totales | 6.8 | ±2.5 | 4/10 |
| Satisfacción | 3.3/5 | ±0.8 | 4/2 |

---

## 3\. Análisis Comparativo Estadístico

### 3.1 Eficiencia por Perfil

| Perfil | Tiempo Estimado (min) | Eficiencia Relativa | Consistencia |
| :---- | :---- | :---- | :---- |
| Estudiante | 2-4 min | Alta | Consistente |
| Aspirante | 5-11 min | Baja | Variable |
| Visitante | 3-6 min | Media | Moderada |

### 3.2 Patrones de Error

* **Estudiantes**: Errores menores en localización inicial (33% de usuarios)  
* **Aspirantes**: Alta variabilidad en errores (2-96 por usuario)  
* **Visitantes**: Errores consistentes en localización de herramientas

---

## 4\. Hallazgos Cualitativos Unificados

### 4.1 Fortalezas Comunes Identificadas

**Funcionalidad Central**

* *"Funciona muy bien y me parece muy apto para mí edad"* (Estudiante, prueba 1\)  
* *"Es fácil, y no se me dificultó hacer el recorrido"* (Aspirante 1\)  
* *"Es simple y dice lo necesario"* (Visitante, primer usuario)

**Navegación una vez Superada la Curva de Aprendizaje**

* *"Logró desplegar la ventana de información sin problemas"* (Estudiante, prueba 1\)  
* *"Los ubicó y usó correctamente"* (Aspirante 2\)  
* *"Siguió el camino marcado sin problemas"* (Visitante, segundo usuario)

### 4.2 Problemas Críticos Identificados

**Diseño de Interfaz y Descubribilidad**

* *"Es difícil de ver la barra de búsqueda por que es pequeña y mal posicionada"* (Usuario1 Estudiante)  
* *"No se ve la barra de búsqueda, pensé que era el fondo"* (Aspirante 2\)  
* *"Fue lo último que encontró debido a que se encuentra hasta el fondo de la pagina"* (Visitante Usuario1)

**Expectativas vs Realidad Interactiva**

* *"Pensó que se podía buscar directamente oprimiendo el mapa"* (Usuario1 Estudiante)  
* *"Pensó que el mapa 2D tendría elementos seleccionables y no los hubo"* (Aspirante 3\)  
* *"Confusa debido a los diferentes botones del mapa que no eran funcionales"* (Visitante Usuario1)

**Problemas de Orientación y Navegación**

* *"Me molesta que me perdía en el mapa, regresaba al 2D y al regresar al Street View me había regresado al inicio"* (Aspirante 3\)  
* *"Cuando al hacer click en el mapa 2D no había nada seleccionable"* (Aspirante 2\)  
* *"En una primera instancia, entró al edificio A, pero después regresó, porque no encontró control escolar"* (Visitante Usuario2)

### 4.3 Comentarios Constructivos

**Mejoras Sugeridas por Usuarios**

* *"Debería ser touch el mapa para que sea más rápido buscar el aula"* (Usuario1 Estudiante)  
* *"¿Por qué no simplemente ponen el mapa en el Street View igual para que sepamos por dónde estamos navegando?"* (Aspirante 3\)  
* *"Mejor claridad visual de la ruta trazada en el mapa"* (Visitante Usuario1)  
* *"Especificar en el croquis del mapa que se encuentra dentro de cada edificio"* (Visitante Usuario2)

---

## 5\. Análisis por Perfil de Usuario

### 5.1 Perfil Estudiante

**Patrón de Comportamiento**: Eficiente una vez superada la barrera inicial de localización del buscador.

**Cita Representativa**: *"tiene una interfaz que permite una fácil navegación"* (Estudiante, prueba 3\)

**Hallazgo Principal**: 67% de los estudiantes completaron todas las tareas sin ayuda después de encontrar la barra de búsqueda.

### 5.2 Perfil Aspirante

**Patrón de Comportamiento**: Alta variabilidad en desempeño, con significativa confusión en la navegación Street View.

**Cita Representativa**: *"Me sentí perdido al no conocer la facultad, pero esto me ayudo a precisamente, conocerla"* (Aspirante 3\)

**Hallazgo Principal**: Solo 33% de aspirantes mostraron alta satisfacción, versus 83% en estudiantes.

### 5.3 Perfil Visitante

**Patrón de Comportamiento**: Dificultades consistentes en localizar herramientas, pero buena ejecución una vez encontradas.

**Cita Representativa**: *"Podrían mejorar el desplazamiento debajo del mapa, ya que no se desliza fácil"* (Visitante, segundo usuario)

**Hallazgo Principal**: 100% de visitantes requirieron ayuda para localizar el planificador de rutas.

---

## 6\. Patrones Transversales

### 6.1 Problemas de Descubribilidad

* **66%** de todos los usuarios tuvieron dificultades iniciales para localizar herramientas clave  
* La barra de búsqueda y planificador de rutas presentaron los mayores desafíos de descubribilidad

### 6.2 Expectativas de Interactividad No Cumplidas

* **50%** de usuarios intentaron interactuar con elementos no funcionales del mapa  
* La expectativa de mapas táctiles/interactivos fue consistente across perfiles

### 6.3 Brecha Generacional en Satisfacción

* Usuarios más jóvenes (estudiantes): **4.3/5** satisfacción  
* Usuarios mayores (visitantes): **3.3/5** satisfacción  
* Diferencia significativa en tolerancia a problemas de usabilidad

---

## 7\. Métricas de Usabilidad Consolidadas

### 7.1 Tasa de Éxito por Tipo de Tarea

| Tipo de Tarea | Tasa de Éxito | Compleción sin Ayuda |
| :---- | :---- | :---- |
| Búsqueda de espacios | 100% | 83% |
| Navegación Street View | 100% | 61% |
| Planificación de rutas | 100% | 67% |

### 7.2 Indicadores de Eficiencia

* **Tiempo promedio para tarea inicial**: 2.3 minutos  
* **Curva de aprendizaje**: Empinada para aspirantes, moderada para otros perfiles  
* **Recuperación de errores**: Efectiva en 89% de los casos

*Este análisis evidencia patrones consistentes en problemas de descubribilidad y expectativas de interactividad, con variaciones significativas en satisfacción y eficiencia entre perfiles de usuario.*