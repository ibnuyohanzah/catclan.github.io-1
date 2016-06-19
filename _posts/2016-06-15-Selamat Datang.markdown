---
layout: post
---



<html manifest="cache-manifest.manifest">
<body>

<div id="result"></div>

<script>
// Check browser support
if (typeof(Storage) !== "undefined") {
    // Store
    localStorage.setItem("Westlife", "Mylove");
    // Retrieve
    document.getElementById("result").innerHTML = localStorage.getItem("lastname");
} else {
    document.getElementById("result").innerHTML = "Sorry, your browser does not support Web Storage...";
}
</script>

 </body>
</html>

<h3> coba dengarkan seksama musik dibawah ini</h3>
<br>pastinya menggunakan format .Ogg :D <br>


<p>Westlife - My love<br> tanpa fate in dan Fat out <br>
<audio controls="controls">
  <source src="/img/Aerosmith - I Don't Wanna Miss a Thing.oog" type="audio/ogg" />
  Your browser does not support the audio element.
</audio> 
</p>

