Facebox with iFrame support
===========================
This is just an adaptation of the original [Facebox][facebox_url] plugin to add iFrame support.
[facebox_url]:(http://defunkt.io/facebox/)

The adaptation is based on this [post][original_post_url] by ShortcutTO701
[original_post_url]:(http://lnx.shortcutto701.com/2010/05/21/using-iframe-with-facebox-jquery-plugin/)

Usage example
-------------
You can use the plugin as always, however if you want to display "iframed" content you should add a "rev" attribute to the link as follows:

`<a href="contactform.aspx" rel="[facebox]" rev="iframe|350">Contact us</a>`

The "rev" attribute has two options splitted up by a pipe (|). In the above example, the "350" is the "height" of the iFrame.