# Responsive Type jQuery Plugin

Version 1.1
Updated 31/05/2012

Copyright (c) 2012 Zach Inglis   (@zachinglis)
                   Laura Sanders (@teawithlemon)

## Demo

It's being used on zachinglis.com (Excuse the live redesign though.)

## Usage

    $("html").responsiveType();

Or for customisation, you can input options:

    $("html").responsiveType(minSize: 62.5,
                             maxSize: 82,
                             minWidth: 320,
                             maxWidth: 1280);


If you want to get the font smaller the larger your browser (as requested by @nathan_ford), then you can use the reverse option.
    $("html").respnsiveType(…options…
                             reverse: true);



NOTE: Don't forget to make a backup CSS rule for font size in case this stops working! It's a progressive enhancement.


There will be a better Readme coming soon!
