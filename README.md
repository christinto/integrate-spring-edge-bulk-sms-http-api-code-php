integrate-spring-edge-bulk-sms-http-api-code-php
================================================

Sample code of how to integrate SpringEdge's bulk SMS HTTP API in website - PHP Class

Steps:

Integrating HTTP API: Download sendsms.php class file from developers section of SpringEdge Messaging Application

Use below code in your file to send sms

<?php
 include 'sendsms.php';
 $sendsms=new sendsms("http://alerts.springedge.com/api", "API key HERE", "sender ID HERE");
 $sendsms->send_sms("99xxxxxxxx", "MESSAGE BODY HERE", "", "xml");
?>

for websites with CMS like joomla, opencart, woo commerce, zencart, wordpress use SpringEdge's messaging Modules.
