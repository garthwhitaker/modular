## eslint-config-modular-app

An ESLint config, made for `create-modular-react-app`/`modular-scripts`. It's
simply
[`eslint-config-react-app`](https://www.npmjs.com/package/eslint-config-react-app)
with dependencies bundled in.

If you want to extend the ESLint configuration in a modular repo, create a file
named `.eslintrc.js` in your project's root folder with the following content:

    module.exports = {
      extends: "modular-app",
    }

That's it! Add your additional config to this file. Read more about
[extending sharable configuration packages here](https://eslint.org/docs/user-guide/configuring/configuration-files#using-a-shareable-configuration-package).
