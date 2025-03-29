# xatframe
<html><head>
<style>
body {
	background-image: linear-gradient( 109.6deg,  rgba(48,207,208,1) 11.2%, rgba(51,8,103,1) 92.5% );
	overflow: hidden;
}

.but {
    z-index: 1000;
    position: absolute;
    background-color: #383838;
    padding: 20px 8px 8px 8px;
    border-radius: 6px;
    border: 1px solid #707070;
    top: 6%;
    color: #ffffff;
    text-decoration: none;
    right: 1%;
}
	
.but:hover {
    background-color: #000000;
}

.but1 {
    z-index: 1000;
    position: absolute;
    background-color: #646464;
    padding: 50px 8px 50px 8px;
    border-radius: 6px;
    border: 1px solid #707070;
    top: 81%;
    color: #ffffff;
    text-decoration: none;
    opacity: 0.8;
}

.info {
    z-index: 1000;
    position: absolute;
    top: 8%;
	color: #fff;
}
  
.but:hover {
	opacity: 0.8;
}

.but1:hover {
	opacity: 0.8;
}
</style>
</head>

<body>
<a class="but" href="#" onClick="Bgs()">Switch Background</a>



<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>

<script>
    var count = 0;
    var n = 10;

    function Bgs() {
        if (count === 0) {
            $('body').css({'background-image': 'linear-gradient( 110.6deg,  rgba(179,157,219,1) 7%, rgba(150,159,222,1) 47.7%, rgba(24,255,255,1) 100.6% )', 'background-repeat': 'repeat'})
        } else if (count === 1) {
            $('body').css({'background-image': 'url(https://i.imgur.com/tzY1XF4.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 2) {
            $('body').css({'background-image': 'url(https://i.imgur.com/7ktvjTE.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 3) {
            $('body').css({'background-image': 'url(https://i.imgur.com/uMkTAti.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 4) {
            $('body').css({'background-image': 'url(https://i.imgur.com/fyiMWW3.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 5) {
            $('body').css({'background-image': 'url(https://i.imgur.com/rDGdxBJ.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 6) {
            $('body').css({'background-image': 'url(https://i.imgur.com/RxLOJL6.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 7) {
            $('body').css({'background-image': 'url(https://i.imgur.com/iZHTxNZ.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 8) {
            $('body').css({'background-image': 'url(https://i.imgur.com/7ktvjTE.jpg)', 'background-repeat': 'no-repeat', 'background-size': '100%'});
        } else if (count === 9) {
            $('body').css({'background-image': 'linear-gradient( 109.6deg,  rgba(48,207,208,1) 11.2%, rgba(51,8,103,1) 92.5%', 'background-repeat': 'repeat'});
        }

        count += 1;
        if (count === n)
            count = 0;
    }
</script>
</body></html>
