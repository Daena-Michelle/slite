# Slite Technical Test
The test consist of a simple page extracted from the Slite app that you will need to reproduce in React. Here's the Figma (design) of the page you need to implement:
https://www.figma.com/file/T0tvBUI22O3EF70pvsrpqC/Developer-test-Demo-app-structure?node-id=0%3A1.

The scope of the test is:

- Setup basic React application with Create React App
<!-- Done. -->
- Reproduce the design with React components. Use plain CSS, do not waste time setting up CSS-in-JS solutions
<!-- To ensure the most faithful look I've decided to combine plain CSS with Bootstrap. I'm quicker and most effective with it. -->
- Use React Router to implement the 4 static pages corresponding to the 4 links in the sidebar (have different content for each page but one needs to have the design on Figma)
<!-- Done. -->
- Have a simple state to handle Favorites expand/collapse
<!-- I'm not sure I understood what you meant with this, my Sidebar expansion for favorites works without the need of state handling.
If you meant that you want for me to create a way to store which pages are or aren't favorites, then I'll do my best. -->


## Final notes:
<!--
I know the header and favorite icons are still missing, as so is some styling improvement here and there (like the list to the right),
but I'm also sure I'd be able to do them no problem.
I was told not to overdo it, but I was certainly having fun by the moment I was running out of time.
Hope you like the final result!
Regards,
Daena Michelle.
-->





This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

 Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
