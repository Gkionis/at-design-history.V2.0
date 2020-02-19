---
layout: product
title: Academy Transfers design history 
description: The repository of iterations during discovery and alpha.
breadcrumbs: false
---
{% from "govuk/components/tag/macro.njk" import govukTag %}
{{ govukTag({
  classes: "govuk-!-margin-bottom-4",
  text: "Alpha"
}) }}





<hr class="govuk-section-break govuk-section-break--visible">

{% from "document-list/macro.njk" import appDocumentList %}
<div class="govuk-grid-row">
  <section class="govuk-grid-column-one-third">
    <h2 class="govuk-heading-l govuk-!-font-size-27">Getting started</h2>
    {{ appDocumentList({
      items: collections["getting-started"]
    }) | safe }}
  </section>

  <section class="govuk-grid-column-one-third">
    <h2 class="govuk-heading-l govuk-!-font-size-27">Layouts</h2>
    {{ appDocumentList({
      items: collections["layout"]
    }) | safe }}
  </section>

  <section class="govuk-grid-column-one-third">
    <h2 class="govuk-heading-l govuk-!-font-size-27">Components</h2>
    {{ appDocumentList({
      items: collections["component"]
    }) | safe }}
  </section>
</div>
