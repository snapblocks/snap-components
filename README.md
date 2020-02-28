# snap-components

Snapblocks technology-agnostic component library and styleguide. This component library is **100% made in CSS** and can be used by any JavaScript framework your team uses.

### Style Guide

Run the built-in style guide:
```
npm run styleguide
```

Generate shareable style guide code:
```
npm run build-styleguide
```

### Build

The single minified production ready CSS file is located under `/packages/snap-components/dist`.


### Custom builds

All components for the systems can be found under under the **'packages'**.

If you don't need all components you can open the `/packages/snap-components/snap-components.css` and remove the unnecessary components. To build the custom list of components run the following command:
```
npm run build
```
