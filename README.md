# shopper-template
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopper-template</title>
    <link rel="shortcut icon" href="public/images/shopperfavicon.ico">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        .header-1{
            
            background-color: rgb(247, 245, 245);
            margin-top: -10px; height: 45px;
            align-items: center;
            font-family: arial;
            font-size: 13px;
            font-weight: 500;
        }
        .hed1-btn{
            border: none;
        }
        .hed1-2nd{
            display: flex; margin-left: -160px;
        }
        .hed1-3rd{
            display: grid; grid-template-columns: 5fr 3fr 4fr; width: 200px;
        }
        .hed1-4th{
            display: flex; margin-left: -200px; color: gray;
        }
        
        @media screen and (orientation:landscape)
        {
            .header-1{
                display: flex;
                justify-content: space-around;
            }
            .hed1-btn{
                display: none;
            }
            .header{
                display: flex;
                justify-content: space-around;
                padding: 22px;
            }
            .brand-name{
                font-size: 25px;
                font-weight: bold;
                cursor: pointer;
            }
            .header-btn{
                display: none;
            }
            main{
                height: 500px;
                display: grid;
                grid-template-columns: 4fr 4fr 4fr;
            }
            .det-d{
                font-size: 13px;
                display: grid;
                grid-template-columns: 1fr 11fr;
            }
            .portpara{
                display: none;
            }
            .details{
            margin-top: 30px;
            display: flex;
            justify-content: space-between;
            margin-left: 120px;
            margin-right: 120px;
            padding-bottom: 30px;
            border-bottom: 1px solid lightgray;
            padding-left: 50px;
            }
            .container{
                display: grid;
                grid-template-columns: 1.5fr 3fr 6fr 1.5fr;
                grid-gap: 30px;
            }
            .container2{
                display: grid;
                grid-template-columns: 1.5fr 6fr 3fr 1.5fr;
                grid-gap: 30px;
            }
            .bag{
                width: 100%;
                height: 400px;
                overflow: hidden;
                position: relative;
            }
            .men{
                width: 100%;
                height: 400px;
                overflow: hidden;
                position: relative;
            }
            .men-title-box{
                position: absolute;
                color: black;
                top: 0px;
                width: 100%;
                height: 100%;
                font-family: arial;
                display: flex;
                justify-content: center;
                flex-direction: column;
                align-items: baseline;
                text-align: center;
            }
            .new-collection{
                margin-top: 70px;
                display: flex;
                flex-direction: column;
                font-family: arial;
                align-items: center;
            }
            .pport{
                display: none;
            }
            .new-collection p{
                color: gray;
                font-size: 14px;
            }
            .item-category{
                display: grid;
                grid-template-columns: 1.5fr 2.25fr 2.25fr 2.25fr 2.25fr 1.5fr;
                grid-gap: 30px;
                margin-top: 50px;
            }
            .Discover-more-img{
                background-image: url("public/images/discovery-more.jpg");
                width:100%;
                height: 500px;
                background-size: cover;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: space-evenly;
            }
            #con{
                margin-left: 390px;
            }
            section{
                height: 4900px;
                margin-top: 15px;
                font-family: arial;
            }
            .shopper-cap{
                font-size:17px; color: gray;
            }
            .shopper-capl{
            display: none;
            
            }
            .shopper-img{
                display: grid;
                grid-template-columns: 1.5fr 1.5fr 1.5fr 1.5fr 1.5fr 1.5fr 1.5fr 1.5fr;
                grid-gap: 5px;
                margin-top: 50px;
            }
            .shopper{
                margin-top: 70px;
                background-color: rgb(248, 246, 246);
                height: 650px;
           
            }
            .shopper-img2{
                display: grid;
                grid-template-columns: 1.40fr 1.31fr 1.31fr 1.31fr 1.31fr 1.31fr 1.31fr 1.31fr 1.40fr;
                grid-gap: 10px;
                margin-top: 50px;
            }
            .reviews{
                display: grid;
                grid-template-columns: 1.5fr 3fr 3fr 3fr 1.5fr ;
                grid-gap: 35px;
                margin-top: 50px;
            }
            footer{
                background-color: #000;
                padding: 10px;
                color: #fff;
                height: 625px;
            }
            .subscribe{
                display: flex;
                justify-content: center;
                align-items: center;
                height: 200px;
                text-align: center;
                margin-top: 50px;
            }
            .email{
                display: inline-block;
                width: 300px;
                padding: 20px;
                font-size: 16px;
                color: lightgray;
                text-align: left;
                background-color: rgb(46, 43, 43)
            }
            .btn{
                font-size: 18px;
                padding: 20px;
                width: 100px;
                text-align:center;
                display: inline-block;
                text-align: center;
                background-color: rgb(87, 82, 82);
            }
            .footer{
                margin-top: 50px;
                display: grid;
                height: 300px;
                grid-template-columns: 1fr 2fr 2fr 2fr 2fr 2fr 1fr;
                font-family: arial;
            }
            .last-div{
                margin-top: -50px;
                border-bottom: 2px solid rgb(87, 84, 84);
            }
            .footer .no{
                display: none;
            }
            .copyright{
                font-size: 12px; 
                margin-top: 30px; 
                margin-left: 200px; 
                color: gray;
            }
            .footcardimg{
                float: right; 
                margin-top: -20px; 
                margin-right: 200px;
            }
        }
        @media screen and (orientation:portrait){
            .header-1{
                display: flex;
                justify-content: space-between;
            }
            .hed1-1st{
                padding-left: 20px;
            }
            .hed1-2nd{
                display: none;
            }
            .hed1-3rd{
                display: none;
            }
            .hed1-4th{
                display: none;
            }
            .hed1-btn{
                display: inline;
                font-size: 20px;
                background-color: transparent;
            }
            .header{
                display: flex;
                justify-content: space-between;
                padding-top: 22px;
                padding-bottom: 22px;
            }
            .header-btn{
                display: inline;
                font-size: 20px;
            }
            .brand-name{
                font-size: 25px;
                font-weight: bold;
                cursor: pointer;
                padding-left: 20px;
            }
            .header-2nd{
                display: none;

            }
            .header-3rd{
                display: none;
            }
            .womens{
                height: 500px;
            }
            .mens{
                height: 500px;
            }
            .kids{
                height: 500px;
            }
            .new-collection{
                margin-top: 70px;
                display: flex;
                flex-direction: column;
                font-family: arial;
                justify-content: center;
                align-items: center;
                text-align: center;
            }
            .pland{
                display: none;
            }
            .det-d{
                font-size: 13px;
                display: grid;
                margin-bottom: 20px;
                margin-left: 10px;
                font-size: 20px;
                grid-template-columns: 1fr 11fr;
            }
            .details{
            margin-top: 30px;
            border-bottom: 1px solid lightgray;
            }
            
            .new-collection p{
                color: gray;
                font-size: 16px;
            }
            .bag{
                width: 100%;
                height: 450px;
                overflow: hidden;
                position: relative;
            }
            .men{
                width: 100%;
                height: 450px;
                overflow: hidden;
                position: relative;
                margin-top: 50px;
                margin-bottom: 50px;
            }
            .men-title-box{
                position: absolute;
                color: black;
                top: 0px;
                width: 100%;
                height: 100%;
                font-family: arial;
                display: flex;
                justify-content: center;
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            .item-category{
                display: grid;
                grid-template-columns:6fr 6fr;
                grid-gap: 30px;
                margin-top: 50px;
            }
            .item-category .none{
                display: none;
            }
            .item-category .pic-1{
                height: 250px;
            }
            .item-category .pic-2{
                height: 250px;
            }
            .item-category .pic-3{
                height: 250px;
            }
            .item-category .pic-4{
                height: 250px;
            }
            .item-category .pic-5{
                height: 250px;
            }
            .item-category .pic-6{
                height: 250px;
            }
            .item-category .pic-7{
                height: 250px;
            }
            .item-category .pic-8{
                height: 250px;
            }
            .Discover-more-img{
                background-image: url("public/images/discovery-more.jpg");
                width:100%;
                height: 650px;
                background-size: cover;
                background-position: center center;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: space-evenly;
            }
            #con{
            font-size:smaller;
            }

            .reviews{
                display: grid;
                grid-template-columns: 12fr;
                grid-gap: 35px;
                margin: 25px;
                margin-top: 50px;
            }
            .reviews .none{
                display: none;
            }
            #review2{
                display: none;
            }

            .shopper{
                margin-top: 70px;
                background-color: rgb(248, 246, 246);
                padding-bottom: 100px;
            }
            .shopper-capl{
                font-size:20px; color: gray;
                align-items: center;
            }
            .shopper-cap{
                display: none;
            }
            .shopper-img{
                display: grid;
                grid-template-columns: 6fr 6fr;
                grid-gap: 5px;
                margin-top: 50px;
            }
            .shopper-img .none{
                display: none;
            }
            .shopper-img2{
                display: grid;
                grid-template-columns: 6fr 6fr;
                grid-gap: 10px;
                margin-top: 50px;
            }
            .shopper-img2 .none{
                display: none;
            }
            footer{
                background-color: #000;
                padding: 10px;
                color: #fff;
            }
            .subscribe{
                display: flex;
                justify-content: center;
                align-items: center;
                height: 200px;
                text-align: center;
                width: 100%;
                margin-top: 100px;
            }
            .emailsubsc{
                display: grid;
                grid-template-columns: 7fr 5fr;
            }
            .email{
                display: inline-block;
                padding: 20px;
                margin-left: 15px;
                font-size: 16px;
                color: lightgray;
                text-align: left;
                background-color: rgb(46, 43, 43);
            }
            .btn{
                font-size: 18px;
                padding: 20px;
                text-align:center;
                display: inline-block;
                text-align: center;
                background-color: rgb(87, 82, 82);
            }
            .footer{
                margin-top: 50px;
                display: grid;
                margin-left: 10px;
                height: 600px;
                grid-template-columns: 6fr 6fr;
                grid-gap:5px ;
                font-family: arial;
            }
            .last-div{
                margin-top: 25px;
                border-bottom: 2px solid rgb(87, 84, 84);
            }
            .footer .none{
                display: none;
            }
            .footer div{
                height: fit-content;
            }
            .copyright{
                margin-bottom: 30px;
                font-size: 12px; 
                margin-top: 30px; 
                color: gray;
            }
        }
        .header{
            font-size: 15px;
            font-family: arial;
            position: sticky;
            top: 0px;
        }
        .header-btn{
            border: none;
            background-color: #fff;
        }
        span{
            margin-right: 20px;
        }
        .brand-name a{
            color: #000;
            text-decoration: none;
        }
        nav span:hover{
            color: #ff6f61;
            cursor:pointer;
            
        }
        article{
            text-align: center;
            background-color: #000;
            color: #fff;
            font-size: 13px;
            font-family: Arial;
            padding: 15px;
            font-weight: bold;
        }
        .bi-lightning-fill{
            color: #ff6f61;
            font-size: 10px;
        }
        article span{
            
            margin: 0px;
            margin-left: 5px;
            display: inline-block;
        }
        .subscribe-title{
            font-family: arial;
            font-size: 25px;
            font-weight: bold;
            margin-bottom: 40px;
        }
        .btn:hover{
            background-color: rgb(108, 105, 105);
        }
        .footer-title{
            font-weight: bold;
            display: block;
            margin-bottom: 20px;
        }
        .footer-title~span{
            display: block;
            margin-bottom: 15px;
            color:gray;
           
        }
        .footer-brand{
            font-size: 25px;
            font-weight: bold;
            margin-bottom: 20px;
           
        }
        .footer-brand~aside{
            color: gray;
        }
        aside span{
            font-size: 20px;
            margin-right: 10px;
           
        }
        .cart{
            position: relative;
            width: 20px;
        }
        .items{
            display: inline-block;
            height: 18px;
            width: 18px;
            background-color: #ff6f61;
            color: white;
            font-size: 10px;
            border-radius: 20px;
            padding: 1px;
            text-align: center;
            position: absolute;
            top: -13px;
            right: -13px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .btn-shop .bi-arrow-right{
            margin-left: 15px;
        }
        .womens{
            background-image: url("public/images/Women-fashions.jpg");
            background-size: cover;
            background-repeat: no-repeat;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
            opacity: 1;
        }
        .mens{
            background-image: url("public/images/mens-shoppings.jpg");
            background-size: cover;
            background-repeat: no-repeat;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
            opacity: 1;
        }
        .kids{
            background-image: url("public/images/kids-fashions.jpg");
            background-size: cover;
            background-repeat: no-repeat;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
            opacity: 1;
        }
        .bi-arrow-right{
            transition: 1s;
        }
        .womens:hover, .mens:hover, .kids:hover{
            opacity: 0.9;
        }
        .womens:hover .bi-arrow-right{
            transform: translateX(5px);
            display: inline-block;
            transition: 1s;
            color: black;
        }
        .mens:hover .bi-arrow-right{
            transform: translateX(5px);
            transition: 1s;
            color: black;
        }
        .kids:hover .bi-arrow-right{
            transform: translateX(5px);
            transition: 1s;
            color: black;
        }
        .mens .bi-arrow-right{   
            transform: translateX(0px);
            display: inline-block;
            transition: 1s;
        }
        .womens .bi-arrow-right{   
            transform: translateX(0px);
            display: inline-block;
            transition: 1s;
        }
        .kids .bi-arrow-right{   
            transform: translateX(0px);
            display: inline-block;
            transition: 1s;
        }
        
        .title{
            font-size: 50px;
            color: white;
            font-weight: bold;
            margin-top: 180px;
        }
        .btn-shop{
            display: inline-block;
            text-align: center;
            align-items: center;
            background-color: white;
            padding: 20px;
            justify-content: center;
            display: flex;
        }
        #icons{
            color: #ff6f61;
        }
        .det-d>span{
            font-size: 18px;
        }
        .details-par{
            line-height: 1px;
            color: gray;
        }
        .new-collection div{
            font-size: 33px;
            font-weight: 600;
            font-family: arial;
        }
        p{
            line-height: 0px;
            
        }

        .container{
            margin-top: 60px;
        }
        .container2{
            margin-top: 30px;
        }
        .bag-title-box{
            position: absolute;
            color: white;
            top: 0px;
            width: 100%;
            height: 100%;
            font-family: arial;
            display: flex;
            justify-content: center;
            flex-direction: column;
            align-items: center;
        }
        .bag button{
            border: none;
            background-color: transparent;
            width: 200px;
            color: white;
            margin-top: 20px;
            font-weight: bold;
            font-size: 15px;
        }
        .bag-title{
            font-size: 25px;
            font-weight: bold;
        }
        .bi-arrow-right{
            transform: translateX(5px);
            display: inline-block;
            transition: 1s;
        }
        .bag img{
            transition: 1s;
        }
        .bag:hover img{
            transform: translateX(-5px);
            transition: 1s;
        }
        .bag:hover .bi-arrow-right{
            transform: translateX(18px);
            transition: 1s;
        }
        .men button{
            border: none;
            background-color: transparent;
            color: black;
            margin-left: 100px;
            margin-top: 20px;
            font-weight: bold;
            font-size: 15px;
        }
        .men-title{
            font-size: 25px;
            font-weight: bold;
        }
        .men img{
            transition: 1s;
        }
        .men:hover img{
            transform: translateX(-5px);
            transition: 1s;
        }
        .men:hover .bi-arrow-right{
            transform: translateX(18px);
            transition: 1s;
        }
        .offer-shirt{
            background-color: red;
            border-radius: 50px;
            color: white;
            font-weight: bold;
            width: 100px;
            height: 100px;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            align-items: center;
            text-align: center;
            position: absolute;
            top: 20px;
            right: 20px;
            text-align: center;
        }
        .tms{
            margin-top: 90px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .tms-category{
            margin-top: 30px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .tms span:hover {
            color:#ff6f61;
           
        }
        .tms-span{
            margin-right: 32px;
        }
        #active{
            color: #ff6f61;
            padding-top: 10px;
            padding-bottom: 10px;
            border-bottom: 1px solid #ff6f61;
        }
                                            /* new */
        
        
        .pic-1{
            background-image: url("public/images/shoe.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
            position: relative;
            
        }
        .pic-1:hover{
            background-image: url("public/images/shoe-copy.jpg");
        }
        .pic-2{
            background-image: url("public/images/dresses.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
        }
        .pic-2:hover{
            background-image: url("public/images/dresses-copy.jpg");
            background-size: cover;
        }
        .pic-3{
            background-image: url("public/images/shoes.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
            position: relative;
        }
        .pic-3:hover{
            background-image: url("public/images/shoes-copy.jpg");
        }
        .pic-4{
            background-image: url("public/images/dress-two.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
        }
        .pic-5{
            background-image: url("public/images/dress-three.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
        }
        .pic-6{
            background-image: url("public/images/bags.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
            position: relative;
        }
        .pic-6:hover{
            background-image: url("public/images/bags-copy.jpg");
        }
        .pic-7{
            background-image: url("public/images/skirs.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
        }
        .pic-7:hover{
            background-image: url("public/images/skirs-copy.jpg");
        }
        .pic-8{
            background-image: url("public/images/shoes-two.jpg");
            background-size: cover;
            width: 100%;
            height: 300px;
            position: relative;
        }
        .pic-1,.pic-2,.pic-3,.pic-4,.pic-5,.pic-6,.pic-7,.pic-8 {
            display: flex;
            justify-content: center;
            align-items: end;
            overflow: hidden;
        }
        .pic-1:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-2:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-3:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-4:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-5:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-6:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-7:hover .cicons{
            margin-bottom: 35px;
        }
        .pic-8:hover .cicons{
            margin-bottom: 35px;
        }
        .cicons span{
            background-color: #fff;
            padding: 10px;
            border-radius: 30px;
            margin-right: 2px;
        }
        .cicons{
            margin-bottom: -35px;
            transition: 300ms;
        }
        #heart1:hover{
            background-color: #ff6f61;
            color: white;
        }
        #eye1:hover{
            background-color: #ff6f61;
            color: white;
        }
        #cart1:hover{
            background-color: #ff6f61;
            color: white;
        }
        
        .pic-child{
        background-color: white;
        width: 45px;
        height: 20px;
        position: absolute;
        top: 20px;
        left: 0px;
        padding: 2px;
        }
        .pic-new{
        color: black;
        padding: 5px;
        font-size: 11px;
        text-align: center;
        }
        .pic-child-b{
        background-color: black;
        width: 45px;
        height: 20px;
        position: absolute;
        top: 20px;
        left: 0px;
        padding: 2px;
        }
        .pic-new-b{
        color: white;
        padding: 5px;
        font-size: 11px;
        text-align: center;
        }

        .pro-det{
            margin-top: 25px;
        }
        .pro-det div{
            margin-top: 8px;
        }
                                                    /* new */
        .Discover-more{
            
            margin-top: 100px;
            margin-bottom: 100px;
            padding-bottom: 5px;
            display: flex;
            text-align: center;
            align-items: center;
            justify-content: center;
        }
        .discmotit{
            border-bottom: 1px solid black; 
            padding-left: 15px; 
            padding-right: 15px;
        }
        .discmotit:hover{
            border-bottom: 1px solid white;
            transition: 200ms;
        }
        
        .time{
            color: orangered;
            
            opacity: 0.7 ;
        }
        .btn-dmi{
            background-color:black;
            color: white;
            padding: 19px;
            width: 115px;
            font-weight: 500;
        }
        .btn-dmi:hover .bi-arrow-right{
            transform: translateX(15px);
            transition: 500ms;
            display: inline-block;
        }
        .btn-dmi .bi-arrow-right{
            transform: translateX(10px);
            transition: 500ms;
            display: inline-block;
        }
        .what-buyer-say{
            margin-top: 100px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        .what-buyer-say div{
            margin-bottom: 15px;
        }
        .card{
             border: 1px solid lightgray;
             padding: 30px;
             height: fit-content;
             
        }
        .card-header{
            display: grid;
            grid-template-columns: 3fr 9fr;
            grid-gap: 30px;
        }
        .card-body{
            margin-top: 30px;
            margin-bottom: 30px;
            color: gray;
            text-align: left;
        }
        .card-footer
        {
            color: gray;
        }
        .rev-one{
            display: flex;
            flex-direction: column;

        }

        .rev-one span{
            margin: 0px;
            margin-bottom: 5px;
            color: rgb(240, 93, 8);
        }
        .dot{
            display: flex;
            align-items: center;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-top: 40px;
            
        }
        .dot span{
            display: inline-block;
            margin: 0px;
            color: rgb(240, 93, 8);
            font-size: 30px;
        }
        .shopper-div{
            padding-top: 100px;
            display: flex;
            flex-direction: column;
            align-items: center;
          
        }
        .shopper-div span{
            margin-bottom: 20px;
        }
        .shopper-img img{
            opacity: 1;
        }
        .shopper-img img:hover{
            opacity: 0.5;
            
        }
        .shopper-img2 div{
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .simg{
            position: relative;
        }
        .cmt{
            position: absolute; 
            top: 85px; 
            right: 10px; 
            font-size: 13px; 
            display: none;
        }
        .simg:hover .cmt{
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-1">
            <div class="hed1-1st">
                <div><span class="bi bi-truck"></span>FREE SHIPPING WORLDWIDE</div>
            </div>
            <div class="hed1-2nd">
                <div style="display: flex; justify-content: center; align-items: center; text-align: center;"><img src="public/images/aus.jpg" alt=""> United States <span class="bi bi-chevron-down"></span></div>
                <div>USD <span class="bi bi-chevron-down"></span></div>
                <div>English <span class="bi bi-chevron-down"></span></div>
            </div>
            <div class="hed1-3rd">
                <div>Shipping</div>
                <div>FAQ</div>
                <div>Contact</div>
            </div>
            <div class="hed1-4th">
                <span class="bi bi-facebook"></span>
                <span class="bi bi-twitter-x"></span>
                <span class="bi bi-instagram"></span>
                
            </div>
            <button class="hed1-btn"><span class="bi bi-justify"></span></button>
        </div>


        <div class="header">
            <div>
                <span class="brand-name"><a href="#">Shopper.</a></span>
            </div>
            <div class="header-2nd">
                <nav>
                    <span>Home</span>
                    <span>Catalog</span>
                    <span>Shop</span>
                    <span>Pages</span>
                    <span>Blog</span>
                    <span>Docs</span>
                </nav>
            </div>
            <div class="header-3rd">
                <nav>
                    <span class="bi bi-search"></span>
                    <span class="bi bi-person"></span>
                    <span class="bi bi-heart"></span>
                    <span class="cart">
                        <span class="bi bi-cart"></span>
                        <span class="items">2</span>
                    </span>
                </nav>
            </div>
            <button class="header-btn"><span class="bi bi-justify"></span></button>
    </header>
    <article>
        <span class="bi bi-lightning-fill"></span>
        <span>HAPPY HOLIDAY DEALS ON EVERYTHING</span>
        <span class="bi bi-lightning-fill"></span>
    </article>
    <section>
        <main>
            <div class="womens">
                <div class="title">Women</div>
                <span class="btn-shop">Shop Women<span class="bi bi-arrow-right" id="arrow"></span></span>
            </div>
            <div class="mens">
                <div class="title">Men</div>
                <span class="btn-shop">Shop Men<span class="bi bi-arrow-right"></span></span>
            </div>
            <div class="kids">
                <div class="title">Kids</div>
                <span class="btn-shop">Shop Kids<span class="bi bi-arrow-right"></span></span>
            </div>
        </main>

        <div class="details">
            <div></div>
            <div class="det-d">
                <span class=" bi bi-truck" id="icons"></span>
                <div>
                    <span>FREE SHIPPING</span><br>
                    <p class="details-par"> From all orders over $100</p>
                </div>
            </div>
            <div class="det-d">
                <span class="bi bi-repeat" id="icons" ></span>
                <div>
                    <span>FREE RETURNS</span><br>
                    <p class="details-par"> Return money within 30 days</p>
                </div>
            </div>
            <div class="det-d">
                <span class="bi bi-lock" id="icons" ></span>
                <div>
                    <span>SECURE SHOPPING</span><br>
                    <p class="details-par"> You're in safe hands</p>
                </div>
            </div>
            <div class="det-d">
                <span class="bi bi-tag" id="icons" ></span>
                <div>
                    <span>OVER 10,000 STYLES</span><br>
                    <p class="details-par"> We have everything you need</p>
                </div>
            </div>
            <div></div>
        </div>

        <div class="new-collection">
            <h5><font color="gray">NEW COLLECTION</font></h5>
            <div>Best Picks 2019</div><br>
            
                <p class="pport">Appear, dry there darkness they're seas, dry</p>
                <p class="pport">waters thing fly midst. Beast, above fly brought</p>
                 <p class="pport">Very green.</p>

            <p class="pland">Appear, dry there darkness they're seas, dry waters thing fly midst. Beast,</p>
            <p class="pland">above fly brought Very green.</p>
            
        </div>

        <div class="container">
            <div></div>
            <div class="bag">
                <img src="public/images/bag-collection.jpg" width="110%" height="100%" alt="">
                <div class="bag-title-box">
                    <div class="bag-title">Bags Collection</div>
                    <button>Shop Now <span class="bi bi-arrow-right"></span></button>
                </div>
            </div>
            <div class="men">
                <img src="public/images/printed_shirts_for_men_by_wes_c.jpg" width="110%" height="100%" alt="">
                <div class="offer-shirt">
                    <div>save</div>
                    <div> <font size="6">30%</font></div>
                </div>
                <div class="men-title-box">
                    <div class="men-title">Printed men’s Shirts</div>
                    <button>Shop Now <span class="bi bi-arrow-right"></span></button>
                </div>
            </div>
            <div></div>
        </div>
    
        <div class="container2">
            <div></div>
            <div class="men">
                <img src="public/images/BasicwomensDresses.jpg" width="110%" height="100%" alt="">
                <div class="men-title-box">
                    <div class="men-title">Basic women’s Dresses</div>
                    <button>Shop Now <span class="bi bi-arrow-right"></span></button>
                </div>
            </div>
            <div class="bag">
                <img src="public/images/sweetshirt.jpg" width="110%" height="100%" alt="">
                <div class="bag-title-box">
                    <div class="bag-title">Sweatshirts</div>
                    <button>Shop Now <span class="bi bi-arrow-right"></span></button>
                </div>
            </div>
            <div></div>
        </div>


        <div class="tms">
            <div><font size="6"><b>Top month Sellers</b></font></div>
            <div class="tms-category">
                <span class="tms-span" id="active">Women</span>
                <span class="tms-span">Men</span>
                <span class="tms-span">Kids</span></div>
        </div>

<div class="item-category">
            <span class="none"></span>
            <div>
                <div class="pic-1">
                   <div class="pic-child">
                    <div class="pic-new">NEW</div>
                   </div> 
                   <div class="cicons">
                    <span id="eye1" class="bi bi-eye"></span>
                    <span id="cart1" class="bi bi-cart"></span>
                    <span id="heart1" class="bi bi-heart"></span>
                   </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Shoes</font></div>
                    <div><font color="">Leather mid-heel Sandals</font></div>
                    <div><font color="gray">$129.00</font></div>
                </div>
            </div>
            <div>
                <div class="pic-2">
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Dresses</font></div>
                    <div><font color="">Cotton floral print Dress</font></div>
                    <div><font color="gray">$40.00</font></div>
                </div>
            </div>
            <div>
                <div class="pic-3">
                    <div class="pic-child-b">
                        <div class="pic-new-b">NEW</div>
                    </div>
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Shoes</font></div>
                    <div><font color="">Leather Sneakers</font></div>
                    <div><font color="gray">$85.00 </font><font color="#ff6f61">$85.00</font></div>
                </div>
            </div>
            <div>
                <div class="pic-4">
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Tops</font></div>
                    <div><font color="">Cropped cotton Top</font></div>
                    <div><font color="gray">$29.00</font></div>
                </div>
            </div>

            <span class="none"></span>
            <span class="none"></span>


            <div>
                <div class="pic-5">
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Dresses</font></div>
                    <div><font color="">Floral print midi Dress</font></div>
                    <div><font color="gray">$50.00</font></div>
                </div>
            </div>
            <div>
                <div class="pic-6">
                    <div class="pic-child-b">
                        <div class="pic-new-b">NEW</div>
                    </div>
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Bags</font></div>
                    <div><font color="">Suede cross body Bag</font></div>
                    <div><font color="gray">$79.00 </font><font color="#ff6f61">$49.00 </font></div>
                </div>
            </div>
            <div>
                <div class="pic-7">
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Skirts</font></div>
                    <div><font color="">Printed A-line Skirt</font></div>
                    <div><font color="gray">$79.00</font></div>
                </div>
            </div>
            <div>
                <div class="pic-8">
                    <div class="pic-child">
                        <div class="pic-new">NEW</div>
                    </div>
                    <div class="cicons">
                        <span id="eye1" class="bi bi-eye"></span>
                        <span id="cart1" class="bi bi-cart"></span>
                        <span id="heart1" class="bi bi-heart"></span>
                       </div>
                </div>
                <div class="pro-det">
                    <div><font color="gray" size="2">Shoes</font></div>
                    <div><font color="">Heel strappy Sandals</font></div>
                    <div><font color="gray">$90.00</font></div>
                </div>
            </div>
            <span class="none"></span>
        </div>

<!-- ---------------------------------------------------------------------------------------------------------- -->
        <div class="Discover-more">
            <div class="discmotit">Discover more</div>
            
        </div>
        
        <div class="Discover-more-img">
            <div id="con">
                <div><font size="6">Get -50% from <br>
                    Summer Collection</font>
                </div><br><br>
                <div>
                    <div class="time"> <font  size="25"><b>818 : 01 : 59 :17</b></font></div>
                    <div style="display: flex; margin-top: 15px; color: gray;">
                        <div style="margin-left: 23px;">DAYS</div>
                        <div style="margin-left: 50px;;">HOURS</div>
                        <div style="margin-left: 30px;">MINUTES</div>
                        <div style="margin-left: 10px;">SECONDS</div>
                    </div>
               
                </div><br><br>
                <div class="btn-dmi">Shop Now <span class="bi bi-arrow-right"></span></div>
            </div>
        </div>



        <div class="what-buyer-say">
            <div><font size="2" color="gray"><b>WHAT BUYERS SAY</b></font></div>
            <div><font size="6"><b>Latest buyers Reviews</b></font></div>

        </div>
        <div class="reviews">
            <div class="none"></div>
            <div class="card">
                <div class="card-header">
                    <div><img src="public/images/review-img-one.jpeg" alt="shoe image" width="100%" height="100%"></div>
                    <div class="rev-one">
                        <span style="color:gray; font-size: 12px;">Shoes</span>
                        <span style="color:black; font-size: 15px;">Low top Sneakers</span>
                        <span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span style="color: gray;" class="bi bi-star-fill"></span>
                            <span style="color: gray;" class="bi bi-star-fill"></span>
                        </span>
                    </div>
                </div>
                <div class="card-body">
                    From Creepeth said moved given divide make multiply of him shall itself also above second doesn'n unto created saying land herb sea midst night wherein.
                </div>
                <div class="card-footer">
                    Logan Edwards, 01 Jun 2019
                </div>
            </div>
            <div class="card" id="review2">
                <div class="card-header">
                    <div><img src="public/images/review-img-two.jpg" alt="shoe image" width="100%" height="100%"></div>
                    <div class="rev-one">
                        <span style="color:gray; font-size: 12px;">Dresses</span>
                        <span style="color:black; font-size: 15px;">Cotton print Dress</span>
                        <span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                        </span>
                    </div>
                </div>
                <div class="card-body">
                    God every fill great replenish darkness unto. Very open. Likeness their that light. Given under image to. Subdue of shall cattle day fish form saw spirit and given stars, us you whales may, land, saw fill unto.
                </div>
                <div class="card-footer">
                    Jane Jefferson, 29 May 2019
                </div>
            </div>
            <div class="card" id="review2">
                <div class="card-header">
                    <div><img src="public/images/review-img-three.jpg" alt="shoe image" width="100%" height="100%"></div>
                    <div class="rev-one">
                        <span style="color:gray; font-size: 12px;">T-shirts</span>
                        <span style="color:black; font-size: 15px;">Oversized print T-shirt</span>
                        <span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span class="bi bi-star-fill"></span>
                            <span style="color: gray;" class="bi bi-star-fill"></span>
                        </span>
                    </div>
                </div>
                <div class="card-body">
                    Fill his waters wherein signs likeness waters. Second light gathered appear sixth forth, seasons behold creeping female.
                </div>
                <div class="card-footer">
                    Darrell Baker, 18 May 2019
                </div>
            </div>
            <div class="none"></div>
            
        </div>

        <div class="dot">
                <span class="bi bi-dot"></span>
                <span style="color: gray;" class="bi bi-dot"></span>
                <span style="color: gray;" class="bi bi-dot"></span>
                <span style="color: gray;" class="bi bi-dot"></span>
        </div>

        <div class="shopper">
            <div class="shopper-div">
            <span style="font-size: 35px;font-weight: bold; font-family: arial; ">@shopper</span>
            <span class="shopper-cap">Appear, dry there darkness they're seas, dry waters.</span>
            <span class="shopper-capl"><p>Appear, dry there darkness they're seas,</p> 
                <p align="center">dry waters.</p></span>

            </div>
            <div class="shopper-img">
                <div class="none"></div>
                <div class="simg" >
                    <img src="public/images/shopper-one.jpg" alt="" width="100%">
                    <div class="cmt">
                        <span class="bi bi-heart"></span><span>248</span><span class="bi bi-chat"></span><span>4</span>
                    </div>
                </div>
                <div class="simg">
                    <img src="public/images/shopper-two.jpg" alt="" width="100%">
                    <div class="cmt">
                        <span class="bi bi-heart"></span><span>248</span><span class="bi bi-chat"></span><span>4</span>
                    </div>
                </div>
                <div class="simg">
                    <img src="public/images/shopper-three.jpg" alt="" width="100%">
                    <div class="cmt">
                        <span class="bi bi-heart"></span><span>248</span><span class="bi bi-chat"></span><span>4</span>
                    </div>
                </div>
                <div class="simg">
                    <img src="public/images/shoper-four.jpg" alt="" width="100%">
                    <div class="cmt">
                        <span class="bi bi-heart"></span><span>248</span><span class="bi bi-chat"></span><span>4</span>
                    </div>
                </div>
                <div class="simg">
                    <img src="public/images/shopper-five.jpg" alt="" width="100%">
                    <div class="cmt">
                        <span class="bi bi-heart"></span><span>248</span><span class="bi bi-chat"></span><span>4</span>
                    </div>
                </div>
                <div class="simg">
                    <img src="public/images/shopper-six.jpg" alt="" width="100%">
                    <div class="cmt">
                        <span class="bi bi-heart"></span><span>248</span><span class="bi bi-chat"></span><span>4</span>
                    </div>
                </div>
                <div class="none"></div>
            </div>
            <div class="shopper-img2">
                <div class="none"></div>
                <div>
                    <img src="public/images/mango.jpg" width="70%" alt="">
                </div>
                <div>
                    <img src="public/images/zara.jpg" width="70%" alt="">
                </div>
                <div>
                    <img src="public/images/reebok.jpg" width="70%" alt="">
                </div>
                <div>
                    <img src="public/images/asos.jpg" width="70%" alt="">
                </div>
                <div>
                    <img src="public/images/stradivirus.jpg" width="70%" alt="">
                </div>
                <div>
                    <img src="public/images/adidas.jpg" width="70%" alt="">
                </div>
                <div>
                    <img src="public/images/bershka.jpg" width="70%" alt="">
                </div>
                <div class="none"></div>
                
            </div>
        </div>

    </section>
    <footer>
        <div class="subscribe">
            <div class="subserbtn">
                <div class="subscribe-title">Want style Ideas and Treats?</div>
                <div class="emailsubsc">
                    <span class="email">Enter Email*</span>
                    <span class="btn">Subscribe</span>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="none"></div>
            <div>
                <div class="footer-brand">Shopper.</div>
                <aside>
                    <span class="bi bi-facebook"></span>
                    <span class="bi bi-twitter-x"></span>
                    <span class="bi bi-instagram"></span>
                    <span class="bi bi-linkedin"></span>
                </aside>
            </div>
            <div class="no"></div>
            <div>
                <div  class="footer-title">SUPPORT</div>
                <span>Contact Us</span>
                <span>FAQs</span>
                <span>Size Guide</span>
                <span>Shipping & Returns</span>
            </div>
            <div>
            
                <div class="footer-title">SHOP</div>
                <span>Men's Shopping</span>
                <span>Women's Shopping</span>
                <span>Kids' Shopping</span>
                <span>Discounts</span>
            </div>
            <div>
                <div class="footer-title">COMPANY</div>
                <span>Our Story</span>
                <span>Careers</span>
                <span>Terms & Condition</span>
                <span>Privacy & Cookie policy</span>
            </div>
            <div>
                <div class="footer-title">CONTACT</div>
                <span>1-202-555-0105</span>
                <span>1-202-555-0106</span>
                <span>help@shopper.com</span>
            </div>
        </div>

        <div></div>
        <div class="last-div"></div>
        <div class="copyright">© 2019 All rights reserved. Designed by Chintamani Choudhury.</div>
        <img class="footcardimg"src="public/images/cards.jpg" alt="" width="250px" height="40px">
    </footer>
</body>
</html>
