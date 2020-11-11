# 20-11-11 CSS HTML Forms Practice

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an html file called `index.html` and use the `html:5` shortcut to generate the html, head, and body elements
2. create a css file called `style.css`
3. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
4. check that the file is linked by setting the `background-color` property of the body to any color other than white/gray and open the HTML file using `ctrl o` in the browser

### Assignment
Replicate the wireframe image provided following the steps below. Include comments in your HTML file. Push after completing the `Content` section and after completing the `Styling` section. To ensure that your form is working correctly submit the form and view the request in the address bar.

#### Content
1. add a heading with the text `Register`
1. add an HTML `form` element below heading - following elements will be nested in the form element
1. create a firstName field with a text input and `First Name` label
1. create a lastName field with a text input and `Last Name` label
1. create gender radio buttons for female, male, and not listed
1. create an email field with a required email input, an email placeholder and `Email` label
1. create a birthday field with a date input and a `Date of Birth` label
1.  create a subscription field with a selection element nesting 4 options (unselected, basic, premium, and gold) and a `Subscription` label
1. create a required terms and conditions checkbox
1. create a submission input 

#### Styling
1. add space between all content on the page and the window
1. add space between each of the label-input form element groups
1. style the submit button to be green with white text 

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)
