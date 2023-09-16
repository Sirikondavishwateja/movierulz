# movierulz
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>movierulz</title>
    <link rel="stylesheet" href="../node_modules/bootstrap-icons/font/bootstrap-icons.css">
    <style>
        body{
            background-size: cover;
            width:1000px;
            margin:30px auto ;
        }
       .head1{
            display: flex;
            justify-content: space-between;
            color: white;
       }
       .h1{
            font-size: 40px;
       }
        .head-nav{
            background-color: black;
            color: rgb(249, 243, 243);
            text-align: center;
            margin-top: 10px;
            border-radius: 5px;
        }
        .head-nav1{
            background-color: rgb(186, 174, 174);
            color: rgb(10, 10, 10);
            text-align: center;
            margin-top: 10px;
            padding: 15px;
            border: 8px;
            border-style: double;
            border-top-color: rgb(98, 98, 208);
            border-bottom-color: rgb(222, 89, 89);
            border-left-color: rgb(13, 164, 121);
            border-right-color: rgb(239, 86, 216);
            border-radius: 5px;
        }
        .search{
            margin-top: 15px;
            margin-right: 20px;
        }
        input{
            padding: 5px;
            padding-left: 10px;
            border-radius: 5px;
            border: none;
        }
        button{
            padding: 5px;
            margin-left: 2px;
            border-radius: 5px;
            border: none;
        }
        #bt{
            background-color: black;
            color: white;
            border: none;
            padding: 15px;
            cursor: pointer;
        }
        .button1{
          height: 20px;
          margin-top: 10px;
          padding:10px;
          text-align: center;
        }
        #bt1{
            background-color: rgba(25, 22, 22, 0.821);
            color: white;
            margin-right: 7px;
            padding: 7px 15px 7px 15px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
        .container{
            width: 1000px;
            /* background-color: rgba(50, 49, 49, 0.759); */
            color: white;
            margin-top: 20px;
            display: grid;
            grid-template-columns: 9fr 3fr;
        }
        .c1{
            display: flex;
            width: 710px;
            font-size: 15px;
            font-weight: bold;
            background-color: rgb(10, 10, 10); 
            color: brown;
            justify-content: space-between;
            padding-left: 15px;
            padding-right: 15px;
           border: none;
           border-radius: 5px;
        }
        .c2{
            width: 720px;
             display: flex;
             justify-content: space-between;
        }
        .card{
             position: relative; 
             background-color: rgb(22, 21, 21);
            width: 160px;
            height: 300px;
            border-radius: 5px;
            margin-top: 20px;
             margin-left: 15px;
             margin-right: -22px;
             margin-bottom: 10px;
        }
        .card-img{
            width: 100%;
            border-radius: 5px 5px 0px 0px;   
        }
        .card-p{
             margin-top: -1px; 
             padding-left:5px;
        }
        .lang{
            width: 45px;
            background-color: blueviolet;
            padding: 2px;
            border-radius: 7px;
            border: none;
            margin: 3px 0px 0px 3px;
            position: absolute;
             left: 0;
             top: 0;
        }
        .left{
            width:750px;
            background-color: rgba(33, 31, 31, 0.762);
        }
        .right{           
            margin-left: 20px;
            width: 230px;
            border-radius: 10px;   
        }
        .Genres1{
            background-color: black;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        .Genres2{
            background-color: black;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        .Genres1 div{
            border-radius: 10px 10px 0px 0px;
          text-align: center;
          padding: 5px;
          font-size: 15px;
          background-color: rgb(36, 34, 34);
          border-bottom: 1px solid rgb(34, 33, 33); 
          color: rgba(255, 217, 0, 0.911);   
        }
        .Genres2 div{
            border-radius: 10px 10px 0px 0px;
          text-align: center;
          padding: 5px;
          font-size: 15px;
          background-color: rgb(36, 34, 34);
          border-bottom: 1px solid rgb(34, 33, 33); 
          color: rgba(255, 217, 0, 0.911); 
        }
        #a1{
            margin-top: 7px;
            margin-right: 2px;
            margin-bottom: 2px;
            background-color: blueviolet;
            font-weight: bold;
        }
        .container-1{
            margin-top: 50px;
            text-align: center; 
            color: blanchedalmond;  
        }
        .container1{
            margin-bottom: 15px;
            font-size: 25px;
            text-align: center;
        }
    </style>
</head>
<body background="imeges/bg.webp">
    <header>
        <div class="head1">
            <div class="title">
               <div class="h1"> 4Movierulz</div>
               <p>Watch Telugu Hindi Tamil Punjabi Full Movies Online Free MovieRulz</p>
            </div>
                <div class="search"><input type="search" placeholder="search..."><button>search</button>  </div>
        </div>
        <nav class="head-nav">
            <div>
                <button id="bt">HOME</button>
                <button id="bt">FEATURED</button>
                <button id="bt">TELUGU</button>
                <button id="bt">BOLLYWOOD</button>
                <button id="bt">TAMIL</button>
                <button id="bt">MALAYALAM</button>
                <button id="bt">KANNADA</button>
                <button id="bt">DUBBED</button>
                <button id="bt">OTHERS</button>
                <button id="bt">QUALITY</button>
             </div>
        </nav>
    </header>
    <article class="head-nav1">"Don't Search Us on Google, Save Our Website URL &nbsp;&nbsp;<b>4MovieRulz.live</b>&nbsp; &nbsp;url"</article>
    <div class="button1">
        <button id="bt1"> Movierulz App</button>
        <button id="bt1">Requsted</button>
        <button id="bt1">Multi audio </button>
        <button id="bt1">Adult 18+</button>
    </div>
    <main class="container" >
          <div class="left">
            <div class="c1">
                <p>Trending</p>
                <p>More...</p>
         </div>
         <div class="c2">
            <div class="card">
                   <img src="imeges/adipurush.jpeg" class="card-img">
                    <p class="card-p">Adipurush (2023) HDRip Telugu Movie Watch Online</p>
                    <span class="lang">Telugu</span>
            </div>
            <div class="card">
                  <img src="imeges/baby.jpeg" class="card-img">
                  <p class="card-p">Baby (2023) HDRip Telugu Movie Watch Online</p>
                  <span class="lang">Telugu</span>
           </div>
           <div class="card">
                  <img src="imeges/bahubali1.jpeg" class="card-img">
                  <p class="card-p"> Bahubali-1 (2023) HDrip Telugu Movie Watch Online</p>
                  <span class="lang">Telugu</span>
           </div>
           <div class="card">                
                  <img src="imeges/Bahubali 2.webp" class="card-img">
                  <p class="card-p">Bahubali-2 (2023) HDRip Telugu Movie Watch Online</p>
                  <span class="lang">Telugu</span>
           </div>
         </div>
         <div class="c2">
           <div class="card">
                  <img src="imeges/bheemla nayak.jpeg" class="card-img">
                   <p class="card-p">Bheemla Nayak (2022) HDRip Telugu Movie Watch Online</p>
                   <span class="lang">Telugu</span>
           </div>
           <div class="card">
                 <img src="imeges/maharshi 2019.jpeg" class="card-img">
                 <p class="card-p">Maharshi (2019) HDRip Telugu Movie</p>
                 <span class="lang">Telugu</span>
          </div>
          <div class="card">
                 <img src="imeges/bharath ane nenu.jpeg" class="card-img">
                 <p class="card-p"> Bharath Ane Nenu (2023) HDrip Telugu Movie Watch Online</p>
                 <span class="lang">Telugu</span>
          </div>
          <div class="card">                
                 <img src="imeges/ps2.jpeg" class="card-img">
                 <p class="card-p">Ps-2(2023) HDRip Telugu Movie Watch Online</p>
                 <span class="lang">Telugu</span>
          </div>
        </div>
        <div class="c2">
           <div class="card">
                  <img src="imeges/ps1.jpeg" class="card-img">
                   <p class="card-p">Ps-1(2022) HDRip Telugu Movie Watch Online</p>
                   <span class="lang">Telugu</span>
           </div>
           <div class="card">
                 <img src="imeges/bro.jpeg" class="card-img">
                 <p class="card-p">Bro (2023) HDRip Telugu Movie Watch Online</p>
                 <span class="lang">Telugu</span>
          </div>
          <div class="card">
                 <img src="imeges/mahaveerudu.jpg" class="card-img">
                 <p class="card-p">Mahaveerudu (2023) Movie Watch Online</p>
                 <span class="lang">Telugu</span>
          </div>
          <div class="card">                
                 <img src="imeges/mem famous.jpeg" class="card-img">
                 <p class="card-p">Mem Famous (2023) HDRip Telugu Movie Watch Online</p>
                 <span class="lang">Telugu</span>
          </div>
        </div>
        <div class="c2">
           <div class="card">
                  <img src="imeges/nayakudu.jpeg" class="card-img">
                   <p class="card-p">Nayakudu (2023) HDRip Telugu Movie Watch Online</p>
                   <span class="lang">Telugu</span>
           </div>
           <div class="card">
                 <img src="imeges/rudrangi.jpeg" class="card-img">
                 <p class="card-p">Rudrangi(2023) HDRip Telugu Movie Watch Online</p>
                 <span class="lang">Telugu</span>
          </div>
          <div class="card">
                 <img src="imeges/hidimba.jpeg" class="card-img">
                 <p class="card-p"> Hidimba (2023) HDrip Telugu Movie </p>
                 <span class="lang">Telugu</span>
          </div>
          <div class="card">                
                 <img src="imeges/spy.jpeg" class="card-img">
                 <p class="card-p">Spy (2023) HDRip Telugu Movie </p>
                 <span class="lang">Telugu</span>
          </div>   
        </div>
        <div class="c1">
            <p>Trending <u>HOLLYWOOD</u> web-series</p>
            <p>More...</p>
        </div>
        <div class="c2">
            <div class="card">
                   <img src="imeges/peaky blinders.jpg" class="card-img">
                    <p class="card-p">Peaky blinders HDRip English web-series Watch Online</p>
                    <span class="lang">English</span>
            </div>
            <div class="card">
                  <img src="imeges/money heist.jpg" class="card-img">
                  <p class="card-p">money Heist HDRip English web-series Watch Online</p>
                  <span class="lang">English</span>
           </div>
           <div class="card">
                  <img src="imeges/got.jpg" class="card-img">
                  <p class="card-p">GOT HDRip english web-series Watch Online</p>
                  <span class="lang">English</span>
           </div>
           <div class="card">                
                  <img src="imeges/breaking bad.jpeg" class="card-img">
                  <p class="card-p">Breaking Bad HDRip web-series Watch Online</p>
                  <span class="lang">English</span>
           </div>
         </div>
         <div class="c1">
            <p>Trending <u>INDIAN</u> web-series</p>
            <p>More...</p>
        </div>
         <div class="c2">
            <div class="card">
                   <img src="imeges/mirzapur.jpg" class="card-img">
                    <p class="card-p">MIRZAPUR HDRip Hindi web-series Watch Online</p>
                    <span class="lang">Hindi</span>
            </div>
            <div class="card">
                  <img src="imeges/guns and gulaabs.jpg" class="card-img">
                  <p class="card-p">Guns And Gulaabs HDRip Hindi web-series Watch Online</p>
                  <span class="lang">Hindi</span>
           </div>
           <div class="card">
                  <img src="imeges/scam1.jpeg" class="card-img">
                  <p class="card-p">Scam 1992 HDRip Hindi web-series Watch Online</p>
                  <span class="lang">Hindi</span>
           </div>
           <div class="card">                
                  <img src="imeges/scam2.jpeg" class="card-img">
                  <p class="card-p">Scam 2003 HDRip Hindi web-series Watch Online</p>
                  <span class="lang">Hindi</span>
           </div>
         </div>   
         </div>
          </div>
         <aside class="right">
            <div class=" Genres1">
                <div >★ Genres</div>
                <button id="a1">Action</button>
                <button id="a1">Adventure</button>
                <button id="a1"> Animation</button>
                <button id="a1">biography</button>
                <button id="a1">Comedy</button>
                <button id="a1">Crime</button>
                <button id="a1"> Documentary</button>
                <button id="a1">Drama</button>
                <button id="a1">Erotic</button>
                <button id="a1">Family</button>
                <button id="a1"> Fantasy</button>
                <button id="a1">Film-noir</button>
                <button id="a1">Games-show</button>
                <button id="a1">History</button>
                <button id="a1"> Horror</button>
                <button id="a1">Music</button>
                <button id="a1">Musical</button>
                <button id="a1">Mystery</button>
                <button id="a1">News</button>
                <button id="a1">Reality-tv</button>
                <button id="a1">Romance</button>
                <button id="a1">Sci-Fi</button>
                <button id="a1">Sports</button>
                <button id="a1">Suspence</button>
                <button id="a1">Action</button>
                <button id="a1">Talk-show</button>
                <button id="a1"> Triller</button>
                <!-- <button id="a1">War</button> -->
            </div>
            <div class=" Genres2">
                <div >★ Genres</div>
                <button id="a1">2023</button>
                <button id="a1">2022</button>
                <button id="a1">2021</button>
                <button id="a1">2020</button>
                <button id="a1">2019</button>
                <button id="a1">2018</button>
                <button id="a1">2017</button>
                <button id="a1">2016</button>
                <button id="a1">2015</button>
                <button id="a1">2014</button>
                <button id="a1">2013</button>
                <button id="a1">2012</button>
                <button id="a1">2011</button>
                <button id="a1">2010</button>
                <button id="a1">2009</button>
                <button id="a1">2008</button>
                <button id="a1">2007</button>
                <button id="a1">2006</button>
                <button id="a1">2005</button>
                <button id="a1">2004</button>
                <button id="a1">2003</button>
                <button id="a1">2002</button>
                <button id="a1">2001</button>
            </div>
        </aside>
    </main>
    <footer class="container-1">
        <div class="container1">"Copyright Policy / DMCA"</div>
        <div class="container1">Powered by <u>4MoviesRulz</u></div>
        <div >All of the free movies found on this website are hosted on third-party servers that are freely available to watch online for all internet users.
            Any legal issues regarding the free online movies on this website should be taken up with the actual file hosts themselves, as we're not affiliated with them.</div>
    </footer>
   
    
</body>
</html>
