<html>
  <head>
    <style type="text/css">
    *{
    margin:0;
    padding:0;
    box-sizing:border-box;
    }
    .cl{
    height:auto;
    width:100%;
    background:linear-gradient(to top left,black,grey);
    }
    .container{
    height:100%;
    display:flex;
    justify-content:center;
    align-items:center;
    }
    .card{
    width:80%;
    height:auto;
    border-radius:10px;
    }
    img{
    width:100%;
    height:auto;
    object-fit:cover;
    border-radius:10px;
    }
    .child{
    width:100%;
    height:auto;
    padding:10px;
    background:white;
    }
    .p-i,.p-ii,h3{
    text-align:center;
    }
    .p-ii{
    margin-top:2.5rem;
    text-align:justify;
    text-align-last:center;
    }
    .p-i{
     color:red;
     font-size:18px;
    }
    h3{
    font-size:28px;
    }
    .child-ii{
    width:100%;
    height:auto;
    background:grey;
    display:flex;
    justify-content:space-between;
    border-radius:100px;
    }
    .item{
    width:33%;
    height:auto;
    background:red;
    padding:10px;
    }
    h5,.a{
    text-align:center;
    }
    .i{
    border-radius:0 0 0 10px;
    }
    .iii{
    border-radius:0 0 10px 0;
    }
    p::selection{
    color:aqua;
    background:yellow;
    }
    h3{
    position:relative;
    }
    h3::after{
    content:"";
    display:block;
    height:15px;
    width:15px;
    background:white;
    position:absolute;
    right:50%;
    top:3.2rem;
    border:1px solid grey;
    border-radius:50% 50% 10px 10px;
    transition:all 0.8s ease-out;
    }
    h3:hover::after{
    background:red;
    transform:scale(1.5) translate(0,-4px);
    box-shadow:0 0 2px 1px red;
    }
    .cl-ii{
    width:100%;
    height:auto;
    background:linear-gradient(to top right,blue,white,pink);
    padding:10px;
    display:flex;
    flex-flow:row wrap;
    
    }
    .qu{
    flex:100%;
    }
    a,h4{
    text-decoration:none;
    text-align:center;
    display:block;
    color:black;
    margin:1rem 0;
    cursor:progress;
    }
    a:hover{
    color:red;
    text-decoration:underline black;
    }
    .header{
    height:100%;
    background:url(images/newyork.jpg) no-repeat center center;
    background-size:100% 100%;
    }
    .navbar{
    height:auto;
    width:100%; 
    display:flex;
    justify-content:space-around;
    background:black;
    border-radius:25px;
    }
    .navbar a{
    text-decoration:none;
    display:inline-block;
    color:white;
    position:relative;
    }
    .navbar a:hover{
    color:red;
    }
    .navbar a::after{
    content:"";
    display:block;
    width:0;
    height:2px;
    background:cyan;
    position:absolute;
    bottom:0; 
    left:50%;
    transition:width 0.5s ease-out,
               left 0.5s ease-out
               ;      
    } 
    .navbar a:hover::after{
    width:100%;
    left:0;
    }
    .section{
    width:100%;
    height:auto;
    }
    .h3-s{
    text-align:center;
    margin:50% 0 0 0;
    }
    .p-s{
    text-align:center;
    margin:1rem 0 0 0;
    color:white;
    }
    .m-s{
    width:100%;
    height:auto;
    padding:1rem;
    }
    .m-s-i{
    width:80%;
    height:auto;
    margin:0 auto;
    }
    .m-s-i img{
    border-radius:0;
    }
    </style>
  </head>
  <body>
  <div class="header">
    <div class="navbar">
      <a href="#" >HOME</a>
      <a href="#" >VIDEO</a>
      <a href="#" >INFO</a>
      <a href="#" >ABOUT</a>
    </div>
    <div class="section">
      <h4 class="h3-s">OUR SPECIAL OFFER</h4>
      <p class="p-s">ON 23rd JUNE WE ARE GIVING A SPECIAL OFFER AND THE OFFER IS A
      SURPRISE , IT WILL BE ANNOUNCED LATER</p>
    </div>
  </div>
  <div class="m-s">
    <div class="m-s-i">
      <img src="images/green.jpg" alt="IPHONE image">
    </div>
  </div>
  <div class="cl">
    <div class="container">
      <div class="card">
        <img src="images/lo.jpg" alt="dekstop image" class="card-i">
        <div class="child">
          <p class="p-i">4 DAY AGO</p>
          <h3>post one</h3>
          <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
           background office of mumbai is an excellent resource that has a great. </p>
        </div>
        <div class="child-ii">
          <div class="i item">
          <h5>4m</h5>
          <p class="a">READ</p>
          </div>
          <div class="ii item">
          <h5>5122</h5>
          <p class="a">VIEWS</p>
          </div>
          <div class="iii item">
          <h5>32</h5>
          <p class="a">COMMENT</p>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
    <div class="card">
    <img src="images/o.jpg" alt="dekstop image" class="card-i">
    <div class="child">
    <p class="p-i">4 DAY AGO</p>
    <h3>post one</h3>
    <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
    background office of mumbai is an excellent resource that has a great. </p>
    </div>
    <div class="child-ii">
    <div class="i item">
    <h5>4m</h5>
    <p class="a">READ</p>
    </div>
    <div class="ii item">
    <h5>5122</h5>
    <p class="a">VIEWS</p>
    </div>
    <div class="iii item">
    <h5>32</h5>
    <p class="a">COMMENT</p>
    </div>
    </div>
    </div>
    </div>
    <div class="container">
    <div class="card">
    <img src="images/qp.jpg" alt="dekstop image" class="card-i">
    <div class="child">
    <p class="p-i">4 DAY AGO</p>
    <h3>post one</h3>
    <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
    background office of mumbai is an excellent resource that has a great. </p>
    </div>
    <div class="child-ii">
    <div class="i item">
    <h5>4m</h5>
    <p class="a">READ</p>
    </div>
    <div class="ii item">
    <h5>5122</h5>
    <p class="a">VIEWS</p>
    </div>
    <div class="iii item">
    <h5>32</h5>
    <p class="a">COMMENT</p>
    </div>
    </div>
    </div>
    </div>
    <div class="container">
    <div class="card">
    <img src="images/curry.jpg" alt="dekstop image" class="card-i">
    <div class="child">
    <p class="p-i">4 DAY AGO</p>
    <h3>post one</h3>
    <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
    background office of mumbai is an excellent resource that has a great. </p>
    </div>
    <div class="child-ii">
    <div class="i item">
    <h5>4m</h5>
    <p class="a">READ</p>
    </div>
    <div class="ii item">
    <h5>5122</h5>
    <p class="a">VIEWS</p>
    </div>
    <div class="iii item">
    <h5>32</h5>
    <p class="a">COMMENT</p>
    </div>
    </div>
    </div>
    </div>
    <div class="container">
    <div class="card">
    <img src="images/mountain.jpg" alt="dekstop image" class="card-i">
    <div class="child">
    <p class="p-i">4 DAY AGO</p>
    <h3>post one</h3>
    <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
    background office of mumbai is an excellent resource that has a great. </p>
    </div>
    <div class="child-ii">
    <div class="i item">
    <h5>4m</h5>
    <p class="a">READ</p>
    </div>
    <div class="ii item">
    <h5>5122</h5>
    <p class="a">VIEWS</p>
    </div>
    <div class="iii item">
    <h5>32</h5>
    <p class="a">COMMENT</p>
    </div>
    </div>
    </div>
    </div>
    <div class="container">
    <div class="card">
    <img src="images/city.jpg" alt="dekstop image" class="card-i">
    <div class="child">
    <p class="p-i">4 DAY AGO</p>
    <h3>post one</h3>
    <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
    background office of mumbai is an excellent resource that has a great. </p>
    </div>
    <div class="child-ii">
    <div class="i item">
    <h5>4m</h5>
    <p class="a">READ</p>
    </div>
    <div class="ii item">
    <h5>5122</h5>
    <p class="a">VIEWS</p>
    </div>
    <div class="iii item">
    <h5>32</h5>
    <p class="a">COMMENT</p>
    </div>
    </div>
    </div>
    </div>
    <div class="container">
    <div class="card">
    <img src="images/singapore.jpg" alt="dekstop image" class="card-i">
    <div class="child">
    <p class="p-i">4 DAY AGO</p>
    <h3>post one</h3>
    <p class="p-ii">This is a official accountant from India i have to wake your child di&nbsp;and the yes Intellectualism has
    background office of mumbai is an excellent resource that has a great. </p>
    </div>
    <div class="child-ii">
    <div class="i item">
    <h5>4m</h5>
    <p class="a">READ</p>
    </div>
    <div class="ii item">
    <h5>5122</h5>
    <p class="a">VIEWS</p>
    </div>
    <div class="iii item">
    <h5>32</h5>
    <p class="a">COMMENT</p>
    </div>
    </div>
    </div>
    </div>
  </div>
  <div class="cl-ii">
    <div class="social qu">
      <h4>SOCIAL ACCOUNTS</h4>
      <a href="#" >TWITTER</a>
      <a href="#" >YOUTUBE</a>
      <a href="#" >FACEBOOK</a>
      <a href="#" >KOO</a>
      <a href="#" >INSTAGRAM</a>
    </div>
    <div class="page qu">
      <h4>OWN PAGE</h4>
      <a href="#" >HOME</a>
      <a href="#" >VIDEO</a>
      <a href="#" >BLOG</a>
      <a href="#" >INFO</a>
      <a href="#" >SECTION</a>
    </div>
    <div class="links qu">
      <h4>INFLUENCE</h4>
      <a href="#" >OUR APP</a>
      <a href="#" >META</a>
      <a href="#" >SET UP</a>
      <a href="#" >LAPS</a>
    </div>
  </div>
  </body>
</html>
