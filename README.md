# cookie-demo
Cookie Demo for Students

Getting all cookies as an associative array

foreach($_COOKIE as $a=>$b) {
  echo $a."-".$b;
}

Check Cookie is enabled or not?

Delete cookie
setcookie("Cookie Name","Cookie Value",time()-3600);
