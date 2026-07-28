### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Quantity](https://hl7.org/fhir/R5/Quantity.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Quantity complex type.

A computable version of the following element information is available in: [R5QuantityElementMapToR4](ConceptMap-R5-Quantity-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Quantity`](https://hl7.org/fhir/R5/datatypes.html#Quantity) | [Quantity](https://hl7.org/fhir/R4/datatypes.html#Quantity) | FHIR R5 ComplexType `Quantity` is representable via extensions in FHIR R4.<br/>The root element `Quantity` is mapped to FHIR R4 `Quantity`. |
| [`Quantity.value`](https://hl7.org/fhir/R5/datatypes.html#Quantity) | [Quantity.value](https://hl7.org/fhir/R4/datatypes.html#Quantity) | Element `Quantity.value` is mapped to FHIR R4 element `Quantity.value` as `Equivalent`. |
| [`Quantity.comparator`](https://hl7.org/fhir/R5/datatypes.html#Quantity) | [Quantity.comparator](https://hl7.org/fhir/R4/datatypes.html#Quantity)<br/>[Extension: ExtensionQuantity_Comparator](StructureDefinition-ext-R5-Quantity.comparator.html) | Element `Quantity.comparator` is mapped to FHIR R4 element `Quantity.comparator` as `SourceIsBroaderThanTarget`.<br/>The target context `Quantity.comparator` is a modifier element, so this extension does not need to be defined as a modifier. |
| [`Quantity.unit`](https://hl7.org/fhir/R5/datatypes.html#Quantity) | [Quantity.unit](https://hl7.org/fhir/R4/datatypes.html#Quantity) | Element `Quantity.unit` is mapped to FHIR R4 element `Quantity.unit` as `Equivalent`. |
| [`Quantity.system`](https://hl7.org/fhir/R5/datatypes.html#Quantity) | [Quantity.system](https://hl7.org/fhir/R4/datatypes.html#Quantity) | Element `Quantity.system` is mapped to FHIR R4 element `Quantity.system` as `Equivalent`. |
| [`Quantity.code`](https://hl7.org/fhir/R5/datatypes.html#Quantity) | [Quantity.code](https://hl7.org/fhir/R4/datatypes.html#Quantity) | Element `Quantity.code` is mapped to FHIR R4 element `Quantity.code` as `Equivalent`. |
{: .grid }

