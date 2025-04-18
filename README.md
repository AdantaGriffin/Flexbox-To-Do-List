# Flexbox: To Do App

## Overview
In this project, you will follow step-by-step instructions to fix a to-do web app. All of the HTML and most of the CSS is intact, however, a few Flexbox values are missing.

In order to complete this project, you must know how to set an element’s Flexbox properties.

## Installation
Set up a html:5 and css doc in your text editor of choice.

## Steps
1.
Start off by turning some of the elements into <code>flex</code> and <code>inline-flex</code> containers.

    Turn elements with the class container and elements with the class square into flex containers.
    Turn elements with the class week and elements with the class reminders into inline-flex containers.

To do this, add the display property with a value of either <code>flex</code> or <code>inline-flex</code>.

2.
The elements inside the new <code>inline-flex</code> containers should grow to fill the container. This is accomplished using the <code>flex-grow</code> property:

    Elements with the class .week will get a flex-grow property with a value of 3.
    Elements with the class .reminders will get a flex-grow property with a value of 2.

3.
We want the flex items with the class week to be ordered vertically, instead of horizontally.

Inside the <code>.week</code> ruleset, add a <code>flex-direction</code> property with the value that orders the items in a column.

4.
The items with the class <code>row</code> should move to the next line when the container gets too small.

Inside the <code>.row</code> ruleset, add a .ro<code>.row</code> property with the value that moves items to the next row, while keeping their order intact.

5.
The items with the class row also need some space:

Inside the <code>.row</code> ruleset, add a <code>justify-content</code> property with the value that adds space around each item.

Furthermore, the items with the class <code>square</code> need to be centered:6.

Inside the <code>.square ruleset</code>, add a <code>justify-content</code> property with the value that centers the items in the container.

6.
Lastly, the elements with the class <code>row</code> and elements with the class <code>square</code> need to be aligned vertically:

Inside the rulesets for <code>.row</code> and <code>.square</code>, add the <code>align-items</code> property with the value that centers the items inside the container.

You did it! Great work. Now resize the browser to see your flex properties in action!

## Credits
www.codecademy.com
### License
MIT License

Copyright (c) 2025 Adanta Griffin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.