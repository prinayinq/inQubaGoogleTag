# inQuba Journey Tracker
This is the official GTM template for the [inQuba customer journey management & customer experience (CX) platform](https://www.inquba.com). inQuba’s Journey Cloud offers a toolbox of cloud-based apps to help you optimize customer journeys and reinvent customer experiences.

## Documentation

### inQuba Endpoint
Enter your custom inQuba endpoint, i.e. the URL where you'd like to send the hits from the tracker.

### Event Details
The tracker captures certain details by default, but you'll have to add the inQuba transaction code for the event you would like to capture. You can also add additional identifiers to identify users across the entire journey. 

#### Default parameters
By default the inQuba template will capture any query parameter starting with `utm_` present in the URL as well as a `contactid` parameter. It will also capture a timestamp and the current URL the user is visiting.

#### Transaction Code
You can add the transaction code from your inQuba setup to match with the trigger for firing the inQuba GTM template (e.g. a pageview, login or form submission)

#### Identifiers
Identifiers allow you to match your users across channels and platforms. By default will auto generate its own pseudonymous identifier to identify users within and across sessions, but you can also use an existing value if, for example, you already have a cookie with a user ID. On certain events you can also add additional identifiers like a user ID, (hashed) phone number or (hashed) email address. These identifiers can help you create a full picture of a user's journey by matching the pseudonymous identifier with the known identifiers for the user.

### Custom Attributes
The inQuba Journey tracker also allows you to send up to 10 of your own custom attributes in key-value pairs. This way you can add details like, for example, a type of form the user has submitted or category for the page the user is on. 