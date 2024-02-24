<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.hero-image {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("photographer.jpg");
  height: 50%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

.hero-text button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 10px 25px;
  color: black;
  background-color: #ddd;
  text-align: center;
  cursor: pointer;
}

.hero-text button:hover {
  background-color: #555;
  color: white;
}
</style>
</head>
<body>

<div class="hero-image">
  <div class="hero-text">
    <h1 style="font-size:50px">I am John Doe</h1>
    <p>And I'm a Photographer</p>
    <button>Hire me</button>
  </div>
</div>

<p>Page Content..</p>

</body>
</html>




# LCB42 HTML repository (LastCodeBender42.github.io):

This repository stores a group of HTML files that I use on my personal website . I prefer the convenience of using a hosted website for showcasing my experience. However, there are file size restrictions that can be annoying. I work around that limitation by storing HTML files on my .github.io repo and then open the file within an iframe on a hosted web page. For the purposes of developing a personal website this seems time and cost effective.

As an example, I would be unable to host this interactive network visualization natively on my hosted website. 
<br></br>
<br></br>
<img src="network.png" alt="Example Image">
<br></br>
<br></br>
However, I can use an iframe that includes `src=https://LastCodeBender42.github.io/d3graph2.html` and now it works like a charm. See the interactive network viz on my personal website <a href="https://analysisandinformatics.org/d2graph2-html">here</a>.


Please, take a moment to review my profile at my personal website <a href="https://analysisandinformatics.org/home">Data Analysis and Bioinformatics</a>.

