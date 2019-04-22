# Saxon

This is a docker image containing [Saxon-HE](http://saxon.sourceforge.net/).

The following commands may be used:

* `xslt` - Triggering XSLT commands.
* `xquery` - Triggering Xquery commands.
* `saxon` - Used by `xslt` and `xquery` to trigger Saxon.

Example:

`docker run --rm -it -v $(pwd):/src klakegg/saxon xslt -s:input.xml -xsl:transformer.xslt -o:output.xml`

Please see the Saxon documentation for information about [XSLT commands](http://www.saxonica.com/documentation/#!using-xsl/commandline) and [XQuery commands](http://www.saxonica.com/documentation/#!using-xquery/commandline).