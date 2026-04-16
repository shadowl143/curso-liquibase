# Curso liquiebase.

Es necesario habilitar los puertos para que se pueda conectar liquidbase 
win + R
SQLServerManager16.msc
SQLServerManager15.msc
SQLServerManager14.msc

depende de la version de windows.

buscar la opcion protocols for SQLEXPRESS
- opciopn tcp/ip -> enable = true
- ip addresses -> all-> ipall -> tcp port 1433
- reiniciar el servicio de sql server SQL Server Services -> sql server (SQLEXPRESS) click derecho reinciar.