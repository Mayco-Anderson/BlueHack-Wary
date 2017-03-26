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
  ![alt tag](https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/conversation.png)
  ![alt tag](https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/conversation2.png)
  
  ## Back end
  Toda o backed e frontend da aplicação está hospedado no BLuemix. A seguir apresentamos os flows reponsáveis pelo frontend.
  
  ![alt tag](https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/front-end.png)
  A seguir, apresentamos o código do backend, onde disponibilizamos end-points 
 
  ![alt tag]( https://github.com/Mayco-Anderson/BlueHack-Wary/blob/master/otherFlows.png)
 
 Os cuidados de Wary chegam também às mãos dos profissionais da saúde responsáveis pelo acompanhamento clínico desses indivíduos. De maneira
 remota, através de uma interface Web, médicos podem fazer o setup de notificações sobre posologia, frequência e tipo de remédios devem
 ser consumidos pelo paciente.
 
 


