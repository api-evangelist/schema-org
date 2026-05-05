---
title: "Announcing Schema Markup Validator: validator.schema.org (beta)"
url: "https://blog.schema.org/2021/05/21/announcing-schema-markup-validator-validator-schema-org-beta/"
date: "Fri, 21 May 2021 05:43:00 +0000"
author: "Adriana Olmos"
feed_url: "https://blog.schema.org/feed/"
---
<p class="wp-block-paragraph"></p>



<p class="wp-block-paragraph">Announcing preview availability of&nbsp;<a href="https://validator.schema.org/">validator.schema.org</a>&nbsp;for review and feedback.</p>



<p class="wp-block-paragraph">As&nbsp;<a href="https://lists.w3.org/Archives/Public/public-schemaorg/2020Dec/0002.html">agreed</a>&nbsp;<a href="https://developers.google.com/search/blog/2020/12/structured-data-testing-tool-update">last year</a>, Schema.org is the new home for the structured data validator previously known as the Structured Data Testing Tool (SDTT). It is now simpler to use, and available for testing. Schema.org will integrate feedback into its&nbsp;<a href="https://github.com/schemaorg/schemaorg/blob/main/docs/validator.md">draft</a>&nbsp;documentation and add it more explicitly to the Schema.org website for the next official release.</p>



<p class="wp-block-paragraph">SDTT is a tool from Google which began life as the&nbsp;<a href="https://developers.google.com/search/blog/2010/09/rich-snippets-testing-tool-improvements">Rich Snippets Testing Tool&nbsp;</a>back in 2010. Last year Google&nbsp;<a href="https://developers.google.com/search/blog/2020/07/rich-results-test-out-of-beta">announced plans</a>&nbsp;to migrate from SDTT to successor tooling, the&nbsp;<a href="https://search.google.com/test/rich-results">Rich Results Test</a>, alongside plans to &#8220;deprecate the Structured Data Testing Tool&#8221;. The newer Google tooling is focused on helping publishers who are targeting specific schema.org-powered&nbsp;<a href="https://developers.google.com/search/docs/guides/search-gallery">searc</a><a href="https://www.blogger.com/#">h features</a>&nbsp;offered by Google, and for these purposes is a huge improvement as it contextualizes many warnings and errors to a specific target application.</p>



<p class="wp-block-paragraph">However, many publishers had also appreciated SDTT as a powerful and general purpose structured data validator. Headlines such as &#8220;<a href="https://www.seroundtable.com/google-deprecate-the-structured-data-testing-tool-29737.html">Google Structured Data Testing Tool Going Away; SEOs Are Not Happy</a>&#8221; captured something of the mood.</p>



<p class="wp-block-paragraph">Schema.org started out written only in&nbsp;<a href="https://en.wikipedia.org/wiki/Microdata_(HTML)">Microdata</a>, before embracing&nbsp;<a href="http://blog.schema.org/2011/11/using-rdfa-11-lite-with-schemaorg.html">RDFa 1.1 Lite</a>&nbsp;and&nbsp;<a href="http://blog.schema.org/2013/06/schemaorg-and-json-ld.html">JSON-LD 1.0</a>. There are now huge amounts of Schema.org data in all of these formats and more (see&nbsp;<a href="http://webdatacommons.org/structureddata/#results-2020-1">webdatacommons</a>&nbsp;report). Schema.org endorsed these multiple encodings, because they can each meet different needs and constraints experienced by publishers. The new validator will check all of these formats.</p>



<p class="wp-block-paragraph">Amongst all this complexity, it is important to remind ourselves of the importance of simplicity and usability of Schema.org markup for its founding purpose: machine-readable summaries of ordinary web page content. Markup that &#8211; when well-formed &#8211; helps real people find jobs, educational opportunities, images they can&nbsp;<a href="https://iptc.org/news/schema-org-update-for-better-mapping-to-iptc-photo-metadata/">re-use</a>, learn from fact checkers or find a recipe to cook for dinner.</p>



<p class="wp-block-paragraph">This is the focus of the new Schema Markup Validator (SMV). It is simpler than its predecessor SDTT because it is dedicated to checking that you&#8217;re using JSON-LD, RDFa and Microdata in widely understood ways, and to warning you if you are using Schema.org types and properties in unusual combinations. It does&nbsp;<em>not</em>&nbsp;try to check your content against the information needs of specific services, tools or products (a topic deserving its own blog post). But it&nbsp;<em>will</em>&nbsp;help you understand whether or not your data expresses what you hope it expresses, and to reflect the essence of your structured data back in an intuitive way that reflects its underlying meaning.</p>



<p class="wp-block-paragraph">The&nbsp;<a href="http://validator.schema.org/">validator.schema.org</a>&nbsp;service&nbsp;is powered by Google&#8217;s general infrastructure for working with structured data, and is provided to the Schema.org project as a Google-hosted tool. We are also happy to note that many other schema.org-oriented validators are available, both commercial (e.g.&nbsp;<a href="https://yandex.com/support/webmaster/yandex-indexing/validator.html">Yandex&#8217;s</a>) and opensource. For example, the&nbsp;<a href="http://linter.structured-data.org/">Structured Data Linter,</a><a href="https://json-ld.org/playground/">JSON-LD Playground</a>,&nbsp;<a href="https://github.com/semantifyit/sdo-check/">SDO-Check</a>&nbsp;and&nbsp;<a href="https://github.com/google/schemarama/">Schemarama</a>&nbsp;tools. We hope that the new Schema Markup Validator will stimulate collaboration among tool makers to improve consistency and developer experience for all those working on systems that consume Schema.org data.&nbsp;</p>



<p class="wp-block-paragraph">Please share any feedback with the Schema.org community via&nbsp;<a href="https://github.com/schemaorg/schemaorg/issues/2790">Github</a>, Twitter (#schemasmv), or the Schema.org W3C&nbsp;<a href="https://www.w3.org/community/schemaorg/">community group</a>.</p>



<p class="wp-block-paragraph"></p>
