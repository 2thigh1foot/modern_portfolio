# Portfolio Website following Traversy Media

---

## Getting Started

You can modify this website in any way or shape. I used Sass to generate the CSS in these projects. To run Sass, you will wantt to get node.js so that you can use the Node Packet Manager (NPM).

## Setting up the Package Json

Once you get Node.js installed and ready, you'll want to get your package manager with these commands.
In your terminal:__
run npm init__
package name: (name of your package)__
version: (1.0.0)__
description: Responsive portfolio website__
entry point: (index.js)__
test command:__
git repository:__
keywords:__
author: Your Name__
license:__
 --- 

After that, you want to run npm i node-sass

This will create a node_modules folder. It's quite large

Under scripts, you will want to look for the npm scripts. You can change the name to anything ("I called it sass"), and input the following command.

```javascript

"name": "modern_portfolio2",
"version": "1.0.0",
"description": "Responsive Portfolio website",
"main": "index.js",
"scripts": {
"sass": "node-sass -w scss/ -o dist/css/ --recursive"
},
"author": "Your Name Here",
"license": "ISC",
"dependencies": {
"node-sass": "^4.11.0"
}

```

To run the script:

npm run sass
