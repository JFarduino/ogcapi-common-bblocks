
# Integer query parameter value (Datatype)

`ogc.api.common.part1.schemas.queryParamValueInteger` *v0.1*

The encoding of an integer query parameter value: a finite-length sequence of decimal digits with an optional leading negative sign.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
$schema: https://json-schema.org/draft/2020-12/schema
title: Integer query parameter value
description: Integer values SHALL be represented by a finite-length sequence of decimal
  digits with an optional leading negative ("-") sign. Positive values are assumed
  if the leading sign is omitted.
type: integer
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.schemas.queryParamValueInteger
  register: https://jfarduino.github.io/ogcapi-common-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2026-09-16'

```

Links to the schema:

* YAML version: [schema.yaml](https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/schemas/queryParamValueInteger/schema.json)
* JSON version: [schema.json](https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/schemas/queryParamValueInteger/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core, Requirement /req/core/query-param-value-integer](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/JFarduino/ogcapi-common-bblocks](https://github.com/JFarduino/ogcapi-common-bblocks)
* Path: `_sources/part1/schemas/queryParamValueInteger`

