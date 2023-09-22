<!DOCTYPE html>
<html>
<head>
<title>mini-presentation</title>
<meta name="viewport" content="initial-scale:1.0;width=device-width">
<style>
.bangtrencung {
    width: 97.7%;
    text-align: center;
    padding: 15px;
    font-family: Bernard MT Condensed;
    font-size: 30px;
    opacity: initial;
}
.img {
    box-shadow: 0px 10px 12px 0px black;
    width: 100%;
}
table , tr , td {
    border: 2px solid black;
    text-align: center;
    font-family:Bernard MT Condensed ;
    font-size: larger;
    text-align: center;
    margin: 40px auto;
    border-collapse: collapse;

}
td {
    transition: all 0.3s ease-out;
}
td:hover {background-color:chartreuse;transform: scale(1.1);}
h1 {
    border: 1px solid black;
    padding: 20px;
    text-align: center;
    width: 200px;
    background-color: rgb(64, 163, 163);
}

.div1 {
    animation-name:nguyen1 ;
    animation-duration: 2s;
    animation-iteration-count: infinite;
}
@keyframes nguyen1 {
    from {background-color:aquamarine}
    to {background-color:rgb(212, 51, 83)}
}

#Grad {
    background-image:linear-gradient(to right ,rgba(9, 214, 170, 0.938) , rgb(255, 248, 238));
}

.bangp2 {
    margin: 0 auto;
    border: 2px solid black;
    text-align: center;
    width: 650px;
    height: 150px;
    overflow: auto;
    background-color:antiquewhite ;
    font-family:Bernard MT Condensed ;
    font-size:larger;
    z-index: 1;
}
.body1 {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .iloveyou{
    font-family: "Arial", sans-serif;
    font-size: 50px;
    font-weight: bold;
    text-transform: uppercase;
    color:#f2f2f2;
  }
 
  .iloveyou span {
    display: inline;
    margin: 10px;
    transition: 0.3s ease-out;
  }
 
.div2 {
    animation-name:nhatnguyen1 ;
    animation-duration: 2s;
    animation-iteration-count: infinite;
}
@keyframes nhatnguyen1 {
    from {color: white;}
    to {color: #cf5123;}
}

#div3 {
    animation-name: nguyen2;
    animation: nguyen2 3s infinite;
    transition: all 0.3s ease-out;
}
@keyframes nguyen2 {
    30% {margin-left: 30px;}
}
.img1 {
    transition : all 0.3s ease-out ; 
}
.img1:hover {transform: scale(1.1);}

.layout_card { 
    max-width: 960px;  
    padding: 40px;
    margin: 0 auto;
}
.Column_card {
    display: grid;
    grid-template-columns: repeat(2,1fr);
    gap: 40px;
}
.Card { 
    background-color:#f2f2f2;
    border-radius: 6px;
    padding: 40px;
    box-shadow: 0px 8px 8px 0px rgb(49, 49, 49) ;
    transition: all 0.3s ease-out;
}
.img_end {
    transition: all 0.3s ease-out;
}
.Card:hover {transform:scale(1.2) ;}
.img_end:hover {transform: scale(1.25);}

.button { 
    text-align: center;
    border-radius: 10px;
    padding: 20px;
    background-color:rgba(255, 127, 80, 0.651) ;
    font-family:Bernard MT Condensed ;
    font-size: larger;
    transition:all 0.3s ease-out ;
    box-shadow: 0px 7px 7px 0px rgb(37, 37, 37) ;
    margin-left: 40%;
}
.preButton {
    text-align: center;
    border-radius: 10px;
    padding: 20px;
    background-color:rgba(255, 127, 80, 0.651) ;
    font-family:Bernard MT Condensed ;
    font-size: larger;
    transition:all 0.3s ease-out ;
    box-shadow: 0px 7px 7px 0px rgb(37, 37, 37) ;
}

.button:hover {transform: scale(1.1);}
.preButton:hover {transform: scale(1.1);}

.div4 {
    animation-name: nn;
    animation-duration:3s ;
    animation-iteration-count:infinite;
}
@keyframes nn { 
    from {background-color:darkorchid;}
    to {background-color:chartreuse;}
}
ul {
    top:0;
    position: sticky;
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow:hidden ;
    background-color: rgba(9, 214, 170, 0.938) ;
    border: 2px solid black;
    z-index: 2;
}
li {
    float: left;
}
li a {
    display: inline-block;
    text-align: center;
    text-decoration: none;
    padding: 20px;
    color: aliceblue;
    transition: all 0.3s ease-out;
    font-size: larger;
    font-family: Bernard MT Condensed;
}
li a:hover {background-color: rgb(142, 101, 180)}

.img_giua {
    margin: 40px auto;
}
</style>
</head>

<body>

    <ul >
        <li><a href="#Home">Introduction</a></li>
        <li><a href="#Overview">Pie Chart</a></li>
        <li><a href="#Hoc_van">Scatter Plot</a></li>
        <li><a href="#4">Bar Chart</a></li>
        <li><a href="#5">Histogram</a></li>
        
    </ul>

<h id="Home"></h>
<br>
<br>
<br>
<br>
<div><h1 id="div3" style="font-family:Bernard MT Condensed;border-radius: 12px;width:fit-content;box-shadow: 2px 7px 7px 0px black">1.Introduction </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;" id="animation">Hello everyone, this is our website we want to share today. 
    Firstly ,we spent time finding the dataset on the Kaggle.com and it is about the statistics of the Premier League .Ultimately, let try out my product ^^</p>

<center><img src="d478e5437effaba1f2ee.jpg" class="img_end" alt="me" width=800px height=650px></center>

<h id="Overview"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 style="font-family:Bernard MT Condensed;border-radius: 16px;box-shadow: 2px 12px 10px 0px black;">2.Pie Chart </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">On this chart, Duc Binh will share some information that they include top 6 team with most total of goals</p>
<center><img src="c43d1051d0ed05b35cfc.jpg" class="img_end" alt="me" width=800px height=450px></center>

<br>
<br>
<br>

<div class="body1">
    <div class="iloveyou div2" style="width:fit-content">
        <span>M</span>
        <span>I</span>
        <span>N</span>
        <span>I</span>
        <span>-</span>
        <span>P</span>
        <span>R</span>
        <span>E</span>
        <span>S</span>
        <span>E</span>
        <span>N</span>
    </div>
</div>
<h id="Hoc_van"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 id="Hoc_van" style="font-family:Bernard MT Condensed;width:fit-content;border-radius: 16px;box-shadow: 2px 12px 10px 0px black;">3.Scatter Plot </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">Welcome to Nhat Nguyen Part, hope you guys might broaden the knowledge related to the scatter plot</p>
<center><img src="39179a1d77a1a2fffbb0.jpg" class="img_end" alt="me" width=800px height=450px></center>
<h id="4"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 style="font-family:Bernard MT Condensed;border-radius: 16px;width:fit-content;box-shadow: 2px 12px 10px 0px black;">4.Bar chart </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">This is Huy Cuong part, which is mainly talking about the total of own goals from the big six teams of the Premier League</p>
<center><img src="0e82daeb2157f409ad46.jpg" class="img_end" alt="me" width=800px height=450px></center>
<h id="5"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 id="Hoc_van" style="font-family:Bernard MT Condensed;border-radius: 16px;width:fit-content;box-shadow: 2px 12px 10px 0px black;">5.Histogram </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">Hi it's Cuong again and this is also the last chart on our presentation. Check it out with this interesting chart.</p>
<center><img src="5ffe7320649fb1c1e88e.jpg" class="img_end" alt="me" width=800px height=450px></center>

</body>
</html>

