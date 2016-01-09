WebJar for textAngular

More info: http://webjars.org

Upstream: https://github.com/fraywing/textAngular/


usage with requirejs:

require([ 'textAngular-rangy', 'textAngular' ], function(rangyCore) {
	window.rangy = rangyCore;
	window.rangy.saveSelection = function(){
		return undefined;
	}
}); 