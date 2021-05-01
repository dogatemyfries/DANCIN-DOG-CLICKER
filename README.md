<html><head>
	<title>0 Dogcoin - Dancing Dog Clicker</title>

	<style>
       #puppy {
           background-color: rgb(255, 0, 0, 0.5);
           border-radius: 10px;
        }
        #puppy:hover {
background-color: rgb(255, 75, 75);
transition: all .15s ease-in-out;

}
           #puppy2 {
           background-color: rgb(255, 0, 0, 0.5);
           border-radius: 10px;
        }
        #puppy2:hover {
background-color: rgb(255, 75, 75);
transition: all .15s ease-in-out;

}
        
        
        body {
          background-image: url("https://th.bing.com/th/id/R8879d971ed6c65b47b88f3810d3bc0a0?rik=MiG0KIBei0x7pA&pid=ImgRaw");
            background-repeat:no-repeat;
            background-size:cover;
        }
	.sectionLeft{
float: left;
width: 75%;
}
.sectionRight {
float: right;
width: 25%;
}
.scoreContainer {
background-color: crimson;
opacity: 0.95;
width: 55%;
padding: 4px;
border-radius: 10px;
font-size: 18.5px;
font-family: arial;

}
        .nameOfTitle {
background-color: white;
opacity: 0.99;
width: 75%;
padding: 4px;
border-radius: 16px;
font-size: 25px;
            font-family: verdana;

}
        .scoreContainer:hover {
background-color: crimson;
opacity: 1;
width: 55%;
padding: 4px;
border-radius: 20px;
font-size: 20px;
font-weight: bold; 
transition: all .1s ease-in-out;
}
span {
color: green;
font-family: tahoma;
}



.clickerContainer img {
position: relative;
transition: all .1s ease-in-out;




}

.clickerContainer img:hover { transform: scale(1.175); }
.clickerContainer img:active { transform: scale(0.99); }

.shopButton {
background-color: grey;
transition: all .2s ease-in-out;
border-radius: 5px;
width: 100%;
margin: 10px 0px 10px 0px
 

}

.shopButton:hover {
background-color: lightgrey;
transition: all .15s ease-in-out;

}

.shopButton #image {
width: 25%;
}

.shopButton img {
height: 70px;
width: 100px;

}
.shopButton #nameAndCost p {
margin: 0px;
width: 60%;
    
}

.shopButton #nameAndCost p:first-of-type {
font-size: 20px;
font-weight: bold;
    font-family: arial;
}

.shopButton #amount {
font-size: 30px;
color: darkgrey;
font-family: roboto;
width: 15%;
}

.clickerButton {
background-color: grey;
transition: all .2s ease-in-out;
border-radius: 5px;
width: 100%;
margin: 10px 0px 10px 0px
 

}

.clickerButton:hover {
background-color: lightgrey;
transition: all .15s ease-in-out;

}

.clickerButton #image {
width: 25%;
}

.clickerButton img {
height: 70px;
width: 100px;

}
.clickerButton #nameAndCost p {
margin: 0px;
width: 60%;
    
}

.clickerButton #nameAndCost p:first-of-type {
font-size: 20px;
font-weight: bold;
    font-family: arial;
}

.clickerButton #amount {
font-size: 30px;
color: darkgrey;
font-family: roboto;
width: 15%;
}




.unselectable {
-webkit-user-select: none;
-moz-user-select: none;
-ms-user-select: none; /* if not using a chromium browser */
user-select: none;
}
	</style>
	</head>

	<body>

    <div class="sectionLeft">
<center>
<div class="nameOfTitle unselectable">
    <p>Welcome to DANCING DOG CLICKER!</p>
    </div>
    <br>
    <div class="scoreContainer unselectable">
	<span id="score">384</span> Dogcoin (Click dog to get some)<br>
	<span id="scorepersecond">0</span> DPS (Dogcoin per second)
</div>


<br>

<div class="clickerContainer">
	<img src="https://cdn.betterttv.net/emote/5eeb197cfdee545e3067a2de/3x" id="puppy" width="200" height="200" onclick="addToScore(clickingPower)">
    <img src="https://i.pinimg.com/originals/c4/2b/51/c42b51befc65839e88bae780e933ae0a.gif" id="puppy2" width="200" height="200" onclick="addToScore(clickingPower * 2)">
</div>
</center>
<div>
<table  class="clickerButton unselectable" onclick="buyclicker2()">
<tbody><tr>
<td id="image"><img src="https://i.pinimg.com/originals/c4/2b/51/c42b51befc65839e88bae780e933ae0a.gif" width="200"></td>
<td id="nameAndCost">
<p>Duck Dachshund</p>
<p><span id="clicker2cost">1000</span> Dogcoin (x2 Click Multiplier)</p>
</td>
</tr>
</tbody></table>
</div>
</div>

<div class="sectionRight">
<table class="shopButton unselectable" onclick="buyCursor()">
<tbody><tr>
<td id="image"><img src="https://th.bing.com/th/id/R89b890691949f6e8b2f07a9f229b8fc0?rik=fM8Vi%2b%2bQjSK3%2fQ&amp;riu=http%3a%2f%2fquicklol.com%2fwp-content%2fuploads%2f2012%2f12%2fdog-dancing-animation.gif&amp;ehk=%2fRQZ0G6ix6no8MjL%2bc5Q5OLqOjQRE7t%2bu%2f%2bBDSOKBpY%3d&amp;risl=&amp;pid=ImgRaw" width="200"></td>
<td id="nameAndCost">
<p>Dancing Chihuahua</p><p>
</p><p><span id="cursorcost">50</span> Dogcoin (1 Power)</p>
</td>
<td id="amount"><span id="cursors">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyDoggo()">
<tbody><tr>
<td id="image"><img src="https://th.bing.com/th/id/R0ba77b2abce35a6d9bc7bea51b42aabb?rik=dy4yDoKNCFxRuQ&amp;pid=ImgRaw" width="200"></td>
<td id="nameAndCost">
<p>Disco Dog</p><p>
</p><p><span id="doggocost">300</span> Dogcoin (5 Power)</p>
</td>
<td id="amount"><span id="doggos">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyFacility()">
<tbody><tr>
<td id="image"><img src="https://th.bing.com/th/id/R5021d4344e40b7f0a3ec3e88da241b15?rik=iHzJg5YMBoN%2fEw&amp;pid=ImgRaw" width="200"></td>
<td id="nameAndCost">
<p>Dogcoin Research Facility</p><p>
</p><p><span id="facilitycost">2000</span> Dogcoin (40 Power)</p>
</td>
<td id="amount"><span id="facilitys">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyPile()">
<tbody><tr>
<td id="image"><img src="https://th.bing.com/th/id/OIP.epcEcJ0Wl8VMfSrCGAlf3QHaDr?pid=ImgDet&amp;rs=1" width="400"></td>
<td id="nameAndCost">
<p>Worker Pile</p><p>
</p><p><span id="pilecost">12000</span> Dogcoin (1000 Power)</p>
</td>
<td id="amount"><span id="piles">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyMirror()">
<tbody><tr>
<td id="image"><img src="https://media.giphy.com/media/zEndcYZYLmxz2/giphy.gif" width="200"></td>
<td id="nameAndCost">
<p>Mirror Dancer</p><p>
</p><p><span id="mirrorcost">50000</span> Dogcoin (7500 Power)</p>
</td>
<td id="amount"><span id="mirrors">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyCoucher()">
<tbody><tr>
<td id="image"><img src="https://th.bing.com/th/id/R2e95317ddcf739ba5e5e473c850b5e97?rik=SxBFtImfjqlmvw&amp;riu=http%3a%2f%2f3.bp.blogspot.com%2f--jE71V9cHdc%2fUlh353imfJI%2fAAAAAAAAEh4%2fbu6s3-o8Nzw%2fs400%2fgif%2bdancing%2bdog%2bgif.gif&amp;ehk=sCnWIW7vOufUbPLnUICAEGxrTUwcNB2QvyNTwY5YbRU%3d&amp;risl=&amp;pid=ImgRaw" width="200"></td>
<td id="nameAndCost">
<p>Couch Chihuahua</p><p>
</p><p><span id="couchercost">200000</span> Dogcoin (50000 Power)</p>
</td>
<td id="amount"><span id="couchers">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyHappe()">
<tbody><tr>
<td id="image"><img src="https://th.bing.com/th/id/R1e6393a044704fd37c92d88907e5d91d?rik=Ia5kGYxA5vzejA&amp;pid=ImgRaw" width="200"></td>
<td id="nameAndCost">
<p>Happe Pouncer</p><p>
</p><p><span id="happecost">1000000</span> Dogcoin (500000 Power)</p>
</td>
<td id="amount"><span id="happes">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buyGabe()">
<tbody><tr>
<td id="image"><img src="https://i.makeagif.com/media/12-02-2015/8CO2R5.gif" width="200"></td>
<td id="nameAndCost">
<p>Gabe the Dog (RIP)</p><p>
</p><p><span id="gabecost">10000000</span> Dogcoin (10000000 Power)</p>
</td>
<td id="amount"><span id="gabes">0</span></td>
</tr>
</tbody></table>
<table class="shopButton unselectable" onclick="buySpin()">
<tbody><tr>
<td id="image"><img src="https://i.imgur.com/YbkBxYb.gif" width="200"></td>
<td id="nameAndCost">
<p>SPINNY BOI</p><p>
</p><p><span id="spincost">1000000000</span> Dogcoin (1000000000000 Power)</p>
</td>
<td id="amount"><span id="spins">0</span></td>
</tr>
</tbody></table>
</div>




	<script>
	var score = 0;
	var clickingPower = 1;
	var cursorCost = 50;
	var cursors = 0;
	var doggoCost = 300
	var doggos = 0;
	var facilityCost = 2000;
	var facilitys = 0;
	var pileCost = 12000;
	var piles = 0;
	var mirrorCost = 50000;
	var mirrors = 0;
	var coucherCost = 200000;
	var couchers = 0;
	var happeCost = 1000000;
	var happes = 0;
	var gabeCost = 10000000
	var gabes = 0;
	var spinCost = 1000000000
	var spins = 0;




function buyCursor() {
	if (score >= cursorCost) {
	score = score - cursorCost;
	cursors = cursors + 1;
	cursorCost= Math.round (cursorCost * 1.25);

	document.getElementById("score").innerHTML = score;
	document.getElementById("cursorcost").innerHTML = cursorCost;
	document.getElementById("cursors").innerHTML = cursors;
	updateScorePerSecond();
	}
	}
	function buyDoggo() {
	if (score >= doggoCost) {
	score = score - doggoCost;
	doggos = doggos + 1;
	doggoCost= Math.round (doggoCost * 1.75);

	document.getElementById("score").innerHTML = score;
	document.getElementById("doggocost").innerHTML = doggoCost;
	document.getElementById("doggos").innerHTML = doggos;
	updateScorePerSecond();
	}
	}
function buyFacility() {
	if (score >= facilityCost) {
	score = score - facilityCost;
	facilitys = facilitys + 1;
	facilityCost= Math.round (facilityCost * 3);

	document.getElementById("score").innerHTML = score;
	document.getElementById("facilitycost").innerHTML = facilityCost;
	document.getElementById("facilitys").innerHTML = facilitys;
	updateScorePerSecond();
	}
	}
function buyPile() {
	if (score >= pileCost) {
	score = score - pileCost;
	piles = piles + 1;
	pileCost= Math.round (pileCost * 10);

	document.getElementById("score").innerHTML = score;
	document.getElementById("pilecost").innerHTML = pileCost;
	document.getElementById("piles").innerHTML = piles;
	updateScorePerSecond();
	}
	}
function buyMirror() {
	if (score >= mirrorCost) {
	score = score - mirrorCost;
	mirrors = mirrors + 1;
	mirrorCost= Math.round (mirrorCost * 25);

	document.getElementById("score").innerHTML = score;
	document.getElementById("mirrorcost").innerHTML = mirrorCost;
	document.getElementById("mirrors").innerHTML = mirrors;
	updateScorePerSecond();
	}
	}
function buyCoucher() {
	if (score >= coucherCost) {
	score = score - coucherCost;
	couchers = couchers + 1;
	coucherCost= Math.round (coucherCost * 100);

	document.getElementById("score").innerHTML = score;
	document.getElementById("couchercost").innerHTML = coucherCost;
	document.getElementById("couchers").innerHTML = couchers;
	updateScorePerSecond();
	}
	}
function buyHappe() {
	if (score >= happeCost) {
	score = score - happeCost;
	happes = happes + 1;
	happeCost= Math.round (happeCost * 2500);

	document.getElementById("score").innerHTML = score;
	document.getElementById("happecost").innerHTML = happeCost;
	document.getElementById("happes").innerHTML = happes;
	updateScorePerSecond();
	}
	}
function buyGabe() {
	if (score >= gabeCost) {
	score = score - gabeCost;
	gabes = gabes + 1;
	gabeCost= Math.round (gabeCost * 10000);

	document.getElementById("score").innerHTML = score;
	document.getElementById("gabecost").innerHTML = gabeCost;
	document.getElementById("gabes").innerHTML = gabes;
	updateScorePerSecond();
	}
	}
function buySpin() {
	if (score >= spinCost) {
	score = score - spinCost;
	spins = spins + 1;
	spinCost= Math.round (spinCost * 1000000);

	document.getElementById("score").innerHTML = score;
	document.getElementById("spincost").innerHTML = spinCost;
	document.getElementById("spins").innerHTML = spins;
	updateScorePerSecond();
	}
	}

	function addToScore (amount) {
	score = score + amount;
	document.getElementById("score").innerHTML = score;
	}

	function updateScorePerSecond() {
	scorePerSecond = cursors + doggos * 5 + facilitys * 40 + piles * 1000 + mirrors * 7500 + couchers * 50000 + happes * 500000 + gabes * 10000000 + spins * 1000000000000
	document.getElementById("scorepersecond").innerHTML = scorePerSecond
	}


	setInterval (function() {
	score = score + cursors * 1;
	score = score + doggos * 5;
	score = score + facilitys * 40;
	score = score + piles * 1000
	score = score + mirrors * 7500
	score = score + couchers * 50000
	score = score + happes * 500000
	score = score + gabes * 10000000
	score = score + spins * 1000000000000
	document.getElementById("score").innerHTML = score;


	document.title = score + " Dogcoin - Dancing Dog Clicker";
	}, 1000); // 1000ms = 1 second


	</script>

	</body></html>
