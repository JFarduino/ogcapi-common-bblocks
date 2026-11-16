
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
      $ref: https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/schemas/exception/schema.yaml
  text/html:
    schema:
      type: string
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.responses.Exception
  register: https://jfarduino.github.io/ogcapi-common-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2026-09-16'

```

Links to the schema:

* YAML version: [schema.yaml](https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/responses/Exception/schema.json)
* JSON version: [schema.json](https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/responses/Exception/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/JFarduino/ogcapi-common-bblocks](https://github.com/JFarduino/ogcapi-common-bblocks)
* Path: `_sources/part1/responses/Exception`

