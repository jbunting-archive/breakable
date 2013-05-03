breakable
=========

This is a [breakable toy] that I decided to write to learn some new technologies and bone up on some rusty ones.

 [breakable toy]: http://redsquirrel.com/dave/work/a2j/patterns/BreakableToys.html

Myself
------

I think an important start is to detail where I'm coming from. During the day I program primarily in Java, 
with some dabbling in Groovy, Scala, and Python. In the past I have worked with html/css/javascript, C, 
and some embedded languages. I have played around with many more languages, but I'm not sure that they're 
really work mentioning here. Needless to say, most of my current expertise is tied to the JVM, and my
framework/community/ecosystem knowledge is almost all Java-centric. 

The Application
---------------

The goal is an application that allows for management of asset maintenance. The more concrete thought is a way
to track maintenance performed, remind about regularly scheduled required maintenance, and track usage for 
my vehicles.

My current thinking is the following steps:
 1. Write a [django] app to do this. (very simple, good UI isn't interesting to me at this phase)
 2. Use [django rest framework] to expose a rest api.  I might combine this with step 1.
 3. Write a single-page webapp using [AngularJS].
 4. Write an [android] client app.
 5. Depending on how #4 turns out, make sure that my android app is useful on both a phone and tablet.
 6. This one is a huge maybe, but maybe I'll get the bug to write an [iOS] app.

 [django]: https://www.djangoproject.com/
 [django rest framework]: http://django-rest-framework.org/
 [AngularJS]: http://angularjs.org/
 [android]: http://developer.android.com/guide/
 [iOS]: https://developer.apple.com/ios/

Working with all of the previously mentioned technologies will be pretty much new to me.  In addition, 
my python and git skills could use some enhancement. Also, I haven't used html/css/javascript in so long
that there's a fair amount of rust to brush off.  I might play with some of the new fun stuff happening
there like less, sass, and coffeescript.  Depends...  (although almost definitely I will use either less 
or sass...)


