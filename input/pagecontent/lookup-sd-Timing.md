### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Timing](https://hl7.org/fhir/R5/Timing.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the Timing complex type.

A computable version of the following element information is available in: [R5TimingElementMapToR4](ConceptMap-R5-Timing-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`Timing`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing](https://hl7.org/fhir/R4/datatypes.html#Timing) | FHIR R5 ComplexType `Timing` is representable via extensions in FHIR R4.<br/>The root element `Timing` is mapped to FHIR R4 `Timing`. |
| [`Timing.event`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.event](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.event` is mapped to FHIR R4 element `Timing.event` as `Equivalent`. |
| [`Timing.repeat`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat` is mapped to FHIR R4 element `Timing.repeat` as `Equivalent`. |
| [`Timing.repeat.bounds[x]`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.bounds[x]](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.bounds[x]` is mapped to FHIR R4 element `Timing.repeat.bounds[x]` as `Equivalent`.<br/>The target context `Timing.repeat.bounds[x]` is a choice-type element and cannot directly hold extensions. The context is moved up to parent element `Timing.repeat`. |
| [`Timing.repeat.count`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.count](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.count` is mapped to FHIR R4 element `Timing.repeat.count` as `Equivalent`. |
| [`Timing.repeat.countMax`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.countMax](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.countMax` is mapped to FHIR R4 element `Timing.repeat.countMax` as `Equivalent`. |
| [`Timing.repeat.duration`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.duration](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.duration` is mapped to FHIR R4 element `Timing.repeat.duration` as `Equivalent`. |
| [`Timing.repeat.durationMax`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.durationMax](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.durationMax` is mapped to FHIR R4 element `Timing.repeat.durationMax` as `Equivalent`. |
| [`Timing.repeat.durationUnit`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.durationUnit](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.durationUnit` is mapped to FHIR R4 element `Timing.repeat.durationUnit` as `Equivalent`. |
| [`Timing.repeat.frequency`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.frequency](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.frequency` is mapped to FHIR R4 element `Timing.repeat.frequency` as `Equivalent`. |
| [`Timing.repeat.frequencyMax`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.frequencyMax](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.frequencyMax` is mapped to FHIR R4 element `Timing.repeat.frequencyMax` as `Equivalent`. |
| [`Timing.repeat.period`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.period](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.period` is mapped to FHIR R4 element `Timing.repeat.period` as `Equivalent`. |
| [`Timing.repeat.periodMax`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.periodMax](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.periodMax` is mapped to FHIR R4 element `Timing.repeat.periodMax` as `Equivalent`. |
| [`Timing.repeat.periodUnit`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.periodUnit](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.periodUnit` is mapped to FHIR R4 element `Timing.repeat.periodUnit` as `Equivalent`. |
| [`Timing.repeat.dayOfWeek`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.dayOfWeek](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.dayOfWeek` is mapped to FHIR R4 element `Timing.repeat.dayOfWeek` as `Equivalent`. |
| [`Timing.repeat.timeOfDay`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.timeOfDay](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.timeOfDay` is mapped to FHIR R4 element `Timing.repeat.timeOfDay` as `Equivalent`. |
| [`Timing.repeat.when`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.when](https://hl7.org/fhir/R4/datatypes.html#Timing)<br/>[Extension: ExtensionTiming_Repeat_When](StructureDefinition-ext-R5-Timing.rep.when.html) | Element `Timing.repeat.when` is mapped to FHIR R4 element `Timing.repeat.when` as `SourceIsBroaderThanTarget`. |
| [`Timing.repeat.offset`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.repeat.offset](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.repeat.offset` is mapped to FHIR R4 element `Timing.repeat.offset` as `Equivalent`. |
| [`Timing.code`](https://hl7.org/fhir/R5/datatypes.html#Timing) | [Timing.code](https://hl7.org/fhir/R4/datatypes.html#Timing) | Element `Timing.code` is mapped to FHIR R4 element `Timing.code` as `Equivalent`. |
{: .grid }

