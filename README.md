# chiaoyu
測試
<HTML>
<BODY>
<h2 ALIGN="CENTER">
嗨！親愛的會員您好，為讓您能在本站通行無阻，<BR>
請於下表填入您的認證資料！
<FORM Action="<?=$_SERVER["PHP_SELF"];?>" Method=post>
<TABLE BORDER=1 CELLSPACING=0 ></h2>
<TR><TD ALIGN=RIGHT>登入名稱:</TD>
<TD><Input Type=Text Name=ID Size=10></TD></TR>
<TR><TD ALIGN=RIGHT>登入密碼:</TD>
<TD><Input Type=Password Name=Password Size=8></TD></TR>
</TABLE><P>
<INPUT Type=Submit Value=" 確 定 " name="B1">
</FORM>
</CENTER>
</BODY>
</HTML>


<html>
var user = new Parse.User();
user.set("username", "my name");
user.set("password", "my pass");
user.set("email", "email@example.com");
 
// other fields can be set just like with Parse.Object
user.set("phone", "415-392-0202");
 
user.signUp(null, {
  success: function(user) {
    // Hooray! Let them use the app now.
  },
  error: function(user, error) {
    // Show the error message somewhere and let the user try again.
    alert("Error: " + error.code + " " + error.message);
  }
});
  <head>
    <title>Sample App</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p><%= message %></p>
    <form method="post" action="/hello">
      <p>
        <input name="message"></input>
        <input class="button" type="submit" value="Update Greeting">
      </p>
    </form>
  </body>
</html>
