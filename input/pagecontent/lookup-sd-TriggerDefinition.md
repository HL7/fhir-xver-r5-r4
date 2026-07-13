### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [TriggerDefinition](https://hl7.org/fhir/R5/TriggerDefinition.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the TriggerDefinition complex type.

A computable version of the following element information is available in: [R5TriggerDefinitionElementMapToR4](ConceptMap-R5-TriggerDefinition-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`TriggerDefinition`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [TriggerDefinition](https://hl7.org/fhir/R4/metadatatypes.html#TriggerDefinition) | FHIR R5 ComplexType `TriggerDefinition` is representable via extensions in FHIR R4.<br/>The root element `TriggerDefinition` is mapped to FHIR R4 `TriggerDefinition`. |
| [`TriggerDefinition.type`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [TriggerDefinition.type](https://hl7.org/fhir/R4/metadatatypes.html#TriggerDefinition) | Element `TriggerDefinition.type` is mapped to FHIR R4 element `TriggerDefinition.type` as `Equivalent`. |
| [`TriggerDefinition.name`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [TriggerDefinition.name](https://hl7.org/fhir/R4/metadatatypes.html#TriggerDefinition) | Element `TriggerDefinition.name` is mapped to FHIR R4 element `TriggerDefinition.name` as `Equivalent`. |
| [`TriggerDefinition.code`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [Extension: ExtensionTriggerDefinition_Code](StructureDefinition-ext-R5-TriggerDefinition.code.html) | Element `TriggerDefinition.code` has a context of TriggerDefinition based on following the parent source element upwards and mapping to `TriggerDefinition`.<br/>Element `TriggerDefinition.code` has no mapping targets in FHIR R4. Typically, this is because the element has been added (is a new element). |
| [`TriggerDefinition.subscriptionTopic`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [Extension: ExtensionTriggerDefinition_SubscriptionTopic](StructureDefinition-ext-R5-TriggerDefinition.subscriptionTopic.html) | Element `TriggerDefinition.subscriptionTopic` has a context of TriggerDefinition based on following the parent source element upwards and mapping to `TriggerDefinition`.<br/>Element `TriggerDefinition.subscriptionTopic` has no mapping targets in FHIR R4. Typically, this is because the element has been added (is a new element). |
| [`TriggerDefinition.timing[x]`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [TriggerDefinition.timing[x]](https://hl7.org/fhir/R4/metadatatypes.html#TriggerDefinition) | Element `TriggerDefinition.timing[x]` is mapped to FHIR R4 element `TriggerDefinition.timing[x]` as `RelatedTo`.<br/>The target context `TriggerDefinition.timing[x]` is a choice-type element and cannot directly hold extensions. The context is moved up to parent element `TriggerDefinition`. |
| [`TriggerDefinition.data`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [TriggerDefinition.data](https://hl7.org/fhir/R4/metadatatypes.html#TriggerDefinition) | Element `TriggerDefinition.data` is mapped to FHIR R4 element `TriggerDefinition.data` as `Equivalent`. |
| [`TriggerDefinition.condition`](https://hl7.org/fhir/R5/metadatatypes.html#TriggerDefinition) | [TriggerDefinition.condition](https://hl7.org/fhir/R4/metadatatypes.html#TriggerDefinition) | Element `TriggerDefinition.condition` is mapped to FHIR R4 element `TriggerDefinition.condition` as `Equivalent`. |
{: .grid }

