# custom-react-webpack-setup
My custom react project setup with Webpack

<strong>Three webpack config files:</strong><br/>
 -common config<br/>
 -development mode config<br/>
 -production mode config<br/>

-JSX babel loader<br/>
-SCSS/CSS/Styles loader<br/>
-HTML loader<br/>

-HtmlWebPackPlugin for creating .html by template and minifying created .html (/dist/index.html)<br/>
-MiniCssExtractPlugin for creating separate .css file in production mode<br/>
-OptimizeCssAssetsPlugin for minifying .css files<br/>
-TerserPlugin for minifying .js files<br/>
-CleanWebpackPlugin for clearing /dist folder on every production build<br/>

<strong>ToDo:</strong><br/>
  Image loaders<br/>
  Image Minifiers<br/>
  Url loaders (transforms img url to base64 - https://webpack.js.org/loaders/url-loader/)<br/>
  Font Loaders<br/>
  Loading data (.json, .csv...)<br/>
  Explore more about performance, caching, tree shaking...<br/>
