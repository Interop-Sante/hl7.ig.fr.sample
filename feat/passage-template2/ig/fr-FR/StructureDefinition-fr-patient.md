# Patient français - Exemple d'IG Français v0.1.0

## : Patient français 

 
Description du patient français 

**Utilisations:**

* Exemples pour ce/t/te Profil: [Patient/frpatient-exemple](Patient-frpatient-exemple.md)

Vous pouvez également vérifier [les usages dans le FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.fhir.fr.example|current/StructureDefinition/fr-patient)

### 

 . 

*   
*   
*   
*   

#### Bindings terminologiques

#### Contraintes

** Résumé **

Must-Support : 1 élément

 **View** 

#### Bindings terminologiques

#### Contraintes

** Résumé **

Must-Support : 1 élément

 

 ,  



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "fr-patient",
  "url" : "http://hl7.fr/fhir/fr/example/StructureDefinition/fr-patient",
  "version" : "0.1.0",
  "name" : "FrPatientExample",
  "title" : "Patient français",
  "status" : "draft",
  "date" : "2026-06-29T09:35:10+00:00",
  "publisher" : "Interop'Santé",
  "contact" : [{
    "name" : "Interop'Santé",
    "telecom" : [{
      "system" : "url",
      "value" : "http://interopsante.org/"
    }]
  },
  {
    "name" : "InteropSanté",
    "telecom" : [{
      "system" : "email",
      "value" : "fhir@interopsante.org",
      "use" : "work"
    }]
  }],
  "description" : "Description du patient français",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "FRANCE"
    }]
  }],
  "fhirVersion" : "4.0.1",
  "mapping" : [{
    "identity" : "rim",
    "uri" : "http://hl7.org/v3",
    "name" : "RIM Mapping"
  },
  {
    "identity" : "cda",
    "uri" : "http://hl7.org/v3/cda",
    "name" : "CDA (R2)"
  },
  {
    "identity" : "w5",
    "uri" : "http://hl7.org/fhir/fivews",
    "name" : "FiveWs Pattern Mapping"
  },
  {
    "identity" : "v2",
    "uri" : "http://hl7.org/v2",
    "name" : "HL7 v2 Mapping"
  },
  {
    "identity" : "loinc",
    "uri" : "http://loinc.org",
    "name" : "LOINC code for the element"
  }],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Patient",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Patient",
  "derivation" : "constraint",
  "differential" : {
    "element" : [{
      "id" : "Patient",
      "path" : "Patient"
    },
    {
      "id" : "Patient.identifier",
      "path" : "Patient.identifier",
      "mustSupport" : true
    }]
  }
}

```
