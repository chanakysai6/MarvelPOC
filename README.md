# MarvelPOC
Contributing to project
Clone a branch master Branch

git clone https://github.com/informa-ibi/dna-ui.git

Check your branch

git branch  
* master 
Create new branch and checkout

git branch -b my-branch-name
git checkout my-branch-name
git push origin my-branch-name
Verify branch

git branch
master

PS: Do not commit package-lock.json file
Available Scripts
In the project directory, you can run:

npm install 
Runs the Node Modules installed in your project

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

npm build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

npm run lint
Will test code against all liniting rules and produce a warning/error summary

npm run format
Will rewrite code files with format defined in Prettier rules.
