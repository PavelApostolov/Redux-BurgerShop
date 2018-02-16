[React-BurgerShop](https://github.com/PavelApostolov/ReactJS-BurgerShop) app refactored with Redux for ingredients and orders state. It lets you design a tasty burger with ingredients and their quantity of your choice. 

# How does it work

After building your burger (you can see the burger designed with CSS) a modal with the order summary pops. After confirmation you are redirected to a contacts page where you fill a form for delivery and finish your order. It is stored in Firebase database.

Added features after refactoring with Redux: authentication(register, login, logout), guarding routes, asynchronous requests and lazy loading, unit tests. 
Used: Firebase, ReactRouter 4, Axios, Redux-Thunk 

# How to use the downloaded files

1) Run "npm install" in the extracted folder
2) Run "npm start" to view the project

The application is deployed on https://react-burger-shop.firebaseapp.com/

### You have to authenticate to gain access to the full functionality of the application:
1) Click Authenticate 
2) Sign up with email (it should contain @ even if it does not exist (e.g. testmail@test.com)) and password (with at least 6 characters)
3) Sign in
4) Build your burger and confirm your order
5) Fill in the fields for the delivery form and finish the order
6) After making an order you can see it at the "Orders" page
