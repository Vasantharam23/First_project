# First_project
<!DOCTYPE html>
<html lang="en">
<head>
    <title>pro</title>
    <link rel="stylesheet" href="https://png.pngtree.com/png-clipart/20200709/original/pngtree-watercolor-purple-flowers-png-image_857904.jpg">
    <link href="https://fonts.googleapis.com/css2?family=Philosopher:ital@1&family=Tangerine:wght@700&display=swap" rel="stylesheet">  
    <link href="https://fonts.googleapis.com/css2?family=Fredericka+the+Great&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Italianno&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Italianno&family=Rochester&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Zen+Loop&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Cinzel&family=Zen+Loop&display=swap" rel="stylesheet">

<style>
        * 
        {
            box-sizing: border-box;            
        }
        .grid
        {
            display: grid;
            grid-template-columns: auto auto auto auto auto;
            grid-row-gap: 3%;
        }   
        .peak
        {
            background: rgb(76,50,50);
            background: linear-gradient(315deg, rgba(76,50,50,1) 0%, rgba(27,21,64,1) 42%);          
            padding: 25px;
            position: absolute;
            width: 100%;
            color: rgba(228, 231, 209, 0.849);
            top: 0;
            left: 0;           
        }
        body , html
        {
            height: 100%;
            margin: 0;
            padding: 0%;
        }
        body
        {
            background: rgb(13,12,20);
            background: radial-gradient(circle, rgba(13,12,20,1) 0%, rgba(0,0,0,1) 0%);
            background-size:cover;         
        } 
        .box
        {
            display:block;
            opacity: 0.8;
            height: 14%;
            width: 90%;
            margin-left: 5.5%;
            margin-top: 160px;
            color: rgba(247, 242, 242, 0.945);
            text-align: center;
            font-size: 25px;
            opacity: 1;
            border-radius: 10px;   
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; z-index:-1;        
        }     
        .box1
        {         
            color: silver;         
            margin-top: 1%;
            text-align: center;
            font-family: 'Italianno', cursive;  text-align: center; font-size: 68px;
        } 
        .circle
        {
            height: 35px;
            width: 35px;
            border: 1px solid black;
            opacity: .8;
            background-color: goldenrod;
            border-radius: 50%;
            position: absolute;
            top: 0;
            left: 10px;
            animation-name: slide;
            animation-iteration-count: infinite;
            animation-direction:alternate-reverse;
            animation-duration: 9s;
        }
        @keyframes slide
        {
            from
            {
              top: 0;
              left: 0;
            }
            to 
            {
              left: 100% ;
            }
        }
        .item item2:hover
        {
        background-color: grey;
        }
        .end
        {
            padding: 20px;
            display: block;
            background: rgb(76,50,50);
            background: linear-gradient(315deg, rgba(76,50,50,1) 0%, rgba(27,21,64,1) 42%);
            color: white;
            text-align: center;
            font-size: 20px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        .first
        {
            font-size: 100px;
            float: left;
            font-family: 'Zen Loop', cursive;
        }
        
        .item4
        {
            font-size: 20px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            margin-top: 30px;
            color: rgba(228, 231, 209, 0.849);
            text-decoration: none;
        }
        .item3
        {
             font-size: 20px;
             /* background-color: rgb(5, 3, 15); */
             color: rgba(228, 231, 209, 0.849); 
             font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
             margin-top: 30px;
             text-decoration: none;
        }
        .item5
        {
            font-size: 20px; ;color: rgba(228, 231, 209, 0.849);  
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            margin-top: 30px;
            text-decoration: none;
        }
        .item1
        {
            font-size: 70px; font-family: 'Tangerine', cursive; text-align: center; color: goldenrod;
        }
        #search1
        {
            margin-top: 2%; background-color: wheat; color: black; height: 50px; width: 600px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            text-align: center;
            font-size: 20px;           
        }
        #search2
        {
            height: 50px; 
            background: rgb(135,48,86);
            background: linear-gradient(315deg, rgba(135,48,86,1) 0%, rgba(7,25,47,1) 100%);
            color: wheat;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #img1
        {
            margin-top: 1%;
            margin-left: 5%;
            border: 2px solid silver;  
        }
        #img2
        {
            margin-top: 0; 
            margin-left: 35%; 
            border: 2px solid silver;
        }
        #img3
        {
            margin-top: 0;
            margin-left: 65%; 
            border: 2px solid silver;
        }
        .line
        {
            margin-left: 20%;
            margin-right: 20%;
            margin-top: 3%;
            border-bottom: 1px solid goldenrod;
        }
 </style>
</head>

<body>
    <div class="peak">

        <div class="grid">
            <div class="circle"></div>
            <div class="item item1">De Grand Interiors..</div>
            <div class="item item2">
                <form action="" method="GET">
                    <input id="search1" name="address" type="text" placeholder="What are you looking for?">
                    <button id="search2">Search</button>
                </form>
            </div>
    
            <a class="item item5" href="wwww.google.com">About Us</a>
            <a class="item item4" href="www.google.com">Book An Appointment</a>
            <a class="item item3" href="www.google.com">Log In/Sign In</a>
        </div>

    </div>


    <div class="box">  
        <span class="first">M</span> odern design grew out of the decorative arts, mostly from the Art Deco, in the early 20th century. One of the first to introduce this style was Frank Lloyd Wright, who hadn't become hugely popularized until completing the house called Fallingwater in the 1930s. Modern art reached its peak in the 1950s and '60s, which is why designers and decorators today may refer to modern design as being "mid-century." Modern art does not refer to the era or age of design and is not the same as contemporary design, a term used by interior designers for a shifting group of recent styles and trends.
    </div> 
    <div class="line"></div>
      
    <div class="box1">    Chips of our works!     </div>

    <img id="img1" src="https://images.unsplash.com/photo-1623839627668-0b0a573d5ccf?ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDE1fFJfRnluLUd3dGx3fHxlbnwwfHx8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=60" height="70%" width="30%">

    <img src="https://images.unsplash.com/photo-1623921017613-9970959b91b7?ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDEzfFJfRnluLUd3dGx3fHxlbnwwfHx8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=60" height="70%" width="30%" id="img2">

    <img src="https://images.unsplash.com/photo-1597498178146-3e9378203bc9?ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDEyMnxSX0Z5bi1Hd3Rsd3x8ZW58MHx8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=60" height="70%" width="30%" id="img3">
    
    <div class="end">  

        Email us: contact@degrand.com
        <div>Toll: 1800 xxx 3419</div>
        <div>De Grand Interiors &copy;</div>

    </div>

</body>
</html>
