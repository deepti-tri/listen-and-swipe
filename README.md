# [Access the App here!](https://deepti-tri.github.io/listen-and-swipe/){:target="_blank"}

In the project directory, you can run:

### `npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`
Launches the test runner in the interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

Your app is ready to be deployed!

## Deploy the React app to GitHub Pages
### `npm install gh-pages --save-dev`
Add a `homepage` property in this format: `https://{username}.github.io/{repo-name}` to `package.json`

Add properties to the `scripts` object:\
`"predeploy": "npm run build",`\
`"deploy": "gh-pages -d build",`

### `npm run deploy`
Deploys the app to GitHub Pages (ensure that <b>GitHub Pages</b> is being built from the `gh-pages` branch.)\
Repeat this step for all further builds as well.
