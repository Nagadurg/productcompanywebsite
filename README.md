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
```
HOME PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>realme narzo</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">realme narzo</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/icon1.png" alt="icon" />
          <div class="contenttext">
            Before its startup on May 4, 2018, in India, Realme first appeared
            in China in 2010 with the name "OPPO Real".[1] It was a sub-brand of
            OPPO (which is itself a subsidiary of BBK Electronics)[2] until its 
            formation as a spinoff on May 4, 2018.[3][4][5]. Former Oppo Vice President
            and Head of Oppo India and Overseas Department, Sky Li, has still remember
            his time during the 2017 Diwali festival in India before his foundation of this company.
            In May 2018, they released their first phone, Realme 1.
            <br />
            According to a report from the international analyst institution Counterpoint,
            Realme recorded shipping 4.7 million units worldwide in the second quarter of
            2019, which is an 848% year-on-year increase, and has become one of the top
            10 mobile phone manufacturers in the world.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 realme narzo, Developed by ch.nagadurga.
      </div>
    </div>
  </body>
</html>

PRODUCTS PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>realme narzo</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">realme narzo.</div>
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
                  <img src="./img/d1.PNG"  alt="product image">
                  </div>
                  <div class="itemname">realme1</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/d2.PNG"  alt="product image">
                </div>
                <div class="itemname">realme2</div>
                <div class="itemprice">Price: Rs.15,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/d3.PNG"  alt="product image">
              </div>
              <div class="itemname">realme3</div>
              <div class="itemprice">Price: Rs.17,000.00 </div>
           </div>
           <div class="productitem"> 
             <div class="itemimage">
             <img src="./img/d4.PNG"  alt="product image">
             </div>
             <div class="itemname">realme4</div>
             <div class="itemprice">Price: Rs.22,000.00 </div>
           </div>
           <div class="productitem"> 
            <div class="itemimage">
            <img src="./img/d5.PNG"  alt="product image">
            </div>
            <div class="itemname">realme5</div>
            <div class="itemprice">Price: Rs.26,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="./img/d6.PNG"  alt="product image">
            </div>
            <div class="itemname">realme6</div>
            <div class="itemprice">Price: Rs.29,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="./img/d7.PNG"  alt="product image">
            </div>
            <div class="itemname">realme7</div>
            <div class="itemprice">Price: Rs.32,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="./img/d8.PNG"  alt="product image">
        </div>
        <div class="itemname">realme8</div>
        <div class="itemprice">Price: Rs.38,000.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="./img/d9.PNG"  alt="product image">
    </div>
    <div class="itemname">realme9</div>
    <div class="itemprice">Price: Rs.41,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="./img/d10.PNG"  alt="product image">
  </div>
  <div class="itemname">realme10</div>
  <div class="itemprice">Price: Rs.45,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="./img/d11.PNG"  alt="product image">
  </div>
  <div class="itemname">realme11</div>
  <div class="itemprice">Price: Rs.49,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="./img/d12.PNG"  alt="product image">
  </div>
  <div class="itemname">realme12</div>
  <div class="itemprice">Price: Rs.55,000.00 </div>
</div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 realme narzo, Developed by ch.nagadurga.
      </div>
    </div>
  </body>
</html>

 PEOPLE PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>realme narzo</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">realme narzo</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Meet Our Team</h1>
          <table>
            <tr> 
            <td>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/nd1.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Lisa Su </div> <br>
                  <div class="itemprice"> CEO  </div> 
                </td>
            <td>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="./img/nd2.jpg" alt="product image">
                    </div>
                    <div class="itemname"> Karen Lynch </div> <br>
                    <div class="itemprice">Managing Director</div>
                </td>
                <td>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="./img/nd3.jpg" alt="product image">
                        </div>
                        <div class="itemname">Dilip</div> <br>
                        <div class="itemprice">Project Director</div>

                </td>  
            </tr>
            <tr>
                <td>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="./img/nd4.jpg" alt="product image">
                        </div>
                        <div class="itemname">Barry Leo</div> <br>
                        <div class="itemprice">Senior Manager</div>
                    </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/nd5.jpg" alt="product image">
                            </div>
                            <div class="itemname">Safra Catz</div><br>
                            <div class="itemprice"> Manager</div>

                    </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/nd6.webp" alt="product image">
                            </div>
                            <div class="itemname">David Hason</div> <br>
                            <div class="itemprice">Senior Team Leader</div>
                    </td>

            </tr>    
            </table>
            </div>
            </div>
        </body>
        </html>

CONTACT US PAGE:

!DOCTYPE html>
<html lang="en">
  <head>
    <title>realme narzo</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">realme narzo</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="contactus" background-image="url(/static/img/cbg.jpg")>
          OFFICE ADDRESS <br>
          <hr style="height:2px;border-width:5px;color:#e6752f;background-color: #e6752f">
          
          806v, 
          Marque Estate,<br>
          Chennai,<br>
          76009,<br>
          India<br>

          CONTACT ADDRESS<br>
          <hr style="height:2px;border-width:5px;color:#e6752f;background-color: #e6752f">
          
          Tel: 044-87635421
               044-87635422
          Fax: 0091-67-6784890
          E-mail: Wcrft4528@manufav.com
          <br>
           For Service Queries or Complaints: sales.wc@Service.com
        
        </div>
        <div class="footer">
            Copyright &#169; 2021 realme narzo, Developed by ch.nagajyothi.
          </div>

      </div>
      </body>
      </html>
```
## OUTPUT:

### Home Page:

![output](https://github.com/Nagadurg/productcompanywebsite/blob/4636766702e4abf185ae8df0f4638adcd535904b/companywebsite/static/img/P1.PNG)

### Product Page:

![output](https://github.com/Nagadurg/productcompanywebsite/blob/4636766702e4abf185ae8df0f4638adcd535904b/companywebsite/static/img/P2.PNG)

### People Page:

![output](https://github.com/Nagadurg/productcompanywebsite/blob/4636766702e4abf185ae8df0f4638adcd535904b/companywebsite/static/img/P3.PNG)

### Contact us Page:

![output](https://github.com/Nagadurg/productcompanywebsite/blob/4636766702e4abf185ae8df0f4638adcd535904b/companywebsite/static/img/P4.PNG)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
