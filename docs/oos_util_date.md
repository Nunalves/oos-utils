# OOS_UTIL_DATE

- [DATE2EPOCH Function](#date2epoch)
- [EPOCH2DATE Function](#epoch2date)








 
## <a name="date2epoch"></a>DATE2EPOCH Function


<p>
<p>Coverts date to Unix Epoch time</p><p>Notes:<br /> -</p><p>Related Tickets:</p><ul>
<li>#18</li>
</ul>

</p>
Author: Martin Giffy D&#x27;Souza

### Syntax
```plsql
function date2epoch(
  p_date in date)
  return number
```

 


### Parameters
Name | Description
--- | ---
p_date | Date to convert to Epoch format
*return* | Unix Epoch time
 
 





 
## <a name="epoch2date"></a>EPOCH2DATE Function


<p>
<p>Converts Unix linux time to Oracle date</p><p>Notes:<br /> -</p><p>Related Tickets:</p><ul>
<li>#18</li>
</ul>

</p>
Author: Martin Giffy D&#x27;Souza

### Syntax
```plsql
function epoch2date(
  p_epoch in number)
  return date
```

 


### Parameters
Name | Description
--- | ---
p_epoch | Epoch Unix date (number)
*return* | date
 
 





 