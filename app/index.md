---
layout: product
title: Academy Transfers design history 
description: A repository of user research in discovery and iterations during alpha.
breadcrumbs: false
---

{% from "document-list/macro.njk" import appDocumentList %}
<div class="govuk-grid-row">
  <section class="govuk-grid-column-one-half">
    <h2 class="govuk-heading-l govuk-!-font-size-27">Discovery</h2>
    {{ appDocumentList({ items: collections["getting-started"] }) | safe }}
  </section>

  <section class="govuk-grid-column-one-half">
    <h2 class="govuk-heading-l govuk-!-font-size-27">Alpha</h2>
    {{ appDocumentList({
      items: collections["layout"]
    }) | safe }}
  </section>
</div>
