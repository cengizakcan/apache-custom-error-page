# apache-custom-error-pageCustom error page template for apache webservers (mobile optimized, CSS3)## Instructions1. Copy all files to the root directory of the server2. Add these lines to your .htaccess file:		#Custom Error pages		ErrorDocument 400 /error.php		ErrorDocument 401 /error.php		ErrorDocument 403 /error.php		ErrorDocument 404 /error.php		ErrorDocument 500 /error.php3. The images can be placed in another location by simply changing their path in the status.css file. The css file can be placed in another location by changing its path in the error.php file.4. Change the email address in the error.php file on this line:		$email = 'chocolatkey@gmail.com';Any of the other text variables can be changed as well for different languages. When finished, it is recommended that you minimize the css file for speed.