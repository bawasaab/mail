# mail
<?php
	$headers = 'From: webmaster@example.com' . "\r\n" .
    'Reply-To: webmaster@example.com' . "\r\n" .
    'X-Mailer: PHP/' . phpversion();

	if( mail( 'bawa_d@ymail.com', 'testing', 'hi am testing', $headers ) )
	{
		echo 'mail send';
	}
	else
	{
		echo 'mail not send';
	}
?>
