#Neurons Sublime Text Package#

A SublimeText-Package for [Neurons](https://github.com/platdesign/Neurons).

##Install##

- `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages`
- `git clone https://github.com/platdesign/Neurons.sublime-package`


##Snippets##

###doorman###
	<?PHP /* PREVENT EXECUTION */ defined("nrns") ? true : die(); ?>
	
###module###
	$module = nrns::module('myModule', ['dependencies']);

###service###
	$module->service('myService', function(){
		
	});

###provider###
	$module->provider('myProvider', function(){
		
	});
###factory###
	$module->factory('myFactory', function(){
		
	});
###run###
	$module->run(function(){
		
	});
###shutdown###
	$module->shutdown(function(){
		
	});
	
	
