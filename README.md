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
bundle exec rake bormashino:download
(cd src && bundle install)
npm install
./bin/dev
```

You can see the app at http://localhost:5000/.
App codes are basically in `src/`.

## Deployment

"Vercel for GitHub" works on this project.
See https://vercel.com/docs/concepts/git/vercel-for-github
