# Recipe Book

Recipe Book is an Angular 6 web application where you can browse through a list of simple and exciting recipes and try them out at home. You can also view a list of ingredients and add them to the cart for checkout.

### Features

- Manage recipes posts

  - Create, view, edit and delete recipes
  - Add recipe ingredients to the shopping list
  - Add custom ingredients to the shopping list for checkout

- Responsive web design

- Authentication

  - Signup a user with a username and password
  - User login using the username and password
	
- Authorization

  - One cannot create or edit a recipe without user login
  - One cannot edit or delete a recipe created by a different user

- CRUD operations on recipes and shopping list

### Technologies used

- Google Fonts
- Font Awesome
- Bootstrap 4
- Node.js

## To build a demo project

1) Clone the project repo to your machine

2) Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

3) Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## To run unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## To run end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
