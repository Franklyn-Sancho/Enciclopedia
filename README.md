<h1 align="center"> ENCICLOPÉDIA </h1>

## Sumário

1. [Objetivo](#Objetivo)
2. [Regras do Projeto](#Regras)
3. [Web e Internet](#Web)
   3.1 [Protocolos](#Protocolos)

OBJETIVO	

	Quem me conhece sabe que sou defensor de uma educação mais inclusiva e democrática. Queria muito poder tornar o conhecimento e a educação mais acessível para todos. A tecnologia nos proporciona uma ideia de poder infinito, como se fossemos capazes de fazer qualquer coisa por ela, inclusive resolver os maiores problemas do mundo por completo. O objetivo desse projeto é centralizar o máximo de informações possíveis sobre a tecnologia da informação, tendo como desafio proporcionar uma explicação simples e didática sobre cada um dos conteúdos. Quero proporcionar a todos um lugar de muito aprendizado, roteiros e experiências, um lugar em que todos poderão participar, compartilhando suas histórias, dicas, conselhos e conhecimentos. Ninguém aprende nada sozinho, tudo nesta vida é construído com união. 

REGRAS DO PROJETO

    • Todos terão acesso ao conteúdo do projeto, inclusive de participar, atualizar, corrigir e construir. Basta mandar seu pull request
    • Todos os tópicos terão que ser explicados de maneira simples e didática. Use a imaginação.
    • Cada conteúdo criado será enumerado no sumário, junto de sua categoria e subcategoria. 
    • Para tornar o conteúdo ainda mais rico e completo, está permitido o uso de links externos: artigos, vídeos, sites e etc. 
    • Ao final deste projeto teremos um capítulo chamado: “Roteiros e experiências”. Nele serão compartilhados dicas, conselhos e experiências sobre diversas áreas, incluindo sites, canais e fontes pessoais. Sim, divulgação de trabalho está permitida. 
    • O Objetivo deste projeto será agregar e centralizar o máximo de projetos possíveis. Seu diferencial é ser PESSOAL
    • Seja livre para críticas e sugestões. 


INTERNET E WEB

	Este capítulo é totalmente reservado a tópicos sobre web e internet. Inclui protocolos, navegadores, funcionamento, segurança e etc.

    1. Protocolos de rede:  Para que nós, seres humanos, possamos nos comunicar, é necessário que a gente fale a mesma língua, né? Isso também acontece com os computadores, para que todos eles possam se comunicar na rede, é necessário que eles falem a mesma linguagem. O protocolo de rede funciona exatamente dessa forma, como um idioma que os computadores usam para se comunicar, independente da marca, do hardware, do sistema operacional, do modelo, fabricante e etc. 
Existem diversos tipos de protocolos de rede, cada qual dividido em camadas, dependendo de sua natureza. Mas não se preocupe, porque vou explicar a função de cada um deles, inclusive das camadas

    2. Camadas de rede (Modelo OSI): Vamos pensar da seguinte forma: Para que haja essa comunicação entre todos os computadores na rede, é necessária diversas funcionalidades e etapas? Tanto que temos diversos protocolos. As camadas na rede, além de estabelecer regras e orientações para essa conectividade, também divide as funcionalidades dentro de suas respectivas funções. (Mais abaixo colocarei alguns links para que vocês possam se aprofundar ainda mais no assunto). Temos no total sete camadas: Física, Enlace, rede, transporte, sessão, apresentação e sessão. Cada uma delas com suas funções.
	2.1. Camada Física: De forma bem resumida, é simplesmente toda a parte física da rede: Cabos, repetidores, Hubs, modem, fibra ótica e etc. A unidade de transmissão nessa camada é o bit.
	2.2. Camada de enlace: Esta camada é responsável por corrigir os erros da camada física, assim como também é responsável pelo controle de fluxo e transmissão de dados. Os nossos lindos Switches (Não é o vídeo game da Nintendo) trabalham nessa camada, utilizando o MAC ADRESS para encaminhar o pacote ao dispositivo correto. O nosso maravilho MAC se converte em endereço IP.
	2.3. Camada de rede: aqui é realizado o enderaçamento dos dispositivos na rede. Para ficar mais claro, seria tipo um GPS, determinar quais caminhos as informações devem percorrer para chegar até o destino. Aqui também o nosso endereço IP é convertido em endereço físico, garantindo que as informações cheguem. 
	2.4. Camada de transporte: Assim como a camada de enlace, ele também detecta e corrige os erros das camadas anteriores, Além disso também controla e ordena o fluxo de dados da origem até o destino. E não para por aí, sim, tem mais coisa. Garante a confiança do pacote, evitando erros, perdas e duplicações, garantindo segurança. É o bicho. 
	2.5. Camada de sessão: Responsável pelo controle de comunicação entre duas máquinas. Os filmes no cinema são divididos em sessão, correto? Isso significa que eles tem hora pra começar e terminar. A comunicação entre dois computadores também e essa camada é responsável por determinar quando deve começar, terminar e reiniciar.
	2.6. Camada de apresentação: Você sabe o que significa a criptografia de ponta a ponta do seu Whatsapp? Uso como exemplo porque é algo que faz parte do nosso dia a dia. Ela estabelece que só quem envia e recebe a mensagem terá acesso ao seu conteúdo. Como isso acontece? Simples! Quando você envia sua mensagem, ela é criptografada, convertida em um código que somente o dispositivo da outra pessoa será capaz de traduzir, ou seja, converter na mensagem legível. A camada de apresentação seria como um tradutor, responsável por garantir essa comunicação de forma efetiva
	2.7. Camada de aplicação: Essa é a camada que nós mais temos contato, a interface de todos os serviços que usamos: Como e-mail, redes sociais, navegadores e etc. 

    3. Modelo TCP/IP: Diferente do modelo OSI, este modelo tem apenas quatro camadas: Enlace, Internet, Transporte e Aplicação. A enlace nesse modelo é a união da 1ª e da 2ª camada do modelo OSI; a Internet é a 3ª camada da OSI; A transporte é a 4ª camada da OSI; já a camada aplicação é a união da 5ª, 6ª e 7ª camada do modelo OSI. Caso ainda não saiba o que são os protocolos TCP e IP, aconselho a ler sobre os conceitos aqui mesmo neste artigo. Apesar de, tecnicamente, ter menos camadas, este é o modelo mais usado ultimamente. 

		Agora vamos explicar cada um dos protocolos de rede

    4. Lista dos protocolos de rede: 

4.1. HTTP:  abreviação de HyperText Transference Protocol, que nada mais é do que o protocolo padrão da Internet. É por ele que os navegadores requisitam aos servidores as páginas na internet e vice- versa. Tanto a requisição do navegador, quanto a resposta do servidor. De forma simples. Podemos defini-lo como um protocolo cliente-servidor. Cado queira se aprofundar mais sobre o assunto: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Overview

4.2. FTP: É um protocolo de transferência de arquivo. Este protocolo funciona tanto do lado do cliente, quanto do servidor. Tem como função transferir arquivos e ficheiros entre dispositivos, inclusive armazenamento de arquivos de forma remota. Também temos o SFTP que é o FTP com uma camada de segurança

4.3. TCP:  O Protocolo de controle de transmissão, tem como objetivo garantir que os dados sejam integralmente transmitidos, na sequência de envio, para os hosts de destino corretos. Os dados enviados são quebrados em blocos menores de informação, os datagramas, e recompostos no host de destino. Ele também é responsável pelo reenvio da transmissão, no caso de impossibilidade de recuperação do pacote e dados.
  



