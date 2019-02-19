<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>Lend (Book Management)</title>
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
    
    <div align="center">
      <p>貸出バーコード発行完了いたしました</p>
      <p></p>
      <table border="1">
        <form action="list.html" method="get"></form>
        <tbody>
	      <tr>
            <th>
              題名
            </th>
            <th>
              風と林と火と山とともに去りぬ
            </th>
         </tr>
	       <tr>
            <th>
              発行日時
            </th>
            <th>
              2019/02/15 15:14:56
            </th>
          </tr>
          <tr>
            <th>
              バーコード
            </th>
            <th>
              <img src="BarCodeSample.png" alt="BarCodeID">
            </th>          
          </tr>
        </tbody>
      </table>
    </div>
    <p></p>  
    <div align="center">
      <a href="https://takajo-soft08.github.io/Create/MainPagePARENT/">_Back_To_Home_</a>
    </div>

  



</body></html>
