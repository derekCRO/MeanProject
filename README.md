# Material Shop
+ Material Designed AngularJS Shopping Cart 
+ Created with MEAN Stack (MongoDB + ExpressJS + AngularJS + NodeJS)
+ PayPal + COD Checkout
+ Drag and drop category selection
+ Single page e-commerce
+ Secured authentication system
+ facebook + google + twitter login/signup
+ Email integration 
+ Image uploader
+ CRUD generator
+ ReST API based backend
+ Full source code shared
+ Clean and modular code

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](nodejs.org)
- [MongoDB](https://www.mongodb.com/)
- [Bower](bower.io) (`npm install --g bower`)
- [Gulp](http://gulpjs.com/) (`npm install --g gulp`)

### Developing

- `npm install` - installs server dependencies.
- `bower install` - installs front-end dependencies.
- Run `mongod` in a separate shell to keep an instance of the MongoDB Daemon running
- `gulp serve` to start the application at http://localhost:9000.

### New Features

- Enter your paypal app ID into settings, add products and start selling with no matter of time. This has got inbuilt multi currency support with curency conversion feature
- Developed using the most popular MEAN(MongoDB + Express + Angular + Node) which has a RestAPI based architecture with high scallability.
- Inbuilt authentication mechanism with role based user access and user management
- Most of the components are based on Google Material designe guidelines which gives you a responsive, bold and accessible design with great amount of user interactivity
- Integration of emails at diffent levels like Order Placement, Forgot/Reset password gives a secure as well as informative feeling
- The modular application structure gives you enormous ability to modify, test and deploy easily
- Ability yo manage discount coupons on cart total
- With integrated drag and drop image upload its easy to manage the images for the whole shop
- ES6 module structure for serve side programming.
- PayPal integration with orders
- Role based user management for both client and server side e.g. User, Manager, Administrator
- Now an email is sent as soon as a order is placed or payment failed
- Mobile Centered Material Designed components with accessibility support
- Flex based page design principle
- Free Material CRUD Table module comes with this Material Shop
- Directly select image for a product from the media gallery
- Now Clone any brand, country, shipping, coupon to save time
- Drag and drop category management upto 10 levels
- Support for additional currencies beyond US Dollars from a single settings page
- Forgotten password of a user or shop manager can be retrieved with a encryption based email service
- A tiny little popup window for anybody to reach the store owner with any grievance or suggestions
- Now PayPal integration is more powerful with the managed payment status
- Auto-suggest, keyword product search.

### Store Front

- The MEAN Stack ecommerce with Material Design
- A whole ecommerce application created using AngularJS as front end
- The backend (server side) is backed with the awesome NodeJS framework for better speed and wide extensions support with a very large community base
- The document based No_SQL database used for faster communication and more efficiency
- Industry standard application module structure
- SPA(Single Page App) created with the power of AngularJS and ui-router
- Instant and single page advance checkout system
- Now every activity by a user or shop manger is reflected in realtime across the web app(without page reloads)
- Option to save inactive product for publishing later
- Option to add multiple variants of a single product with different price, size and image
- Additional product details in key/value list
- More product details in key/value list which need to be highlighted in the product details page
- Cross Platform development setup with efficient with gulp, bower, npm
- Category wise product details
- Advanced features like Multiple brands selector, Prodcut type filter, price slider
- Integrated social media login
- Reset and Change Password option
- Automatically load more products on scroll without the need of pagination
- SEO friendly URLs for each page
- Ready for screen readers for improved assistive
- Email service for queries/suggestions/grievances through popup contact form

### Store Backoffice

- Products, Categories, Brand, Order Management from admin panel with easy directives
- Manage Order and Change Status from admin panel
- Facility for Multiple product variants (size, color, price, image)
- Secure and quality code - Takes care all single page web app standards
- Securely built and prevent security attacks
- Generates CRUD(Create, Read, Update, Delete) pages automatically from database.
- NodeJS based ReST API architecture
- Integrated material designed date picker for date fields
- Code is Modular, Maintainable, Well Structured, Easy to customize, Production Ready
- Automatically generates dropdowns, datepickers, number field, toggle switch based on field types
- Easily export the table as Excel, JSON, txt format

### Settings

#### client/app/settings.js

```
demo: false,
country: {name:'India', code: 'IN'}, 
currency: {code: 'USD', symbol: 'Rs ', exchange_rate: '0.015'},
orderStatus: ['Payment Pending','Order Placed','Order Accepted','Order Executed','Shipped','Delivered','Cancelled','Not in Stock']
```

#### local.env.js

```
DOMAIN:               'http://localhost:9000',
SESSION_SECRET:       'materialshop-secret',

FACEBOOK_ID:          'app-id',
FACEBOOK_SECRET:      'secret',

TWITTER_ID:           'app-id',
TWITTER_SECRET:       'secret',

GOOGLE_ID:            'app-id',
GOOGLE_SECRET:        'secret',

SENDGRID_APIKEY:      'YOUR_GENERATED_SENDGRID_API_KEY',

PAYPAL_MODE :         'sandbox', //sandbox or live
PAYPAL_CLIENT_ID:     'YOUR_PAYPAL_CLIENT_ID',
PAYPAL_CLIENT_SECRET: 'YOUR_PAYPAL_CLIENT_SECRET'
```

#### Additional Requirements

Create an account at - [Sendgrid](http://www.sendgrid.com/)"> and generate a new API Key
Create create a new app @
 * [PayPal Developer](http://developer.paypal.com/)
 * [Facebook Developer](http://developer.facebook.com/)
 * [Google Developer Console](https://console.developers.google.com/)
 * [Twitter Developer](https://dev.twitter.com/) 

#### Development History

```
'2016-09-10' => Documentation improvements
'2016-09-10' => Product image and media page layour fixed
'2016-09-10' => Added search button for mobile devices at navbar
'2016-09-09' => Order, Orders, Checkout made responsive
'2016-09-09' => Forgot password fixed
'2016-09-09' => Preloader positioned to center of page
'2016-09-09' => Updated to angular-material 1.1.1
'2016-09-09' => Allowed checkout @ demo mode
'2016-09-09' => Loading indicator at login and signup page fixed
'2016-09-09' => Demo mode setting moved to client/components/auth/interceptor.service.js
'2016-09-09' => Change password ui issue resolved
'2016-09-09' => Message for no order in order page
'2016-09-09' => Forgot and reset password options moved to shared server\config\environment
'2016-09-08' => Removed "checklist-model" from bower.json Implemented own checklist-model using md-checkbox Thi solved the issue of not assigning model while clicking the checkbox itself'
'2016-09-08' => Added Demo mode check to each save route
'2016-09-08' => SortOptions removed from factory.service.js
'2016-09-08' => Circular progress diameter changed
'2016-09-08' => OAUTH buttons loading issue fixed
'2016-09-08' => Loading indicators fixed
'2016-09-08' => Optimized user controller (testing required)
'2016-09-07' => Product loading indicator added
'2016-09-07' => Added the app preloader which loads before css and js
'2016-09-07' => Product list ui-issue fixed
'2016-09-07' => Media manager images made visible from partial to complete
'2016-09-07' => COD @ Checkout + Exchange rate @ Order
'2016-09-07' => Product main page made responsive
'2016-09-07' => Fixed navbar flex issue
'2016-09-06' => Product and navbar layout made flex
'2016-09-06' => Added features to documentation
'2016-09-06' => Prepared documentation page module
'2016-09-05' => Preparing documentation
'2016-09-05' => Added uploads as empty directory
'2016-09-04' => Resolved issue with the media uploader
'2016-09-04' => Push coupon discount only if available
'2016-09-04' => Shipping now calculated @ navbar instead of checkout
'2016-09-04' => Domain/site name removed from settings and cart.services
'2016-09-04' => Filter textbox design changed
'2016-09-04' => Searchbar optimized
'2016-09-04' => Payment response captured by Order document
'2016-09-03' => Validate exchange rate against non int
'2016-09-03' => Exchange rate implemented - Testing required
'2016-09-03' => Order blocked if cart value 0
'2016-09-03' => Order captured with Paypal checkout
'2016-09-02' => Handled ETIMEDOUT @ paypal
'2016-09-02' => Handled 404 error of paypal
'2016-09-02' => Paypal error handling
'2016-09-02' => PayPal moved to /api/pay
'2016-09-01' => Added Shipping info into cart
'2016-09-01' => Started documentation
'2016-09-01' => PayPal Payment settings with actual cart implemented
'2016-08-31' => Added qty change button to cart
'2016-08-31' => Activated login modal again on interceptor.service.js
'2016-08-30' => Added payment response blocks to order and checkout page
'2016-08-30' => Added cart page
'2016-08-29' => PayPal Payment implemented with payment ID response
'2016-08-28' => Migrated all md-icons to ng-md-icons
'2016-08-28' => Cleaned controllers and services from comments
'2016-08-28' => Removed html comments for cleaner code
'2016-08-28' => Changing md-icon to ng-md-icon to reduce page loading time
'2016-08-27' => Fixed: Signup menu item hide on small devices
'2016-08-27' => Added Order Management page for admin
'2016-08-26' => Search button stays there after clicking
'2016-08-26' => Removed sample data from application which was blocking the build process
'2016-08-26' => authInterceptor removed from main app
'2016-08-26' => Implemented filter notifiers
'2016-08-25' => Navigation to product details enabled from cart, order, search page
'2016-08-25' => Set searchbox text after a search is performed
'2016-08-25' => Cart clear after order success implemented
'2016-08-25' => Felt navbar-public unnecessary
'2016-08-25' => Null coupon issue resolved
'2016-08-25' => Order model changed to accomodate created_at and updated_at. Could not use createdAt, updatedAt o {timestamps: true}'
'2016-08-25' => Best shipper determination based on country was removed
'2016-08-24' => Address switching now updates best shipper
'2016-08-24' => Address and Brand model changed to accomodate boolean value
'2016-08-23' => Added free carrier when no free shipper present
'2016-08-22' => Cart and shipping issue resolved
'2016-08-20' => Multi reload issue resolved for cart
'2016-08-16' => Order page layout beautified
'2016-08-16' => Added country into settings
'2016-08-15' => Address update functionality rectified
'2016-08-14' => Merge branch 'master' into gulp
'2016-08-13' => Universal currency settings implemented.
'2016-08-13' => Completed product details page
'2016-08-12' => Product detail added with a link from products
'2016-08-11' => Rectified infinite scroll
'2016-08-08' => Sort options, product sort, filter Removed linting, activated brand search(by ID) Scroll left pane only @ products manager page Added navigation links to parent menu items too.'
'2016-08-06' => Product and category hierarchy updated
'2016-08-05' => Product details update issue corrected
'2016-08-04' => Removed category heirarchy from products page
'2016-08-04' => Category heirarchy level increased to 10
'2016-08-03' => Category drag drop and parent child update done.
'2016-08-03' => Working again on category sorting
'2016-08-02' => Updated bower packages
'2016-07-29' => user controller error resolved
'2016-07-29' => Fixed error at user service
'2016-07-28' => Switched to gulp
'2016-07-01' => Drag and drop category change
'2016-06-14' => Added mutually exclusive dropdown at product page
'2016-06-13' => Working towards category hierarchical sorting.
'2016-06-11' => Categoy modification to accomodate parent reference
'2016-06-06' => Get category path
'2016-06-03' => Implement async for products
'2016-06-02' => Category dropdown
'2016-06-01' => Upgraded media components
'2016-05-30' => Added country name to address book
'2016-05-30' => Blocked checkout if cart is empty
'2016-05-30' => Order checkout completed
'2016-05-28' => Checkout page made responsive
'2016-05-28' => Merged improve-category into master
'2016-05-28' => Layout for checkout freezed
'2016-05-28' => Order page layout
'2016-05-13' => Added category menu
'2016-04-30' => Subcategory error corrected
'2016-04-28' => added updation feature to subcategories
'2016-04-28' => Created category page
'2016-04-28' => Improve category
'2016-04-27' => Implemented tabs for category
'2016-04-27' => Implemented subdocuments for category
'2016-04-26' => Implemented subdocuments
'2016-04-26' => Trying to implement sub-category as subdocument
'2016-04-25' => Working on categories hierarchy
'2016-04-23' => Working on treeview generation
'2016-04-21' => Added enhanced megamenu
'2016-04-21' => Working on topmenu
'2016-04-21' => Added pluralize filter to crud-table
'2016-04-18' => Auth updated for login modal
'2016-04-16' => Implemented modals for login , signup and change password
'2016-04-16' => Added animations
'2016-03-10' => Working on shipping calculations
'2016-03-10' => Shipping charge issue at total amount resolved
'2016-03-09' => Working on orders page
'2016-03-09' => User role issue resolved
'2016-03-09' => Implemented user roles to each route. Optimized the login modal.
'2016-03-08' => Filter menu redisgn
'2016-03-08' => Upgraded user roles management at admin
'2016-03-08' => Price slider now gets the actual value
'2016-03-07' => PRoduct listing page designing
'2016-03-04' => Changing product layout
'2016-03-04' => Changed email text
'2016-03-03' => Added top menu user icon and name
'2016-03-03' => Fixed navmenu dropdown height issue
'2016-03-02' => Add login and signup as modal dialog
'2016-03-02' => Trying to implement login as modal
'2016-03-01' => Added user role module
'2016-02-29' => Added forgot password module
'2016-02-27' => Added Address Module
'2016-02-25' => Changed product filter style
'2016-02-25' => Forced footer to stick to the bottom of page
'2016-02-25' => Resolved sorting issue and icons
'2016-02-25' => Resolved category issue
'2016-02-24' => fixed page flex alignment issue
'2016-02-23' => Fixed footer position issue
'2016-02-22' => Added more flex items
'2016-02-22' => Improved product layout
'2016-02-22' => Converted layouts to flex containers
'2016-02-20' => Added checkout module
'2016-02-20' => Optimized caart module
'2016-02-19' => edited .gitignore to accomodate visual studio code settings file
'2016-02-19' => Changed controller code structure to class type
'2016-02-18' => Added brands, features filter
'2016-02-17' => Added cart
'2016-02-17' => Added filter menu to sidenav
'2016-02-17' => Key features module added
'2016-02-17' => Resolved the multually exclusive dropdown issue at features selection inside products admin page
'2016-02-17' => Resolved pluralization issue at api selection in crud-table client
'2016-02-16' => Added product admin module with image upload
'2016-02-16' => Products admin view created
'2016-02-15' => Working on products admin
'2016-02-15' => Added decissive seed to production env
'2016-02-14' => Gruntfile modified to local abstraction
'2016-02-14' => Corrected line endings and bower injection issue
'2016-02-10' => Initialized the project and crafted the admin panel
```