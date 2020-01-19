The code is based on Maximilian Schwarzmüller course in Udemy with some changes and code styling improvements.

[React-BurgerShop](https://github.com/PavelApostolov/ReactJS-BurgerShop) app refactored with Redux more convenient access to the state by the different components. It lets you design a tasty burger with ingredients and their quantity of your choice. 

# How does it work

You can add and remove different ingredients and you can see the immediate result of your creation as a burger designed with CSS. The price is also updated with every click. You have to be authenticated to make an order.

After building your burger a modal with the order summary pops. After confirmation you are redirected to a contacts page where you fill a form for delivery and finish your order. It is stored in Firebase database.

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
