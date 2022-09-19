# SmartHome
My little homeassistant, mosquitto and zigbee2mqtt setup.

# Usage:
Clone and run from repo folder:

    sudo docker-compose up

Urls:

    HomeAssistant:
    http://< host ip >:8123/
    
    Zigbee2MQtt:
    http://< host ip >:8080/

# Known issues:
* host volumes need to be created manually with mkdir
* external network need to createdwith 'docker network create' (dont remember axact spell-it is shown in Error msg when docker-compose up)
* Configs need to be moved manually from conf folder
* Security! no password protection for mqtt is in config. But shouldn't be much concern since it is running in private docker network.
