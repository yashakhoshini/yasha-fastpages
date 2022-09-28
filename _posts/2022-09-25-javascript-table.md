---
layout: post
description: Creating a table with JavaScript
categories: [markdown]
title: JavaScript Table
---

```
<div id="javascriptTable">

</div>

<script>

const data = ["yasha","james","quinn","aaron"]

let table = document.createElement("table");
let row = document.createElement("tr");
for(let i=0; i<data.length; i++){
    let td=document.createElement("td");
    let node=document.createTextNode(data[i]);
    td.appendChild(node);
    row.appendChild(td);
}
table.appendChild(row);
let div = document.getElementById("javascriptTable");
div.appendChild(table);

</script>
```

{% include javascript-table.html %}

# Roles Table

---
permalink: /FP/js-tab
---
 
 
<h1>Table </h1>
 
<table id = "mytable">
    <tr>
    <th> Member </th>
    <th> Role </th>
    </tr>  
</table>
<script>
    let big_dict = {
        "Quinn":"Scrum Master",
        "Yasha":"Dev-Op",
        "Aaron": "Backend Developer",
        "James" : "Frontend Developer"
    };
    var body = document.getElementsByTagName("body")[0];
 
    var tbl = document.getElementById("mytable");
    var tblBody = document.createElement("tbody");
 
    for (var j = 0; j < Object.keys(big_dict).length; j++) {
        var row = document.createElement("tr");
       
       
        obj = Object.keys(big_dict)[j];
        obj2 = big_dict[obj];
        var cell1 = document.createElement("td");
        var cellText1 = document.createTextNode(obj);
        var cell2 = document.createElement("td");
        var cellText2 = document.createTextNode(obj2);
 
        cell1.appendChild(cellText1);
        row.appendChild(cell1);
        cell2.appendChild(cellText2);
        row.appendChild(cell2);
 
 
      //row added to end of table body
      tblBody.appendChild(row);
    }
 
 
    tbl.appendChild(tblBody);
 
    body.appendChild(tbl);
 
    tbl.setAttribute("border", "2");
  </script>

