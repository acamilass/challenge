# Desafio Data Science

## Objetivo
- Implementar um modelo que retorne a probabilidade que um cliente tem de ser enviado para análise de crédito dado que ele foi pré-aprovado para o empréstimo com garantia de automóvel. 
- Além da implementação do modelo é esperado que o candidato faça a **avaliação** do mesmo, de maneira a entender o motivo pelo qual o modelo apresentado resolve o problema, incluindo quais atributos são mais importantes para o modelo e o motivo.
- É necessário apresentar também a **análise exploratória dos dados**, incluindo as variáveis que foram eliminadas e os motivos.

## Dataset
- Todos os dados necessários para modelagem estão no arquivo `dataset.csv`.
- A descrição dos dados está no arquivo `description.csv`.
- Nesta base estão todos os clientes que entraram no site, mesmo aqueles que não foram pré-aprovados, sendo necessário filtrar os clientes válidos.

 ## Você deve

 - Escrever uma defesa para sua solução, descrevendo **DETALHADAMENTE** todas as etapas utilizadas para resolver o problema: a conceptualização, como realizou as descobertas, as técnicas/algoritmos utilizados e as soluções para cada um dos problemas encontrados. É necessário detalhar/justificar com *gráficos* e *tabelas* as descobertas.
 Você deve fazer isso em um arquivo separado, no formato `.pdf`, `.md` ou `.txt`. Atenção! O relatório não deve ultrapassar 5 páginas.
 - Mandar a sua solução em código Python ou R. O uso de bibiliotecas é livre, mas você deve ser capaz de explicar o conceito dos algoritmos utilizados de maneira sucinta, ou seja, como eles funcionam e porque os escolheu para uso.
 - Além do desenvolvimento da solução é necessário mostrar métricas de avaliação da solução desenvolvida. É necessário apresentar a matriz de confusão do(s) modelo(s) desenvolvido(s), além de outras métricas de avaliação. Pontos extras para o uso do ROC/AUC. Além das métricas é necessário enviar a avaliação dos atributos do modelo e uma possível explicação para o porque o modelo apresentado é bom.
 - Enviar o modelo final para que seja possível testá-lo com um novo conjunto de dados. Para isso você deve garantir que o seu código seja reproduzível e explicar como deveremos rodá-lo no relatório.

### Atenção
 - Os dados não estão normalizados. O cliente pode ter preenchido valores incomuns em alguns campos, como a renda.
 - Alguns dados estão faltando. Faz parte do exercício entender como que os dados faltantes serão tratados (ou justificar se não o serão).
 - Você poderá usar dados externos, desde que explique **detalhadamente** quais dados usou e como o fez.
 - Não há um limite fixo de tempo, porém é estimada que uma semana é mais que o suficiente para para resolver o problema.

## Avaliação
Para nos enviar seu código, você pode:
- Dar acesso ao seu repositório privado no Bitbucket para `creditaschallenge`.
- Mandar um email para `ds-squad@creditas.com.br`
