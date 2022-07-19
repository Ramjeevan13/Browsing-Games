# Browse-games


Create React App is divided into two packages:

create-react-app is a global command-line utility that you use to create new projects.
react-scripts is a development dependency in the generated projects (including this one).
You almost never need to update create-react-app itself: it delegates all the setup to react-scripts.

When you run create-react-app, it always creates the project with the latest version of react-scripts so you’ll get all the new features and improvements in newly created apps automatically.

To update an existing project to a new version of react-scripts, open the changelog, find the version you’re currently on (check package.json in this folder if you’re not sure), and apply the migration instructions for the newer versions.

In most cases bumping the react-scripts version in package.json and running npm install in this folder should be enough, but it’s good to consult the changelog for potential breaking changes.

We commit to keeping the breaking changes minimal so you can upgrade react-scripts painlessly.



In the project directory, you can run:

npm start


Runs the app in the development mode.


Open http://localhost:3000 to view it in the browser.



The page will reload if you make edits.

You will also see any lint errors in the console.

npm test

Launches the test runner in the interactive watch mode.

See the section about running tests for more information.


npm run build

Builds the app for production to the build folder.

It correctly bundles React in production mode and optimizes the build for the best performance.


The build is minified and the filenames include the hashes.

Your app is ready to be deployed!


See the section about deployment for more information.

