# Teste - Engenharia de Dados (Short Track 2)

O seguinte teste tem por premissa ser um problema base (Ref. <a href="https://teaching.cornell.edu/teaching-resources/engaging-students/problem-based-learning">problem based learning</a>) de modo que você pode usá-lo como achar adequado tendo em vista a demonstração de seus conhecimentos técnicos.

Queremos entender melhor seu jeito de atacar problemas desafiadores em ambiente GCP como no trabalho do dia a dia. Portanto, recomendamos ainda que o teste seja feito em no máximo 4 horas (não se preocupe em respostas muito detalhadas ou em complexidades que simplesmente não funcionariam no mundo real!).

As entrega deve ser via envio de link para um github público (ou similar) o qual contenha sua solução para o cenário a seguir:

## Cenário

No seguinte cenário você é a pessoa engenheira de dados por trás do projeto de data ops junto a uma grande operadora de cartões de crédito. Os dados a serem ingeridos e analisados em nossa plataforma de Big Data são dados de compras (trasacao), documentos (contrato) e dados de compradores (cliente).

## Entregável

-1) Imagine que o Json das notas fiscais é disponibilizado em uma API. Como você utilizaria as tecnologias da GCP para ingerir, transformar e, eventualmente, carregar esses dados em um BigTable? 

Este entregável consiste na construção de uma arquitetura de ingestão dos dados de nota fiscal do entregável anterior (como visto <a href="https://www.crystalloids.com/hs-fs/hubfs/Screenshot%202022-02-04%20at%2009-44-40-png.png?width=1232&name=Screenshot%202022-02-04%20at%2009-44-40-png.png">aqui</a>), a qual deve atender aos seguintes pontos:

- Esquemas de fluxo de dados;
- Descrições de funcionamento (se necessário);
- Nomes de tecnologias em ecossistema GCP (serviços, conectores, bibliotecas e módulos).

Será apreciado como esforço extra se você conseguir avançar mais na aplicação além desse ponto.

Lembre-se que, como parte do entregável, esperamos que alguns comentários sejam incluídos em sua solução; queremos entender melhor como foi seu processo de solução de problemas, quais as hipóteses levantadas e, se tivesse mais tempo, como você poderia melhorar a implementação proposta (desenvolvimento incremental).

Ou seja, temos o seguinte entregável:

- Arquitetura exemplo de ingestão de dados (ecossistema GCP);

## O que será avaliado?

1. Buscamos soluções bem definidas e baseadas em método: soube mostrar quais as hipóteses levantadas? Precisou ao menos de modo resumido o por que escolheu determinado caminho? Quais os prós e contras usados para se basear essa solução e quais os passos para implementá-la?
2. Qualidade dos entregável da arquitetura proposta.
3. Se tivesse mais tempo, o que você faria para melhorar a sua solução?
