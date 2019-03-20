---
permalink: "/komponenter/tekstelementer/"
layout: styleguide
type: element
title: Tekstelementer
category: Komponenter_category
subcategory: Komponenter
lead: Tekstelementer show tabular data in columns and rows.
headling: Alert headling default
text: Alert tekst default
role: alert role default
aria: alert aria default
pageblocks:
- template: componentalert
  type: AlertType
  headling: Alert headling default
  text: Alert tekst default
  role: alert role default
  aria: alert aria default

---
## Headings

<p>All HTML headings, <code>&lt;h1&gt;</code> through <code>&lt;h6&gt;</code>, are available. <code>.h1</code> through <code>.h6</code> classes are also available, for when you want to match the font styling of a heading but still want your text to be displayed inline.</p>

{% include code/preview.html component="headings" %}
{% include code/accordion.html component="headings" %}

## Body copy

<p>The Frontend styleguide's global default <code>font-size</code> is <strong>16px</strong>, with a <code>line-height</code> of <strong>1.428</strong>. This is applied to the <code>&lt;body&gt;</code> and all paragraphs. In addition, <code>&lt;p&gt;</code> (paragraphs) receive a bottom margin of half their computed line-height (10px by default).</p>

{% include code/preview.html component="bodycopy" %}
{% include code/accordion.html component="bodycopy" %}