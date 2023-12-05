    <!-- place some inforamtion in the footer along with social media links -->
    <footer>
        <div class="row">
            <div class="column"> 
                <h2>ROCKS</h2>
                <ul>
                    <li>shapes of crystals</li>
                    <li>types of agate</li>
                    <li>iron crystals in meteorites</li>
                </ul>
            </div>
            <div class="column">
                <h2>MUSIC</h2>
                <ul>
                    <li>beatles now and then</li>
                    <li>is nirvana still talked about?</li>
                    <li>why is music good for the brain</li>
                </ul>
            </div>
    
            <div class="column">
                <h2>GAMES</h2>
                <ul>
                    <li>castlevania inspired by dracula movies</li>
                    <li>pikachu to depart</li>
                    <li>how gamegate led gaming industry to embrace more diverse</li>
                </ul>
    
            </div>
            <div class="column">
                <ul>
                    <li>facebook</li>
                    <li>instagram</li>
                </ul>
            </div>

        </div> 
        <div class="copyright">
            <h4>WWW.NONAME4YOU.com, Copyright 2023</h4>
        </div>

    </footer>

















    * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
body {
    font-family: sans-serif;
}

header{
    width: 100vw;
}

header .header_text{
    text-align: center;
    padding: 100px;
    color: white;
    font-size: xx-large;
}

header{
    width: 100vw;
    height: 50vh; 
    background-image: url("../images/pic001.png"); 
    background-repeat: no-repeat, no-repeat; 
    background-size: cover;
}

  
  a {
    text-decoration: none;
    color: white;
    font-size: 1.2rem;
    font-weight: bold;
    text-transform: uppercase;
  }


  /* nav  */

.nav {
    overflow: hidden;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 20px;
  }

  
li{list-style: none; display: inline;}

  .logo {
    font-size: 1.5rem;
    color: rgb(233, 233, 242);
    padding-left: 20px;
  }

  .logo span{
    font-size: 2rem;
    color: rgb(201, 201, 220);
  } 

  
  .hamburger {
    padding-right: 20px;
    cursor: pointer;
  }
  
  .hamburger .line {
    display: block;
    width: 40px;
    height: 5px;
    margin-bottom: 10px;
    background-color: rgb(252, 248, 248);
  }
  
  .nav__link {
    position: fixed;
    width: 94%;
    top: 5rem;
    left: 18px;
    background-color: rgb(150, 153, 153);
    padding: 20px;
  }
  
  .nav__link a {
    display: block;
    text-align: center;
    padding: 10px 0;
  }
  
  .nav__link a:hover {
    background-color: rgb(251, 246, 246);
    color: rgb(53, 55, 55);
  }
  
  .hide {
    display: none;
  }



/* Drop Down */  

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.nav a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.dropdown:hover .dropdown-content {
  display: block;
}



/* Desktop */
  @media screen and (min-width: 600px) {
    .nav__link {
      display: block;
      position: static;
      width: auto;
      margin-right: 20px;
      background: none;
    }
  
    .nav__link a {
      display: inline-block;
      padding: 15px 20px;
    }
  
    .hamburger {
      display: none;
    }
  }

  * {
    box-sizing: border-box;
}

/* Create four equal columns that floats next to each other */
.column {
    float: left;
    width: 25%;
    padding: 10px;
    height: 300px; /* Should be removed. Only for demonstration */
}

.column h2{text-align: center;}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Footer Style */
footer .copyright{width: 100vw; text-align: center;}

#footer {
    position: fixed;
    bottom: 0;
    width: 100%;
    height: 400px; /* Height of the footer */
    background: #6cf;
}

.fa-facebook {
    background: #3B5998;
    color: white;
    height: 50px;
    width: 50px;
    padding: 20px;
}

.fa-instagram {
    background: #3B5998;
    color: white;
    height: 50px;
    width: 50px;
    padding: 20px;
}


/* Responsive layout - makes the four columns stack on top of each other instead of next to each other */