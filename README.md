# CSS Variable Style System

[View deployed example here](https://css-variable-design-system.netlify.com)

## Features

- Responsive typography and spacing
- Responsive light / dark color theme
- Adjustable vertical rhythm
- Light-weight CSS classes that pair with HTML elements to encourage writing semantic HTML by default
- Small number of functional CSS classes for adjusting layout

## CSS Variables

### Typography

<!-- Customizable  Typography-->

- `--sans`
- `--serif`
- `--mono`
- `--heading-line-height`
- `--paragraph-line-height`
  `--heading-letter-spacing`
- `--paragraph-letter-spacing`
  <!-- Text sizes should not be touched because they are calculated. -->
- `--text-xs`
- `--text-sm`
- `--text-md`
- `--text-lg`
- `--text-xl`
- `--text-xxl`
- `--text-xxxl`

### Vertical Rhythm

<!-- Customizable -->

- `--responsive-unit`
- `--text-base-size`
- `--text-scale-ratio`

### Spacing

<!-- Customizable -->

- `--baseline`
  <!-- Calculated -->
- `--space-sm`
- `--space-md`
- `--space-lg`
- `--space-xl`

### Colors

<!-- Customizable -->

- `--text-color`
- `--bg-1`
- `--bg-2`
- `--grey`
- `--href-color`
- `--href-hover-color`
- `--primary-btn-bg`
- `--primary-btn-color`
- `--outline-btn-bg`
- `--outline-btn-color`
- `--outline-btn-border`
- `--input-border`
- `--code-bg`
- `--shadow-color`

### Component Styles

<!-- Customizable -->

- `--radius`
- `--radius-lg`
- `--thickness`
- `--container`
- `--elevation-1`
- `--elevation-2`
- `--elevation-3`
- `--transition`
- `--opacity`

## Component CSS Classes

### Header

- `.header`

### Footer

- `.footer`

### Main

- `.main`

### Fieldset

- `.fieldset`

### Form

- `.form`

### Input

- `.input`

### Textarea

- `.textarea`

### Button

- `.btn`
- `.btn-primary`

### Blockquote

- `.blockquote`

### A / Link

- `.nav-link`

## Elements TODO

<!-- Nav sets display flex, justify content space around -->

- `nav`
  <!-- Main sets margin var(--space-xl) auto and sets a min-height: 100vh on page.  -->
- `main`

  <!-- Figure class removes default figure padding.  -->

  - `figure`

<!-- Figcaption adds the typography classes to html figcaption element, which can replace writing an img alt tag for accessability. -->

- `figcaption`
  <!-- Time class adds typography classes to html time element. -->
- `time`
  <!-- Bold class adds a font-weight: 900 to the html bold element.  -->
- `bold`

## Functional CSS Classes

<!-- Set element to max-width of var(--container) -->

`.container`

<!-- Give element var(--small) padding -->

`.component`
