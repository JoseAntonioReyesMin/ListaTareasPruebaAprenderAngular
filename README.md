# ToDoListTasks

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.5.

# Iniciar el Servidor JSON
Para comenzar a usar el `json-server` y simular una base de datos local:

**1. Instalar json-server**:

Si aún no tienes `json-server` instalado, ejecuta el siguiente comando en tu terminal:

```bash
npm install -g json-server
```
**2. Iniciar el servidor**:

Navega a la carpeta del proyecto donde se encuentra el archivo `db.json` (que actúa como la base de datos) y ejecuta:

```bash
json-server --watch db.json --port 3000
```

Esto iniciará el servidor en http://localhost:3000/, y podrás acceder a la base de datos a través de esa URL. El archivo `db.json` contiene los datos iniciales y el servidor se recargará automáticamente cada vez que se modifique este archivo.

**Nota**: Si el puerto 3000 ya está en uso, puedes especificar otro puerto con `--port <número_de_puerto>`.

**3. Acceder a la API**:

El servidor estará disponible en la siguiente URL:

http://localhost:3000/

Puedes acceder a los datos de tareas a través de rutas como:

http://localhost:3000/tasks para obtener todas las tareas.

http://localhost:3000/tasks/{id} para obtener una tarea específica por su id.

http://localhost:3000/tasks/{id} para actualizar o eliminar tareas.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
