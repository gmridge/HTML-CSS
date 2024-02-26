[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12945689&assignment_repo_type=AssignmentRepo)
</br>
<br/>

![alt text](https://x4w8f4y8.rocketcdn.me/wp-content/uploads/2020/05/iod_h_tp_white_c.png)

<!-- _class: lead -->

![](./images/iod.png)

# Module 2

<br/>

### Part 2 - Lab 2.1

> # Practice using HTML elements

<br/>

# Lab 1 - HTML

The goal of this lab is to familiarize you with HTML tags, their properties, and usages. Completing the steps will require searching for answers on the Internet, which is a fundamental skill for a software developer's life.

**TIP:** Try learning keyboard shortcuts, as they can greatly simplify a web developer’s work.

## I. Template

The template contains a skeleton for your website using semantic HTML. There are two files: `index.html` and `form.html`. We'll create separate pages and link them using `<a>` tags. Assets such as images, audio, and video are found in the `assets` directory.

**Steps:**

1. Take a look at the template.
2. Go Live in VS Code.

## II. HTML elements - metadata

In this section, you'll edit the `index.html` file.

**Steps:**

1. Add a title in the head section of your page using the HTML title tag.
2. Add meta tags in the head section:
   - `charset`
   - `description`
   - `keywords`
   - `author`
   - `viewport`

## III. HTML elements - div, span, p, pre, ul, li, ol, article

**Steps:**

1. Add 3 divs next to each other at the beginning of the body section:

    ```html
    <div>avocado</div>
    <div>kiwi</div>
    <div>banana</div>
    ```

2. Below divs, add 3 spans next to each other.
   Observe the difference between block and inline elements.

## IV. HTML elements - Tables - table, thead, tbody, tr, td, th

**Steps:**

1. Start by adding another article below the first one. Add an h2 tag inside this newly created article.
2. Search the web for an HTML table code, e.g., from the Mozilla website:

    ```html
    <table>
        <thead>
            <tr>
                <th>First header</th>
                <th>Second header</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>First cell - first row</td>
                <td>Second cell - first row</td>
            </tr>
        </tbody>
    </table>
    ```

3. Create another row by copying the `tr` tag together with its children below the first row.
4. By default, tables don't have any styles. Add styling by including the following code in the head section of the page:

    ```html
    <style>
        table, th, td {
            border: 1px solid black;
        }
    </style>
    ```

5. Add a third cell inside one of the rows. Observe how the table lost its shape:

    ```html
    <td>Third cell - first row</td>
    ```

6. Fix the table by adding the missing `td` tag.
7. Now the header is missing for the third column. Fix that by adding `colspan="2"` attribute to the first `th` tag to make it span two columns.
8. Add a third row to the table and add `rowspan="2"` attribute to one of the `td` tags above and observe what happens:

    ```html
    <tr>
        <td>First cell - third row</td>
        <td>Second cell - third row</td>
    </tr>
    ```

## V. HTML elements - img, video, audio

**Steps:**

1. Add an image to your website using an image provided from the external service, picsum:

    ```html
    <img src="https://picsum.photos/200/300" alt="" />
    ```

2. Add a video:

    ```html
    <video controls width="250">
        <source src="/media/cc0-videos/flower.webm" type="video/webm">
        <source src="/media/cc0-videos/flower.mp4" type="video/mp4">
        Sorry, your browser doesn't support embedded videos.
    </video>
    ```

3. Add an audio element:

    ```html
    <audio controls src="/media/cc0-audio/t-rex-roar.mp3">
        Your browser does not support the <code>audio</code> element.
    </audio>
    ```

4. Try removing the `controls` attribute and adding the `autoplay` attribute to both audio and video tags.

## VI. HTML elements - Forms - form, input, label, select, option, button

In this section, you'll be editing the `form.html` file accessible at http://localhost:8080/form.

**Steps:**

1. Open `form.html`.
2. Add a form using the `<form>` tag:

    ```html
    <form method="POST" action="http://localhost:3000/profile">
    </form>
    ```

3. Inside the form, add 2 inputs - one for inputting first name and the second one for inputting last name. Remember to add labels for each input. Wrap inputs together with labels using divs to layer inputs one below another.
4. Add radio buttons, checkboxes, and a select element with options.
5. Add a submit button at the end of the form:

    ```html
    <button type="submit">Submit form</button>
    ```

## VII. Adding a link from a Home to a Form page

Extend a navigation bar so users can navigate from Home to the Form page by clicking a link in the navigation bar.

**Steps:**

1. Add another `<a>` element inside the `<nav>` tag in both `index.html` and `form.html`.
2. Notice the difference between adding:

    ```html
    <a href="./form">Form</a>
    ```

    and

    ```html
    <a href="/form">Form</a>
    ```

## VIII. Inspecting the HTML

In this section, you'll inspect the HTML that you've written on the page.

**Steps:**

1. Use the inspection tool - open the developer console and select the inspection tool from the top left corner.
2. Select various elements on your website using the inspection tool.
3. Take a look at the CSS in the "Styles" subtab in the "Elements" tab after selecting an element using the inspection tool.
    - Try editing CSS styles in the developer console. For example, you may try adding the following values:

    ```css
    margin: 20px;
    color: blue;
    font-size: 24px;
    ```
    
    Use `element.style {}` to add new styles to selected HTML elements.


<br/>

<hr>


  **Resources**: 
  
  W3Schools
  • [LINK](https://w3schools.com/)
  
  Mozilla Developers Network - HTML
  • [LINK](https://developer.mozilla.org/en-US/docs/Learn/HTML)


<br/>


In case you missed any of the instructions in the class, please refer to the recording:

[![Maintainer](https://custom-icon-badges.demolab.com/badge/-ZOOM%20CLASS%20RECORDING-gold?style=for-the-badge&logo=google-logo&logoColor=black)](https://docs.google.com/spreadsheets/d/1ToABwZF6np66kwIxg-qORVwkW-G__6FBbsPHdmH6rOA/edit#gid=0{:target="_blank})


<br/>
<br/>

<html>
  <div align='center'>
    <h4>Please don't forget to add "<b>COMPLETED</b>" into your commit description when your assignment is ready for checking.</h4>
  </div>
</html>

<br/>
<br/>
<br/>


