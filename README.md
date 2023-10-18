# HTML Table Tags Unveiled: A Comprehensive Guide

## Hey all 👋 !

<br>

> Before Diving into the world of Web Development, Every Enthusiast should be always aware of the root of our journey!<br>


<br>
Yeah! that's true because as we go deeper in this whole never ending ocean it's sometimes unable for us to retrieve a basic concepts while catch up with the Structured Datasets. When it comes to presenting structured data on a web page, HTML's table tag is a fundamental and indispensable tool. 
<br><br>
<b>HTML (Hypertext Markup Language)</b> is the standard language for creating and structuring web content. The table tag is a crucial part of HTML, used for displaying tabular data, such as financial reports, product listings, schedules, and more. 
<br><br>
No worries I'm here to give you a solution for this to ace ur daily hustles. 😉 <br><br> So Without further ado, Let's Break the Basics!!
<br><br><br>
Here firstly we will come to the Basic Syntax of Table and will understand one by one it's concpets very easy, short & precisely to remember.

<h2>What actually are Tables? 🤔</h2>
<li>Basically in HTMl, there's a <b>table</b> named tag exists to represent your data records in structured manner where we can modify, view Data accordingly.</li>
<li>It Makes easier to user like us to understand complex information without any conflicts.</li>

<h4>Moving further coming to the syntax & working of the HTML tag:</h4>

So to create a basic table for a Data Record have to follow the below structure:<br><br>

```html
<table>
  <tbody>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
  </tbody>
</table>
```

Here table tag is the table container that holds all the content with some table name which can't be null.
Breaking each & every subtags of table one by one :<br><br>
<b>1. `<tr>` </b> Use to Represents a table row <br>
<b>2. `<th>`: </b> Use to Define table headers (typically bold and centered).<br>
<b>3. `<td>`: </b> Use to Contain regular table data.<br>

Let's take some small example to learn it fastly:<br><br>
```html
<h1>Student Grades</h1>

<table>
  <tbody>
    <!-- Table header row -->
    <tr>
        <th>Student Name</th>
        <th>Math</th>
        <th>Science</th>
        <th>History</th>
    </tr>
    <!-- Table data rows -->
    <tr>
        <td>John Doe</td>
        <td>95</td>
        <td>88</td>
        <td>92</td>
    </tr>
  </tbody>
</table>
```

- In ths above example, as we can see that we've used `<table>` tag to create table.<br>
- `<tbody>` tag holds tha all content of the table.<br>
- `<tr>` tag represents table rows, so we've used here for representing student name, grades like data in rows.
- After that in `<tr>` as earliers we have decided that we want this specific rows in our table, so to name that each column need unique name to store that specific data for that we're using `<thead>`.
- In, this example the Students Name, Math, Science, History are table heads.
- Now coming to the table data, as we have create table so we are having some data, we'll put that data in table `<tr>` tag where we're inserting the data row wise.
- We can retrive this all data by Displaying table using syntax ``SELECT * FROM table_name(the table name you've given)``

  <br>

```
 ✅ Note: Don't Confuse between <tr> tag as we're using it to specify thead & td also. We're using only tr to store data row wise and with wach entry.
```

<br>

So, After Getting about the basics we're good to go with some more table tags to present your data efficiently! 
<br><br><h3>Let's Get Deeper with some more tags used in `<table>` </h3>

<h2>Spannig the (Cols & rows): </h2>
<li> When you need to merge numerous cells into one, you can do it by spanning columns and rows in an HTML table, which enables you to create more intricate table layouts.<br></li>
<li> The colspan and rowspan characteristics are within th or td tags can be used to do this.</li><br><br>


<b> `<Colgroup>` & `<Cols>` : </b>

- Basically, The `<colgroup>` and `<col>` elements in HTML are used to specify properties for one or more columns in an HTML table.
- They provide a way to apply common styling and attributes to multiple columns, making it easier to control the appearance and behavior of columns in a table.

Let's see it more precisely:

- `<colgroup>` Element:
   - The `<colgroup>` element is used to group one or more columns in a table.
   - It can contain one or more `<col>` elements as its children.
   - Attributes, such as `span`, can be applied to the `<colgroup>` element to specify how many columns the group spans.

Example of `<colgroup>` usage:<br>

```html
<table>
    <colgroup>
        <col style="background-color: lightgray;">
        <col span="2" style="background-color: lightblue;">
    </colgroup>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
</table>
```

In this example, we use a `<colgroup>` element to group columns and apply background colors to them. The `span` attribute is used to specify that the second `<col>` element spans two columns.

- `<col>` Element:
   - The `<col>` element is used to define attributes for individual columns.
   - It should be placed as a child of the `<colgroup>` element or within the `<table>` element.

Example of `<col>` usage:

```html
<table>
    <colgroup>
        <col style="width: 100px;">
        <col style="width: 150px;">
    </colgroup>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

In this example, we use `<col>` elements to set the width of individual columns. The first column is given a width of 100 pixels, and the second column is given a width of 150 pixels.

Finally, the HTML table tag remains a strong tool for organising and displaying datasets on the web. Tables, when used appropriately in conjunction with HTML and CSS, can improve the user experience and accessibility of your website. However, when working with non-tabular data, it is critical to investigate other techniques to offer the greatest user experience and search engine optimisation. So, that's will be the enough to cop up with basics in table for structuring data.

Understand what each tag is and what it brings in when come to datasets on the web. In this way, you will be able to ace your daily hustles with a better understanding of datas with practical examples.

That's all for this article. I hope it will help you to gain some insights of Basic in HTML `<table>` tag.
