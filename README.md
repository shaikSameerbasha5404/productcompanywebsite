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
layout.css
```css
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
  border-radius: 10px;
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
  font-family: Franklin Gothic Medium;
  font-size: 60px;
  background-image: url("/static/img/milk_products.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: rgb(210, 12, 236);
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  font-style: italic;
  background-color: rgb(150, 206, 203);
  text-align: center;
  padding-top: 15px;
  border-radius: 10px;
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
  background-image: url("/static/img/dairy-main-banner.jpg");
  background-position: center;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: rgb(247, 231, 10);
  border-style: solid;
  border-radius: 10px;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  font-weight: 600;
}
.homecontent h1 {
  text-align: left;
  color: rgb(230, 137, 17);
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: rgb(255, 211, 67);
  font-family: ;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
    color: rgb(241, 181, 15);
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
    font-size: 40px;
    color: rgb(53, 243, 6);
    font-weight: 600;
  display: block;
}
.productitem .itemprice {
    color: blueviolet;
    font-weight: 900;
    font-family: Calisto MT;
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(118, 163, 231);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  border-radius: 10px;
  color: rgb(241, 198, 4);
}

```
home.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Samurai Private limited</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Samurai milk products</div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
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
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Obed Otto.
      </div>
    </div>
  </body>
</html>
```
products.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Our Products.</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our special products.</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/milk pack.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Milk</div>
                  <div class="itemprice">Price: Rs.30.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/curd.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Curd</div>
                  <div class="itemprice">Price: Rs.35.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/paneer.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Paneer</div>
                  <div class="itemprice">Price: Rs.100.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ghee.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Ghee</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Obed Otto.
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:
### Home Page:
![Screenshot (69)](https://user-images.githubusercontent.com/118707756/215104697-75f54bcd-2bc4-4e95-83e7-0cedda3c2070.png)
### Products Page:
![Screenshot (70)](https://user-images.githubusercontent.com/118707756/215104893-3a808755-e4f7-4bcb-aeaf-96e8869184a2.png)
### HTML VALIDATOR:
#![Screenshot (71)](https://user-images.githubusercontent.com/118707756/215105799-099e7c5c-6280-4505-bac1-f6e556fe6010.png)
## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
