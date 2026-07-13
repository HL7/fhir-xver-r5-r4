### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Count](https://hl7.org/fhir/R5/Count.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Count complex type.

A computable version of the following element information is available in: [R5CountElementMapToR4](ConceptMap-R5-Count-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Count`](https://hl7.org/fhir/R5/datatypes.html#Count) | [Count](https://hl7.org/fhir/R4/datatypes.html#Count) | FHIR R5 ComplexType `Count` is representable via extensions in FHIR R4.<br/>The root element `Count` is mapped to FHIR R4 `Count`. |
| [`Count.value`](https://hl7.org/fhir/R5/datatypes.html#Count) | [Count.value](https://hl7.org/fhir/R4/datatypes.html#Count) | Element `Count.value` is mapped to FHIR R4 element `Count.value` as `Equivalent`. |
| [`Count.comparator`](https://hl7.org/fhir/R5/datatypes.html#Count) | [Count.comparator](https://hl7.org/fhir/R4/datatypes.html#Count)<br/>[Extension: ExtensionCount_Comparator](StructureDefinition-ext-R5-Count.comparator.html) | Element `Count.comparator` is mapped to FHIR R4 element `Count.comparator` as `SourceIsBroaderThanTarget`.<br/>The target context `Count.comparator` is a modifier element, so this extension does not need to be defined as a modifier. |
| [`Count.unit`](https://hl7.org/fhir/R5/datatypes.html#Count) | [Count.unit](https://hl7.org/fhir/R4/datatypes.html#Count) | Element `Count.unit` is mapped to FHIR R4 element `Count.unit` as `Equivalent`. |
| [`Count.system`](https://hl7.org/fhir/R5/datatypes.html#Count) | [Count.system](https://hl7.org/fhir/R4/datatypes.html#Count) | Element `Count.system` is mapped to FHIR R4 element `Count.system` as `Equivalent`. |
| [`Count.code`](https://hl7.org/fhir/R5/datatypes.html#Count) | [Count.code](https://hl7.org/fhir/R4/datatypes.html#Count) | Element `Count.code` is mapped to FHIR R4 element `Count.code` as `Equivalent`. |
{: .grid }

