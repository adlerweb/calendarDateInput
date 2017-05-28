# CalenderDateInput.js
## Fool-Proof Date Input Script with DHTML Calendar

This is a Javascript/HTML based calendar date input written by **Jason Moon**. The original authors site (moonscript.com) dissapeared, this is just a unmaintained mirror for legacy applications. 

It was pulled from a local repository and might have slight changes against the original. Notably:

 - Uses mostly UTF8 instead of images
 - Since the [UTF8 calendar icon](http://www.fileformat.info/info/unicode/char/1f4c5/browsertest.htm) is still not widely supported the calendar icon is still an image. You can modify it using *ImageURL*. Default is to use [koala-framework/library-silkicons](https://packagist.org/packages/koala-framework/library-silkicons).
 - Month predefined in german

You might be able to catch a more original code over at http://www.angelfire.com/ny5/consigliere/dateinputcalendar.html.

Long story short: Use something else ;).

### Compatibility

 IE5+, NS6/, Firefox and Opera 7+. Yes, modern browsers should work too.

### Requirements

None. Plain vanilla JS.

### Features

 - Leap year handling
 - Still works
 
### License

The original author didn't include a proper license and just posted it publicy. It is assumed the code can be used freely as long the authors copyright notice is kept.

### Usage

#### Include
...the file in your `<head>`-section as usual

    <script src="calendarDateInput.js" language="javascript" type="text/javascript"></script>

#### Add field
In your `<body>` use the following code to add a date input. 

    <script>DateInput('Date', true, 'YYYY-MM-DD', '{$date}')</script

This is somewhat equivilant to `<input type="text" name="Date"...`. The second argument defines if the input is required, third is DateFormat, last one the predefined Date.

