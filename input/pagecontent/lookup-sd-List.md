### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [List](https://hl7.org/fhir/R5/List.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

The FHIR R5 resource is represented in FHIR R4 via the List resource.

Note that there is a profile defined to simplify use of this cross-version resource representation:[Profile: List](StructureDefinition-profile-List.html)

A computable version of the following element information is available in: [R5ListElementMapToR4](ConceptMap-R5-List-element-map-to-R4.html)

| Source Element (FHIR R5) | Target(s) | Comments |
| -------------- | ---- | -------- |
| [`List`](https://hl7.org/fhir/R5/List.html#resource) |  |  |
| [`List.meta`](https://hl7.org/fhir/R5/List.html#resource) | [List.meta](https://hl7.org/fhir/R4/List.html#resource) | Element `List.meta` is mapped to FHIR R4 element `List.meta` as `Equivalent`. |
| [`List.implicitRules`](https://hl7.org/fhir/R5/List.html#resource) | [List.implicitRules](https://hl7.org/fhir/R4/List.html#resource) | Element `List.implicitRules` is mapped to FHIR R4 element `List.implicitRules` as `Equivalent`. |
| [`List.language`](https://hl7.org/fhir/R5/List.html#resource) | [List.language](https://hl7.org/fhir/R4/List.html#resource) | Element `List.language` is mapped to FHIR R4 element `List.language` as `Equivalent`. |
| [`List.text`](https://hl7.org/fhir/R5/List.html#resource) | [List.text](https://hl7.org/fhir/R4/List.html#resource) | Element `List.text` is mapped to FHIR R4 element `List.text` as `Equivalent`. |
| [`List.contained`](https://hl7.org/fhir/R5/List.html#resource) | [List.contained](https://hl7.org/fhir/R4/List.html#resource) | Element `List.contained` is mapped to FHIR R4 element `List.contained` as `Equivalent`. |
| [`List.identifier`](https://hl7.org/fhir/R5/List.html#resource) | [List.identifier](https://hl7.org/fhir/R4/List.html#resource) | Element `List.identifier` is mapped to FHIR R4 element `List.identifier` as `Equivalent`. |
| [`List.status`](https://hl7.org/fhir/R5/List.html#resource) | [List.status](https://hl7.org/fhir/R4/List.html#resource) | Element `List.status` is mapped to FHIR R4 element `List.status` as `Equivalent`. |
| [`List.mode`](https://hl7.org/fhir/R5/List.html#resource) | [List.mode](https://hl7.org/fhir/R4/List.html#resource) | Element `List.mode` is mapped to FHIR R4 element `List.mode` as `Equivalent`. |
| [`List.title`](https://hl7.org/fhir/R5/List.html#resource) | [List.title](https://hl7.org/fhir/R4/List.html#resource) | Element `List.title` is mapped to FHIR R4 element `List.title` as `Equivalent`. |
| [`List.code`](https://hl7.org/fhir/R5/List.html#resource) | [List.code](https://hl7.org/fhir/R4/List.html#resource) | Element `List.code` is mapped to FHIR R4 element `List.code` as `Equivalent`. |
| [`List.subject`](https://hl7.org/fhir/R5/List.html#resource) | [List.subject](https://hl7.org/fhir/R4/List.html#resource)<br/>[Extension: ExtensionList_Subject](StructureDefinition-ext-R5-List.subject.html)<br/>[Standard Extension: alternate-reference](http://hl7.org/fhir/StructureDefinition/alternate-reference) | Element `List.subject` allows multiple values in the source, but is mapped to an element that does not allow multiple values in the target.<br/>Element `List.subject` is mapped to FHIR R4 element `List.subject` as `SourceIsBroaderThanTarget`.<br/>The mappings for `List.subject` do not cover the following types based on type expansion: display, identifier, reference, type.<br/>The standard extension `alternate-reference` has been mapped as the representation of FHIR R5 element `List.subject` with unmapped reference targets: Resource. |
| [`List.encounter`](https://hl7.org/fhir/R5/List.html#resource) | [List.encounter](https://hl7.org/fhir/R4/List.html#resource) | Element `List.encounter` is mapped to FHIR R4 element `List.encounter` as `Equivalent`. |
| [`List.date`](https://hl7.org/fhir/R5/List.html#resource) | [List.date](https://hl7.org/fhir/R4/List.html#resource) | Element `List.date` is mapped to FHIR R4 element `List.date` as `Equivalent`. |
| [`List.source`](https://hl7.org/fhir/R5/List.html#resource) | [List.source](https://hl7.org/fhir/R4/List.html#resource)<br/>[Standard Extension: alternate-reference](http://hl7.org/fhir/StructureDefinition/alternate-reference) | Element `List.source` is mapped to FHIR R4 element `List.source` as `SourceIsBroaderThanTarget`.<br/>The standard extension `alternate-reference` has been mapped as the representation of FHIR R5 element `List.source` with unmapped reference targets: CareTeam, Organization, RelatedPerson. |
| [`List.orderedBy`](https://hl7.org/fhir/R5/List.html#resource) | [List.orderedBy](https://hl7.org/fhir/R4/List.html#resource) | Element `List.orderedBy` is mapped to FHIR R4 element `List.orderedBy` as `Equivalent`. |
| [`List.note`](https://hl7.org/fhir/R5/List.html#resource) | [List.note](https://hl7.org/fhir/R4/List.html#resource) | Element `List.note` is mapped to FHIR R4 element `List.note` as `Equivalent`. |
| [`List.entry`](https://hl7.org/fhir/R5/List.html#resource) | [List.entry](https://hl7.org/fhir/R4/List.html#resource) | Element `List.entry` is mapped to FHIR R4 element `List.entry` as `Equivalent`. |
| [`List.entry.flag`](https://hl7.org/fhir/R5/List.html#resource) | [List.entry.flag](https://hl7.org/fhir/R4/List.html#resource) | Element `List.entry.flag` is mapped to FHIR R4 element `List.entry.flag` as `Equivalent`. |
| [`List.entry.deleted`](https://hl7.org/fhir/R5/List.html#resource) | [List.entry.deleted](https://hl7.org/fhir/R4/List.html#resource) | Element `List.entry.deleted` is mapped to FHIR R4 element `List.entry.deleted` as `Equivalent`. |
| [`List.entry.date`](https://hl7.org/fhir/R5/List.html#resource) | [List.entry.date](https://hl7.org/fhir/R4/List.html#resource) | Element `List.entry.date` is mapped to FHIR R4 element `List.entry.date` as `Equivalent`. |
| [`List.entry.item`](https://hl7.org/fhir/R5/List.html#resource) | [List.entry.item](https://hl7.org/fhir/R4/List.html#resource) | Element `List.entry.item` is mapped to FHIR R4 element `List.entry.item` as `Equivalent`. |
| [`List.emptyReason`](https://hl7.org/fhir/R5/List.html#resource) | [List.emptyReason](https://hl7.org/fhir/R4/List.html#resource) | Element `List.emptyReason` is mapped to FHIR R4 element `List.emptyReason` as `Equivalent`. |
{: .grid }

