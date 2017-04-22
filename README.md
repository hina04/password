# password
password authentication module
<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="password.css">
</head>
<body>
<div class="main">
<b>Password:</b><br>
<input type="password" id="password" autofocus class="passlength" onkeyup="match();length();CheckPasswordStrength(this.value);" />    <span id="password_strength"></span><br>

<script type="text/javascript" src="interaction.js"/>
</script>
</div>
</body>
</html>
