# Gestor-de-tramites-documentarios-de-una-universidad
Sistema de gestión de trámites documentarios en Java con interfaz gráfica. Usa estructuras como listas, pilas, colas y árboles para registrar, mover y finalizar expedientes. Incluye alertas por prioridad, navegación entre pantallas y exportación de historial a .txt

▶️ Uso del Proyecto
Este sistema de gestión de trámites documentarios fue desarrollado en Java utilizando el entorno de desarrollo NetBeans. La aplicación incluye una interfaz gráfica construida con Swing, que permite al usuario gestionar expedientes dentro de una oficina simulada de la Universidad de Lima.

El flujo del sistema inicia en la ventana de login, donde el usuario debe autenticarse con credenciales predefinidas. Una vez autenticado, se accede al menú principal, desde el cual se pueden realizar todas las funciones disponibles: registrar un nuevo expediente, visualizar expedientes activos, moverlos entre dependencias, finalizar trámites y consultar el historial de finalizados.

Para ejecutar correctamente el proyecto:

- Abre el proyecto en NetBeans (como proyecto con estructura de paquetes).
- Presiona Shift + F11 para realizar una compilación completa (Clean and Build).
- Luego, presiona F6 para ejecutar la aplicación, la cual abrirá directamente la ventana de inicio de sesión (LoginUI).
- Usa el usuario: admin y contraseña: ulima123 para ingresar.

Este sistema no requiere conexión a base de datos, ya que gestiona toda su lógica en memoria mediante estructuras de datos personalizadas como listas enlazadas, listas dobles, colas circulares, pilas, árboles binarios y colas de prioridad, desarrolladas desde cero.
