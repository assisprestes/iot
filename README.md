# iot
## projeto para matéria de objetos inteligentes conectados
Este projeto usa um sensor de Umidade do Solo Higrômetro, que identifica as condições de um determinado solo e através do Módulo WiFi NodeMCU ESP8266 e envia o comando para irrigação, de acordo com a condição apresentada, automaticamente. Sendo programado se identificar que o solo apresentese em uma condição seca a LED vermelha acenderá e a irrigação acontece e caso se apresente úmido, a LED verde acenderá significando que as condições são boas e não ocorre a irrigação assim como essas condições são apresentadas no app MQTT Dash para um acompanhamento a distância.

![processo](https://user-images.githubusercontent.com/45372363/99703749-3fcf7480-2a76-11eb-9043-86ddc7dcfe61.png)

Neste repositório encontra-se toda documentação do projet a programação está comentada facilitando o entendimento no arquivo .ino, que foi desenvolvido no Software Arduino UNO.
Para esta automação foi utilizado o módulo Wi-Fi NodeMCU ESP8266 que faz conexão com o MQTT Node-RED, onde são estabelecidas as configurações do Broker. Adicionalmente foi intalado LEDs para ser um segundo output do status do solo e um módulo relé que funciona aciona uma bomba de irrigação. Para maiores informações há um artigo neste repositório explicando o objetivo deste projeto e o vídeo desta solução foi publicado no Youtube e está disponível em: https://www.youtube.com/watch?v=Yuy-Mos5mJo&t=24s


