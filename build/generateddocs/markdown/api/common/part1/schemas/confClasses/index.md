
# Conformance Classes schema (Schema)

`ogc.api.common.part1.schemas.confClasses` *v0.1*

This building block corresponds to the schema for an OGC API Common confClasses

[*Status*](http://www.opengis.net/def/status): Under development

## Examples

### A conformance declaration for an OGC API Common - Core implementation
#### json
```json
{
  "conformsTo": [
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/core",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/landing-page",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/json",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/html",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/oas30"
  ]
}

```

#### jsonld
```jsonld
{
  "@context": "https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/confClasses/context.jsonld",
  "conformsTo": [
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/core",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/landing-page",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/json",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/html",
    "http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/oas30"
  ]
}
```

#### ttl
```ttl
@prefix dct: <http://purl.org/dc/terms/> .

[] dct:conformsTo <http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/core>,
        <http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/html>,
        <http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/json>,
        <http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/landing-page>,
        <http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/oas30> .


```

## Schema

```yaml
type: object
required:
- conformsTo
properties:
  conformsTo:
    type: array
    items:
      type: string
      example: http://www.opengis.net/spec/ogcapi-common-1/1.0/conf/core
    x-jsonld-id: http://purl.org/dc/terms/conformsTo
    x-jsonld-type: '@id'
    x-jsonld-container: '@set'
x-jsonld-prefixes:
  dct: http://purl.org/dc/terms/
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.schemas.confClasses
  register: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2025-10-23'

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/confClasses/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/confClasses/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "conformsTo": {
      "@id": "dct:conformsTo",
      "@type": "@id",
      "@container": "@set"
    },
    "dct": "http://purl.org/dc/terms/",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/confClasses/context.jsonld)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/ogcapi-common-all-as-bblocks](https://github.com/GeoLabs/ogcapi-common-all-as-bblocks)
* Path: `_sources/part1/schemas/confClasses`

