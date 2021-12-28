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
layout,css M
```
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
  background-image: url("/static/img/adobe.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
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
  color: #16d1ae;
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
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
home
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adobe Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/adobe.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by A.Ruchitha Reddy.
      </div>
    </div>
  </body>
</html>
```
products
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adobe Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/r1.jfif" alt="product image">
                  </div>
                  <div class="itemname">Acrobat Pro</div>
                  <div class="itemprice">Price: Rs.4000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/r2.png"  alt="product image">
                  </div>
                  <div class="itemname">Photoshop</div>
                  <div class="itemprice">Price: Rs.1000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/r3.png"  alt="product image">
                </div>
                <div class="itemname">Indesign</div>
                <div class="itemprice">Price: Rs.15000 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/r4.png"  alt="product image">
              </div>
              <div class="itemname">Illustrator</div>
              <div class="itemprice">Price: Rs.4000 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/r5.png"  alt="product image">
            </div>
            <div class="itemname">After Effects</div>
            <div class="itemprice">Price: Rs.3800 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/r6.png"  alt="product image">
          </div>
          <div class="itemname">Adobe XD</div>
          <div class="itemprice">Price: Rs.3200</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/r7.png"  alt="product image">
        </div>
        <div class="itemname">Dreamweaver</div>
        <div class="itemprice">Price: Rs.2700 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/r8.png"  alt="product image">
      </div>
      <div class="itemname">Animate</div>
      <div class="itemprice">Price: Rs.5200 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/r9.png"  alt="product image">
    </div>
    <div class="itemname">Aero</div>
    <div class="itemprice">Price: Rs.4200 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/r10.png"  alt="product image">
  </div>
  <div class="itemname">Photoshop Express</div>
  <div class="itemprice">Price: Rs.6000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/r11.png"  alt="product image">
  </div>
  <div class="itemname">InCopy</div>
  <div class="itemprice">Price: Rs.1800 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/r12.png"  alt="product image">
  </div>
  <div class="itemname">Substance 3D Sampler</div>
  <div class="itemprice">Price: Rs.4800 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by A.Ruchitha Reddy.
      </div>
    </div>
  </body>
</html>
```
people
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adobe</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/me.jpg" alt="product image">
                </div>
                <div class="itemname">A.Ruchitha Reddy</div>
                <div class="itemprice">CEO </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/x1.jfif"  alt="product image">
                </div>
                <div class="itemname">Shaheer</div>
                <div class="itemprice">DSM</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/x3.jfif"  alt="product image">
              </div>
              <div class="itemname">Ankit mohan</div>
              <div class="itemprice">Assistant HR </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/x4.jfif"  alt="product image">
              </div>
              <div class="itemname">Saurab</div>
              <div class="itemprice">HR </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/x5.jfif"  alt="product image">
            </div>
            <div class="itemname">Travisht</div>
            <div class="itemprice">RSM </div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/x6.jfif"  alt="product image">
          </div>
          <div class="itemname">Dev Adithya</div>
          <div class="itemprice">senior manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Adobe Private Limited, Developed by A.Ruchitha Reddy.
    </div>
  </div>
</body>
</html>
```
contact us
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adobe</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            22-8-219/2b ,S L V nagar,Revenue ward no 22, tirupathi,AP INDIA.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Miss.A.Ruchitha Reddy(HR):8179056493<br><br>
              Miss.A.Swetha Reddy(Assistant HR):7842854582
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:reddyruchitha90@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  Adobe Private Limited, Developed by A.Ruchitha reddy.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](https://github.com/RuchithaReddy28/productcompanywebsite/blob/main/home.PNG?raw=true)
## products 
![output](https://github.com/RuchithaReddy28/productcompanywebsite/blob/main/products.PNG?raw=true)
## people
![output](https://github.com/RuchithaReddy28/productcompanywebsite/blob/main/people.PNG?raw=true)
## contact us
![output](https://github.com/RuchithaReddy28/productcompanywebsite/blob/main/contact.PNG?raw=true)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
