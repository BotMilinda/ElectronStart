check Node node -v
check npm npm -v

create electron npx create-electron-app --template=vite

run npm start

Adding react

Go to react site add to existing project

change renderer.js to jsx clear it
copy the index.js

**renderer.jsx

const App = () =>{
	return <h1>Hello from react</h1>
}

const container = document.getElementById("root");

**index.html

<div id="root"> </div>

vite react plugin

vite.rendere.config

import and add the plugin