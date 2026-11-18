
# Landing Page schema (Schema)

`ogc.api.common.part1.schemas.landingPage` *v0.1*

This building block corresponds to the schema for an OGC API Common landingPage

[*Status*](http://www.opengis.net/def/status): Under development

## Examples

### A landing page for an OGC API implementation
#### json
```json
{
  "title": "Buildings in Bonn",
  "description": "Access to data about buildings in the city of Bonn via a Web API that conforms to the OGC API Common specification.",
  "links": [
    {
      "href": "http://data.example.org/",
      "rel": "self",
      "type": "application/json",
      "title": "This document"
    },
    {
      "href": "http://data.example.org/api",
      "rel": "service-desc",
      "type": "application/vnd.oai.openapi+json;version=3.0",
      "title": "The API definition"
    },
    {
      "href": "http://data.example.org/conformance",
      "rel": "http://www.opengis.net/def/rel/ogc/1.0/conformance",
      "type": "application/json",
      "title": "OGC API conformance classes implemented by this server"
    }
  ]
}

```

#### jsonld
```jsonld
{
  "@context": "https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/landingPage/context.jsonld",
  "title": "Buildings in Bonn",
  "description": "Access to data about buildings in the city of Bonn via a Web API that conforms to the OGC API Common specification.",
  "links": [
    {
      "href": "http://data.example.org/",
      "rel": "self",
      "type": "application/json",
      "title": "This document"
    },
    {
      "href": "http://data.example.org/api",
      "rel": "service-desc",
      "type": "application/vnd.oai.openapi+json;version=3.0",
      "title": "The API definition"
    },
    {
      "href": "http://data.example.org/conformance",
      "rel": "http://www.opengis.net/def/rel/ogc/1.0/conformance",
      "type": "application/json",
      "title": "OGC API conformance classes implemented by this server"
    }
  ]
}
```

#### ttl
```ttl
@prefix dct: <http://purl.org/dc/terms/> .

[] dct:description "Access to data about buildings in the city of Bonn via a Web API that conforms to the OGC API Common specification." ;
    dct:title "Buildings in Bonn" .


```

## Schema

```yaml
$schema: https://json-schema.org/draft/2020-12/schema
title: Landing Page
description: The landing page provides links to the API definition, the Conformance
  declaration and to the resources exposed by the API.
type: object
required:
- links
properties:
  title:
    type: string
    title: The title of the API.
    description: While a title is not required, implementers are strongly advised
      to include one.
    example: Buildings in Bonn
    x-jsonld-id: http://purl.org/dc/terms/title
  description:
    type: string
    example: Access to data about buildings in the city of Bonn via a Web API that
      conforms to the OGC API Common specification.
    x-jsonld-id: http://purl.org/dc/terms/description
  attribution:
    type: string
    title: attribution for the API
    description: The `attribution` should be short and intended for presentation to
      a user, for example, in a corner of a map. Parts of the text can be links to
      other resources if additional information is needed. The string can include
      HTML markup.
  links:
    type: array
    items:
      $ref: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/link/schema.yaml
x-jsonld-prefixes:
  dct: http://purl.org/dc/terms/
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.schemas.landingPage
  register: https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2025-10-23'

```

Links to the schema:

* YAML version: [schema.yaml](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/landingPage/schema.json)
* JSON version: [schema.json](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/landingPage/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "title": "dct:title",
    "description": "dct:description",
    "dct": "http://purl.org/dc/terms/",
    "oa": "http://www.w3.org/ns/oa#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://geolabs.github.io/ogcapi-common-all-as-bblocks/build/annotated/api/common/part1/schemas/landingPage/context.jsonld)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/GeoLabs/ogcapi-common-all-as-bblocks](https://github.com/GeoLabs/ogcapi-common-all-as-bblocks)
* Path: `_sources/part1/schemas/landingPage`

