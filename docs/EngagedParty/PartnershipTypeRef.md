# Partnership type ref Data Model

## Domain

The  schema is part of the  Domain

## Description

PartnershipType reference. A partnership type contains all the information for the setup of a partnership of a given kind. This includes the list of identified role types for the partnership with the corresponding agreement specifications.

## Data model

A JSON Schema corresponding to this data model can be found
[here](https://github.com/tmforum-rand/schemas/blob/candidates/EngagedParty/PartnershipTypeRef.schema.json).

The Data model is defined as shown below:

- `href` : Reference url for the partnership type

  - Optional


- `id` : Identifier of the partnership

  - Optional


- `name` : Name of the partnership type

  - Optional


- `@referredType` : The actual type of the target instance when needed for disambiguation.

  - Optional






## TMForum APIs that use this schema

Taking into consideration the snapshot of 04/02/2020 04:59:17 UTC the list of [TMForum Open APIs](https://www.tmforum.org/open-apis/) that uses this schemas is:

Coming soon