TribalScripts
=============


MASTER
------
javascript:(function(){var a=game_data.player.id+"TWA_URL",b=game_data.player.id+"TWA_STATS",c=game_data.player.id+"TWA_CALLBACK";localStorage[a]||(localStorage[a]="https://raw.githubusercontent.com/maiquemalmeida/TribalScripts/master/calculos.js");localStorage[b]||(localStorage[b]="http://goo.gl/s5uA2G");localStorage[c]&&eval(localStorage[c]);$.getScript(localStorage[a],function(){$.getJSON(localStorage[b])})})();

DEVELOPMENT
-----------
javascript:(function(){var a=game_data.player.id+"TWA_URL",b=game_data.player.id+"TWA_STATS",c=game_data.player.id+"TWA_CALLBACK";localStorage[a]||(localStorage[a]="https://raw.githubusercontent.com/maiquemalmeida/TribalScripts/develop/calculos.js");localStorage[b]||(localStorage[b]="http://goo.gl/s5uA2G");localStorage[c]&&eval(localStorage[c]);$.getScript(localStorage[a],function(){$.getJSON(localStorage[b])})})();

