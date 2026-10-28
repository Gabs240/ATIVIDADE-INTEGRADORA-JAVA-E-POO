# ATIVIDADE-INTEGRADORA-JAVA-E-POO

Parte I — Questões teóricas (90 minutos) 

Bloco A — Fundamentos de POO 

1.	Explique a diferença entre classe e objeto. Apresente um exemplo de cada um em um sistema acadêmico. 
2.	O que são atributos e métodos? Diferencie estado e comportamento de um objeto. 
3.	Qual é a função de new? Diferencie criar um objeto e declarar uma referência. 
4.	Explique encapsulamento. Por que evitar atributos públicos sem necessidade? 
5.	Qual é a finalidade do construtor? Explique o uso de this.

Bloco B — Relacionamentos e herança 

7.	Diferencie associação, agregação e composição; exemplifique. 
8.	O que é ArrayList e quando preferi-lo a um vetor de tamanho fixo? 
9.	Diferencie superclasse e subclasse. Explique extends e super. 
10.	Diferencie sobrecarga e sobrescrita de métodos; dê exemplos. 
11.	O que é polimorfismo? Como uma referência de superclasse aponta para objetos de subclasses?
    
Bloco C — Interfaces e projeto 

13.	O que é interface? Diferencie implements e extends nos exemplos estudados. 
14.	Compare herança e composição. Quando a composição é preferível? 
15.	O que é baixo acoplamento? Como a injeção por construtor ajuda? 
16.	Explique SRP, OCP e DIP com exemplos simples.
    
Bloco D — Padrões de projeto 

18.	O que é um padrão de projeto? Por que evitar aplicá-lo indiscriminadamente? 
19.	Explique Singleton e a finalidade do construtor privado e de getInstancia(). 
20.	Explique Factory Method e o papel dos criadores abstratos e concretos. 
21.	Como Strategy organiza descontos comuns, estudantis e promocionais? 
22.	Como Observer comunica um pedido confirmado a estoque, financeiro e auditoria? 
23.	Diferencie Adapter e Facade; dê um caso de uso de cada um.

Parte II — Construção prática guiada (90 minutos) 

Projeto: Sistema Acadêmico Simplificado. O sistema cadastra aluno e curso, aplica desconto, registra pagamento em um serviço legado, notifica observadores e emite comprovante. Os exemplos abaixo usam classes sem package para simplificar a execução. 
Cronograma 

•	0–15 min: modelagem de Aluno e Curso; Singleton de configuração. 
•	15–30 min: Strategy para políticas de desconto. 
•	30–45 min: Observer para notificações. 
•	45–60 min: Adapter para o sistema de pagamentos. 
•	60–75 min: Factory Method e Facade. 
•	75–90 min: compilação, testes e análise. 

Etapa 8 — Perguntas de análise da implementação 

1.	Qual classe implementa Singleton e quais instruções controlam a instância? 
2.	Onde aparecem encapsulamento e validação? 
3.	Qual é a relação entre Aluno e Curso? 
4.	Onde foi utilizada uma coleção e com qual objetivo? 
5.	Qual é o papel da interface Desconto? 
6.	Como acrescentar uma política de 20% sem alterar o serviço? 
7.	Quem produz o evento e quem recebe as notificações? 
8.	Por que o adaptador converte reais em centavos? 
9.	Qual método representa Factory Method? 
10.	O que FachadaAcademica simplifica para Main?
