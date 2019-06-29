
BlogApp description and setup

#Blog Index
  * Setup the blog App
  * Create the blog model
  * Add INDEX route and template
 
#Basic Layout
  * Add header and footer partials
  * Include semanticUI
  * Add simple nav bar
  
#C of CRUD
  * Add NEW Route
  * Add new template
  * Add CREATE Route
  * Add CREATE Template

# SHOW
  * Add Show route
  * Add Show template
  * Add links to show page
  * Style show template

# Edit/Update
  * Add Edit Route
  * Add Edit Form
  * Add Update Route
  * Add Update Form
  * Add method-override (As HTML doesn't natively support HTML PUT and DELETE requests, hence we use this npm package to "trick" html and 
    updating our blog content)

#Destroy
  * Add Destroy Route
  * Add Edit and Destroy Links
 
# Final Updates
  * Sanitize blog body (install npm express-sanitizer package) //prevents malicious behaviour, removes scripts <%- to add html tags to text area description)
  * Style index
  * Update REST table