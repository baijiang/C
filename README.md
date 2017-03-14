<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <title>Image Gallery</title>
  <link rel="stylesheet" href="styles/layout.css" media="screen"/>
 </head>
 <body>
    <h1>Snapshots</h1>  
    <ul>
     <li>
      <a href="images/cat.jpg" title="A little cat" onclick="showPic(this);return false;">Cat</a>
     </li>
     <li>
      <a href="images/home.jpg" title="My home" onclick="showPic(this);return false;">Home</a>
     </li>
     <li>
      <a href="images/office.jpg" title="My office" onclick="showPic(this);return false;">Office</a>
     </li>
     <li>
      <a href="images/school.jpg" title="My school" onclick="showPic(this);return false;">School</a>
     </li>
    </ul>
<img id="placeholder" src="images/placeholder.gif" alt="my image gallery">
<p id="description">Choose an image.</p>
<script type="text/javascript" src="scripts/showPic.js"> </script>

</body>
</html>
