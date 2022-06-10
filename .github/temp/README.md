# [{title}][website] &middot; [![GitHub license]](./LICENSE) ![Test Action] ![Deploy Action]

{description}.

<!-- Table of Contents -->

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

The first step will be to clone the repo

```shell
git clone https://github.com/{repo}.git
```

### For development

The requirements are:

- [Node.js]
- [Yarn]

1. Install the dependencies
   ```shell
   yarn
   ```

## Usage

In order to start the website, you will need to run the NPM scripts that are available in the package.json file, using `yarn` or `npm run`. Here are the most important ones:

- **start**: Starts the development server in http://localhost:4200/. The app will automatically reload if you change any of the source files.
- **build**: Builds the static website. The build artifacts will be stored in the `dist` directory.
- **test**: Runs the unit tests using [Karma].
- **lint**: Lints the project using [ESLint] and [Prettier].

## License

Distributed under the MIT License. See [LICENSE](./LICENSE) for more information.

<!-- Packages links -->

[node.js]: https://nodejs.org/en/
[yarn]: https://yarnpkg.com/
[karma]: https://karma-runner.github.io
[eslint]: https://eslint.org
[prettier]: https://prettier.io

<!-- Repository links -->

[website]: https://{author}.github.io/{name}/

<!-- Shields.io links -->

[github license]: https://img.shields.io/badge/license-MIT-blue.svg
[test action]: https://github.com/{repo}/actions/workflows/test.yaml/badge.svg
[deploy action]: https://github.com/{repo}/actions/workflows/deploy.yaml/badge.svg
