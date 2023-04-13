# Search Engine using C++
 > This is a simple search engine implemented in C++. The search engine allows users to search for keywords in a set of documents, and returns a list of documents that contain those keywords.


## Requirements

This is Linux program, but it is based on platform undependable libraries, so can be compiled under each system that supports analogs of following packages.
 
The program requires analogs of the packages in you system, that are listed below.

* `Qt4-Core`
* `Qt4-WebKit`
* `Qt4-Gui`
* `libXML`
* `R-core`
* `XML R-package`

To install Qt libraries and libXML you can use packages from your repository.
To install XML you can type `install.packages("XML")` in the R console. Be sure that R can connect to the CRAN-repository.

## Install

* Make sure to clone the repository first using `git clone`

To install program you should run `build.sh` script in the root of package or something like below:   

    mkdir bin &&
    mkdir bin/gui &&
    cd bin/gui &&
    qmake ../src/gui &&
    make && make clean

The program will be compiled into `bin/gui/gui`.

### Engines

This supports two basic engines: *Google Scholar* and *Microsoft Academic Search*.

Summary, engines:

* Google Scholar;
* Microsoft Academic Search;
* Google Scholar + Microsoft Academic Search;
* Fake Single Test engine;
* Fake Test multi-engine.

### Search modes

There 4 modes of search:

* Single person and single search engine;
* Single person and multi-engine;
* Many persons and single engine;
* Many persons and multi-engine.


