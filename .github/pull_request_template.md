# Fixel check list

## Component

- [ ]  Check if CSS is being overwritten on the original layout without customizing the current component
- [ ]  Create dummy data for components to support sample display
- [ ]  Reuse existing components
- [ ]  Check consistency between component and design (figma)
- [ ]  Check inject event communication between parent & child component.
- [ ]  Use console.log() to display the successful execution of the event
- [ ]  Break down complex components into smaller components
- [ ]  If using an external library in case of a new install compared to the client's existing library:
    - [ ]  Check if the library is still supported by the operator
    - [ ]  Check for available licenses for commercial use

## HTML

- [ ]  Test with markupLint
- [ ]  Check the semantic structure of the components
- [ ]  Do not place CSS inline
- [ ]  Check for duplicate IDs

## CSS

- [ ]  Use Slot to create local layers
- [ ]  When creating a util class, you must follow the white space spacing rule
- [ ]  Check class naming according to BEM rules
- [ ]  Check for unused styles
- [ ]  Set a class name that matches the component naming from figma

## CODE

- [ ]  Check duplicate ID
- [ ]  Check the impact of custom components
- [ ]  Check for spelling errors
- [ ]  Commit / push must be intuitive in the actions performed
- [ ]  Eliminate unnecessary commands
- [ ]  Remove commented code
- [ ]  Check the naming of variables and function names (do not use acronyms)
- [ ]  Remove console.log for debugging
- [ ]  Check for errors and warnings in the browser
- [ ]  Check EventListener initialization and destruction
- [ ]  Use let instead of using the var keyword to declare variables
- [ ]  Don't use global variables, use local variables with the smallest possible scope
