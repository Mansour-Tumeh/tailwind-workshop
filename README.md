# Tailwind CSS

![](https://miro.medium.com/v2/resize:fit:644/1*d7Xs5RnaqcQtKzbNrAOAYA.png)

Tailwind CSS is a popular utility-first CSS framework that provides a set of pre-defined CSS classes that can be used to style HTML elements in your web pages. It allows developers to rapidly create responsive and beautiful user interfaces without the need for writing custom CSS.

## installation

The framwork provides four options to install Tailwind CSS into your frontend project:

    1. Tailwind CLI
    2. Using PostCSS
    3. Framework Guides
    4. Play CDN

### to install css tailwind with react : 

1. Create your project

```
npx create-react-app my-project
cd my-project
```
2. nstall Tailwind CSS

```
npm install -D tailwindcss
npx tailwindcss init
```

3. Configure your template paths

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
4. Add the Tailwind directives to your CSS `index.css`

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

5. start react app

```
 npm run start

 ```
 6. Start using Tailwind in your project
 ```js
import React from 'react';

function App() {
  return (
    <div className="bg-gray-200 p-4">
      <h1 className="text-3xl font-bold">Hello, World!</h1>
      <p className="text-gray-800">Welcome to my React app.</p>
    </div>
  );
}

export default App;

 ```

 ## - Tailwind CSS Playground

  [Tailwind play](https://play.tailwindcss.com/)
  is an advanced online playground for exploring Tailwind CSS, including support for things like customizing your tailwind.config.js file, extracting classes with @apply and code completion with an instant preview editor.

  Some of the most used Tailwind utility classes include the following:
  - [Flex](https://tailwindcss.com/docs/flex) (Flexbox)
  - [Grid](https://tailwindcss.com/docs/grid-template-columns) template columns (CSS Grid)
  - [Spacing](https://tailwindcss.com/docs/padding) (padding, margin, and space between)
  - [Typography](https://tailwindcss.com/docs/font-family) (font family, size, colour etc)
  --- 
  ## Tailwind UI Components for Web Development
  The makers of Tailwind CSS provide over 500+ free and paid beautifully crafted Tailwind CSS UI components, that are production ready for your next project.

  ![](https://tailwindui.com/img/og-default.png)

  The Tailwind UI components are categorized into three; Application UI, Product Marketing and Product E-commerce which are all available in plain HTML, ReactJS and VueJS versions.
  ### [Explore Tailwind components](https://tailwindui.com/components) 

  ### [Tailwind component live preview](https://tailwindui.com/components/preview) 

  ### [Headless UI](https://headlessui.com/)
  Headless UI is an unstyled component UI kit from the creators of Tailwind CSS. Its UI components can be used with both React and Vue.
### [Tailwind Starter Kit by Creative Kim](https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation)
Download the Tailwind Starter Kit from www.creative-tim.com to speed up your project development. The starter kit includes a dashboard page, landing page, login page, profile page, form layouts etc.

### [Free Tailwind Template](https://tailwindtemplates.co/)
free and paid Tailwind CSS landing pages and business websites from tailwindtemplates.co.

### [Tailwind Toolbox](https://www.tailwindtoolbox.com/)
 free Tailwind templates, components and building resources from the Tailwind Toolbox website.

 ### [ThemeForest](https://themeforest.net/search/tailwind)
 Purchase paid and free Tailwind CSS templates from the ThemeForest website.

 ### [Tailwind UI installation](https://tailwindui.com/documentation)