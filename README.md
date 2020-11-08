# SpecDocGenerater
Specefication document generater for VBA code

# Overview
* Python script to generate a specification document for VBA in markdown format
* 2 javascript modules are run via PyExecJS[^1]
* Thank you for the each modules in bellow
  * @x-vba [XDocGen](https://github.com/x-vba/xdocgen)
    * Javascript module to create a json data from VBA source code comment
  * @IonicaBizau [json2md](https://github.com/IonicaBizau/json2md)
    * Javascript module to convert the json data to markdown data

# Description
* Specification document content will be generate from the comments in VBA source code
* The document will be output by markdown format
* Python script will call 2 javascript modules
  * XDocGen
  * json2md
* Please follow the rules in [XDocGen homepage](https://x-vba.com/xdocgen/) for the format of VBA source code comments

[^1]: PyExecJS are already end of life (https://pypi.org/project/PyExecJS/)