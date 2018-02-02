## CareConnect-PractitionerRole-1 ##

The PractitionerRole resource represents a specific set of Roles/Locations/specialties/services that a practitioner may perform at an organization for a period of time.

#### FHIR Assets ####

***Structure Definitions***
CareConnect-PractitionerRole-1: <a href="https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-PractitionerRole-1"> https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-PractitionerRole-1 </a>

***ValueSets***

ValueSet-CareConnect-SDSJobRoleName-1: <a href="https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-SDSJobRoleName-1 "> https://fhir.hl7.org.uk/STU3/ValueSet/CareConnect-SDSJobRoleName-1  </a>
***CodeSystems***CodeSystem-CareConnect-SDSJobRoleName-1: <a href="https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-SDSJobRoleName-1"> https://fhir.hl7.org.uk/STU3/CodeSystem/CareConnect-SDSJobRoleName-1 </a>

#### Guidance ####

***Identifier***

When to use Practitioner.identifier vs PractitionerRole.identifier:

It is suggested that Practitioner.identifier is used for identifiers that are recognised by Royal Colleges (for example a General Medical Council (GMC) Code), and PractitionerRole.identifier is used for the identification of a Practitioner working for an Organisation (such as a SmartCard identifier).
