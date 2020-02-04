# Entity specification Data Model

## Domain

The  schema is part of the  Domain

## Description

EntitySpecification is a class that offers characteristics to describe a type of entity. Entities are generic constructs that may be used to describe bespoke business entities that are not effectively covered by the existing SID model.
Functionally, the entity specification acts as a template by which entities may be instantiated and described. By sharing the same specification, these entities would therefore share the same set of characteristics.
Note: The ‘configurable’ attribute on the specCharacteristics determines if an entity instantiated from the entity specification can override the value of the attribute. When set to false, the entity instance may not define a value that differs from the value in the specification.

## Data model

A JSON Schema corresponding to this data model can be found
[here](https://github.com/tmforum-rand/schemas/blob/candidates/Common/EntitySpecification.schema.json).

No Data Model yet

## Schema Relationships

### This schema is referenced in the following schemas:

-

### This schema references the following schemas directly:

-references

-domain

### This schema references directly or indirectly by the following schemas:

-domain

-references



## Examples

Examples coming soon

## TMForum APIs that use this schema

Taking into consideration the snapshot of 04/02/2020 03:41:06 UTC the list of [TMForum Open APIs](https://www.tmforum.org/open-apis/) that uses this schemas is:

Coming soon