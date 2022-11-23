# Clusterização de Lojas 

Este é o projeto final da capacitação de ciência de dados da VAI Academy  
Foi realizado por um time, no qual nomeamos de Equipe Delta, composta por:
- Bruno Soares
- Ciro Rosa
- Jhonata Feitosa
- Ramon Moreira

## O Desafio:
A empresa A-Tech atua no mercado brasileiro de varejo desde 2005. São 45 lojas físicas
distribuídas em diferentes regiões. Cada loja possui diversos departamentos, nos quais as vendas
acontecem.  
Os eventos que acontecem ao longo do ano afetam bastante as vendas, mas cada departamento
é afetado de forma diferente. A empresa A-Tech também faz ofertas ao longo do ano sempre
antes de eventos importantes. Os principais eventos são: Carnaval (Fevereiro), Independência
(Setembro), Black Friday (Novembro) e Natal (Dezembro). As remarcações de preços/descontos
que acontecem antes desses eventos impactam as vendas e têm um peso cinco vezes maior na
avaliação do que as semanas que não possuem feriado.  

Uma das duas perguntas tem que ser respondida:

1. Previsão da demanda – Qual o planejamento da venda nos departamentos e lojas para
os próximos 6 meses? Quais as variáveis mais importantes na previsão?
2. Segmentação de lojas - Sabemos que nem todas as lojas são iguais. Algumas lojas têm
sazonalidade mais forte, outras são mais afetadas pelos feriados e algumas lojas são afetadas
também pela região na qual estão localizadas. O entendimento desses grupos facilita a gestão dos 
estoques e metas dos gestores. É possível segregar as lojas em grupos? Quais as características
de cada grupo?

Então, decidimos focar nossos esforços na segunda pergunta e fazer uma previsão de demanda bem rápida, 
mais como um bônus. Além de fazer uma boa análise exploratória.

## Bases de dados fornecida:  
1. Lojas - Informação anônima de 45 lojas, com indicação do tipo e a dimensão da loja  
a. Loja - número da loja  
b. Tipo_De_Loja - indica o tipo da loja  
c. Tamanho - indica o tamanho da loja    

2. Características - Dados adicionais relacionados à loja, departamentos e atividade regional
para as datas especificadas  
a. Loja - número da loja  
b. Data - semana  
c. Preco_Combustivel - custo médio do combustível na região  
d. IPC - Índice de Preços ao Consumidor  
e. Taxa_Desemprego - a taxa de desemprego  
f. Evento - se a semana possui algum feriado relevante    

3. Vendas - Dados históricos de vendas (05/02/2010 - 26/10/2012)  
a. Loja - número da loja  
b. Departamento - número do departamento  
c. Data - semana  
d. Venda_Semanal - vendas para algum departamento em alguma loja  
e. Semana_De_Evento - se a semana possui algum feriado relevante  

## Índice do nosso projeto:
1. Leitura das bases consumidas
2. Análise dos dados
3. Construção da base de dados para clusterização
4. Clusterização
5. Entendimento dos clusters
6. Análise de outras variáveis
