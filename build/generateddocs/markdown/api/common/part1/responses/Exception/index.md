
# Exception response (Response)

`ogc.api.common.part1.responses.Exception` *v0.1*

An RFC 7807 "Problem Details" error response, as recommended by OGC API - Common for any error situation.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: An error occurred.
content:
  application/json:
    schema:
      $ref: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/exception/schema.yaml
  text/html:
    schema:
      type: string
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.responses.Exception
  register: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2026-09-16'

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/responses/Exception/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/responses/Exception/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/ogcapi-common-all-as-bblocks](https://github.com/GeoLabs/ogcapi-common-all-as-bblocks)
* Path: `_sources/part1/responses/Exception`

