# planckcss
A minimal css framework based on [milligram](https://github.com/milligram/milligram) and [flexbox grid2](https://github.com/evgenyrodionov/flexboxgrid2).
Planckcss is ~19 kb (Core) & ~35 kb (Bundle of all extensions).

Planckcss made using only css. All components are made of only using just css. There is no javascript at all.
Planckcss is extension based framework. You can use extension only if needed.

## How to use?([CDNs](https://www.jsdelivr.com/package/gh/harish81/planckcss))
```html
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/planckcss.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/extension_form.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/extension_spacing.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/extension_colors.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/extension_toggle.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/extension_display.css" rel="stylesheet">
```
OR Import
```html
<link href="https://cdn.jsdelivr.net/gh/harish81/planckcss@<version>/dist/planckcss.bundle.css" rel="stylesheet">
```

## Examples & Docs
https://harish81.github.io/planckcss/

## Features

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
