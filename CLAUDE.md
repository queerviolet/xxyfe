this is a static site which is pushed to github pages.

style notes for HTML files:

- we keep things human readable
- we don't use quotes around tag values unless we need to (i.e. they contain spaces or other characters)
  say:
    <h1 class=big>Hello</h1>
  rather than:
    <h1 class="big">Hello</h1>
- we use implicitly opened / closed tags when possible
- we don't create CSS classes unless we have to
  - e.g. if we only have one `<header>`, we just put the styles on `header { }`
  - if we need another `<header>`, then we'll add a class to both
