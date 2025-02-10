# Example app with cxs

This example shows how to use a different styling solution than [styled-jsx](https://github.com/vercel/styled-jsx) that also supports universal styles. That means we can serve the required styles for the first render within the HTML and then load the rest in the client. In this case we are using [cxs](https://github.com/jxnblk/cxs/).

For this purpose we are extending the `<Document />` and injecting the server side rendered styles into the `<head>`.

## Preview

Quickly preview this example directly in your browser with [StackBlitz](http://stackblitz.com/):
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-cxs)

#### 🌏  Open in other Cloud IDES

Click any of the buttons below to start a new development environment to demo or contribute to the codebase without having to install anything on your machine:

[![Open in Glitch](https://img.shields.io/badge/Open%20in-Glitch-blue?logo=glitch)](https://glitch.com/edit/#!/import/github/vercel/next.js/tree/canary/examples/with-cxs)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/vercel/next.js/tree/canary/examples/with-cxs)
[![Edit in Codesandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/vercel/next.js/tree/canary/examples/with-cxs)
[![Open in Repl.it](https://replit.com/badge/github/withastro/astro)](https://replit.com/github/vercel/next.js/tree/canary/examples/with-cxs)
[![Open in Codeanywhere](https://codeanywhere.com/img/open-in-codeanywhere-btn.svg)](https://app.codeanywhere.com/#https://github.com/vercel/next.js/tree/canary/examples/with-cxs)
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/vercel/next.js/tree/canary/examples/with-cxs)


## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-cxs&project-name=with-cxs&repository-name=with-cxs)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-cxs with-cxs-app
# or
yarn create next-app --example with-cxs with-cxs-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
