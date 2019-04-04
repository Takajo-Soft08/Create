<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>MainPage (Book Management)</title>
    <!-- /////////////////////////////////////////////////
    	<style>
	    /////// inputは、< >内の先頭の英単語を打ち込んだもの (他にh1,body,divなどもある) /////////////
	    input{
		  // ボタンの高さ
	        height: 15px;
		  // ボタンの幅
	        width: 40px;
		  // 文字のサイズ
	        font-size: 1.4em;
		  // 文字のフォント
	        font-weight: bold;
		  // 背景色
		background-color: #248;
		  // 文字の色
	        color: #fff;
		  // 余白(縦方向に10px、横方向に30pxの余白)
	        padding: 10px 30px;
		  // フチなし
	        border-style: none;
		  // 角丸にする
	        -moz-border-radius: 5px;
		-webkit-border-radius: 5px;
		border-radius: 5px;
	    }
	    ///////// onMouse時の変化 //////////////////////////////////////////////////////////
	    input:hover{
		  // 背景色
		background-color: #24d;
		  // 文字の色
	        color: #fff;
		  // 透明度
	        opacity: 0.8;
	    }
    	</style>
	////////////////////////////////////////////////// -->
    	<style>
	    input{
	        height: 15px;
	        width: 40px;
	        font-size: 1.4em;
	        font-weight: bold;
		background-color: #248;
	        color: #fff;
	        padding: 10px 30px;
	        border-style: none;
	        -moz-border-radius: 5px;
		-webkit-border-radius: 5px;
		border-radius: 5px;
	    }
	    input:hover{
		background-color: #24d;
	        color: #fff;
	        opacity: 0.8;
	    }
    	</style>
	</head>
  <body>
    <div align="center">
      <h1>Main_Page (Book Management)</h1>
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
    <input type="submit" value="MainPagePARENT" onclick="ren()">
	      <script>
		function ren(){
		location.href = "https://takajo-soft08.github.io/Create/MainPagePARENT/";      
		}
	      </script>     
</body></html>
