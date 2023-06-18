# Pagina-Config-ESP8266
Pagina de configuração que está sendo desenvolvida para um projeto com um esp8266, nessa pagina é possível configura as medidas de vários reservatórios além de pegar a localização baseado no Wi-Fi ou gps do dispositivo que esta acessado a pagina.
Essa pagina deverar esta hospedada em um servidor rodando dentro do ESP8266/ESP32.

## Explicação dobre o index
- No index.html estão a parte HTML, CSS e JavaScrip no mesmo arquivo, isso se deve ao fato de que no ESP8266 esse arquivo tem que ser passado todo de uma vez, por esse motivo, o arquivo teve que ser unificado.

# Servidor Web ESP8266

<p align="center">
    <img src="img/status.svg"/>
</p>

<hr>

## Capturas de tela
<p align="center">
    <img src="img/mobile.png" width="800" />
    <img src="img/mobile%20(3).png" width="200" />
    <img src="img/mobile%20(6).png" width="200" />
    <img src="img/mobile%20(7).png" width="200" />
    <img src="img/mobile%20(8).png" width="200" />
</p>

<hr>

## Descrição e objetivos
### Descrição

- Este projeto foi desenvolvido para um projeto de **TCC**
 **UFERSA** - Universidade Ferderal Rural do Semi-Arido
 O mesmo estará se tornando um projeto de desenvolvimento cientifico para ajudar no combate a seca no Nordeste.

- Nesse repositório ficará o codigo da pagina de servidor web
O codigo completo com todas as funcionalidades ficaram em outro repositório por questoes de segurança.

### Objetivos
- Criar uma pagina web que rode em uma placa NodeMCU/Esp8266.
- Desenvolver tela de login
- Desenvolver função que pegue a localização baseado em gps ou wifi.
- Criar uma pagina com campos para o usuário inserir as medidas dos reservatórios.
- A pagina web deve ter um campo de seleção onde se possa escolher o formato do reservatório.
- Os campos de dados dever ser exibidos/ocultos de acordo com o reservatório escolhido pelo usuário.
- Os dados inseridos devem ser enviados para o servidor no ESP8266 para serem tratados

### Instruções

- O arquivo index.html para ser usado no esp deve ser renomeado para pagina.h e depois ser passado como uma estring para o ESP, no codigo do ESP o arquivo pagina.h deve ser chamado como um biblioteca e so depois passar a estring.
- Para usar, o arquivo deve ter a extenção .h, para editar recomendo renomear para exteção .html 

<hr>

## Tecnologias
- HTML5
- CSS3
- Javascript
