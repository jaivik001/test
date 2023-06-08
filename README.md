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

### CSS and Styles

In your project's CSS file (e.g., `styles.scss`), import the provided styles:

```scss
@import '~@turinghealth/webapp-design-bs5-dev/scss/style.scss';
```

### JavaScript

In your project's JavaScript file (e.g., `app.js`), import Bootstrap:

```javascript
import 'bootstrap/dist/js/bootstrap.bundle.min.js';
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
// Import the CSS file for the web app design
import '@turinghealth/webapp-design-bs5-dev/scss/style.scss';

// Import Bootstrap JavaScript
import 'bootstrap/dist/js/bootstrap.bundle.min.js';

// Use the pre-designed components and styles in your web application
// Example:
import { Button, Card } from '@turinghealth/webapp-design-bs5-dev';

// Render a button
const myButton = <Button variant="primary">Click me</Button>;

// Render a card
const myCard = (
  <Card>
    <Card.Header>Card Title</Card.Header>
    <Card.Body>
      <p>Card content goes here...</p>
    </Card.Body>
  </Card>
);
```

For more detailed usage examples and API documentation, please refer to the [Documentation](https://link-to-documentation).

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please submit a bug report or pull request.

Please review our [Contributing Guidelines](https://link-to-contributing-guidelines) for more details.

## License

This package is licensed under the [MIT License](https://opensource.org/licenses/MIT).
```

Make sure to replace the placeholders (`https://link-to-documentation`, `https://link-to-contributing-guidelines`) with the appropriate URLs for your package's documentation and contributing guidelines. Adjust any other content or sections as needed based on
