<!doctype html>
<head>
<title>
Login 
</title>
  <h1 align="center">Login</h1>
</head>

<script language="javascript">
function check(form)
{
 
 if(form.uid.value == "abc" && form.pwd.value == "xyz")
  {
    window.open('next.html')
  }
 else
 {
   alert("Wrong username and password")
  }
}
</script>  
  
<body>
<h1 style="font-family:verdana; text-align="center";font-size:18pt; color:#0FFF00;> </h1>

<form method="post" name="login">
  
Username : <input type="text" name="uid"/>
Password : <input type="password" name="pwd"/>

<input type="button" onclick="check(this.form)" value="Login"/>

</form>

</body>
</html>
