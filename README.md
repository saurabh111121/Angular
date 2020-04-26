# Node-Angular
Basics
npm package manager
Angular, the Angular CLI, and Angular apps depend on features and functionality provided by libraries that are available as npm packages. To download and install npm packages, you must have an npm package manager.

This setup guide uses the npm client command line interface, which is installed with Node.js by default.

To check that you have the npm client installed, run npm -v in a terminal/console window.

Step 1: Install the Angular CLI
You use the Angular CLI to create projects, generate application and library code, and perform a variety of ongoing development tasks such as testing, bundling, and deployment.

Install the Angular CLI globally.

To install the CLI using npm, open a terminal/console window and enter the following command:

content_copy
npm install -g @angular/cli
Step 2: Create a workspace and initial application
You develop apps in the context of an Angular workspace.

To create a new workspace and initial starter app:

Run the CLI command ng new and provide the name my-app, as shown here:

content_copy
ng new my-app
The ng new command prompts you for information about features to include in the initial app. Accept the defaults by pressing the Enter or Return key.

The Angular CLI installs the necessary Angular npm packages and other dependencies. This can take a few minutes.

The CLI creates a new workspace and a simple Welcome app, ready to run.

Step 3: Run the application
The Angular CLI includes a server, so that you can easily build and serve your app locally.

Go to the workspace folder (my-app).

Launch the server by using the CLI command ng serve, with the --open option.

content_copy
cd my-app
ng serve --open
The ng serve command launches the server, watches your files, and rebuilds the app as you make changes to those files.

The --open (or just -o) option automatically opens your browser to http://localhost:4200/.

You will see:

Welcome to my-app!
Next steps
If you are new to Angular, see the Getting Started tutorial. Getting Started helps you quickly learn the essentials of Angular, in the context of building a basic online store app.

Getting Started assumes the StackBlitz online development environment. To learn how to export an app from StackBlitz to your local environment, skip ahead to the Deployment section.

To learn more about using the Angular CLI, see the CLI Overview. In addition to creating the initial workspace and app scaffolding, you can use the CLI to generate Angular code such as components and services. The CLI supports the full development cycle, including building, testing, bundling, and deployment.

