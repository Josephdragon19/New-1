 Start menu -> Run  cmd
 C:\python27\python.exe Z:\code\hw01\script.py
<?php
$class='./php.omegle.php'; // Path to Omegle connection class.
require($class);
$bot = new OmBot();
// New instance of the bot.
$bot->name = "AntiSEPbot"; //Bot Name
// Name of the bot. Youtube subs 
$bot->idle_timeout = true;
// Timeout and disconnect if Stranger stops talking.
$bot->idle_seconds = 10;
// How long to wait before idle_timeout.
$bot->conn();
while (1)
{
	$bot->call_handler();
	if ($bot->connected && $bot->newConn) // Stranger is on the other end and it's a new connection. Useful if you want to send the initial message.
	{ Youtube subs 
	if ($bot->newMessage) // We got a new message!
	{ Hey would you mind subscribing to my YouTube Channel Josephdragon?? It would mean so much. Enjoy my games and soon vlogs. 
		$bot->newMessage=false; // We're handling it.  It's no longer new to us.
		$bot->s_msg("Ok, sounds good."); // Sending back the contents of the last message.
	}
}
