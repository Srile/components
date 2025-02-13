# Wonderland Engine Components

Wonderland Engine's official component library.

Learn more about Wonderland Engine at [https://wonderlandengine.com](https://wonderlandengine.com).

## Usage

Install the components to your project's package as follows:
```
npm i --save @wonderlandengine/components
```

Wonderland Editor will automatically detect all components in the package add auto-import
those that you use in the scene.

## Development

Start by installing all dependencies:

```
npm install
```

To build the TypeScript code, run the `build` or `build:watch` script:
```
npm run build:watch
```

## Running Tests

Some components have automated tests, you can run them with the `test` and `test:watch` scripts:
```
npm run test:watch
```

To run tests with a deploy from archive, use the `DEPLOY_FOLDER` environment variable:
```
DEPLOY_FOLDER="../../some/deploy" npm run test:watch
```

## License

Wonderland Engine API TypeScript and JavaScript code is released under MIT license.
The runtime and editor are licensed under the [Wonderland Engine EULA](https://wonderlandengine.com/eula)
