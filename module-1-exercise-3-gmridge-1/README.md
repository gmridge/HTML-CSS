[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12495182&assignment_repo_type=AssignmentRepo)
</br>
<br/>

![alt text](https://x4w8f4y8.rocketcdn.me/wp-content/uploads/2020/05/iod_h_tp_white_c.png)

<!-- _class: lead -->

![](./images/iod.png)

> # Module 1

<br/>

### Exercise 3

<br/>

Using this code as a starter:

- Add a ‘Change Me’ button under
  each heading
- Style your buttons with CSS
- Add a script tag with two JS
  functions, one for each button
- Clicking each button should change the background colour and the heading text for that column.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Module 1 Exercise 3</title>
    <style>
      body {
        font-family: sans-serif;
        margin: 0;
      }
      .container {
        display: flex;
        min-height: 100vh;
        align-items: stretch;
      }
      .column {
        background: goldenrod;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        flex: 1;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="column" id="column1">
        <h1 id="heading1">Hello</h1>
      </div>
      <div class="column" id="column2">
        <h1 id="heading2">World</h1>
      </div>
    </div>
  </body>
</html>
```

<br/>

Extension: add text fields under the
headings, and replace the heading text
with the value of the text fields when the
buttons are clicked!

<br/>
<br/>
<br/>

<html>
  <div align='center'>
    <h4>Please don't forget to add "<b>COMPLETED</b>" into your commit description when your assignment is ready for checking.</h4>
  </div>
</html>
