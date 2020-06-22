<h2>Automatização Residencial</h2>

<h3>Acender e apagar a luz por comandos de voz</h3> 
<br>
<p> Este projeto tem como finalidade acender e apagar a luz por comandos de voz. 
Neste caso, os comandos são: 'on' para acender e 'off' para apagar.
Para desenvolver o projeto será necessário ter em mãos alguns hardwares indispensáveis,
bem como o Raspberry Pi 3, Jumper Fêmea, Módulo relé, Microfone USB. </p>

<p> Além disso, alguns serviços também são utilizados nesse projeto,
como a plataforma Watson e o Node-RED, utilizando os protocolos MQTT. </p>

<p> De maneira bem simplista, o fluxo funciona da seguinte maneira:</p>
<p> 1- O raspberry é ligado em sua fonte de energia</p>
<p> 2- O microfone começa a receber todas as captações sonoras a as enviam à plataforma Watson.</p>
<p> 3- A plataforma Watson, de serviços cognitivos, traduz os sons capturados e os enviam ao Node-RED </p>
<p> 4- O Node-RED, por sua vez, possui toda a lógica do sistema. Ele será o responsável e tratar os comandos "on" e "off".
Caso o comando enviado seja "on", ele envia uma mensagem ao raspberry para que ele ligue o GPIO responsável em enviar
energia ao Módulo Relé. Caso o comando seja "off", ele envia a mensagem para que o raspberry desligue
o GPIO responsável em alimentar o Módulo Relé.


<p> Neste repositório está disponível o artigo do projeto, onde constam mais
detalhes sobre os hardwares e sistemas utilizados, além de explicar o fluxo detalhado do projeto
e seu objetivo na sociedade. </p>

<p> Também existem um vídeo disponível no youtube exibindo o funcionamento do sistema por completo: </p>



