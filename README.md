# flipcart
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
        <style>
            *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.nav{
    border: 0px solid black;
    height: 80px;
    width: 100%;
    display: flex;
    
}
nav>.logo{
    height: inherit;
    width: 15%;
    background-image: url(./Flipkart-logo-768x432.png);
    background-position: center;
    background-repeat: no-repeat;
    background-size: contain;
    
}
nav>.search{
    height: inherit;
    width: 50%;
    
}
nav>.many{
    height: inherit;
    width: 35%;
   
}
.search{
    display: flex;
    justify-content: flex-start;
    align-items: center;
    padding: 10px;
}
.nav>.search>.searcher{
    height: 80%;
    width: 90%;
    border: 0px solid black;
    border-radius: 10px;
    padding: 5px;
    background-color: beige;
    
}
.search>.searcher>input{
    border: 1px solid black;
    height:100%;
    width: 92%;
    border-radius: 10px;
    align-items: flex-end;
    border: none;
    outline: none;
    background-color: beige;
}
.many>.button{
    height: inherit;
    width: auto;
    display: flex;
    justify-content:space-evenly;
    align-items: center;
    list-style: none;
}
.menu>ul>li>i{
    font-size: small;
    padding: auto;
}
nav>.many>ul>li>span:hover{
    background-color: blue;
    color: white;
    border-radius: 5px;
}
nav>.many>ul>li>.op:hover{
    background-color:#f3eded;
    color: black;
    border-radius: 5px;
    backdrop-filter: blur(50px);
}

.login_pop_up{
    background-color:antiquewhite;
    color: black;
    height: 300px;
    width: 250px;
    border: 2px solid black;
    padding-left: 10px;
    margin-top:30px;
    display:none;
    position:absolute;
    z-index: 999;
}
.login_pop_up>ul>li{
    height:40px;
    width: 200px;
}
.login_pop_up>ul{
    margin-top: 7px;    
    width: 200px;
}
.utt {
    position: relative;
    z-index: 1;
}
.utt:hover + .login_pop_up{
    display: block;
}
.main{
    background-color: white;
    width: 100%;
    height: 100vh;
    padding: 10px 10px 10px ;

}
.category{
    height:170px ;
    width: 97%;
    
    
    margin: auto;
    
}
ul li a{
    
        color: black;
        margin-inline:25px;
        list-style: none;
        margin-top: 12px;
        text-decoration: none;
        float: left;
}
h5{
    display: flex;
    margin-left: 9px;
}
.crosel{
    
    height:200px ;
    width: 98%;
    border: 2px solid black;
    margin-top: 10px;
    background-image: url(./04467b59d86b8ddb.webp);
    background-position: center;
    background-size: contain;
}
.best{
    
    height: 150px;
    width: 99%;
    border: 2px solid black;
}

        </style>
</head>

<body>
    <section>
        <nav class="nav">
            <aside class="logo"></aside>
            <section class="search">
                <div class="searcher">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <input type="text" placeholder="Search for Products, Brands and More">
                </div>

            </section>
            <aside class="many">
                <ul class="button
            ">
                    <li title="login"><span class="utt" style="height: 50px; padding: 5px;"><i      class="fa-regular fa-user"></i>
                        <span style="padding-left: 10px;">Login</span></span>
                        <section class="login_pop_up" >
                            <ul style="list-style: none; padding: 0;">
                                <ul style="display: flex; list-style: none; justify-content:space-between; padding: 0px;">
                                    <li>New customer?</li>
                                    <li><a href="#" style="text-decoration: none;font-weight: bolder;">Sign up</a></li>
                                </ul>
                                <hr style="margin-top: 10px;
                                margin-bottom: 10px;">
                                <li><i class="fa-solid fa-user" style="padding-right: 10px;"></i>My Profile</li>
                                <li><i class="fa-solid fa-compress" style="padding-right: 10px;"></i>Flipcart Plus Zone</li>
                                <li><i class="fa-solid fa-box-open" style="padding-right: 10px;"></i>Orders</li>
                                <li><i class="fa-regular fa-heart" style="padding-right: 10px;"></i>Whishlist</li>
                                <li><i class="fa-solid fa-gift" style="padding-right: 10px;"></i>Rewards</li>
                                <li><i class="fa-solid fa-id-card" style="padding-right: 10px;"></i>Gift Cards</li>
                            </ul>
                        </section>
                    </li>

                    <li title="cart"><span style="height: 50px; padding: 5px;"><i
                                class="fa-solid fa-cart-shopping"></i><span
                                style="padding-left: 10px;">Cart</span></span></li>
                    <li title="Become a Seller"><span style="height: 50px; padding: 5px;"><i
                                class="fa-solid fa-store"></i><span style="padding-left: 10px;">Become a
                                Seller</span></span>
                    <li title="Dropdown with more help link"><span class="op"
                            style="height: 50px; width: 100px; padding: 15px;"><i
                                class="fa-solid fa-ellipsis-vertical"></i></span></li>
                </ul>
            </aside>
        </nav>
    </section>
    <main class="main">
        <section class="category">
        </nav>
        <ul>
            <li>
                <a href="#"><img src="./29327f40e9c4d26b.webp" alt=""><h5>Grocery</h5></a>
                 <a href="#"><img src="./22fddf3c7da4c4f4.webp" alt=""><h5>Mobile</h5></a>
                 <a href="#"><img src="./0139228b2f7eb413.webp" alt=""><h5>Fashion</h5></a>
                 <a href="#"><img src="./69c6589653afdb9a.webp" alt=""><h5>Electronic</h5></a>
                 <a href="#"><img src="./ab7e2b022a4587dd.webp" alt=""><h5>furniture</h5></a>
                 <a href="#"><img src="./0139228b2f7eb413.webp" alt=""><h5>appliance</h5></a>
                 <a href="#"><img src="./71050627a56b4693.webp" alt=""><h5>Travel</h5>
                 </a>
                 <a href="#"><img src="./dff3f7adcf3a90c6.webp" alt=""><h5>Beauty, toys, <br>more</h5></a>
                 
            </li>
        </ul>
        </section>
        <section class="crosel">

        </section>
    </main>
    <section class="best">
        <h4>Best Of Electronic</h4>
        <main class="elec"></main>
    </section>
</body>

</html>
