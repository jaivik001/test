Certainly! Here's an updated version of the README file for the `@turinghealth/webapp-design-bs5-dev` package with the added changes you provided:

```markdown
# @turinghealth/webapp-design-bs5-dev

[![Build Status](https://travis-ci.org/turinghealth/webapp-design-bs5-dev.svg?branch=main)](https://travis-ci.org/turinghealth/webapp-design-bs5-dev)
[![npm version](https://badge.fury.io/js/%40turinghealth%2Fwebapp-design-bs5-dev.svg)](https://badge.fury.io/js/%40turinghealth%2Fwebapp-design-bs5-dev)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A collection of pre-designed components and styles for building beautiful web applications using Bootstrap 5.

## Installation

To install `@turinghealth/webapp-design-bs5-dev`, use the following command:

```bash
npm install @turinghealth/webapp-design-bs5-dev
```

or

```bash
yarn add @turinghealth/webapp-design-bs5-dev
```

## Usage

Add the following configuration to your project's angular.json or webpack.config.js file:

### CSS and Styles

```scss
"styles": [
  "node_modules/@turinghealth/webapp-design-bs5-dev/scss/style.scss",
]
```

### JavaScript

```javascript
"scripts": [
  "node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"
]
```

### Assets

To use the package's image assets, configure your project's asset pipeline to include the package's images. Add the following configuration to your project's `angular.json` or `webpack.config.js` file:

```json
"assets": [
  "src/favicon.ico",
  {
    "glob": "**/*",
    "input": "./node_modules/@turinghealth/webapp-design-bs5-dev/assets/images",
    "output": "./custom_assets"
  }
]
```

Replace `"./custom_assets"` with the desired output directory for the images.

### Example Usage

Here's an example of how to use `@turinghealth/webapp-design-bs5-dev`:

```javascript
// Example:
   <img class="img-fluid th-avatar-38" src="./custom_assets/avatar-lg.png" alt="Avatar Image11">

// Render a button
    <div class="mb-4">
      <p class="mb-4">Use [btn th-btn-primary] classes</p>
      <a class="btn th-btn-primary" href="javascript:;" role="button">Text</a>
    </div>

// Render a checkbox
    <div id="checkbox">
      <h1 class="text-primary my-5">Checkbox</h1>
      <div class="mb-4">
          <div class="form-check th-form-check">
              <input class="form-check-input th-form-check-input" type="checkbox" value="" id="flexCheckDefault">
              <label class="form-check-label ms-3 th-form-check-label" for="flexCheckDefault">
                  Default checkbox
              </label>
          </div>
      </div>
    </div>

```

For more detailed usage examples and API documentation, please refer to the [Documentation](https://link-to-documentation).

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please submit a bug report or pull request.

Please review our [Contributing Guidelines](https://link-to-contributing-guidelines) for more details.

## License

This package is licensed under the [MIT License](https://opensource.org/licenses/MIT).
```

Make sure to replace the placeholders (`https://link-to-documentation`, `https://link-to-contributing-guidelines`) with the appropriate URLs for your package's documentation and contributing guidelines. Adjust any other content or sections as needed based on
