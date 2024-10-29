# htb_axlle

## 1. Trouver l’adresse et service  
Configurer correctement le VPN et obtenir l'adresse：10.10.11.21 
`nmap -sSvc 10.10.11.21`

![nmap](./images/nmap.png)

De nombreux ports ont été ouverts. Jetons un coup d'œil aux ports clés 80 et 445.
