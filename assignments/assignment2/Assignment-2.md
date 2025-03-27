* {
     box-sizing: border-box;
     margin: 0;
     padding: 0;
   }
   
   body {
     font-family: Arial, sans-serif;
     font-size: 16px;
     line-height: 1.5;
   }
   
   h1 {
     text-align: center;
     margin: 20px 0;
     font-size: 1.75em;
   }
   
   .container {
     padding: 15px;
   }
   
   .section {
     position: relative;
     background-color: #f4f4f4;
     border: 1px solid black;
     margin: 15px;
     padding: 40px 15px 15px 15px;
     float: left;
   }
   
   .section-title {
     position: absolute;
     top: 0;
     right: 0;
     padding: 5px 10px;
     border: 1px solid black;
     font-size: 1.25em;
   }
   
   
   @media (min-width: 992px) {
     .section {
       width: calc(33.33% - 30px);
     }
   }
   
  
   @media (min-width: 768px) and (max-width: 991px) {
     #chicken, #beef {
       width: calc(50% - 30px); 
     }
     #sushi {
       width: calc(100% - 30px); 
     }
   }
   
  
   @media (max-width: 767px) {
     .section {
       width: calc(100% - 30px); 
     }
   }
   
   
   #chicken {
     background-color: #808080;
   }
   
   #beef {
     background-color: #808080; 
   }
   
   #sushi {
     background-color: #808080; 
   }
   
   
   #chicken .section-title {
     background-color: #997596; 
   }
   
   #beef .section-title {
     background-color: #ae2727; 
   }
   
   #sushi .section-title {
     background-color: #b9aa29; 
   }
<!DOCTYPE html>
 <html lang="en">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Module 2 Solution</title>
   <link rel="stylesheet" href="css/styles.css">
 </head>
 <body>
   <h1>Our Menu</h1>
 
   <div class="container">
     <section class="section" id="chicken">
       <div class="section-title">Chicken</div>
       <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
     </section>
 
     <section class="section" id="beef">
       <div class="section-title">Beef</div>
       <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
     </section>
 
     <section class="section" id="sushi">
       <div class="section-title">Sushi</div>
       <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
     </section>
   </div>
 </body>
 </html>
