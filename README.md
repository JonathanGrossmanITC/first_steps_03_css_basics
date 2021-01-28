# CSS Basics  

Welcome to the third lesson! In this lesson, you learn the basics of CSS. You start with an introduction to CSS in which you learn about CSS syntax, basic style properties, and how to connect your HTML and CSS. Next, you learn how to write your own custom CSS classes by writing classes for common features on a webpage. Finally, you see a live coding example of using CSS to style a webpage. The live coding session reinforce what you learn in the lesson, and also demonstrates how to make animations. 

This lesson helps prepare you for making your personal portfolio site. The code from the session is included in this repository. You can use it however you like, but as with any code you get from someone else, make sure you understand it well enough to explain it to someone before putting it in your own projects.  

In this lesson, you learn:  

- Hour 1: [Intro to CSS](#intro-to-css)    
- Hour 2: [Writing Custom CSS Classes](#writing-custom-css-lasses)   
- Hour 3: [CSS Live Coding](#css-live-coding)  

The topics below outline what you learn in the live session. After the live session, you can use this material as a resource for guided self-learning. This document will serve you as a roadmap for gaining repetition with the material that you learn during the live session.   

Also included in this material is the code from the live coding session.  

## [Intro to CSS](#intro-to-css)  

  ### CSS Getting Started
  
  - CSS is the language for adding style to webpages  
  - Use styles to control properties of your HTML elements, like color, height, width, layout, font type, and more
  - Here is a [list of CSS properties](https://www.w3schools.com/cssref/)  
  - Write CSS code in a .css file or in your HTML file using the `style` attribute or `script` tags  
  - Recommended to use a .css file instead of the other options because it is easier to maintain  
  - Whichever style approach you use, be consistent, intuitive, and predictable so that reading and maintaining your code is easy  
  - When using a .css file, import it inside your HTML file in the `head` tag using a link tag having its `src` set to the .css file's relative path  
  
  ### Syntax
  
  - In your .css file, use the following syntax:
  
  ```css
  
  div {
      border-radius: 5px;
      color: orange;
      font-size: 18px:
      padding: 10px
      margin: 10x
  }
  
  .name-of-your-class {
      // style propeties here
      background-color: blue;
      font-size: 24px:
      padding: 10px
    }
  ```
  - If writing a class for a tag type, you use the tag name: `p { . . .}` and the class applies to all tags of that type
  - The class name starts with `.` for custom classes followed by a name you give it; set any HTML element's `class` attribute to that name to give it that class's style     
  
  - In your HTML file, apply the class to HTML elements like this:
  
  ```html
    <div class="name-of-your-class>Welcom to ITC!</div>
  ```
  - You can apply a CSS class to as many HTML elements as you want  
  - For custom names, use names that describes the HTML element 
  - Make your custom CSS names nouns because your classes apply to objects, not functions  
  - Good names help bring your code to life when someone reads it!  
  - After the tag type or name is an object `{ }` comprised of key:value pairs separated by a semi-colon   
  - Each key is the name of a CSS property and each value defines that property for the class you're writing. 
  
  - When using the `style` attribute, you set an HTML element's style attribute to a string (not an object) containing key:value pairs separated by a semi-colon  
  - Like in a .css file, each key is the name of a CSS property and each value defines that property for the class you're writing  
  - Here is an example inside an HTML file:
  
  ```html
      <p
        style="
              background-color: aliceblue;
              color: gray;
              margin: 10px;
              padding: 20px;
              width: 50%;
            "
      >
        This is text inside a paragraph tag.
      </p>
    ```
   
  ### Examples of CSS Style Properties for Design  
  - [margin](https://www.w3schools.com/css/css_margin.asp)  
  - [padding](w3schools.com/css/css_padding.asp)  
  - [height and width](w3schools.com/css/css_dimension.asp)  
  - [colors](https://www.w3schools.com/css/css_colors.asp)  
  - [links](https://www.w3schools.com/css/css_link.asp)  

  ### Examples of CSS Style Properties for Layout  
  - [`position` style property and its cousins top, right, bottom, left](https://www.w3schools.com/css/css_positioning.asp)  
  - [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  
  - [Grid Layout](https://css-tricks.com/snippets/css/complete-guide-grid/)  

## [Writing Custom CSS Classes](#writing-custom-css-lasses)   
    
## [CSS Live Coding](#css-live-coding)  
  1. Add add an animation that changes a button's background color when hovered over  
  2.  
  3.  
 
With some knowledge and resources in hand, now you are ready for live coding. In the live coding session, apply what you learned above. As an extra challenge, the last task asks you to do something you haven't yet learned. The tasks are:  
 

