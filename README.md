# composite.js website

This repository deploys the documentation and examples for
[`composite-js/composite.js`](https://github.com/composite-js/composite.js) to
[composite-js.github.io](https://composite-js.github.io/).

The site source remains in the main repository. The deployment workflow checks
out its `master` branch, builds `site/`, and publishes the generated Pages
artifact. It can be started manually and also runs daily to pick up source
changes without requiring a cross-repository access token.
