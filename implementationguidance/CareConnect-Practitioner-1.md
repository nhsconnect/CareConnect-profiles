## CareConnect-Practitioner-1 ##

The Practitioner resource represents the healthcare professional directly or indirectly involved in the provision of healthcare related services.

#### FHIR Assets ####

***Structure Definitions***
CareConnect-Practitioner-1: <a href="https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1"> https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1 </a>
Extension-CareConnect-NHSCommunication-1: <a href="https://fhir.hl7.org.uk/STU3/StructureDefinition/Extension-CareConnect-NHSCommunication-1"> https://fhir.hl7.org.uk/STU3/StructureDefinition/Extension-CareConnect-NHSCommunication-1 </a>


***ValueSets***

ValueSet-CareConnect-AdministrativeGender-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-AdministrativeGender-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-AdministrativeGender-1 </a>

ValueSet-CareConnect-NHSDataDictionary-PersonStatedGender-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-NHSDataDictionary-PersonStatedGender-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-NHSDataDictionary-PersonStatedGender-1 </a>

ValueSet-CareConnect-HumanLanguage-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-HumanLanguage-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-HumanLanguage-1 </a>

ValueSet-CareConnect-LanguageAbilityMode-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-LanguageAbilityMode-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-LanguageAbilityMode-1 </a>

ValueSet-CareConnect-LanguageAbilityProficiency-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-LanguageAbilityProficiency-1"> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-LanguageAbilityProficiency-1 </a>
***CodeSystems***CodeSystem-CareConnect-HumanLanguage-1: <a href="https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-HumanLanguage-1"> https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-HumanLanguage-1 </a>CodeSystem-CareConnect-LanguageAbilityMode-1: <a href="https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-LanguageAbilityMode-1"> https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-LanguageAbilityMode-1 </a>CodeSystem-CareConnect-LanguageAbilityProficiency-1: <a href="https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-LanguageAbilityProficiency-1"> https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-LanguageAbilityProficiency-1 </a>

***ConceptMaps***

ConceptMap-CareConnect-AdministrativeGender-1: <a href="https://fhir.hl7.org.uk/STU3/ConceptMap/CareConnect-AdministrativeGender-1"> https://fhir.hl7.org.uk/STU3/ConceptMap/CareConnect-AdministrativeGender-1 </a>



#### Guidance ####

***Identifier***

When to use Practitioner.identifier vs PractitionerRole.identifier:

It is suggested that Practitioner.identifier is used for identifiers that are recognised by Royal Colleges (for example a General Medical Council (GMC) Code), and PractitionerRole.identifier is used for the identification of a Practitioner working for an Organisation (such as a SmartCard identifier).


***Identifier.system***

The following identifier system uri's should be used where official identifiers are being used:

Organization | URI
--- | --- 
General Medical Council (GMC) | https://fhir.hl7.org.uk/Id/gmc-number
Nurse & Midwifery Council (NMC) | https://fhir.hl7.org.uk/Id/nmc-number
Health & Care Profession Council | https://fhir.hl7.org.uk/Id/hcpc-number