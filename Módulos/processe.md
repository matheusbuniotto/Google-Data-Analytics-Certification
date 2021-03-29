# Processe

### O processo analítico
- objetivo: identificar padrões e relações para responder perguntas

### Lidando com valores faltantes
- problemas comuns
  - somente 1 fonte
  - dados que não param de chegar
  - dados "outdated"

![img](https://github.com/matheusbuniotto/presets/blob/main/google/dados%20faltantes.png?raw=true)

[Leitura](https://www.notion.so/mbntt/O-que-fazer-com-dados-faltando-ae79a778617943a59b49114b2755f34b)

### Importância do tamanho da amostragem
- Poder estatístico 
- Ao menos 80%!
  
<b>Margem de erro</b>
O máximo que esperamos que os restultados da amostra sejam diferentes da população. Contado em ambas as direções.

## Tratando os dados
>Why transform data?
<b>Goals for data transformation might be: </b>
Data organization: better organized data is easier to use
Data compatibility: different applications or systems can then use the same data
Data migration: data with matching formats can be moved from one system to another
Data merging: data with the same organization can be merged together
Data enhancement: data can be displayed with more detailed fields 
Data comparison: apples-to-apples comparisons of the data can then be made 

### Técnicas e ferramentas
Antes de começar o processo, precisamos de um backup!

- Dados duplicados
- Espaços em branco
- Erros de digitação
- Formatação
  
Limpar os dados de diferentes fontes
<b> prezar pela compatibilidade dos dados de fontes diferentes </b>

#### Questões importantes:
- Tenho todos os dados que preciso?
- Eles existem em quais dataset?
- Precisam ser limpos?

#### Features das planilhas
- formatação condicional
- remover duplicados
- formatar
- texto
  - substring
  - len
  - split
  - trim
  - concat
  - 
 > Atividades práticas no Spreadsheet: AVG, Substring, SPLIT, TRIM, CONCATENAR, VLOOKUP
#### Otimizando data cleaning
<b> Funções</b>
- COUNTIF
- TRIM
- LEN
- LEFT/RIGHT/MID
- CONCATENATE

<b> Perspectivas diferente </b>
- Sort e filter
- pivot table
- vlookup
- gráficos
- data mapping

#### SQL
<b> Mais usadas </b>
- SELECT
- INSERT INTO
- FROM
- WHERE
- AGREGAÇÕES (SUM, AVG, MIN, MAX...)

<b> Limpar Strings</b>
- TRIM
- SELECT DISTINCT
- SUBSTR
- IS NULL
- SET
- DELETE
- UPDATE
- SET

<b> Avançados </b>
- CAST
- WITH
- BETWEEN
- COALESCE
- CASE
  
> Atividades práticas no BigQuery: CASE, WITH, WHEN, HAVING, TRIM, SUBSTRNG

[SQL In-depth best pratices](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e100fb53-895c-444f-b56d-b2d24e3b69fa/In-depth-guide_-SQL-best-practices.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210328%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210328T214153Z&X-Amz-Expires=86400&X-Amz-Signature=0e5395d294ce455346ac6a8e4ca467eb0e9842ba682b800e87dd56110f233fa1&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22In-depth-guide_-SQL-best-practices.pdf%22)

## Verificar os resultados

Verificar se o processo de limpeza foi realizado corretamente.

- Changelog: armazena as alterações em ordem cronológica 
  
<b> Verificar </b>
- Comparar dataset antigo com o limpo
- ver a "big picture" para verificar se os dados estão alinhados com o objetivo do negócio
    - Considerar o problema de negócio
    - Considerar o objetivo
    - Considerar os dados
Nas últimas etapas, podemos utilizar uma pivot table para sumarizar e comparar os dados.

No SQL podemos usar CASE para itinerar os valores.

#### Registrando mudanças
- documentar os passos realizados
<b> Benefícios </b>
    - recuperar erros
    - documentar para outros usuários
    - determinar qualidade

no spreadsheet existe o version history

no SQL existe o QUERY history

### P.A.R.
Problema > Ação > Resultado
- solução de problemas

### 4 fases<b>
> 1. Organizar os dados
> 2. Formatar e ajustar
> 3. Input dos outros
> 4. Transformação </b>

### Processamento
- Sort e filters (SORT, SORTRANGE)  
- SQL: ORDER BY

<b> Converter e formatar os dados no começo do projeto</b>

### Validação 
- Permite controlar o que pode ou não ser inserido no worksheet (drop-down/checkbox)
- Ajuda a proteger entradas
- Formatação condicional

