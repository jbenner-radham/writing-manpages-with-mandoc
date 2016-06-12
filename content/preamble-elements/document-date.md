Document Date
=============
Defines the date of authorship for the manpage and is defined by the `.Dd` macro. It accepts a singular date argument in the format of either _month d(d)?, yyyy_ (e.g. April 27, 2015 or June 7, 2016) or _$Mdocdate: month d(d)? yyyy $_

Arguments
---------
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

Syntax
------
- **`.Dt`**_`month day, year`_
- **`.Dt $Mdocdate:`**_` month day year `_**`$`**

Examples
--------
- `.Dd June 07, 2016`
- `.Dd June 7, 2016`
- `.Dd $Mdocdate: June 7 2016 $`
