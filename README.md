foundation-style-prototype
==========================

Zurb Foundation Style Prototyping Yeoman

Branched off of the [style prototype generator](https://github.com/Team-Sass/generator-style-prototype), modified to use [foundation 4](http://foundation.zurb.com/docs).

Some additional helper functions
- **{{{button | Classes | Text}}} - foundation button**
  - example: {{{button "large alert" "Large Alert button"}}}
  - output: 
    ``` html
    <a href="#" class="button large alert">Large Alert button</a>
    ```
- **{{{link | Text | Classes}}} - simple link**
  - example: {{{link "Explore Careers" "bold"}}}
  - output: 
    ``` html
    <a href="#" class="bold">Explore Careers</a>
    ```
- **{{{icon | Icon set | Icon name}}} - foundation icon**
  - where icon set is
    - "gen" - general
    - "enclos" - enclosed general
    - "social" - social icons
  - example: {{{icon "gen" "search"}}}
  - output: 
    ``` html
    <i class="genicons-search"></i>
    ```
- **{{{image | src}}} - simple image**
  - example: {{{image "facebook.png"}}}
  - output: 
    ``` html
    <img src="/images/facebook.png">
    ```
- **{{{placeholder | width | height}}} - placeholder image from placehold.it**
  - example: {{{placeholder "200" "200"}}}
  - output: 
    ``` html
    <img src="http://placehold.it/200x200">
    ```