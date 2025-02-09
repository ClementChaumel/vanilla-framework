---
wrapper_template: '_layouts/docs.html'
context:
  title: Section and block | Components
---

# Sections and blocks

<hr>

Use sections and blocks for different types of elements on the page depending on your markup. They are used for managing the bottom space after each element.

## Sections

Use a section component (`.p-section`) for displaying subsequent sections on the page on a same background. They should be used in place of strips for most of the standard page content.

Sections should not be nested inside each other or inside the strips.

<div class="row">
  <div class="col-6 col-medium-3">
    <div class="p-notification--positive">
      <p class="p-notification__content">
        <span class="p-notification__title">Do:</span>
        <span class="p-notification__message">Use section component to build regular sections of the page that follow each other on the same background.</span>
      </p>
    </div>
  </div>
  <div class="col-6 col-medium-3">
    <div class="p-notification--negative">
      <p class="p-notification__content">
        <span class="p-notification__title">Don't:</span>
        <span class="p-notification__message">If a section of a page has a different background, or needs to be emphasised using deeper spacing use the <a href="/docs/patterns/strip">strip</a> component instead.</span>
      </p>
    </div>
  </div>
</div>

<div class="embedded-example"><a href="/docs/examples/patterns/section/section" class="js-example">
View example of the "section" pattern
</a></div>

## Blocks

Use a block component (`.p-block`) to group larger chunks of content inside a single section or strip.

<div class="embedded-example"><a href="/docs/examples/patterns/section/block" class="js-example">
View example of the "block" pattern
</a></div>

## Import

To import just this component into your project, copy the snippet below and include it in your main Sass file.

```scss
// import Vanilla and include base mixins
// this only needs to happen once in a given project
@import 'vanilla-framework';
@include vf-base;

@include vf-p-container;
```

For more information see [Customising Vanilla](/docs/customising-vanilla/) in your projects, which includes overrides and importing instructions.
