# Dokumentasi PM NODE JS TERAMEDIK CE 
###### 1. List nodejs
`` pm2 list ``
###### 2. Start nodejs
`` pm2 start [nama webservice] --watch  [INI BILA SUDAH ADA]``
`` pm2 start {path_app_js} --name {nama_namespace} --watch [INI BILA BELUM ADA]``
###### 3. Stop nodejs
`` pm2 stop [nama webservice] ``
###### 4. Show List Process Info
`` netstat -lntp ``
###### 5. Restart nodejs
`` pm2 restart master --watch `` 
  **Namun bila gagal, manual saja mulai dari STOP lalu START

# Selengkapnya di :
``` https://pm2.keymetrics.io/docs/usage/restart-strategies/ ```
