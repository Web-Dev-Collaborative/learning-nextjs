# ReactMD and Next.js Example

This example sets up a simple [ReactMD](https://github.com/mlaursen/react-md) and Next.js
app featuring:

- [\_variables.scss](./styles/_variables.scss) to override the default
  `react-md` theme and feature toggles
- [app.scss](./styles/app.scss) global styles that conditionally apply the dark theme
  based on the user's OS preferences
- a custom [\_app.jsx](./pages/_app.jsx) that uses a persistent layout
- a reusable [Layout.jsx](./components/Layout/Layout.jsx) that:
  - updates all the icons to use `SVGIcon`s instead of `FontIcon`s
  - initializes the `Layout` component from `react-md` with navigation items

For more information about ReactMD's features, styling, components, and API, check out
the [main documentation](https://react-md.dev). You can also view the
[documentation site's source code](https://github.com/mlaursen/react-md/tree/master/packages/documentation)
for a more complex example of using ReactMD + Next.js or the [with-react-md-typescript](../with-react-md-typescript)
example for Typescript support.

## Preview

Quickly preview this example directly in your browser with [StackBlitz](http://stackblitz.com/):

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-react-md)

#### 🌏  Open in other Cloud IDES

Click any of the buttons below to start a new development environment to demo or contribute to the codebase without having to install anything on your machine:

[![Open in Glitch](https://img.shields.io/badge/Open%20in-Glitch-blue?logo=glitch)](https://glitch.com/edit/#!/import/github/vercel/next.js/tree/canary/examples/with-react-md)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/vercel/next.js/tree/canary/examples/with-react-md)
[![Edit in Codesandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/vercel/next.js/tree/canary/examples/with-react-md)
[![Open in Repl.it](https://replit.com/badge/github/withastro/astro)](https://replit.com/github/vercel/next.js/tree/canary/examples/with-react-md)
[![Open in Codeanywhere](https://codeanywhere.com/img/open-in-codeanywhere-btn.svg)](https://app.codeanywhere.com/#https://github.com/vercel/next.js/tree/canary/examples/with-react-md)
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/vercel/next.js/tree/canary/examples/with-react-md)


## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-react-md&project-name=with-react-md&repository-name=with-react-md)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-react-md with-react-md-app
# or
yarn create next-app --example with-react-md with-react-md-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
