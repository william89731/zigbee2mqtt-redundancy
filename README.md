![domotica](https://github.com/william89731/zigbee2mqtt-redundancy/assets/68069659/d9638114-b43b-42df-ac97-e06290e07daa)

[![platform](https://img.shields.io/badge/platform-kubernetes-blue)](https://kubernetes.io/)
[![os](https://img.shields.io/badge/os-linux-red)](https://www.linux.org/)
[![docker version](https://img.shields.io/badge/docker%20version-20.10-brightgreen)](https://www.docker.com/)
[![client mqtt](https://img.shields.io/badge/client%20mqtt-zigbee2mqtt-yellow)](https://www.zigbee2mqtt.io/)
[![license](https://img.shields.io/badge/license-Apache--2.0-yellowgreen)](https://apache.org/licenses/LICENSE-2.0)
[![donate](https://img.shields.io/badge/donate-wango-blue)](https://www.wango.org/donate.aspx)

# zigbee2mqtt-redundancy
2 client mqtt to always have the service available

```requirements``` :
 - 2 instance [zigbee2mqtt](https://www.zigbee2mqtt.io/guide/installation/)
 - 1 [zigbee adapter lan](https://www.zigbee2mqtt.io/guide/adapters/#recommended)

![zigbeedash](https://github.com/william89731/zigbee2mqtt-redundancy/assets/68069659/6221df54-5ebc-442d-bac9-97ff9475eaa1)

```important```

Point to same folder. see [network file system](https://ubuntu.com/server/docs/service-nfs) .

### environment

Here, some types of installation and sample files:

```Kubernetes```

![image](https://github.com/william89731/zigbee2mqtt-redundancy/assets/68069659/5e03df8d-d024-4507-879d-87aba3c752d9)

i have installed [microk8s](https://microk8s.io/) in cluster bareMetal (3 mini pc).

see [zigbee2mqtt.yml](https://github.com/william89731/zigbee2mqtt-redundancy/blob/main/zigbee2mqtt.yml)

```Docker```

- 2 instance running in 1 server. [here](https://github.com/william89731/zigbee2mqtt-redundancy/blob/main/docker-compose.yml) file sample.

- 2 instance, 2 servers. delete second container (in docker compose file)












