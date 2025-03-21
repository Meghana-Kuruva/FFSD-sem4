# FFSD - Sem 4

Chasing Horizons - A comprehensive Tourism and Hotel Booking website

## Formats and Syntax

SPACING SYSTEM (px) \
2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

FONT SIZE SYSTEM (px) \
10 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98

01 - Typography \
02 - Font Weights \
03 - Line Heights \
04 - Colors (Primary, Tints, Shades, Greys) \
05 - Spacing System \
06 - Shadows \
07 - border radius

## Folder Structure Explained

Controller -> Contains all the js files that handles user requests \
Model -> Contains all the js files where we define the Database Models \
Views -> Contains all the EJS templates

public -> This folder contains all the files which will be used in the client side of the application \
public/images -> Contains all the images \
public/css -> Contains all the CSS files \
public/js -> Conatins all the Client side js files

routes -> Folder for handling different routes , contains all related routes in one file \
For example all the /tours routing code in one tourRouter file

## Common Questions

1. Difference between Client Side JS and Server Side JS

- Server Side JS \
  Handles backend logic, database interactions, authentication, etc. \
  Fetching data from a database, processing requests \
  Cannot Manipulate DOM

- Client Side JS \
  Handles UI interactions, DOM manipulation, animations, etc. \
  Validating form inputs, updating page content dynamically \
  Can manipulate the DOM
