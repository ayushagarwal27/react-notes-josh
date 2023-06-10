# BEM - Block Element Modifier

      search-form  Block
      search-form__input Element
      search-form_focused Modifier

1. global unique names
2. need to remember syntax

## Automatic scoping

   - CSS Modules
   - Style Components

*Top level element like div named as 'wrapper'*

**CSS Modules**
- long names having component name inside it.
- short names gets expanded to longer names by build process
- Webpack treats the CSS module as a “default export”, and so we can name it whatever we like.

- keeping classNames same as type, will save time and work.

- use clsx package
