<!DOCTYPE html>

<html>
    <head> 
        <style>
            input{
                width: 300px;
                font-size: 20px;
            }
            button{
                width: 230px;
                font-size: 20px;
            }
            .button_div{
                margin-top: 10px;
            }
            #container{
                padding: 10px;
                margin: 10px;
            }
        </style>
    </head>

    <body>
        <div id="container">
            <div class="input_div">
                <input placeholder="Enter the value of X" id="num1"/>
                <input placeholder="Enter the value of Y" id="num2"/>
                <input placeholder="Result will appear here" id="res"/>
            </div>

            <div class="button_div">
                <button onclick="add()">Addition (X + Y)</button>
                <button onclick="subtraction()">Subtraction (X - Y)</button>
                <button onclick="multiplication()">Multiplication (X * Y)</button>
                <button onclick="Division()">Division (X / Y)</button>
            </div>            
        </div>
        <script>
            function add(){
                let x = parseInt(document.getElementById("num1").value);
                let y = parseInt(document.getElementById("num2").value);
            let res = x+y;
            document.getElementById("res").value = res;
            }
            
            function subtraction(){
                let x = parseInt(document.getElementById("num1").value);
                let y = parseInt(document.getElementById("num2").value);
            let res = x-y;
            document.getElementById("res").value = res;
            }

            function multiplication(){
                let x = parseInt(document.getElementById("num1").value);
                let y = parseInt(document.getElementById("num2").value);
            let res = x*y;
            document.getElementById("res").value = res;
            }
            function Division(){
                let x = parseInt(document.getElementById("num1").value);
                let y = parseInt(document.getElementById("num2").value);
            let res = x/y;
            document.getElementById("res").value = res;
            }
            

        </script>

    </body>
</html>
