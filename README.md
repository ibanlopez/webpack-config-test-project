# Full project configuration WebPack test

This project is a WebPack full configuration test project to config.

It consists of a full SPA setup hosted with some basic CI, so every time that files are pushed, or a pull request is made to the main branch, the site automatically updates.

Funcitonalities incluided:

-   Babel and _@babel/preset-env_

    For mmodern JS transpiling.

-   CSS, SASS, PostCSS with _post-preset-env_.

    For CSS fallbacks for better cross-browser support.

-   Browserslist config.

    For customizing the browsers wanted to be supported for JS and CSS, all in one place.

-   _mini-css-extract-plugin_ and hot reloading.

    For all CSS Outputing to a file. (to do: in the future inile css for **critical css**, using _style-loader_).

-   HTML templates.

    With _html-webpack-plugin_.

-   Cleaning the output folder.

    Every build with _clean-webpack-plugin_.

-   React.

    With the automatic importing functionality supported in React 17+ through Babel.

-   React Fast Refresh in Webpack.

    The new hot module reloading tool supported by the React team.

-   Outputting or bundling images.

    With the new Webpack 5 Asset Module type.

-   Quickly getting the app/site hosted on Vercel.

Steps taken:

1. git init locally
2. Create GitHub repo
3. init a project with

```
    npm ini -y
```

4. Install Babel
