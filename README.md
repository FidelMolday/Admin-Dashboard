# Admin-Dashboard
html css and js project
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>Responsive Admin Dashboard</title>
</head>
<body>
    <div class="container">
        <div class="navigation">
            <ul>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="logo-apple"></ion-icon>
                        </span>
                        <span class="title">Brand Name</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="home-outline"></ion-icon>
                        </span>
                        <span class="title">Dash board</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="people-outline"></ion-icon>
                        </span>
                        <span class="title">Customers</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="chatbubble-outline"></ion-icon>
                        </span>
                        <span class="title">Messages</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="help-outline"></ion-icon>
                        </span>
                        <span class="title">Help</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="settings-outline"></ion-icon>
                        </span>
                        <span class="title">Settings</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="lock-closed-outline"></ion-icon>
                        </span>
                        <span class="title">Password</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span class="icon">
                            <ion-icon name="log-out-outline"></ion-icon>
                        </span>
                        <span class="title">Sign Out</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>
    <div class="main">
        <div class="topbar">
            <div class="toggle">
                <ion-icon name="menu-outline"></ion-icon>
            </div>
            <div class="search">
                <label>
                    <input type="text" placeholder="search here">
                    <ion-icon name="search-outline"></ion-icon>
                </label>
            </div>
            <div class="user">
                <img src="" alt="">
            </div>
        </div>
        <div class="cardbox">
            <div class="card">
                <div>
                    <div class="numbers">1,504</div>
                    <div class="cardname">Daily views</div>
                </div>
                <div class="iconBx">
                    <ion-icon name="eye-outline"></ion-icon> 
                </div>
            </div>
            <div class="card">
                <div>
                    <div class="numbers">80</div>
                    <div class="cardname">Sales</div>
                </div>
                <div class="iconBx">
                    <ion-icon name="cart-outline"></ion-icon> 
                </div>
            </div>
            <div class="card">
                <div>
                    <div class="numbers">284</div>
                    <div class="cardname">Comments</div>
                </div>
                <div class="iconBx">
                    <ion-icon name="chatbubble-outline"></ion-icon> 
                </div>
            </div>
            <div class="card">
                <div>
                    <div class="numbers">$7,842</div>
                    <div class="cardname">Earnings</div>
                </div>
                <div class="iconBx">
                    <ion-icon name="cash-outline"></ion-icon>
                </div>
        </div>
        </div>
        <div class="details">
            <div class="recentOrders">
            <div class="cardHeader">
                <h2>Recent Orders</h2>
                <a href="#" class="btn">View All</a>
            </div>
            <table>
                <thead>
                    <tr>
                        <td>Name</td>
                        <td>Price</td>
                        <td>Payment</td>
                        <td>Status</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Lenovo laptop</td>
                        <td>$1200</td>
                        <td>Paid</td>
                        <td><span class="Status delivered">Delivered</span></td>
                    </tr>
                    <tr>
                        <td>Dell laptop</td>
                        <td>$1100</td>
                        <td>Due</td>
                        <td><span class="Status pending">Pending</span></td>
                    </tr>
                    <tr>
                        <td>Apple Watch</td>
                        <td>$880</td>
                        <td>Paid</td>
                        <td><span class="Status return">Return</span></td>
                    </tr>
                    <tr>
                        <td>Hard Disc</td>
                        <td>$900</td>
                        <td>Due</td>
                        <td><span class="Status inprogress">In Progress</span></td>
                    </tr>
                    <tr>
                        <td>Lenovo laptop</td>
                        <td>$1200</td>
                        <td>Paid</td>
                        <td><span class="Status delivered">Delivered</span></td>
                    </tr>
                    <tr>
                        <td>Dell laptop</td>
                        <td>$1100</td>
                        <td>Due</td>
                        <td><span class="Status pending">Pending</span></td>
                    </tr>
                    <tr>
                        <td>Apple Watch</td>
                        <td>$880</td>
                        <td>Paid</td>
                        <td><span class="Status return">Return</span></td>
                    </tr>
                    <tr>
                        <td>Hard Disck</td>
                        <td>$900</td>
                        <td>Due</td>
                        <td><span class="Status inprogress">In Progress</span></td>
                    </tr>
                </tbody>
            </table>
            </div>
        </div>
    </div>
</div>
    <style>
        *{
            font-family: "ubuntu",sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        :root{
            --blue:#2a2185;
            --white:#fff;
            --gray:#f5f5f5;
            --black1:#222;
            --black2:#999;
        }
        body{
            min-height: 100vh;
            overflow-x: hidden;
        }
        .container{
            position: relative;
            width: 100%;
        }
        .navigation{
            position: fixed;
            width: 300px;
            height: 100%;
            background: var(--blue);
            border-left: 10px solid var(--blue);
            transition: 0.5s;
            overflow: hidden;
        }
        .navigation.active{
            width: 80px;

        }
        .navigation ul{
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
        }
        .navigation ul li{
            position: relative;
            width: 100%;
            list-style: none;
            border-top-left-radius: 30px;
            border-bottom-left-radius:30px;
        }
        .navigation ul li:hover,
        .navigation ul li.hovered{
            background-color: var(--white);
        }
        .navigationul li:nth-child(1){
            margin-bottom: 40px;
            pointer-events: none;
        }
        .navigation ul li a{
            position: relative;
            display: block;
            width: 100%;
            display: flex;
            text-decoration: none;
            color:var(--white);
        }
        .navigation ul li:hover a,
        .navigation ul li.hovered a{
            color: var(--blue);
        }
        .navigation ul li a .icon{
            position: relative;
            display: block;
            min-width: 60px;
            height: 60px;
            line-height: 60px;
            text-align: center;
        }
        .navigation ul li a .icon ion-icon{
            font-size: 1.75rem;
        }
        .navigation ul li a.title{
            position: relative;
            display: block;
            padding: 0 10px;
            height: 60px;
            line-height: 75px;
        }
        .navigation ul li a .title{
            position: relative;
            display: block;
            padding: 0 10px;
            height: 60px;
            line-height: 60px;
            text-align: start;
            white-space: nowrap;
        }
        
        .main{
            position: absolute;
            width: calc(100% -300px);
            left: 300px;
            min-height: 100vh;
            background: var(--white);
            transition: 0.5s;
        }
        .main.active{
            width: calc(100% -80px);
            left: 80px;
        }
        .topbar{
            width: 100%;
            height: 60px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 10px;
        }
        .toggle{
            position: relative;
            width: 60px;
            height: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 2.5rem;
            cursor: pointer;
        }
        .search{
            position: relative;
            width: 400px;
            margin: 0 10px;
        }
        .search label{
            position: relative;
            width: 100%;
        }
        .search label input{
            width: 100%;
            height: 40px;
            border-radius: 40px;
            padding: 5px 20px;
            padding-left: 35px;
            font-size: 18px;
            outline: none;
            border: 1px solid var(--black2);
        }
        .search label ion-icon{
            position: absolute;
            top: 0;
            left: 10px;
            font-size: 1.2rem;
        }
        .user{
            position: relative;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            overflow: hidden;
            cursor: pointer;
        }
        .user img{
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .cardbox{
            position: relative;
            width: 100%;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(4,1fr);
            grid-gap:30px;
        }
        .cardbox .card{
            position: relative;
            background: var(--white);
            padding: 30px;
            border-radius: 20px;
            display: flex;
            justify-content: space-between;
            cursor: pointer;
            box-shadow: 0 7px 25px rgba(0,0,0,0.08);
        }
        .cardbox .card .numbers{
            position: relative;
            font-weight: 500;
            font-size: 2.5rem;
            color: var(--blue);
        }
        .cardbox .card .cardname{
            color: var(--black2);
            font-size: 1.1rem;
            margin-top: 5px;
        }
        .cardbox .card .iconBx{
            font-size: 3.5rem;
            color: var(--black2);
        }
        .cardbox .card:hover{
            background: var(--blue);
        }
        .cardbox .card:hover .numbers,
        .cardbox .card:hover .cardname,
        .cardbox .card:hover .iconBx{
            color: var(--white);
        }
        .details{
             position: relative;
             width: 100%;
             padding: 20px;
             display: grid;
             grid-template-columns: 2fr 1fr;
             grid-gap: 30px;
             
        }
        .details .recentOrders{
            position: relative;
            display: grid;
            min-height: 500px;
            background: var(--white);
            padding: 20px;
            box-shadow: 0 7px 25px rgba(0,0,0,0.08);
            border-radius: 20px;
        }
        .details .cardHeader{
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }
        .cardHeader h2{
            font-weight: 600;
            color: var(--blue);
        }
        .cardHeader .btn{
            position: relative;
            padding: 5px 10px;
            background: var(--blue);
            text-decoration: none;
            color: var(--white);
            border-radius: 6px;
        }
        .details table{
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        .details table thead td{
            font-weight: 600;
        }
        .details .recentOrders table tr{
            color: var(--black1);
            border-bottom: 1px solid rgba(0,0,0,0.1);
        }
        .details .recentOrders table tr:last-child{
            border-bottom: none;

        }
        .details .recentOrders table tbody tr:hover{
            background: var(--blue);
            color: var(--white);
        }
        .details .recentOrders table tr td{
            padding: 10px;
        }
        .details .recentOrders table tr td:last-child{
            text-align: end;
        }
        .details .recentOrders table tr td:nth-child(2){
            text-align: end;
        }
        .details .recentOrders table tr td:nth-child(3){
            text-align: center;
        }
        .Status.delivered{
            padding: 2px 4px;
            background: #8de02c;
            color: var(--white);
            border-radius: 4px;
            font-size: 14px;
            font-weight: 500;
        }
        .Status.pending{
            padding: 2px 4px;
            background: #f00;
            color: var(--white);
            border-radius: 4px;
            font-size: 14px;
            font-weight: 500;
        }
        .Status.return{
            padding: 2px 4px;
            background: #f9ca3f;
            color: var(--white);
            border-radius: 4px;
            font-size: 14px;
            font-weight: 500;
        }
        .Status.inprogress{
            padding: 2px 4px;
            background: #1795ce;
            color: var(--white);
            border-radius: 4px;
            font-size: 14px;
            font-weight: 500;
        }
    </style>
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
<script>
    let list = document.querySelectorAll("navigation li");
    function activeLink(){
        list.forEach(item=>{
            item.classList.remove("hovered");
        });
        this.classList.add("hovered");
    }
    list.forEach(item => item.addEventListener("mouseover",activeLink))

    let toggle = document.querySelector(".toggle");
    let navigation = document.querySelector(".navigation");
    let main = document.querySelector(".main");
    toggle.onclick =function(){
        navigation.classList.toggle("active");
        main.classList.toggle("active");
    };
</script>
</body>
</html>
