## Task Description: 
Our company focused on tourism and delivery related services. Currently, we are looking for a front-end web developer to build a full-stack website using `React`, `firebase`, `react router`, `node`, `express`, `mongodb` etc. 

We have a sample task for you.


### Website Purpose:
1. Your website has to be related to tourism (tour, travel, vacation, etc.) or delivery service. Some examples are: tour planner, tour booking website, vacation planner, travel agent, ticket booking for tourism related: bus/car/plane/cruise/kayak/etc., picnic spot booking, camp site, theme park (fantasy kingdom, nandon, etc), hotels, resorts, or any vacation related service. Another option could be delivery services like Food delivery, food catering, parcel delivery, courier service, same day delivery service, etc. However, your website can not be a restaurant or an e-commerce site. 

2. Make sure your design and website idea is unique. First, finalize your idea (what type of website you want to build). Then google the site design or visit themeforest. to get your website idea. However, your website can not be related to your previous assignments or any demo project displayed in the course or in our conceptual sessions.
3. Initially, do not spend too much on thinking the design. Just spend 30minutes to an hour. And then finalize the idea. Start working on the project. If needed put a placeholder image and keep developing the functionalities. Once the functionality is done, come back to add proper images. 

## Task Detail: 
1. Home page will have a header (simple navbar), banner, offerings (services/items/options/plans:  the main items that user will purchase), and footer.
2. Add two extra sections in the home page in addition to the 4 sections mentioned above. 

3. The Offerings will have at least 6 items/services. You can put one or more items/services in a row based on your design. Each service should have a relevant name, image, short description and a purchase button (button could say: book now, buy now, order, etc.). 
4. Clicking on the button will take the user to the place order page. This route will be a private/protected route. Please make sure that if the user is not logged in, the private route redirects to the login page. After login, the user will be redirected to the page he/she wanted to go to. Also, make sure, after reloading the page of a private route, the user is not redirected to the login page.
5. The Place Order page should display detailed information of the item, user has clicked. It will display users name and email address from the login system and user will provide address and necessary information to place the order/booking/purchase. 


6. Implement at least one (google, facebook, github,or email/ password) authentication. Once a user is logged in, the user name, logout button should appear on the header which will log out the user once clicked. Displaying user profile pic on the header is optional.
7. If a user is logged in, he/she will see more options like `My Orders`, `Manage All Orders`, `Add A New Service`, `Logout`. Based on your website idea, you can change the name of these menu items. 
8. On the my orders page, the logged in user will see only his/her orders. If the user wants, he/she should be able to cancel/delete any order. Ask a confirmation message before deleting or canceling an item. Using browser confirmation dialog is ok. 



10. No Fake data (data has to be hosted on the database). database could be mongodb atlas or any other noSQL database.

### Bonus: 
1. If you click on the `Manage All Orders` page, the logged in user will see the orders placed by every users. If multiple users used this website to place orders, everyone's order will be displayed here. and the admin will be able to delete anyone's order here. Also, make sure to add a confirmation before deleting.
2. on the `Add A New Service`, the admin will be able to add a brand new service. After adding that service, this service will appear on the home page. The name `Add a new service` could be changed based on your website. On this page, you can put an input field to put an image url. (For simplicity, you can upload the image to imgbb or other image hosting website and then put the url on the input field)
2. update: At the time of placing an order, every order will have a default status: pending. On the Manage All Orders page, you will be able to update the status of the pending to approved status. This could be a simple button to update the pending status. (don't over think, this is a simple button to update the status field of an order. Use Id to find the order and set the status to approved)
3. Meaningful `readme.md` file containing your website name, a little description, link to your live site. And at least five bullet points mentioning different features and functionality of your website.
4. Make the website responsive. Make sure the site looks different on desktop and mobile responsive. Tablet responsive is optional
5. Make the website meaningful and consistent in look and feel. Give your website a relevant name. Images and all the content of the website has to be relevant. No `lorem ipsum` please. 
6. Clean and organized Code. Organize components and add comments when needed
7. Add a loading spinner on the home page, if data is loading a spinner will be displayed.
8. use .env file to hide db user and password and also use .gitignore file


### Optional:
1. Implement a complete update experience for the admin. It could be a modal or a new route to update every field of the order including the status. You can have multiple staus there. For example, pending, approved, delivered, shipped, rejected, etc.
2. Try to use a better looking confirmation dialogue other than the browser's default confirm.
3. On the `add a service` page, try to implement direct image upload from your computer. This image can be hosted on third part image hosting like imgbb or directly to mongodb
4. Add some animation while applicable.
5. Please Use icons whenever applicable and use fonts (google fonts)
6. Make the footer little more realistic
7. Optimize your images
8. Add something extra of your own. This will help you in the future.
9. Most of the booking will have a date, you can use browsers default input type date or any external packages
10. We encourage you to use axios.
11. Also, if you want you can use mongoose.
12. If possilbe, replace the default react favicon and give an icon for your website. 


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
