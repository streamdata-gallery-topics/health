---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services--trust-in-axa-assistance-for-your-insurance
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /information/v1/countries/{country_id}/health_cards:
    get:
      summary: Retrieve health information for a country
      description: Retrieve health information for a country
      operationId: getInformationV1CountriesCountry_idHealth_cards
      x-api-path-slug: informationv1countriescountry-idhealth-cards-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - health
      - informationa
      - country
---