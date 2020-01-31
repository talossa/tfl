
<html>
<head>

</head>
</html>

<a href="https://drive.google.com/file/d/1zkHnFcyZ5oz9iL5d2erzsCG2O8G_w8e-/view?usp=sharing"> map        </a>

<a href="https://moovitapp.com/?metroId=2122"> route planner </a>



<iframe src="https://free.timeanddate.com/countdown/i6wjyv1s/n101/cf100/cm0/cu4/ct5/cs1/ca0/co0/cr0/ss0/cac000/cpc000/pct/tc66c/fn3/fs175/szw320/szh135/iso2020-06-15T08:05:00" allowTransparency="true" frameborder="0" width="320" height="135"></iframe>











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





<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {box-sizing: border-box;}

.img-zoom-container {
  position: relative;
}

.img-zoom-lens {
  position: absolute;
  border: 1px solid #d4d4d4;
  /*set the size of the lens:*/
  width: 60px;
  height: 60px;
}

.img-zoom-result {
  border: 1px solid #d4d4d4;
  /*set the size of the result div:*/
  width: 440px;
  height: 440px;
}
</style>
<script>
function imageZoom(imgID, resultID) {
  var img, lens, result, cx, cy;
  img = document.getElementById(imgID);
  result = document.getElementById(resultID);
  /*create lens:*/
  lens = document.createElement("DIV");
  lens.setAttribute("class", "img-zoom-lens");
  /*insert lens:*/
  img.parentElement.insertBefore(lens, img);
  /*calculate the ratio between result DIV and lens:*/
  cx = result.offsetWidth / lens.offsetWidth;
  cy = result.offsetHeight / lens.offsetHeight;
  /*set background properties for the result DIV:*/
  result.style.backgroundImage = "url('" + img.src + "')";
  result.style.backgroundSize = (img.width * cx) + "px " + (img.height * cy) + "px";
  /*execute a function when someone moves the cursor over the image, or the lens:*/
  lens.addEventListener("mousemove", moveLens);
  img.addEventListener("mousemove", moveLens);
  /*and also for touch screens:*/
  lens.addEventListener("touchmove", moveLens);
  img.addEventListener("touchmove", moveLens);
  function moveLens(e) {
    var pos, x, y;
    /*prevent any other actions that may occur when moving over the image:*/
    e.preventDefault();
    /*get the cursor's x and y positions:*/
    pos = getCursorPos(e);
    /*calculate the position of the lens:*/
    x = pos.x - (lens.offsetWidth / 2);
    y = pos.y - (lens.offsetHeight / 2);
    /*prevent the lens from being positioned outside the image:*/
    if (x > img.width - lens.offsetWidth) {x = img.width - lens.offsetWidth;}
    if (x < 0) {x = 0;}
    if (y > img.height - lens.offsetHeight) {y = img.height - lens.offsetHeight;}
    if (y < 0) {y = 0;}
    /*set the position of the lens:*/
    lens.style.left = x + "px";
    lens.style.top = y + "px";
    /*display what the lens "sees":*/
    result.style.backgroundPosition = "-" + (x * cx) + "px -" + (y * cy) + "px";
  }
  function getCursorPos(e) {
    var a, x = 0, y = 0;
    e = e || window.event;
    /*get the x and y positions of the image:*/
    a = img.getBoundingClientRect();
    /*calculate the cursor's x and y coordinates, relative to the image:*/
    x = e.pageX - a.left;
    y = e.pageY - a.top;
    /*consider any page scrolling:*/
    x = x - window.pageXOffset;
    y = y - window.pageYOffset;
    return {x : x, y : y};
  }
}
</script>
</head>
<body>


<div class="img-zoom-container">
  <img id="myimage" src="https://tfl.gov.uk/cdn/static/cms/images/london-rail-and-tube-services-map.gif" width="300" height="240">
  <div id="myresult" class="img-zoom-result"></div>
</div>


<script>
// Initiate zoom effect:
imageZoom("myimage", "myresult");
</script>



</body>
</html>

## lennot
541 € - (541 € / 4) = 405.75 €
## asuminen lontoossa
noin 201/yö, 3 yötä lontoossa + palvelumaksut = 755 €, tarkista https://51.fi/eAG
## juna ldn -> brig
= 52.68 €, tarkista https://51.fi/ez8
## juna brig -> LGW
= 23.72 €, tarkista https://51.fi/ez9

# yhteensä 
405.75 + 755 + 52.68 + 23.72  = 
## 1237.15 €
