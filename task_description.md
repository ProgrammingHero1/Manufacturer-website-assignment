## Task Description: 
Our company focused on a single product category selling website. Currently, we are looking for a front-end web developer to build a full-stack website using `React`, `firebase`, `react router`, `node`, `express`, `mongodb` etc. 

We have a sample task for you.


### Website Purpose:
1. Your website has to be related to Car Sales, Moto Bikes sales, Bike Sales, Apartment sales, Insurance Sales, handicraft, camera, security camera, air condition, mobile phone, Alarm Clock, sunglass, lipstick, Baby Care, Baby toys, Decorative lights, Blender, etc. However, your website can not be similar to any of your previous assignments. 

2. Make sure your design and website idea is unique. First, finalize your idea (what type of website you want to build). Then google the site design or visit themeforest. to get your website idea. However, your website can not be related to your previous assignments or any demo project displayed in the course or in our conceptual sessions.
3. Initially, do not spend too much on thinking the design. Just spend 30minutes to an hour. And then finalize the idea. Start working on the project. If needed put a placeholder image and keep developing the functionalities. Once the functionality is done, come back to add proper images. 

## Task Detail: 
1. Home page will have a header (simple navbar), products/items/services: (the main items that user will purchase), reviews, and footer. On the home page, the products/services will have maximum 6 items/services. You can put one or more items/services in a row based on your design. Each service should have a relevant name, image, short description but no purchase or buy now button.
2. Add two extra sections in the home page in addition to the 4 sections mentioned above. 


4. We will have another page on the top navigation bar (header) mentioning purchase/book/order. Clicking on the button will take the user to the place order page. This route will be a private/protected route. Please make sure that if the user is not logged in, the private route redirects to the login page. After login, the user will be redirected to the page he/she wanted to go to. Also, make sure, after reloading the page of a private route, the user is not redirected to the login page.
5. On this page, user will see all the products or services. you will need at least 10 products/services on this page. Each item will have name, description, image, price and button. Once user clicks on this button, will take the user to the order place page.
6. The Place Order page should display detailed information of the item, user has clicked. It will display users name and email address from the login system and user will provide address and necessary information to place the order/booking/purchase. 


6. Implement at least two (google, facebook, github,or email/ password) authentication. Once a user is logged in, the user name, logout button should appear on the header which will log out the user once clicked. Displaying username or the user profile pic on the header is optional.
7. If a user is logged in, he/she will see another option called `Dashboard` and inside that dashboard a normal user will see options like `My Orders`, `Review`, `Logout`. Based on your website idea, you can change the name of these menu items. 
8. On the my orders page, the logged in user will see only his/her orders. If the user wants, he/she should be able to cancel/delete any order. Ask a confirmation message before deleting or canceling an item. Using browser confirmation dialog is ok. 
9. On the Review page, user should be able to add a review and that review will appear on the hope age.

7. If an admin logs in, he/she will see more options like `Manage All Orders`, `Add A Service`, `Make Admin`, `Manage Services` `Logout`. Based on your website idea, you can change the name of these menu items. 
8. An Admin should be able to make another user admin. If and admin wants, he/she will be able to add a service. after adding the service, this service will appear on the home page. Please note, of images. you can just add a link of the image after uploading the image to image hosting sites like imgbb, etc.

3. on the `Add A New Product`, the admin will be able to add a brand new service. After adding that service, this service will appear on the home page. The name `Add a new service` could be changed based on your website. On this page, you can put an input field to put an image url. (For simplicity, you can upload the image to imgbb or other image hosting website and then put the url on the input field)

10. No Fake data (data has to be hosted on the database). database could be mongodb atlas or any other noSQL database.

### Bonus: 
1. 5 start review
2. If you click on the `Manage All Orders` page, the logged in user will see the orders placed by every users. If multiple users used this website to place orders, everyone's order will be displayed here. and the admin will be able to delete anyone's order here. Also, make sure to add a confirmation before deleting.

4. update: At the time of placing an order, every order will have a default status: pending. On the Manage All Orders page, you will be able to update the status of the pending to approved status. This could be a simple button to update the pending status. (don't over think, this is a simple button to update the status field of an order. Use Id to find the order and set the status to approved)
5. Meaningful `readme.md` file containing your website name, a little description, link to your live site. And at least five bullet points mentioning different features and functionality of your website.
6. Make the website responsive. Make sure the site looks different on desktop and mobile responsive. Tablet responsive is optional
7. Make the website meaningful and consistent in look and feel. Give your website a relevant name. Images and all the content of the website has to be relevant. No `lorem ipsum` please. 
8. Clean and organized Code. Organize components and add comments when needed

8. use .env file to hide db user and password and also use .gitignore file


### Optional:
1. shopping cart
2. pagination
3. jwt
4. Manage Services
5. Try to use a better looking confirmation dialogue other than the browser's default confirm.
6. On the `add a service` page, try to implement direct image upload from your computer. This image can be hosted on third part image hosting like imgbb or directly to mongodb
7. Add some animation while applicable.
8. Please Use icons whenever applicable and use fonts (google fonts)
9. Make the footer little more realistic
10. Optimize your images
11. Add something extra of your own. This will help you in the future.
12. Most of the booking will have a date, you can use browsers default input type date or any external packages
13. We encourage you to use axios.
14. Also, if you want you can use mongoose.
15. If possilbe, replace the default react favicon and give an icon for your website. 


### Additional information:
1. You can use local image or host image anywhere if you want or both.
3. You are free to use any css library you want. But, we recommend using tailwind css. 
4. If needed you can mix CSS framework with a component library
5. You may use `react hook form`, basic html form or any library for authentication
6. Local storage is optional
7. Client side Environment variable is recommended but optional.
8. Try to host your site on Firebase (Netlify host will need extra configuration)
9. Try to host server on heroku

### What to submit 
1. Your client side code github repository
2. Your server side code github repository
3. Your live website link



Have FUN! Have Patience. 
