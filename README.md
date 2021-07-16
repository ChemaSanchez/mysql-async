# Script Original From ESX-Org
FXServer mysql-async  | Chema Leaks


[INSTALLATION]

1) CD in your resources/[esx] folder

```
3) Add this in your server.cfg :

set mysql_connection_string "server=127.0.0.1;database=essentialmode;userid=root;password="
server_script '@mysql-async/lib/MySQL.lua'

start mysql-async 
```