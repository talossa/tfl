


<a href="https://drive.google.com/file/d/1gdZPr6FWmMy-J4uvFzJi1J-7NzfFoiNb/view?usp=drivesdk"> map        </a>

<a href="https://moovitapp.com/?metroId=2122"> route planner </a>



<iframe src="https://free.timeanddate.com/countdown/i6wjyv1s/n101/cf100/cm0/cu4/ct5/cs1/ca0/co0/cr0/ss0/cac000/cpc000/pct/tc66c/fn3/fs175/szw320/szh135/iso2019-11-02T07:30:00" allowTransparency="true" frameborder="0" width="320" height="135"></iframe>


<script>(function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        var ro = !!d.getElementById(id);
        js = d.createElement(s); js.id = id;
        js.src = "https://widgets.moovit.com/ws/90B471657AD81967E0530100007F0087/3032576";
        fjs.parentNode.insertBefore(js, fjs);
    })(document, 'script', 'moovit-jsw');</script>

   <div class="mv-gd-widget-20" 
        data-width="100%" 
        data-height="100%"
        data-id="3032576"></div>













<!DOCTYPE html>
<html>
<head>
	<meta charset='utf-8'/>
	<title>jQuery Zoom Demo</title>
	<style>
		/* styles unrelated to zoom */
		* { border:0; margin:0; padding:0; }
		p { position:absolute; top:3px; right:28px; color:#555; font:bold 13px/1 sans-serif;}
		.zoom {
			display:inline-block;
			position: relative;
		}
		.zoom img {
			display: block;
		}
                .zoom img::selection { background-color: transparent; }
		#ex2 img:hover { cursor: url(grab.cur), default; }
		#ex2 img:active { cursor: url(grabbed.cur), default; }
	</style>
	<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js'></script>
	<script src='jquery.zoom.js'></script>
	<script>
		$(document).ready(function(){
			$('#ex1').zoom();
			$('#ex2').zoom({ on:'grab' });
			$('#ex3').zoom({ on:'click' });			 
			$('#ex4').zoom({ on:'toggle' });
		});
	</script>
</head>
<body>
	<span class='zoom' id='ex1'>
		<img src='https://tfl.gov.uk/cdn/static/cms/images/london-rail-and-tube-services-map.gif' width='555' height='320' alt='Daisy on the Ohoopee'/>
		<p>Hover</p>
	</span>
	<span class='zoom' id='ex2'>
		<img src='https://tfl.gov.uk/cdn/static/cms/images/london-rail-and-tube-services-map.gif' width='290' height='320' alt='Roxy on the Ohoopee'/>
		<p>Grab</p>
	</span>
	<span class='zoom' id='ex3'>
		<img src='https://tfl.gov.uk/cdn/static/cms/images/london-rail-and-tube-services-map.gif' width='555' height='320' alt='Daisy on the Ohoopee'/>
		<p>Click to activate</p>
	</span>
	<span class='zoom' id='ex4'>
		<img src='https://tfl.gov.uk/cdn/static/cms/images/london-rail-and-tube-services-map.gif' width='290' height='320' alt='Roxy on the Ohoopee'/>
		<p>Click to toggle</p>
	</span>
</body>
</html>
