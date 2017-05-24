# Lightning Experience Development

### Page-centric web application model = Salesforce Classic
  * it relies on the server to generate a new page every time you interact with the application
  * Visualforce framework provides a robust set of tags that are resolved on the server, and that work alongside standard or custom controllers to make database and other operation simple to implement.
  
#### UI Generation
* Server-side
#### Data and Business Logic
* Apex standard or custom controller
#### Workflow
* User requests a page
* The server executes the page’s underlying code and sends the resulting HTML to the browser
* The browser displays the HTML
* When the user interacts with the page, return to step one
#### Pros
* Tried and true model
* Easy to implement for greater productivity
* Naturally splits large applications into small, manageable pages
* Has built-in metadata integration
#### Caveats
* Limited interactivity (aside from added JavaScript functionality)
* Higher latency, which degrades mobile performance

Visualforce is conceptually similar to other page-centric technologies like PHP, ASP, JSP, and Ruby on Rails. Salesforce’s rich metadata infrastructure makes Visualforce a productive solution. The standard controller makes it easy to access objects directly and via relationships without executing a single query. Other metadata-aware components are similarly plug-and-play: add markup to a page and you’re done. These capabilities are alive and well on the platform, and they’re still suitable for many use cases.
  
### App-centric model
 * Javascript is used to create, modify, transform, and animate the UI rather than completely replacing it a page at a time.


