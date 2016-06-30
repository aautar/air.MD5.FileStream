#air.MD5.FileStream

JavaScript functions to allow MD5 hash on an Adobe Air air.FileStream object. Uses and based upon the JavaScript MD5 implementation done by Paul Johnston.

## How to use

```
var filename = "somefile.txt";				
var inStream = new air.FileStream(); 

var file = new air.File(); 
file.url = "file:///" + filename;				

inStream.open(file, air.FileMode.READ); 

// Compute MD5 on file
var md5String = hex_md5_stream(inStream); 				
//

inStream.close(); 								
```
