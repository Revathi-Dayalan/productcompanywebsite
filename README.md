# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home page coding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJSoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/bookr.png" alt="Building" />
          <div class="contenttext">
            Welcome to RJsoftware Limited!
            RJsoftware is an online bookstore with a mission to financially support local, 
            independent bookstores.
            We believe that bookstores are essential to a healthy culture. 
            They are where authors can connect with readers, 
            where we discover new writers, where children get hooked on the thrill of 
            reading that can last a lifetime. They are also anchors for our downtowns and communities.
           <br />
           We hope that Bookshop can help strengthen the fragile ecosystem and margins around bookselling 
           and keep local bookstores an integral part of our culture and communities.
           Bookshop is a benefit corporation - a corporation dedicated to the public good.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
      </div>
    </div>
  </body>
</html>

### products:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJsoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book1.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer course</div>
                <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book2.jfif"  alt="product image">
                </div>
                <div class="itemname">Code</div>
                <div class="itemprice">Price: Rs.6,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book3.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer</div>
                <div class="itemprice">Price: Rs.9,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book4.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer</div>
                <div class="itemprice">Price: Rs.6,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book5.jpg"  alt="product image">
                </div>
                <div class="itemname">C++</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book6.jpg"  alt="product image">
                </div>
                <div class="itemname">Math in computer</div>
                <div class="itemprice">Price: Rs.9,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book7.png"  alt="product image">
                </div>
                <div class="itemname">Computer</div>
                <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book8.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer programing</div>
                <div class="itemprice">Price: Rs.9,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book9.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer application</div>
                <div class="itemprice">Price: Rs.8,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book10.jpg"  alt="product image">
                </div>
                <div class="itemname">computer</div>
                <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
      </div>
    </div>
  </body>
</html>

### contact:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJsoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>
  
  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Address: 31, gandhi nagar, adyar, Chennai - 6000105
           <br>Phone:7852347509
           <br>Email-address:Onlineproductssale@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
</div>
</div>
</body>
</html>

### people:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJsoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c1.jfif"  alt="product image">
      </div>
         <div class="itemname">Navnit Nakra</div>
         <div class="itemname">CEO</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c2.jfif"  alt="product image">
      </div>
         <div class="itemname">Jim Lanzone</div>
         <div class="itemname">Assissant ceo</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c3.jfif"  alt="product image">
      </div>
        <div class="itemname">Benedetto vigna</div>
        <div class="itemname">Cheif information officer</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c4.jpg"  alt="product image">
      </div>
        <div class="itemname">Marc Llistosella</div>
        <div class="itemname">Project manager</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c5.jpeg"  alt="product image">
      </div>
        <div class="itemname">tony stokes</div>
        <div class="itemname">cheif financial officer</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c6.jpg"  alt="product image">
      </div>
        <div class="itemname">Satya nadella</div>
        <div class="itemname">Team leader</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
      </div>
    </div>
  </body>
</html>

### layout:
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/shop.jfif");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #e6a667;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #6784e6;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #67e6c2;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #6784e6;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}### home page coding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJSoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/bookr.png" alt="Building" />
          <div class="contenttext">
            Welcome to RJsoftware Limited!
            RJsoftware is an online bookstore with a mission to financially support local, 
            independent bookstores.
            We believe that bookstores are essential to a healthy culture. 
            They are where authors can connect with readers, 
            where we discover new writers, where children get hooked on the thrill of 
            reading that can last a lifetime. They are also anchors for our downtowns and communities.
           <br />
           We hope that Bookshop can help strengthen the fragile ecosystem and margins around bookselling 
           and keep local bookstores an integral part of our culture and communities.
           Bookshop is a benefit corporation - a corporation dedicated to the public good.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
      </div>
    </div>
  </body>
</html>

### products:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJsoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book1.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer course</div>
                <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book2.jfif"  alt="product image">
                </div>
                <div class="itemname">Code</div>
                <div class="itemprice">Price: Rs.6,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book3.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer</div>
                <div class="itemprice">Price: Rs.9,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book4.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer</div>
                <div class="itemprice">Price: Rs.6,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book5.jpg"  alt="product image">
                </div>
                <div class="itemname">C++</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book6.jpg"  alt="product image">
                </div>
                <div class="itemname">Math in computer</div>
                <div class="itemprice">Price: Rs.9,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book7.png"  alt="product image">
                </div>
                <div class="itemname">Computer</div>
                <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book8.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer programing</div>
                <div class="itemprice">Price: Rs.9,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book9.jpg"  alt="product image">
                </div>
                <div class="itemname">Computer application</div>
                <div class="itemprice">Price: Rs.8,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/book10.jpg"  alt="product image">
                </div>
                <div class="itemname">computer</div>
                <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
      </div>
    </div>
  </body>
</html>

### contact:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJsoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>
  
  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Address: 31, gandhi nagar, adyar, Chennai - 6000105
           <br>Phone:7852347509
           <br>Email-address:Onlineproductssale@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
</div>
</div>
</body>
</html>

### people:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>RJsoftware Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">RJsoftware Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c1.jfif"  alt="product image">
      </div>
         <div class="itemname">Navnit Nakra</div>
         <div class="itemname">CEO</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c2.jfif"  alt="product image">
      </div>
         <div class="itemname">Jim Lanzone</div>
         <div class="itemname">Assissant ceo</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c3.jfif"  alt="product image">
      </div>
        <div class="itemname">Benedetto vigna</div>
        <div class="itemname">Cheif information officer</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c4.jpg"  alt="product image">
      </div>
        <div class="itemname">Marc Llistosella</div>
        <div class="itemname">Project manager</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c5.jpeg"  alt="product image">
      </div>
        <div class="itemname">tony stokes</div>
        <div class="itemname">cheif financial officer</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/c6.jpg"  alt="product image">
      </div>
        <div class="itemname">Satya nadella</div>
        <div class="itemname">Team leader</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 RJsoftware Private Limited, Developed by Janani.R
      </div>
    </div>
  </body>
</html>

### layout:
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/shop.jfif");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #e6a667;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #6784e6;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #67e6c2;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #6784e6;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

## OUTPUT:


### Home Page:
![output](.//screeenshot (55).jpg)
![output](.//screeenshot (55).jpg)
![output](.//screeenshot (55).jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
