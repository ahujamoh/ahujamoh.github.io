# ahujamoh.github.io

[![Netlify Status](https://api.netlify.com/api/v1/badges/037c5f36-b001-4b6e-a339-a4da2c04ee4b/deploy-status)](https://app.netlify.com/sites/ahujamoh/deploys)

A personal website of Mohit Ahuja( forked from [Richard's Nguyen](https://github.com/richardnguyen99/richardnguyen99) and this is its source code. This website is written in [Gatsby](https://www.gatsbyjs.org/), [React](https://reactjs.org/), [Typescript](https://www.typescriptlang.org/) and [Styled-components](https://www.styled-components.com/).

_Notes: Richard had open-sourced his website to share the structure, the configurations, and how he organizes all of those things. He hopes that it could help some people are having troubles in writing their very first sites (in Gatsby and stuff). However, the website is highly customized to match his desires, so it could be a little frustrating to modify the codes to your version. But he will be happy if you do so. Not only will you improve your coding skills but also respect him and what he's doing._

## Usage

1. Clone the repository

   ```bash
     git clone https://github.com/richardnguyen99/richardnguyen99.github.io

     # or
     # git clone  https://github.com/ahujamoh/ahujamoh.github.io
   ```

2. Know the structure

   Before getting your hands on, Richard would like to tell you more about how he organizes stuff. Richard only explains his stuff. Others can be seen at [gatsby-starter-default](https://github.com/gatsbyjs/gatsby-starter-default)

   - In the root directory:

     - **_.editorconfig_**: a set of consistent formatting styles for the whole project.

     - **_.eslintrc.js_**: a tool to check all Javascript errors and fix them.

     - **_.eslintignore_**: a list of files and folders that ESLint will ignore.

     - **_.huskyrc_**: a pre-commit hook script to prevent bad commits.

     - **_.lintstagedrc_**: a linter linting files on staged.

     - **_.stylelintrc_**: a tool like ESLint but for CSS.

     - **_tsconfig.json_**: a set of rules and configurations for Typescript compiler.

   - In the source directory:

     - **_@types/_**: customized type definitions.

     - **_components/_**: reusable components.

     - **\_contexts/\_\_**: React context (theme, languagues, etc.).

     - **_hooks/_**: customized React hooks.

     - \***\*images/\*\***: images for displaying content of the website.

     - \***\*pages/\*\***: contents will be displayed on the website

     - \***\*utils/\*\***: sets of tools to help in development process.

     - \***\*types.ts\*\***: list of types and interfaces.

3. Play around:

   Install dependencies:
   ```bash
     yarn install
   ```

   Setup 
   ```bash
      yarn install dotenv
      # setup .env in root folder for GATSBY_GITHUB_KEY
   ```

   Development:

   ```bash
     yarn develop
   ```

   Production:

   ```bash
     yarn build
   ```

4. Deploy:

Currently, this website is being deployed to [Netlify](https://www.netlify.com/) (free for static website), so the script `yarn deploy` won't work properly (You can try if you still want to).

## Liability declartion

This is an open source code and you are responsible for securing your website, the authors are not responsible for your usage of the source code.

## Authors

- [Richard Nguyen](https://github.com/richardnguyen99): *ORIGINAL* author
- [Mohit Ahuja](https://github.com/ahujamoh): small contributor

## Contribution & Contact

If you found any problems or issues, please feel free to open a pull request to fix that. Mohit would be happy if there were someone improving the website with him. If a pull request is unnecessary, you contact him with:

- Github: <https://github.com/ahujamoh>
- Twitter: <https://twitter.com/ahujamoh>
