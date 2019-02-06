# Gerenciamento de Big Data

O gerenciamento de *big data* garante um certo nível de qualidade e acessibilidade para *BI* e *análise de dados*. O gerenciamento de big data incorpora regras, técnicas e processos para coletar, armazenar, administrar e entrega de grande repositórios de dados. Os passos involvidos pode ser a limpeza, integração, migração e reportações.

## Data Ingestion
Refere-se ao processo de aquisição de dados no sistema. Significa a ingestão de dados no ambiente que estamos construíndo.

### Ingestion Policies
  Regras que guiam o tratamento de erros, assim como incompleticidade de informação e outras coisas.

## Data Storage
Tem como objetivo armazenar os dados. Existem dois tópicos que devem ser levados em consideração:

 * Capacidade: Quanto de armazenamento deve ser alocado (ou o tamanho da memória) para armazenar os dados.

 * Escalabilidade: Os dispositivos de armazenamento devem ser escaláveis, pois é esperado que o volume de dados cresça com o tempo. Também leva em consideração a abilidade de conexão com a rede para armazenamento extra ao longo do tempo.

Em sistemas big data temos escolha de arquitetar a infra-estrutura de armazenamento escolhendo o quanto de cada tipo de armazenamento precisamos ter. A utilização de SSDs permite uma busca de dados mais rápida (10 vezes mais rápida no mínimo) apesar de aumentar os custos.

## Data Quality

É importante que os dados armazenados sejam de qualidade, livre de erros e destinado ao seu próposito pretendido. Dados de alta qualidade geram *insights* de qualidade, já dados de baixa qualidade geram insights de péssima qualidade, logo, decisões equivocadas. Em certas industrias erros podem quebrar regulamentações e levar a complicações legais. Os fatores a seguir podem ajudar a avaliar a qualidade dos dados.

  * Completicidade: Existem valores faltantes?
  * Validade: Os dados correspondem ao conjunto de regras.
  * Unicidade: Os dados tem mínimas redundancias.
  * Consistência: Os dados são consistentes entre vários *data stores*.
  * Pontualidade: Os dados representão a realidade requisitada de um ponto no tempo.
  * Acurácia: O grau em que determinada métrica, calculo ou especificação está de acordo com o valor correto.


## Data Operations

Um aspecto significante do gerenciamento de dados é a documentação, definição, implementação e teste de conjunto de operações que são requeridas para um grande conjunto de aplicações. Em resumo existem dois grupos de operações que são utilizados para o gerenciamento:

  * Uma operação que funciona em um objeto único: Como exemplo, uma operação que corta uma imagem, extráindo uma sub-área dos pixels é uma operações de objeto único, pois a imagem é um objeto único.

  * Uma operação que funciona em um conjunto de objeto de dados: Essa operação trata de combinar duas coleções de dados, com o objetivo de formar um objeto ainda maior.

## Escalabilidade e Segurança

A maioria dos sistemas de gerenciamento são desenhados para operar em um *cluster* de máquinas hoje em dia, e possuem a abilidade de se ajustar quando mais máquinas são adicionadas ao cluster ou quando alguma delas falha.

Segurança é uma característica do sistema de proteger os dados de acessos não autorizados enquanto provê acessos para pessoal autorizado.

Escalabilidade envolve o impacto de adicionar ou remover recursos, e as métricas iram refletir a disponibilidade e empréstimo atribuídos à recursos novos ou já existentes.
