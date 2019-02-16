<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>Login (Book Management)</title>
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
      location.href = "file:///Network/Servers/iemac.ie.tokuyama.ac.jp/Volumes/Users/15/i15kasibe/_CreativePractice_/SignUp/signup.html";      
      }
    </script>
    
    <hr>
    <div align="center">
      <table border="0">
        <form action="list.html" method="get"></form>
        <tbody>
	  <tr>
            <th>
              User_ID:
            </th>
            <td>
              <input type="text" name="user_id" value="" size="24">
            </td>
          </tr>
          <tr>
            <th>
              Password:
            </th>
            <td>
              <input type="password" name="password" value="" size="24">
            </td>
          </tr>
          <tr>
            <td colspan="2" align="center">
              <input type="submit" value="Enter" onClick="mainJump()">
	      <script>
		function mainJump(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/";
		}
	      </script>            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </body>
</html>
      <!--
	  if (confirm("Sign Up")==true) 
	  location.href = "file:///Network/Servers/iemac.ie.tokuyama.ac.jp/Volumes/Users/15/i15kasibe/_CreativePractice_/SignUp/signup.html";
	-->
