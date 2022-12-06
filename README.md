# mqtt

## Engenharia da Computação - João Pedro de Alcantara Lima

Inialmente dê um npm install para instalar as dependências da biblioteca mqtt
fonte : https://www.npmjs.com/package/mqtt

Primeiramente para fazer uma aplicação Node JS conectar com o server do MQTT Box é preciso instalar a extensão no navegador :

![image](https://user-images.githubusercontent.com/84744587/206017817-102e88ab-31e2-47bd-8351-e4bb14a1f9bf.png)

O segundo passo é configurar o client no MQTT Box:

![image](https://user-images.githubusercontent.com/84744587/206018007-6cd71eea-7f3c-4146-93b7-5602572e51ea.png)

Com nossa aplicação Node rodando , precisamos enviar o topic igual configurado no index e uma mensagem no campo Payload :

![image](https://user-images.githubusercontent.com/84744587/206018196-99f5e070-ab65-498c-b989-f9141379cdfb.png)

E assim portanto temos nosso app Node conectando com o server do MQTT:

![image](https://user-images.githubusercontent.com/84744587/206018475-fedf7ef4-a401-4f3f-9626-944edef7ca6d.png)

