Facebox with iFrame support
===========================
This is just an adaptation of the original [Facebox](http://defunkt.io/facebox/) plugin to add iFrame support.

The adaptation is based on this [post](http://lnx.shortcutto701.com/2010/05/21/using-iframe-with-facebox-jquery-plugin/) by ShortcutTO701

Usage example
-------------
You can use the plugin as always, however if you want to display "iframed" content you should add a "rev" attribute to the link as follows:

`<a href="/contact" rel="[facebox]" rev="iframe|350">Contact us</a>`

The "rev" attribute has two options splitted up by a pipe (|). In the above example, the "350" is the "height" of the iFrame.