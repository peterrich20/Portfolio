# Portfolio
Este proyecto es un portafolio web desarrollado con Angular, diseñado para mostrar información personal y profesional de manera interactiva y estructurada. El sitio incluye varias secciones para proporcionar a los visitantes detalles sobre el autor, sus habilidades, proyectos y una forma de contacto.

Estructura del Proyecto
La aplicación sigue la estructura estándar de Angular:

1️.Archivos y Carpetas Principales
src/ → Contiene el código fuente de la aplicación.
app/ → Carpeta principal con los componentes de la web.
index.html → Archivo base donde Angular inyecta la aplicación.
styles.css → Hoja de estilos global para personalización del diseño.
main.ts → Punto de entrada de la aplicación Angular.
angular.json → Configuración de Angular.
package.json → Contiene dependencias y scripts de instalación.
server.ts → Indica que puede haber una configuración backend con Node.js o Express.

2.Funcionalidades del Portafolio
La aplicación tiene varias secciones importantes:
-Inicio:
Presenta una introducción con una breve biografía.
Puede incluir una imagen de perfil y animaciones llamativas.
-Sobre Mí:
Muestra detalles sobre la trayectoria profesional, estudios y habilidades.
Posiblemente contiene una lista de tecnologías dominadas (Angular, JavaScript, CSS, etc.).
-Proyectos:
Galería de proyectos en los que el usuario ha trabajado.
Cada proyecto puede tener una descripción, imagen y enlaces a GitHub o demostraciones en vivo.
-Contacto:
Un formulario donde los visitantes pueden enviar mensajes.
Posible integración con un backend para almacenar mensajes o enviar correos electrónicos.

3.En este proyecto se ha utilizado:
✅ Angular → Framework frontend para construir la aplicación.
✅ TypeScript → Lenguaje de programación con tipado estático.
✅ HTML y CSS → Creación de la estructura y diseño de la web.
✅ Routing de Angular → Navegación entre páginas sin recargar la web.
✅ Backend con Node.js → El archivo server.ts sugiere una integración con Express u otro servidor backend.

4.Problemas Detectados
1. Botones que no funcionan (Contacto y Saber Más sobre Mí)
Posibles causas:
-Error en el enrutamiento de Angular (app-routing.module.ts).
-El botón no está llamando correctamente a la función en TypeScript.
-Problema con la vinculación de eventos en el HTML ((click)="nombreFuncion()").
-La página de destino no está bien configurada o falta el componente correspondiente.

2. No se pueden subir archivos a GitHub
Posibles causas:
-Archivos grandes: GitHub tiene un límite de tamaño (100MB por archivo).
-.gitignore mal configurado: Puede estar excluyendo archivos importantes.
-Problema de autenticación: Si GitHub pide credenciales y falla el login.
-Errores en Git: Puedes revisar qué archivos están pendientes con git status.
