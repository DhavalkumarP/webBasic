<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>js1</title>
    <!-- 1  -->
        <script>
        function myfunc(){
            document.getElementById('para').innerHTML='paragraph Changed';
        }
    </script>
</head>
<body>
    


    <!-- for printing the page -->
    <h2>the window.print() method</h2>
    <p>to print current page</p>
    <button type="button" onclick="window.print()">print</button>

    <!-- to display in console -->
    <h1>console.log function</h1>
    <p>this para define me</p>
    <p>f12 on your keyboard will activate debugging</p>
    <p>then select console in the drbugger menu.</p>
    <p>then click run agin</p>
    <script>
        console.log("hello world");
    </script>

    <!-- alert box -->
    <h1>alert box</h1>
    <p>alert para</p>
    <script>
        window.alert('red warning');
    </script>

    <!-- document.write()func for write output -->
    <h1>document.write</h1>
    <p>my first paragraph</p>
    <script>
        document.write(5+6);
        document.write("hello world");
    </script>

    <!-- externel js2 -->
    <script src="script.js"></script>
    <h1>webpage</h1>
    <p id="funcId">my view</p>
    <button type="button" onclick="myjsfunc()"> click me</button>
    
    <!-- internal js1 -->
    <h1>my webpage</h1>
    <p id="para">paragraph</p>
    <button type="button" onclick="myfunc()">try it</button>

    <!-- use script tage in body -->
    <p id="text"></p>
    <script>
        document.getElementById('text').innerHTML="my name is dhaval";
    </script>

    <!-- show hidden elements -->
    <p>java script can show hidden elements</p>
    <p id="show" style="display: none;">my text</p>
    <button type="button" onclick="document.getElementById('show').style.display='block'">click me</button>

    <!-- hide html elements  -->
    <p id="hide">my text </p>
    <button type="button" onclick="document.getElementById('hide').style.display='none'">click to hide text</button>

    <!-- increas font size -->
    <p id="font">this is font</p>
    <button type="button" onclick="document.getElementById('font').style.fontSize='39px'">click to increas font size</button>

    <!-- bulb on off -->
        <button type="button" onclick="document.getElementById('bulb').src='program_img/pic_bulboff.gif'"> turn off bulb </button>
    <img id="bulb" src="program_img/pic_bulboff.gif" alt="bulboff" style="width: 100px;">
    <button type="button" onclick="document.getElementById('bulb').src='program_img/pic_bulbon.gif'"> turn on bulb </button>

    
    <h1 id="demo">click to button for show name</h1>
    <button  types="button" onclick="document.getElementById('demo').innerHTML='demo'">click me</button> 


    <h1>date and time</h1>
    <button onclick="document.getElementById('demo').innerHTML = Date()">click me</button>
    <p id='demo'></p>
</body>
</html>
