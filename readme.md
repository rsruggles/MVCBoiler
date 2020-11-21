A NodeJS MVC Boiler

In your terminal, cd into the project directory (MVCBoiler) and run 'npm install' to install project dependencies.

You'll notice in .gitignore, we've opted to ignore our .env file, which will eventually hold potentially sensitive environment variables. Create your own .env file in the root directory, and add this line:

DATABASE_URL=mongodb://localhost/MVCBoiler

Make sure you have mongo installed and running. At this point you should be completely setup to run this project. In terminal run 'npm run devStart' to launch the server. Then in your browser you should be able to navigate to http://localhost:3000 to view the project.