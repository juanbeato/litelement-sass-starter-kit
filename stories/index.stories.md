```js script
import { html } from '@open-wc/demoing-storybook';
import '../starter-component.js';

export default {
  title: 'StarterComponent',
  component: 'starter-component',
  options: { selectedPanel: "storybookjs/knobs/panel" },
};
```

# StarterComponent

A component for...

## Features:

- a
- b
- ...

## How to use

### Installation

```bash
yarn add starter-component
```

```js
import 'starter-component/starter-component.js';
```

```js preview-story
export const Simple = () => html`
  <starter-component></starter-component>
`;
```

## Variations

###### Custom Title

```js preview-story
export const CustomTitle = () => html`
  <starter-component title="Hello World"></starter-component>
`;
```
