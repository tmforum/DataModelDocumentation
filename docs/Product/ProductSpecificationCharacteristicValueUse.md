# Product specification characteristic value use Data Model

## Domain

The  schema is part of the  Domain

## Description

A use of the ProductSpecificationCharacteristicValue by a ProductOffering to which additional properties (attributes) apply or override the properties of similar properties contained in ProductSpecificationCharacteristicValue. It should be noted that characteristics which their value(s) addressed by this object must exist in corresponding product specification. The available characteristic values for a ProductSpecificationCharacteristic in a Product specification can be modified at the ProductOffering level. For example, a characteristic &#x27;Color&#x27; might have values White, Blue, Green, and Red. But, the list of values can be restricted to e.g. White and Blue in an associated product offering. It should be noted that the list of values in &#x27;ProductSpecificationCharacteristicValueUse&#x27; is a strict subset of the list of values as defined in the corresponding product specification characteristics.

## Data model

A JSON Schema corresponding to this data model can be found
[here](https://github.com/tmforum-rand/schemas/blob/master/Product/ProductSpecificationCharacteristicValueUse.schema.json).

No Data Model yet

## Schema Relationships

### This schema is referenced in the following schemas:

-

### This schema references the following schemas directly:

-TimePeriod

-ProductSpecificationRef

### This schema references directly or indirectly by the following schemas:

-EntityRef

-ProductSpecificationRef

-TargetProductSchema

-TimePeriod

-Entity



## Examples

Examples coming soon

## TMForum APIs that use this schema

Taking into consideration the snapshot of 18/09/2019 02:29:59 UTC the list of [TMForum Open APIs](https://www.tmforum.org/open-apis/) that uses this schemas is:

Coming soon