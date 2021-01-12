# NGINX-LETSENCRYPT + DOCKER + WORDPRESS + GHOST

Sistema realizado en la nube de Microsoft Azure.☁

Something like:

![Web Proxy environment](https://github.com/evertramos/images/raw/master/webproxy.jpg)

## Why use it❓

Using this set up you will be able start a production environment in a few seconds. For each new web project simply start the containers with the option `-e VIRTUAL_HOST=your.domain.com` and you will be ready to go. If you want to use SSL (Let's Encrypt) just add the tag `-e LETSENCRYPT_HOST=your.domain.com`. Done!

Easy and trustworthy!


## Prerequisites 🧑‍💻

In order to use this compose file (docker-compose.yml) you must have:

1. docker (https://docs.docker.com/engine/installation/)
2. docker-compose (https://docs.docker.com/compose/install/)

## How to use it📣

Clone this project
  1. Clone repo
  2. Change domains in docker-compose
  2. `docker-compose up -d` ./
  3. `docker-compose up -d` /anyService


## Resources 💻:
* Docker 🐳
* Microsoft Azure
* Letsencrypt🔐
* Wordpress
* Ghost👻

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## Expresiones de Gratitud 🎁

* ¡Dale un ⭐️ si este proyecto te ayudó!
* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
