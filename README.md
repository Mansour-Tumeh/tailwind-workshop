# Tailwind CSS

![](https://miro.medium.com/v2/resize:fit:644/1*d7Xs5RnaqcQtKzbNrAOAYA.png)

Tailwind CSS is a popular utility-first CSS framework that provides a set of pre-defined CSS classes that can be used to style HTML elements in your web pages. It allows developers to rapidly create responsive and beautiful user interfaces without the need for writing custom CSS.

## installation
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