📌 To Do List - Sistema de Organización Personal
To Do List es una aplicación web diseñada para ayudar a los usuarios a planificar, visualizar y dar seguimiento a sus actividades diarias. Con un enfoque dinámico, estético y motivacional, esta herramienta permite administrar tareas de forma intuitiva y eficiente.

🧠 Funcionalidades principales
- ✅ Registro e inicio de sesión con carga de foto de perfil.
- 📋 Panel de actividades con edición, estados (pendiente, en proceso, realizado, no realizado), prioridad y eliminación.
- 🗓️ Calendario interactivo, con vista semanal y mensual, animaciones, expansión de tareas y visualización por colores de estado.
- 📊 Resumen de progreso que muestra cuántas actividades están completadas, en proceso, pendientes o no realizadas.
- 🎨 Interfaz responsiva y visualmente atractiva, con animaciones suaves y diseño modular.
- 🖼️ Carga de imágenes asociadas a cada actividad, mostradas en tarjetas y calendario.

🛠️ Tecnologías utilizadas
- Frontend: HTML5, CSS3, JavaScript ES6
- Backend: PHP puro
- Almacenamiento: Archivos JSON para persistencia de usuarios y actividades

🔓 Cómo ejecutar el proyecto localmente
- Clona el repositorio o descarga los archivos.
- Asegúrate de tener un servidor local configurado (como XAMPP, WAMP, Laragon, etc.).
- Coloca la carpeta en el directorio raíz del servidor (por ejemplo: htdocs en XAMPP).
- Asegúrate de tener las siguientes subcarpetas creadas correctamente:
- /IMG/ → Para fotos de perfil y tareas
- /JSON/ → Para almacenar los archivos login.json y actividades.json
- /pages/ → Donde están las vistas como login.php, actividades.php, etc.
- /JS/ y /CSS/ → Para estilos y scripts
- Inicia Apache en tu servidor local.
- Abre tu navegador y accede a:
http://localhost/To-Do_List/index.php

👤 Usuario no registrado
- Verá una sección motivacional con texto e imagen inspiradora.
- Botón claro para registrarse o iniciar sesión.
🙋 Usuario logueado
- Se muestra su foto de perfil y nombre.
- Accede al panel de actividades, calendario, progreso y opción para editar.
- Puede registrar nuevas actividades y visualizar su estado y avance.

📦 Archivos importantes
| Archivo | Descripción | 
| index.php | Entrada principal, muestra bienvenida y resumen | 
| login.php | Registro e inicio de sesión con foto | 
| actividades.php | Gestión de actividades | 
| calendario.php | Calendario dinámico con vista semanal y mensual | 
| progreso.php | Panel para editar actividades y ver detalles | 
| /JSON/login.json | Datos de usuarios registrados | 
| /JSON/actividades.json | Actividades personales guardadas | 



✨ Recomendaciones
- Las imágenes deben estar en la carpeta IMG/ con rutas relativas como IMG/archivo.png
- Usa navegadores modernos (Chrome, Firefox, Edge) para mejor compatibilidad.
- Revisa que los archivos tengan permisos de escritura si estás en Windows con XAMPP.

Este proyecto fue desarrollado con un enfoque centrado en la experiencia del usuario, combinando funcionalidad técnica y estética visual para impulsar la productividad diaria.
