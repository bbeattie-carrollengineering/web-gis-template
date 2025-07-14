# Vue and ArcGIS Template

This template contains the following packages:

```
arcgis-core
arcgis-map-components
calcite-components
vue
pinia
```

To install dependencies and start the development server, run:

```sh
npm install
npm run dev
```

### Copy the assets

Static assets must be copied over to the public folder manually. A `copy` script has been created to make this process easier:

```sh
npm run copy
```

This will copy the assets required by the components to your project's `public/assets` directory.

## Recommended IDE setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).
