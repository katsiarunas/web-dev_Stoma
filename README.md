# web-dev_Stoma
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #E6E6FA;
  padding: 10px;
  text-align: center;
  font-size: 35px;
  color: #9370DB;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;

  background: #FFFFFF;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #F0FFF0;
 
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #E6E6FA;
  padding: 10px;
  text-align: center;
  color: #9370DB;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<header>
  <h2>Stoma Katsiaryna 354</h2>
</header>

<section>
  <nav>
    <ul style="list-style-type:square;">
      <li><a href="#1">Question 1</a></li>
      <li><a href="#2">Question 2</a></li>
      <li><a href="#3">Question 3</a></li>
      <li><a href="#4">Question 4</a></li>
      <li><a href="#5">Question 5</a></li>
      <li><a href="#6">Question 6</a></li>
    </ul>
  </nav>
  
  <article>
    <h1 id="1">Question 1</h1>
    <p>HTML5 became a standard on October 28, 2014. The main reasons for developing a new standard were evolving Web technologies, consistency and interoperability, mobile and responsive Web, rich media support.</p>
    
     <h1 id="2">Question 2</h1>
    <p>The main difference between W3C HTML5 and WHATWG HTML Living Standard is the development process and the ownership.</p>
    
      <h1 id="3">Question 3</h1>
    <p>The < !DOCTYPE html > declaration at the beginning specifies that the document is an HTML5 document. The < html > element is the root element of the HTML page, and all other elements are nested inside it. The < head > element contains meta-information about the page, including the < title > element, which specifies the page title displayed in the browser's title bar. The actual content of the page goes inside the < body > element.</p>
    
     <h1 id="4">Question 4</h1>
    <p>Semantic markup refers to using HTML elements that convey meaning and structure to the content. It focuses on using elements like < header >, < nav >, < section >, < article >, < footer >, etc., which describe the purpose and role of the content they wrap. Semantic markup improves accessibility, search engine optimization, and code maintainability.

Presentational markup, on the other hand, refers to using HTML elements primarily for visual styling purposes, rather than conveying meaning. It includes elements like < b >, < i >, < font >, < center >, etc., which were commonly used in older versions of HTML to apply formatting and styling. Presentational markup is considered deprecated now because it separates the structure from the presentation, making it harder to maintain and update web pages. It also hinders accessibility and semantic understanding by assistive technologies and search engines.</p>

 <h1 id="5">Question 5</h1>
    <p>To check browser support for a particular HTML tag or attribute, you can refer to online resources like the Mozilla Developer Network (MDN) or check the compatibility tables provided by caniuse.com. These resources provide detailed information about HTML features and their compatibility with different browsers, versions, and platforms. You can search for the specific tag or attribute and review its support matrix to determine if it is widely supported or has limitations in certain environments.</p>
    
     <h1 id="6">Question 6</h1>
    <p>The audio and video formats officially supported by the HTML standard are MP3, WAV, OGG Vorbis, MP4 (H.264 video codec), WebM (VP8 and VP9 video codecs), OGG Theora. 
If you use an unsupported audio or video format, the browser will not be able to play the media natively. Instead, it may fall back to a plugin-based solution if available or display a fallback content specified within the < video > or < audio > element. It's essential to provide alternative formats or use media transcoding techniques to ensure broad compatibility across different browsers and devices.</p>
    
   <video width="400" controls>
  <source src="mov_bbb.mp4" type="video/mp4">
  <source src="mov_bbb.ogg" type="video/ogg">
  Your browser does not support HTML video.
</video>

<p>
Video courtesy of 
<a href="https://www.bigbuckbunny.org/" target="_blank">Big Buck Bunny</a>.
</p>

<audio controls autoplay muted>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

  </article>
</section>

<footer>
  <p>In general, everything was clear. But I didn’t understand point 6 and whether any video needs to be inserted.</p>
  <img src="data:image/png;base64,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" alt="Flowers in Chania" width="200" height="70">
</footer>

</body>
</html>
