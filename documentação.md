# Documentação Ponderdaa de dBm de Sinal WiFi - Módulo 4 - Inteli

# Grupo - SIM

<img src="../assets/inteli.png">

## Integrantes
- <a href="https://www.linkedin.com/in/isabela-pe%C3%A7anha-27b91a356/">Isabela Rosati Peçanha</a>
- <a href="https://www.linkedin.com/in/mariana-pereira-de-souza1/">Mariana Pereira de Souza</a>
- <a href="https://www.linkedin.com/in/sarah-araujo-duarte?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Sarah Araujo Duarte</a>

## Sumário

[1. Introdução](#c1)

[2. Desenvolvimento e Resultados](#c2)

[3. Conclusões ](#c3)

[4. Referências](#c4)

<br>

# <a name="c1"></a> 1. Introdução

&nbsp; &nbsp; &nbsp; &nbsp;Este projeto é composto de uma coleta de potência do sinal WiFi em dBm de uma rede WiFi usando um ESP32 e a publicação destes valores em uma dashboard de uma plataforma online. O projeto IoT deve posssuir um ESP32 conectado a um Wifi, medindo o sinal de radiofrequência e imprimindo os dados em dBm na porta serial da Arduino IDE, além de publicar tais valores para a plataforma. Elabore um código MQTT capaz de transferir o valor de dBm de cada instante para a plataforma online. Nesta plataforma online, configure um gráfico contínuo de valores do dBm (gráfico tempo x dBm), e realize testes em cenários distintos. No final, vá até o elevador do Inteli para simular a gaiola de Faraday. Mais detalhes, vá até o final dessa aula.

# <a name="c2"></a> 2. Desenvolvimento 

&nbsp; &nbsp; &nbsp; &nbsp; Na seção de desenvolvimento, vamos apresentar um relatório evidenciando as constatações realizadas durante os testes, no caso, os locais por onde passsamos e o que conseguimos arrecadar de informações. Prmeiamente, abaixo teremos um vídeo de 7 a 10 minutos aproximadamente, demonstrando essa coleta de dados, mostrando o gráfico do Ubidots, o monitor Serial e o ESP32:

Colocar aqui o link do vídeo do youtube 

&nbsp; &nbsp; &nbsp; &nbsp;Portanto, após a realização do vídeo, algumas conclusões puderam ser tiradas, por isso, logo abaixo vamos descrever como ficou o sinal em cada local que foi visitado e as as diferenças entre eles:

1) sala de aula, monitore por 10s

2) catraca da recepção (onde tem uma bancada com recepcionistas), monitore por 10s

3) suba para o 1º andar, vá até o posto do IT Bar, monitore por 10s

4) ainda no 1º andar, entre no elevador e fique por lá com a porta fechada por 20s e monitore

5) suba até 2º andar, vá até laboratório do André Leal, monitore por 10s

6) vá até o final do mesanino 2, na última salinha de reunião, monitore por 10s

7) dessa pelo elevador novamente sem ficar lá dentro

8) saia do Inteli pela catraca da recepção e vá até a quadra de areia e monitore por 10s.

9) Encerre o vídeo lá.

# <a name="c3"></a> 3. Conclusões 

&nbsp; &nbsp; &nbsp; &nbsp;

[4. Referências](#c4)

m04-semana07.São Paulo. Disponível em: https://github.com/agodoi/m04-semana07/blob/main/README.md?plain=1 Acesso em: 27 nov. 2025.



