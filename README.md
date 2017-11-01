1. INTRODUÇÃO

A robótica móvel é uma área que desperta a curiosidade de muitos e que tem evoluído bastante nos últimos anos para o desenvolvimento de sistemas de controle de robôs.
O projeto propõe um controle de trajetória de um carro robô usando PID, onde o robô irá sempre seguir reto na direção inicial.
As etapas da construção do veículo estão esquematizadas em três sistemas e consequentemente seus subsistemas, tais como sistema mecânico (estrutura), sistema elétrico e o sistema eletrônico de controle (controle de velocidade, aceleração e posição, motores e bateria).  
No sistema mecânico, a estrutura pode ser comprada onde é composta de chassi e pneus.
A etapa que faz referência a parte elétrica e eletrônica do sistema, serão abordados os motores DC, o sensor de velocidade/aceleração (MPU5060), a ponte H, bateria e o controlador Arduino UNO.

2. EMBASAMENTO TEÓRICO/PRÁTICO

2.1 MODELAGEM DO SISTEMA

O motor de corrente contínua é representado por 3 equações:

●	Equação da armadura 

<p align="center"><a href="https://imgur.com/jUPqjAR"><img src="https://i.imgur.com/jUPqjAR.jpg" title="source: imgur.com" /></a>
  
  
onde "e" a força eletromotriz, "Va" é a tensão de armadura e "Ra e "La" são a resistência e a indutância da armadura, respectivamente.

●	Equação da força eletromotriz

<p align="center"><a href="https://imgur.com/pYslE4L"><img src="https://i.imgur.com/pYslE4L.jpg" title="source: imgur.com" /></a>

