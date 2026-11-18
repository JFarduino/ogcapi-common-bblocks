
# ConformanceDeclaration response (Response)

`ogc.api.common.part1.responses.ConformanceDeclaration` *v0.1*

The response for the OGC API conformance declaration resource.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'The URIs of all conformance classes supported by the server.

  To support "generic" clients that want to access multiple OGC API implementations
  - and not "just" a specific API / server, the server declares the conformance classes
  it implements and conforms to.'
content:
  application/json:
    schema:
      $ref: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/confClasses/schema.yaml
    example:
      conformsTo:
      - http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/core
  text/html:
    schema:
      type: string
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.responses.ConformanceDeclaration
  register: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2026-09-16'

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/responses/ConformanceDeclaration/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/responses/ConformanceDeclaration/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/ogcapi-common-all-as-bblocks](https://github.com/GeoLabs/ogcapi-common-all-as-bblocks)
* Path: `_sources/part1/responses/ConformanceDeclaration`

