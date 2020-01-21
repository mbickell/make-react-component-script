# make-react-component-script

powershell script to generate react component similar to ng-generate

## Folder structure

```
|-- src
|    +-components
|      +-<react components go here>
|    +-containers
|      +-<App>
|        +-App.jsx
```

## Setting up script

In your package.json add:

```
"make": "@powershell ./scripts/makeReactComponent.ps1"
```

To your scripts.

## Run script

The script accepts 2 parameters:

First is containing folder in src. e.g. components or containers.

Second is the name of the component.

```
yarn make container header
```

or

```
npm make container header
```
