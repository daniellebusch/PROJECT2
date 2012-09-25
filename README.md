PROJECT2
========

project 2 - comp sci
<!DOCTYPE HTML>
<html>
   <!-- Danielle Busch
   September 24, 2012
	 Introduction to Programming
	 Project 2 -->
   <head>
	  <title>Off To The Races</title>
	  <style>
	      body {background-color:purple;}
	  </style>
      <script type="text/JavaScript">
      				var hasVisitedDestination1= false;
					var hasVisitedDestination2= false;
					var hasVisitedDestination3= false;
					var hasVisitedDestination4= false;
					var score= 0;
         function Destination1 () {
               var msg = "You arrive at the beautiful California coast.";
               alert(msg);
               if (!hasVisitedDestination1) {
					score=score+5;
					hasVisitedDestination1=true;
                  }
    	  }
    	  
    	  function Destination2 () {
               var msg = "You have reached a dead end.";
               alert(msg);  
               if (!hasVisitedDestination2) {
					score=score+5;
					hasVisitedDestination2=true;
                  }
    	  }             
    	  
    	  function Destination3 () {
           	   var msg =  "Uh oh! Down in the ditch you go!";
           	   alert(msg);
           	   if (!hasVisitedDestination3) {
					score=score+5;
					hasVisitedDestination3=true;
                  }
    	  }
    	  
    	  function Destination4 () {
           	   var msg = "Smooth ride, keep driving!";
           	   alert(msg);
           	   if (!hasVisitedDestination4) {
					score=score+5;
					hasVisitedDestination4=true;
                  }
    	  }
         
          function Totalscore () {
               alert(score);
          }
      </script>
	</head>
	<body>
		<font color="FFFFFF">OFF TO THE RACES!!</font>
		<br>
		<br>
		<font color="81F781">Welcome to my text-adventure game
		<br>
		where you can either sight-see across the country,
		<br>
		or end up at a dead end.
		<br>
		On your mark, get set, GO!</font>
		<br>
		<br>
		<textarea id="taGame" rows="8" cols="40">You are at the NASCAR headquarters.
        </textarea>
        <p class="bottom">
    		<a href="mailto:Danielle.Busch1@marist.edu">E-mail Link</a>
	    </p>
        <br>
        <input value="North"
               onclick="Destination1 ();"
               type="button">

      <input value="East"
             onclick="Destination2 ();"
             type="button">
             
      <input value="South"
             onclick="Destination3 ();"
             type="button">
             
      <input value="West"
             onclick="Destination4 ();"
             type="button">
             
      <input value="Score"
             onclick="Totalscore ();"
             type="button">
    </body>
</html>
	