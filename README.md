# Desenvolvedores do Programa [Projeto CMA02]
:: Natália Botelho Gomes Fávaro ::
:: Eduardo da Silva Norberto ::
:: Bianca da Silva Pinto ::

# Últimas Modificações
:: Os processos de triagem e prensagem foram inseridos em um único processo [processamento];
:: O menu foi alterado, trocando Triagem e Prensagem por Processamento e adicionando Rendimentos;
:: O novo menu Rendimentos consiste em informar os salários dos funcionários, valores gastos com transporte e manutenção e calcular o lucro obtido com a reciclagem;
:: Foram inseridos structs dos materiais reciclados para venda e rendimento dos funcionários;
:: Foi consertado a string dos nomes dos materiais (o erro estava na quantidade de caracteres);
:: Foi detectado erro no momento em que deveria aparecer a tabela com o nome do local com a quantidade de reciclados vendidos;


# Variáveis da Etapa 1

# sistema_reciclagem_resíduos 
Cálculo do lucro da usina de reciclagem de lixo

|Nome do campo|Tipo|Descrição|
|reciclagem|resíduos|lucro|
|----------|---------|--------|
|peso_mat_coletado|Real|Campo que armazena o peso de cada material coletado|
|peso_mat_processamento|Real|Campo que armazena o peso de cada material destinado ao processamento|
|peso_mat_estoque|Real|Campo que armazena o peso de cada material destinado ao estoque|
|mat_saida_estoque|Real|Campo que armazena o peso de cada material retirado do estoque|
|peso_mat_reciclado|Real|Campo que armazena o peso de cada material reciclado|
|peso_mat_espera|Real|Campo que armazena o peso de cada material reciclado com destino ao armazém|
|peso_mat_armazem|Real|Campo que armazena o peso de cada material reciclado e armazenado no armazém|
|peso_mat_descarte|Real|Campo que armazena o peso de cada material não processado a ser descartado|
|peso_mat_venda|Real|Campo que armazena o peso de cada material a ser retirado do armazém|
|valor_mat_coletado|Real|Campo que armazena o valor em peso de cada material coletado|
|valor_mat_reciclado|Real|Campo que armazena o valor em peso de cada material reciclado|
|valor_mat_estoque|Real|Campo que armazena o valor em peso de cada material guardado no estoque|
|valor_mat_armazem|Real|Campo que armazena o valor em peso de cada material guardado no armazém|
|valor_mat_descarte|Real|Campo que armazena o valor em peso de cada material a ser descartado|
|valor_mat_venda|Real|Campo que armazena o valor em peso de cada material a ser retirado do armazém|
|mes_maior_rendimento|Cadeia de caracteres|Campo que armazena o mês com maior rendimento|
|dia_maior_rendimento|Cadeia de caracteres|Campo que armazena o dia da semana com maior rendimento|
|cap_processamento|Real|Campo que mostra a capacidade total do processamento|
|cap_armazem|Real|Campo que mostra a capacidade total do armazém|
|cap_estoque|Real|Campo que mostra a capacidade total do estoque|
|cap_descarte|Real|Campo que mostra a capacidade total do descarte|
|local_processamento|Cadeia de caracteres|Campo que armazena o local onde o material será processado|
|local_armazem|Cadeia de caracteres|Campo que armazena o local do material reciclado|
|local_estoque|Cadeia de caracteres|Campo que armazena o local do estoque do material a ser processado|
|local_descarte|Cadeia de caracteres|Campo que armazena o destino do material a ser descartado|
|local_retirada|Cadeia de caracteres|Campo que armazena o destino do material posto a venda do armazém|
|funcionarios|Real|Campo que armazena o gasto com funcionários|
|transporte|Real|Campo que armazena o gasto com combustível e manutenção dos veículos|
|manutencao|Real|Campo que armazena o gasto com a manutenção do local onde é realizada a reciclagem|
|lucro_reciclagem|Real|Campo que armazena o valor do lucro obtido pela venda do material reciclado|
