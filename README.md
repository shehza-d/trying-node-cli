# Publish Executable to NPM

1. Test your pkg before publishing to NPM

1. Make a NODE Project by initializing

   ```bash
   npm init
   ```

1. Add this in your package.json file

   ```json
     "bin": "index.js",
   ```

1. Add this on top of your file.

   ```bash
   #! /usr/bin/env node
   ```

1. Create account on [npmjs.com](https://www.npmjs.com/)
1. Login to npm on CLI (Terminal)

   ```bash
   npm login
   ```

1. Publish your work with

   ```bash
    npm publish --access=public
   ```

If a package name is not available use your username as prefix

"name": "@username/unavailable-pkg-name",

"name": "@shehza-d/calculator",
