# Contratos confrontados e conferência das diárias

Consulta em 20/11/2026. Os nove contratos encontrados no Portal Nacional de Contratações Públicas (PNCP) totalizam **R$ 799.510,18 em valores iniciais**. O recorte abrange os sequenciais 1 a 9 do órgão 10.222.495/0001-57 no exercício 2026. Os sequenciais 10 a 24 retornaram HTTP 404 na consulta. O cadastro municipal também contém instrumentos posteriores, entre eles a caminhonete. A soma representa apenas estes nove registros nacionais. A conciliação com pagamentos depende da execução financeira por credor.

## Três divergências esclarecidas

| Serviço | Valor maior no CSV municipal | Valor inicial no PNCP | Sequencial nacional |
|---|---:|---:|---:|
| Assessoria contábil | R$ 264.000.000 | R$ 264.000 | 7 |
| Impressão, serviços gráficos e bandeiras | R$ 53.400.000 | R$ 53.400 | 5 |
| Suporte tecnológico e transmissão | R$ 43.200.000 | R$ 43.200 | 3 |

Nos três casos, outro lançamento municipal já trazia o valor menor. A confirmação independente favorece erro de escala ou duplicação no cadastro/exportação municipal. O mecanismo do erro e eventual efeito sobre a contabilidade permanecem por verificar. A correção pública deveria alcançar tanto a ficha quanto o arquivo exportado.

## Publicidade dos contratos

Todos os nove registros indicam publicação no PNCP nos dias 28 e 29 de maio. As assinaturas se distribuem entre fevereiro e maio. A diferença em dias corridos varia de 14 a 113. Para a licença de identificação civil e a assessoria de recursos humanos, as assinaturas datam de 5 de fevereiro e as publicações de 29 de maio. Para a impressora, o intervalo foi de 90 dias. A concentração reduz a utilidade do PNCP para o cidadão que tenta acompanhar a contratação no momento da assinatura. A análise de eventual infração exige modalidade, prazo aplicável, demais meios de divulgação e histórico de transmissão.

## Viagens e resultados

O contrato inicial de agenciamento de passagens é de R$ 197.558,40. Para apurar o custo de cada missão, o dado necessário é a fatura dos bilhetes efetivamente emitidos, com estornos, associada à portaria de diária. Somar o valor global contratado às diárias autorizadas misturaria grandezas diferentes.

A licença anual do sistema de identificação civil foi contratada por R$ 6.289,10 com a PRODEPA. O objeto vincula a contratação à continuidade da emissão de carteiras de identidade. É despesa identificável em favor de um serviço ao cidadão. Para medir eficiência, faltam quantidade de documentos entregues, prazo de entrega e custos de pessoal e deslocamento.

## Verificação do histórico de diárias

Correção da contagem anterior: o CSV tem 474 linhas de dados, sendo **473 lançamentos datados e uma linha TOTAL GERAL**. Essa última linha traz inclusive nome próprio e deve ser excluída de qualquer ranking. A soma dos lançamentos datados confere com o total divulgado de R$ 1.408.470. A série inclui R$ 535.320 em 2024, R$ 253.200 em 2025 e R$ 619.950 em 2026 até a última portaria cadastrada, de 22 de outubro. A cobertura dos anos difere.

Dos 200 registros de 2026, sete, totalizando R$ 25.500, acionam ao menos uma das três verificações: três apresentam fim anterior à partida, três trazem cargo no campo destino e dois têm data da portaria posterior à partida. A portaria 256 aparece em duas categorias e entra apenas uma vez no total. Esses R$ 25.500 medem o valor a conferir. A existência de dano depende de prova de desembolso e análise das viagens.

Na nº 236 a partida consta em 2028 e o retorno em 2026. Na nº 230, a partida aparece em agosto e o retorno em junho. Na nº 133, ambas as datas da viagem antecedem a data registrada para a portaria. As peças prioritárias são o ato original assinado, o comprovante de deslocamento, a prestação de contas e o lançamento de pagamento.

## Arquivos e critérios

- [Nove registros do PNCP com URLs oficiais, fornecedor, objeto, valor e datas](pncp.json). Campos selecionados dos retornos oficiais.
- [Diárias por mês da portaria](diarias-mensais.csv), [por beneficiário](diarias-beneficiarios-2026.csv) e [por destino](diarias-destinos-2026.csv). Os meses sem registros não foram preenchidos com zero. Na agregação nominal e por destino, removeram-se acentos e diferenças de maiúsculas. Variações de sobrenome, pontuação e outras grafias permanecem separadas.
- [Sete registros para conferência individual](verificacoes-diarias-2026.csv). O teste cronológico usa as datas que constam na exportação e não presume a data efetiva do deslocamento.
- [Exportação original de diárias](../dados/diarias-exportacao.csv) e [exportação de contratos](../dados/contratos-exportacao.csv). Datas de referência são as das portarias. A moeda foi lida considerando as últimas duas casas como centavos.
