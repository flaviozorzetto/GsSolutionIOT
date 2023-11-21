# GsSolutionIOT

<p>Link video uso: https://youtu.be/KUtBBcCN2-U</p>

## Descrição

<p> Esta solução tem como objetivo capturar as temperaturas do paciente e enviar para um servidor MQTT Broker, para ser posteriormente registrado na evidencia do exame do paciente ocorrências como estado febril por exemplo.</p>

## Instruções de uso

<p> Simulador wowki: https://wokwi.com/projects/381864174731207681 </p>

<p> Este simulador capta as informações de temperatura e estabelece uma conexão com o servidor MQTT para ser capturado pelo red-node que posteriormente renderiza um gráfico com as informações capturadas. </p>

<p> Node-RED (json do flow para ser importado) </p>

<p> Estabelece conexão com o servidor MQTT ouvindo o topico de temperatura e renderizando um gráfico.</p>

<p> Link Node-RED http://localhost:1880</p>
<p> Link node-red-dashboard: http://localhost:1880/ui </p>

<p> Variaveis no node-red: </p>

<p>Porta mqtt: 1883</p>
<p>Host: broker.hivemq.com</p>
<p>Topico: topic_sensor_temperature</p>

## RMS
<ul>
  <li>Flavio Esrenko Zorzetto RM93175</li>
  <li>Lucas Kenji Nishida RM94233</li>
  <li>Wesley Novais Kleim RM94412</li>
  <li>Jorge Rodrigo dos Santos RM93418</li>
  <li>Lucas Gonçalves Leu De Lima RM88349</li>
</ul>
