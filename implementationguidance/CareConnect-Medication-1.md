## CareConnect-Medication-1 ##

This Medication Resource is primarily used for the identification and definition of a medication.

#### FHIR Assets ####

***Structure Definitions***
CareConnect-Medication-1: <a href="https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Medication-1"> https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Medication-1 </a>Extension-coding-sctdescid: <a href="https://fhir.hl7.org.uk/STU3/StructureDefinition/Extension-coding-sctdescid"> https://fhir.hl7.org.uk/STU3/StructureDefinition/Extension-coding-sctdescid </a>***ValueSets***ValueSet-CareConnect-MedicationCode-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-MedicationCode-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-MedicationCode-1 </a>ValueSet-CareConnect-MedicationForm-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-MedicationForm-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-CareConnect-MedicationForm-1 </a>#### Guidance ####

***Medication.code***

The Health & Social Care Act 2012 and the Standardisation Committee for Care Information (SCCI) standard requires the use of the Dictionary of medicines and devices (dm+d). This is a dictionary of descriptions and codes which represent medicines and devices in use across the NHS. The options for recording medication.code are as follows:

1) Secondary care systems send virtual therapeutic moiety (VTM) - GP systems are given "product" choices of equivalents.
2) Secondary care systems send product based virtual medicinal product (VMP) actual medicinal product (AMP) from pharmacy, and primary care handles directly.
3) Given the use of option 2), there might be VTMs sent and GP systems should be able to handle VTM conversions.
4) receiving system can deprecate to text if unable to process
5) VTM code sent along side AMP (as a mapping)

As an alternative, Medication.code.text can be used where dm+d is not in use.

