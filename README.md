# Project 5: CSS to Sass

## Project Instructions
In this project you will convert a CSS stylesheet to Sass. You'll refactor the stylesheet from the "Responsive Layout" project using SCSS partials, variables, extends, and mixins.

## Before you start
- Collect your completed files from the "Responsive Layout" project.
  - Make a copy of the “Build a Responsive Layout” project and use those as a starting point.
  - Create a new GitHub repository for this project when it is completed and ready for submission.

## Project Instructions
**Create a 'scss' folder in your "Responsive Layout" project.**

**Convert the CSS stylesheet to an SCSS stylesheet, then place it inside the 'scss' folder.**

**Run Sass from the console or with a tool like CodeKit, Workspaces, or any of these.**

**In the 'scss' folder, create subfolders to organize your CSS code into Sass partial files.**
- For example for base styles, layout, components, and so on.
- Create at least three folders.

**Group related sections of CSS into SCSS partials.**
- For example, base styles for elements can go inside a `_base.scss` partial inside the 'base' folder.
- Create at least 3 Sass partial files.
**Import your partials into your project's main SCSS file.**
- When using multiple @import’s make sure they are listed in the correct order for styling.

**Find repeating patterns in the stylesheet and extract them into placeholder selectors, then extend them wherever necessary.**
- At a minimum create at least one placeholder selector, and use it with the @extend keyword in at least 3 other selectors.

**Create variables for repeating values. At a minimum create variables for colors, font-sizes and font-family values
Write mixins for media queries.**

**Create at least one example of a nested Sass rule. For example:**
```
nav {

      ul {

          margin: 0;

          padding: 0;

          list-style: none;

      }

  li { display: inline-block; }

  a {

      display: block;

      padding: 6px 12px;

      text-decoration: none;

     }

  }
  ```
  No nested rules greater than 3 levels deep. For example:
```
.weather {

    .cities {

        li {

             // no more!

        }

    }

}
```

**You don’t need to make any changes to your original design, but make sure the site is still responsive and works well on different screen sizes.**

**Make sure to check your code is valid by running it through an HTML and CSS validator.**
- Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
- **There are a few exceptions that you don’t need to fix:**
  - Don’t worry about any warnings, we just need you to check any errors that might be there.
  - If CSS validator flags use of calc, vendor prefixes or pseudo-elements/pseudo-classes these errors should be ignored.
  - If HTML validator flags use of pipe (‘|’) in Google font links/URLs this error can also be ignored.

**NOTE:** A good practice is to check your project for cross browser compatibility. Making sure that it looks and functions correctly in multiple (at least three) browsers is an important part of being a top-notch developer. If you want, leave a comment to the project reviewer about which browser(s) the project was checked to ensure they are seeing things as you have designed them.

Some browser options:
- Google Chrome
- Mozilla Firefox
- Internet Explorer/Edge
- Safari

## Extra Credit
**Create multiple subfolders (more than 3) for organizing styles.**

**Create multiple SCSS partial files (more than 3).**

**Multiple (more than 1)placeholder selectors**

**Multiple (more than 3) uses of @extends with placeholders**

**Multiple (more than 1) additional Sass variables (not just color, font-size, font-family).**

**Include at least 1 additional mixin for other code (not just for media queries)**

**Create more than 3 nested Sass rules where appropriate.**

**Using JavaScript or CSS/Sass, include an icon that, when clicked toggles the navigation on and off when on mobile screen sizes.**


## How You'll Be Graded

### Meets Expectations

+ Includes a 'scss' folder (**COMPLETE**)
+ Convert the CSS stylesheet to an SCSS stylesheet (**COMPLETE**)
  - Converts the stylesheet
  - Adds to correct scss folder
+ Includes at least 3 well named subfolders (**COMPLETE**)
+ Groups related sections of CSS into 3 SCSS partials (**COMPLETE**)
+ Import partials into your project's main SCSS file (**COMPLETE**)
+ Find repeating patterns and extract into placeholder selectors, then extend wherever necessary.
  - 1 placeholder selected
  - @extend used with placeholder in 3 styles
+ Create variables for repeating values (*TODO: color and font-family are done, need to do font-size*)
  - Sass variables for color, font-size, and font-family
+ Includes mixins for all media queries
+ At least one example of a nested Sass rule
+ No nested Sass rule greater than 3 levels deep
+ Site is still responsive and works well on different screen sizes
+ Valid Code
  - HTML and CSS code passes the validation
  - HTML and CSS errors are accepted exceptions
