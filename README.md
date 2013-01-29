User Content
============

Overview
-------------

User content is a basic quarantine class used in front-end development when unknown content is going to be injected into a container (most likely via WYSIWYG). It allows for the flexibility of declaring all your styles for portions of the site you control, while also quarantining styles when the content is unknown.

It currently uses the Eric Meyer reset but could also potentionally be paired with something like normalize.

Usage
-------------
* grab the styles you want out of the user-content.css file and include them on your project
* update the styles to work with your website
* wrap user content in an HTML element with the class "user-content"
* watch the magic happen