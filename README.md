# SCSS styleguide

## CSS Architecture: Scalable and Modular Architecture of CSS (SMACSS) and <br> Blocks, Elements, Modules (BEM)

### File Structurure used: SMACSS
  
### Class name styles: BEM 

  ## Formatting
  - Use tabs for indention
  - Use dash (-) instead of Camelcasing for class names, or __ and -- if using BEM structure
  - No use of ID selectors
  - Only one property per line
    (font-size: 1em;
      color: black;)
  - Add space before opening bracket { 
  - All classnames must be small letters
  - In properties, put a space after colon (:) (i.e. font-size: 2em);
  - Each scss file should have comment header to identify its module/component
  
  **Format**
  ```
  .categories {
	  display: flex;
	  margin-top: 50px;
  }
  ```
  
  ## San Francisco Architects File Structure
  
    - SCSS
      - Modules
        - Module folder
          - SCSS file
          - JS file
      - _base.scss (contains normalize and general semantics styles)
      - _layout.scss
      - _global.scss
      - _modules.scss (imports all components found in Modules folder)
      - _utils.scss (imports all third party i.e. bootstrap)
      - _variables.scss
      - style.scss
 
   ## Prefix meaning
   
   In San Francisco architect html files, I've used prefixes which will direct developers to specific scss files. Below are as follows:
   
   **L** - all class names with prefix "L" (i.e l-overview, l-categories) can be found under _layout.scss
   
   **G** - all class names with prefix "G" which represents modules/components (i.e. g-section__title) can be found under _global.scss
      
   
   
   
