# README

## Building

In order to build Kuromoji from source, please do as follows:
  
    % mvn clean package

   which downloads source dictionary data and builds Kuromoji with all dictionaries.

These additional build options are available:

* Use to `-DskipCompileDictionary` to not recompile dictionaries on each build
* Use to `-DskipDownloadDictionary` to not download source dictionaries on dictionary compile
  (can be used with with `-DskipCompileDictionary`)

# Contact us

Please feel free to contact us on kuromoji@atilika.com if you have any questions.

