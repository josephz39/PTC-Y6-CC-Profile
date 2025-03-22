# PTC Community Codes TASK 2: Set up your first React App

## Introduction
This guide will walk you through the process of setting up a simple React app as a beginner. You will learn how to install Node.js, create a React project, run the development server, and structure your project.

## What is React?
React.js is a front-end javascript library that aims to make building websites and apps easier for users. It’s a popular JavaScript library that lets developers design user interfaces in smaller, reusable pieces called "components." Think of components as building blocks that help you design your application while keeping everything organized and efficient. React is fast and dynamic because it updates only the parts of the page that change, instead of reloading the whole thing (see React DOM). Thus, react apps would be the next step up from your standard static HTML/CSS pages. Feel free to look at the React Documentation to lean more: https://react.dev/reference/react

## What is Node?
Node.js is a javascript library that handles all the behind-the-scenes work to make sure your application run smoothly. It's also a runtime environment for JavaScript, which means it lets you use JavaScript not just for the website itself (the frontend), but also for the server (the backend). With Node.js, developers can build fast, scalable apps like chat platforms, online games, or streaming services. For more info, take a look at the node.js documentation: https://nodejs.org/docs/latest/api/


**If you have any troubles setting up any of the steps, please reach out to our coding challenge coordinators over on our [community discord](https://discord.gg/cbSdUCHCKK)**

---

## Step 1: Install Node.js and npm
React requires Node.js and npm (Node Package Manager) to manage dependencies.

1. Download and install Node.js from [nodejs.org](https://nodejs.org/).
2. Verify installation by running the following commands in your terminal or command prompt:
   ```sh
   node -v
   npm -v
   ```
   This should output the installed versions of Node.js and npm.

---

## Step 2: Create a New React App
The easiest way to set up a new React project is by using **Create React App**.

1. Open a terminal or command prompt.
2. Run the following command to create a new React app:
   ```sh
   npx create-react-app my-app
   ```
   Replace `my-app` with your desired project name.
3. Navigate into your project folder:
   ```sh
   cd my-app
   ```
   - make sure to replace `cd my-app` with `cd [your project name]`
---

## Step 3: Start the Development Server
1. Inside the project folder, run:
   ```sh
   npm start
   ```
2. This will start the development server, and your React app will open in the browser at `http://localhost:3000/`.

---

## Step 4: Understand the Project Structure
After creating a React app, you will see the following file structure:
```
my-app/
├── node_modules/       # Installed dependencies
├── public/            # Static files (e.g., index.html)
├── src/               # Source code
│   ├── App.js         # Main app component
│   ├── index.js       # Entry point
├── .gitignore         # Files to be ignored in Git
├── package.json       # Project metadata and dependencies
└── README.md          # Project documentation
```

---

## Step 5: Modify Your First React Component
1. Open the `src/App.js` file in a code editor (such as VS Code).
2. Modify the default code inside `App.js`:
   ```jsx
   function App() {
     return (
       <div>
         <h1>Welcome to My First React App!</h1>
       </div>
     );
   }

   export default App;
   ```
3. Save the file, and your browser should automatically refresh with the updated content.

---

## Step 6: Install Additional Packages (Optional)
To add extra functionality, you can install packages using npm. For example, to install React Router:
```sh
npm install react-router-dom
```

---

## Step 7: Build the Project for Production
When you are ready to deploy your app, build it for production:
```sh
npm run build
```
This will create an optimized `build/` folder with the final production-ready files.

---

## Conclusion
Congratulations! You have successfully set up and run a simple React app. 

## Challenge
1. Try updating your current react app with some content
2. From here you can start to brainstorm what you want your application to loock like

For more information, check out
- [React.js Documentation](https://reactjs.org/docs/getting-started.html).
- [Node.js documentation](https://nodejs.org/docs/latest/api/).
