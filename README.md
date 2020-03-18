## What it does

This application (Salty-Dogs-Galley) is part of a two-sided restaurant application created so you can order seafood dishes online.From the home page navigation bar, you can access menu items, place orders and checkout. 

Click the following URL to view the customer side application https://sdgcustomer.herokuapp.com/

The other part of this applciation is the manager part found which can be used to edit menu items and manage orders. You can use the following URL to access the manager app https://sdgmanager.herokuapp.com/ and use the below username and password.
```
User Name: sdg.manager@hotmail.com
Password: 1234567
```

## Screenshots

### Home Screen
![Home Screen](https://github.com/josephmerlitz/Salty-Dogs-Galley-Customer-App/blob/master/repo-images/Home.png)

### Menu
![Menu](https://github.com/josephmerlitz/Salty-Dogs-Galley-Customer-App/blob/master/repo-images/Menu.png)

### Place Order Page
![Place Order Page](https://github.com/josephmerlitz/Salty-Dogs-Galley-Customer-App/blob/master/repo-images/Order.png)

### Cart
![Cart](https://github.com/josephmerlitz/Salty-Dogs-Galley-Customer-App/blob/master/repo-images/Cart.png)

### Checkout Page
![Checkout Page](https://github.com/josephmerlitz/Salty-Dogs-Galley-Customer-App/blob/master/repo-images/Checkout.png)

### Receipt Page
![Receipt Page](https://github.com/josephmerlitz/Salty-Dogs-Galley-Customer-App/blob/master/repo-images/Receipt.png)

## You can follow the below steps to install and run the customer app

1. Rename the file **.env.example** to **.env**
2. Create your Stripe account and update **STRIPE_SECRET_KEY** and **STRIPE_PUBLISHABLE_KEY** in your .env file
3. Create a MongoDB database and configure the database connection string **MONGODB_URI** in your **.env** file
4. Install all dependencies by moving to the **project** main directory and then running **npm install** then running **npm run client-install**
6. Start the app by moving to the project main directory and then running the command **npm run dev**


## Used Technologies

1. React
2. MongoDB
3. React Router
4. Bootstrap
5. React Context API
6. Node JS
7. Express
8. Mongoose
9. Axios
10. Stripe
