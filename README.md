# Full project configuration WebPack test

This project is a WebPack full configuration test project to config.

It consists of a full SPA setup hosted with some basic CI, so every time that files are pushed, or a pull request is made to the main branch, the site automatically updates.

Funcitonalities incluided:

- Babel and @babel/preset-env for mmodern JS transpiling.
- CSS, SASS, PostCSS with post-preset-env for CSS fallbacks for better cross-browser support.
- Browserslist config for customizing the browsers wanted to be supported for JS and CSS, all in one place.
- Outputing all CSS to a file with mini-css-extract-plugin and hot reloading. (to do: in the future inile css for ==critical css, using style-loader==).
- HTML templates with html-webpack-plugin-
- Cleaning the output folder every build with clean-webpack-plugin-
- React with the automativ importing functionality supported in React 17+ through Babel.
- React Fast Refresh in Webpack: The new hot module reloading tool supported by the React team.
- Outputting or bundling images with the new Webpack 5 Asset Module type.
- Quickly getting the app/site hosted on Vercel.

Steps taken:

1. git init locally
2. Create GitHub repo
3. init a project with

```
    npm ini -y
```

4. Install Babel
