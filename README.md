<b>Tasks:
- [ ] Login form:
  - [ ] Only login form on first visit
  - [ ] user can type his name
  - [ ] user can submit this form (no validation needed)

- [ ] After submitting the login form:
  - [ ] User's info stored in Database
  - [ ] user's name appears on the navbar with something like "Welcome, userName"
  - [ ] redirect the user to the main page

- [ ] The main listing page should display all the products with their:
  - [ ] image
  - [ ] name
  - [ ] price
  - [ ] time created
  - [ ] sort feature
    - [ ] price
    - [ ] time created
    - [ ] name

- [ ] Clicking on a single product:
  - [ ] sends the user to that products’ detail page,

- [ ] Detail Page:
  - [ ]  user can see detailed product information
    - [ ] seller
    - [ ] created_at
    - [ ] categories
    - [ ] product_id
    - [ ] etc.

- [ ] The user should be able to go back to the main page from the product-detail one

<br></br>

<b>Key points:
- [ ] Use React and Redux to build this app.
- [ ] Use a database(MongoDB is preferred) to store user's information in it. The App should have a
functionality to show all users that were previously logged in.
- [ ] Create a feature that will allow to sort the products on the main page based on their price, time
created, and name.
- [ ] Set up cookies for user data
- [ ] Prevent unlogged users from going to the main page(or product-details page).
- [ ] Host it on any platform you want(ex. AWS, Heroku etc.)

<b>Bonus points:
- [ ] Use SSR
- [ ] Build some unit tests for this App(ex. using jest, mocha etc.)
- [ ] Implement pagination for the main page, so it will show 20-25 products per page.
