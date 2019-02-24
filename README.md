# lint-configuration
Lint configuration, which I use with my projects. Contains different
framework and library lint configurations and also a global lint 
which can be used by any typescript project 

### Installation
```
npm install lint-configuration -D
```

```
yarn add lint-configuration -D
```

### Usage
To use it in your project, just add `tslint.json` in your
project root directory with the following lint configuration.

 
```
{
    "extends": "lint-configuration/config/tsconfig.global.json"
}
```

##### Options

- Typescript lint configuration `tsconfig.global.json`
- React lint configuration `tsconfig.react.json` (Extends the Typescript lint configuration)
