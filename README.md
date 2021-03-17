# Astro-Test
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            
        }
        
        .wrap{
            width: 2000px;
            background-color:#aaa;
            display: flex; 
            flex-wrap: wrap;
        }
        .col{
            width:350px; 
            margin: 20px;
            border: 5px solid white;
            height: 400px;
            background-color: #faa;
            font-size: 30px;
            
            /* 規格設定要由上往下讀 */
        }
        .box { 
            width: 100%;
            height: 250px;
            align-content: center;
        }
        img {
            /* object-fit: contain; */
            width: 100%;
            height: 100%;
        }      
        </style>

</head>
<body>
    
<body>
   
   <div class="wrap">
       <div class="col">
           <div class="box">
            <img src="https://picsum.photos/id/684/600/400" alt="">
           </div >
            <h2>title</h2>
            <p>健康公里傷害報導一天一本，妻子加上，無。</p>
       </div>

       <div class="col">
           <div class="box">
                <img src="https://upload.wikimedia.org/wikipedia/commons/b/b1/VAN_CAT.png" alt="">
            </div>
        <h2>title1</h2>
        <p>健康公里傷害報導一天一本，妻子加上，無。</p>
    </div>

    <div class="col">
         <div class="box">
             <img src="https://upload.wikimedia.org/wikipedia/commons/b/b1/VAN_CAT.png" alt="">
        </div>
        <h2>title1</h2>
        <p>健康公里傷害報導一天一本，妻子加上，無。</p>
    </div>

    <div class="col">
        <div class="box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/b/b1/VAN_CAT.png" alt="">
        </div>
        <h2>title1</h2>
        <p>健康公里傷害報導一天一本，妻子加上，無。</p>
    </div>
    <div class="col">
        <div class="box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/b/b1/VAN_CAT.png" alt="">
        </div>
        <h2>title1</h2>
        <p>健康公里傷害報導一天一本，妻子加上，無。</p>
    </div>
    
           
           <!-- 理解>>>熟悉>>>快速 -->
   </div> 

</body>
</html>
