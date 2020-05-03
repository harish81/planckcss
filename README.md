# planckcss
A minimal css framework based on [milligram](https://github.com/milligram/milligram) and [flexbox grid2](https://github.com/evgenyrodionov/flexboxgrid2).

Planckcss made using only css. All components are made of only using just css. There is no javascript at all.

## How to use?
```html
<link rel="stylesheet" href="dist/planckcss.css">
<link rel="stylesheet" href="dist/extension_form.css">
<link rel="stylesheet" href="dist/extension_spacing.css">
<link rel="stylesheet" href="dist/extension_colors.css">
<link rel="stylesheet" href="dist/extension_toggle.css">
<link rel="stylesheet" href="dist/extension_display.css">
```
OR Import
```html
<link rel="stylesheet" href="dist/planckcss.bundle.css">
```


## How to contribute?
Planckcss is made of `scss`. We use [laravel-mix](https://github.com/JeffreyWay/laravel-mix) to 
bundle our css. 

1. Clone repo.
2. `npm install`
3. Make changes to scss files in `src` directory.
4. Add Section to `docs/index.html`
5. Compile to css using `npm run dev`
6. Generate production minified css `npm run prod` 

## Inspiration

- [Milligram](https://milligram.io/) - A minimalist CSS framework.
- [flexboxgrid2](https://github.com/evgenyrodionov/flexboxgrid2) - Bootstrap like grid based on css flexbox,
An original author [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid). 
- [Bootstrap](https://getbootstrap.com/)
