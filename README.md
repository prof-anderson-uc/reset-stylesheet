# Reset CSS 

A modern reset stylesheet designed for student learning, accessibility, and real-world web development.

## What is This?

This `reset.css` file is part of the UCBA Stylekit — a lightweight, educational CSS toolkit designed for students learning modern HTML and CSS. It builds on the foundation of [Eric Meyer's Reset v2.0](https://meyerweb.com/eric/tools/css/reset/) and includes modern enhancements for accessibility, responsive design, and clarity.

This reset stylesheet:

- Normalizes default styles across browsers
- Provides a consistent baseline for margin, padding, and typography
- Keeps the browser's keyboard focus outlines visible
- Includes useful resets for text, tables, form elements, and print
- Is heavily commented to support learning and comprehension

## Why Use It?

Different browsers apply their own default styles to elements like headings, lists, and forms. These inconsistencies can cause frustration for beginners and professionals alike. This reset:

- Gives your projects a consistent starting point
- Removes unpredictable browser spacing and typography quirks
- Encourages clean, accessible markup and styling habits
- Helps students focus on *what they build*, not how browsers render it by default

## How to Use

1. **Add the CSS file to your project.**  
   Download `reset.css` or copy it into your project directory.

2. **Link it in your HTML `<head>`**:
   ```html
   <link rel="stylesheet" href="reset.css">
   ```

3. **Place your custom styles AFTER the reset:**<br>
This ensures **your** styles build on top of a clean foundation.
   ```html
   <link rel="stylesheet" href="reset.css">
   <link rel="stylesheet" href="example.css">
   ```

4. **Use it for every project you build in my courses**<br>
It's especially helpful for layout, typography, accessibility, and consistency!


## 🔧 What It Covers

- Universal margin, padding, and border reset

- Normalized font styles, line height, and heading behavior

- Bold and italic kept for meaningful tags (`<strong>`, `<em>`, `<cite>`, etc.)

- Dotted underline and question-mark cursor for `<abbr>`; quotation marks kept for `<q>`

- A simple gray bar on the left of `<blockquote>` so quotes stand out (replace it with your own design)

- Long words and web addresses wrap instead of stretching the page; headings and paragraphs wrap more evenly

- No mystery gap underneath images

- Text doesn't enlarge itself when a phone is turned sideways

- Form field consistency across browsers

- Table and caption formatting

- Print styles for better output in PDFs and printed pages

## What It Leaves for You

Some things are left out on purpose, so you practice writing them yourself:

- **Navigation lists keep their bullets.** Remove them in your own stylesheet with `list-style: none;`.

- **Lists have no left padding.** Bullets can sit outside the edge of their container until you add padding or margin.

- **Images aren't automatically sized to fit.** Add `max-width: 100%;` to your images so they don't overflow on small screens.


## Conventions Used

- **Font Inheritance**: All elements inherit the font from the body  

- **Box Sizing**: Uses `box-sizing: border-box` for layout sanity  

- **Line Height**: Slightly increased for better readability (`line-height: 1.3`)  

- **Commenting**: Clear, sectioned comments guide students through the logic  

- **Accessibility**: Never removes the browser's focus outlines, so keyboard users can always see where they are  

- **Browser Support**: Written for current browsers; old Internet Explorer workarounds have been removed  


## About the Author

**Eric Anderson**
Professor, Media Communications & Technology <br>
University of Cincinnati - UC Blue Ash College <br>
GitHub: [@prof-anderson-uc](https://github.com/prof-anderson-uc)


Eric teaches web design, front-end development, and digital media production. His focus is on helping students build real-world skills with clean, accessible, standards-based code. The reset stylesheet and UCBA Stylekit are part of his effort to create practical, educational tools for students at all levels.

## License
This reset is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT). <br>
Modify it, share it, and adapt it to your own needs — especially in a classroom or learning environment!

---

🤓 Happy coding!
