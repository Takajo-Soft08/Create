
<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>MainPage (Book Management)</title>
  </head>

  <body>
    <div align="center">
      <h1>Main_Page_PARENT_VERSION (Book Management)</h1>
    </div>
    
    <div align="right">
      <input type="submit" value="ログアウト" onclick="logOut()">
    </div>
    <script>
      function logOut(){
      location.href = "https://takajo-soft08.github.io/Create/";      
      }
    </script>
    
    <hr>
    <div align="center">
      <table border="0">
        <form action="list.html" method="get"></form>
        <tbody>
	  
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="貸出処理" onclick="rend()">
	      </div>
	      <script>
		function rend(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Lend/";      
		}
	      </script>     
            </td>
	    <th>
	      図書の貸出を行います。
	    </th>
	  </tr>
	  
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="返却処理" onclick="rend1()">
	      </div>
	      <script>
		function rend1(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Return/";      
		}
	      </script>     
            </td>
	    <th>
	      図書の返却を行います。
	    </th>
	  </tr>

	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="予約処理" onclick="booking()">
	      </div>
	      <script>
		function booking(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Booking/";      
		}
	      </script>     
            </td>
	    <th>
	      貸出中の図書の予約を行います。
	    </th>
	  </tr>
	  
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="登録図書一覧" onclick="list1()">
	      </div>
	      <script>
		function list1(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/List/";
		}
	      </script>     
            </td>
	    <th>
	      登録されている図書の一覧になります。
	    </th>
	  </tr>
	  
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="貸借履歴" onclick="record()">
	      </div>
	      <script>
		function record(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Record/";      
		}
	      </script>     
            </td>
	    <th>
	      これまでに貸借した本の一覧になります。
	    </th>
	  </tr>
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="パスワード変更" onclick="rend1w()">
	      </div>
	      <script>
		function rend1w(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Password/";      
		}
	      </script>     
            </td>
	    <th>
	      パスワードの変更を行います。
	    </th>
	  </tr>
	 
	<tr>
            <td>
	      <div align="center">
		<input type="submit" value="図書登録処理" onclick="subscribe()">
	      </div>
	      <script>
		function subscribe(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Lend/";      
		}
	      </script>     
            </td>
	    <th>
	      図書の登録処理を行います。
	    </th>
	  </tr>
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="図書削除処理" onclick="del()">
	      </div>
	      <script>
		function del(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/Return/";      
		}
	      </script>     
            </td>
	    <th>
	      図書の削除処理を行います。
	    </th>
	  </tr>
	  <tr>
            <td>
	      <div align="center">
		<input type="submit" value="貸出バーコード発行" onclick="publication()">
	      </div>
	      <script>
		function publication(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/List/";      
		}
	      </script>     
            </td>
	    <th>
	      図書の貸出時に使用する、栞状の貸出バーコードの発行処理を行います。
	    </th>
	  </tr>
        </tbody>
      </table>
    </div>
    <div align="right">
      <a href="https://takajo-soft08.github.io/Create/MainPage/">_Back_To_Home_</a>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <input type="submit" value="Ver.CHILD" onclick="ren()">
	      <script>
		function ren(){
		location.href = "https://takajo-soft08.github.io/Create/MainPage/";      
		}
	      </script>    
</body></html>


		
		
