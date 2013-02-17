Example CCDs and descriptions of functionality.

1.  ccd-f9493153-8960-4974-8725-3bf824319ac8.xsd  
Test using a Cluster at the CCD.definition. Notice that is a rather complex process compared to many XML Schema implementations.

cluster1.xml shows that the DvString type requires one of the enumerated values and a datetime is required.

cluster2.xml shows that we have now set to require valid-time-begin for both the Gender and the temporal value.


2.   ccd-ab88e5b7-18e4-4074-a4e9-952379f7daa9.xsd 
Test choosing any datetime temporal variant.  
The CCD modeller will set the types not allowed to maxOccurs=0. Normally 'all allowed' will be set to maxOccurs=1 minOccurs=0.
If there is a need for a required entry, set minOccurs=1.  This does not preclude multiple dates being allowed by adjusting 
the minOccurs and maxOccurs to any desired value. Just note that minOccurs must be less than or equal to maxOCcurs. 

temporal-all.xml displays a sample of all possible types in one instance, normally not very useful in actual practice.
If you change any of the temporal elements to maxOccurs=0, you will now see that the instance file is no longer valid.

temporal-date-year_month.xml is a more practical example where the modeller might want a full date but allow for cases where 
only a month and year are available. The user interface (template) might be responsible for restricting the month-year if the full date is
entered. 
  

3.  ccd-ce2a1c62-37a3-4ff6-a7f3-6f1fef408d23.xsd
This is a 2.4.1 version of the Assessment Scales CCD created by Flavio L. Seixas for his PhD project.
See the 2.4.1 change notes (release_changes.pdf file).

AssesmentTest-required-entries.xml is a sample of the required elements for this CCD.

4.  ccd-122ea196-3460-46fe-996b-c265eef7d98d.xsd
This is a 2.4.1 version of the Clinical Diagnosis CCD created by Flavio L. Seixas for his PhD project.
See the 2.4.1 change notes (release_changes.pdf file).

ClinicalDiagnosis.xml is a sample of the required elements for this CCD.
