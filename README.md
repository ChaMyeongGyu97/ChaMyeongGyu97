### Hi there 👋

<!--
**ChaMyeongGyu97/ChaMyeongGyu97** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="kor">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Avoid</title>
</head>
<style>
	div canvas{
		border: 1px solid;
		margin-left: 80px;
		cursor: none;
	}
	
	#bg_canvas{
		background-image: url("/0508avoid/img/Backgrounds.jpg");
		z-index: 1;
		position: absolute;
		background-size: cover;
		background-position: 0px -41px;
	}

	#canvas{
		backdrop-filter: blur(2px);
		z-index: 5;
		position: absolute;
	}

	.ui{
		z-index: 9;
		position: absolute;
		top: 0;
		margin-top: 25px;
		-webkit-user-select:none;
 	 	-moz-user-select:none;
 	 	-ms-user-select:none;
 	 	user-select:none;
		cursor: none;
	}

	#timer{
		margin-left: 600px;
		color: orangered;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
	}

	#score{
		margin-left: 1000px;
		color: white;
		text-shadow: -1px 0px black, 0px 1px black, 1px 0px black, 0px -1px black;
	}

	#score_title{
		margin-left: 910px;
		color: orange;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
	}

	#life{
		margin-left: 100px;
	}

	#g{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 430px;
		visibility: hidden;
	}
	#a{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 480px;
		visibility: hidden;
	}
	#m{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 530px;
		visibility: hidden;
	}
	#e{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 580px;
		visibility: hidden;
	}
	#o{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 660px;
		visibility: hidden;
	}
	#v{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 710px;
		visibility: hidden;
	}
	#e2{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 760px;
		visibility: hidden;
	}
	#r{
		color: red;
		text-shadow: -1px 0px white, 0px 1px white, 1px 0px white, 0px -1px white;
		margin-top: 330px;
		margin-left: 810px;
		visibility: hidden;
	}

</style>

<body>
	<div id="canvas_container">
		<canvas id="bg_canvas" width="1100" height="700">
		</canvas>	
		<canvas id="canvas" width="1100" height="700">
		</canvas>
		<h1 id="timer" class="ui"></h1>
		<div id="life" class="ui"></div><h2 id="score_title" class="ui">SCORE</h2><h2 id="score" class="ui">
		</h2>
		<h1 class="ui" id="g">G</h1><h1 class="ui" id="a">A</h1><h1 class="ui" id="m">M</h1>
		<h1 class="ui" id="e">E</h1><h1 class="ui" id="o">O</h1><h1 class="ui" id="v">V</h1>
		<h1 class="ui" id="e2">E</h1><h1 class="ui" id="r">R</h1>
	</div>
</body>
<script src="/0508avoid/js/enemy.js"></script>
<script src="/0508avoid/js/bullet_p.js"></script>
<script src="/0508avoid/js/player.js"></script>
<script src="/0508avoid/js/manager.js"></script>
<script src="/0508avoid/js/boss.js"></script>
</html>
