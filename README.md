Twitterbootstrap Responsive Layout
====================================

Add this gem to GEMFILE

gem "twitter-bootstrap-rails"


Install Bootstrap
------------------

rails g bootstrap:install


Install Responsive layout
---------------------------

rails g bootstrap:layout application fluid


About responsive Bootstrap
-----------------------------

Media queries allow for custom CSS based on a number of conditions—ratios, widths, display type, etc—but usually focuses around min-width and max-width.

   - Modify the width of column in our grid
   - Stack elements instead of float wherever necessary
   - Resize headings and text to be more appropriate for devices

Use media queries responsibly and only as a start to your mobile audiences. For larger projects, do consider dedicated code bases and not layers of media queries.


Supported devices
---------------------

Bootstrap supports a handful of media queries in a single file to help make your projects more appropriate on different devices and screen resolutions. Here's what's included:

Label 			    Layout width 	     Column width 	     Gutter width
Large display 	    1200px and up 	     70px 	             30px
Default 		    980px and up 	     60px 	             20px
Portrait tablets 	768px and above 	 42px 	             20px
Phones to tablets 	767px and below 	 Fluid columns, no fixed widths
Phones 	            480px and below 	 Fluid columns, no fixed widths



