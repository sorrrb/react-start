# react-start

- Notes taken from The Odin Project React curriculum
---
## Introduction
#### JavaScript Libraries
- *generally speaking* - a collection of pre-written code that is designed to make development easier.
- Reusing/reimplementing this code in our codebases allows us to achieve complex tasks.
- It's important not to confuse a library with a framework, though the terms are often used interchangeably.
#### React
- React as a framework provides powerful primitives (built-in functions and modules) that allow us to build user interfaces of varying complexities.
- Frameworks have a tendency to make code easily scalable, more readable and modestly speaking, intensely more efficient.
- Some highlighted utilities of React:
  1. Components are reusable
  2. It's well-supported due to poularity and large community
  3. It's not opinionated - you aren't forced to follow any specific design patterns, project organizational structure or logic - it is up to the developer.
  4. There is a smaller learning curve moving from HTML/CSS/JS to React than moving with no background into the former.
---
## Setting up a React Environment
- There are various ways to start using React in a project.
- Several popular toolchains (a set of tools that is used to perform a complex task or create a software project - generally speaking, a set of tools used for building/developing an application)
  1. Vite's React Config
  2. Gatsby
  3. NextJS
- If you want to initiate a React project on your own, at a minimum, you would require...
  - a system for package management (NPM, Yarn),
  - a system for module bundling (Webpack, Parcel),
  - a system for compilation (Babel),
  - and the codebase for React itself.
- Initializing a React project from the command line is easy using Vite.
- Vite builds frontend tools for developers and leverages the latest technologies under the hood to provide a great developer experience.
- Vite also caters to the React ecosystem.
#### CLI Vite Process
- **NOTE:** Ensure you are using the LTS version of Node to prevent potential errors.
- Enter `npm create vite@latest PROJECT-NAME -- --template react`
- You may see:
`Need to install the following packages:`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`create-vite@5.X.X`
`OK to proceed? (y)`
- You enter 'y' then press **enter**
- After execution, you then navigate into the application directory that was created and run:
  1. `npm install`
  2. `npm run dev`

#### Application Folder
- Inside the new project directory, you will see several folders, as well as the files:
  1. `package.json`
  2. `package-lock.json`
  3. `.gitignore`
  4. `README.md`
- The `public` folder houses all the static assets related to your app (images, icons, information files for the browser, etc.)
- The `src` folder houses all the code that runs your app
  - Within the `src` folder, the `main.jsx` file acts as the entry point for the application