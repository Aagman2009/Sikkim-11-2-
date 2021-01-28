# Sikkim-11-2-

<div style="padding-left:16px">
  <h2>sikkim</h2>
  <p>THE LAND OF PARADISE</p>
</div><!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body, html {
  height: 100%;
}

.parallax {
  /* The image used */
  background-image: url('https://cdn.theculturetrip.com/wp-content/uploads/2017/11/sikkim.jpg');

  /* Full height */
  height: 56%; 

  /* Create the parallax scrolling effect */
  background-attachment: auto;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
</head>
<body>

<div class="parallax"></div>

<div style="height:180px;background-color:purple;font-size:36px">
Sikkim is a state in northeast India, bordered by Bhutan, Tibet and Nepal. Part of the Himalayas, the area has a dramatic landscape that includes India’s highest mountain, 8,586m Kangchenjunga. Sikkim is also home to glaciers, alpine meadows and thousands of varieties of wildflowers. Steep paths lead to hilltop Buddhist monasteries such as Pemayangtse, which dates to the early 1700s.
</div>

<div class="parallax"></div>

<div style="height:180px;background-color:blue;font-size:36px">
Sikkim, state of India, located in the northeastern part of the country, in the eastern Himalayas. It is one of the smallest states in India. Sikkim is bordered by the Tibet Autonomous Region of China to the north and northeast, by Bhutan to the southeast, by the Indian state of West Bengal to the south, and by Nepal to the west. The capital is Gangtok, in the southeastern part of the state.
</div>

<div class="auto"></div>



<div style="height:180px;background-color:green;font-size:36px">
The Kingdom of Sikkim was founded by the Namgyal dynasty in the 17th century. It was ruled by Buddhist priest-kings known as the Chogyal. ... In 1975, after the Indian Army took over the city of Gangtok, a referendum was held that led to the deposition of the monarchy and Sikkim joining India as its 22nd state.
Royal line: Chogyal
</div>

<div class="parallex"></div>


</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: purple;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc; 
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: green;
  overflow: hidden;
}
</style>
</head>
<body>

<h2>SIKKIM</h2>

<button class="accordion">Food</button>
<div class="panel">
  <p>1 Momos.
2 Thukpa.
3 Phagshapa.
4 Sael Roti.
5 Niguru with Churpi.
6 Gundruk and Sinki.
7 Chang.
8 Thenthuk.
9 Kinema Curry.
10 Chhurpi Soup.</p>
 <a href="#">https://www.crazymasalafood.com/best-20-local-foods-to-be-tried-in-sikkim/ </a>

</div>

<button class="accordion">Tourism</button>
<div class="panel">
  <p>"Wonders do come in small packages!”, and if you want to witness this, you must visit the picturesque state of Sikkim. Tucked away in the lap of the magical Himalayas, though it is the second smallest state in the country, its prismatic beauty and mesmeric charm will make you wonder!

The gateway to the North-Eastern corridor of India, Sikkim not only boasts of its enchanting beauty, but also offers an engrossing list of things to do and places to visit as well. </p>
<"bg color=red">
<a href="#">https://www.esikkimtourism.in/places-to-visit-in-sikkim/ </a>
</div>

<button class="accordion">Others</button>
<div class="panel">
  <p>Sikkim is a state in northeastern India. It borders Tibet in the north and northeast, Bhutan in the east, Nepal in the west, and West Bengal in the south. Sikkim is also close to India's Siliguri Corridor near Bangladesh. Sikkim is the least populous and second smallest among the Indian states. A part of the Eastern Himalaya, Sikkim is notable for its biodiversity, including alpine and subtropical climates, as well as being a host to Kangchenjunga, the highest peak in India and third highest on Earth. Sikkim's capital and largest city is Gangtok. Almost 35% of the state is covered by the Khangchendzonga National Park - a UNESCO World Heritage Site.
  
  Population: 6,19,000 (2012)
Area: 7,096 km²
Founded: 15 May 1975
Capital: Gangtok
Governor: Ganga Prasad
Colleges and universities: Sikkim University · Sikkim Manipal University · Loyola College, Chennai · Namchi Government College</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: purple;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  
}
</style>
</head>
<body>

<div class="topnav" id="myTopnav">
  <a href="#home" class="active">Home</a>
  
 <p>Modern Sikkim is a multiethnic and multilingual Indian state. The official languages of the state are English, Nepali, Sikkimese and Lepcha. Additional official languages include Gurung, Limbu, Magar, Mukhia, Newari, Rai, Sherpa and Tamang for the purpose of preservation of culture and tradition in the state.
Admission to Union: 16 May 1975
Capital: Gangtok
Country: India
Largest city: Gangtok</p>

  <a href="#news">News</a>
  <p>Sikkim (/ ˈ s ɪ k ɪ m /; pronounced [ˈsɪkːɪm]) is a state in northeastern India.It borders Tibet in the north and northeast, Bhutan in the east, Nepal in the west, and West Bengal in the south. Sikkim is also close to India's Siliguri Corridor near Bangladesh.Sikkim is the least populous and second smallest among the Indian states. A part of the Eastern Himalaya, Sikkim is notable for its biodiversity, including alpine and subtropical climates, as well as being a host to Kangchenjunga
  Admission to Union: 16 May 1975
Capital: Gangtok
Country: India
Largest city: Gangtok</p>

  <a href="#contact">places to visit</a>
  Tsomgo Lake, Nathula Pass, Yuksom, Lachung, Lachen, Yumthang Valley, Teesta River, Ravangla, Pelling, Zuluk, Namchi, Khangchendzonga National Park, Rumtek Monastery and many other beautiful places. 
Housing the world’s third highest peak Mount Kanchenjunga (8586 meters) within its bounds, this Himalayan state offers you ample reasons to visit it right away. Book your slot of Kanchenjunga trek  today and conquer the challenging trail. Sikkim tourist places are outspread in four divisions of the state which are North, South, East, and West.

The North Sikkim is dotted with dense Alpine forest, steep valleys, pristine waterfalls, tundra regions, and melting snow glaciers. Lachung, Lachen, Chungthang, Yumthang Valley, Mangan, Zemu glacier, Khangchendzonga National Park, etc. fall in this region. Our well crafted 6 Days North Sikkim Tour (Flat 15% Off + 3000 Cashback) covers all these attractions of Sikkim.

Places like Namchi, Temi, Turuk, Yangang to name a few belong to South district the best for tea plantation. Rumtek Monastery, Nathula, Zuluk, Lake Tsomgo and the state capital Gangtok dwells in the district of East Sikkim. Here is the Gangtok Special Tour Package (Flat 32% Off) that has got all these places included in its itinerary. 

Yuksom and Singalila are few of the popular getaways in West Sikkim district which is also known as Gyalshing. You can Book Our West Sikkim Tour (Flat 18% Off) to explore this region of Sikkim. So, check the following list and start planning your visit to Sikkim to discover its vast offerings!</p>

  <a href="#about">Food🍎🍎🍎</a>
  1 Momos.
2 Thukpa.
3 Phagshapa.
4 Sael Roti.
5 Niguru with Churpi.
6 Gundruk and Sinki.
7 Chang.
8 Thenthuk.
9 Kinema Curry.
10 Chhurpi Soup.
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>



<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>

</body>
</html> 
