
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My web</title>
    <style>
        .Vistor {
            background-color: rgb(11, 143, 204);
            margin-bottom: 20px;
        
        }
        
        .Student {
            background-color: rgb(231, 55, 31);
        }
        
		.Vistor img{
            width: 50px;
        	height: 50px;
            position: absolute;
        	text-align: center;
        }
        .Student img {
            width: 50px;
        	height: 50px;
            position: absolute;
        	text-align: center;
        }
		#text1 {
		    position: absolute;
		    left: -1px;
		    width: 200px;
		    height: 70px;
		    text-align: center;
		    line-height: 20px;
		    transition: opacity 1s;
		    color: white;
		}
		
		#text2 {
		    position: absolute;
		    left: -1px;
		    width: 200px;
		    height: 70px;
		
		    text-align: center;
		    line-height: 20px;
		    transition: opacity 1s;
		    color: white;
		}
		.Vistor,
		.Student {
		    width: 50px;
		    height: 50px;
		    position: relative;
		    transition: padding 1s;
		    overflow: hidden;
		}
		
		.Vistor:hover {
		    padding-left: 180px;
		}
		
		.Student:hover {
		    padding-left: 180px;
		}
		
      
    </style>
</head>

<body>
    <div>
        <div class="Vistor">
            <p id="text1"> 访客 Vistor</p>
            <img src="./img/1.png" >
        </div>
        <div class="Student">
            <p id="text2"> 学生 Student</p>
            <img src="./img/2.png" >
        </div>
    </div>
</body>
</html>
