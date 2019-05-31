<html>
    <style>
    body {
        font-family: arial, Helvetica, sans-serif;
    }
    .navbar {
        overflow: hidden;
        background-color: #333;
    }
    .navbar a {
        float:left;
        font-size:16px;
        color:white;
        text-align:center;
        padding:14px 16px;
        text-decoration:none;
    }
    .dropdown {
        float:right;
        overflow:hidden;
    }
    
    .dropdown .dropbtn {
        font-size:16px;
        border:none;
        outline:none;
        color:white;
        padding:14px 16px;
        background-color:inherit;
        font-family:inherit;
        margin:0;
        
    }
    .dropdown:hover
    .dropbtn{
        background-color:#90afff;
    }
    .navbar a:hover{
        background-color: #ff7d74;
    }
    
    .dropdown-content{
        display:none;
        position:absolute;
        background-color:#f9f9f9;
        min-width: 160px;
        box-shadow:0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index:1;
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
         background-color:#90afff;
         
    }

    .dropdown:hover .dropdown-content {
        display: block;
    }
    .head{
        font-size:20px;
        color:#90afff;
        text-shadow:2px 2px 4px #000000;
    }
    .backgroundimage{
        background:url(https://images.fineartamerica.com/images-medium-large-5/the-distance-abstract-art-by-laura-gomez-horizontal-long-strip-format-laura-and-karina-gomez.jpg)center;
        background-repeat:no-repeat;
    }
    .transbox{
        margin:30px;
        background-color:#ffffff;
        border:1px solid black;
        opacity:0.6;
        filter:alpha(opacity=60);
    }
    div.transbox p {
        margin: 5%;
        font-weight: bold;
    }
    .backgroundimage2{
        background-image:url(https://www.bing.com/th?id=OIP.i6WQ6gnVprzg5UG3QouNxAAAAA&pid=Api&rs=1&p=0);
        border:2px solid black;
    }
    .footer {
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: #333;
        color: white;
    }
    .padding{
        padding: 12px 16px;
    }
    </style>
    <div class="backgroundimage2">
    <body>
    <!--this is the start of the navbar-->
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#news">Interesting</a>
        <div class="dropdown">
            <button class="dropbtn">Projects   
                <i class="fa fa-caret-down"></i>
            </button>
            
            <div class="dropdown-content" id="myDropdown">
                <a href="https://getongethub.github.io/yes/">Explorer<br>Project</a>
                <a href="#">Working<br>on it</a>
                <a href="#">classwork</a>
            </div>
        </div>
    </div>
    <div class="head">
    <center><h2>welcome to my website</h2></center>
    </div>
    <div class="backgroundimage">
        <div class="transbox">
            <p>
               Hello and welcome, <br>My name is Jonathan,this is my website presenting 
               a multitude of options. one being the drop down button which is labeled "Projects" there you can find classwork that i have done and Project that i am working on or going to work on.After you read all of this you can see a few videos
               underneath they are some of my favorite songs to listen to.
            </p>
        </div>
    </div>    
    </div>
    
    <div class="padding">
    <iframe width="250" height="200" align="right" src="https://www.youtube.com/embed/lAIGb1lfpBw" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen >
    </iframe> 
    <iframe width="250" height="200" src="https://www.youtube.com/embed/5ChvaSe6aK0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen align="right"></iframe>
    <iframe width="250" height="200" src="https://www.youtube.com/embed/3SDBTVcBUVs" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen align="right"></iframe>
    </div>
   
  
    <!--this is the end of the body-->
    </body>

    <div class="footer">
        <div class="padding">
            <p text-align="right, center">this will be more info</p>
    </div>
    </div>
     
</html>
