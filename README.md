# Staticlayout
<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

html {
    width: 1000px;
    height: 2000px;
}
body {
  font-family: Caliber;
  padding: 10px;
  background: #f1f1f1;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  margin-right: 40px;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.option li {
    list-style: none;
    float: left;
    font-size: 16pt;
    padding-right: 30px;
}

/* section 2 */
.one, .two, .three{
	float:left;
}
.three li {
	list-style: none;
}
.clearfix::after {
	content:"";
	clear: both;
	display: table;
}
.container {
	display: block;
	background-color: lightgray;
}
/* section 3 */
.flex-container {
  display: flex;
  flex-direction: row;
  margin-left: 100px;
}

.flex-container > div {
  background-color: #f1f1f1;
  width: 100px;
  margin: 0 40px 0 0;
  text-align: center;
  line-height: 25px;
  font-size: 30px;
  padding: 10px;
}

.offer li {
    list-style: none;
    float: left;
    font-size: 20pt;
    margin: 0;
    padding: 0;
}

/* section 4 */
.flex-containers {
  display: flex;
  flex-direction: row;
}

.flex-containers > div {
  background-color: #0feaf1;
  width: 240px;
  margin-left: 85px;
  padding: 5px;
  text-align: center;
  line-height: 25px;
  font-size: 30px;
}

.jan, .feb, .mar, .apr {
  margin: 5px 35px 0 35px;
  padding: 5px;
  font-size: 20pt;
}


/* section 5 */
.ones, .twos, .threes, .fours{
	font-size: 16pt;
	float:left;
	color: white;
	line-height: 1.5;
}
.ones li, .twos li, .threes li, .fours li{
	list-style: none;
}

.containerFooter {
	display: block;
	background-color: black;
	height: 500px;
}

.final {
  color: #ff0000;
  margin: -50px 0 0 90px;
}

</style>
</head>
<body>

    <div class="topnav" style="width: 1320px;">
      <a href="#" style="font-size:48pt; margin-left: 100px;">eStore</a>
      <a href="#" style="float:right; padding-top: 40px;">Checkout</a>
      <a href="#" style="float:right; padding-top: 40px;">Cart</a>
      <a href="#" style="float:right; padding-top: 40px;">Shopping</a>
      <a href="#" style="float:right; padding-top: 40px;">Wish List</a>
      <a href="#" style="float:right; padding-top: 40px;">My Account</a>
    </div>

    <div class="option" style="width: 1300px;">
        <ul>
            <li>Men</li>
            <li>Women</li>
            <li>Kids</li>
            <li>Protective Wear</li>
            <li>Footwear</li>
            <li>Accessories</li>
            <li>Friday Causal</li>
            <li style="float: right; border: 1.5px solid black; padding: 7px 30px 7px 7px;">Search for Products & Brands</li>
        </ul>
    </div>
    <br><br><br>
    
    <div class="container clearfix" style="width: 1320px;">
      <div class="one" style="width:33.3%;">
        <img src="masks.jpg" alt="Image of an mask" style="height:240px; margin: 160px 0 100px 20px;">
      </div>
      <div class="two" style="width:33.3%;">
        <p style="font-size:50pt; margin: 220px 0 150px -40px;">STAY HOME, STAY SAFE.</p>
      </div>
      <div class="three" style="width:33.3%; font-size:18pt; line-height: 2; margin-left: -70px;">
        <ul>
          <li>Contactless Deliveries</li>
          <li>All delivery staff trained in COVID-19 preventive measures</li>
          <li>All Delivery and warehouse staff are equipped with medical-grade hand Santiziers</li>
          <li>All warehouses staff undergo daily mandatory thermal temperature scanning</li>
          <li>No deliveries in 'highly affected' areas</li>
        </ul>
      </div>
    </div>

    <h2 style="font-size: 30pt; margin-left: 85px;"><b>Deals of the day</b></h2>
    <div class="flex-container">
      <div style="width: 16.66%;"><img src="placeholder123.jpg" alt="image"></div>
      <div style="width: 16.66%;"><img src="placeholder123.jpg" alt="image"></div>
      <div style="width: 16.66%;"><img src="placeholder123.jpg" alt="image"></div>
      <div style="width: 16.66%;"><img src="placeholder123.jpg" alt="image"></div>
      <div style="width: 16.66%;"><img src="placeholder123.jpg" alt="image"></div>
      <div style="width: 16.66%;"><img src="placeholder123.jpg" alt="image"></div>
    </div>
    <div class="offer clearfix" style="width: 1200px; margin-left: 50px;">
        <ul>
            <li style="width:12.66%; margin-left: 25px;">Sports & Fitness Gear Upto 80% Off</li>
            <li style="width:12.66%; margin-left: 38px;">Branded Jeans Upto 50% Off</li>
            <li style="width:12.66%; margin-left: 35px;">Branded T-Shrits Upto 60% Off</li>
            <li style="width:12.66%; margin-left: 40px;">Sports & Fitness Gear Upto 50% Off</li>
            <li style="width:12.66%; margin-left: 32px;">Branded Kids T Shrits Upto 40% Off</li>
            <li style="width:12.66%; margin-left: 36px;">Sports Girls T Shrits Upto 550% Off</li>
        </ul>
    </div>

    <h2 style="font-size: 30pt; margin-left: 85px;"><b>Fashion categories</b></h2>
    <div class="flex-containers">
      <div><img src="placeholder.png" alt="image"> <p class="jan">Kurtas</p></div>
      <div><img src="placeholder.png" alt="image"> <p class="feb">Shirts</p></div>
      <div><img src="placeholder.png" alt="image"> <p class="mar">Pants</p></div>  
      <div><img src="placeholder.png" alt="image"> <p class="apr">TShrits</p></div> 
    </div>
    <br><br><br>
    <div class="flex-containers">
      <div><img src="placeholder.png" alt="image"> <p class="jan">Shoes</p></div>
      <div><img src="placeholder.png" alt="image"> <p class="feb">Causal Shirts</p></div>
      <div><img src="placeholder.png" alt="image"> <p class="mar">JEANS</p></div>  
      <div><img src="placeholder.png" alt="image"> <p class="apr">Tops</p></div> 
    </div>
    <br><br>
    
    <div>
      <p style="font-size: 14pt; margin-left: 85px; width: 1200px;">Adidas | Arrow | Fila | Online Shopping | Nike | Pepe Jeans | Puma | United Colors of Benetton | Fastrack | Shorts | Being Human | Skirts | Woodland</p>
      <p style="font-size: 14pt; margin-left: 85px; width: 1200px;">Supra Dresses Clothing | Jewellery | T-shrits | Shoes | Bags | Watches | Caps | Shrits | Backpacks | Flip Flops | Sunglasses | kurtas | Jackets | Skechers</p>
      <p style="font-size: 14pt; margin-left: 85px; width: 1200px;">Saree | Sandals | Puma Tshrits | Woodland Shoes | Titan Watches | Fastrack Watches | Wrangular Shrits | Adidas Tshrits | Nike Shoes | Roadster Shirts</p>
      <p style="font-size: 14pt; margin-left: 85px; width: 1200px;">Causal Shoes | Running Shoes | Nike Sports Shoes | Jeans | Being Human | Tshrits | Converse Shoes | Cricket Shoes</p>
    </div>
    <br><br>

    <div class="containerFooter clearfix" style="width: 1320px;">
      <div class="ones" style="margin-left: 50px;">
        <ul>
          <li style="font-size: 18pt;">MY ACCOUNT</li>
          <li>Orders</li>
          <li>Returns/Refunds</li>
          <li>Track Order</li>
          <li>Frequently Asked Questions</li>
        </ul>
      </div>
      <div class="twos">
        <ul>
          <li style="font-size: 18pt;">POLICIES</li>
          <li>Payment Options</li>
          <li>Terms & Conditions of Use</li>
          <li>Terms & Conditions of Membership Program</li>
          <li>Offer Terms & Conditions</li>
          <li>Returns & Exchange Policy</li>
          <li>Shipping Policy</li>
          <li>Privacy Policy</li>
          <li>Safety Checklist</li>
        </ul>
      </div>
      <div class="threes">
        <ul>
          <li style="font-size: 18pt;">CONTACT US</li>
          <li>Customer Support</li>
          <li>Store Locators</li>
          <li>Help Center</li>
          <li style="font-size: 18pt;">ABOUT US</li>
          <li>Offical Brand Store</li>
          <li>About Us</li>
          <li>Careers</li>
        </ul>
      </div>
      <div class="fours">
        <ul>
          <li style="font-size: 18pt;">SOCIAL</li>
          <li>Facebook</li>
          <li>Twitter</li>
          <li>YOutube</li>
        </ul>
      </div>
    </div>
    <p class="final">Note : This layout for HTML5 & CSS3 Handson Practise.</p>
</body>
</html>