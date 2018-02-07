1. 
put these files into /html
rfTYPEAHEAD.htm
rfTYPEAHEAD_backup.htm
countries.json

or instead of copying the htm files change your template

add this line to your jsctempl.htm:
<link type="text/css" rel="stylesheet" href="css/typeahead.css" />
<script type="text/javascript" src="scripts/user.js"></script>
<script src="http://twitter.github.io/typeahead.js/releases/latest/typeahead.bundle.js"></script>

2. run the omnis library
TYPEAHEAD.lbs

3. if you or your OS overwrites rfTYPEAHEAD.htm use the copy in rfTYPEAHEAD_backup.htm


Please report any problem you might run into.

TIA, LArs
