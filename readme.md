
[deployed page](https://7300aaa2-bebc-47e7-b8b4-f840c4d90643.hubspotpagebuilder.com/practicum-two-torcellini)

## Overview 
Gauges proficiency in the following skills:
- Web accessibility
- Website performance
- Creating optimized themes, sections, and modules in the CMS
- SEO

Uses
- Template layouts
- Reusable section templates
- Partials
- Modules
- Theme fields for account brand settings


## Requirements:
### Accessibility
- Free of issues when using the Axe DevTools browser extension.
- Score of 100 using Lighthouse’s accessibility audit on both Desktop and Mobile devices.
- Functioning skip to content link.
- Page should reflow appropriately when zoomed up to 200%.

### Performance
- Score of at least 90 using Lighthouse’s performance audit when testing on both Desktop and Mobile devices.
- In Team Module, use the resize_image_url function to resize images used in the module. For this exercise, using srcset and sizes attributes is optional. Include height and width attributes on the image using HubL.
- The image within your module should be lazy-loaded, by default.

### Themes, Sections, and Modules
- Theme-Level Requirements
    - Your theme should include at least one page template, which extends a base.html template, as outlined in the video, “Reducing Code Repetition in Your Theme.”
    - Your theme should contain a main.css file and at least one other css file (e.g., _layout.css) which you should include in your main css file, using the include tag, as outlined in the video “Reducing Code Repetition in Your Theme.” Your main.css file should be included in your base.html file.
    - Your fields.json file should contain at least three theme colors that inherit from the account’s brand settings. It should also contain an option to set the header and footer background color, as in the original practicum. You must use field groups.
- Section requirements
    - Your theme should contain at least two reusable section templates that you include in your page’s template, as outlined below:
        - Create an image and text section that uses the image and text content from the original practicum.
        - Create a team members section, that includes a rich text module with a heading and your custom team module.
        - Your section templates should include a screenshot so editors can easily visualize them in the page editor.
- Module requirements
    - Update your team module to include at least one style field (e.g., a border).
    - Your style field should belong to a field group as outlined in the video, “Building Custom Modules.”
    - Use the require_css tag, scope_css tag and a generated CSS property to apply the style from the style field to each module instance, as outlined in the video “Building Custom Modules.”

### SEO
- Your page should pass Lighthouse’s SEO audits on both Desktop and Mobile devices.
- You do not need to use Lighthouse or Google Chrome, but your page should be able to pass all of the audits outlined in the Lighthouse SEO audits documentation.
    - Note: You do not need to pass the “Page is blocked from indexing” audit since pages in CMS sandbox accounts cannot be indexed
- Your page should be mobile-friendly. Pages that are not fully responsive at all breakpoints will not meet the practicum requirements.
- Your page should pass the SEO requirements within HubSpot’s page editor.
- Your page must include a valid and appropriate title and meta description.

## hs cli commands

hs watch src dev-practicum-two

hs fetch dev-practicum-two src -o