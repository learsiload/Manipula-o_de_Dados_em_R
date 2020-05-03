# Manipula-o_de_Dados_em_R

PACOTES PARA MANIPULAÇÃO DE DADOS EM R

#### tidyr ####

tidyr -> Remodelagem de dados, converter colunas em linhas e vice-versa,
mudança no formato de dados. Mudar o formato(shape) dos dados

gathe() -> linha para colunas
spread() -> coluna para linhas
separete() -> divide um a coluna em 3
unite() -> uni 3 colunas em 1

shape significa formato de dados.

#### dplyr ####

dplyr -> Transformação dos dados.

selet() -> selecionar dados
filter() -> filtra os dados aplicando uma regra
group_by() -> agrupar os dados
summarise() resumo
arrange() -> organizar linhas em uma ou mais colunas
mutate() -> realizar cálculos dentro de uma mesma coluna
join() -> unir dois ou mais dataset

#### Operador de Contatenação ####

%>%  ->  é útil utilizar quando precisa usar varias funções dentro de um dataset,
sem precisar ficar repetindo o dataset em todas as funções.

exemplo: filter(data, variable == numeric_value)   (sem uso do %>%)

data %>% filter(variabrle == numeric_value)  (neste caso resolveria)
