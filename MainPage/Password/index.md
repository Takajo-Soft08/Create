<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>SignUp (Book Management)</title>
  </head>

  <body>
    <div align="center">
      <h1>パスワード変更画面</h1>
    </div>
    
    <hr>
    <div align="center">
      <table border="0">
        <form action="list.html" method="get"></form>
        <tbody>

	    
	  <tr>
            <th>
              Old_Password(Old):
            </th>
            <td>
              <input type="text" name="user_id" value="" size="24">
            </td>
          </tr>
          <tr>
            <th>
              New_Password (New):
            </th>
            <td>
              <input type="password" name="password" value="" size="24">
            </td>
          </tr>
          <tr>
            <th>
              New_Password (Again):
            </th>
            <td>
              <input type="password" name="password" value="" size="24">
            </td>
          </tr>
	  <!--
	  <tr>
            <td colspan="2" align="center">
              <input type="submit" value="Enter">
            </td>
	  </tr>
	  -->
          <tr>
            <td colspan="2" align="center">
              <input type="submit" value="Enter" onClick="verify()">
	      <script>
		function verify(){
		location.href = "https://takajo-soft08.github.io/Create/SignUp/SignUpVerify/";
		}
	      </script>
            </td>
          </tr>
        </tbody>
      </table>
    </div>

    <div align="right">
      <a href="https://takajo-soft08.github.io/Create/">_Back_To_Home_</a>
    </div>

  </body>
</html>

