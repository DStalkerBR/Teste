# Projeto desenvolvido em equipe.

Script Python que permite ao usuário gerenciar e analisar várias listas de dados, incluindo nomes, salários, datas e idades. O script fornece um menu de opções para o usuário, permitindo que ele adicione dados a qualquer uma das listas, percorra as listas, calcule o valor da folha de pagamento com um reajuste de 10% e modifique as datas anteriores a 2019.

## Arquivos

O projeto consiste em dois scripts Python:

- `exercicio1.py`: Este script corresponde à primeira parte da avaliação em equipe.
- `equipe.py`: Este script corresponde à segunda parte da avaliação em equipe, especificamente ao terceiro exercício.

## Classes

O script contém várias classes, incluindo:

- `Data`: Representa uma data com dia, mês e ano.
- `AnaliseDados`: Classe abstrata que define a estrutura para análise de dados.
- `ListaNomes`, `ListaSalarios`, `ListaDatas`, `ListaIdades`: Estas classes herdam de `AnaliseDados` e implementam métodos específicos para lidar com diferentes tipos de dados.

## Funções

O script também contém várias funções, incluindo:

- `incluir_nome`, `incluir_salario`, `incluir_data`, `incluir_idade`: Estas funções permitem ao usuário adicionar dados às respectivas listas.
- `percorrer_listas`: Esta função percorre todas as listas e imprime seus conteúdos.
- `calcular_folha_salarios`: Esta função recalcula a folha de pagamento com um reajuste de 10%.
- `modificar_datas_antes_2019`: Esta função modifica todas as datas anteriores a 2019 para 01/01/2019.

## Execução

Para executar o script, basta rodar o comando `python equipe.py` no terminal. Em seguida, siga as instruções no menu de opções.