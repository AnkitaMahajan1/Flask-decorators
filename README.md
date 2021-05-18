# Flask-decorators
The problem is that in Flask you can define many routes, each associated with a different URL, 
so somehow you need to tell the decorator which URL you are registering a handler for.
Without being able to pass the URL argument to the decorator there would be no way to
make this route decorator work.

Unfortunately adding arguments to a decorator is far from trivial.So in this repository you 
can see the how the decorator function and passing *args to the wrapper class.

A simple website is created using Flask and used decorators to define routes.
