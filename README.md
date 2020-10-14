<!IDOCTYPE HTML >
<HTML>
<head>
<meta charset="utf-8">
<title>module 2 assignment</title>
<style>
*{ 
 box-sizing: border-box; 
font-family: Cambria , Cochin, Georgia,Times, 'Times New Roman', Serif}
.box { 
      float: right; 
      width: 33.33%;
      padding: 50px;
    }

h1 { 
   margin-bottom: 15px;
   color:blue ;
   font font-size: 175%;

  }
   section {
          border: 1px solid black;
          background-color: bisque;
          height :250px;
          overflow: auto;
   }
   h2{ 
      float: right;
      border: 1px solid black;
      color: lavender;
      font-size: 125%
      padding : 5px 20 px 5px 20px;
      margin-top: 0;
      margin-bottom: 20px;
       }
  ul  {
      clear: right;
      width: 90%;
  }
#chicken { background-color: darkorchid; }
#pork { background-color: brown; }
#steak { background-color: forestgreen; } 
@media(min-width: 992px)
      {.col-1g-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6,
       .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 
       { float: left;
        padding: 15px;
       }
       .col-lg-1 { width: 8.33%; }
       .col-lg-2 {width: 16.66%;} 
       .col-lg-3 {width: 25%;}
       .col-lg-4 {width: 33.33%;}
       .col-lg-5 {width: 41.66%;}
       .col-lg-6 {width: 50%;}
       .col-lg-7 {width: 58.33%;}
       .col-lg-8 {width: 66.66%;}
       .col-lg-9 {width: 75%;}
       .col-lg-10 {width: 83.33%;}
       .col-lg-11 {width: 91.66%;}
       .col-lg-12 {width: 100%;}
       }
</style>
</head>
<body>
  <h1> Our Menu </h1>
   <div class="col-lg-4 col-md-6 col-sm-12">
    <section>
  <h2 id="chicken">Chicken</h2>
   <ul> 
    <li> Balsamic Roasted Brussels Sprouts, Butternut Squash and Chicken Thighs </li>
    <li>Prosciutto-Wrapped Chicken with Garlic and Herb Cheese</li>
    <li>Siri Pinter's one-pot Chicken Alferado </li>
    <li>Florentine Penne with Chicken </li>
    <li>Garlic bread Chicken Nuggets with Balsamic Ketchup</li>
    </ul>
     </section>
   </div>
   <div class="col-lg-4 col-md-6 col-sm-12">
     <section>
    <h2 id="pork"> Pork </h2>
    <ul>
     <li> Pork Cheek  and Black-Eyed Pea Chilli</li>
     <li> Braisded pork with Cherry Gravy </li>
     <li> Aleppo-Pepper-Pork-and-Funnel SAndwiches </li>
     <li> Herb-Roasted Pork Subs with Garlicky Spinach </li>
     <li> Chinese-style with Guava Barbecue Sauce </li>
     <li> Pork Medallions with Onion Marmalade</li>
    </ul>
      </section>
   </div>
   <div class=" col-lg-4 col-md-12 col-sm-12 ">
    <section>
      <h2 id="steak"> Steak </h2>
    <ul>
      <li> Butter-Basted Rib Eye Steaks </li>
      <li> Balsamic Marinated Flank Steak </li>
      <li> Grilled Hanger Steak with Kimchi-Apple Slaw</li>
      <li> Throwback Porterhouse Steaks</li>
     <li> Minute Steak Stacks with Herbed Anchovy Butter </li>
    </ul>
    </section>
    </div>
</body>
</html>
