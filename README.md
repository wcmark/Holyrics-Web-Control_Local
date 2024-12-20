# Holyrics-Web-Control_Local

*Este sitio web local proporcina la posibilidad de manejar controles básicos de Holyrics y visualizar la lista de medios seleccionada. Solo funciona en el mismo equipo donde se está ejecutando Holyrics, no funciona a través de ninguna red.*

1. Descarga solamente el archivo .html, puedes renombrarlo si quieres.

2. Abre el archivo con doble click o "abrir con" y elige un navegador web.
    O bien puedes ir a OBS Studio, agregar un nuevo panel web personalizado, y pegas la ruta completa del archivo. Por ej.: C:\Users\marko\Proyectos\Web-Control_Local\index.html .

3. La primera vez que visualices el Web Control Local te pedirá que indiques la IP, PUERTO y TOKEN de Holyrics.
    IP: será siempre la de localhost, es decir, `127.0.0.1`,
        en el caso de que ésta no funcione se puede usar la configurada para la red, ej.: `192.168.0.187`.
    PUERTO: por defecto es `8091`. Es el configurado para la API. (explicado en el siguiente item).
    TOKEN: Ve al menú Archivo > Configuraciones > API Server, activa la casilla correspondoente a "API Server - Local",
        botón "Administrar Permisos", "Añadir", ponerle cualquier nombre, "OK", luego "Editar",
        click sobre el encabezado "Local" y luego en "Activar (todos)".
        En la misma ventana se ve el Token parcialmente (`mH2oV****OWq`) y al lado hay un botón que te permitirá copiarlo.
        Luego de copiarlo puedes aceptar y cerrar todas las ventanas de configuración.

