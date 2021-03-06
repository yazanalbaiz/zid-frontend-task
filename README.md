
<h1 style="line-height:100px">
    Basic E-Commerce Website Demo
</h1>

https://yazan-e-commerce-demo.herokuapp.com/

[![Build Status](https://travis-ci.org/yazanalbaiz/e-commerce-demo.svg?branch=master)](https://travis-ci.org/yazanalbaiz/e-commerce-demo)

---

## The Criteria

Implement a store home page that can mostly be altered dynamically through JSON payload
returned by the server. An example of the json is attached in data.json.
* You should be able to add products to cart, and products that are already in cart should be
marked.

* Unavailable products should be marked as unavailable.
  
* Datetimes should be in the user's timezone.

* No persistency is needed at all.

* You might want to make a product page or a product modal.

* Our focus here is functionality, not design, yet a good design is a plus.

* You can use whatever framework/libaries you want, but be careful.

---

## Implementation Comments

I have chosen to serve the `data.json` with a Node.js server proxy that will run on port 3001.

I have done so because I've found no native way in JavaScript to open a local file.

Upon running the command `npm run dev`, the npm script will run the proxy server and launch the react dev server.

---

## Requirements

- Node.js
- NPM
<!-- - A browser extension that allows CORS, such as:
  - [Allow-Control-Allow-Origin](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en)
  - [Allow CORS](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf?hl=en) -->

---

## Installation
<!-- 2.  Make sure you have installed a CORS extension. -->

1.  Clone or Download this repo.
2.  Open your terminal and navigate to the repo's directory on your machine.
3.  Run `npm install` to install all dependancy packages.
4.  Run `npm run dev` to launch the api and app.

---
