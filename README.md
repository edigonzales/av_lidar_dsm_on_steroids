# DSM ON STEROIDS #

See [here](http://rapidlasso.com/2013/11/03/grafcan-launches-dsm-on-steroids/) and [here](http://visor.grafcan.es/visorweb/default.php?svc=svcMTL&lat=28.1997572&lng=-16.7887721&zoom=9&lang=en) for credits.

This README would normally document whatever steps are necessary to get your application up and running.
 
### Get the data ###

```
#!bash
wget -r -nH -np -R index.html --cut-dirs=5 http://maps.zh.ch/download/hoehen/2014/dtm/tif/
wget -r -nH -np -R index.html --cut-dirs=5 http://maps.zh.ch/download/hoehen/2014/dom/tif/
```

There is already a tileindex shapefile and a vrt file which are also downloaded by `wget`.


### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact