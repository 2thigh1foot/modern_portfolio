# Portfolio Website following Traversy Media #

## Getting Started ##


You can modify this website in any way or shape. I used Sass to generate the CSS in these projects. To run Sass, you will want to get node.js so that you can use the Node Packet Manager (NPM).

## Setting up the Package Json ##


Once you get Node.js installed and ready, you'll want to get your package manager with these commands.<br />
In your terminal: <br />
run npm init <br />
package name: (name of your package)<br />
version: (1.0.0)<br />
description: Responsive portfolio website<br />
entry point: (index.js)<br />
test command:<br />
git repository:<br />
keywords:<br />
author: Your Name<br />
license: <br />

 --- 

After that, you want to run:<br />
npm i node-sass<br />

This will create a node_modules folder. It's quite large.<br />

Under scripts, you will want to look for the scripts section in the package.json file. You can change the name to anything ("I called it sass"), and input the following command.<br />

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

To run the script:<br />

npm run sass
