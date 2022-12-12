---
layout: post
description: Cool button
categories: [markdown]
title: Button that says hi
---

<button id="enter" onclick="print(a,b)">PRESS THIS TO GET 3</button> 
<p id="result"></p>
<!-- javascript -->
<script>
    function print(a,b) {
        document.getElementById("result").innerHTML = a + b // math
    }
    // variables are defined
    var a = 1
    var b = 2
</script>
