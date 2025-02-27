# Introdução ao Arduíno 


## O que é Arduíno? 
 Normalmente e utilizado quando é preciso facilitar a criação de circuitos elétricos e facilitar projetos eletrônicos, robóticos e mecatrônicos. 
O microcontrolador arduíno é uma placa programável que serve para enviar instruções em forma de sinais elétricos para um circuito elétrico(que pode ter componentes mecânicos como um robô). 
Basicamente, o arduíno serve para transportar a informação que descrevemos no programa para o circuito.
plataforma serve não apenas para "escrever" informações no circuito como também para ler informações que queremos obter.
Em termos práticos, um Arduino é um pequeno computador que você pode programar para processar entradas e saídas entre o dispositivo e os componentes externos conectados a ele McRoberts (2010).

Entenderemos melhor esses conceitos quando estudarmos as partes do arduíno. 

## O que você pode fazer com Arduino ? 

A placa arduíno serve para uma infinidade de coisas. Projetos robóticos, projetos de automatização, projetos eletrônicos. 
Você pode utilizar sensores, motores e uma série de componentes eletrônicos para realizar seus projetos.
Para ver exemplos de projetos com arduínos acesse esse [link](https://www.youtube.com/watch?v=XxmD70Wvmdw) e esse [link](https://www.youtube.com/watch?v=0XTcJ5-0u00).

## Partes do arduíno
Há muitas variantes diferentes do Arduino. No entato, iremos conhecer as partes do arduíno mais comum, o arduíno uno.
Você também pode obter versões Mini, Nano e Bluetooth do Arduino.
Outra nova adição aos produtos disponíveis é o Arduino Mega 2560, que oferece mais memória e um número maior de pinos de entrada/saída. 

![Arduino](partesa.png)
Conector USB: É por esse conector que realizamos a comunicação com o computador através de um cabo USB.

Entradas/saídas Digitais: São as entradas responsáveis por mandar sinais para o componente que queremos trabalhar. Se por exemplo, fomos ligar um motor deveremos utilizar essas entradas para passar o sinal (ligado/desligado) ao motor. 
Entradas digitais só podem transmitir duas informações. Ligado ou desligado. Por isso usamos comumente para ligar Leds, motores ou receber informações de um botão, por exemplo. 

Fonte externa: Quando o arduíno não está ligado no cabo USB a alimentação pode ser feita pela fonte externa 

	
## O que precisamos para criar circuitos ? 
Normalmente não usamos o arduíno sozinho, mas em conjunto com outros componentes. O arduíno é apenas a programação do circuito. Para utilizar o arduíno é necessário ter algumas noções básicas de eletrônica.

Citamos aqui alguns dos componentes mais utilizados em projetos com arduíno. 

### Protoboard:

Normalmente circuitos elétricos são organizados em placas. As placas de circuito impresso são pensadas para um propósito especifico e depois de pronta não são mudadas(e quando é feito recebe o nome carinhoso de gambiarra).
Imagine que você está testando um circuito elétrico, ou quer apenas fazer uma atividade e não quer que o circuito exista para sempre, nesse caso você pode usar a protoboard. 
A protoboard, também chamada de placa de ensaio é uma placa física para prototipagem e testes. Saiba mais sobre a protoboard e como utilizar vendo [esse](https://www.youtube.com/watch?v=OJF_QA7r_Pc) vídeo


### Componentes eletrônicos:

#### Resistores

Um resistor é um componente eletrônico utilizado com a finalidade de transformar energia elétrica em energia térmica por meio do efeito joule, ora com a finalidade de limitar a corrente elétrica em um circuito.
Os resistores são muito usados na eletrônica e é importante aprender o funcionamento deles para não queimar outros componentes eletrônicos. 

Para aprender mais sobre resistores assista [esse](https://www.youtube.com/watch?v=xK1xe5gsfVk) video.



#### Pushbuttons

Também chamado de botão de pressão é usado normalmente para ligar/desligar circuitos. Seu funcionamento é bem simples e 
é comum que um pushbutton possua ação de contato momentânea.
Pode ser utilizado para mandar um comando toda vez que pressionado, como por exemplo um teclado. 


### Sensores
Exitem uma infinidade de sensores para o arduíno, utilizados nas mais variadas aplicações nesse texto abordaremos apenas os mais utilizados.
Os sensores são elementos eletrônicos que funcionam como dispositivos de entrada. São eles que irão coletar as informações sobre o meio e transmitirá essas informações para o arduíno. 

#### Sensor ultrassônico 
Transmite e recebe uma onda sonora de alta frequência que detecta objetos que refletem a onda. Normalmente utilizada para detectar a existência de objetos ou obstáculos e a distância entre o sensor e o obstáculo Júnior(2017)   

#### Sensor de luminosidade(LDR) 
Componente no qual a resistência varia de acordo com a variação da luz. Normalmente utilizamos esse sensor para saber se a luz está acessa ou apagada. 


#### Sensor de cor 
Esse sensor é utilizado para identificares cores de objetos. O sensor retorna a quantidade de vermelho, verde e azul do objeto (RGB)

para saber um pouco mais sobre sensores veja [esse](https://www.youtube.com/watch?v=vEdYjAbzrAE) video

#### Um pouco mais de conhecimento.
Nesse material nós só abordamos o básico sobre o arduíno, o que ele é e suas ferramentas.
Para ir para a prática de verdade, assista esse curso da [udemy](https://www.udemy.com/aprenda-arduino-torne-se-um-mestre-de-programacao-cc/).

O melhor site para se consultar documentação e projetos é o próprio site do [Arduino](https://www.arduino.cc/) no entanto, se você não souber inglês existe o site do [Arduino.org](https://br-arduino.org/) em português que tem um bom volume de projetos e artigos traduzidos. 

Além desses existem vários sites para simulação de circuitos caso você queira testar sem uma placa à mão. Como por exemplo o [Thinkercat](https://www.tinkercad.com/learn/circuits)
### Referências

McRoberts M. (2010). Beginning Arduino. Editora apress 

Junior V. (2017). Automação e instrumentação: 1 ed. 

