# 3D-Portfolio
I am using vite+react+threejs and I will describe all the setup and key points in it.
1. npm create vite@latest ./ (To include all the repositories).
2. Pick React, Javascript, or any framework, be it vue.js or next js.
3. npm install
4. npm run dev and follow the localhost link you will see react and vite svg.
5. Delete the src, Create a new src film inside it create a main.js file inside it uses import 'ReactDOM' from react-router-dom, use ReactDOM.createRoot Change the package from react-dom/client.
6. Use snippets to help you I am using ES7+react/redux snippets, Then create an app. just use RAFCE to get the basic structure of the react application. npm install -D tailwindcss@3 postcss autoprefixer run this first in a seperate terminal. Then initialise it npx tailwindcss init -p Then configure the template path.
 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],  Add this in the tailwind.config.js content section. Try to run hello world in h1 and copy it from the tailwind CSS command set inside App.js
Create a new file called index.css and add the following snippet to it.
After copying the snippet rerun the file you will see changes in the browser now in the tailwind.config.js paste the following snippet
