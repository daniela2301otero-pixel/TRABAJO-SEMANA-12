# TRABAJO-SEMANA-12
preguntas-semana12
Pregunta 1:
Respuesta: Una herramienta simple para que una comunidad registre apoyos a una causa y genere una petición formal.

Pregunta 2:
Respuesta: Convertir información registrada en un documento formal que pueda ser compartido o presentado.

Pregunta 3:
Respuesta: Para evitar almacenar información innecesaria o sensible.

Pregunta 4:
Respuesta: Enviar notificaciones automáticas cuando ocurre un evento en el sistema.

flujo-sistema.txt
Flujo del sistema "Petición en 3 Clics"

1. Un ciudadano registra una nueva causa en la plataforma.
2. La información queda almacenada en la base de datos.
3. Otros ciudadanos pueden ingresar y apoyar la causa.
4. El sistema registra y cuenta automáticamente los apoyos recibidos.
5. Cuando la causa cumple los requisitos, el sistema genera un documento PDF con la petición para ser presentado ante la entidad correspondiente.

modelo-datos.txt
Entidad: Causa

Campos principales:
- id
- titulo
- descripcion
- fecha

Propósito:
Guardar la información de cada causa comunitaria registrada en la plataforma.

Entidad: Apoyo

Campos principales:
- id
- causa_id
- nombre
- fecha

Propósito:
Registrar los apoyos que recibe cada causa y hacer seguimiento a la participación de la comunidad.

automatizacion
Automatización con n8n o Telegram

Evento:
Nueva causa registrada en la plataforma.

Mensaje:
"Nueva causa creada en la plataforma. Revísela para su seguimiento."

Información que no debe enviarse:
No se deben enviar cédulas, teléfonos, direcciones, contraseñas, comentarios privados ni otros datos personales o sensibles de los usuarios.

reflexion-semana12
Durante este curso aprendí que la tecnología puede fortalecer la participación ciudadana y mejorar la organización comunitaria. También comprendí la importancia de usar bases de datos para almacenar información de forma organizada y segura. Aprendí que la autenticación protege el acceso a la plataforma y que la automatización facilita procesos como las notificaciones. Además, entendí que los datos personales deben protegerse para garantizar la privacidad de la comunidad. El uso de herramientas como GitHub, Node.js, n8n y Telegram permite desarrollar soluciones prácticas y colaborativas. Estos conocimientos ayudan a crear plataformas transparentes, eficientes y con impacto social para beneficiar a las comunidades.


