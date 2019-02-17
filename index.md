<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>Login (Book Management)</title>
	<script type="text/javascript" language="javascript">
		<!--
function click(){        
        var flagNULL=0;
        if(document.form1.field1.value==""){
            flagNULL=1;
        }
        else if(document.form1.field2.value==""){
            flagNULL=1;
        }

        var flagERROR=0;
        if(document.form1.field1.value!="user"){
            flagERROR=1;
        }
        else if(document.form1.field2.value!="password"){
            flagERROR=1;
        }
	
	if(flagNULL){
	window.alert('User_ID、またはPasswordは必ず記入してください。');
	}
	else if(flagERROR){
	window.alert('User_ID、またはPasswordが間違っています。');
	}
	else{ location.href = "https://takajo-soft08.github.io/Create/MainPage/";}
	}
	-->
	  </script>
  </head>

  <body>
    <div align="center">
      <h1>Log_In (Book Management)</h1>
    </div>
	
		
    <div align="right">
      <input type="submit" value="新規登録" onClick="Subsclibe()">
    </div>
	
    <script>
      function Subsclibe(){
       location.href = "https://takajo-soft08.github.io/Create/SignUp/";      
      }
    </script>
    
    <hr>
   <div align="center">
    <form name="form1">
	    <p>User_ID :
	    <input name="field1" type="text" value=""></p>
	    <p>Password:
	    <input name="field2" type="password" value=""></p>
	    <p><input type="button" value="Enter" onClick="click()"></p>
	</form>
	</div>
  </body>
</html>
