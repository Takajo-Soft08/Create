<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>SignUp (Book Management)</title>
  </head>

  <body>
    <div align="center">
      <h1>貸出バーコード発行画面</h1>
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
	<input type="checkbox" id="ds" name="dscheck">日々是好日のススメ<br>
	<input type="checkbox" id="ps3" name="ps3check">セッション!!<br>
	<input type="checkbox" id="wii" name="wiicheck">Butterfly_Effect_Boys<br>
	<input type="checkbox" id="ds" name="1dscheck">風と林と火と山とともに去りぬ<br>
	<input type="checkbox" id="ps3" name="1ps3check">ライ麦畑で落ち穂拾い<br>
	<input type="checkbox" id="wii" name="1wiicheck">拝啓、150歳のATM<br>
  </form>
    </div>
    
    <div align="center">
      <input type="submit" value="Enter" onClick="success()">
      <script>
	function success(){
	location.href = "https://takajo-soft08.github.io/Create/MainPagePARENT/Barcode/BarcordSucceed/";
	}
      </script>
    </div>
    
    <div align="right">
      <a href="https://takajo-soft08.github.io/Create/MainPagePARENT/">_Back_To_Home_</a>
    </div>

  


</body></html>
