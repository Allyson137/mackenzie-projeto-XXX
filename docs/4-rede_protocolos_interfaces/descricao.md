
Descrição do Projeto 
	Vamos utilizar o RFID RC522 para ler os cartões cadastradas, quando os cartões se aproximarem do RFID RC522 irá apresentar a mensagem cartões cadastrada ou cartões não cadastrados. Para os cartões cadastrados o projeto irá acender a luz verde e vermelha para os cartões não cadastrados irá acender a luz vermelha. Para realizar o cadastramento das dos cartões de acesso iremos colocar o código que vem nele no código do programa assim esse cartão já esta cadastrado.  

Problemas Enfrentados 
Tivemos dificuldades de realizar a comunicadas dos cartões no RFID RC522 para não prejudicar o projeto realizarmos pesquisara na web como ler os cartões no RFID RC522 outros problemas que tivemos foi os leds que não estavam acendendo devido a realizar uma conexão na Protoboard. Outro ponto é a comunicação web que de início o Arduino não estava comunicando com internet, após algumas buscas pela web encontrados a solução.

Protocolo de Comunicação utilizado no Projeto:
HTTP  
Iremos apresenta as informações assim que o cartão ler no RFID RC522 se ele está cadastrado ou não. 

MQTT  
Vamos passar as mensagens do Arduino para o mqtt, após o recebimento das mensagens iremos apresenta na tela do node red se o cartão está acessando.

Componentes
lâmpadas de LED: 
      Iremos utilizar uma lâmpada de LED no projeto, ela tem como objetivo piscar após o sensor identificar a leitura do cartão.

Leitor de Cartão:
O leitor do cartão irá ler o cartão cadastrado registrando que foi efetuado a leitura correta do cartão como entrada e saída do estabelecimento.

Cartão de Acesso:
O cartão de acesso cadastrado no sistema a ser utilizado pelo cliente assim deverá ser encostado no leitor para que seja efetuado a sua leitura.

