# 3D-Portfolio
I am using vite+react+threejs and I will describe all the setup and key points in it
1. npm create vite@latest ./ (To include all the repository).
2. Pick React,Javascript or any framework be it vue.js and next js,either of your choice.
3. npm install
4. npm run dev and follow localhost link you will be seeing react and vite svg.
5. Delete the src ,Create a new src filem inside it create a main.jsx file inside it use import 'ReactDOM' from react-router-dom, use ReactDOM.createRoot Change the package from react-dom/client.
6. Use snippets to help you I am using ES7+react/redux snippets,Then create app.jsx use RAFCE to get the basic structure of react application. npm install -D tailwindcss@3 postcss autoprefixer run this first in a seperate terminal. Then initialise it npx tailwindcss init -p Then configure the template path.
 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],  Add this in the tailwind.config.js content section. Try to run hello world in h1 copy it from the tailwind css command set inside App.jsx
Create a new file called index.css and add the following snippet in it.
