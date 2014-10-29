TitaniumShareViaAndroid
=======================

Share contents natively directly from your Titanium app.
This simple module allows you to share contents (text or images) via Facebook or native apps (using intents).

####Usage

To share text:

~~~
require('/ShareViaAndroid')("Text to be shared", "text");
~~~

To share image:

~~~
var Blob = win.toImage().media;
var file = Titanium.Filesystem.getFile(Titanium.Filesystem.externalStorageDirectory,'image_1.png');
file.write(Blob);
	
require('/ShareViaAndroid')("Text to be shared", "image" , file);
~~~

MIT licensed, have fun ;)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/joseandro/titaniumshareviaandroid/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

