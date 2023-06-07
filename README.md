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

### Home Page:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AR Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/camera.png" alt="Building" />
          <div class="contenttext">
            Welcome to Camera Sale Hub!

            At Camera Sale Hub, we are your one-stop destination for all things camera-related.
            We understand that finding the perfect camera at an affordable price can be a daunting task,
            and that's where we come in. Our mission is to provide you with a seamless shopping experience,
            offering a wide range of cameras and accessories at competitive prices.
            <br />
            <br>
            We take pride in curating an extensive collection of cameras, lenses, and accessories to suit every 
            photographer's needs.From entry-level point-and-shoot cameras to professional DSLRs and mirrorless cameras, 
            we have a range of options to cater to all skill levels and budgets. Our inventory consists of the latest models, 
            ensuring that you stay up-to-date with the ever-evolving world of photography.
            <ul>
                <br>
             Best Sale going on;<br>
              <li>Canon</li>
              <li>Nikon</li>
              <li>Sony</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AR Private Limited, Developed by Aakashraj M.
      </div>
    </div>
  </body>
</html>
```
### Product

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">AR Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/camera 1.png" alt="product image">
                  </div>
                  <div class="itemname">Sony S20</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/camera 2.png"  alt="product image">
                  </div>
                  <div class="itemname">Canon Z50</div>
                  <div class="itemprice">Price: Rs.60,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/camera 3.png"  alt="product image">
                  </div>
                  <div class="itemname">Osaka Flashlight</div>
                  <div class="itemprice">Price: Rs.3,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/camera 4.png"  alt="product image">
                  </div>
                  <div class="itemname">Nikon Waterproof 22</div>
                  <div class="itemprice">Price: Rs.55,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/camera 5.png"  alt="product image">
                  </div>
                  <div class="itemname">FitSpark i12</div>
                  <div class="itemprice">Price: Rs.8,300.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/camera 6.png"  alt="product image">
                  </div>
                  <div class="itemname">GoPro Hero 11</div>
                  <div class="itemprice">Price: Rs.30,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 AR Private Limited, Developed by Aakashraj M.
      </div>
    </div>
  </body>
</html>

```
### People
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">AR Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected">
          <a href="/static/people.html">People</a>
        </div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our PEOPLES</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/AR.jpg" alt="">
                  </div>
                  <div class="itemname">Aakashraj</div>
                  <div class="itemprice">Founder</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/PR.jpg"  alt="">
                  </div>
                  <div class="itemname">Prajeeth</div>
                  <div class="itemprice">CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/MANI.jpg"  alt="">
                  </div>
                  <div class="itemname">Jayamani</div>
                  <div class="itemprice">Manager</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/Jaya.jpg"  alt="">
                  </div>
                  <div class="itemname">Jayavarathan</div>
                  <div class="itemprice">Assistant-Manager</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/darshan.jpg"  alt="">
                  </div>
                  <div class="itemname">Darshan</div>
                  <div class="itemprice">Supervisior</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/pradeep.jpg"  alt="">
                  </div>
                  <div class="itemname">Pradeep</div>
                  <div class="itemprice">Mentor</div>
              </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 AR Private Limited, Developed by Aakashraj M.
      </div>
    </div>
  </body>
</html>
```
### Contact Us:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">AR Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected">
          <a href="/static/contact.html">Contact us</a>
        </div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>TO CONTACT US</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/call 1.png" alt="">
                  </div>
                  <div class="itemname">Call us: </div>
                  <div class="itemprice">6381366409</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/mail.png"  alt="">
                  </div>
                  <div class="itemname">Mail us:</div>
                  <div class="itemprice">edusoftpvt@gmail.com</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/location.png"  alt="">
                  </div>
                  <div class="itemname">Reach us:</div>
                  <div class="itemprice">Block-87,Gandhi nagar,Chennai-81,Tamilnadu,India.</div>
              </div>
         </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 AR Private Limited, Developed by Aakashraj M.
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:

### Home Page:
![Home](https://github.com/Aakashraj04/productcompanywebsite/assets/121117266/77de8218-f991-40af-a610-04ba162d032e)

### Product Page:
![product](https://github.com/Aakashraj04/productcompanywebsite/assets/121117266/43fd44ba-2091-4391-bdbf-2be4cef0547b)

### People Page:
![People](https://github.com/Aakashraj04/productcompanywebsite/assets/121117266/98b60ad8-e6b6-4e06-9d36-2e223f69fde0)

### Contact Us Page:
![contact ](https://github.com/Aakashraj04/productcompanywebsite/assets/121117266/902027e7-55af-4701-be59-097c4a61ad4b)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
