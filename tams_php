<?php
$ch = curl_init();

curl_setopt($ch, CURLOPT_URL, "http://blynk-cloud.com/081f84563ac145d38b999e47736cbece/get/V5");
curl_setopt($ch, CURLOPT_RETURNTRANSFER, TRUE);
curl_setopt($ch, CURLOPT_HEADER, FALSE);

$response = curl_exec($ch);
curl_close($ch);

var_dump($response);

?>