# Controller-Generator-with-Symfony-Console
Automatict Generate File Controller to your own projects with Symfony Console

# How to use by default?
php app repo::controller homeController
ex.
<?php

namespace Applications\Http\Controllers;

use Applications\Http\controller\BaseController;

use Applications\Http\models\Users;

use Applications\Provider\Package\Resources;

use Applications\Provider\Signature\Authentication\Authentication;

use Applications\Provider\Signature\Authentication\Token;

use Applications\Provider\Signature\Authentication\Request;

use Applications\Provider\Package\UrlGenerator\View;


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

use Applications\Provider\Package\Resources;

use Applications\Provider\Signature\Authentication\Authentication;

use Applications\Provider\Signature\Authentication\Token;

use Applications\Provider\Signature\Authentication\Request;

use Applications\Provider\Package\UrlGenerator\View;


class homeController
{

	//method declaration
}
