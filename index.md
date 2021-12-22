<!DOCTYPE HTML>
<html>
<head>

</head>

<body>
  

<?php>

§empfaenger="raphael.mikesch@vs-durach.de";
§betreff="php Email html test";
&from =": KOBER <raphael.mikesch@vs-durach.de>\r\n";
&from.="Reply-To: rapahel.mikesch@vs-durach.de\r\n";
&from.="Conttentent-Type: text/html\r\n";
§msg ="<h1>PHP Email</h1><br><p>Danke Für deine </strong></p>";

if(mail(§empfaenger,§betreff,§msg,&from)){
  echo "Email Wurde gesändet"

}

?>


</body>
</html>
