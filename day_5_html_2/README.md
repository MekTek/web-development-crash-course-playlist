# HTML -2

### 5. HTML – TABLES

#### Table rows and Data Cells:
The HTML tables are created using the `<table>` tag in which the `<tr>` tag is used to create table rows and `<td>` tag is used to create data cells
 ###### Example: table1.html
 ```HTML
 <!DOCTYPE html>
 <html>
   <head>
     <meta charset="utf-8">
     <title>Table 1</title>
   </head>
   <body>
     <h1>Simple Table</h1>
     <table border="1">
       <tr>
         <td>1,1</td>
         <td>1,2</td>
       </tr>
       <tr>
         <td>2,1</td>
         <td>2,2</td>
       </tr>
     </table>

   </body>
 </html>

 ```
***
#### Table Heading
Table heading can be defined as `<th>...</th>`. It's used as `<td>` tag in a table.
###### Example: tableHeading.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Table Heading</title>
  </head>
  <body>
    <h1>Table Header Example</h1>
    <table border="1">
      <tr>
        <th>Tag Name</th>
        <th>Tag</th>
      </tr>
      <tr>
        <td>Table</td>
        <td> &lttable&gt </td>
      </tr>
      <tr>
        <td>Table Heading</td>
        <td> &ltth&gt </td>
      </tr>
    </table>
  </body>
</html>
```
***
#### Cellpadding and Cellspacing Attributes

Cellpadding and Cellspacing are basically two attributes which is used to  adjust the white space in your table cells.  The cellspacing is used for width of the border and cellpadding is used for the distance between cell borders and the content within a cell.

###### Example: tablePadSpac.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Cellpadding and Cellspacing</title>
  </head>
  <body>
    <h1>Cellpadding and Cellspacing</h1>
    <table border="1" Cellpadding="5" Cellspacing="5">
      <tr>
        <th>Tag Name</th>
        <th>Tag</th>
      </tr>
      <tr>
        <td>Table</td>
        <td> &lttable&gt </td>
      </tr>
      <tr>
        <td>Table Heading</td>
        <td> &ltth&gt </td>
      </tr>
    </table>
  </body>
</html>
```
***
#### Colspan and Rowspan Attributes
colspan is used for merge two or more columns and similarly rowspan is used for merge two or more rows.
###### Example: tableSpan.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Colspan and Rowspan</title>
  </head>
  <body>
    <h1>Colspan and Rowspan</h1>
    <table border="1">
      <tr>
        <th>Column 1</th>
        <th>Column 2</th>
        <th>Column 3</th>
      </tr>
      <tr>
        <td rowspan="2">Row 1 Cell 1</td>
        <td>Row 1 Cell 2</td>
        <td>Row 1 Cell 3</td>
      </tr>
      <tr>
        <td>Row 2 Cell 2</td>
        <td>Row 2 Cell 3</td>
      </tr>
      <tr>
        <td colspan="3">Row 3 Cell 1</td>
      </tr>
    </table>
  </body>
</html>

```
***
#### Table Height and Width
You can set height and width of a table. lets see the example
###### Example: tableHeightWidth.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Table Height and Width</title>
  </head>
  <body>
    <h1>Table Height and Width</h1>
    <table border="1" height = "150" width= "400">
      <tr>
        <th>Column 1</th>
        <th>Column 2</th>
        <th>Column 3</th>
      </tr>
      <tr>
        <td rowspan="2">Row 1 Cell 1</td>
        <td>Row 1 Cell 2</td>
        <td>Row 1 Cell 3</td>
      </tr>
      <tr>
        <td>Row 2 Cell 2</td>
        <td>Row 2 Cell 3</td>
      </tr>
      <tr>
        <td colspan="3">Row 3 Cell 1</td>
      </tr>
    </table>
  </body>
</html>

```
***
#### All examples of table in a single page
###### Example: allTable.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>All Table</title>
  </head>
  <body>
    <h1>All Table</h1>
    <h3>Table rows and Data Cells</h3>
    <table border="1">
      <tr>
        <td>1,1</td>
        <td>1,2</td>
      </tr>
      <tr>
        <td>2,1</td>
        <td>2,2</td>
      </tr>
    </table>
    <hr>
    <h3>Table Heading</h3>
    <table border="1">
      <tr>
        <th>Tag Name</th>
        <th>Tag</th>
      </tr>
      <tr>
        <td>Table</td>
        <td> &lttable&gt </td>
      </tr>
      <tr>
        <td>Table Heading</td>
        <td> &ltth&gt </td>
      </tr>
    </table>
    <hr>
    <h3>Cellpadding and Cellspacing Attributes</h3>
    <table border="1" Cellpadding="5" Cellspacing="5">
      <tr>
        <th>Tag Name</th>
        <th>Tag</th>
      </tr>
      <tr>
        <td>Table</td>
        <td> &lttable&gt </td>
      </tr>
      <tr>
        <td>Table Heading</td>
        <td> &ltth&gt </td>
      </tr>
    </table>
    <hr>
    <h3>Colspan and Rowspan Attributes</h3>
    <table border="1">
      <tr>
        <th>Column 1</th>
        <th>Column 2</th>
        <th>Column 3</th>
      </tr>
      <tr>
        <td rowspan="2">Row 1 Cell 1</td>
        <td>Row 1 Cell 2</td>
        <td>Row 1 Cell 3</td>
      </tr>
      <tr>
        <td>Row 2 Cell 2</td>
        <td>Row 2 Cell 3</td>
      </tr>
      <tr>
        <td colspan="3">Row 3 Cell 1</td>
      </tr>
    </table>
    <hr>
    <h3>Table Height and Width</h3>
    <table border="1" height = "150" width= "400">
      <tr>
        <th>Column 1</th>
        <th>Column 2</th>
        <th>Column 3</th>
      </tr>
      <tr>
        <td rowspan="2">Row 1 Cell 1</td>
        <td>Row 1 Cell 2</td>
        <td>Row 1 Cell 3</td>
      </tr>
      <tr>
        <td>Row 2 Cell 2</td>
        <td>Row 2 Cell 3</td>
      </tr>
      <tr>
        <td colspan="3">Row 3 Cell 1</td>
      </tr>
    </table>
  </body>
</html>

```
***

### 6. HTML – LISTS
There are three ways for specifying lists in HTML. All list can be consist of one or more list element.
* `<ul>` - Unordered List
* `<ol>` - Ordered List
* `<dl>` - Description List

#### HTML Unordered Lists
An Unordered list is a list of similar point or content that have no special order or sequence. There is a type attribute of Html list. By default it is a disc, others are `"square"` and `"circle"`

###### Example: uList.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Unordered List</title>
  </head>
  <body>
    <h1>Unordered List</h1>
    <h4>Default Type</h4>
    <ul>
      <li>item 1</li>
      <li>item 2</li>
      <li>item 3</li>
      <li>item 4</li>
    </ul>

    <h4>Square Type</h4>
    <ul type = "square">
      <li>item 1</li>
      <li>item 2</li>
      <li>item 3</li>
      <li>item 4</li>
    </ul>

    <h4>Circle Type</h4>
    <ul type="circle">
      <li>item 1</li>
      <li>item 2</li>
      <li>item 3</li>
      <li>item 4</li>
    </ul>

  </body>
</html>

```

#### HTML Ordered Lists
If you are required to put your items in a numbered list instead of bulleted, then HTML ordered list will be used.

You can use a `type` attribute to specify the type of numbering you like. By default, it is a number. Others are -
* "1" - Numerals.
* "I" - Upper-Case Roman.
* "i" - Lower-Case Roman.
* "a" - Lower-Case Letters.
* "A" - Upper-Case Letters.

###### Example: oList1.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Ordered List</h1>
    <h4>Numerals Type</h4>
    <ol type="1">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Upper-Case Roman</h4>
    <ol type="I">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Lower-Case Roman</h4>
    <ol type="i">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Upper-Case Letters</h4>
    <ol type="A">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Lower-Case Letters</h4>
    <ol type="a">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
  </body>
</html>
```

You can also use a `start` attribute to specify the starting point of numbering you need. Rewrite the previous .html file with `start` attribute.

###### Example: oList2.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Ordered List</h1>
    <h4>Numerals Type</h4>
    <ol type="1" start="4">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Upper-Case Roman</h4>
    <ol type="I" start="4">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Lower-Case Roman</h4>
    <ol type="i" start="4">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Upper-Case Letters</h4>
    <ol type="A" start="4">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
    <h4>Lower-Case Letters</h4>
    <ol type="a" start="4">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
      <li>Item 4</li>
    </ol>
  </body>
</html>

```

### HTML Description Lists
Html supports Description style list where entries are listed like in a dictionary or encyclopedia. It's a ideal  way to present a glossary, list of terms, or other name/value list.
Description List have three key tag
* `<dl>...</dl>` - Description list enclosure.
* `<dd>...</dd>` - A term.
* `<dt>...</dt>` - Term Description.

###### Example: dList.html
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Description List</title>
  </head>
  <body>
    <h1>Description List</h1>
    <dl>
      <dt>HTML</dt>
      <dd>HTML stands for Hyper Text Markup Language.</dd>
      <dt>HTTP</dt>
      <dd>HTTP stands for Hyper Text Transfer Protocol. </dd>
    </dl>
  </body>
</html>

```
***
### 7. HTML – LINK
