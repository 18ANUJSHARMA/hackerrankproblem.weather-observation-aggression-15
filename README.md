# hackerrankproblem.weather-observation-aggression-15
![image](https://github.com/18ANUJSHARMA/hackerrankproblem.weather-observation-aggression-15/assets/122561183/be503b83-17cd-42cf-ad0d-a20a62f1ad0f)

output=>
select ROUND(LONG_W,4)
from STATION 
where LAT_N=(select(max(LAT_N))from STATION where LAT_N<137.2345);
