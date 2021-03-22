# Resume Site

This is pretty overkill for such a simple site, but it was a fun way for me to learn [Jekyll](https://jekyllrb.com/) and brush up on my CSS. This also let me create a fresh baseline project for future sites to build off of.

## Assets

- [Jekyll](https://jekyllrb.com/)
- [Bitters](https://github.com/thoughtbot/bitters)
- [HTML5 Boilerplate](https://html5boilerplate.com/)
- [ionicons](https://ionicons.com/)

## Perks of Jekyll

All of the info on my resume can now be updated without updating or duplicating any sections, lists, or paragraphs. For example, I can list each job experience in the [experience.yml](_data/experience.yml) file like this:

```yaml
- company: Bethel University
  position: Salesforce Administrator
  duration: April 2018 &ndash; Present
  summaries:
    - bullet: Problem-solve complex business needs and adapt them into usable Salesforce enhancements.
    - bullet: etc...
```

and the Jekyll [index.html](index.html) file will loop through the data and render it into the correct tags and classes.
