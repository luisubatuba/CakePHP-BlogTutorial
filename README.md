# CakePHP-BlogTutorial
This is the complete project with the finished  tutorial that CakePHP show in their documentation page.

# To Know
This project is the result of have finished this tutorial:

http://book.cakephp.org/2.0/en/tutorials-and-examples/blog/blog.html

# Installation
I recommend you to install a web server like WAMP or XAMPP or whatever you prefer, and then copy the "blog" folder into "www" or "htdocs" respectively.
Then import the script called "cakephp.sql". Can do it going to localhost/phpmyadmin

Be careful because the configuration established for this proyect at "blog/app/Config/database.php" is:

	class DATABASE_CONFIG {
		public $default = array(
			'datasource' => 'Database/Mysql',
			'persistent' => false,
			'host' => 'localhost',
			'login' => 'root',
			'password' => '',
			'database' => 'cakephp',
			'prefix' => '',
			'encoding' => 'utf8'
		);
	}


You should adapt this configuration but if you installed the server just now then nothing of this is neccesary, just import the sql script.

# Use
After the installation, just go to localhost/blog or serverpath/blog

# Read the Tutorial!
