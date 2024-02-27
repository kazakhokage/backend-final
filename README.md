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

- **Add Users**: Creating new accounts allowing to choose the role(admin/user).
- **Edit Users**: Update existing user account data.
- **Delete Users**: Remove user accounts from the system.
- **Add Market Info Cards**: Creating new data in 3 languages(en, ru, kz)
- **Edit Market Info Cards**: Update existing data details.
- **Delete Market Info Cards**: Remove data from the system.


## Project functionality:

### Starting page
User can choose register or login
### Registration
User enters username and password to register
### Login
User enters username and password to login
### Admin page
Admin can add, edit and delete the users' information and change the data
### Main page
User can see the data and other functions 
### Dashboard page
User can use Exchange rate option
### Stocks page
User can check stock prices




