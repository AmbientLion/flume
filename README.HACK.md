# HACK NOTES

Make sure to use `npm link` to bind the `react` and `react-dom` modules to your project's node_modules version.
Otherwise, importing this project may results in multiple copies of React that may conflict in your project.

Example:

````
npm link '../path/to/project/node_modules/react' react
npm link '../path/to/project/node_modules/react-dom' react-dom
````

You can then use either `npm link` or `npm install ../../path/to/this/module` to install this library as a referenced module.
