### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Distance](https://hl7.org/fhir/R5/Distance.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Distance complex type.

A computable version of the following element information is available in: [R5DistanceElementMapToR4](ConceptMap-R5-Distance-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Distance`](https://hl7.org/fhir/R5/datatypes.html#Distance) | [Distance](https://hl7.org/fhir/R4/datatypes.html#Distance) | FHIR R5 ComplexType `Distance` is representable via extensions in FHIR R4.<br/>The root element `Distance` is mapped to FHIR R4 `Distance`. |
| [`Distance.value`](https://hl7.org/fhir/R5/datatypes.html#Distance) | [Distance.value](https://hl7.org/fhir/R4/datatypes.html#Distance) | Element `Distance.value` is mapped to FHIR R4 element `Distance.value` as `Equivalent`. |
| [`Distance.comparator`](https://hl7.org/fhir/R5/datatypes.html#Distance) | [Distance.comparator](https://hl7.org/fhir/R4/datatypes.html#Distance)<br/>[Extension: ExtensionDistance_Comparator](StructureDefinition-ext-R5-Distance.comparator.html) | Element `Distance.comparator` is mapped to FHIR R4 element `Distance.comparator` as `SourceIsBroaderThanTarget`.<br/>The target context `Distance.comparator` is a modifier element, so this extension does not need to be defined as a modifier. |
| [`Distance.unit`](https://hl7.org/fhir/R5/datatypes.html#Distance) | [Distance.unit](https://hl7.org/fhir/R4/datatypes.html#Distance) | Element `Distance.unit` is mapped to FHIR R4 element `Distance.unit` as `Equivalent`. |
| [`Distance.system`](https://hl7.org/fhir/R5/datatypes.html#Distance) | [Distance.system](https://hl7.org/fhir/R4/datatypes.html#Distance) | Element `Distance.system` is mapped to FHIR R4 element `Distance.system` as `Equivalent`. |
| [`Distance.code`](https://hl7.org/fhir/R5/datatypes.html#Distance) | [Distance.code](https://hl7.org/fhir/R4/datatypes.html#Distance) | Element `Distance.code` is mapped to FHIR R4 element `Distance.code` as `Equivalent`. |
{: .grid }

