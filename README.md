SELECT ROUND(LONG_W, 4)
<br>
FROM STATION
<br>
WHERE
<br>
LAT_N = (
<br>
<p></p> SELECT MIN(LAT_N)
<br>
<p></p>FROM STATION
<br>
<p></p>WHERE
<br>
<p></p>LAT_N > 38.7780);
