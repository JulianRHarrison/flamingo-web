# Colors

```js script
import { html } from 'lit';
import '@divriots/dockit-core/css-showcases/dockit-css-showcases.define.js';
import './styles.css';
import '~/sd-output/variables.css';
```

## Core

### Primary colors

Primary colors of our brand.

```js story
export const primary = () => html`
  <dockit-css-showcases
    css-props-prefix="--flamingo-primary-900"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```
