# express-template

A template for creating Node Express applications

> NOTE: If you are using this template, you can delete the contents in this file, but you'll also need to
>
> - Modified the `LICENSE` to replace my name with your own.
> - Edit `package.json` to replace my name or email with your own and modify a few other fields.

This template was created to create a set of standard instructions for setting up a minimalist ESM Node Express application.

Currently, this template is configured to work with VSCode, but I would like to make it also usable with NeoVim to work in minimalist environments.  It is literally possible to set NeoVim up to behave like an IDE similar to VSCode or JetBrains, but us NeoVim geeks need to get together sometime to create a configuration file to make it happen.

This template will include

- **Settings for using ECMAScript Modules** (ESM), because you should stop using Common.js
- [**Express.js**](https://expressjs.com/) for Middleware
- [**Dotenv**](https://www.npmjs.com/package/dotenv) for protected environmental variable storage
- [**ESLint**](https://eslint.org/) for Linting (using the Google style guide)
- [**Prettier**](https://prettier.io/) for Code formatting
- [**Jest**](https://jestjs.io/) for Test Driven Development

There will likely be a couple of other templates based on this template that include using databases like MySQL and MongoDB, but this is likely the base template for those.

To use this template

1. Got to [https://github.com/jrcharney/express-template](https://github.com/jrcharney/express-template)
2. Click on the green "Use This Template" button/menu.
3. Select "Create a new repository" to create a new repository with this template.
4. Fill out the usual Github creation fields (Owner, Repo Name, Description, etc.)
5. Click "Create repository from template"
6. `git clone https://github.com/YourUserName/YourRepoName`
7. Edit those things I mentioned to replace my name with yours in `LICENSE` and `package.json` as well as any other necessary fields in `package.json` that should be modified.
8. Probably delete `package-lock.json`. (Use a fresh one, which we will generate in just a bit.)
9. `npm install` to download the packages you need into `node_modules`.
10. `npm init @eslint/config` to modify any ESLint settings
11. `npx prettier --write .` to format all the files with Prettier. (This template doesn't use Continuous Integration (CI), so we won't need to run `npx prettier --check .` or set up any hooks.)
12. `npx jest --init` to make sure your Jest configuration (`jest.config.mjs`) is set the way you want it.

> TODO: Should I use `jest --watch`?
