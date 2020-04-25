> This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Purpose

This repository adds a couple configuration defaults and scripts to a default CRA install.

This can be useful for pair programming interviews, when every minute counts.

## Changes

### Yarn & TypeScript

This was created using `yarn create react-app demo-cra-ts --template typescript`. As a result, it has a yarn.lock file, a [tsconfig](tsconfig.json), and all application code uses `.ts` and `.tsx`.

### Prettier and lint scripts

An example Prettier config is added, as well as a script for linting and applying fixes. No CI config is currently present in this repo, however.

### Lodash

Lodash was added because some of its methods are still useful, such as _.range, _.debounce, and \_.throttle. It typings have been added as well.

### Sass

Although CRA [recommends against the use of Sass](https://create-react-app.dev/docs/adding-a-sass-stylesheet/) due to a recommendation to not reuse classes across components, there are several other reasons why the use of Sass may be desirable over CSS-in-JS like Styled Components. In the interest of expediency, especially in pair-coding interviews, sometimes it's best to just stick to Sass.

## Docs

For convenience, here are a couple of useful links for documentation within easy reach.

- [Create React App](https://create-react-app.dev/docs/getting-started)
- [Lodash](https://lodash.com/docs/)
- [Sass Basics](https://sass-lang.com/guide)
- [Sass Docs](https://sass-lang.com/documentation)

Familiarity with React, TypeScript, Yarn, and Git are all assumed.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn lint`

This validates the project for adherence to the [Prettier config file](.prettierrc). Also, `lint-fix` is available, which applies linter fixes.

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
