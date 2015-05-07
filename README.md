# Debussy

Debussy is a CSS/Sass standard for keeping your rules readable.

Also see [Amadeus](https://github.com/ajkochanowicz/Amadeus) for CSS Variable specs and [Chopin](https://github.com/ajkochanowicz/Chopin) for CSS selector specs.

## Example

    selector1,
    selector2 {
      first-attribute: first-property;
      second-attribute: second-property;
      
      subselector1,
      subselector2, {
        first-attribute: first-property;
        second-attribute: second-property;
      }
      
      &:appended-selector1,
      &:appended-selector2 {
        first-attribute: first-property;
        second-attribute: second-property;
      }
      
      @media screen and (min-width: 100px) {
        /* Media query for selector1, selector2 */
      }
    }
    
    selector1 { /* Selector 1 only rules */
      first-attribute: first-property;
      second-attribute: second-property;
    }
    
    selector2 { /* Selector 2 only rules */      
      first-attribute: first-property;
      second-attribute: second-property;
    }
