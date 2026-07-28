### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Age](https://hl7.org/fhir/R5/Age.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Age complex type.

A computable version of the following element information is available in: [R5AgeElementMapToR4](ConceptMap-R5-Age-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Age`](https://hl7.org/fhir/R5/datatypes.html#Age) | [Age](https://hl7.org/fhir/R4/datatypes.html#Age) | FHIR R5 ComplexType `Age` is representable via extensions in FHIR R4.<br/>The root element `Age` is mapped to FHIR R4 `Age`. |
| [`Age.value`](https://hl7.org/fhir/R5/datatypes.html#Age) | [Age.value](https://hl7.org/fhir/R4/datatypes.html#Age) | Element `Age.value` is mapped to FHIR R4 element `Age.value` as `Equivalent`. |
| [`Age.comparator`](https://hl7.org/fhir/R5/datatypes.html#Age) | [Age.comparator](https://hl7.org/fhir/R4/datatypes.html#Age)<br/>[Extension: ExtensionAge_Comparator](StructureDefinition-ext-R5-Age.comparator.html) | Element `Age.comparator` is mapped to FHIR R4 element `Age.comparator` as `SourceIsBroaderThanTarget`.<br/>The target context `Age.comparator` is a modifier element, so this extension does not need to be defined as a modifier. |
| [`Age.unit`](https://hl7.org/fhir/R5/datatypes.html#Age) | [Age.unit](https://hl7.org/fhir/R4/datatypes.html#Age) | Element `Age.unit` is mapped to FHIR R4 element `Age.unit` as `Equivalent`. |
| [`Age.system`](https://hl7.org/fhir/R5/datatypes.html#Age) | [Age.system](https://hl7.org/fhir/R4/datatypes.html#Age) | Element `Age.system` is mapped to FHIR R4 element `Age.system` as `Equivalent`. |
| [`Age.code`](https://hl7.org/fhir/R5/datatypes.html#Age) | [Age.code](https://hl7.org/fhir/R4/datatypes.html#Age) | Element `Age.code` is mapped to FHIR R4 element `Age.code` as `Equivalent`. |
{: .grid }

