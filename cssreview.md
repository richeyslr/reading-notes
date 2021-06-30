# CSS Review

### What is CSS
- Cascading style sheets
- help create good looking webpages
- controls look of HTML elements
- rule based language

### CSS Syntax
- define rules by specifying style groups
- selector defines HTML element to style
- `{declaration}` made of `property: value;`

### Inserting CSS
- External CSS
    -only change one file to change styling
    - HTML must include reference to .css file `<link rel="stylesheet" href="style.css">`
- Internal CSS
    - used if one HTML page is styled uniquely
    - defined inside `<style>` element in `<head>`
- Inline CSS
    - used if one HTML element styled uniquely
    - added as attribute to element
    - `<h1 style="color:blue;text-align:center;">This is a Heading</h1>`
- Multiple stylesheet
    - takes style defined latest in `<head>`
    - Cascading order
        - inline
        - external and internal
        - browser default
