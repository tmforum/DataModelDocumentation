# App usage data analytics Data Model

## Domain

The  schema is part of the  Domain

## Description



## Data model

A JSON Schema corresponding to this data model can be found
[here](https://github.com/tmforum-rand/schemas/blob/candidates/Analytics/AppUsageDataAnalytics.schema.json).

The Data model is defined as shown below:
- `startTimestamp` : The beginning of the measurement interval 
START_TIMESTAMP to END_TIME_STAMP defines define the period for which the measurement is done

  - Optional

- `endTimestamp` : The beginning of the measurement interval 
START_TIMESTAMP to END_TIME_STAMP defines define the period for which the measurement is done

  - Optional

- `appInstalledTimestamp` : The TIMESTAMP of the APP installation (empty if not in the period START_TIMESTAMP-END_TIMESTAMP)

  - Optional

- `appUpdatedTimestamp` : The TIMESTAMP of the APP update (empty if not in the period START_TIMESTAMP-END_TIMESTAMP)

  - Optional

- `dataCreationTimestamp` : Time stamp for data creation (e.g. system dump creation, event generation…)

  - Optional

- `runTimestamp` : Time stamp for data upload run

  - Optional

- `validFromTimestamp` : Time stamp for business validity of entity record

  - Optional





## TMForum APIs that use this schema

Taking into consideration the snapshot of 04/02/2020 04:45:39 UTC the list of [TMForum Open APIs](https://www.tmforum.org/open-apis/) that uses this schemas is:

Coming soon