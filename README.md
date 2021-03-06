# _{Application Name}_

#### _{Brief description of application}, {Date of current version}_

#### By _**{List of contributors}**_

## Description

_{This is a detailed description of your application. Its purpose and usage.  Give as much detail as needed to explain what the application does, and any other information you want users or other developers to have. }_

## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_

_{Leave nothing to chance! You want it to be easy for potential users, employers and collaborators to run your app. Do I need to run a server? How should I set up my databases? Is there other code this app depends on?}_

### Software Requirements
_1. Internet browser of choice._
_2. A code editor like VSCode or Atom to view or edit the codebase._

#### Open by downloading:
_1. Download this repository onto your computer by clicking the 'clone or download button'_
_2. Double click index.html to open it in your web browser_

### Open via Bash/GitBash:
_1. Clone this repository onto your computer:_
`git clone {PUT_REPO_HERE}`
_2. Navigate into the `{NAME_OF_DIRECTORY}` directory, and open in Visual Studio Code or preferred text editor_
`code .`
_3. Open index.html in Chrome or preferred browser_

## TDD testing:

Describe: toRomanNum();

Test: "recognizes single digits as roman numerals"
expect(toRomanNum(5)).toequal(V);

Test: The most basic rule is that you add the value of all the symbols: so II is 2, LXVI is 66, etc.
expect(toRomanNum(2)).toEqual(II);

Test: The exception is that there may not be more than three of the same characters in a row, and if there is you switch to subtraction.
expect(toRomanNum(9)).toEqual(IX);

Test: You also have to separate ones, tens, hundreds, and thousands. In other words, 99 is XCIX, not IC. 
expect(toRomanNum(99)).toEqual(XCIX);

Test: You cannot count higher than 3,999 in Roman numerals.
expect(toRomanNum(4000)).toEqual("This is beyond the limit of the roman numeral system");




#### To see my live website go to {GH_PAGES_LINK_HERE}!

## Known Bugs

_{Are there issues that have not yet been resolved that you want to let users know you know?  Outline any issues that would impact use of your application.  Share any workarounds that are in place. }_

## Support and contact details

_{Let people know what to do if they run into any issues or have questions, ideas or concerns.  Encourage them to contact you or make a contribution to the code.}_

## Technologies Used

_{Tell me about the languages and tools you used to create this app. Assume that I know you probably used HTML and CSS. If you did something really cool using only HTML, point that out.}_

### License

*{Determine the license under which this application can be used.  See below for more details on licensing.}*

Copyright (c) 2016 **_{List of contributors or company name}_**