#Use FPDF with Phalcon Framework
==============================

Setup
-----

In 'composer.json' file add the following lines:

{
    "repositories":[
        {
            "type":"vcs",
            "url":"git@github.com:ScorpWebs/fpdf-phalcon.git" 
        }
    ],
    "require": {
		"scorpwebs/fpdf-phalcon": "dev-master"
    }
}


Now execute `php composer.phar update` or `composer update`.

Usage
--------

        $pdf = new \PDF;

Sources
---------
[FPDF](http://www.fpdf.org/)
Uses FPDF 1.7

Developed by
---------
[ScorpWebs](http://www.scorpwebs.com/)
