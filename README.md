# Amigos Gatsby/TaiwindCSS Starter Repo

### **Do not commit to this repo unless updating the base template! Clone it, start a new repo, then set the upstream origin there**

### Main Available Scripts
- `gatsby develop` Runs dev server normally
- `yarn run develop` Runs dev server, but with the option of using Prisma's graphQL Playground
- `gatsby build` Build public directory for deplooyment

### Contentful headless CMS
The Gatsby package for using the Contenful headless CMS as a data source is already included. The file `gatsby-config.js` contains the code to access the API (with the proper credentials and a .ENV file); all that's necessary is to uncomment the relevant portions. For a full example, [see this file](https://github.com/Only-Amigos/stick-it-good/blob/master/gatsby-config.js)

To set up dynamic routing based on a repeatable type in the Contentful repo, [check out this file](https://github.com/Only-Amigos/stick-it-good/blob/master/gatsby-node.js).

### SCSS Support
To use SCSS, create a /styles folder, add a `main.scss` file, then import it in (likely) the `layout.js` file. Use `main.scss` to `@include` other SCSS files.

##### Find [Tailwind docs here](https://tailwindcss.com/docs/installation).

### 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-default)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/gatsbyjs/gatsby-starter-default)
