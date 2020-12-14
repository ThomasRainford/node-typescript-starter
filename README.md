# node-typescript-starter

Super lightweight node-typescript starter with no added dependecies on top of the required TypeScript dependencies.

## Getting Started

Step 1: Clone the repo.

```bash
$ git clone https://github.com/ThomasRainford/node-typescript-starter.git
$ cd node-typescript-starter
```

Step 2. Install the dependencies using yarn.

```bash
$ yarn
```

Step 3. Watch the .ts files.

```bash
$ yarn watch
```

Step 4. Launch in dev mode.

```bash
$ yarn dev
```

The .ts files will be compiled to JavaScript and placed in the dist directory. Nodemon will then run the project using the index.js file.

**Note:** Step 3 and step 4 will need to be run in seperate terminals.

## Next Steps

-  After dev mode is launched you can start coding!
-  Checkout all scripts below.
-  Feel free to open issues.

## All Scripts

-  `yarn watch` -- Watches the .ts files and compiles them into javascript.
-  `yarn dev` -- Runs the project in developer mode. This means any changes made will automatically re-run the typescript code.
-  `yarn start` -- Runs the project using Node instead of nodemon.
-  `yarn lint` -- Runs ESLint
