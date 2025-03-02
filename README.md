Esta es una aplicación de API REST para gestionar tareas, construida con Node.js, Express y Firebase Firestore. Proporciona operaciones básicas como crear, leer, actualizar tareas. Esta API de pruebas funciona con una base de datos de documentos la cual es accedida mediante los controladores que manejan el modelo de datos guardado en Firebase, haciendo uso de promesas para manejar el controlador y generar las rutas con las que se accede a cada Request, entre GET,POST y PUT,asimismo en el proyecto se agrego la carpeta public la cual contiene un index donde se tiene tambien documentacion sobre las consultas y la lista de elementos en la base de datos, por ultimo se agrego un campo y boton para agregar un elemento directamente, haciendo uso de POST.

La API se encuentra en el siguiente enlace, donde encontrara parte de la dfocumentacion https://api-task-firebase-cd.onrender.com

Uso de la API La API proporciona los siguientes endpoints para gestionar tareas:

Obtener todas las tareas: GET /apiV1/task

Obtener una tarea por ID: GET /apiV1/task/{id}

Crear una nueva tarea: POST /apiV1/task

Actualizar una tarea: PUT /apiV1/task/{id}