<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 </head>
  <body>
<table>
        <thead>
            <tr>
            <th>학년</th>
            <th>성별</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <td>2</td>
            <td>남자</td>
            </tr>
            <tr>
            <td>3</td>
            <td rowspan="2">여자</td>    
            </tr>
            <tr>
            <td>2</td>
            </tr>
        </tbody>
    </table>
    <a href="./write.html">글 작성하기</a>
   
    <form action="http://localhost/login.php" method="post">
        <p>
        <label for="아이디">아이디:</label>
        <input placeholder="아이디"type="text"name="ID" value="default value">
        </p>
        <p>
        <label for="비밀번호">비밀번호:</label>
        <input placeholder="비밀번호" type="password"name="pwd" value="default value"></p>
        <p>
        <label>textarea:<textarea placeholder="글을 입력하시오" cols="50" rows="10"></textarea>>
        </label>
        </p>
        <h1>색상</h1>
        <select name="color">
            <option value="pink">분홍색</option>
            <option value="green">초록색</option>
            <option value="purple">보라색</option>
        </select>
        
        <p>빨간색<input type="radio" name="color" value="red"</p>
        <p>파란색<input type="radio" name="color" value="blue"></p>
        
        <p><input type="checkbox" name="color" value="black" checked></p>
        <p><input type="checkbox" name="color" value="white" checked></p>
        <p><input type="submit"></p>
    </form>
    </body>
  </html>
