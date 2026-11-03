# Research Paper Toolbox

COM321 Sustainable Information Structure Project - Praveen Maramreddy

Open `index.html` after extracting the entire project. No build tools or JavaScript are required.

## Files

- `index.html`: home page and module links.
- `modules/research.html`: research resources lesson.
- `modules/data.html`: data organization and analysis lesson.
- `modules/placeholder.html`: shared destination for six future modules.
- `modules/template.html`: reusable examples of every recurring lesson structure.
- `css/styles.css`: the one stylesheet shared by all pages.
- `images/`: supplied lesson illustrations, preserved as provided.
- `downloads/`: the tutorial spreadsheet used in the Data lesson.

## Adding a module

1. Copy `modules/template.html` to a descriptive filename in the same folder.
2. Update the page title, description, main heading, and example content.
3. Give sections unique IDs and update the lesson contents links to match.
4. Add illustrations with accurate alt text and visible captions. Use ordered lists for procedures, unordered lists for related items, definition lists for terms, and asides for supporting advice.
5. Keep the shared stylesheet link. Update the top navigation on every page and the module list on the home page.
6. Validate the HTML and check links, keyboard navigation, and narrow-screen layout.

The lesson copy and screenshots describe the software and library systems in the supplied course materials. Quizzes were excluded from the assignment's scope. Links embedded in the Word copy have been restored; the UCLA and research-service URLs use current destinations.

## Self-critique

I organized the toolbox around a shared home page and one page for each completed module. Section links let readers move through long lessons without splitting the instructions across many files. Numbered lists identify procedures, while bullet lists and definition lists group related information. Sidebars separate supporting advice from the main lesson, and captions explain the supplied screenshots. Following feedback, I corrected missing list structures and captions, narrowed the reading area, changed the body font, and moved the shared stylesheet into a dedicated folder. The template demonstrates the structures used throughout the lessons so another author can add modules consistently. Skip links, descriptive image text, and visible keyboard focus support accessibility. With more time, I would test the navigation with more readers and review the older screenshots and software instructions with the content owner.

## Verification

All five HTML pages passed the HTML5 validator without errors or warnings. Internal page links, section anchors, image paths, and the spreadsheet download resolve. Chromium checks at 1440px and 390px found no horizontal overflow or broken images. The keyboard skip link reaches the main content on every page. Automated axe checks reported no WCAG A/AA violations in those viewports; this is not a substitute for user testing.
