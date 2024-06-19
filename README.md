Boilerplate taken from https://github.com/ixartz/Next-js-Blog-Boilerplate with edits to fit our specific business needs.
TO DO:
1. Create an 'About'
2. Create a logo/icon if you want: https://favicon.io/favicon-converter/
3. Buy a domain

   
Adding Posts:
1. Create a Markdown file (.md)
   ![339912894-fe765923-328b-4e06-bd70-2f033b12c1d2](https://github.com/cncordance/AGsPersonalBlog/assets/168015665/71824ed2-01ed-410f-9326-fc544fbdd622)

2. PLEASE ADD TAGS: AT THE BOTTOM OF EACH POST, I WILL EVENTUALLY FIGURE OUT HOW TO DO CATEGORIES
3. Add the file to _posts (the first subfolder in the project) following the naming convention 'year-month-date-my-first-post.md'
4. Run a test in dev.
5. Run a test in prod.
6. Push the change to the Github Repo
7. Publish the new version of the blog on Firebase
Elements of the code: This is a semi-static webpage made with the listed frameworks for lightweight, fast, and simple pages.

Skeleton: App is instanciated in .../src/pages/_app.ts. This is also where we import the app styling css components. 

Pagination happens in .../src/pages/[page].tsx AND .../src/pages/pagination/... 

There is no index.html, only a index.tsx Markdown is taken from the Content pages and transformed to HTML. 

Full Layout is configured in .../src/templates/Main.tsx (Nav is globally declared in ...nagivation/Navbar.tsx)

Getters
* GetPosts: ../src/utils/Content.ts (ordered date desc)

Static
* About is a static page that can be found .../src/pages/about.tsx

About the Frameworks used: 

Next.js:
Next.js is a React framework for building server-side rendered (SSR) or statically generated (SSG) web applications. It is used to structure and organize your React application, handle routing, and optimize performance. Next.js uses React components, which are primarily written in JSX (a syntax extension for JavaScript that looks similar to HTML but is actually JavaScript). TypeScript:

TypeScript:
TypeScript is a superset of JavaScript that adds static typing and other features to JavaScript. It helps catch errors early during development and improves the maintainability of large-scale JavaScript applications. TypeScript is used alongside JavaScript to write logic and functionality in web applications. ESLint:

ESLint: 
ESLint is a static code analysis tool for identifying problematic patterns or code that doesn't adhere to coding standards. It helps ensure code quality and consistency across a codebase. ESLint primarily checks JavaScript and TypeScript code, not HTML. Prettier:

Prettier:
Prettier is a code formatter that helps enforce a consistent code style across your project. It can format code automatically based on predefined rules or configurations. Like ESLint, Prettier focuses on formatting JavaScript and TypeScript code, not HTML. PostCSS:

PostCSS:
PostCSS is a tool for transforming CSS with JavaScript plugins. It allows you to use future CSS syntax today, such as variables, nesting, and mixins, using plugins. PostCSS is used to process CSS stylesheets, which are referenced in HTML documents. Tailwind CSS:

Tailwind:
Tailwind CSS is a utility-first CSS framework for quickly building custom designs. It provides a set of utility classes that you can use directly in your HTML or JSX/TSX components to style elements. While Tailwind CSS is primarily used to style components, it does not replace HTML but rather enhances how you write and manage CSS styles within HTML or JSX/TSX files.
