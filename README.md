# react-electron-boilerplate

This is a boilerplate for writing desktop applications using Electron with React. A more [complex boilerplate using Redux, Webpack, etc can be found here](https://github.com/electron-react-boilerplate/electron-react-boilerplate).

This project was built using [the guide published here](https://www.codementor.io/randyfindley/how-to-build-an-electron-app-using-create-react-app-and-electron-builder-ss1k0sfer).


## Setup

```
yarn install
yarn dev
```

Test using:

```
yarn test
```

## Packaging the app

```
yarn electron-pack
```

This process will create application files that are suitable for use on Windows or Mac. Check the [electron-builder configuration docs](https://www.electron.build/configuration/configuration) for further info on configuring build options. Also check out the [electron icon documentation](https://www.electron.build/icons) for info on providing the correct icon formats for both Windows and Mac applications.

## How to use this boilerplate

Clone the boilerplate, and then change the remote origin to your own project repo. 

Before changing the remote origin, it's a good time to rename the project folder and edit the package.json details. In particular it's important to update Author details, `appId`, and `productName`, as these are the publishing details of your final Electron application.

```
git clone git@github.com:NuclearError/react-electron-boilerplate.git
cd react-electron-boilerplate
```

After you're happy with the changes, change the remote origin from the original repo to yours:

```
git remote set-url origin git://your-repo-url
```

You can now develop your app as normal, using the `src` folder. Store assets and icons in the `public` folder. You can test out how your application will look in packaged form by following the packaging guidelines above.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs
