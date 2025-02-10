# API Routes Rate Limiting Example

This example uses `lru-cache` to implement a simple rate limiter for API routes ([Serverless Functions](https://vercel.com/docs/serverless-functions/introduction)).

**Demo: https://nextjs-rate-limit.vercel.app/**

```bash
curl http://localhost:3000/api/user -I
HTTP/1.1 200 OK
X-RateLimit-Limit: 10
X-RateLimit-Remaining: 9

curl http://localhost:3000/api/user -I
HTTP/1.1 429 Too Many Requests
X-RateLimit-Limit: 10
X-RateLimit-Remaining: 0
```

## Preview

Quickly preview this example directly in your browser with [StackBlitz](http://stackblitz.com/):

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/api-routes-rate-limit)

#### 🌏  Open in other Cloud IDES

Click any of the buttons below to start a new development environment to demo or contribute to the codebase without having to install anything on your machine:


[![Open in Glitch](https://img.shields.io/badge/Open%20in-Glitch-blue?logo=glitch)](https://glitch.com/edit/#!/import/github/vercel/next.js/tree/canary/examples/api-routes-rate-limit)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/vercel/next.js/tree/canary/examples/api-routes-rate-limit)
[![Edit in Codesandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/vercel/next.js/tree/canary/examples/api-routes-rate-limit)
[![Open in Repl.it](https://replit.com/badge/github/withastro/astro)](https://replit.com/github/vercel/next.js/tree/canary/examples/api-routes-rate-limit)
[![Open in Codeanywhere](https://codeanywhere.com/img/open-in-codeanywhere-btn.svg)](https://app.codeanywhere.com/#https://github.com/vercel/next.js/tree/canary/examples/api-routes-rate-limit)
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/vercel/next.js/tree/canary/examples/api-routes-rate-limit)

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/api-routes-rate-limit&project-name=api-routes-rate-limit&repository-name=api-routes-rate-limit)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example api-routes api-routes-rate-limit
# or
yarn create next-app --example api-routes api-routes-rate-limit
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
