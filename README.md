#HTML CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify-Web Player:Music for Everyone</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="./assests/logo.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">

</head>
<body>
    <div class="main">
        <div class="sidebar">
            <div class="nav">
                <div class="nav-options" style="opacity:1">
                    <i class="fa-solid fa-house"></i>
                    <a href="#">Home</a>
                </div>
                <div class="nav-options">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <a href="#">Search</a>
                </div>
                </div>
                <div class="library">
                    <div class="options">
                        <div class="lib-options  ">
                    <img src="./assests/library_icon.png" alt="Library">
                    <a href="#">Your library</a>
                </div>
                <div class="icons  nav-options ">
                    <i class="fa-solid fa-plus"></i>
                   <i class="fa-solid fa-arrow-right"></i>
                </div>
                

                    </div>
                    <div class="lib-box">
                       <div class="box">
                       <div class="box-p1">Create your first Playlist</div> 
                       <div class="box-p2">It's easy, we'll help you</div>
                       <button class="badge">Create Playlist</button>
                       </div>
                       <div class="box">
                       <div class="box-p1">Let's find some Podcasts to follow</div> 
                       <div class="box-p2">We'll keep you updated on new episodes</div>
                       <button class="badge">Browse Poadcasts</button>
                       </div>

                    </div>

                </div>
            </div>
        <div class="maincontent">
           <div class="sticky-nav">
            <div class="sticky-nav-icons">
                 <img src="./assests/backward_icon.png" alt="Backward Icon">
            <img src="./assests/forward_icon.png" class="hide" alt="Forward Icon">

            </div>
           <div class="sticky-nav-options">
            <button class="badge dark-badge hide" >Explore Premium</button>
            <button class="badge dark-badge" style="margin-left:8px;"><i class="fa-solid fa-circle-down"></i> Install App</button>
            <button class="badge">Log in/sign-up</button>


           </div>
            
           </div>
           
            <h2>Recently Played</h2>
            <div class="cards-container"></div>
            <div class="card">
              <img src="./assests/card1img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Top 50-Global</p>
              <p class="card-Info">Your daily updates of most playing...</p>
             </div>
             <h2>Trending Songs</h2>
            <div class="cards-container">
            <div class="card">
              <img src="./assests/card2img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Maiye jinna sohna</p>
              <p class="card-Info">By A.R Rahman</p>
              </div>
               <div class="card">
              <img src="./assests/card3img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Mere paas tum ho</p>
              <p class="card-Info">Lofi mix-Mini Music</p>
              </div>
               <div class="card">
              <img src="./assests/card4img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Badass-Leo</p>
              <p class="card-Info">Mixture of Hindi+English</p>
              </div>
               <div class="card">
              <img src="./assests/card5img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Top Songs Global</p>
              <p class="card-Info">Most trending songs track...</p>
              </div>
              <div class="card">
              <img src="./assests/card7img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">Chandani</p>
              <p class="card-Info">Inner feeling song...</p>
              </div>
              <div class="card">
              <img src="./assests/card8img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">Ladki kyon</p>
              <p class="card-Info">Hum Tum</p>
              </div>
              <div class="card">
              <img src="./assests/card9img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">Tagdi-2</p>
              <p class="card-Info">Haryanvi songs</p>
              </div>
              <div class="card">
              <img src="./assests/card10img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">Lal Pari</p>
              <p class="card-Info">Housefull-5</p>
              </div>
              </div>
              
              <h2>Popular Artists</h2>
              <div class="artists">
              <div class="card">
              <img src="./assests/card11img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">A.R Rahman</p>
              <p class="card-Info">Famous singer</p>
              </div>
              <div class="card">
              <img src="./assests/card12img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Alka Yagnik</p>
              <p class="card-Info"> 90's famous Singer</p>
              </div>
              <div class="card">
              <img src="./assests/card13img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">Guru Randhawa</p>
              <p class="card-Info">21's famous Singer</p>
              </div>
              <div class="card">
              <img src="./assests/card14img.jpg" class="card-img" alt="Card 1">
              <p class="card-title">Arjit Singh</p>
              <p class="card-Info">famous Singer</p>
              </div>
              <div class="card">
              <img src="./assests/card15img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Shreya Ghoshal</p>
              <p class="card-Info">Singer</p>
              </div>
                </div>
                <h2>Featured charts</h2>
                <div class="card-8">
            <div class="cards-container">
            <div class="card">
              <img src="./assests/card1img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Top 50-Global</p>
              <p class="card-Info">Your daily updates of most playing...</p>
             </div>
            <div class="cards-container">
            <div class="card">
              <img src="./assests/card6img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Top Songs India</p>
              <p class="card-Info">Weekly Music Chart...</p>
             </div>
             <div class="cards-container">
            <div class="card">
              <img src="./assests/card5img.jpeg" class="card-img" alt="Card 1">
              <p class="card-title">Top Songs Global</p>
              <p class="card-Info">Weekly Music Charts...</p>
             </div>
             </div>
             
             </div>

                     

               <footer class="footer">
                
  <div class="footer-col">
    
    <h4>Company</h4>
    <ul>
      <li>About</li>
      <li>Jobs</li>
      <li>For the Record</li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Communities</h4>
    <ul>
      <li>For Artists</li>
      <li>Developers</li>
      <li>Advertising</li>
      <li>Investors</li>
      <li>Vendors</li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Useful links</h4>
    <ul>
      <li>Support</li>
      <li>Free Mobile App</li>
      <li>Popular by Country</li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Spotify Plans</h4>
    <ul>
      <li>Premium Individual</li>
      <li>Premium Duo</li>
      <li>Premium Family</li>
      <li>Premium Student</li>
      <li>Spotify Free</li>
    </ul>
    
  </div>
  <div class="icons-3">
    <i class="fa-brands fa-instagram"></i>
    <i class="fa-brands fa-x-twitter"></i>
    <i class="fa-brands fa-facebook"></i>
  </div>
</footer>
</div>
<h5><i class="fa-brands fa-spotify"></i> 2025 Spotify AB</h5>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br> 
    <div class="musicplayer">
      <div class="album">
        <img src="./assests/card21img.jpeg"alt="Album Cover" class="album-cover">
        <div class="album-info">
          <p class="album-title">2 khatola</p>
        <p class="album-artist">Masoom Sharma</p>
        </div>
      </div>
      <div class="player">
        <div class="player-control">
          <img src="./assests/player_icon1.png" class="player-control-icon">
          <img src="./assests/player_icon2.png" class="player-control-icon">
          <img src="./assests/player_icon3.png" class="player-control-icon" style="opacity:1;height:2rem">
          <img src="./assests/player_icon4.png" class="player-control-icon">
          <img src="./assests/player_icon5.png" class="player-control-icon">
        </div>
        <div class="playback-bar">
          <span class="current-time">0:00</span>
          <input type="range" class="progress-bar" value="0" min="0" max="100" step="1">
          <span class="total-time">5:50</span>
        </div>
      </div>
      <div class="controls">
    <i class="fa-regular fa-display active"></i>
    <i class="fa-solid fa-magnifying-glass"></i>
    <i class="fa-solid fa-bars"></i>
    <i class="fa-regular fa-rectangle-list"></i>
    <i class="fa-solid fa-volume-low"></i>
    <input type="range" class="volume-bar" min="0" max="100" value="50">
    <i class="fa-regular fa-desktop"></i>
    <i class="fa-regular fa-up-right-and-down-left-from-center"></i>
</div>
      </div>
    </div>
    </div>


</body>
</html>




#CSS code
body{
    background-color: black;
   font-family: "Montserrat", sans-serif;
     font-weight:600;
     font-style: normal;
     overflow:hidden;
     color: #fff;
}
    


.main{
    
   display: flex;
    height:100vh;
    padding:0.5rem;

}
.sidebar{
   width:340px; 
   border-radius: 1rem;
   background-color:#000;
   margin-right:0.5rem;
   /* Removed border-right for better divider control */
}

.divider {
    width: 2px;
    background: #232323;
    border-radius: 1rem;
    margin: 0 0.5rem;
    /* Make divider fill the sidebar height */
}

.maincontent{
    flex:1;
    /*background-color: red;*/
    border-radius: 1rem;
    overflow-y: auto;
     background-color:#121212;
     height:100vh;
     
     padding:0 1.5rem 0 1.5rem;
    scrollbar-width: thin;
    scrollbar-color: #232323 #121212;
  
  
}



    a{
        text-decoration: none;
        color:#fff
    }

    .nav{
       background-color: #121212;
       line-height: 2.5rem;
       border-radius:1rem;
       padding: 0.5rem 0.75rem 0.5rem 0.75rem;
       display:flex;
       flex-direction: column;
       justify-content:center;
       height:6.25rem;

    }
    .nav-options{
      line-height:2.5rem;
      opacity:0.75;
      padding:0.5rem 0.75rem;
      
     
      
    }

    .nav-options:hover{
      line-height:2.5rem;
      opacity:1;
      
    }
    .nav-options i{
        font-size:1.25rem;
    }

    .nav-options a{
        font-size: 1rem;
         margin-left:1rem;

    }
    .lib-options img{
        height:1.25rem;
        width:1.25rem;
    }

    .library{
        border-radius:1rem;
        background-color: #121212;
        height:100vh;
        display: flex;
        margin-top: 0.5rem;
        /*width: 100%; *//* Ensure it stretches fully */
        padding:0.5rem 0.75rem 0.5rem 0.75rem;
        flex-direction: column;;
        
       
    }

    

    .options{
        display: flex;
        justify-content: space-between;
        align-items: center; /* Vertically center children */
        width: 100%; /* Ensure it stretches fully */
        opacity:0.5;
        height:2.5rem
    }
      .options:hover{
        opacity:1
    }


    .icons{
       display: flex;
        cursor:pointer;
    }
       .icons i:hover{
        opacity: 1;
    }
     .icons i{
       opacity:0.75;
       margin-right:1rem;
       width:100%;
    }

    .box{
        
        height:8rem;
         /*width: 100%; */ /* Make box width responsive to sidebar */
        background-color:#232323;
        border-radius:1rem;
        margin: 1rem auto; /* Center horizontally and add more vertical space */
        padding:1rem 1.25rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .box-p1{
        font-size: 1rem;
        font-weight: 600;
        margin:0.25rem;
        
    }

    .box-p2{
        font-size: 0.85rem;
        opacity: 0.75;
        margin:1rem ;

    }


    .badge{
       background-color: #fff;
       border-radius: 6.25rem;
       padding:0.25rem 1rem;
       border:none;
       font-weight:500;
       margin:0.5rem;
       height:2rem;
       width:fit-content;
       cursor:pointer;

    }

    .dark-badge{
        
        color: #fff;
        background-color: #000;
    }

    .sticky-nav{
    position: sticky;
    top:0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0 1rem 0;

    }


    .sticky-nav-icons img{
       
        height:1.25rem;
        width:1.25rem;
    }

    .sticky-nav-icons{
        margin:0.75rem;
    }

    .sticky-nav-options buttons{
        display: flex;
        align-items: center;
        justify-content: center;
        margin-right:2rem;
    }

    @media(max-width:860px){
        .hide{
            display:none;
        }

        }

        .card{
            background-color: #232323;
            width:9.37rem;
              border-radius:0.5rem;
              padding:1.25rem;
              margin-left:1rem;
              margin-top:0.75rem;
        }

        .cards-container{
            display:flex;
            flex-wrap: wrap;
        }

        .card-img{
            width:100%;
             border-radius:0.5rem;
            
            
        }

        
            
        

        .card-title{
            font-weight: 500;
        }

        .card-Info{
            font-size:0.85;
            opacity:0.7;
        }

        .artists{
            display:flex;
        }

        .footer {
  display: flex;
  justify-content: space-around;
  background: #181818;
  color: #fff;
  padding: 1rem 0;
  font-family: "Montserrat", sans-serif;
  padding-left: 1.5rem;
  margin-top:1.75rem;
}
.footer-col {
  min-width:11.25rem;
}
.footer-col h4 {
  font-size: 1rem;
  font-weight: 300;
  margin-bottom: 2rem;
}
.footer-col ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
.footer-col li {
  margin-bottom: 0.75rem;
  font-size: 0.85rem;
  font-weight: 200;
  color: #ccc;
}

.icons-3 {
    display: flex;
    justify-content: flex-end; /* Align icons to the right */
    align-items: center;
    column-gap: 2rem; /* More space between icons */
    padding: 1rem 2rem 1rem 0; /* Add right padding for spacing from edge */
}
.icons-3 i {
    font-size: 1rem;
    color: #fff;
    background: #232323;
    border-radius: 50%;
    padding: 0.5rem;
    
    margin-right: 1.5rem; /* Add margin between icons */
}
.icons-3 i:last-child {
    margin-right: 0; /* Remove margin from last icon */
}
.icons-3 i:hover {
    background:#121212;;
    color: #fff;
    opacity:1;
}

h5{
    opacity:0.75;
    margin-left:1rem;
    padding:1.5rem;
}

/* For Chrome, Edge, and Safari */
.maincontent::-webkit-scrollbar {
    width: 8px;
    background: #121212;
}
.maincontent::-webkit-scrollbar-thumb {
    background: #232323;
    border-radius: 4px;
}
.maincontent::-webkit-scrollbar-track {
    background: #121212;
}

.musicplayer {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100vw; /* Full viewport width */
    height: 3.5rem;
    background-color: #181818;
    border-top: 1px solid #232323;
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: #fff;
    font-size: 1rem;

    }


.player-control{
   display: flex;
    align-items: center;
 justify-content:center;
}


.album{
     width:25%;
}

.player{
         width:50%;
}

.controls{
 width:25%;
 display: flex;
   
    gap: 1rem;
    padding: 0.2rem;
    height: 100%;
    background: transparent;
}

.player-control-icon{
    height:1rem;
    cursor:pointer;
    margin-right:1.5rem;
    opacity:0.75;

}

    
.player-control-icon:hover{
    opacity:1;
}


.playback-bar{
    display:flex;
     align-items: center;
    justify-content:center;
}

.progress-bar{
    width:70%;
    appearance:none;
    cursor:pointer;
    background-color:transparent;
   
    
}


.progress-bar::-webkit-slider-runnable-track{
    background-color: #ddd;
    border-radius: 110px;
    height:0.3rem;
}

.progress-bar::-webkit-slider-thumb{
    appearance:none;
    height:1rem;
    width:1rem;
    background-color: green;
    border-radius: 50%;
    margin-top:-6px;    
}


.album {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.album-cover {
    width: 56px;
    height: 56px;
    border-radius: 8px;
    object-fit: cover;
}

.album-info {
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.album-title {
    font-size: 1.1rem;
    font-weight: 600;
    color: #fff;
    margin-bottom: 0.2rem;
    
}

.album-artist {
    font-size: 0.95rem;
    color: #b3b3b3;
    margin-top:0;
    line-height: 1.1;

}

/* Controls bar styling */
.controls {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    padding: 0 2rem;
    height: 100%;
    background: transparent;
}

/* Icon styling */
.controls i {
    font-size: 1.5rem;
    color: #fff;
    opacity: 0.85;
    cursor: pointer;
    transition: color 0.2s, opacity 0.2s;
}

.controls i.active,
.controls i:hover {
    color: #1db954;
    opacity: 1;
}

/* First icon green with dot below */
.controls i:first-child {
    color: #1db954;
    position: relative;
}

.controls i:first-child::after {
    content: '';
    display: block;
    width: 6px;
    height: 6px;
    background: #1db954;
    border-radius: 50%;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    bottom: -10px;
}

/* Volume bar styling */
.controls .volume-bar {
    width: 100px;
    height: 6px;
    border-radius: 3px;
    background: linear-gradient(to right, #1db954 50%, #fff 50%);
    appearance: none;
    outline: none;
    margin:  0.5rem;
}

/* Green thumb for volume bar */
.controls .volume-bar::-webkit-slider-thumb {
    appearance: none;
    width: 18px;
    height: 18px;
    background: #fff;
    border: 3px solid #1db954;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 0 0 4px rgba(29,185,84,0.2); /* soft green glow */
    transition: box-shadow 0.2s;
}

.controls .volume-bar:focus::-webkit-slider-thumb,
.controls .volume-bar:hover::-webkit-slider-thumb {
    box-shadow: 0 0 0 6px rgba(29,185,84,0.3);
}

.controls .volume-bar::-moz-range-thumb {
    width: 18px;
    height: 18px;
    background: #fff;
    border: 3px solid #1db954;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 0 0 4px rgba(29,185,84,0.2);
    transition: box-shadow 0.2s;
}

.controls .volume-bar:focus::-moz-range-thumb,
.controls .volume-bar:hover::-moz-range-thumb {
    box-shadow: 0 0 0 6px rgba(29,185,84,0.3);
}

.controls .volume-bar::-ms-thumb {
    width: 18px;
    height: 18px;
    background: #fff;
    border: 3px solid #1db954;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 0 0 4px rgba(29,185,84,0.2);
    transition: box-shadow 0.2s;
}

.controls .volume-bar:focus::-ms-thumb,
.controls .volume-bar:hover::-ms-thumb {
    box-shadow: 0 0 0 6px rgba(29,185,84,0.3);
}
















