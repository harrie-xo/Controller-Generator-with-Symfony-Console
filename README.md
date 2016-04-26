# Controller-Generator-with-Symfony-Console
Automatict Generate File Controller to your own projects with Symfony Console

# How to use by default?
php app repo::controller homeController

ex.

<?php

namespace Applications\Http\Controllers;

use Applications\Http\controller\BaseController;

use Applications\Http\models\Users;

class sampleController extends BaseController
{

	public function index(){
		
		//index method declarations.        

	}
}



# How to use with clean code?
php app repo::controller homeController --clear

ex.

<?php

namespace Applications\Http\Controllers;

use Applications\Http\controller\BaseController;

use Applications\Http\models\Users;

class homeController
{

	//method declaration
}
