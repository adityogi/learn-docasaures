# Learning Docusaurus

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

- ⚡️ Docusaurus will help you ship a beautiful documentation site in no time.
- 💸 Building a custom tech stack is expensive. Instead, focus on your content and just write Markdown files.
- 💥 Ready for more? Use advanced features like versioning, i18n, search and theme customizations.
- 💅 Check the best Docusaurus sites for inspiration and read some testimonials.
- 🧐 Docusaurus is a static-site generator. It builds a single-page application with fast client-side navigation, leveraging the full power of React to make your site interactive. It provides out-of-the-box documentation features but can be used to create any kind of site (personal website, product, blog, marketing landing pages, etc).

## Fast Track ⏱️

- Understand Docusaurus in 5 minutes by playing!
- Create a new Docusaurus site and follow the very short embedded tutorial.

Install Node.js and create a new Docusaurus site using the Terminal (Here's how!!!):

```text
npx create-docusaurus@latest my-website classic
```

Start the site:

```text
cd my-website
npx docusaurus start
```

Open `http://localhost:3000` and follow the tutorial.

## Project structure

> Assuming you chose the classic template and named your site my-website, you will see the following files generated under a new directory my-website/:

```text
my-website
├── blog
│   ├── 2019-05-28-hola.md
│   ├── 2019-05-29-hello-world.md
│   └── 2020-05-30-welcome.md
├── docs
│   ├── doc1.md
│   ├── doc2.md
│   ├── doc3.md
│   └── mdx.md
├── src
│   ├── css
│   │   └── custom.css
│   └── pages
│       ├── styles.module.css
│       └── index.js
├── static
│   └── img
├── docusaurus.config.js
├── package.json
├── README.md
├── sidebars.js
└── yarn.lock
```

## Build

Docusaurus is a modern static website generator so we need to build the website into a directory of static contents and put it on a web server so that it can be viewed. To build the website:

**NPM**

```npm
npm run build
```

**YARN**

```yarn
yarn run build
```

and contents will be generated within the /build directory, which can be copied to any static file hosting service like GitHub pages, Vercel or Netlify. Check out the docs on deployment for more details.
