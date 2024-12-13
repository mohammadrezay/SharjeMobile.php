# SharjeMobile.php
https://quera.org/problemset/17244?tab=description
<?php
$k = (int)readline("Enter a number: ");
$a = [];
for($i = $k; $i > 0; $i--){
	array_push($a, $i);
}
echo array_sum($a);
