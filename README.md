# GravityFormsWebAPI
Swift 3 example using the Gravity Forms Web API to read entries over HTTP following RESTful principles.  Includes the subsequent JSON serialization.  The Web API requires a a base64 HMAC-SHA1 hash signature in the URL.  I used the Objective-C Common Crypto library to achieve this, since Swift 3 doesn’t have an equivalent.  This required a bridging header, which is in this project.  

Additional required project settings as configured in the project:
Build Settings: Swift Complier - General, Objective-C Bridging Header
Info: Custom iOS Target Properties, App Transport Security Settings



