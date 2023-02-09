# Clase-30-Servidor-con-balance-de-carga
## Ejecución normal
node server.js -m FORK
node server.js -m CLUSTER

## Ejecución con Forever
forever start server.js -m FORK
forever list

## Ejecución con PM2
pm2 start server.js
pm2 start server.js -i max