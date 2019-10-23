## How to use
```
$ git clone https://github.com/hapumee/frame-react-and-storybook
$ cd frame-react-and-storybook
$ npm install
```

## Available Scripts

In the project directory, you can run:

### `npm run start-react`

Runs the React app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build-react`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### `npm run start-storybook`

Runs the Storybook in the browser.<br />
Open [http://localhost:9001](http://localhost:9001) to view it in the browser.

### `npm run build-storybook`
Build storybook configured in the Storybook directory into a static web app and place it inside the `.storybook-app-dist` directory. Also you can deploy the content in the `.storybook-app-dist` directory where you want.

When you want to test it locally, run below and open [http://127.0.0.1:8080/index.html](http://127.0.0.1:8080/index.html) in the browser. 
```
npx http-server .storybook-app-dist
```

### `npm run deploy-storybook`

Deploy Storybook directly into **Github** pages.<br />
Open [https://your-github/frame-react-and-storybook](https://your-github/frame-react-and-storybook) to view it in the browser.<br />
You can see the `frame-react-and-storybook` storybook with [https://hapumee.github.io/frame-react-and-storybook](https://hapumee.github.io/frame-react-and-storybook).