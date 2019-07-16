# Cypress
## Installing Cypress
Installing Cypress via `npm`
* `npm init`
* `npm install cypress --save-dev`
## Opening Cypress
`./node_modules/.bin/cypress open`
## Adding npm scripts
* add Cypress commands to the scripts field in your `package.json` file.
```json
{
  "scripts": {
    "cypress:open": "cypress open"
  }
}
```
* run cypress: `npm run cypress:open`