## JSConf BR 2014

### Overall Task
- Reproduce the website: http://2014.jsconfbr.org/
- Skip any animation.
- Skip the Google Maps section.
- Make sure you implement links as links (you can use "#" as the href)
- Make sure you see an appropriate mouse pointer when you hover over linkable items.
- Make sure you implement the rollover effects in the Speakers section (feel free to - use lorem ipsum text here).
- Make sure you duplicate the narrow strip of gray at the top of the page.
- Make sure you duplicate the fixed positioning of the navigation bar.
- Implement responsive features. Almost all sections of the page change at different widths. Don't forget to check them all. In particular, pay attention to the layout of photos in the Speakers section, and the format of the individual sessions in the Schedule section.
- Note that the Sponsors section is a bit tricky due to inconsistencies. Don't stress too much about the exact appearance of this section.
- Use semantic HTML wherever possible. In particular, take a closer look every time you're tempted to use a `<div>` or `<span>`.
- Try to avoid over-qualified selectors. For instance, do you need to say `main p em.green` when `.green` is all you need?
- Make sure your HTML markup passes the W3C Validator.
- Make sure your CSS passes the W3C CSS Validator.
- Consider using an HTML or CSS linter (see the Install Software assignment in Lesson 1 of LS202) to identify potentially troublesome HTML and CSS.
- Inspect your work several browsers if you can, including mobile.
- Use blink comparisons to identify discrepancies.

### Header
- *Note* not set up in mobile version of current site
- Push below the hero image?
- Nav
  1. Tickets
  2. Speakers
  3. Schedule
  4. Location
  5. Call For Papers
  6. Sponsors
  7. Code of Conduct

- Heading
  + Hero image is the background
  + Logo accessible
  + h1 Text
  + h2 / h3 text

- Hero image
  + Not accessible

### Tickets
  + H2
  + Descriptive info
    * Link
    * Text

### Speakers
- Images
  + Accessible
  + Caption
    - Name
    - Description
- Hover
  + rollover effect
  + embedded text

### Schedule
- Time
  + Lines up next to a speaker's image if event related to a speaker
- Event
  + Event with a reference to a speaker links to their speaker profile

### Location
- Skip