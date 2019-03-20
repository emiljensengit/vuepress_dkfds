<template>
  <section id="section"> <!-- section-{{page.id}} -->
    <!--{% if page.alertwarningheader != null and page.alertwarningheader != "" or page.alertwarningtext != null and page.alertwarningtext != "" %}
    <div class="alert alert-warning" role="alert">
        <div class="alert-body">
            <h3 class="alert-heading">{{page.alertwarningheader}}</h3>
            <p class="alert-text">
              {{page.alertwarningtext}}
            </p>
        </div>
    </div>
    {% endif %}-->
    <p class="h6 m-0">
      {{ $page.frontmatter.subcategory }}
    </p>
    <h1 class="mt-0">{{ $page.frontmatter.title }}</h1> <!-- id="{{ page.title | slugify }}"-->
    <p class="font-lead" v-if="$page.frontmatter.lead">{{ $page.frontmatter.lead }}</p>

    <!--{{ content }} -->
    <Content :custom="false"/>
  </section>
</template>