### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Annotation](https://hl7.org/fhir/R5/Annotation.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Annotation complex type.

A computable version of the following element information is available in: [R5AnnotationElementMapToR4](ConceptMap-R5-Annotation-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Annotation`](https://hl7.org/fhir/R5/datatypes.html#Annotation) | [Annotation](https://hl7.org/fhir/R4/datatypes.html#Annotation) | FHIR R5 ComplexType `Annotation` is representable via extensions in FHIR R4.<br/>The root element `Annotation` is mapped to FHIR R4 `Annotation`. |
| [`Annotation.author[x]`](https://hl7.org/fhir/R5/datatypes.html#Annotation) | [Annotation.author[x]](https://hl7.org/fhir/R4/datatypes.html#Annotation)<br/>[Standard Extension: alternate-reference](http://hl7.org/fhir/StructureDefinition/alternate-reference) | Element `Annotation.author[x]` is mapped to FHIR R4 element `Annotation.author[x]` as `SourceIsBroaderThanTarget`.<br/>The standard extension `alternate-reference` has been mapped as the representation of FHIR R5 element `Annotation.author[x]` with unmapped reference targets: PractitionerRole.<br/>Source element `Annotation.author[x]` has unmapped reference types. While the target element `Annotation.author[x]` is a choice type and does not allow extensions, the `alternate-reference` extension can be applied to Reference values within it. |
| [`Annotation.time`](https://hl7.org/fhir/R5/datatypes.html#Annotation) | [Annotation.time](https://hl7.org/fhir/R4/datatypes.html#Annotation) | Element `Annotation.time` is mapped to FHIR R4 element `Annotation.time` as `Equivalent`. |
| [`Annotation.text`](https://hl7.org/fhir/R5/datatypes.html#Annotation) | [Annotation.text](https://hl7.org/fhir/R4/datatypes.html#Annotation) | Element `Annotation.text` is mapped to FHIR R4 element `Annotation.text` as `Equivalent`. |
{: .grid }

