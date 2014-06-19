IonicTestExample
================

This is an example for the ionic learn article [link needed]();

# Usage
~~~
npm install -g protractor
web-driver update
~~~


Clone this into a repository

~~~
cd IonicTestExample
~~~

###### *To run this example*
~~~
npm install -g http-server
http-server app/
protractor tests/protractor.config.js
~~~

###### *to run this with an ionic app*
replace app/* with an ionic app or run this app with 

Change
~~~
ptor.ignoreSynchronization = true;
~~~

to:

~~~
ptor.ignoreSynchronization = false;
~~~

in protractor.config.js, then 

~~~
ionic serve
protractor tests/protractor.config.js
~~~
