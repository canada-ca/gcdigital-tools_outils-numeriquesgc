---
layout: default
title:  "Government of Canada Digital Tools (draft)"
lang: en
altLang: fr
altLangPage: apercu
---
{% assign dataVariable = site.playbookData[page.lang] %}
{% assign dataSource = site.data[dataVariable] %}
<section class="dpgn-section-overview">

## Overview (draft)

Provides tools and guidance to assist the Government of Canada in digital transformation and augmented service delivery, including becoming more agile, open and user-focused. Includes task-specific views and interactive features to make it easier to find relevant guidance and to apply it to day-to-day work.
{: .dpgn-overview-start}

The GCDigital Tools proivde an opportunity to experiment with new approaches while reusing as much as possible and contributing back reusable components for others to use (see [Experimental approaches and reusable components]({{ site.baseurl }}/docs/en/experimental-approaches-reusable-components.html)).
{: .dpgn-overview-start}

{% include views-vues.html lang=page.lang %}

<section class="dpgn-overview-end">

### About the GCDigital Tools

<section class="dpgn-overview-end">
  
#### Improving government services in the Digital Age

Our goal is to provide public services to Canadians which are simple to use and trustworthy. These GCDigital Tools, and the Government of Canada's Digital Standards it is built upon, form the foundation of the Government of Canada’s shift to becoming more agile, open, and user-focused.

The Government of Canada Digital Tools are available under the [Open Government Licence - Canada](https://open.canada.ca/en/open-government-licence-canada), except where otherwise stated.

</section>

<section class="dpgn-overview-end">

#### Implementation approach

The approach to developing and releasing the GCDigital Tools will be similar to the Web Experience Toolkit and HTML5, where the GCDigital Tools continuously evolve on GitHub and stable snapshots of that work are released as formal versions through Canada.ca. This enables the GCDigital Tools to be both agile and ever-improving on GitHub while also providing a stable version through Canada.ca that can be relied upon for guidance.

Community feedback and contributions to the GCDigital Tools are encouraged, with designated reviewers for each part of the GCDigital Tools being responsible for reviewing, responding to, requesting changes (as needed) and eventually approving or declining the feedback and contributions. The primary reviewers are individuals from the related policy areas and areas of expertise, and are also responsible for contributing content and engaging with their respective communities.

To ensure that the GCDigital Tools are as easy to use as possible, contributors/reviewers would work with their respective communities to determine how to make the GCDigital Tools more applicable to their day-to-day work, including for which tasks/scenarios personalized [GCDigital Tools views]({{ site.baseurl }}/docs/{{ page.lang }}/views{{ site.RenderedFileExtension }}) should be provided.

</section>
</section>
