Requires:
sass

``` 
gem install sass
```

bourbon

```
gem install bourbon
``` 

neat

``` 
gem install neat
``` 

bitters

```
gem install bitters
``` 

takes code from refils

Structure:

- Project/Site - folder
- index.html
    - css - folder
    - sass - folder
        - app.sass
        - _mixins.scss
        - _variables.scss,
        - _reset.scss
        - lib - folder

adding Bourbon and Neat to their directories

```
cd scss

bitters install

cd scss/lib

bourbon install
neat install
``` 

add bourbon and neat imports

```
// in app.sass

// import bourbon and neat libraries, with bourbon first
@import "lib/bourbon/bourbon.scss";
@import "lib/neat/neat.scss";

// import user partials
@import "_reset.scss";

@import "_variables.scss";

@import "_mixins.scss";

command for tracking sass

sass --watch scss:css
``` 


sudo gem install x
x install

With Bourbon I need to decide what functions and mixins to use for examples
+size
+position
+fonts - show the use of fonts and their declaration of backups. Good replacements are preselected
Try showing a clearfix
+clearfix
predefined easing functions

Neat
examples of span columns
show the visual grid

Bitters
Is generating output css
try using a minified normalize function

Padding vs margin will effect if a line shows up at the bottom of the grids
