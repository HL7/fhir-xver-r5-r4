### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Duration](https://hl7.org/fhir/R5/Duration.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Duration complex type.

A computable version of the following element information is available in: [R5DurationElementMapToR4](ConceptMap-R5-Duration-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Duration`](https://hl7.org/fhir/R5/datatypes.html#Duration) | [Duration](https://hl7.org/fhir/R4/datatypes.html#Duration) | FHIR R5 ComplexType `Duration` is representable via extensions in FHIR R4.<br/>The root element `Duration` is mapped to FHIR R4 `Duration`. |
| [`Duration.value`](https://hl7.org/fhir/R5/datatypes.html#Duration) | [Duration.value](https://hl7.org/fhir/R4/datatypes.html#Duration) | Element `Duration.value` is mapped to FHIR R4 element `Duration.value` as `Equivalent`. |
| [`Duration.comparator`](https://hl7.org/fhir/R5/datatypes.html#Duration) | [Duration.comparator](https://hl7.org/fhir/R4/datatypes.html#Duration)<br/>[Extension: ExtensionDuration_Comparator](StructureDefinition-ext-R5-Duration.comparator.html) | Element `Duration.comparator` is mapped to FHIR R4 element `Duration.comparator` as `SourceIsBroaderThanTarget`.<br/>The target context `Duration.comparator` is a modifier element, so this extension does not need to be defined as a modifier. |
| [`Duration.unit`](https://hl7.org/fhir/R5/datatypes.html#Duration) | [Duration.unit](https://hl7.org/fhir/R4/datatypes.html#Duration) | Element `Duration.unit` is mapped to FHIR R4 element `Duration.unit` as `Equivalent`. |
| [`Duration.system`](https://hl7.org/fhir/R5/datatypes.html#Duration) | [Duration.system](https://hl7.org/fhir/R4/datatypes.html#Duration) | Element `Duration.system` is mapped to FHIR R4 element `Duration.system` as `Equivalent`. |
| [`Duration.code`](https://hl7.org/fhir/R5/datatypes.html#Duration) | [Duration.code](https://hl7.org/fhir/R4/datatypes.html#Duration) | Element `Duration.code` is mapped to FHIR R4 element `Duration.code` as `Equivalent`. |
{: .grid }

