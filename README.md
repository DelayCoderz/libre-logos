# Libre Logos

Libre Logos is a library of free logos.
The logos are intended for open source projects and NGOs.

Designers are invited to contribute.

**The logo designs are meant to be unique, and there's no intention to steal creative property. If you find a logo that looks too similar to an existing brand, let me know so that it can be removed**

## Screenshots

![](screenshot.png)

## Website

This website is built with Gatsby, a site generator based on React. The `logo` route is dynamically generated using the Gatsby createPage API. To stop the client side router serving the 404 page on `/logo` requests, there is a [conditional check](./src/pages/404.js).

In the future, this website may be rewritten and architected to use of Gatsby's new [File System Router API](https://www.gatsbyjs.com/docs/reference/routing/creating-routes/#using-the-file-system-route-api).

To build a local version:

1. Clone the repository

    ``` 
    git clone https://github.com/PROTechThor/libre-logos.git
    ```
2. Enter the project folder and install node modules

    ``` 
    cd libre-logos
    npm install 
    ```
3. Run
    - `npm start` to develop
    - `npm run build` to build
    - `npm run serve` to serve built site
