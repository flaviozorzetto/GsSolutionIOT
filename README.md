# GsSolutionIOT

## Descrição

<p> Esta solução tem como objetivo capturar as temperaturas do paciente e enviar para um servidor MQTT Broker, para ser posteriormente registrado na evidencia do exame do paciente ocorrências como estado febril por exemplo.</p>

## Instruções de uso

<p> Simulador wowki: https://wokwi.com/projects/381864174731207681 </p>

<p> Este simulador capta as informações de temperatura e estabelece uma conexão com o servidor MQTT para ser capturado pelo red-node que posteriormente renderiza um gráfico com as informações capturadas. </p>

<p> Node-RED (json do flow para ser importado) </p>

<p> Estabelece conexão com o servidor MQTT ouvindo o topico de temperatura e renderizando um gráfico.</p>
