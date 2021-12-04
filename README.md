# wboard
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, height=device-height, user-scalable=no">
    <title>手書きホワイトボード(Canvasサンプル)</title>
    <link rel="stylesheet" type="text/css" href="wboard.css">
</head>
<body>
    <audio id="ClickSound" preload="auto">
        <source src="clickm.ogg" type="audio/ogg">
        <source src="clickm.mp3" type="audio/mp3">
    </audio>
    <div class="wrapper">
        <form>
            <p>
                <a href="../../index.html">ホーム</a>
                &nbsp;<input type="button" class="b1" style="background: #000000;" value=" " onclick="change_black()"><input type="button" class="b1" style="background: #ff0000;" value=" " onclick="change_red()"><input type="button" class="b1" style="background: #008000;" value=" " onclick="change_green()"><input type="button" class="b1" style="background: #0000ff;" value=" " onclick="change_blue()"><input type="button" class="b1" style="background: #ffff00;" value=" " onclick="change_yellow()"><input type="button" class="b1" style="background: #ffffff;" value=" " onclick="change_white()">&nbsp;&nbsp;線幅&nbsp;<input type="button" class="b2" value="8px" onclick="change_8()"><input type="button" class="b2" value="16px" onclick="change_16()">&nbsp;&nbsp;<input type="button" class="b2" value="全面" onclick="spread()"><input type="button" class="b2" value="消去" onclick="clr()">
                &nbsp;&nbsp;<a href="wb-kai.htm">説明</a>
            </p>
        </form>
        <canvas id="drawArea"></canvas>
        <script src="wboard.js"></script>
    </div>
</body>
</html>
