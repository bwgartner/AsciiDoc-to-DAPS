# TIPS

Some helpful tips/guidance to get started with AsciiDoc ( https://github.com/asciidoc/asciidoc ) and leverage DAPS ( https://github.com/openSUSE/daps )

* example directory structure
~~~text
 ./DC-sample (DAPS configuration file, referencing which AsciiDoc file)
 ./adoc
       /sample.adoc			(example AsciiDoc file)
       /sample-include.adoc		(example AsciiDoc file to include)
       /sample_vars.adoc		(example AsciiDoc file for variables)
 ./images
         /src
             /png
                 /sample.png	(example image)
             /svg
                 /sample.svg	(example image, preferred format)
 ./build				(created during DAPS output generation)
~~~
