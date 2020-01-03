# Ann-o-mate API

The endpoint for the ann-o-mate API is https://api.audioblast.org/annotations/. The API is used to provide a graphical frontend to the ann-o-mate project (https://audioblast.org/annotations), integration with R via the [warbleR](https://cran.r-project.org/package=warbleR) package, and is open for all developers to make use of. We would welcome notficication of notable implementations via ann-o-mate@googlegroups.com. 

The return is a JSON formatted object. No authentication is required.

Any field may be searched by modifying the URL request. Some examples are provided below.

### Searching for taxa
https://api.audioblast.org/annotations/?taxon=Gryllotalpa%20vineae (search for species)

https://api.audioblast.org/annotations/?taxon=Gryllotalpa%25 (search for all species in genus)

### Infrastructure
The project uses infrastructure provided by the [BioAcoustica](http://bio.acousti.ca) project.
