# 9. HTML: TABLE

This elements helps in arranging the data into rows and columns.

a`<table>` element consists of table cells inside rows and columns, each table cell is defined by `<td>` & `</td>` tag.

## Table rows
in table element a tble row starts with `<tr>` tag and is a closing tag.

## Table headers
Sometimes you want your cells to be table header cells. In those cases use the `<th>` tag instead of the `<td>` tag.

Example:

```
<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```

## Table styling

### Border

To add a border, use the CSS `border:` property on `<table>`, `<th>`, and `<td>` elements.

### Collapsed table Border

In order to avoid double border, use the CSS `border-collapse:` property to `collapse` on `<table>`, `<th>`, and `<td>` elements.

* Example:
```
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}   
```
### background color
in order to beautify the table you can add color to table cells and its by simply using the CCS `background-color:` property in `<th>` and `<td>` elements. With the `border-color` property, you can set the color of the border.

* Example (background color):

```
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
th, td {
  background-color: #96D4D4;
}
```

* Example (border color):

```
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
th, td {
  border-color: #96D4D4;
}
```

### Round borders

With the border-radius property, the borders get rounded corners.

* Example:

```

table, th, td {
  border: 1px solid black;
  border-radius: 10px;
} 
```

## topics to read more about:

* colspan & rowspan
* padding & spacing
* table styling
* table Colgroup