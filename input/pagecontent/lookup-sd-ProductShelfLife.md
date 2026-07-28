### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [ProductShelfLife](https://hl7.org/fhir/R5/ProductShelfLife.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the ProductShelfLife complex type.

A computable version of the following element information is available in: [R5ProductShelfLifeElementMapToR4](ConceptMap-R5-ProductShelfLife-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`ProductShelfLife`](https://hl7.org/fhir/R5/datatypes.html#ProductShelfLife) | [ProductShelfLife](https://hl7.org/fhir/R4/datatypes.html#ProductShelfLife) | FHIR R5 ComplexType `ProductShelfLife` is representable via extensions in FHIR R4.<br/>The root element `ProductShelfLife` is mapped to FHIR R4 `ProductShelfLife`. |
| [`ProductShelfLife.type`](https://hl7.org/fhir/R5/datatypes.html#ProductShelfLife) | [ProductShelfLife.type](https://hl7.org/fhir/R4/datatypes.html#ProductShelfLife) | Element `ProductShelfLife.type` is mapped to FHIR R4 element `ProductShelfLife.type` as `Equivalent`. |
| [`ProductShelfLife.period[x]`](https://hl7.org/fhir/R5/datatypes.html#ProductShelfLife) | [ProductShelfLife.period](https://hl7.org/fhir/R4/datatypes.html#ProductShelfLife)<br/>[Extension: ExtensionProductShelfLife_Period](StructureDefinition-ext-R5-ProductShelfLife.period.html) | Element `ProductShelfLife.period[x]` is mapped to FHIR R4 element `ProductShelfLife.period` as `RelatedTo`.<br/>The mappings for `ProductShelfLife.period[x]` do not cover the following types: string.<br/>The mappings for `ProductShelfLife.period[x]` do not cover the following types based on type expansion: value. |
| [`ProductShelfLife.specialPrecautionsForStorage`](https://hl7.org/fhir/R5/datatypes.html#ProductShelfLife) | [ProductShelfLife.specialPrecautionsForStorage](https://hl7.org/fhir/R4/datatypes.html#ProductShelfLife) | Element `ProductShelfLife.specialPrecautionsForStorage` is mapped to FHIR R4 element `ProductShelfLife.specialPrecautionsForStorage` as `Equivalent`. |
{: .grid }

