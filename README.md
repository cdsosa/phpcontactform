# phpcontactform
###Sending contact form using php and forwarding to a redirect page

```
if ($success){
  print "<meta http-equiv=\"refresh\" content=\"0;URL=index.html\">";
}
else{
  print "<meta http-equiv=\"refresh\" content=\"0;URL=error.htm\">";
}
```
