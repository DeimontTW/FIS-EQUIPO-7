# REQUISITOS NO FUNCIONALES

- **Geofencing y privacidad:**  
  El sistema debe restringir la visualización y el rastreo de la ubicación del usuario únicamente cuando este se encuentre físicamente dentro del perímetro geográfico de la Facultad de Matemáticas, utilizando geofencing para validar la posición.

- **Alta disponibilidad:**  
  El sistema debe garantizar una disponibilidad del 99.999% mensual, equivalente a un máximo de aproximadamente 5 minutos de inactividad no planificada por mes.

- **Rendimiento de navegación:**  
  La navegación entre secciones del sistema no debe superar una latencia de 3 segundos por interacción en condiciones de red estándar (al menos 5 Mbps de bajada).

- **Compatibilidad multiplataforma:**  
  El sitio debe ser completamente funcional y visualmente coherente en los navegadores modernos más utilizados (Chrome, Firefox, Safari, Edge) y en dispositivos móviles (Android e iOS) con pantallas desde 5” hasta 15”, adaptándose mediante diseño responsivo.

- **Seguridad en la comunicación:**  
  El sistema debe implementar cifrado HTTPS en todas las comunicaciones para proteger los datos del usuario.

- **Documentación técnica:**  
  El sistema debe estar documentado utilizando estándares de desarrollo web para facilitar futuras actualizaciones o corrección de errores.

- **Anonimización de imágenes:**  
  Las imágenes mostradas en la vista tipo Street View deben aplicar un desenfoque automático (blur) sobre los rostros humanos detectados, utilizando técnicas de anonimización visual antes de su publicación, para proteger la identidad y privacidad de las personas.

- **Escalabilidad y concurrencia:**  
  El sistema debe soportar un mínimo de 300 usuarios activos concurrentes accediendo simultáneamente a las funcionalidades principales (navegación del mapa, visualización en Street View y consulta de información de espacios) sin degradación perceptible en el rendimiento.