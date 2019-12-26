# Welcome to wiki.RPGMate.club sourse

## Credits

This is a non-for-profit project. everyone is invited to collaborate.

## Features

- [Gatsby MDX](https://github.com/ChristopherBiscardi/gatsby-mdx) for JSX in Markdown loading, parsing, and rendering of pages
- [Storybook](https://storybook.js.org/) for isolated component development
- [styled-components](https://www.styled-components.com/) for CSS-in-JS
- [ESLint](https://eslint.org/) with [Airbnb's config](https://www.npmjs.com/package/eslint-config-airbnb)
- [Prettier](https://prettier.io/) integrated into ESLint
- [Typescript]() integrations and validation
- A few example components and pages with stories and simple site structure

## Development

[`Node.js`](https://nodejs.org/) v8.0.0 or above is required and using [`Yarn`](https://yarnpkg.com) is recommended.

```bash
# install dependencies
yarn

# ...or with npm
npm install

# serve with hot reload for development (localhost:8000)
yarn develop

# serve storybook with hot reload for development (localhost:9000)
yarn storybook

# lint project
yarn lint

# format project source
yarn format

# run tests
yarn test

# build for production
yarn build

# build static storybook (outputs to `public/docs` folder)
yarn storybook:build

# serve locally (after building)
yarn serve

# clean the local build
yarn clean
```

## License

This project is licensed under [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)
