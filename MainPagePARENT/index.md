
<html><head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <title>MainPage (Book Management)</title>
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
		
