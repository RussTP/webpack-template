<!--WebPack project setup for webpack.dev and webpack.prod-->

1. make directory for new project
2. bash cd into project directory
3. npm init -y <!--initializes NPM with project-->
4. npm install --save-dev webpack webpack-cli <!--Installs webpack-->
5. npm install --save-dev html-webpack-plugin <!--Installs HTML webpack plugin-->
6. npm install --save-dev style-loader css-Loader <!--Installs CSS Loader-->
7. npm install --save-dev html-loader <!--Installs HTML Loader - To allow images to be loaded -->
8. npm i --save-dev webpack-favicons <!--install Favicon -->
<!-- once you have favicons in directory, open webpack.common.js and uncomment newFavIcons, make sure directory and file name is correct -->
9. npm install --save-dev webpack-dev-server <!--To use Webpack dev server-->

<!--To update GitHub repo-->

10. npm run build <!--npm run build to initiate script for the package.json to transpile the code-->
11. git add . or git add --a <!--add content-->
12. git commit -m "initial commit" <!--commit content-->
13. git push origin -main <!--push commit to origin-->
14. npm run deploy <!--npm run deploy when you are ready to deploy the project and create GitHub page for repo-->
