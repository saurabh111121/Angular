[![npm version](https://badge.fury.io/js/%40angular%2Fcore.svg)](https://www.npmjs.com/@angular/core)
<h2> Step 1: Install the Angular CLI </h2> 

To install the CLI using npm, open a terminal/console window and enter the following command:

```text 
  npm install -g @angular/cli
```  

<h2> Step 2: Create a workspace and initial application </h2>
To create a new workspace and initial starter app:

Run the CLI command ng new and provide the name my-app, as shown here:
```text
ng new my-app
```
The ng new command prompts you for information about features to include in the initial app. Accept the defaults by pressing the Enter or Return key.

The Angular CLI installs the necessary Angular npm packages and other dependencies. This can take a few minutes.

The CLI creates a new workspace and a simple Welcome app, ready to run.
<h2>Step 3: Run the application </h2>
Go to the workspace folder (my-app).

Launch the server by using the CLI command ng serve, with the --open option.

```text
cd my-app
ng serve --open
```
The ng serve command launches the server, watches your files, and rebuilds the app as you make changes to those files.

The --open (or just -o) option automatically opens your browser to http://localhost:4200/.

## Quickstart

[Get started in 5 minutes][quickstart].

##BootStrap
.[installation, Documentations, code etc].[abc].

[quickstart]: https://angular.io/start
.[abc]: https://www.npmjs.com/package/bootstrap#quick-start
