<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>The AKC Page</title>
     
        <style>
            html { 
    overflow-y: scroll;
    -webkit-font-smoothing: antialiased; }

  body {
  	background: green; }
            
            #message{
                float: right;
                width:1000px;
                height:100%;
                margin:0px 0px 190px 0px;
                text-align: start;
            }

  #main {
     
      float:left;
  	height: 100px;
  	margin: 100px,0px; }

  #outer-circle {
  	-webkit-box-shadow: 0 0 50px 10px darkgreen;
  	-moz-box-shadow: 0 0 50px 10px darkgreen;
  	box-shadow: 0 0 50px 20px aqua;
  	border: 10px solid #ECEBFA;
  	border-top-color:aqua;
  	margin: 20% 66% auto;
  	text-align:center;
  	background: linear-gradient(to top,#ECEBFA,#ECEBFA,#ECEBFA,#ECEBFA);
  	width: 220px;
  	height: 220px;
	
  	-webkit-border-radius: 200px;
  	-moz-border-radius: 200px;
  	border-radius: 200px;
	
  	-webkit-animation:turning_cw 5s infinite;
  	-moz-animation:turning_cw 5s infinite;
  	animation:turning_cw 5s infinite;
  	position:relative;
  	opacity: 0.6; }
  	
  #outer-circle:hover {
  	-webkit-box-shadow: 0 0 100px 15px darkgreen;
  	-moz-box-shadow: 0 0 100px 15px darkgreen;
  	box-shadow: 0 0 1000px 150px green; 
            
      animation:turning_acw 31s infinite;
            
            }
  	
  #inner-circle {
  	border: 10px solid #ECEBFA;
  	border-left-color:aqua;
  	border-right-color:yellow;
	
  	-webkit-transform: rotate(360deg);
  	-moz-transform: rotate(360deg);
  	transform: rotate(360deg);
	
  	position:absolute;
	
  	background: -webkit-linear-gradient(top, #ecebfa 48%, darkgreen 49%, darkgreen 51%, #ECEBFA 52%);
  	background: -moz-linear-gradient(top, #ecebfa 48%, darkgreen 49%, darkgreen 51%, #ECEBFA 52%);
  	background: linear-gradient(to top, red 48%, darkgreen 49%, darkgreen 51%, red 52%);
	
  	margin: 10px;
  	width: 180px;
  	height: 180px;
	
  	-webkit-border-radius: 180px;
  	-moz-border-radius: 180px;
  	border-radius: 180px;
	
  	-webkit-animation:turning_acw 3s infinite;
  	-moz-animation:turning_acw 3s infinite;
  	animation:turning_acw 3s infinite; }
            

  #center-circle {
  	border: 10px solid aqua;
  	border-bottom-color:Yellow   ;
  	-webkit-transform: rotate(360deg); 
  	-moz-transform: rotate(360deg); 
  	transform: rotate(360deg); 
  	position:absolute;

  	background: -webkit-linear-gradient(top, #fff 48%, #ECEBFA 49%, #ECEBFA 51%, #fff 52%);
  	background: -moz-linear-gradient(top, #fff 48%, #ECEBFA 49%, #ECEBFA 51%, #fff 52%);
  	background: linear-gradient(to bottom, #fff 48%, #ECEBFA 49%, #ECEBFA 51%, #fff 52%);
	
  	margin: 10px;
  	width: 140px;
  	height: 140px;
	
  	-webkit-border-radius: 140px;
  	-moz-border-radius: 140px;
  	border-radius: 140px;
	
  	-webkit-animation:turning_cw 5s infinite;
  	-moz-animation:turning_cw 5s infinite;
  	animation:turning_cw 5s infinite; }

  #content {
  	position:absolute;
  	top: 10px;
  	left: 10px;
  	width: 120px;
  	height: 120px;
  	-webkit-border-radius: 140px;
  	-moz-border-radius: 140px;
  	border-radius: 140px;
  	background: orange; 
  	text-align:center;
  	line-height: 120px;
  	font-size: 40px;
  	color:clear;
  	text-shadow: 0 2px 2px #000;
  	font-weight:bold; }
  @keyframes aura {
  	0%{
  		text-shadow: 0 2px 2px #000; }
  		
  	50%{
  		text-shadow: 0 10px 10px #000;
  		line-height: 190px; }
  		
  	100%{
  		text-shadow: 0 2px 10px #000; }
  }

  @keyframes turning_cw {
  	0%{
  		transform: rotate(0deg); }
  	50%{
  		transform: rotate(12deg); }
      75%{
  		transform: rotate(240deg); }
      100%{
  		transform: rotate(360deg); }
      
  }
  
  @keyframes turning_acw {
  	0%{
  		transform: rotate(360deg); }
  	100%{
  		transform: rotate(0deg); }
  }
            
            body {
                background-image:url( IMG20190519164005.jpg);
                background-repeat:no-repeat;
                background-size: cover;
                 text-align: center;
                color: Black;
                font-weight: bold;
                font-size: 25px;
                
            
            }
            #date{
                color:yellow;
                font-weight:bold;
                font-size: 2em;
                
            }
            h1{
                color:Red;
                font-style:italic;
                background-color:clear;
                font-size: 100px;
                font-weight: 50000px;
                align-content: stretch;
                text-align: center;
            }
            
            #couplepic{
                float:right;
                margin:0px 10px 20px 3px;
            }
            p{background-color:clear;
            color:orangered;
            margin-left:1px;
            }
            
            h2{
                background:clear;
                color:azure;
                font-weight:200px;
                text-align: center;
                padding-top: 60px;
                
            }
        </style>
    </head>
    <body>
      <div id="container">    

    <div id="main">
      <div id="outer-circle">
        <div id="inner-circle">
          <div id="center-circle">
              <div id="content" <p> <a href="https://kariho.github.io/Untitled-1.html">!AKC!</a></p></div>
          </div>
        </div>
      </div>

    
  
  </div>
<div id="message">
    
        
        <h1>You're invited!!</h1>
        <h2>Please come to embrace "My Friend's Marriage"</h2>
                
        <p>My younger sister is set to marrry to her betterhalf Mr. Indi on <span id="date"> 30th Febuary.</span></p>
        <ul>
            <li>Please come along with all your family.</li>
            <li> If Possible, please come a day before to enjoy all sorts of rituals.</li>
        </ul>
        
        <p>Hoping to see all of you at our residence situated at 22Y, Huawei INDISTANN. on said date.</p>
    </div>
    </body>

</html>
