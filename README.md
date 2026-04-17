# Project-Homepage

A learning project focused on web accessibility (A11y). This portfolio website demonstrates fundamental accessibility principles and best practices for creating inclusive web experiences.

## Accessibility Features

### Semantic HTML

- Proper use of HTML5 elements: `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<address>`
- Landmarks: `role="banner"`, `role="contentinfo"`, `role="img"`
- Sectioning elements with `aria-labelledby` for programmatic association

### Navigation

- Navigation regions wrapped in `<nav>` elements with descriptive `aria-label`
- Skip links (implicit via proper heading structure)
- Logical heading hierarchy (`h1` → `h2` → `h3`)

### Images & Media

- All images have descriptive `alt` text
- Decorative icons marked with `aria-hidden="true"`
- Profile image includes `role="img"` and descriptive `aria-label`

### Links & Interactive Elements

- All links have descriptive `aria-label` for screen readers
- Phone numbers use `tel:` href for native dialer integration
- Email uses `mailto:` href for native mail client

### Form & Contact

- Address wrapped in `<address>` element for semantic markup
- Contact links are focusable, tab-accessible elements

## Accessibility Guidelines Followed

- WCAG 2.1 Level AA
- WAI-ARIA Best Practices
- Semantic HTML specification
- Focus management best practices

## Testing

Validate accessibility with:

- Browser developer tools (Accessibility panel)
- [axe DevTools](https://www.deque.com/axe/devtools/)
