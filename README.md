# Project Catwalk by Marvelous Maitake

Catwalk is a Front End Capstone Project using NodeJS and React. This is a single page e-commerce application with a backend retrieving product data from an external API.
    - Node v14.17.2
    - React 17.0.2

## Components and Features
### Product Overview
![product overall](https://user-images.githubusercontent.com/72169023/159382954-3b5de348-4ef4-4a2f-b756-7abbd59a987c.gif)
- Display with dark theme or light theme 
- Display an image carousel with a zoom-in and expand feature. Contains various photos of the currently selected style of a product.
- Users are able to select a product with multiple styles, and the images in the coursel will dynamically updates.
- Product detail information section emphasize a product's name, category, price and available styles. This section's information will update when choose different products.

### Related Products
- Displays other product options related to the currently selected product.
- Provide various styles of each current seleted product without reloading page.
- A modal comparing details of the current product and the related product will be displayed when click the start on related product

### Questions and Answers
- Questions and Answers section displays other users' questions and answers regaring current selected product. 
- Users are able to target accurate questions by typing key words in search bar
- A modal for adding quetion displays when users click "add a question+" button
- Clicking "add anwer" button will display a modal of forms for adding new answers

### Rating and Reviews
- Display review of current selected product, and reviews can be sorted by relevance, helpfulness, and time
- Overall rating data is shown on the left, which consist of multiple rating aspects of current product
- Users are able to add their own review by clicking "add review+" button

## Setup
### Installation
Use the package manager [npm](https://www.npmjs.com/) to install dependencies.

```bash
npm install
```
### Usage
Use webpack to bundle files
```bash
npm run transpile
```
### initializes server
```bash
npm run server
```
### enter api key
copy config.example.js in server folder
rename it to config.js
uncomment code and replace 'GITHUBKEY' with your personal access token
### open client
open http://localhost:3000/ in browser

## Technologies
- React.js
- Node.js
- Nodemon
- Express.js
- Axios
- React styled-component
- Webpack
- Babel
- React-testing library
- Jest

