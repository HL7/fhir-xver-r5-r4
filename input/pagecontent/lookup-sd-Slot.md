### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Slot](https://hl7.org/fhir/R5/Slot.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 resource is represented in FHIR R4 via the Slot resource.

Note that there is a profile defined to simplify use of this cross-version resource representation:[Profile: Slot](StructureDefinition-profile-Slot.html)

A computable version of the following element information is available in: [R5SlotElementMapToR4](ConceptMap-R5-Slot-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Slot`](https://hl7.org/fhir/R5/Slot.html#resource) |  |  |
| [`Slot.meta`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.meta](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.meta` is mapped to FHIR R4 element `Slot.meta` as `Equivalent`. |
| [`Slot.implicitRules`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.implicitRules](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.implicitRules` is mapped to FHIR R4 element `Slot.implicitRules` as `Equivalent`. |
| [`Slot.language`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.language](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.language` is mapped to FHIR R4 element `Slot.language` as `Equivalent`. |
| [`Slot.text`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.text](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.text` is mapped to FHIR R4 element `Slot.text` as `Equivalent`. |
| [`Slot.contained`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.contained](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.contained` is mapped to FHIR R4 element `Slot.contained` as `Equivalent`. |
| [`Slot.identifier`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.identifier](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.identifier` is mapped to FHIR R4 element `Slot.identifier` as `Equivalent`. |
| [`Slot.serviceCategory`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.serviceCategory](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.serviceCategory` is mapped to FHIR R4 element `Slot.serviceCategory` as `Equivalent`. |
| [`Slot.serviceType`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.serviceType](https://hl7.org/fhir/R4/Slot.html#resource)<br/>[Extension: ExtensionSlot_ServiceType](StructureDefinition-ext-R5-Slot.serviceType.html) | Element `Slot.serviceType` is mapped to FHIR R4 element `Slot.serviceType` as `SourceIsBroaderThanTarget`.<br/>The mappings for `Slot.serviceType` do not cover the following types: CodeableReference.<br/>The mappings for `Slot.serviceType` do not cover the following types based on type expansion: reference. |
| [`Slot.specialty`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.specialty](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.specialty` is mapped to FHIR R4 element `Slot.specialty` as `Equivalent`. |
| [`Slot.appointmentType`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.appointmentType](https://hl7.org/fhir/R4/Slot.html#resource)<br/>[Extension: ExtensionSlot_AppointmentType](StructureDefinition-ext-R5-Slot.appointmentType.html) | Element `Slot.appointmentType` allows multiple values in the source, but is mapped to an element that does not allow multiple values in the target.<br/>Element `Slot.appointmentType` is mapped to FHIR R4 element `Slot.appointmentType` as `SourceIsBroaderThanTarget`. |
| [`Slot.schedule`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.schedule](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.schedule` is mapped to FHIR R4 element `Slot.schedule` as `Equivalent`. |
| [`Slot.status`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.status](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.status` is mapped to FHIR R4 element `Slot.status` as `Equivalent`. |
| [`Slot.start`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.start](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.start` is mapped to FHIR R4 element `Slot.start` as `Equivalent`. |
| [`Slot.end`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.end](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.end` is mapped to FHIR R4 element `Slot.end` as `Equivalent`. |
| [`Slot.overbooked`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.overbooked](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.overbooked` is mapped to FHIR R4 element `Slot.overbooked` as `Equivalent`. |
| [`Slot.comment`](https://hl7.org/fhir/R5/Slot.html#resource) | [Slot.comment](https://hl7.org/fhir/R4/Slot.html#resource) | Element `Slot.comment` is mapped to FHIR R4 element `Slot.comment` as `Equivalent`. |
{: .grid }

