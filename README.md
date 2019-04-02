![Developer Tools search box](https://screenshot.click/developer-tools-search-hero-cropped.gif)

**Shopify Developer Tools** is a macOS app that connects to your Shopify store(s) and allows you to make authenticated calls to the [Admin API](https://help.shopify.com/api/reference), generate dummy data, and view and customize [Polaris](https://polaris.shopify.com/) components.

## Installation
- Download the latest version of [`shopify-developer-tools-desktop-X.X.X-mac.zip`](https://github.com/shopifypartners/developer-tools/releases)
- Unzip the app and move it to your `Applications` folder
- Open it!

## Usage
![Data generator gif](https://screenshot.click/ezgif-4-2255f1d2e5.gif)

### Basics
- Press `control` + `option` + `s` to make Developer Tools visible (or bring it to focus) [above your active workspace](https://screenshot.click/06-13-yzhye-jugd7.jpg). Close the window with the same keys, or by using the standard macOS shortcut `command` + `w`
- When the app is in focus, press `command` + `f` at any time to focus on the search input
- Enter resource names, or app features to navigate to them:
  - `generator` to navigate to the data generator 
  - `get products count` to use the Admin API playground to get a count of all products in a store
  - `Layout` to view the Polaris `Layout` component
  - `profiles` to manage stores connected to Developer Tools 

### Authentication
Connect your Shopify store to Developer Tools to take advantage of the Admin API playground and data generator. You can login using your [development store](https://help.shopify.com/partners/dashboard/development-stores) credentials, or with an  [access token](https://help.shopify.com/api/getting-started/authentication/oauth).

### Data generator
![Data generator screenshot](https://screenshot.click/07-43-pr8cc-bajlo.jpg)
- Generate and delete dummy data for your store
- Create products using presets or a random data generator
- Jobs run the background so you can continue using the app or close the window

### Admin API playground
![Admin API playground screenshot](https://screenshot.click/06-37-mdca0-zhkqd.jpg)
- Press `command` + `enter` to run a request without having to click on the form button
- Access resources or endpoints directly via search (e.g `post order` or `count products`)
- View and customize sample **POST** and **PUT** requests 
- Copy responses from Shopify as prettified JSON

### Polaris playground
![Polaris playground screenshot](https://screenshot.click/06-41-in736-d8cxt.jpg)
- View and customize Polaris components
- Use the pop-out builder to save layouts

## Feedback / Issues
[Contact us](https://partners.shopify.com/current/support/form) if you have any issues using Developer Tools or want to share your ideas for feature requests.
