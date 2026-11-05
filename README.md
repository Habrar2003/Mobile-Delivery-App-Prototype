# Mobile Delivery App Prototype

This project is an interactive prototype for a mobile food-delivery application. It was designed in Axure RP and exported as a collection of HTML, CSS, JavaScript, and image assets.

## Prototype scope

The prototype demonstrates the main customer journey, including:

- Starting the app and signing up or signing in
- Selecting a delivery location
- Browsing restaurants by cuisine
- Searching for shops and restaurants
- Viewing restaurant information, menus, and reviews
- Selecting food items
- Reviewing the order and checking out
- Viewing order records
- Accessing help and account recovery pages

This is a user-interface prototype only. It does not include a production backend, production authentication, payment processing, live restaurant data, or actual order delivery.

### Demo account

The sign-in screen includes a prototype-only demo account:

- Username: `Demo`
- Password: `123`

## Running the prototype

The exported files can be opened through a local web server. From the project directory, run:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000/prototype/index.html](http://localhost:8000/prototype/index.html) in a browser.

Using a local server is recommended so that the prototype's JavaScript, stylesheets, images, and page navigation load correctly.

## Project structure

- `prototype/index.html` - Prototype entry point
- `prototype/*.html` - Individual prototype screens
- `prototype/files/` - Screen-specific stylesheets and Axure data
- `prototype/resources/` - Axure runtime scripts, styles, and supporting assets
- `prototype/images/` - Images used throughout the prototype