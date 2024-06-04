## PHP no framework HTMX example

This is a simple example of using HTMX with PHP and no framework. It uses the [HTMX](https://htmx.org/) library to make AJAX requests and update the page with HTML over the wire. It has some basic error handling and exception handling.
We can also parse the HX-request header and render content without template. See `register_shutdown_function()`. In the `/about` page I also included an example of how one can work with a SQLite database.
