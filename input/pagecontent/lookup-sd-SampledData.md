### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [SampledData](https://hl7.org/fhir/R5/SampledData.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 complex type is represented in FHIR R4 via the SampledData complex type.

A computable version of the following element information is available in: [R5SampledDataElementMapToR4](ConceptMap-R5-SampledData-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`SampledData`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData](https://hl7.org/fhir/R4/datatypes.html#SampledData) | FHIR R5 ComplexType `SampledData` is representable via extensions in FHIR R4.<br/>The root element `SampledData` is mapped to FHIR R4 `SampledData`. |
| [`SampledData.origin`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.origin](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.origin` is mapped to FHIR R4 element `SampledData.origin` as `Equivalent`. |
| [`SampledData.interval`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.period](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.interval` is mapped to FHIR R4 element `SampledData.period` as `Equivalent`. |
| [`SampledData.intervalUnit`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [Extension: ExtensionSampledData_IntervalUnit](StructureDefinition-ext-R5-SampledData.intervalUnit.html) | Element `SampledData.intervalUnit` has a context of SampledData based on following the parent source element upwards and mapping to `SampledData`.<br/>Element `SampledData.intervalUnit` has no mapping targets in FHIR R4. Typically, this is because the element has been added (is a new element). |
| [`SampledData.factor`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.factor](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.factor` is mapped to FHIR R4 element `SampledData.factor` as `Equivalent`. |
| [`SampledData.lowerLimit`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.lowerLimit](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.lowerLimit` is mapped to FHIR R4 element `SampledData.lowerLimit` as `Equivalent`. |
| [`SampledData.upperLimit`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.upperLimit](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.upperLimit` is mapped to FHIR R4 element `SampledData.upperLimit` as `Equivalent`. |
| [`SampledData.dimensions`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.dimensions](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.dimensions` is mapped to FHIR R4 element `SampledData.dimensions` as `Equivalent`. |
| [`SampledData.codeMap`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [Extension: ExtensionSampledData_CodeMap](StructureDefinition-ext-R5-SampledData.codeMap.html) | Element `SampledData.codeMap` has a context of SampledData based on following the parent source element upwards and mapping to `SampledData`.<br/>Element `SampledData.codeMap` has no mapping targets in FHIR R4. Typically, this is because the element has been added (is a new element). |
| [`SampledData.offsets`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [Extension: ExtensionSampledData_Offsets](StructureDefinition-ext-R5-SampledData.offsets.html) | Element `SampledData.offsets` has a context of SampledData based on following the parent source element upwards and mapping to `SampledData`.<br/>Element `SampledData.offsets` has no mapping targets in FHIR R4. Typically, this is because the element has been added (is a new element). |
| [`SampledData.data`](https://hl7.org/fhir/R5/datatypes.html#SampledData) | [SampledData.data](https://hl7.org/fhir/R4/datatypes.html#SampledData) | Element `SampledData.data` is mapped to FHIR R4 element `SampledData.data` as `Equivalent`. |
{: .grid }

