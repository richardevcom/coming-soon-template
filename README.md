# Coming soon template

Boilerplate for HTML coming soon webpage. Bare-bones HTML starter template with Tailwind CSS, PostCSS, Gulp, Browsersync &amp; Imagemin.<br/>
The main purpose of this boilerplate is to simplify build of quick coming soon/maintenance one-pagers.

![screenshot](https://raw.githubusercontent.com/richardevcom/unknown-coming-soon/main/screenshot.png)

## How to use this Boilerplate

1. Clone the repository:

   ```bash
   git clone git@github.com:salttechno/tailwindcss-boilerplate.git <YOUR_PROJECT_NAME>

   cd <YOUR_PROJECT_NAME>
   ```

   Or else simply download boilerplate's zip file from [this link](https://github.com/salttechno/tailwindcss-boilerplate).

2. Install the dependencies:

   ```bash
   # if you are using npm
   npm install

   # OR if you are using Yarn
   yarn
   ```

3. Start the development server:

   ```bash
   # if you are using npm
   npm run dev

   # OR if you are using Yarn
   yarn run dev
   ```

   Now you should be able to see the project running at [localhost:3000](http://localhost:3000).

4. Open `./index.html` in your editor (VS Code recommended) and start editing!

## Optimizing for production

Tailwind CSS output needs to be optimized for the production use. The development version for the CSS file is almost 4MB which is not good for production websites. [Read this for more details](https://tailwindcss.com/docs/optimizing-for-production). This boilerplate **helps you generate the production version** of your CSS file easily & quickly.

We have configured `purge` option for PostCSS & Tailwind CSS. To build optimized version of your custom CSS, simply run:

```bash
# if you are using npm
npm run build

# OR if you are using Yarn
yarn run build
```

For optimizing your images, simply run:

```bash
# if you are using npm
npm run build-images

# OR if you are using Yarn
yarn run build-images
```
