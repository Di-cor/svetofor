<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Box traffic Lights</title>
    <style>
        #light{
            width: 100px;
            background-color: #333;
            height: 320px;
            border-radius: 5px;
	        font-size: 70px;
	        text-align:center;
	        padding: 1px 0px 1px 0px;
	        border: 6px;
            margin: auto;
        }        
        #light .red{
            width: 80px;
            height: 80px;
            background-color: red;
            border-radius: 50%;
	        margin-left: 10px;
	        margin-top: 20px;
        }
        #light .yellow{
           width: 80px;
           height: 80px;
           background-color: yellow;
           border-radius: 50%;
	       margin-left: 10px;
	       margin-top: 20px;
        }
        #light .green{
           width: 80px;
           height: 80px;
           background-color: green;
           border-radius: 50%;
	       margin-left: 10px;
	       margin-top: 20px;
        }
    </style>
</head>
<body>
    
    <div id="light">
        <div class="red"></div>
        <div class="yellow"></div>
        <div class="green"></div>
    </div>

</body>
</html>
