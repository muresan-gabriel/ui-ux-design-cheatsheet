<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="#" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">UI / UX Design Cheatsheet</h3>

  <p align="center">
    Tips, resources and guidance to help you develop application interfaces.
    <br />
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet/issues">Report a Problem</a>
    ·
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet/issues">Contribute</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#basic-design-principles">Basic Design Principles</a>
      <ul>
        <li>
          <a href="#contrast">Contrast</a>
        </li>
        <li>
          <a href="#proportion">Proportion</a>
        </li>
        <li>
          <a href="#hierarchy">Hierarchy</a>
        </li>
        <li>
          <a href="#white-space">White-Space</a>
        </li>
        <li>
          <a href="#unity">Unity</a>
        </li>
      <ul>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This repository was created with the purpose of assisting you with either tips or resources to create fantastic UIs.

* As a developer, your time should be dedicated towards programming and learning. Not all of us want to be designers, but sometimes we have to work on the visual part of the projects as well.
* UI is not just the looks of an application. UI includes UX. Every time a user interacts with your application, they should already be comfortable with your functionalities and know what each button is supposed to do.
* UI Design is NOT always font combinations, a good choice of color palette and advanced concepts and principles of art and design. Sometimes it's just CONSISTENCY.
* Overloading the UI with things you don't understand or don't know how to combine just yet is a bad practice. Constistency is easy to achieve and will bring immediate good results.
* Just like in development, you don't need to reinvent the wheel. Make use of available resources out there on the Internet. There are multiple FREE resources ready to be implemented in your projects. For example, we can make use of free icons available to us. They can take any form, from simple ```.svg``` / ```.png``` images, to HTML ```<i></i>``` elements from libraries of icons, such as <a href="https://fontawesome.com/icons">FontAwesome</a> or <a href="https://icons.getbootstrap.com/">BootstrapIcons</a>, to ```JSX``` components which you can copy to clipboard and paste in your projects.

### What to expect

This repository contains information and resources to help you create good UIs for your projects.

As I do not have any experience with applications outside of the web, I recommend you to stick to general tips and guidance and apply them to your projects in the way you find suitable. 

For example, for the UI of a desktop application, if you'd like to add an icon to a button, I suppose you'd save the image of the icon, add it to your project folder and use some kind of class methods to display that icon within the button.

You can use the Table of Contents to navigate to each section of interest.

Feel free to contribute with anything you think it's missing to help other developers or students.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BASIC DESIGN PRINCIPLES -->
## Basic Design Principles

### Contrast

Defined as the difference between elements within a design that makes them stand out from each other, contrast plays an important role in the visibility of each element. 

You should (almost) never put a blue text on a slightly lighter blue background. It affects the text's readability. 

Of course, you could bring the color of text closer to the background color to suggest that the text is secondary, informational and doesn't play a very important role in transmitting a message, but even it this situation, it should still be visible and readable for the user.

### Proportion

Refers to the size of the elements in relation to each other. Proportion and scale are important in hierarchy as well, as larger elements tend to appear more important.

Use proportion and scale in your advantage and define important elements, such as CTAs (Call to Actions) using scale, color, or shape.

### Hierarchy

We place elements accordingly based on levels of importance. You should also provide a visual solutions to this. A simple example would be making the title large (```24px```) in contrast to the paragraph of text (```12px```).

### White-Space

White-space is an important element in most designs. We can define empty spaces on a page on each side, left and right, and keep all the content in the center. For a blog post, this would allow the user to focus on the text, the most important element of an article, and it could be a solution to shorter lines of text, which are easier to follow.

For example, it's easier to read lines that are ```8-12``` words in length. We can easily follow to the next line and keep track of where we are in the article. It's harder to read text which has lines that are, for example, ```24-28``` words in length.

White space can also be a good separator between elements or clusters of elements (see <a href="#unity">Unity</a>).

### Unity

Defining clusters of elements that are related to each other offers a solid structure to your interface. For example, you should always stick all important elements related to navigation to the navbar / header menu, or, usually, you would keep the Login / Sign Up buttons together, not spread apart from each other.

__

These are 5 principles which I think you can easily apply to your projects for fast and clear improvements to the UI. There are 12 principles in total, and if you'd like to learn more about them, I strongly recommend a Google search.

All of these principles are:

1. Contrast
2. Balance
3. Emphasis
4. Proportion
5. Hierarchy
6. Repetition
7. Rhythm
8. Pattern
9. White space
10. Movement
11. Variety
12. Unity

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GENERAL TIPS & TRICKS -->
## General Tips & Tricks for UI/UX

### Keep things simple and consistent

This is one of the most important tip I can provide. Be consistent throughout your entire application. This refers to colors, fonts, sizes, shapes and more.

Create a default look and feel for your application.

* Choose a background color and stick to it.
* Choose a font-size for each element you think you'll have on your page, but limit yourself to a handful of different elements. Paragraphs of text should have a size of ```16px```. Apply these font-sizes consistently to your elements.
* Choose a few colors for your application. If you have an application which is heavily branded, your brand should have a set of colors (usually, at max, 3). Besides these colors, you should choose colors according to the elements of your application. If you have information alerts, depending on the type of alert, you'd want to use a specific color (e.g. red for danger, orange / yellow for warnings, green for success).
* If you have a set of brand colors in place for your project, choose the shade, tone and tint of the colors for your informational elements accordingly. If you have bold, intense colors for your brand, you'd want your red, green and yellow for your alerts to be just as bold. If you have a pastel, playful color palette for your brand, you'd want to use pastel green, red and yellow for your alerts as well.
* Besides defining a set of colors to use in your project, make sure to be consistent! Don't use a lighter shade of red or blue, use the exact same color, exact same ```RGB / HEX``` code.
* Your shapes should be just as consistent as your colors. If you're working on an application that you think would suit rounded corners, keep the value consistent throughout all elements. Don't enforce a button with a border-radius of ```25px``` and the parent container with a border-radius of ```20px```. Keep them the same.
* Use the same font everywhere. You need a good vision and a good understanding of typography to be able to combine fonts together. Use one type of font everywhere. Define the importance of the text based on size, and sometimes color, not based on the font. All of this text you're reading is displayed using ```Segoe UI```. GitHub stays consistent and uses the same font for messages, placeholder text in input elements or buttons. The only exception to this rule are markdown / code blocks. These are written using a monospace font called ```Consolas```.
* To further provide an example of consistency in GitHub, everything related to danger or aborting specific action is marked using red. The ```HEX``` value of this red is ```#DA3633```. The same blue is used in hyperlinks and the same green is used for CTAs or elements used in confirmation / submitting an action.
* Consistency can be found in size as well. Use the same size for buttons, the same border radius, and differentiate their importance by color. If the purpose of your application is to attract user registrations, which can make use of some free functionalities of your applications, later to be tempted to pay for access to more functionalities, you'd want to make your ```Sign Up``` button a CTA and have the ```Login``` button as a secondary option, next to the ```Sign Up```.
 
### Font recommendation

I suggest exploring <a href="https://fonts.google.com/">Google Fonts</a> and finding a font that fits your needs. It offers users the possibility of using ```imports``` in stylesheets or ```link``` elements to add to the ```head``` of your ```HTML``` document. You can also download an entire family or only specific font weights. Make sure to check the license before you use the font.

There are other websites to help you find good fonts, but I'd recommend sticking to Google Fonts, as they provide very good solutions for fast implementation of fonts in your projects.

I recommend implementing only ```2-3``` weights of a font family for your project. Stick to Regular and Bold / Extra-Bold / Black.

I also recommend, as mentioned before, to maintain consistency throughout your project. Use the same font size for paragraphs, the same font size for buttons (also the same heights / colors, depending of their use-case)

__

##### Personal font preferences

These choices are subjective and are fonts which I am familiar with and have used throughout various web projects. Consider taking this with a grain of salt.

* <a href="https://github.com/rsms/inter">Inter</a> - This is a fantastic font which was crafted and designed especially for computer screens. It's my go-to font for almost every project. See the <a href="https://fonts.google.com/specimen/Inter?query=inter">Google Fonts</a> page aswell.
* <a href="https://www.cufonfonts.com/font/segoe-ui-4">Segoe UI</a> - You're seeing it right now. GitHub uses Segoe UI by default. It should be available on any Windows OS version after Windows 7. I'm not sure about Linux distributions or MacOS, but you can download it for free from anywhere.
* <a href="https://fonts.google.com/specimen/Montserrat?query=montserr">Montserrat</a> - Fantastic font, loved by many.

These are a handful of fonts to use in your projects. Feel free to explore more. All of these are sans-serif fonts. I strongly recommend not opting for serif fonts, unless you have a specific reason to do so.

Either way, a good choice of serif fonts:

* <a href="https://fonts.google.com/specimen/Libre+Baskerville">Libre Baskerville</a> - Fantastic serif, usually a very good choice for blog posts and article bodies, or simply used in display headings.
* <a href="https://befonts.com/butler-font.html">Butler</a> - Very well crafted typeface for display and graphics.
