# Schema.org

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Schema.org is a collaborative, community-driven project that creates and maintains a shared vocabulary for structured data on the web. Founded by Google, Microsoft, Yahoo, and Yandex in 2011, it provides types and properties that developers and webmasters use to annotate content in formats like JSON-LD, RDFa, and Microdata, enabling search engines and applications to better understand web content. The vocabulary covers 800+ Types and 1500+ Properties spanning commerce, healthcare, organizations, events, creative works, and more.

**URL:** [https://schema.org/](https://schema.org/)

## Tags

 - Schema.org, Structured Data, Linked Data, JSON-LD, Vocabulary, SEO, Web Standards, RDF, Ontology

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Schema.org Vocabulary

Schema.org is a collaborative, community-driven vocabulary for structured data on the internet. It provides a collection of shared vocabularies that webmasters and developers can use to mark up pages in ways recognized by major search engines including Google, Microsoft, Yahoo, and Yandex. Machine-readable definitions are available in RDF/Turtle, JSON-LD, CSV, and other formats.

**Human URL:** [https://schema.org/docs/developers.html](https://schema.org/docs/developers.html)

#### Tags

 - Schema.org, Vocabulary, Structured Data, Linked Data, JSON-LD, RDF, Microdata, RDFa, SEO, Web Standards

#### Properties

- [Documentation](https://schema.org/docs/developers.html)
- [Reference](https://schema.org/docs/schemas.html)
- [Data Model](https://schema.org/docs/datamodel.html)
- [Change Log](https://schema.org/docs/releases.html)
- [GitHub Repository](https://github.com/schemaorg/schemaorg)
- [JSON Schema](json-schema/schema-org-thing-schema.json)

### Schema.org JSON-LD Context

The Schema.org JSON-LD Context provides the canonical JSON-LD context file for the Schema.org vocabulary. This context file maps Schema.org terms to their full IRIs, enabling JSON-LD processors to correctly interpret structured data markup. Google recommends JSON-LD as the preferred format for Schema.org structured data on websites.

**Human URL:** [https://schema.org/docs/developers.html](https://schema.org/docs/developers.html)

#### Tags

 - JSON-LD, Linked Data, Context, Vocabulary, Structured Data

#### Properties

- [Documentation](https://schema.org/docs/developers.html)
- [JSON-LD Context](https://schema.org/docs/jsonldcontext.json)

### Schema.org Markup Validator

The Schema.org Markup Validator tests and validates structured data markup against the Schema.org vocabulary. It supports JSON-LD, Microdata, and RDFa formats and helps ensure structured data will be correctly interpreted by search engines.

**Human URL:** [https://validator.schema.org/](https://validator.schema.org/)

#### Tags

 - Validation, Structured Data, Testing, Schema, Markup

#### Properties

- [Documentation](https://validator.schema.org/)

### Schema.org WebAPI Type

The Schema.org WebAPI type defines a Web API accessible over Web and Internet technologies. It provides standardized properties for describing APIs including documentation URL, terms of service, provider, and API entry point. The WebAPI type enables search engines and automated tools to discover and understand published APIs.

**Human URL:** [https://schema.org/WebAPI](https://schema.org/WebAPI)

#### Tags

 - WebAPI, API Description, Structured Data, Linked Data, Schema

#### Properties

- [Documentation](https://schema.org/WebAPI)
- [JSON Schema](json-schema/schema-org-web-api-schema.json)

## Common Properties

- [Website](https://schema.org/)
- [Documentation](https://schema.org/docs/documents.html)
- [Blog](https://blog.schema.org/)
- [Support](https://github.com/schemaorg/schemaorg/issues)

## Spectral Rules

| Ruleset | Description |
|---|---|
| [schema-org-rules.yml](rules/schema-org-rules.yml) | Validation rules for Schema.org JSON-LD structured data |

## JSON Schema

| Schema | Description |
|---|---|
| [schema-org-thing-schema.json](json-schema/schema-org-thing-schema.json) | Schema.org Thing type — base for all Schema.org types |
| [schema-org-web-api-schema.json](json-schema/schema-org-web-api-schema.json) | Schema.org WebAPI type for describing APIs |
| [schema-org-person-schema.json](json-schema/schema-org-person-schema.json) | Schema.org Person type |
| [schema-org-organization-schema.json](json-schema/schema-org-organization-schema.json) | Schema.org Organization type |
| [schema-org-product-schema.json](json-schema/schema-org-product-schema.json) | Schema.org Product type for e-commerce |
| [schema-org-event-schema.json](json-schema/schema-org-event-schema.json) | Schema.org Event type |
| [schema-org-article-schema.json](json-schema/schema-org-article-schema.json) | Schema.org Article type |
| [schema-org-local-business-schema.json](json-schema/schema-org-local-business-schema.json) | Schema.org LocalBusiness type |
| [schema-org-job-posting-schema.json](json-schema/schema-org-job-posting-schema.json) | Schema.org JobPosting type |
| [schema-org-course-schema.json](json-schema/schema-org-course-schema.json) | Schema.org Course type |

## JSON Structure

| Structure | Description |
|---|---|
| [schema-org-thing.json](json-structure/schema-org-thing.json) | Thing type structure documentation |
| [schema-org-product.json](json-structure/schema-org-product.json) | Product type structure documentation |
| [schema-org-person.json](json-structure/schema-org-person.json) | Person type structure documentation |

## JSON-LD

| Context | Description |
|---|---|
| [schema-org-context.jsonld](json-ld/schema-org-context.jsonld) | Canonical Schema.org JSON-LD context mapping all major types |

## Examples

| Example | Description |
|---|---|
| [schema-org-web-api-example.json](examples/schema-org-web-api-example.json) | WebAPI type JSON-LD structured data for API description |
| [schema-org-product-example.json](examples/schema-org-product-example.json) | Product type with offer and rating for e-commerce rich results |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [schema-org-vocabulary.yml](vocabulary/schema-org-vocabulary.yml) | Schema.org core types and concepts vocabulary |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
