# rankingi
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>rankingi.pl</title>
        <style>
      
        body{
         color: white; 
    background: #396f38;
    margin: 0;
    font-family: Arial;
    
        }
       .menu-1{
           background: white;
           top: 0px;
           width: 100%;
           height: 70px;
           position: absolute;
           font-family: Arial;
           float: left;
          left: 0px;
          z-index: 3;
       }
       #aut{
        
         color: green;  
       }
      #klik{
         color: grey; 
      }
      
     
      
      #lokiter{
          z-index: 2;
          background-color: #4e9447;
          position: absolute;
          top:300px;
          right: 0px;
         left: 0px;
         font-size: 20px;
         text-align: center;
      }
      #akt{
          border-bottom:1px solid white;
          text-align: center;
      }
   
      #img {
       position: fixed;
       z-index: 1;
      height: 300px;
      bottom: 0px;
       top: 0px;
       width: 100%;
       right: 0px;
       left: 0px;
       }
    .nav{
           
           position: absolute;
           text-align: right;
           color: black;
           height: 30px;
           line-height: 30px;
           right: 0px;
           top: 10px;
           z-index: 4;
       }
       .menu{
         margin-right: 30px;  
       }
       .menu a{
           clear: right;
           text-decoration: none;
           color: black;
           position: relative;
           line-height: 40px;
           margin-right: 30px; 
       }
       label{
           position: absolute;
           font-size: 26px;
           line-height: 40px;
           display: none;
           width: 26px;
           right: 10px;
           
       }
       #toggle{
           display: none;
           top: 10px;
           right: 10px;
       }
       
       
       
       @media only screen and (max-width: 500px){
         label{
          
           
          
           display: block;
           cursor: pointer;
}  
         .menu{
           display: none;
           text-align: center;
           width: 500px;
          position: relative;
          top: 25px;
          right: 0px;
          left: 0px;
           margin-right: 0px;
}
         .menu a{
           display: block;
           width: 500px;
           text-decoration: none; 
           border-bottom: 1px solid black;
           margin: 0;
           color: black;
           background-color: white;
           top: 25px;
           right: 0px;
           left: 0px;
            text-align: center;
          }
          
          #toggle:checked + .menu {
          display: block;
}
       }
       a:hover{
          background-color: red;
          color: white;
       }
       a:active{
          background-color: red;
           color: white;
       }
       table {
       color: black;
       }
       #title {
       font-size: 40px;
       }
       .king {
       color: yellow;
       }
       #king-thing {
       left-margin: auto;
       right-margin: auto;
       top: 40px;
       position: relative;
       width: 40px;
       height: 40px;
       }
        </style>
    </head>
    <body>
    <div class="menu-1">
    
        <p><span id="aut"><strong>Autor:</strong></span><span id="klik"><em><strong> JAKUB<BR>WITKOWSKI</strong></em></span></p>
         </div>
         <div class="nav"> 
         <label for="toggle">&#9776;</label>
         <input type="checkbox" id="toggle">
         <div class="menu">
      <a href="https://witas-w.github.io/Aktualnosci/">Aktualności</a>
            <a href="https://witas-w.github.io/Bloguje-witas/">Blog</a>
            <a href="https://witas-w.github.io/Galeria-zdjec/">Zdjęcia</a>
            <a href="https://witas-w.github.io/Ranking/">Rankingi</a>
     </div>  
        
     </div>   
        
         
<img id="img" src="https://s6.ifotos.pl/img/IMG6219JP_qswwpha.jpg">
        
        <div id="lokiter">
        <img id="king-thing" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Crown_of_Italy.svg/200px-Crown_of_Italy.svg.png">
      <h2 id="title">Ran<strong><span class="king">KING</span></strong>i</h2>
      
      <h2>Mój ranking restauracji</h2>

<table>
   <thead>
       <tr>
           <th>Miejsce</th>
           <th>Nazwa</th>
           <th>punkty</th>
       </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>U Przyjaciół</td>
            <td>100/100</td>
        </tr>
         <tr>
            <td>2</td>
            <td>Syrenka</td>
            <td>98/100</td>
        </tr>
         <tr>
            <td>3</td>
            <td>Columbus</td>
            <td>95/100</td>
        </tr>
         <tr>
            <td>4</td>
            <td>Krzywy Róg</td>
            <td>93/100</td>
        </tr>
         <tr>
            <td>5</td>
            <td>Al Dente</td>
            <td>90/100</td>
        </tr>
         <tr>
            <td>6</td>
            <td>Szybka Rybka</td>
            <td>85/100</td>
        </tr>
         <tr>
            <td>7</td>
            <td>Laguna</td>
            <td>69/100</td>
        </tr>
    </tbody>
  </table>
   <h2>Mój ranking lodów</h2>
   <table>
    <thed>
       <tr>
           <th>Miejsce</th>
           <th>Nazwa</th>
           <th>Punkt</th>
        </tr>
       
    </thed>
    <tbody>
    <tr>
    <td>1</td>
    <td>Bacio</td>
    <td>100/100</td>
    </tr>
     <tr>
    <td>2</td>
    <td>Góra Lodowa</td>
    <td>97/100</td>
    </tr>
     <tr>
    <td>3</td>
    <td>U Lodziarzy</td>
    <td>95/100</td>
    </tr>
     <tr>
    <td>4</td>
    <td>Wenta</td>
    <td>90/100</td>
    </tr>
     <tr>
    <td>5</td>
    <td>Chomczyńscy</td>
    <td>20/100</td>
    </tr>
    </tbody>
    </table>
    <h2>Mój ranking gofrów</h2>
    <table>
        <thead>
            <tr>
                <th>Miejsce</th>
                <th>Nazwa</th>
                <th>Punkty</th>
            </tr>
        </thead>
        <tbody>
            <tr>
               <td>1</td>
                <td>Bar 3 molo</td>
                <td>100/100</td>
            </tr>
            <tr>
                <td>1</td>
                <td>Chomczyńscy</td>
                <td>100/100</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Lody,Gofry</td>
                <td>87/100</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Kołacze,Gofry,Lody</td>
                <td>76/100</td>
            </tr>
        </tbody>
    </table>
 </div>
       
   
 
    </body>
</html>
