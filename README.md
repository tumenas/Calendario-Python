# Calendario-Python

Uma das tarefas mais básicas na precificação de ativos financeiros é determinar as datas dos fluxos de pagamento. Porém, as datas dos pagamentos são necessariamente em dias úteis, o que gera a necessidade de determinar se, além de ser dia da semana, um dia é feriado ou não.

Para isso, a Anbima disponibiliza arquivos com os feriados brasileiros para vários anos (http://www.anbima.com.br/feriados/feriados.asp).

Este código busca realizar essa tarefa, determinar se um dia é útil ou não, via biblioteca Pandas do Python sem depender de nenhum arquivo externo.

