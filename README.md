# @sigveh/css

A simple CSS Reset and base styles, for a clean start to every project.  
Inspired by [@acab/reset.css](https://github.com/mayank99/reset.css)

## Usage

Install the package via `npm`.

```sh
npm install @sigveh/css
```

You can then import the stylesheet wherever.

```css
/* CSS */
@import '@sigveh/css';
```

```js
/* JS */
import '@sigveh/css'
```

If you're not using a package manager, you can simply import from a CDN.

```html
<link rel="stylesheet" href="https://unpkg.com/@sigveh/css" />
```

## Customization

There are certain customization options when you are using the base styles. Make sure to define the CSS variables in `:root` to correctly override the default values.

```css
:root {
  /* define variables here */
  --border-radius: 6px;
}
```

These are the available CSS variables:

| Name            | Description                                   | Default value |
| --------------- | --------------------------------------------- | ------------- |
| --border-radius | Other radii are calculated from this          | `4px`         |
| --border-color  | Used for form elements, tables and separators | `#808080`     |

## License

This package is licensed under the [MIT license](./LICENSE).
