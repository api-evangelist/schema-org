---
title: "Supporting Ordering in schema.org"
url: "https://blog.schema.org/2026/06/17/supporting-ordering-in-schema-org/"
date: "2026-06-17"
author: "rrlevering"
feed_url: "https://blog.schema.org/feed/"
---
Ordering is hard in RDF because triples are not ordered by default and expressing order requires implicit syntax or structures like rdf:List or rdf:Seq. Schema.org is taking steps to make ordering easier by explicitly supporting collections, clarifying that collection elements must match expected property types and allowing the simpler JSON-LD @list syntax instead of requiring the more complex ItemList structure for ordered data.
