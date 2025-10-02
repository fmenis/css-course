# CSS3 course

## Links

- [CSS3 complete course](https://www.youtube.com/watch?v=OXGznpKZ_sA&list=PLWKjhJtqVAbnSe1qUNMG7AbPmjIG54u88&index=7)

## Best practices

- don't use inline style, prefer external stylesheet
- don't use id selectors, prefer class selectors
- order matters in the definition of css rules. Eg: if a rule change the color inside a p within an external file and the same rule is added inline, the inline rule wins
- form elements (button, input, textarea, select) don't inherit fonts settings
- put font settings in html selector
- don't use the !important rule (indicates that css is not well organized)

## Specificity

TBD
class selectors wins over element selectors
id selectors wins over class selectors (but we don't want to use them)
https://specificity.keegan.st/
