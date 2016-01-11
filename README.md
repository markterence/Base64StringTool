
# Base64StringTool
=================

This is a personal tool i write to decode and encode a file into base64 string format.<br />
The program creates a text file containing the base64 string of the file<br />
<br /><br />
currently the base64 string format in the file has 2 parts<br />
the base64 string is the first part ofcourse<br />
and it is followed by a ',' comma (comma's are not part of the base64 string characters)<br />
next to the comma is the file extension of the file.<br />
example<br />
`<base64>,zip`<br /><br />

the tool reads the base64 and it will output the file along with the extension<br /><br />

i hope that i explained it very vell<br />

# Next on my list
* `<base64>,<file-extension>,<filename>`
* improve the compression of the output string(might switch to other fomats like Lempel-Ziv-Markov chain compression algorithm).
