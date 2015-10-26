<img src='https://raw.githubusercontent.com/pedro-ramirez-suarez/rawtemplate/master/rawlogo1.png' style='heigth:200px'/> 
## Rapid Application Wireframe

### Approach

The RAW framework was developed with the Database First approach in mind, we encourage a good and clean design of the database, we think that the code first approach is good for quick creation of prototypes but not well suited for existing applications, applications that require complex schemas and most important, code first approach wastes DB computational power and features.  
Continuously testing is also part of the framework, any change performed and saved in the code automatically runs all the unit tests and automatically deploys the new version to IIS Express, if you need more control to debug               the code you can run the website directly from visual studio.
### Technology stack
The framework was built with C# and Ruby, the framework generates code for  Asp.Net MVC 5 applications, it generates models, repositores, controllers and views, but most important is how the code is generated, to generate the code, the framework uses templates so it's  easy  to modify them and suit your needs. 

These are the libraries used by the code generated by the RAW framework:

- Needletail DataAccess
- jQuery
- Knockout JS
- Require JS
- Boostrap+ Bootstrap validator
- NSpec+ Spec Watcher

### Pre requisites
Before you can start coding and generating code with the framework, here is a list of prerequisites that you need.

The framework was built with C# and Ruby, the framework generates code for Asp.Net MVC 5 applications, it generates models, repositores, controllers and views, but most important is how the code is generated, to generate the code, the framework uses templates so it's  easy  to modify them and suit your needs. 

#### Requirements

These are the libraries used by the code generated by the RAW framework:

- IIS Express
- [Ruby 2+ 32bit](https://www.ruby-lang.org/en/downloads/ "Download Ruby"), also compatible with Ruby 1.9.2
- rawinit gem (install it if you don't have it like this `gem install rawinit`)
- rawf gem (install it if you don't have it like this `gem install rawf`)
- Nokogiri gem (install it if you don't have it like this `gem install nokogiri`); If you have problems installing nokigiri, it's very likely that you have a buggy gem version, update your gems and try again.
- Warmup gem (install it if you don't have it like this `gem install warmup`)
- Jasmine (install it if you don't have it like this `gem install jasmine`)
- [Growl](http://growl.info/downloads "Download Growl") (to continuously check the status of the unit tests)

### Notes

If you're sharing your project with the world please considere to include the badge [![RAW Framework](https://img.shields.io/badge/RAW-Framework-blue.svg)](
https://github.com/pedro-ramirez-suarez/rawtemplate)
