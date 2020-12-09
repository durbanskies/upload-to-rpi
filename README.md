# upload-to-rpi
Host server with upload on raspi <br>
Find your files by going to <code><i>ip/uploads</i></code> for example <code>192.168.1.67/uploads<br></code><br>
<b>Edit variables</b><br>
You can change the allowed file types by changing the <code>$allowed = array('txt', 'jpg', 'png');</code> and adding different file types<br>
You can change the file end destination by changing the <code>$f_destination = '/var/www/html/uploads/' . $f_name_new;</code>
