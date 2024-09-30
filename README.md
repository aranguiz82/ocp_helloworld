# ocp_helloworld
Ejemplo: Aplicación "Hola Mundo" en Flask
1. Crear un Repositorio en OpenShift
Accede a tu consola de OpenShift.
Crea un nuevo proyecto (namespace) donde desplegarás la aplicación.

2. Construir y Desplegar la Aplicación
En OpenShift, usa la opción de Crear desde Git para apuntar a tu repositorio.
Selecciona la imagen de contenedor (Dockerfile) y configura el puerto de servicio (8080).
Completa el proceso y OpenShift construirá y desplegará automáticamente tu aplicación.

3. Acceder a la Aplicación
Una vez desplegada, OpenShift te proporcionará una URL pública. Accede a esa URL en tu navegador y deberías ver el mensaje "¡Hola, Mundo!".
