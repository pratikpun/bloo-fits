## BLOO - FITS

An full stack e-commerce project, allowing users to browse through items and _purchase_ them

Authentication is done using Firebase, which handles login, signup, account management.

#### TECH STACK

- Frontend : React.js, SCSS
- Backend : Firebase

#### Learnt

- react-router-dom:
  - nested routes, which can be found by navigating to the items in /shop.
  - Usage of Link, in _declarative_ ways. By specifying the target destination, without explaining the way to get there.
  #### Declarative
  ```
  <Link className="title" to={title}>
          {title.toUpperCase()}
  </Link>
  ```
- React context for state management:
  - Check if user is logged in or not.
  - Keep track of toggling state for displaying cart dropdown menu in different pages.
  - Keeping track of quantity of items when adding to cart.
- Firebase authentication

## Installation guides

After you clone your project down, in your terminal, type 'cd bloo-fits' to navigate into the project and remember to run either `yarn` or `npm install` to build all the dependencies in the project.

## Set your firebase config

Remember to replace the config variable in your firebase.utils.js with your own config object from the firebase dashboard! Navigate to the project settings gear icon > project settings and scroll down to the config code. Copy the object in the code and replace the variable in your cloned code.

<img width="1261" alt="Screen Shot 2022-03-11 at 8 51 22 PM" src="https://user-images.githubusercontent.com/10578605/157999158-10e921cc-9ee5-46f6-a0c5-1ae5686f54f3.png">

# bloo-fits
