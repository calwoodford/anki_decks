<div align="center">
  <img height="60" src="https://upload.wikimedia.org/wikipedia/commons/6/62/CSS3_logo.svg">
  <h1>CSS Questions and Answers</h1>
    <br>
  <a href="https://ankiweb.net/shared/info/376600095?cb=1696104749579"> Download the Anki deck here </a>
  <br><br>
</div>

Question 1.
What does CSS stand for, and what is its primary purpose in web development?

<details><summary><b>Answer</b></summary>
CSS stands for Cascading Style Sheets, and its primary purpose in web development is to control the presentation and layout of web pages, including elements like fonts, colors, spacing, and positioning.

</details>
<br><br>
Question 2.
How do you link a external CSS file to a HTML document?

<details><summary><b>Answer</b></summary>
To link an external CSS file to a HTML document, you use the < link > element in the HTML document's < head > section. The < link > element specifies the stylesheet's path using the href attribute.

</details>
<br><br>
Question 3.
What are the three primary ways to include CSS styles in a HTML document?

<details><summary><b>Answer</b></summary>
The three primary ways to include CSS styles in a HTML document are inline styles, internal styles, and external styles. Inline styles are applied directly to a HTML element using the style attribute, internal styles are defined within a < style > element in the HTML's < head >, and external styles are stored in separate CSS files linked to the HTML document.
 
</details>
<br><br>
Question 4.

Explain the concept of specificity in CSS and how it affects the application of styles.

<details><summary><b>Answer</b></summary>
Specificity in CSS refers to the rules that determine which styles are applied to an element when conflicting styles exist. It is calculated based on the type of selector and the number of IDs, classes, and elements used. More specific selectors take precedence
 
</details>
<br><br>
Question 5.
What is the purpose of media queries, and how do you use them to create responsive layouts?

<details><summary><b>Answer</b></summary>
<p>
Media queries in CSS are used to apply different styles to a web page based on the characteristics of the device or screen it's viewed on, such as width, height, or orientation. By defining specific conditions in media queries, we can create responsive layouts that adapt to various screen sizes and devices, ensuring a better user experience across different platforms.
</p>
</details>
<br><br>

Question 6.
What are CSS selectors and how do they work?

<details><summary><b>Answer</b></summary>
<p>
CSS selectors are patterns used to select and style HTML elements. They define the elements to which a set of CSS rules should be applied. Selectors can target elements based on their type, class, ID, attributes, and more.

For example:

Element Selector: Targets specific HTML elements. Example: p { color: blue; }
Class Selector: Targets elements with a specific class attribute. Example: .my-class { font-weight: bold; }
ID Selector: Targets a single element with a specific ID attribute. Example: #my-id { text-decoration: underline; }
Attribute Selector: Targets elements based on their attribute values. Example: input[type="text"] { background-color: #f0f0f0; }
Selectors can also be combined to create more specific and targeted styles.

</p>
</details>
<br><br>
Question 7.
What are CSS transitions, and how can they be used to create smooth animations?

<details><summary><b>Answer</b></summary>
CSS transitions allow for smooth animations by gradually changing property values over time. They can be used for various effects like fading, sliding, or scaling elements
 
</details>
<br><br>
Question 8.
What is the concept of "inheritance" in CSS and how does it affect the cascading nature of styles?

<details><summary><b>Answer</b></summary>
Inheritance in CSS refers to the mechanism by which styles are passed down from a parent element to its child elements. Child elements inherit styles from their ancestors unless overridden by specific rules.
 
</details>
<br><br>

Question 9.
Question: What is the difference between margin and padding in CSS?

<details><summary><b>Answer</b></summary>
<p>
Margin: Margin is the space outside the border of an element. It clears the area between the border and adjacent elements. It does not have a background color, and it's transparent by default. Margin is used for creating space between elements.
Example: margin: 10px;

Padding: Padding is the space between the content of an element and its border. It clears the area between the content and the border. Padding is often used to increase the readability and aesthetics of the content inside an element.
Example: padding: 10px;

In summary, margin is the space outside the border, and padding is the space inside the border around the content.

</p>
</details>
<br><br>

Question 10.
Question: How can you use CSS to create a responsive navigation menu for different screen sizes?

<details><summary><b>Answer</b></summary>
<p>
You can use CSS to create a responsive navigation menu for different screen sizes by using media queries to adjust the menu's layout and appearance based on the device's width. This can include changing menu styles or converting it into a dropdown for smaller screens.

</p>
</details>
<br><br>

Question 11.
Question: Describe the CSS "z-index" property and explain its use in stacking elements.

<details><summary><b>Answer</b></summary>
<p>
CSS "z-index" is used to control the stacking order of elements. A higher value brings an element to the front of the stacking context.

</p>
</details>
<br><br>

Question 12.
Question: What is the CSS pseudo-class and how is it used in styling elements?

<details><summary><b>Answer</b></summary>
<p>
A CSS pseudo-class is a keyword that specifies a special state of the selected element(s). Pseudo-classes are used to style elements when they are in a certain state or condition, such as when a user hovers over an element or when an element is the first child of its parent.

Example:
a:hover {
    color: red;
}

</p>
</details>
<br><br>

###### Question 13.

How do you include custom fonts in a web page using CSS?

<details><summary><b>Answer</b></summary>
<p>

To include custom fonts in a webpage using CSS:

1. Choose a custom font source.
2. Host or download font files (e.g., .woff, .woff2).
3. Define the `@font-face` rule in your CSS with the font-family and src properties.
4. Apply the custom font using the font-family property to specific HTML elements.
5. Link your CSS in your HTML document's head section.

This allows your webpage to use the specified custom font.
</p>
</details>

<br><br>

###### Question 14.

How do you center an element horizontally and vertically using CSS?

<details><summary><b>Answer</b></summary>
<p>

To center an element both horizontally and vertically in CSS, use Flexbox or CSS Grid. With Flexbox, apply "display: flex" and use "justify-content" and "align-items." For CSS Grid, use "display: grid" and "place-items: center."

</p>
</details>

<br><br>
