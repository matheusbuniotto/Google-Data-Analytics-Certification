### Dados internos e externos
Dados primários
Dados secundários/externos

![img](https://github.com/matheusbuniotto/presets/blob/main/google/estrutura.png?raw=true)



- Estrutura de dados
    - Longa - cada linha é um ponto, compacta.
    - Larga
Exemplo longa:
![longa](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dq8jjvDiQgmvI47w4hIJsA_ffb38f9200364ce7862d8848c8147a19_Screen-Shot-2020-11-24-at-5.42.01-PM.png?expiry=1617062400000&hmac=R1sEQcCdv4uSB6j0rrVu6QRa-WXcJGc9lqOO1XMHd8U)


Exemplo larga:
![larga](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/5IiB_OOFR_eIgfzjhVf3VA_5066f31f0192481980d15830caf61b8e_Screen-Shot-2021-03-17-at-3.00.51-PM.png?expiry=1617062400000&hmac=q25ovKemU7vdeXWqJV3WuNWUqKHgteSOIKetbyOKSvk)

### Viés
Preferência em relação a algo

- [Viés de Amostragem](https://github.com/matheusbuniotto/Estatistica/blob/main/Estudos/vi%C3%A9s_sele%C3%A7%C3%A3o.md)

- Viés de obervação

- Viés de interpretação

- Viés de confirmação

### Fonte de dados
- identificar boas fontes de dados 
  - ROCCC
  - R > reliable
  - O > original
  - C > comprehensive
  - C > 
  - C > cited

![img](https://github.com/matheusbuniotto/presets/blob/main/google/data-coleta.png?raw=true)

### Ética nos dados
<b> Princípios </b>
- Individuo
- Transparência
- consentimento
Dados são pessoas!

Uso ético dos dados
- quem somos?
- quais danos podemos causar?

### Base de dados
- Relacional
- PK e FK 
- Schemas
[Data formats in practice](https://www.notion.so/mbntt/Data-formats-in-practice-82234a17ad7043dbab42101767e6c4a3)

### Metadados
- exemplo das fotos
<b> 3 tipos comuns</b>
  - Descritivo: descreve o "pedaço" dos dados
  - Estrutural: como é organizado
  - Admnistrativo: indicativo técnico

>atividade SQL no BigQuery - agregações, where, select, from

### Organizando e protegendo os dados
- nomes: convenções
- pastas e subpastas
- arquivamento
- alinhado com equipe
- backups
<b> Deve ser considerado no começo do projeto</b>

#### Nomear
-<b> Do's </b>
  - curto e simples
  - incluir datas
  - incluir revisão
  - não usar espaço
  - criar agrupamento

[More about data integrity and compliance](https://www.notion.so/mbntt/More-about-data-integrity-and-compliance-e9a1d0ec4788496787a9221699616865)

### Processos 
- Integridade dos dados
  - Acurácia
  - Completidade
  - Consistência
  - Confiabilidade


### Balancear objetivo e integridade
- Os dados devem estar alinhados com o objetivo da análise
- ver a "foto completa"

> #### Clean data + alignment to business objective = accurate conclusions
> #### Alignment to business objective + newly discovered variables + constraints = accurate conclusions

[Leitura](https://www.notion.so/mbntt/Well-aligned-objectives-and-data-6a236448fbf042e8ae774a23dae5debd)

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



