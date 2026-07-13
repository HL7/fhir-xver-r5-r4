### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [UsageContext](https://hl7.org/fhir/R5/UsageContext.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the UsageContext complex type.

A computable version of the following element information is available in: [R5UsageContextElementMapToR4](ConceptMap-R5-UsageContext-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`UsageContext`](https://hl7.org/fhir/R5/metadatatypes.html#UsageContext) | [UsageContext](https://hl7.org/fhir/R4/metadatatypes.html#UsageContext) | FHIR R5 ComplexType `UsageContext` is representable via extensions in FHIR R4.<br/>The root element `UsageContext` is mapped to FHIR R4 `UsageContext`. |
| [`UsageContext.code`](https://hl7.org/fhir/R5/metadatatypes.html#UsageContext) | [UsageContext.code](https://hl7.org/fhir/R4/metadatatypes.html#UsageContext) | Element `UsageContext.code` is mapped to FHIR R4 element `UsageContext.code` as `Equivalent`. |
| [`UsageContext.value[x]`](https://hl7.org/fhir/R5/metadatatypes.html#UsageContext) | [UsageContext.value[x]](https://hl7.org/fhir/R4/metadatatypes.html#UsageContext) | Element `UsageContext.value[x]` is mapped to FHIR R4 element `UsageContext.value[x]` as `Equivalent`.<br/>The target context `UsageContext.value[x]` is a choice-type element and cannot directly hold extensions. The context is moved up to parent element `UsageContext`. |
{: .grid }

