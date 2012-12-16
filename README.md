# CADL

Common API Description Language

__*One language to rule them all*__

## Yet another description language?

Hey there are multiple languages in the wild to describe apis or webservices.

* http://www.w3.org/TR/wsdl20/
* http://www.w3.org/Submission/wadl/
* http://www.w3.org/2005/Incubator/usdl/
* and so on..

And always remeber: http://xkcd.com/927/ 

![how standards proliferate](http://imgs.xkcd.com/comics/standards.png)

## So why CADL?

Well we:

* create MVC architectures
* design our applications to be accessable via multiple protocols or even by CLI
* have clear validation rules what kind of information will be accepted
* return various types of informations and various types of contents 
* have to deal with privacy and data protection issues 
* have to deal diffrent protection levels for APIs and informations
* need to deal with licence and copyright foo
* have to deal with backwards compatibility / diffrent api versions
* have a multi langual world
* have artificial borders and laws that prevent us from dealing with some regions
* sometimes need usage constraints like intranet only
* maybe want money if somebody use our services
* need so much more information than just a bunch of rudimental tech information
* sometimes just need information how to deal with that fkn (vendor) system
* do stuff that has so much more impact than just beeing some piece of technology

The technology part is only one part of our work.
Regarding to the actual success stories or the absolutly crazy legal situation it's even maybe even a minor part
of the big picture. 

So if we want to descripe an API but use a languages that only describes the
technical structure don't we forget the major part of that API? 

CADL provides a way to describe (almost) every aspect of your API in one format in
a lightweigt JSON format.





