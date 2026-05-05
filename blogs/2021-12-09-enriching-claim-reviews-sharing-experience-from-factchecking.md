---
title: "Enriching Claim Reviews – Sharing Experience From Factchecking"
url: "https://blog.schema.org/2021/12/09/the-art-of-connection/"
date: "Thu, 09 Dec 2021 05:49:00 +0000"
author: "Adriana Olmos"
feed_url: "https://blog.schema.org/feed/"
---
<p class="wp-block-paragraph"></p>



<p class="wp-block-paragraph"><em>ClaimReview is one of the hidden jewels that can be found amongst schema.org&#8217;s 2700+ definitions. To kick off a series of guest posts around this topic, we bring you a guest post from two members of the factchecking and open data community who have been exploring the potential of this work.</em></p>



<p class="wp-block-paragraph">Enriching ClaimReview for fact checkers</p>



<p class="wp-block-paragraph">To help fight bad information, search engines, social media platforms and other sources of online content are increasingly highlighting the work of fact checkers by labelling posts with incorrect, misleading or harmful information.</p>



<p class="wp-block-paragraph">This is often enabled through the publication of structured data that uses Schema.org&#8217;s <a href="https://schema.org/ClaimReview">ClaimReview</a> schema. This defines a simple approach for <a href="https://developers.google.com/search/docs/data-types/factcheck">tagging fact checking articles</a> that has been collaboratively developed and documented through <a href="https://schema.org/">Schema.org</a>. For more background for a journalistic and factchecking audience, see <a href="https://reporterslab.org/">Duke Reporters&#8217; Lab</a>&#8216;s <a href="https://www.claimreviewproject.com/">dedicated site</a>.&nbsp;At&nbsp;<a href="https://fullfact.org/">Full Fact</a> we have recently been exploring ways to revise and extend the claim review metadata to provide more detail that might enable further reuse and labelling of content, and further insights into the fact checking process.</p>



<p class="wp-block-paragraph">Our investigation has covered the following areas:</p>



<ul class="wp-block-list">
<li><strong>Current scope and application of ClaimReview</strong>. The currently defined model provides a lot of flexibility around how much detail might be included in a review, with Google, <a href="https://blogs.bing.com/Webmaster-Blog/September-2017/Bing-adds-Fact-Check-label-in-SERP-to-support-the-ClaimReview-markup">Bing</a> and others recommending specific profiles of that in their structured markup documentation. Full Fact has adopted their own approach for applying the standard, we have reflected on that experience and the current recommendations from Google, Bing and other adopters, in pursuit of a Full Fact profile that is close to those used elsewhere.</li>



<li><strong>Identifiers and linking</strong>. How can additional links and identifiers be included in ClaimReview markup to support disambiguation and aggregation of data? We&#8217;ve concluded that Schema.org already provides useful properties which, if applied consistently, can support this goal. In line with its growing role as a clearing house for identifiers, we believe <a href="https://wikidata.org/">Wikidata</a> would be a useful common target for linking data across the community, e.g. making use of schema.org&#8217;s <a href="https://schema.org/sameAs">sameAs</a> property. Full Fact articles <a href="https://twitter.com/mr_dudders/status/1466362791200280581">now contain</a> experimental markup in this direction.</li>



<li><strong>Enriching Claims</strong>. The standard was revised to include the notion of a <a href="https://schema.org/Claim">Claim</a>: a statement made by an author that appears in one or more locations. We believe this is an important part of the data model and one that should be more widely adopted. Consistent use of Claim markup would help to clearly indicate situations in which a person or organisation is repeatedly making the same claim, or where others are repeating the same misinformation. In addition to enriching claims with author and appearance information, the addition of topic information would provide a useful dimension to the data, helping to surface related claims and fact checks. </li>



<li><strong>Corrections and actions</strong>. The <a href="https://fullfact.org/blog/2019/jun/how-fact-checking-works/">second wave of fact checking</a> is about more than just writing fact checks, it involves taking action to tackle disinformation. How might we surface data about requests for corrections to published content, and record when those corrections have been made? Schema.org currently includes some vocabulary to help describe corrections and comments which we&#8217;ve explored. But further work is needed to define a useful way of recording and sharing the other activities undertaken by fact checkers</li>



<li><strong>Citing evidence</strong>. Finally citing evidence is an essential part of performing a fact check, so how can we use existing Schema.org vocabulary to help to surface the key resources, papers and datasets that were used in producing a fact check?</li>
</ul>



<p class="wp-block-paragraph">Building on the open, collaborative approach that the community has taken so far, we have published <a href="https://fullfact.github.io/markup-investigation/">our research notes</a> that explore these questions in more detail and present some early recommendations. We welcome feedback from anyone working to tackle online disinformation.</p>



<p class="wp-block-paragraph">We would also like to propose the creation of an informal mailing list or community group to support ongoing discussion and experimentation, e.g. hosted at W3C alongside the broader <a href="https://www.w3.org/community/schemaorg/">Schema.org CG</a>.</p>



<p class="wp-block-paragraph">Our joint goal would be to create proposals for further enhancing the current Schema.org model, as necessary, and documenting useful patterns of applying the current model to real-world scenarios including both tagging content and developing APIs.</p>
