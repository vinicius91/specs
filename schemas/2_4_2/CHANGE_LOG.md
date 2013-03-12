#Changes from 2.4.1 to 2.4.2
Planned entries that are in _italics_ have been completed and moved to the Committed section.


##Committed:
1. DvStringType should be the type for the 'units' attribute of DvCount, DvQuantity and DvRatio (numerator, denominator and ratio), 
thus allowing all of them to be defined either by a DvString (when the unit is not available in any terminology) or by DvCodedString 
(when the unit of measurement can be found in a terminology or any type of controlled vocabulary).

2. There should be a 'ratio_units' attribute in DvRatio. The probability that, in one of the zillions of healthcare domains, for a given concept expressed as a ratio, 
the numerator unit is 'A', the denominator unit is 'B', and the ratio unit is known as 'Omega_Z' instead of 'A/B', is not zero.

3. Rename the XMind template from CDD-(version).xmt  to MLHIM_Model-(version).xmt



##Planned:

1. _DvStringType should be the type for the 'units' attribute of DvCount, DvQuantity and DvRatio (numerator, denominator and ratio), 
thus allowing all of them to be defined either by a DvString (when the unit is not available in any terminology) or by DvCodedString 
(when the unit of measurement can be found in a terminology or any type of controlled vocabulary)._

2. _There should be a 'ratio_units' attribute in DvRatio. The probability that, in one of the zillions of healthcare domains, for a given concept expressed as a ratio, 
the numerator unit is 'A', the denominator unit is 'B', and the ratio unit is known as 'Omega_Z' instead of 'A/B', is not zero._

3. _Rename the XMind template from CDD-(version).xmt  to MLHIM_Model-(version).xmt_




