
# ComponentLibrary

## Project setup
```
yarn install
npm install
```

### Compiles and hot-reloads for development
```
yarn serve

npm run serve
```

### Compiles and minifies for production
```
yarn build
npm run build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
pluginOptions: {
        'style-resources-loader': {
            preProcessor: 'less',
            patterns: [
                path.resolve(__dirname, './src/assets/less/enter.less')
            ]
        }
    }
