# react-storybook-decorator-github-corner

> Storybook decorator to render the Github Corner. 

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/Personare/react-storybook-decorator-github-corner/master/screenshot.png" alt="Screenshot" />
</p>

## Installation 

```bash
npm install @personare/react-storybook-decorator-github-corner --save-dev
```

## Using globally mode

Inside `.storybook/config.js`

```js
import { configure, addDecorator } from '@kadira/storybook';
import GithubCorner from '@personare/react-storybook-decorator-github-corner';

addDecorator(GithubCorner);

function loadStories() {
  require('../src/Button.story');
}

configure(loadStories, module);
```

*Note: The link of repository is based on pages that are hosted on Github Pages (***.github.io)*

## Examples

* [react-freshdesk-widget](https://personare.github.io/react-freshdesk-widget)
* [lyef-pokemon](https://lyef.github.io/lyef-pokemon/)
* [lyef-switch-button](https://lyef.github.io/lyef-switch-button/)
* [lyef-flags](https://lyef.github.io/lyef-flags/)

## Related

* [react-github-corner](https://github.com/skratchdot/react-github-corner) - component used by this decorator

## License

[MIT © Personare](./LICENSE)
