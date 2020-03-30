# regex

## pyhton

import re

. any character
.* 0 or more characters
.+ 1 or more characters
? optional

^ start of input
$ end of input


ex: search for "yes"
s="y"
s="yes"
s="YES"
s="ummmmmm, yes"
if re.search("yes|y", s)
if re.search("y(es)?", s)
if re.search("y(es)?", s, re.IGNORECASE)
if re.search("^y(es)?$", s, re.IGNORECASE)


## sql
