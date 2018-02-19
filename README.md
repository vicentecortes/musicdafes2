# musicdafes2
&lt;!DOCTYPE html> &lt;html> &lt;body>  &lt;?php $xml=simplexml_load_file("note.xml") or die("Error: Cannot create object"); echo $xml->to . "&lt;br>"; echo $xml->from . "&lt;br>"; echo $xml->heading . "&lt;br>"; echo $xml->body; ?>   &lt;/body> &lt;/html>
<?php
define("GREETING", "vienvenido musicdafes);

function myTest() {
    echo GREETING;
}
 
myTest();
?> 
