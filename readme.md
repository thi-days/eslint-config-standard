# My ESLint Shareable Config

## Introduction
This **Shareable Config** is being designed to provide developers (like me in my personal projects) a set of rules and configurations for ESLint based on my previous experiences leading the code to a clean format.  

**I'm still working on it, but I'm excited to share my progress with you.**

## Installation
To use the `eslint-config-standard` library, you'll need to install it as a `devDependency` in your project and extend it in your ESLint configuration file. Once you've done that, you can customize the rules and configurations as needed for your project.

To install the library, run the following command:  
```bash
npm install --save-dev @thi-days/eslint-config-standard
```

Then, in your `.eslintrc.js` file, add the following:
```js
module.exports = {
  extends: [
    // Your personal extends
    '@thi-days/eslint-config',
  ],
  // Other configuration options
};
```


## Features
As mentioned earlier, I'm still in the early stages of development, but here are a few features I'm currently working on:
- A base configuration with sensible defaults for common use cases
- Support for different coding styles and frameworks
- Integration with popular tools and editors

## Contributing
I welcome contributions from the community and would love to hear your feedback. If you encounter any issues or have ideas for new features, please feel free to open an issue or submit a pull request.

## Conclusion
Thanks for checking out. I'm still in the early stages of development, but I'm excited to continue building out the configurations and rules to help make code reading easier for everyone.  

**Stay tuned for updates!** 👨🏻‍💻
