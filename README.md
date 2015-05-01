# Interactive Web Application 

This website is the final project for a Media Studies course taught
at NYU School of Engineering. The point of this is to have a small pool of 
users contribute to a giant story by appending submissions by only seeing
the most recent submission.

# Set-Up

This web application can be copied straight over to the root directory of
any web server. The `interactive.sql` instruction set should be imported 
to the back end database. The PHP queries in this web application used
the default options of `localhost`, `root`, and a blank password.

* Some of PHP scripts were embedded within HTML files. To allow the 
web-server to parse PHP code within HTML files, `AddType application/x-httpd-php .htm .html`
needs to be added to the `.htaccess` or `httpd.conf` files as necessary.