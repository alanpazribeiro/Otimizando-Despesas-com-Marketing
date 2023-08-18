# Otimizando-Despesas-com-Marketing

## Objetivo do Projeto
Analisar a carteira de clientes e otimizar as despesas com Marketing 

## Bibliotecas Utilizadas
- Pandas
- Matplotlib
- Numpy
- Scipy
- Math
- Seaborn

## Descrição dos Dados:
1 - Tabela visits:
 - *Uid* — identificador unívoco do usuário
 - *Device* — dispositivo do usuário
 - *Start Ts* — data e hora do início da sessão
 - *End Ts* — data e hora do final da sessão
 - *Source Id* — identificador da origem do anúncio através do qual o usuário chegou
 -  *Todas as datas nesta tabela estão no formato YYYY-MM-DD.

2 - A tabela orders (dados sobre os pedidos):

 - *Uid* — identificador unívoco do usuário que faz um pedido
 - *Buy Ts* — data e hora do pedido
 - *Revenue* — a receita da Y.Afisha com o pedido

3 - A tabela costs (dados sobre as despesas com marketing):

 - *source_id* — identificador da origem de anúncio
 - *dt* — data
 - *costs* — despesas com esta origem de anúncio neste dia
     
## Análises Feitas e questionamentos respondidos:

1 - Comportamento do Usuário
 - Quantas pessoas usam-no cada dia, semana e mês?
 - Quantas sessões ocorrem por dia? (um usuário pode realizar várias sessões).
 - Que comprimento tem cada sessão?
 - Com que frequência os usuários voltam?

2 - Vendas
 - Quando as pessoas começam a comprar?
 - Quantos pedidos os clientes fazem durante um determinado período de tempo?
 - Qual é o volume médio de uma compra?
 - Quanto dinheiro eles trazem para a empresa (LTV)?

3 - Marketing
 - Quanto dinheiro foi gasto? No total/por origem/ao longo do tempo
 - Quanto custou a aquisição de clientes para cada origem?
 - Os investimentos valeram a pena? (ROI)

## Conclusões 

 - Qual a recomendação aos especialistas de marketing quanto dinheiro e onde seria melhor investir.
 - Quais origens/plataformas você recomendaria? Fundamente sua escolha: em quais métricas você se concentrou? Por quê? Que conclusões você tirou ao encontrar os valores das métricas?
