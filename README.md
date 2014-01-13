#Neurons Sublime Text Package#

A SublimeText-Package for [Neurons](https://github.com/platdesign/Neurons).

##Install##

- `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages`
- `git clone https://github.com/platdesign/Neurons.sublime-package`


##Snippets##

###doorman###
This should be placed at the top of each template-file to prevent direct execution.

	<?PHP /* PREVENT EXECUTION */ defined("nrns") ? true : die(); ?>
	
###module###
Creates a new module.

	$module = nrns::module('myModule', ['dependencies']);

###service###
Creates a new Service.

	$module->service('myService', function(){
		
	});

###provider###
Creates a new Provider.

	$module->provider('myProvider', function(){
		
	});
###factory###
Creates a new Factory.

	$module->factory('myFactory', function(){
		
	});
###run###
Creates a new run-event-handler.

	$module->run(function(){
		
	});
###shutdown###
Creates a new shutdown-event-handler.

	$module->shutdown(function(){
		
	});
	
	
##Author##

Twitter: [Platdesign](https://twitter.com/platdesign)	
eMail: [mail@platdesign.de](mailto:mail@platdesign.de)