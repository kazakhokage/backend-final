# Makhanov Yessengali SE-2211 Web Final Project

## Description

Portfolio Management System- web application created by using nodejs, mongodb atlas and API's. It allows to register as user and then use the website functions. Admin can directly change the user's role, data and etc.

## Features

- User registration and login
- Utilizing two API's to show graph and charts
- Multi-language support (English, Russian, Kazakh).
- Admin page for managing information and user data.

## Installation

1. Clone the repository:
   ```bash
  git clone <https://github.com/kazakhokage/backend-final.git>

3. Install dependencies:
    ```bash
   npm install

4. Start the server:
    ```bash
   node app.js

## Usage

After starting the server, navigate to `http://localhost:3000` in your web browser to access the application.

- Use the navbar to switch between different sections of the application.
- Convert currencies using the conversion tool on the dashboard.
- View current currency rates in the rates section.
- Admin users can add, edit, and delete market information through the admin page.

## APIs 

- **Alpha Vantage API** 
- **ExchangeRatesAPI** 

## Administrative Functionality

### Admin Page

The admin page allows administrators to manage user accounts. Admin can do:

- **Add Users**: Create new user accounts by specifying a username, password, and whether the account should have admin privileges.
- **Edit Users**: Update existing user account details, including changing their username, password, and admin status.
- **Delete Users**: Remove user accounts from the system.
- **Add Market Info Cards**: Create new market info card by entering the name and description in 3 languages(en, ru, kz)
- **Edit Market Info Cards**: Update existing market info details, including changing their names, description and images.
- **Delete Market Info Cards**: Remove market info cards from the system.


## Project functionality:

### Greeting page
User can choose register or login
### Registration
User enters username and password to register
### Login
User enters username and password to login
### Admin page
Admin can add, edit and delete the users' information
Also, admin can add, edit and delete market information cards
### Main page
User can see the market info cards 
### Dashboard page
User can convert and check the current currency rates
### Stocks page
User can check the prices of stocks by their stock market tags




