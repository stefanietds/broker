# Broker

Tutorial para criar broker mqtt dentro de um container Docker.
## Configurar broker:

Ao acessar o container, utilize o comando apt-get install mosquitto para baixar o broker. E depois, utilize o comando apt-get install mosquitto-clients.

![image](https://github.com/stefanietds/broker/assets/123187831/5b44e803-5e43-4ee1-ae5b-94136dd66713)

Para iniciar o broker, digite o comando mosquitto -v no prompt. 

![image](https://github.com/stefanietds/broker/assets/123187831/b8b21a9a-b201-421e-ba02-ddafad989587)

## Se inscrever no tópico:

Para se inscrever no tópico, utilize o comando abaixo que identifica que o broker esta rodando em localhost, porta 1883 e identifique o nome do tópico.

![image](https://github.com/stefanietds/broker/assets/123187831/8e747727-9d2e-4635-b47c-52d7dcf076b8)

## Publicar no tópico:

Para ser um publisher, utilize o comando abaixo e identique o nome do tópico e mensagem.

![image](https://github.com/stefanietds/broker/assets/123187831/87d39123-9668-4837-8c93-60f95a5b4af2)

### Resultado:

O subscriber recebe a mensagem imediatamente após sua publicação.

![image](https://github.com/stefanietds/broker/assets/123187831/3d359b3c-8612-440d-9fcd-4fd8b4b8cb0c)

No broker MQTT, é possivel observar que mensagens foram publicadas no tópico.

![image](https://github.com/stefanietds/broker/assets/123187831/68298733-3c63-4807-9a95-e700b400dc77)



