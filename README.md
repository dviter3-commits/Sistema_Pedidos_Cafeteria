# Sistema_Pedidos_Cafeteria
Repositorio del caso Sistema de pedidos para cafetería universitaria
1. Descripción del caso

El sistema de pedidos para la cafetería universitaria surge como respuesta a la necesidad de mejorar la atención, reducir el tiempo de espera y optimizar la organización interna del establecimiento. Actualmente, los estudiantes y docentes deben esperar largas filas para realizar pedidos, lo que afecta la eficiencia del servicio y genera congestionamiento en horas pico.

El sistema propuesto permitirá que los usuarios consulten el menú en línea, seleccionen los productos que desean consumir, procesen su pedido y reciban una notificación con el tiempo estimado de entrega. De manera simultánea, el personal de la cafetería podrá gestionar pedidos, actualizar el inventario y visualizar estadísticas diarias de consumo. Con esto se busca modernizar el servicio y ofrecer una experiencia más rápida, ordenada y accesible.

2. Objetivos del sistema
Objetivo general
Desarrollar un sistema digital que permita gestionar los pedidos de la cafetería universitaria de manera eficiente, reduciendo tiempos de espera y mejorando la organización operacional.

Objetivos específicos
- Facilitar a los usuarios la consulta del menú y la realización de pedidos desde cualquier dispositivo.
- Optimizar la gestión interna del personal de la cafetería mediante un panel administrativo centralizado.
- Generar reportes de consumo e inventario que apoyen la toma de decisiones.
- Reducir errores en los pedidos y evitar la saturación de filas en horas de mayor demanda.
- Mantener un registro histórico de ventas y pedidos que permita mejorar el servicio.

3. Requerimientos del sistema
3.1 Requerimientos funcionales
-El sistema debe permitir el registro e inicio de sesión de los usuarios.
-Los usuarios podrán visualizar el menú actualizado y agregar productos al carrito.
-El sistema debe permitir confirmar pedidos y generar un número de orden.
-El personal podrá actualizar el estado del pedido (pendiente, en preparación, listo, entregado).
-El administrador podrá gestionar inventarios y generar reportes de ventas.

3.2 Requerimientos no funcionales
-El sistema debe ser accesible desde dispositivos móviles y navegadores modernos.
-La interfaz debe ser intuitiva y fácil de usar.
-Los datos deben almacenarse de forma segura mediante cifrado.
-El sistema debe tener disponibilidad mínima del 95% en horario de atención.
-Debe permitir escalabilidad para futuras mejoras.

| **ID** | **Función evaluada**       | **Caso de prueba**                           | **Resultado esperado**                                      | **Validación**                                   |
|--------|----------------------------|----------------------------------------------|--------------------------------------------------------------|--------------------------------------------------|
| PF-01  | Registro de usuarios       | Registrar una cuenta nueva                    | El sistema crea la cuenta y permite iniciar sesión           | Usuario aparece en la base de datos             |
| PF-02  | Realización de pedido      | Agregar productos y confirmar pedido          | Se genera número de orden y estado “Pendiente”               | Pedido registrado correctamente                  |
| PF-03  | Actualización de estado    | Cambiar estado a “En preparación”             | El usuario recibe notificación del cambio                    | Estado reflejado en el panel del cliente        |
| PF-04  | Control de inventario      | Disminuir stock al confirmar pedido           | Stock actualizado sin inconsistencias                        | No permite seleccionar productos agotados       |
| PF-05  | Consulta de historial      | Ver pedidos previos                           | Se despliega lista con fechas y detalles                     | Datos coinciden con la base de datos             |


5. Tipo de mantenimiento propuesto
- Mantenimiento correctivo
Aplicado para corregir errores como fallas en el registro, problemas de visualización del menú, estados de pedido que no cambian o errores en cálculos de precios.

-Mantenimiento adaptativo
Implementado si la universidad modifica su infraestructura tecnológica, como integración con otros sistemas institucionales, nuevos métodos de pago o cambios en servidores.

-Mantenimiento perfectivo
Enfocado en mejorar el rendimiento y usabilidad del sistema: optimización del tiempo de carga, rediseño de la interfaz, nuevos filtros del menú, gráficos en reportes o integración de avisos automáticos de inventario.

6. Reflexión sobre el control de versiones

El control de versiones es una herramienta esencial durante el desarrollo del sistema de pedidos, ya que permite administrar los cambios de forma organizada y segura. Gracias a herramientas como Git y GitHub, es posible llevar un registro detallado de cada modificación realizada en el código o la documentación técnica, facilitando la detección de errores, la comparación entre versiones y la restauración de estados anteriores cuando algo falla. Esto asegura estabilidad y coherencia en todo el proyecto.

Además, el uso del control de versiones fomenta el trabajo colaborativo, permitiendo que varios desarrolladores trabajen simultáneamente sin interferir entre sí. Esto es particularmente útil en proyectos académicos o institucionales, donde cada integrante puede aportar, documentar y mejorar continuamente el sistema. En conjunto, el control de versiones se convierte en un pilar para mantener la calidad del software y garantizar una evolución ordenada del proyecto.
