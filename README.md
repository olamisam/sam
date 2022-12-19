<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>keyframes</title>
    <style>
        body{
            background: #333;
        }
        .box{
            width: 200px;
            height: 200px;
            background: #fff;
            animation: sam;
            animation-duration: 9s;
            animation-fill-mode: forwards;
            animation-iteration-count: infinite;
            transition-property: all;
            position: relative;
        }

        @keyframes sam{
            0%{ background: red;
                left: 0px;
                top: 0px;
                border-radius: 0 0 0 0;
            }
            
            25%{ background: rgb(188, 124, 124);
                left: 300px;
                top: 0px;
            
                border-radius: 50% 0 0 0;
                
                
            }
            50%{ background: blue;
                top: 300px;
                left: 300px;

            border-radius: 50% 50% 0 0;}
            75%{
                background-color: aqua;
                left: 0px;
                top: 300px;
                border-radius: 50% 50% 50% 0;
            }
            
            100%{background: green;
                left: 0px;
                top: 0px;
                
            border-radius: 50%;}
        }
    </style>
</head>
<body>
    <div class="box"></div>
</body>
</html>
