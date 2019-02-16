<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>SignUp (Book Management)</title>
  </head>

  <body>
    <div align="center">
      <h1>Sign_Up</h1>
    </div>
    
    <hr>
    <div align="center">
      <table border="0">
        <form action="list.html" method="get"></form>
        <tbody>

	  <tr>
	    <script type="text/javascript"> 
	      function setEditEnable(strName, boolEnable){ 
	      var elm = document.getElementsByName(strName).item(0);
	      elm.disabled = !boolEnable;
	      if (boolEnable) {
	      elm.value = ""; <!-- "入力可";-->
	      } else {
	      elm.value = "_You_Are_Parent. (入力不可)";
	      }
	      } 
	    </script> 
	    
	    <form action="" name="form1">
	      <p>
		<input type="checkbox" name="chk1" onclick="setEditEnable('edt1', this.checked)" />
		_Are_you_Child?_ (これをチェックすると下の入力欄が有効になる)
	      </p>
	      <p> Parent_User_ID:
		<input type="text" name="edt1" value="Parent_ID(初期値)" disabled="disabled" /></p>
	    </form>
	  </tr>
	    
	  <tr>
            <th>
              New_User_ID:
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
