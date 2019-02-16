<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>Login (Book Management)</title>
	<script type="text/javascript" language="javascript">
		function onButtonClick(){
		target1=document.getElementById("output1");
		target1.innerText=document.forms.id_form1.id_textBox1.value;
		target2=document.getElementById("output2");
		target2.innerText=document.forms.id_form1.id_textBox2.value;
		if(target1.innerText != "" && target2.innerText != "")
		{
		if(target1.innerText == "user" && target2.innerText == "password")
		location.href = "https://takajo-soft08.github.io/Create/MainPage/";
		else window.alert('User_ID、またはPasswordが間違っています。');
		}
		else window.alert('User_ID、またはPasswordは必ず記入してください。');
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
    <form name="form1" id="id_form1" action="">
	    User_ID :
	    <input name="textBox1" id="id_textBox1" type="text" value="" /><br>
	    Password:
	    <input name="textBox2" id="id_textBox2" type="text" value="" /><br>
	    <input type="button" value="Enter" onClick="onButtonClick();"/>
	</form>
	<div id="output1"></div>
	<div id="output2"></div>
	</div>
  </body>
</html>
