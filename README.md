# Horiseon Website Code Refactor

The marketing agency Horiseon has asked that I refactor their website codebase, retaining any existing features and updating accessibility factors for the website.

Looking at the already existing HTML and CSS codebase, it became apparent that the code could be condensed a fair amount. The HTML needed semantic elements to replace divs and from looking at the Css, some individual id elements could be cleaned up to one class and others could be modified for more simplicity.

### Main Code Changes
- Changed div elements to semantic elements, header, footer, aside, figure etc.
- Reduced id's benefit cost, benefits lead and benefit brand to one benefitsAside class, changed Css to suit.
- Reduced the search engine optimization, online reputation management and social media marketing id's to one mediaSections class, kept individual id's for site navigation links, also changed CSS to suit.
- Added a underline hover effect to links so links are more obvious to user.
- Added alt text to all images for screen-reader accessibility.

Some codebase changes:
![Changing header elements](https://github.com/HobbaZ/Refactor-Code-Homework/blob/main/Refactor-Code-Assessment/Develop/assets/images/code-refactor1.PNG)

![Removing unneeded element code](https://github.com/HobbaZ/Refactor-Code-Homework/blob/main/Refactor-Code-Assessment/Develop/assets/images/code-refactor2.PNG)

![Adding needed meta data tags](https://github.com/HobbaZ/Refactor-Code-Homework/blob/main/Refactor-Code-Assessment/Develop/assets/images/code-refactor3.PNG)

Image below shows link hover effect
![screenshot of link hover effect](https://github.com/HobbaZ/Refactor-Code-Homework/blob/main/Refactor-Code-Assessment/Develop/assets/images/Horiseon-link-hover.png)

### Technology Used
- HTML
- CSS

### Full Website Screenshot
![screenshot of full website](https://github.com/HobbaZ/Refactor-Code-Homework/blob/main/Refactor-Code-Assessment/Develop/assets/images/website-fullscreen-screenshot.png)

### Website Link
https://hobbaz.github.io/Refactor-Code-Homework/Refactor-Code-Assessment/Develop/

### MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
