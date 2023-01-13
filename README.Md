# Ann-o-mate API

The endpoint for the ann-o-mate API is https://api.audioblast.org/data/annomate/. The API is used to provide a graphical frontend to the ann-o-mate project (https://audioblast.org/?page=annomate), integration with R via the [warbleR](https://cran.r-project.org/package=warbleR) package, and is open for all developers to make use of. We would welcome notification of notable implementations via ann-o-mate@googlegroups.com. 

The return is a JSON formatted object. No authentication is required.

Any field may be searched by modifying the URL request. Some examples are provided below.

### Searching for taxa
https://api.audioblast.org/data/annomate/?taxon=Gryllotalpa%20vineae (search for species)

https://api.audioblast.org/data/annomate/?taxon=Gryllotalpa%25 (search for all species in genus)

### Infrastructure
The project uses infrastructure provided by the Natural History Museum, London.

Initial development was undertaken as part of the Leverhulme Trust funded Automated Acoustic Observaties project at the University of York.
