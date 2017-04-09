# Learn Redux

This is my implementation following a [React + Redux tutorial](https://learnredux.com).

## Running

First `npm install` to grab all the necessary dependencies.

Then run `npm start` and open <localhost:7770> in your browser.

## Production Build

Run `npm build` to create a distro folder and a bundle.js file.

## To works with [sentry.io](https://sentry.io)

Put a file called `private.js` within `/client/data` with the following content:

```
export default {
  'sentry_key': '<your_sentry_key>',
  'sentry_app': '<your_sentry_app_id>'
}
```
