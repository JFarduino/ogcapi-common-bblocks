
# LandingPage response (Response)

`ogc.api.common.part1.responses.LandingPage` *v0.1*

The response for the OGC API landing page resource.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: The landing page provides links to the API definition (link relations
  `service-desc` and `service-doc`), the Conformance declaration (path `/conformance`,
  link relation `http://www.opengis.net/def/rel/ogc/1.0/conformance`), and to other
  resources.
content:
  application/json:
    schema:
      $ref: https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/schemas/landingPage/schema.yaml
  text/html:
    schema:
      type: string
x-bblocks-metadata:
  itemIdentifier: ogc.api.common.part1.responses.LandingPage
  register: https://jfarduino.github.io/ogcapi-common-bblocks/build/register.json
  version: '0.1'
  dateOfLastChange: '2026-09-16'

```

Links to the schema:

* YAML version: [schema.yaml](https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/responses/LandingPage/schema.json)
* JSON version: [schema.json](https://jfarduino.github.io/ogcapi-common-bblocks/build/annotated/api/common/part1/responses/LandingPage/schema.yaml)

## Sources

* [OGC API - Common - Part 1: Core](https://docs.ogc.org/is/19-072/19-072.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/JFarduino/ogcapi-common-bblocks](https://github.com/JFarduino/ogcapi-common-bblocks)
* Path: `_sources/part1/responses/LandingPage`

