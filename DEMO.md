## Create a static site

1. Create the file `site/index.html`. Use the snippet `html-me-bro` to generate the content.

1. Push the changes.

1. Link Repository to netlify. Set the **Publish directory** to `site`

1. Navigate to `{siteUrl}` to demonstrate that the site is running.

---

## File configuration

1. Create the file `netlify.toml`. Use the snippet `config-me-bro` to generate the content.

---

## Create a serverless function

1. Create the file `funcs/hello.js`. Use the snippet `greet-me-bro`.

1. Update the file `netlify.toml`. Use the snippet `config-funcs-bro`.

1. Push the changes.

1. Navigate to `{siteUrl}/.netlify/functions/hello` to demonstrate that the hello function is running.

---

## Development Tools

1. Create the file `package.json`. Use the snippet `package-me-bro`.

1. Run the following command: `npm i`

1. Run the following command: `npm run start`.

## Use the serverless function in the static site

1. In `site/index.html`, replace the content of the `body` tag. Use the snippet `wire-it-up-bro`.

---
