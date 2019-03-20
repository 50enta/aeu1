# Votação electronica


## Introdução

Na Universidade Eduardo Mondlane, existe uma associação dos estudantes Universitários designada AEU-UEM. Tal instituíção foi criada para dar suporte aos estudantes em diversas situações.
A associação é grande o suficiente para dar suporte aos estudantes de toda a Universidade Eduardo Mondlane, a maior Universidade do país. 
A associação abrange toda a Universidade e por essa razão precisa de Recursos humanos para o fazer da melhor forma possível. É perante este cenários onde se sentiu necessidade de melhor estruturar a organização, que é com base na eleição do presidente e consequentemento o presidente atribui confiança à membros de sua lista para cargos de confiança. 

### 1.1.	Contextualização
O que está em causa é o processo de eleição do presidente da AEU-UEM da forma mais transparente possível.
### 1.2.	Objectivos
#### 1.2.1.	Objectivo geral
Propor um sistema para submissão de votos de forma electrónica.
#### 1.2.2.	Objectivo específico
•	Analisar o atual sistema de submissão de votos;
•	Propor uma solução para submissão de votos de forma eletrónica;
•	Reduzir sigificativamente os custos e a falta de confiança durante o processo;

 



## Apresetação do problema
Tal como foi descrito no ponto 1 (Introdução e objectivos), o trabalho em volta do processo de eleição do presidente da Associação dos estudantes Unisersitários da Universidade Eduardo Mondlane. 
### 2.1	Descrição 
Actualmente os votos são submetidos e econtados de forma manual
Quando chega o dia de votar, a entidade responsável por moderar as eleições, têm a missão de criar condições para que os estudantes o façam. 
São espalhadas urnas para introdução dos formulários para votar em todas as faculdades, escolas ou departamentos, onde os estudantes precisam se aproximar, se identificarem e depois têm acesso ao formulário onde irão destacar o candidato desejado e iseri-lo na urna. 
#### 2.1.1.	Vantagens 
•	 O estudante apresenta o seu cartão de estudante durante o voto;
•	
#### 2.1.2.	Desvantagens
•	 Muitos votos falsificados;
•	O estudante precisa de tempo para suportar a fila, o que pode levá-lo a desistir;
•	Contagem dos votos feita manualmente, e consequentemente uma margem de erro maior;
•	Várias portas abertas para a corrupção;
•	
 



## Propostas de solução

O modelo proposto consiste em um sistema Web e USSD que permitirá efectuar a submissão dos votos durante a eleição. 
### 4.1.	Aplicação WEB 
Nesta aplicação, as tarefas que serão automatizadas partem desde o registo da eleição, candidatos até ao processamento dos resultados finais em forma de números, gráficos e todos os meios interessantes possíveis garantindo a transparência no processo.
Basicamento quem terá acesso à aplicação Web são membros da assembleia (A entidade da AEU responsável por moderar o processo das eleições).
As funcionalidades serão as básicas necessárias, para garantir que não tenham privilégios desnecessários sobre o processo.
 
### 4.2.	Aplicação USSD
4.2.1.	 Visão geral? (Overview)
Esta aplicação é a interface entre os estudantes e a plataforma de votos, a partir da qual os estudantes poderão submeter os votos, consultar os candidatos e outras informações relevantes sobre o processo.
Algumas funcionalidades desta aplicação só estarão disponíveis apenas na data de votação e no horário em que estará a decorrer.
#### 4.2.2.	 Como funcionará?
A aplica,cão USSD funcionará da seguinte forma: Chegado o dia de votar, os estudantes acessarão as funcionalidades a partir de um menú após digitar o código USSD em seus telemóveis (tomemos com exemplo o código: *132*76#), escolhendo o número correspondente à funcionalidade no menú terá acesso ao mesmo.
Para a votação, cada número de celular irá votar apenas uma única vez, e depois só teraá acesso às demais funcionalidades relativas ao processo. 
Os contacto que cada estudante irá utilizar, será o mesmo que o informado no Sistema de Académica (SIGA) e associado ao seu número de estudante por questões de segurança. 
 
### 4.3.	Vantagens e desvantagens
#### 4.3.1.  Vantagens
•	 O estudante poderá votar a partir de qualquer ponto;
•	Sem custos para o estudante;
•	Redução significativa do número dos estudantes que não votavam;
•	Processamento automático dos votos;
•	
#### 4.3.2. Desvantagens
•	 Celebração de contractos com as operadoras (Vodacom, tMcel e Movitel) para a utilização dos serviços USSD e SMS;
•	Enfrentar a burrocracia durante a bsuca de dados dos estudantes (número do estudante, contacto, estado e outros) a partir da API do SIGA;
•	

