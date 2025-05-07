<!DOCTYPE html>
<html>
   <head>
     <style>
         body{
         background-image:url(./jinjia.png);
         background-size:cover;
         }
         #omikujihako{
             position:relative;
             cursor:pointer;
         }
    </style>
     </head>
    <body>
            <script type="text/javascript">
            myImage = new Array(
            "./daikichi.png",
            "./chukichi.png",
            "./shokichi.png",
            "./kyo.png"
            );

            function myChange(){
                 myRnd = Math.floor( Math.random() * myImage.length );
                 document.kuji.src = myImage[myRnd];
            }
            </script>
            <img src="omikujihako.png" border="0" name="kuji">
            <form>
            <input type="button" value="choose" onclick="myChange()">
            </form>
        </script>
    </body>
</html>
