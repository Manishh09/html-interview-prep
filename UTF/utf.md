## What is UTF ?

- The `<meta charset="UTF-8">` tag ensures the browser interprets the document using UTF-8 encoding.
- Always include this tag in your HTML templates to avoid character rendering issues, especially for non-English content.

- `UTF` stands for `Unicode Transformation Format`, and it is a character encoding standard used to represent text in computers and web pages.

- In the context of HTML templates, `UTF-8` is the most commonly used encoding because it supports a wide range of characters, including those from different languages and symbols.

## Why is UTF-8 important in HTML?

1. **Universal Compatibility:** UTF-8 can encode all characters in the Unicode standard, making it suitable for multilingual websites.
2. **Default Encoding**: Modern browsers default to UTF-8, ensuring consistent rendering of text.
3. **Avoids Encoding Issues:** Without specifying UTF-8, special characters (like é, ©, or €) might not display correctly.

## How to specify in an HTML Template ?

You define the character encoding in the <head> section of your HTML file using the <meta> tag. Here's an example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>UTF-8 Example</title>
  </head>
  <body>
    <p>
      Special characters like é, ©, and € will display correctly with UTF-8.
    </p>
  </body>
</html>
```
