# Application_Global_Loader
Application Global Loader


step 1 : Add Common JS File:

        $(window).load(function () { 
           $("#preloaderBox").fadeOut("slow"); 
           });

Step 2: Add html code in start of Body

       <div id="preloaderBox" class="Preloader" style="display: none;"></div> 
 
 Step 3: Add css in common css file:
 
         #preloaderBox { position: fixed; left: 0px; top: 0px; width: 100%; height: 100%; z-index: 9999; background: url("../images/Preloader_2.gif") center no-repeat #fff; background-size: 55px; }
