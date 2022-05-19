## Task Description: 
We are a manufacturer. We are looking for a front-end web developer to build a website using for us. 

### Website Purpose:
1. Your website has to be a `tools manufacturer`. The tool manufacturers could manufacture carpentry tools, masonry tools, electric tools, metalwork tools, or any tool. Some examples of tools could be a hammer, drill machine, screwdriver, wrench, Pliers, Measuring Tape, Chisel, Soldering Iron, shovel, electric saw, hacksaw, paint roller, paintbrush, sandpaper, nut, bolts, drill bit, clamp, workbench, nail gun, glue gun, etc. 

2. Alternatively, your website could be a `parts manufacturer`. A part will produce parts of a machine or a device. Examples of parts manufacturers could be car parts manufacturers, Motor Bike parts manufacturers, Bicycle parts manufacturers, camera parts manufacturers, refrigerator parts manufacturers, air conditioner parts manufacturers, table fan parts manufacturers, Clock parts manufacturers, TV parts manufacturers, microwave oven parts manufacturers, computer parts manufacturer, etc. 

3. Your website can not be typical e-commerce or any of your previous assignments. Make sure your design and website idea is unique. Make sure your code or design doesn't match any of the projects implemented in our course. Your website can not be related to your previous assignments or any practice project displayed in the course or our conceptual sessions.

4. Initially, do not spend too much time thinking about the design. Just spend 30minutes to an hour. And then finalize the idea. Start working on the Project. If needed, put a placeholder image and keep developing the functionalities. Once the functionality is done, come back to add proper images. 

## Task Details: 
1. Home page will have a Header (simple navbar), Banner, Tools/Parts, Business Summary, Reviews, and Footer. The tools/parts will have either 3 or 6 tools/parts. Based on your design, you can put one or more tools/parts in a row. Each tool/part should have a relevant name, image, short description, minimum order quantity, available quantity, price (per unit price), a place order/purchase/book now/ buy now button. If a user clicks on the purchase or buy now button it will take the user to the purchase page. 

2. Add two different sections on the home page and the 6 sections mentioned above. Tips: This is the place to shine. Add something different and unique to make your website looks different than others. And Make them relevant to your website. And make these two sections meaningful.

3. The business summary will show some summary of your business. There could be 3/4 summary on this summary section. For example, we served 100+ customers, 120M+ Annual revenue, 33K+ Reviews, 50+ tools, etc. Make sure you use some relevant icons here. 

5. The `purchase' page will be a private/protected route. Please make sure that the private route redirects to the login page if the user is not logged in. After login, the user will be redirected to the page he/she wanted to go to. Also, after reloading the page of a private/protected route, the user is not redirected to the login page. The purchase page should display detailed information about the item the user has clicked somewhere at the top. It will also display the user's name and email address from the login system. The user will have a field to provide an address, phone number, and other necessary information (if applicable) to place the order or complete the purchase. 

6. User will be able to change the order quantity (increase/decrease). However, the user won't be able to reduce the quantity below the minimum order quantity mentioned on the tool/part. Also, the order quantity can not be higher than the available quantity. You will display an error and disable the purchase button in both cases.

7. Implement an email/ password (login/Register) based login system. The registration form should have the name, and once a user is logged in, the user name and the logout button should appear on the header, which will log out the user once clicked. Implement at least one social login system (google, facebook, or github, etc.). Make sure to display login-related errors and password validation-related errors. 

9. If a user is logged in, they will see another option on the header is called `Dashboard`. Inside the dashboard, a user (not an admin) will see options like `My Orders`, `Add A Review`, `My Profile` options on the side nav. This is the time to implement a nested route. Based on your website idea, you can change the name of these menu items. The logout option will log the user out and redirect them to the home page.

10. On `My Orders` page, the logged-in user will see only his/her orders. If the user wants, he/she should be able to cancel/delete any order that is not shipped yet. Ask for a confirmation message before deleting or canceling an order. Using browser confirmation dialog is ok. However, we will prefer a good-looking modal.

7. On the `My Orders` page, there will be a payment button for each order. The user has not paid yet. The pay button will take the user to the payment page. The user should be able to pay by using a credit card here. The payment page will display order details. Once the payment is completed for an order, you will show the transaction id for that order on my orders page.

11. On the Review page, users should be able to add a review. That review will appear on the home page reviews section. Right now, you will see every review on the home page. There is no limit on the number of reviews or the order of the review. 

12. Another different route will be `My profile`. A user will see his/her name and email address on this profile. Also, this page will have fields to add fields like education, location (city/district), phone number, LinkedIn profile link, etc. And users will be able to save this information in the database. Also, the user will be able to update this information.

13. If an admin logs in, he/she will not see the options that a user sees. Instead, an admin will see `Manage All Orders`, `Add A Product`, `Make Admin`, `Manage Products`, `My Profile`. Based on your website idea, you can change the name of these menu items. 

14. An Admin should be able to make another user an admin. If an admin wants, he/she will be able to add a product on the add a product page. After adding the product, this product will appear on the `home` page. Please note, to add an image for a new product, you can just upload the image directly to the image hosting sites like imgbb, etc using API. Alternatively, you can have an input field to add the link to the image.

15. Add two more routes. one route will be `blogs`. You will need to answer at least five questions on the blogs page. This won't be a protected route. We recommend answering all four questions.

    15.1 How will you increase the performance of a React Application?

    15.2 What are the different ways to manage a state in a React application?

    15.3 How does prototypical inheritance work?

    15.4 Why you do not set the state directly in React. For example, if you have `const [products, setProducts] = useState([])`. Why you do not set `products = [...]` instead, you use the `setProducts`
    
    15.5 You have an array of products. Each object has a name, price, description, etc. How will you implement a search to find products by name?  

    15.6 What is a unit test? Why should write unit tests?

16. Create a meaningful 404 page (not found page)

17. Use a database to store information. It could be mongodb atlas or any other database.

### Bonus: 
1. Add an input field to add ratings (a number between 0-5). Based on the rating, display a rating star on each review on the home page. 

2. Meaningful `readme.md` file on both the client and server sides containing your website name, a short description (at least 5 bullet points), and a link to your live site. And at least five bullet points mention your website's different features and functionality.

3. At least 15 meaningful GitHub commits for the client-side and at least 10 meaningful commits for the server-side repository.

6. Make the website responsive. Make sure the site looks different on desktop and mobile responsive. Tablet responsive is optional.

7. Make the website meaningful and consistent in look and feel. Give your website a relevant name. Images and all the content of the website have to be appropriate. No `lorem ipsum` please. 

8. Clean and organized Code. Organize components and add comments when needed. use `.env` file on the server, `.env.local` file on the client to hide db user and password, etc. Also use the `.gitignore` file

9. On the `Manage All Orders` page for the admin, the logged-in admin will see the orders placed by every user. If multiple users use this website to place orders, everyone's order will be displayed here. Admin can update the status of the order. When placing an order, every order will have a default status: pending. On the Manage All Orders page, an admin will be able to update the status of the pending to `shipped` status. This could be a simple button to update the pending status. (don't overthink, this is a simple button to update the status field of the order. Use Id to find the order and set the status to approved). Also, it would be nice if you could do one additional task here: The admin will be able to delete anyone's order here. Make sure to add a confirmation before deleting. Please note: delete is optional but recommended on this page.

10. Implement the basic version of the `jwt` token for email/password-based authentication. Upon login, you will create a jwt token and store it on the client-side, and for the My Items page, you will send the token with the call and verify the user. Implementing 401 and 403 is optional. For social login, jwt token implementation is optional.

11. on the `Manage Products` page, an admin can delete any products. Please make sure there is a confirmation. After deleting that product will not appear on the `explore` page.

12. Use `react query` for at least one API call. Avoid browser default alert, confirm. Instead, use toast or modal.

1. Use `react hook form` at least one form. For the rest of the forms, you can either use react hook form or basic html form or any other form you want.

### Optional but highly encouraged to do:
Make sure you have done everything on the main part and bonus. Deploy and test everything. After that, you may try optional things.

1. We encourage you to use `axios` and implement interceptors to inject headers for the secure API call.
2. Raw materials Suppliers
3. send a confirmation email after placing an order. Even if the email doesn't get sent or goes to the spam folder. 
5. If possible, add pagination on your `explore route`. Also, you can add categories and filter by category on this page.
6. Manage the orders page, add more options like: pending, rejected, and shipped. And consider using a select (drop-down options). Also, once the status of an item is updated, that status is reflected on the 'my orders' page once the order user is logged in.

7. Try to use a better-looking confirmation dialogue other than the browser's default confirm.
8. Add some animation while applicable.
9. Please Use icons whenever applicable and use fonts (google fonts)
10. Make the footer a little more realistic
11. Optimize your images
12. Add something extra of your own. This will help you in the future.
15. Also, if you want, you can use mongoose.
16. If possible, replace the default react favicon and give an icon for your website. 
17. You should (optional for the assignment)  Implement email verification. However, do not block the user if the email is not verified for our assignment evaluation purpose. Because it will stop the assignment evaluation if the email sending is not working, if you want, you can enforce this after receiving assignment marks.

### Additional information:
1. You can use local image or host image anywhere if you want or both.
3. You are free to use any css library you want. But, we recommend using tailwind css. 
4. If needed, you can mix CSS framework with a component library
6. Local storage is optional
8. Try to host your site on Firebase (Netlify host will need extra configuration)
9. Try to host server on heroku

### What to submit 
1. Client-side code github repository
2. Server-side code github repository
3. Live website link
4. For our testing purpose, you will need to provide admin credentials (an email address and a password)
5. [optional] Project and code overview demo video

Have FUN! Have Patience. 