# Página Web de Monitoreo de Sensores (FOODWARD)
Este repositorio contiene una página web diseñada para el monitoreo de sensores de temperatura, que utiliza Node.js, Express y MongoDB para el backend. La aplicación permite el manejo de usuarios con autenticación y almacena información mediante cookies. Además, se conecta a la plataforma Ubidots para recibir datos de una placa ESP32 y diversos sensores.

### Descripción
La aplicación permite a los usuarios registrarse, iniciar sesión y visualizar datos de temperatura en un formato amigable. Los datos son enviados desde una placa ESP32 a Ubidots por LoRa, que luego los recupera la página web y los presenta de manera gráfica.
### Características
- Manejo de usuarios: Registro y autenticación de usuarios utilizando Node.js y MongoDB.
- Visualización de datos en tiempo real: Los datos de temperatura son enviados desde la placa ESP32 a Ubidots y luego se muestran en la interfaz de usuario.
- Uso de cookies: Almacena información de contacto con cifrado JWT para mejorar la experiencia del usuario.
- Interfaz amigable: Presentación atractiva de los datos en el frontend.

### Tecnologías utilizadas
- Backend: Node.js, Express
- Base de datos: MongoDB
- Conexión a Ubidots: API de Ubidots para obtener datos de sensores
- Cookies: Para almacenar información de contacto del usuario
- Frontend: HTML, CSS, JavaScript

