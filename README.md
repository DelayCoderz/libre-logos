# Libre

This project contains a collection of free logos built with Inkscape.
The logos are intended for small open source projects and startups needing a temporary logo.
This website is built with Gatsby, a site generator based on React. The `logo` route is dynamically generated using the Gatsby createPage API. To stop the client side router serving the 404 page on `/logo` requests, there is a [conditional check](./src/pages/404.js).

In the future, this project will be rewritten and architected to take advantage of Gatsby's new [File System Router API](https://www.gatsbyjs.com/docs/reference/routing/creating-routes/#using-the-file-system-route-api).

## Screenshots

### Home page
![](screenshot.png)

### Individual item page
![](screenshot1.png)

## Building a local version

1. Clone the repository
    `git clone https://github.com/PROTechThor/libre-logos.git`
2. Enter the project folder and install node modules
    `cd libre-logos`
    `npm install`
3. Run
    - `npm start` to develop
    - `npm run build` to build
    - `npm run serve` to serve built site
