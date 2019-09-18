# Entity catalog Data Model

## Domain

The  schema is part of the  Domain

## Description

The root entity for entity catalog management. An entity catalog can be defined as a collection of entity catalog items and arranging them in a particular manner based on the need.
In comparison to Product, Service and Resource catalogs, the entity catalog is intended for the purpose of providing any SID entity to consumers via a catalog, with its specification and policy providing governance over its content. Even Entity catalog may have an overlap with Product, Service or Resource catalog, it does not replace them. It is primarily intended to address those SID entities which may not be addressed by any of Product, Service or Resource catalog.
An entity catalog comprises of a list of RootEntities made available through EntityCatalogItems. This API addresses only RootEntity extended items as EntitySpecification. An entity catalog typically includes name, description and time period that it is valid for.

## Data model

A JSON Schema corresponding to this data model can be found
[here](https://github.com/tmforum-rand/schemas/blob/master/Common/EntityCatalog.schema.json).

No Data Model yet

## Schema Relationships

### This schema is referenced in the following schemas:

-

### This schema references the following schemas directly:

-Entity

-TimePeriod

### This schema references directly or indirectly by the following schemas:

-TimePeriod

-Entity



## Examples

Examples coming soon

## TMForum APIs that use this schema

Taking into consideration the snapshot of 18/09/2019 02:29:59 UTC the list of [TMForum Open APIs](https://www.tmforum.org/open-apis/) that uses this schemas is:

Coming soon