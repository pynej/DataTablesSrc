# DataTables plug-in for jQuery - source repository

This git repository contains the un-built source files for DataTables - the table enhancing plug-in for jQuery. If you are looking to use DataTables, rather than to modify it, please use the built files in the build repo: [//github.com/DataTables/DataTables](//github.com/DataTables/DataTables). There are instructions there on how to use DataTables, and on the [DataTables site](//datatables.net) which contains the full documentation for DataTables.


## Why two repos

The source repo for DataTables is kept distinct from the built repo in order to provide separation between generated files and source files. The majority of the files in the DataTables built repo are generated by compiling source files from this repo, including:

* Main Javascript file - compiled from multiple individual Javascript files
* CSS files -compiled from SASS files
* Examples - compiled from a common data source data and HTML template files

This separation allows developers who simply want to use DataTables as is, to do so, while keeping the source repo clean of generated files.


## Building

DataTables can be built using the `make.sh` script in the `/scripts` directory of this repo. Simply check out the repo and run `make.sh --help` to get a full list of the options available for the build process. `make.sh build` will be the most common (with `make.sh build debug` available for quick testing - it skips the minification steps for speed).

A number of programs are required out your computer to be able to build DataTables:

* Bash
* PHP 5.4+
* JSHint 2.1+
* Closure compiler

A Mac or Linux environment is assumed in the build script - Windows builds are not currently supported.  


## Documentation

Full documentation of the DataTables options, API and pug-in interface are available on the [DataTables web-site](//datatables.net). The site also contains information on the wide variety of plug-ins that are available for DataTables, which can be used to enhance and customise your table even further.


## Support

Support for DataTables is available through the [DataTables forums](//datatables.net/forums) and [commercial support options](//datatables.net/support) are available.


## License

DataTables is release under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.
