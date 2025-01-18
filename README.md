# Utilisez la commande suivante pour identifier toutes les versions de Node.js sur votre système :
`which -a node`

# Supprimez les anciennes installations de Node.js
`sudo apt-get remove --purge nodejs`

# Si Node.js a été installé manuellement, vérifiez les chemins et supprimez les fichiers :
`sudo rm -rf /usr/"path to node installation"`

# Installez une version officielle et stable de Node.js
`curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs`

# Pour une version spécifique, modifiez setup_lts.x par setup_16.x, setup_18.x, etc.

`node -v
npm -v`

https://nodejs.org/en/download




