# Process Writeup

## Name: Aaron Williams
## Course: SEP10 Web Design
## Period: 7
## Concept: Css
## 11/03/24

## Introduction
## Currently I'm learning the basics of CSS. CSS, or Cascading Style Sheet, is a language model that i use to style HTML elements. This allows me to control the appearance of web pages; this includes color, fonts,layouts, and etc.

## Experiences while Learning Css
## Overtime, I've been exploring the fundamentals of CSS, it's been amazing while also challenging journey. I've learned how to select elements using various selectors such as class,ID, and elements selectors. With these selectors, I can apply specific style to different 
parts of my web page.

## Challenges
### Something that I often struggle with is being unorganized, either in my personal life or working, when I'm in the zone. I don't think about the later, so often when I write my CSS, it's often unorganized, which later led me to be confused and made it hard for me to maintain order in my style sheet. My CSS lacks a clear structure as most of the class names are generic and don't provide any context what so ever. I've learned that I should use more descriptive names that help others understand. While also helping me maintain my style sheet. This right here is an example of how my CSS used to look like before. I have outside help to help me improve.
```
Ex-
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

h1 {
    font-size: 36px;
    text-align: center;
    margin-bottom: 20px;
}

p {
    font-size: 16px;
    line-height: 1.5;
    margin-bottom: 20px;
}

.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;   

    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

.image {
    width: 300px;
    height:   
 200px;
    margin-bottom: 20px;
}

```
### I discovered that my CSS had odd spacing and indentation when I initially reviewed it following peer review. It frequently makes it more difficult for others to read and comprehend the code. I spoke with a friend about CSS, and he suggested that I start using comments since they help to explain the objective of each style or piece of code I've heard about my teacher's comments before, but I've never understood their significance. It was "a waist of time" as I thought, when my friend showed me their CSS. It was understandable and clear. I decided to totally rewrite my CSS because of it.
## Solution
```
Ex-
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Typography */
h1 {
    font-size: 36px;
    text-align: center;
    margin-bottom: 20px;
}

p {
    font-size: 16px;
    line-height: 1.5;
    margin-bottom: 20px;
}

/* Layout */
.main-container {
    width: 80%;
    margin: 0 auto;
}

/* Components */
.primary-button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;   

    margin: 4px 2px;
    cursor: pointer;   

}

.product-image {
    width: 300px;
    height: 200px;
    margin-bottom: 20px;
}
```
### Although I've heard of my teacher'c comments before, I've never really grasped the significance of them. CSS comments aid in explaining the purpose of every style sheet or every piece of code. I considered "a waste of time". Has actually come to use for me as it helps me grasp the concept of CSS and how to organize it. To not just help me understand but for peers to understand the code, even if they didn't write it.


