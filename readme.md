# Co-op Foundations: Typography
Baseline typographic setup for all Co-op's web projects.

## Dependencies (for PostCSS sources only)
- `@coopdigital/foundations-vars`
- `postcss`
- `precss`

## How to use
1. Install via `npm` or Yarn:
  ```bash
  $ npm install @coopdigital/foundations-typography --save
  $ yarn add @coopdigital/foundations-typography
  ```
2. Add CSS module to your application via a most appropriate method. This will entirely depend on your application and how you are currently loading CSS modules within it.

## Examples
Here's a bunch of examples, showing how you can integrate this CSS module in your project, based on most popular types of project. You can either use a post-processed and pre-built CSS form the `dist` directory, ot use PostCSS sources from the `src` dir.

The latter have two dependencies, which should be consumed by your frontend toolkit to postprocess the CSS correctly.

### Vue.js
In Vue, you can just reference it from a global component like so:
```css
<style>
/* Import PostCSS source */
@import "~@coopdigital/foundations-typography/src/typography.pcss";
/* Import postprocessed distributable CSS */
@import "~@coopdigital/foundations-typography/dist/typography.css";
</style>
```

### React.js
TBD

### Webpack
TBD
