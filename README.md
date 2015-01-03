snow510
=======

plugin "snow"

Плагин падающих снежинок.

dependency: jQuery

Start: <br />
&lt;head&gt;<br />
    &lt;script src="js/snow.js" type="text/javascript"&gt;&lt;/script&gt;<br />
    &lt;link rel="stylesheet" type="text/css" href="css/snow.css"&gt;<br />
    &lt;script&gt;<br />
        $( document ).ready(function(){<br />
            snow('Количество снежинок int')<br />
        })
    &lt;/script&gt;<br />
&lt;/head&gt;<br />
