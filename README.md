# ToDoListTasks

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.5.

# Start the JSON Server
To start using `json-server` and simulate a local database:

**1. Install the JSON server**:

If you don't have `json-server` installed yet, run the following command in your terminal:

```bash
npm install -g json-server
```
**2. Start the server**:

Navigate to the project folder where the `db.json` file (which acts as the database) is located and run:

```bash
json-server --watch db.json --port 3000
```

This will start the server at `http://localhost:3000/`, and you can access the database through that URL. The `db.json` file contains the initial data, and the server will automatically reload whenever this file is modified.

**Note**: If port 3000 is already in use, you can specify another port with `--port <port_number>`.

**3. Accessing the API**:

The server will be available at the following URL:

http://localhost:3000/

You can access task data through paths such as:

http://localhost:3000/tasks to retrieve all tasks.

http://localhost:3000/tasks/{id} to retrieve a specific task by its ID.

http://localhost:3000/tasks/{id} to update or delete tasks.

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
