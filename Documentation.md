In the 'lib' folder, you can find the JSDoc toolkit.
This toolkit is used to generate the documentation for the project.
The documentation is in the folder 'doc'.
Use a web browser to visualize 'index.html', the base file of the documentation.
To generate the documentation again, open a terminal and navigate to the folder
where the file 'Makefile' is. Then, run the command 'make'. This will generate
the documentation.

## Functions: ##

---

```
<static>  	YAML.eval(str) 
Parse a YAML file from a string.

<static>  	YAML.fromURL(src, ondone) 
Load and parse a YAML file from a URL.

<static>  	YAML.getErrors() 
Get errors found when parsing the last file.

<static>  	YAML.getProcessingTime() 
Get the time it took to parse the last file.
```

---


### Method Detail ###

---


`<static>` **YAML.eval(str)**

Parse a YAML file from a string.

_Parameters:_

{String} str
String with the YAML file contents.


---


`<static>` **YAML.fromURL(src, ondone)**

Load and parse a YAML file from a URL.

_Parameters:_

{String} src
URL from where to load the YAML file
{Function} ondone
Function that will be called when the file is parsed. The result is passed as an argument.


---


`<static>` **YAML.getErrors()**

Get errors found when parsing the last file.

_Returns:_

Errors found when parsing the last file.


---


`<static>` **YAML.getProcessingTime()**

Get the time it took to parse the last file.

_Returns:_

Time in milliseconds.