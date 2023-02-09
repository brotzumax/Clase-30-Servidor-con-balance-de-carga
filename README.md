# Clase-30-Servidor-con-balance-de-carga
## Ejecución normal
node server.js -m FORK <br />
node server.js -m CLUSTER <br />

## Ejecución con Forever
forever start server.js -m FORK <br />
forever list <br />

## Ejecución con PM2
pm2 start server.js <br />
pm2 start server.js -i max <br />