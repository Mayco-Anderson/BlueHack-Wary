# Wary by Dream On BOT

Este projeto apresenta a proposta do grupo Dream On BOT para o IBM Blue Hack 2017

Wary é a mais nova integrante da família TJ BOT, somando sua expertise em gerenciar temas e atividades para pessoas idosas. Mais que isso,
 ela foi especialmente desenvolvida para prover uma atenção especial para portadores do Mau de Alzheimer.
 
 Dentre suas inúmeras tarefas, Wary passa grande parte do seu tempo zelando pela segurança e integridade de seu(s) companheiro(s) velhinhos
 dentro de casa.
 
 Nos momentos em que não pode acompanhar de perto, Wary garante que um dispositivo colocado junto ao pulso do indivíduo, envie informações
 sobre geolocalização, guarde dados sobre as características fisiológicas básicas da pessoa e auxilie os demais ao seu redor no evento de um
 incidente.
 
 Para isso, as seguintes aplicações foram desenvolvidas utilizando os ambientes Raspberry Pi Node Red + IBM BLueMix.
 ## Conversation
Desenvolvemos todo o sistema de chat, identificação de Intent e Entity presentes no serviço de Conversation do Watson para iteragir com nosso usuários de uma maneira não estruturada. 
  ![alt tag](https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/conversation2.png)
  ## Node-Red - Bluemix
  O backend da solução foi desenvolvido utilizando a linguagem JavaScript no Node-Red hospedado no Bluemix. A seguir apresentamos os flows reponsáveis pelo Backend.
  
 ![alt tag](https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/backend.png)
 A seguir apresentamos os flows do fronend
 ![alt tag](https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/front-end.png)
 A seguir apresentamos o flow responseável por simular o disparo de um evento quando o paciente precisa tomar um remédio, além do flow que trata um evento de RFID.
  ![alt tag]( https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/otherFlows.png)
  
  ## Raspiberry Pi
  No coração do TJ bot encontramos o Raspiberry Pi. Um mini computador do tamanho de um cartão de crédito. Utilizando também o Node-Red no Bluemix podemos integrar om facilidade o device com a nuvem, além de controlar a comunição serial e as portas analógicas e digitais do Raspiberry pi.
  ![alt tag]( https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/raspiCode.png)
 
 Os cuidados de Wary chegam também às mãos dos profissionais da saúde responsáveis pelo acompanhamento clínico desses indivíduos. De maneira
 remota, através de uma interface Web, médicos podem fazer o setup de notificações sobre posologia, frequência e tipo de remédios devem
 ser consumidos pelo paciente.
 
 


