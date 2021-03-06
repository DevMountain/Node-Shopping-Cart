<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# Node Shopping Cart

## Project Summary
In this project we will cover how to use sessions, middleware, and url parameters by creating a shopping cart. We will do this by making an `express` server that stores a user's shopping cart on their session and have endpoints that can `update`, `delete`, and `read` items from their shopping cart. We'll test these endpoints using postman. 

## Setup

Before getting started with this repository run `npm install` when in the root of the project. Also make sure that you are using Node version 7.5.0 or greator ( `node --version` ).

## Step 1

### Summary

In this step we will install and require `express-session` to use with our express application.

### Instructions

In the root of the project run `npm install --save express-session`. After installing it, open `index.js` and on line 2 require the express-session package.

### Solution

<details>

<summary> <code> index.js </code> </summary>

```js
const express = require('express');
const session = require('express-session');

// Express Application
const app = express();

// Server
app.listen(3000, () => console.log('Server initiated on port 3000'));
```

</details>

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250">
</p>
