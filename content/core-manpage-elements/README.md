Core Manpage Elements
=====================
Here in this section we'll be covering some of the fundamental manpage elements that you'll probably end up using most often.

Document Date
-------------
Defines the date of authorship for the manpage and is defined by the `.Dd` macro. It accepts a singular date argument in the format of either _month d(d)?, yyyy_ (e.g. April 27, 2015 or June 7, 2016) or _$Mdocdate: month d(d)? yyyy $_

### Arguments
- **month**
  - January
  - February
  - March
  - April
  - May
  - June
  - July
  - August
  - September
  - October
  - November
  - December

### Syntax
- _month day, year_
- **$Mdocdate:** _month day year_ **$**

### Examples
- `.Dd June 07, 2016`
- `.Dd June 7, 2016`
- `.Dd $Mdocdate: June 7 2016 $`

Document Title
--------------
The title of the document as specified by the `.Dt` macro.

### Arguments
- **section**
  - 1 _(General Commands)_
  - 2 _(System Calls)_
  - 3 _(Library Functions)_
  - 3p _(Perl Library)_
  - 4 _(Device Drivers)_
  - 5 _(File Formats)_
  - 6 _(Games)_
  - 7 _(Miscellaneous Information)_
  - 8 _(System Manager's Manual)_
  - 9 _(Kernel Developer's Manual)_

### Syntax
- _TITLE section [arch]_

### Examples
- `.Dt MAN-TITLE 1`