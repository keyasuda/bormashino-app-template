# bormashino-app-template

template repository of apps with Bormaŝino / SPAs written in Ruby

## Demo

https://bormashino-app-template.vercel.app

## Prerequisites

You need:

- rbenv + ruby-build
- npm

## Quickstart

in the cloned dir

```bash
cat .ruby-version | rbenv install -
gem install foreman
bundle install
(cd src && bundle install)
npm install
./bin/dev
```

You can see the app at http://localhost:5000/.
App codes are basically in `src/`.

## Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fkeyasuda%2Fbormashino-app-template)

"Vercel for GitHub" works on this project.
See https://vercel.com/docs/concepts/git/vercel-for-github
