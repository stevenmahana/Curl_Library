EXAMPLE:

$C = new Curl_Library();

$url = 'http://news.yahoo.com/rss/';

$C->fetch($url);

$response =  $C->getResponse();
 
Options:

$C->setProxy($ip, $port, $type)

$test = $C->test();
