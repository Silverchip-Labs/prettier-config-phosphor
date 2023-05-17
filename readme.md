# Prettier Config Phosphor

Prettier Config Phosphor is a shared configuration package for Prettier, the opinionated code formatter. It provides a consistent code formatting style across your JavaScript projects, ensuring that your codebase is clean and easy to read.

## Installation

To start using Prettier Config Phosphor, follow these simple steps:

1. Install the package as a development dependency in your project:

```bash
npm install --save-dev prettier-config-phosphor
```

2. Create a .prettierrc file in the root of your project or update your existing .prettierrc file.

3. Extend the prettier-config-phosphor configuration in your .prettierrc file:

```json

"prettier-config-phosphor"
```

4. Customize the configuration to match your project's requirements by adding or modifying rules.

## Usage

Prettier Config Phosphor provides a predefined set of formatting rules that align with the best practices for JavaScript development. However, you can customize the configuration to suit your needs. Simply update the .prettierrc file as follows:

```json
{
  "tabWidth": 2,
  "semi": false,
  "singleQuote": true,
  // Add or modify other rules
}
```
