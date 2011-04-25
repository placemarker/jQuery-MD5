# jQuery MD5 Plugin

## Usage
Create ([hex](http://en.wikipedia.org/wiki/Hexadecimal)-encoded) [MD5](http://en.wikipedia.org/wiki/MD5) hash of a given string value:

    var md5 = $.md5('value');

Create ([hex](http://en.wikipedia.org/wiki/Hexadecimal)-encoded) [HMAC](http://en.wikipedia.org/wiki/HMAC)-MD5 hash of a given string value and key:

    var md5 = $.md5('value', 'key');
    
Create raw [MD5](http://en.wikipedia.org/wiki/MD5) hash of a given string value:

    var md5 = $.md5('value', null, true);

Create raw [HMAC](http://en.wikipedia.org/wiki/HMAC)-MD5 hash of a given string value and key:

    var md5 = $.md5('value', 'key', true);

## Requirements
[jQuery](http://jquery.com/) v. 1.4+

## License
Released under the [MIT license](http://creativecommons.org/licenses/MIT/).

## Source Code & Download
* Browse and checkout the [source code](https://github.com/blueimp/jQuery-MD5).
* [Download](https://github.com/blueimp/jQuery-MD5/archives/master) the project to add the plugin to your website.
