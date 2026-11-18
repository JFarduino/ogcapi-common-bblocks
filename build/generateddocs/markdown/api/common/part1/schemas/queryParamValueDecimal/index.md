
# Decimal query parameter value (Datatype)

`ogc.api.common.part1.schemas.queryParamValueDecimal` *v0.1*

The encoding of a decimal query parameter value: decimal digits separated by a period as a decimal indicator.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
$schema: https://json-schema.org/draft/2020-12/schema
title: Decimal query parameter value
description: Decimal values SHALL be represented by a finite-length sequence of decimal
  digits separated by a period as a decimal indicator. An optional leading negative
  ("-") sign is allowed (positive, "+", is assumed if omitted). Leading and trailing
  zeroes are optional, and if the fractional part is zero, the period and following
  zero(es) can be omitted.
type: number
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.schemas.queryParamValueDecimal
  register: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2026-09-16'

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/queryParamValueDecimal/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/queryParamValueDecimal/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core, Requirement /req/core/query-param-value-decimal](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/ogcapi-common-all-as-bblocks](https://github.com/GeoLabs/ogcapi-common-all-as-bblocks)
* Path: `_sources/part1/schemas/queryParamValueDecimal`

