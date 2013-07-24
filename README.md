cidades-estados-brasileiros
===========================

Cidades, estados, e UF do Brasil.

Edit: Atualizado em 24/07/2013. Fonte IBGE. 5,570 Municípios.

Inicialmente publiquei no Gist, porém a array pesava muito por lá.
https://gist.github.com/SushiNaBrasa/6067537

Usei parte do scritpt do Paulo Freitas, que ajudou respondendo  minha publicação no grupo PHP Brasil.
Paulo elegantemente usando DOMDocument() cria uma Shema SQL utilizando:

http://www.ibge.gov.br/cidadesat/download/mapa_e_municipios.php?uf=sp // Onde 'sp' quando substituido por 'pr' resulta na query do estado do Paraná.

Em meu caso gravei a resposta em JSON. E como minha conexão é lenta alterei o set_time_limit().

Paulo Freitas Gist: https://gist.github.com/paulofreitas/6068224
Grupo PHP: https://www.facebook.com/groups/nao.tem.biscoito/10153135985695160/

