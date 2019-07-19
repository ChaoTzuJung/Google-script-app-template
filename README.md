# Google script app template

This is a sample app template showing the potential of Apps Script to create complete (server/client) web apps.

The front-end (client side) uses VueJS/React.

The back-end uses ES6 Javascript that gets compiled and bundled to Apps Script compatible code using webpack.

## Usage

Install clasp command line tool (if you don't have it already)

```bash
npm install @google/clasp -g
```

Then login to your Google account:

```bash
clasp login
```

Open the terminal and clone this project.

You have to create an Apps Script project to run this code.

```bash
clasp create --type standalone --title "YOUR_APP_NAME"
```

Now build the project and upload to your newly created Apps Script project

```bash
yarn install
yarn run deploy
```
