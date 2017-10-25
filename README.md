# eluosi
game
<!!DOCTYPE html>
<head>

	<meta charset="utf-8">

	<title>俄罗斯方块</title>

	<link rel="stylesheet" href="css/style.css" />

</head>

<body>

	<div>请用方向键和空格键进行操作</div>

	<div class="square" id="local">

		<div class="title">我的游戏区域</div>

		<div class="game" id = "local_game"></div>

		<div class="next" id = "local_next"></div>

		<div class="info">

			<div>已用时:<span id="local_time">0</span>s</div>

			<div>已得分:<span id="local_score">0</span>分</div>

			<div id="local_gameover"></div>

		</div>

	</div>

	<div class="square" id="local">

		<div class="title">对方游戏区域</div>

		<div class="remoto_game" id = "game"></div>

		<div class="remoto_next" id = "next"></div>

		<div class="info">

			<div>已用时:<span id="remoto_time">0</span>s</div>

			<div>已得分:<span id="remoto_score">0</span>分</div>

			<div id="remoto_gameover"></div>

		</div>

	</div>

	<script src="js/square.js"></script>

	<script src="js/squareFactory.js"></script>

	<script src="js/game.js"></script>

	<script src="js/local.js"></script>

	<script src="js/remote.js"></script>

	<script src="js/script.js"></script>

</body>
