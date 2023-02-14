**Notice:** *As of the beginning of 2023 the Data Accessioner no longer has any active developers maintaining it. If you are interested in reviving the project, please contact [Seth Shaw](mailto:seth.e.shaw@gmail.com?subject=DataAccessioner%20Feedback%2FQuestion).*

The Data Accessioner (DA) is a simple tool, with an easy-to-use graphic interface, for migrating content between media while also:

  - creating and validating checksums,
  - gathering metadata (via FITS),
  - and compiling an XML metadata file (with the option to include Dublin Core metadata as of v 1.0) for future reference.

The DataAccessioner was built out of the need for a simple GUI interface to allow the Technical Services staff at the [David M. Rubenstein Rare Book & Manuscript Library at Duke University](http://library.duke.edu/rubenstein) an easy way of migrating data off disks and onto a file server for basic preservation, further appraisal, arrangement, & description. It also provides a way to integrate common metadata tools at the time of migration rather than after the fact. With a simplified interface and being written in Java it is intended to be easily adopted by smaller institutions with little or no IT staff support.

The very first version of the tool was created by Seth Shaw in the course of a week in early 2008 and, although usable, it was more of a proof-of-concept. In January 2009 the Data Accessioner was revisited with a revised architecture. Also, the metadata tool adapters and the custom metadata manager where extracted to be used as plugins.

Later versions (0.3.1 and 1.0.0-beta) were made possible by the [POWRR Project](http://digitalpowrr.niu.edu/). *As of these versions the Data Accessioner is no longer formally associated with the Duke University Archives or their parent organization.*

The latest update of Data Accessioner (1.1), released on Feb. 1, 2017, was done by Scott Prater for the Archives of the Episcopal Church.

## Additional Tools
For those of you who are uncomfortable reading (or transforming) the XML-based metadata files produced by the DA, take a look at the [Data Accessioner Metadata Transformer (XSLTProcessor)](https://github.com/DataAccessioner/XSLTProcessor).

[DA Fixity](https://github.com/DataAccessioner/dafixity) is a simple command line fixity checker that verifies the checksums of files managed by Data Accessioner.

