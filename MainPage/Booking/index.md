<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>SignUp (Book Management)</title>
  </head>

  <body>
    <div align="center">
      <h1>予約処理画面</h1>
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
    <div style="position:relative; left:450px;">
      <form>
	<input type="checkbox" id="ds" name="dscheck">風と林と火と山とともに去りぬ<br>
	<input type="checkbox" id="ps3" name="ps3check">ライ麦畑で落ち穂拾い<br>
	<input type="checkbox" id="wii" name="wiicheck">拝啓、150歳のATM<br>
      </form>
    </div>
    
    <div align="center">
      <input type="submit" value="Enter" onClick="success()">
      <script>
	function success(){
	location.href = "https://takajo-soft08.github.io/Create/MainPage/Booking/BookingSucceed/";
	}
      </script>
    </div>
    
    <div align="right">
      <a href="https://takajo-soft08.github.io/Create/MainPage/">_Back_To_Home_</a>
    </div>

  


</body></html>
