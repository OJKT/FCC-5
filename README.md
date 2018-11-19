# FCC-5
Responsive Web Design Principles Lesson Notes of OJKT
<style>
  #page-wrapper {
  position: relative;
}

body, html {
  font-family: "Khand", sans-serif;
  background: lightgrey;
}

/*toolbar&title*/
#head {
  position: fixed;
	@media (max-height: 800px) {
		h1{ font-size: 20px}
  }
}
#title {
	position: fixed;
	padding-left: 40px;
	padding-right: 50px;
	padding-bottom: 75px;
	padding-top: 10px;
	color: white;
	background: repeating-linear-gradient(180deg, black 0px, darkgray 40px, black 80px);
  font-size: 30px;
  margin-top: 20px;
	margin-left: 1400px;
	margin-right: 0px;
	border: solid black 4px;
	border-radius: 15px;
  font-family: font-family: 'Lobster Two', cursive;
	text-align: center;
	text-transform: uppercase;
	@media (max-height: 800px) {
	h1{ font-size: 20px}
}	
/*toolbar&title*/

/*footer*/
footer {
  margin-top: 15px;
	margin-bottom: 0px;
	margin-left: 1400px;
	padding-left: 13px;
	margin-right: 15px;
  background-color: #C0C0C0;
	border: 4px solid black;
 	border-radius: 10px;
	color: darkgrey;
	}
}
span {
    margin-right: 10px;
    display: flex;
    justify-content: flex-end;
    font-size: 0.9em;
    color: #444;
}
/*footer*/

/*navlinks*/
  ul {
		position: fixed;
		padding-left: 5px;
		padding-right: 0px;
		padding-bottom: 5px;
		padding-top: 10px;
		font-color: black;
		margin-top: 125px;
		margin-left: 1525px;
		font-family: font-family: 'Lobster Two', cursive;
		font-size: 25px;
		text-transform: none;
}
#nav-link {
			padding-left: 20px;
			padding-right: 20px;
			color: white;
    }
/*navlinks*/

img { height: 100px; width: 100px; }

  h2{
      width: 80vw;
  }
  p {
      width: 75vimn;
  }
  li {
      width: 100vmax;
  }
</style>
<div id="page-wrapper">
<link href="https://fonts.googleapis.com/css?family=Khand:500" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Lobster+Two" rel="stylesheet">
# FCC-6-Responsive Web Design Challenges
Responsive Web Design Challenges Lesson Notes of OJKT
<!DOCTYPE: html>
<html>
	
	<header id="header"></header>
<head>
		<h1 id=title><u>Introduction to <br> Responsive Web Design Challenges</u></h1>
		<hr>
		
		<nav id="nav-bar">
		<ul>
      <i><a class="nav-link" href="#footer" id="nav-link">Jump to Bottom</a></i>
			<i><a class="nav-link" href="#header" id="nav-link">Jump to top</a></i>
    </ul>
  </nav>
</head>
	
<div>
	<p><u>Learning Objectives :</u><p>
    <ol>
<li>) Create a Media Query</li>
			<li>) <a class="nav-link" href="#images">Make an Image Responsive</a></li>
<li>) Use a Retina Image for Higher Resolution Displays</li>
<li>) Make Typography Responsive.</li>
<li>) Make Elements Only Visible to a Screen Reader by Using Custom CSS.</a></li>
   </ol>
  </div>
	
<br>
<hr>
<img src="https://s3.amazonaws.com/freecodecamp/FCCStickers-CamperBot200x200.jpg" alt="freeCodeCamp sticker that says 'Because CamperBot Cares'" id="images">
	
<img src="https://www.google.co.uk/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjJma3ijN7eAhUB0BoKHTUnD2UQjRx6BAgBEAU&url=https%3A%2F%2Fwww.codeclub.org.uk%2F&psig=AOvVaw0qWwjUy5377QIVDQtSlgwX&ust=1542635912823623" alt="code camp'">
	
<img src"https://avatars0.githubusercontent.com/u/9892522?s=400&v=4" alt=" FCC'">
	<hr>
<h2>Important veiwport units are:</h2>
<p>as above i have some images (not loading) but the resolution was increased by decreasing the image size. here rather than using em or px i have used vw (10vw would be 10%od the veiwports width),vh (3vh would be 3% of the viewports height.) vmin, (70vmin would be 70% of the viewports smaller dimension (height vs. width), vmax: 100vmax would be 100% of the viewport's bigger dimension (height vs. width)</p>

<i>The four different viewport units are:</i>

<0l>
    <li>vw: 10vw would be 10% of the viewport's width.</li>
    <li>vh: 3vh would be 3% of the viewport's height.</li>
    <li>vmin: 70vmin would be 70% of the viewport's smaller dimension (height vs. width).</li>
    <li>vmax: 100vmax would be 100% of the viewport's bigger dimension (height vs. width).</li>
</ol>
<hr>
	
	<footer id="footer" tabindex="0">
		<ol>
			<i><a href="#">Privacy  .</a></i>
      <i><a href="#">Terms  .</a></i>
      <i><a href="https://www.facebook.com/Active-Boardom-1433050133615965/?__tn__=kC-R&eid=ARDxFnA2JMu6bjlwqWvI3V1d0Rce9HdYBzDGGtJp0BhH-ueOlTAQbh0whATwwgFna9sm9jkboRpjWJnD&hc_ref=ARQaDkOV-XEkdyZItVQH9yuafF_narIIMZukBWJoaFoVgKTTBr5qBLQ1pDtdCP1cxF0&fref=nf&__xts__[0]=68.ARDYkTx9CsRT4OGTCvkO4FfhIcApAmkjQ-zBxaLHt1nqutrcdBfuonVlBKBXLg-l6giN-MiLriy2iHhYK3-uZ7l8efaHcYfOQPPUo3YknyBCljz10jZVwawd_JPGlqxxUxpaKdDVOc7vv4zQb1gvTtbiga9MLXcGfadpQU6YN_ZFZFBORq0wTJ2gjwQWf-hqAyErVWR_HM-_tje583zlZDxOBvyFSIb71aWN5zby5u-Ar3tr-Zn6BXKJ03w-KH30lCsYY8yrgpdS7DWA_-M3ogU_9pI9jGXFww4iDR6qmOdznSinEPP_J0pCY3maDJ4_2n1-a3Uq57kDKz4vC98">Contact  .</a></i> <!--contact-->
		</ol>
	    <span>&copy Copyright 2018, OJKT STYLES</span>
	</footer>
</div>
