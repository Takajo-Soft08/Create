<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>List (Book Management)</title>
  </head>

  <body>
    <div align="center">
      <h1>登録図書一覧画面</h1>
    </div>
    <div align="right">
      <input type="submit" value="ログアウト" onclick="logOut()">
    </div>
    <script>
      function logOut(){
      location.href = "file:///Network/Servers/iemac.ie.tokuyama.ac.jp/Volumes/Users/15/i15kasibe/_CreativePractice_/login.html";      
      }
    </script>
    
    <hr>
    <div align="center">
      <table border="1">
        <form action="list.html" method="get"></form>
        <tbody>
	  <tr>
            <th> 題名 </th>
            <th> 貸出状況 </th>
          </tr>
	  <tr>
            <th> 日々是好日のススメ </th>
            <th> 貸出可 </th>
          </tr>
	  <tr>
            <th> セッション!! </th>
            <th> 貸出可 </th>
          </tr>
	  <tr>
            <th> Butterfly_Effect_Boys </th>
            <th> 予約申込み </th>
          </tr>
	  <tr>
            <th> 風と林と火と山とともに去りぬ </th>
            <th> 貸出中 </th>
          </tr>
          <tr>
            <th> ライ麦畑で落ち穂拾い </th>
            <th> 貸出中 </th>
          </tr>
          <tr>
            <th> 拝啓、150歳のATM </th>
            <th> 貸出中 </th>
          </tr>
        </tbody>
      </table>
    </div>
    <p></p>
    <div align="center">
      <a href="https://takajo-soft08.github.io/Create/MainPage/">_Back_To_Home_</a>
    </div>

  


</body></html>
