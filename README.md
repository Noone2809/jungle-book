# The Jungle Cook

The Jungle Cook is a recipe-themed website project built with JavaScript, Sass, and Vite. Its home page introduces the site, and the navigation includes a login page and links for browsing and creating recipes.

## Website

https://in-info-web4.luddy.indianapolis.iu.edu/~ccucuiet/N315/jungle-book/#home


## Features

- Home page introducing The Jungle Cook
- Login and sign-up page layout
- Hash-based page navigation
- Sass stylesheets organized by page and layout area

## Run locally

You’ll need [Node.js](https://nodejs.org/) and npm installed.

1. Clone or download this project.
2. From the project folder, install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the local URL shown in your terminal.

## Build for production

Create a production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## Project structure

```text
index.html       Main HTML entry point
public/          Public assets, including icons
src/
  main.js        App entry point and navigation setup
  model/         Page loading logic
  pages/         Home and login page content
  sass/          Stylesheets
  assets/        Images, social icons, and fonts
```

## Tech stack

- JavaScript (ES modules)
- Sass
- Vite
