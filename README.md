# M-Trix-cafe
Cake shop
<!DOCTYPE html>
<html>
    <head>
        <style>
             body{
                font-family: 'Segoe UI', sans-serif;
                background-color: #e6f4ef;
                padding:0;
                margin: 0;
            }   
            header {
                background-color: #27755d;
                color: white;
                display: flex;
                align-items: center;
                justify-content: space-between;
                padding: 10px 60px;
            }
            .left {
                display: flex;
                align-items: center;
                gap: 100px;
            }
           .right a {
                color: white;
                text-decoration: none;
                margin-left: 20px;
                font-size: 16px;
            }

            .logo{
                display:flex;
                justify-content: space-around;
                align-items: center;
                width: 90vw;
            }
            .cake{
                width: 300px;
                background-color: #ffffff;
                border-radius: 10px;
                box-shadow: 0 4px 8px rgba(0,0,0,0.1);
                overflow: hidden;
                text-align: center;
                padding: 10px;
                
            }
            .card{
                display: flex;
                flex-direction: row;
                justify-content: space-around;
                align-items: center;
                width: 280px;
                height: 10px;
                padding-bottom: 15px;
            }
            .container{
                width: 100%;
                display: flex;
                justify-content: space-around;
                align-items: center;
                gap: 20px;
                flex-wrap: wrap;
                padding: 20px;
            }
            button{
                width: 30px;
                height: 30px;
                background-color: #94cbba;
                border-radius: 5px;
            }
            
            .cake img {
                width: 250px ;
                height: 220px;
                border-radius: 10px;
            }
            #logo {
                height:60px;
            }
            .controls {
                display: flex;
                align-items: center;
                gap: 10px;
            }

            .controls button {
                background-color: #27755d;
                color: white;
                width: 30px;
                height: 30px;
                font-size: 18px;
                border-radius: 5px;
        }
        </style>
    </head>
    <body>
        <header>
            <div class="left">
                <img src="c:\Users\Dell\Downloads\m-trix_logo-removebg-preview.png" alt="M-TRIX Logo" id="logo">
                <h2>M-TRIX Café</h2>
            </div>
            <div class="right">
                <a href="main.html">Home</a>
                <a href="card.html">Cart</a>
            </div>
        </header>
        <div class="container">
        <div class="cake">
            <img 
            src="https://i.pinimg.com/736x/3c/4f/c8/3c4fc8d10c64c6d2446c44d6d6ccd881.jpg" 
            alt="zurag"
            width="280px"
            height="280px">
            <h1 
            style="margin-top: 5px;">Dubai Chocolate Cheesecake</h1>
            <div class="card">
                <h2>150000</h2>
                <div class="controls">
                    <button>+</button>
                    1
                    <button>-</button>
                </div>
            </div>
        </div>
        <div class="cake">
            <img 
            src="https://i.pinimg.com/474x/e9/e0/c9/e9e0c96d957892b8572aaef4c6afe15a.jpg" 
            alt="zurag"
            width="280px"
            height="280px">
            <h1 
            style="margin-top: 5px;">Waxberry Crepe cake</h1>
            <div class="card">
                <h2>70000</h2>
                <div class="controls">
                    <button>+</button>
                    1
                    <button>-</button>
                </div>
            </div>
        </div>
        <div class="cake">
            <img 
            src="https://i.pinimg.com/474x/a1/b7/5b/a1b75b3d6f78b7a5c5ba0a7607aaf794.jpg" 
            alt="zurag"
            width="280px"
            height="280px">
            <h1 
            style="margin-top: 5px;">Mini Biscuit Mousse Cake</h1>
            <div class="card">
                <h2>50000</h2>
                <div class="controls">
                    <button>+</button>
                    1
                    <button>-</button>
                </div>
            </div>
        </div>
        <div class="cake">
            <img 
            src="https://i.pinimg.com/474x/7d/bc/d7/7dbcd7b8ea0725ae14075abc01d536b2.jpg" 
            alt="zurag"
            width="280px"
            height="280px">
            <h1 
            style="margin-top: 5px;">Moloko Strawberry Cheesecake</h1>
            <div class="card">
                <h2>67000</h2>
                <div class="controls">
                    <button>+</button>
                    1
                    <button>-</button>
                </div>
            </div>
        </div>
        <div class="cake">
            <img 
            src="https://i.pinimg.com/474x/95/cb/e5/95cbe508759833b35ab22b405f2489d9.jpg" 
            alt="zurag"
            width="280px"
            height="240px">
            <h1 
            style="margin-top: 5px;">Blueberry mint cheesecake</h1>
            <div class="card">
                <h2>76000</h2>
                <div class="controls">
                    <button>+</button>
                    1
                    <button>-</button>
                </div>
            </div>
        </div>
        <div class="cake">
            <img 
            src="https://www.deborah-dianne.com/cdn/shop/files/20230810_144742.jpg?v=1714604548"
            alt="zurag"
            width="280px"
            height="240px">
            <h1 
            style="margin-top: 5px;">Decadent chocolate cake</h1>
            <div class="card">
                <h2>69000</h2>
                <div class="controls">
                    <button>+</button>
                    1
                    <button>-</button>
                </div>
            </div>
        </div>
        </div>
    </body>
</html>
