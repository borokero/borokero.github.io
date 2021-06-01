<p align="center">
  <img src="https://raw.githubusercontent.com/borokero/borokero-docs/master/images/borokero_iot_platform.png">
</p>

# Borokero ;) Open Source Platform for Ever

## About


#### Open Source Back End for IoT, Web, Apps and Mobile

Borokero will enable you to put your IoT, Mobile, Apps or Web API services on your own server simply and painless in one command. It supports the popular MQTT protocol in sync with HTTP. It is in javascript and authenticate and authorize your device list so broker perform authentication by your entry data in oauth server like Keycloak.
Borokero is under development so it should work. It need time to release stable version.


## Features

* Simple and Scalable based on docker-compose and as soon as possible on kubernetes
* HTTP, MQTT connections together as a bridge.
* MQTT 3.1 and 3.1.1 compliant.
* Sercured with authentication and authorization.


## Installation

Borokero IoT Platform is installed by two methods. Firstly besure docker and docker-compose is installed.

### Using Shell Script

Run the following command in your terminal to install the latest official Borokero IoT Platform release. For customization environment variables, make iot-mqtt.env and iot-http.env with your desired variables before run installer shell script. Deafualt value will loaded if .env files is not existence in current path.

```bash
sudo curl -o- https://raw.githubusercontent.com/borokero/borokero/master/install.sh | bash
```


### Using Git

Download Borokero Platform git

```bash
git clone https://github.com/borokero/borokero-docker-compose

cd borokero-docker-compose

sudo docker-compose up
```



## Tutorial

You can find a step by step <a href="https://github.com/borokero/borokero/wiki/Tutorial">tutorial</a> in wiki page .

### Development

Borokero is composed by different microservices.
Follow the installation guidelines for each of them.

| Microservice  | Description |
| ------------- | ------------- |
| [Docs](https://borokero.github.io/borokero-docs) | Borokero Documentations |
| [Borokero](https://borokero.github.io/brokero)  | Borokero Installer Shell Script |
| [HTTP Bridge](https://borokero.github.io/borokero-iot-http) | HTTP/HTTPS server |
| [MQTT Bridge](https://borokero.github.io/borokero-iot-mqtt) | MQTT/MQTTS broker |
| [Borokero Auth](https://borokero.github.io/borokero-auth) | Borokero Authentication and Authorization |
| [Docker-Compose](https://borokero.github.io/borokero-iot-mqtt) | Docker-Compose confiuration |
| [CLI](https://borokero.github.io/borokero-cli) | Borokero CLI |
| [Borokero Webpage](https://borokero.github.io) | Borokero Github Page |



#### Development Environment Variable

During deployment, every microservice needs to be set to the following environment variables. You can customize .env file in every repository.


### Learn more

You can find a test version of Borokero IoT Platform at borokero.iokloud.com as soon as possible.

If you find Borokero useful, consider supporting the project by buying a support package
from [me](http://twitter.com/iokloud) by writing an email to borokero.platform@gmail.com

Check out our [showcase](https://github.com/borokero/borokero/wiki/Borokero-Showcases) wiki
page! Feel free to add yourself! :)

## Security Issues

__Borokero__ sits between your system and the devices: this is a tough role, and we did our best to secure your systems.
However, you might find a security issue: in that case, email borokero.platform@gmail.com


## Feedback

Use the [issue tracker](https://github.com/borokero/borokero/issues) for bugs.
[Tweet](http://twitter.com/iokloud) us for any idea that can improve the project.


## Links

* [Aedes](https://github.com/moscajs/aedes)
* [Mosca](http://github.com/mcollina/mosca)
* [Ponte](https://github.com/eclipse/ponte)
* [Parse Server](https://parseplatform.org)
* [Mongodb](https://www.mongodb.com/)
* [MQTT protocol](http://mqtt.org)
* [MQTT.js](http://github.com/adamvr/MQTT.js)
* [Paraffin Platform](https://paraffiniot.github.io)


## Authors

* [Hadi Mahdavi](https://github.com/expandboard)
* [Nana Kwame Zoe](https://github.com/banphlet)
* [Kwarteng Wisdom](https://github.com/Wisdom0063)
* [Ahmad Rafiee](https://github.com/AhmadRafiee)
