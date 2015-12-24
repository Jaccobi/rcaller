# Introduction #

We are happy to announce that we released the php version of RCaller, namely RCallerPhp.
It uses a similar wrapper API to Java, between R and Php.

# Details #

Properties of current version
  * Passing Php arrays to R
  * Creating R source codes on the fly and run from Php
  * Handles the result of R program which sent from Php.
  * Creates, shows and saves plots that are not stored in htdoc or www root folder. Images are created in R, saved in temp directory, loaded as bytes and sent with img html tag with image source data. No user type html tags required. See the example in the link below.
  * LGPL!

# Tutorials #

## Calling R from PHP - RCallerPhp ##
http://stdioe.blogspot.com/search/label/rcallerphp