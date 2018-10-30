## CareConnect-MedicationStatement-1 ##

This MedicationStatement Resource is a record of a medication that is being consumed by a patient.

#### FHIR Assets ####

***Structure Definitions***


***MedicationStatement.additionalInstruction***

To be used as a string element for "Continue Indefinitely"; "Do not discontinue" & "Stop when course complete".


Any Duration instructions in MedicationStatement.effective[x].effectivePeriod (or in MedicationStatement.note as a degrade to text)




***Do not use***

The following elements are advised not to be used:

- MedicationStatement.dosage.maxDosePerAdministration
- MedicationStatement.dosage.maxDosePerLifetime
- MedicationStatement.dosage.rate