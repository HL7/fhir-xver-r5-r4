### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Extension](https://hl7.org/fhir/R5/Extension.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Extension complex type.

A computable version of the following element information is available in: [R5ExtensionElementMapToR4](ConceptMap-R5-Extension-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Extension.url`](https://hl7.org/fhir/R5/extensibility.html#Extension) | [Extension.url](https://hl7.org/fhir/R4/extensibility.html#Extension) | Element `Extension.url` is mapped to FHIR R4 element `Extension.url` as `Equivalent`. |
| [`Extension.value[x]`](https://hl7.org/fhir/R5/extensibility.html#Extension) | [Extension.value[x]](https://hl7.org/fhir/R4/extensibility.html#Extension)<br/>[Extension: ExtensionExtension_Value](StructureDefinition-ext-R5-Extension.value.html) | Element `Extension.value[x]` is mapped to FHIR R4 element `Extension.value[x]` as `RelatedTo`.<br/>The mappings for `Extension.value[x]` do not cover the following types: Availability, CodeableReference, ExtendedContactDetail, RatioRange.<br/>The target context `Extension.value[x]` is a choice-type element and cannot directly hold extensions. The context is moved up to parent element `Extension`. |
{: .grid }

