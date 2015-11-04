API
===

Get Spell Correction API from xSpell.tk

Use This code to get output

```php
<?

$xt = "Token Issued By xSpell";

$xs = "Word Or Sentence To Check Spelling";

$xu = "http://xspell.ga";

$xp = "api=spell&token=$xt&check=$xs";

$x = curl_init();

curl_setopt($x,CURLOPT_POST,1);

curl_setopt($x,CURLOPT_POSTFIELDS,$xp);

curl_setopt($x,CURLOPT_URL,$xu);

curl_setopt($x,CURLOPT_RETURNTRANSFER,1);

$output = curl_exec($x);

?>
```
