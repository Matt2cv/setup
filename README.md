Biienvenue sur github pour vous aider à l'installation des différentes solutions de domotique que je vous présente ici.
https://www.youtube.com/channel/UCLoLYGnh66x9cMee-qBi3XQ/

En quelques minutes, je vous montre comment installer #openhab sur un raspberry pi. Une solution de domotique qui se bonifie avec le temps.

De plus, on peut configurer rapidement un influxdb/grafana pour la visualisation des données avec de jolies graphes.

Installer Openhab ( solution domotique ) : 
curl -sL "https://raw.githubusercontent.com/ArminasTV/setup/master/openhab.sh" | bash -s

Installer Hass.io ( solution domotique ) : 
curl -sL "https://raw.githubusercontent.com/ArminasTV/setup/master/homeassistant.sh" | bash -s

Installer Influxdb (base de données temporelle ) : 
curl -sL "https://raw.githubusercontent.com/ArminasTV/setup/master/influxdb.sh" | bash -s

Installer Grafana ( Solution web de visualisation de grapgique ) : 
curl -sL "https://raw.githubusercontent.com/ArminasTV/setup/master/grafana.sh" | bash -s

Installer Mosquitto: 
sudo apt-get install mosquitto mosquitto-clients

Installer les conf pour Openhab : 
curl -sL "https://raw.githubusercontent.com/ArminasTV/setup/master/openhab/setup.sh" | bash -s

url sur le raspberry pi : 
Openhab   : http://raspberrypi.local:8080
Hass.io   : http://raspberrypi.local:8123

Grafana   : http://raspberrypi.local:3000

Abonnez vous !!!
https://twitter.com/ArminasTV
https://www.facebook.com/ArminasTV
