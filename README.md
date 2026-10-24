# Análise de Vendas e Resultados por Loja — Senac

Terceiro exercício prático desenvolvido no curso de Power BI do **Senac**, como atividade em sala de aula.

O relatório reúne seis páginas com indicadores comerciais e resultados por loja e categoria, para o período indicado de **2025 a 2026**.

## Objetivo

Praticar a construção de um relatório com diferentes páginas e indicadores de faturamento, lucro, margem, comissões e metas, permitindo comparar lojas e categorias de produtos.

## Contexto e fonte dos dados

Projeto educacional realizado no curso do Senac. A origem detalhada e a natureza da base não estão documentadas neste repositório.

## Perguntas exploradas

- Qual é o faturamento total no recorte apresentado?
- Como o faturamento se distribui entre lojas e categorias?
- Quais valores de lucro, margem e comissão são apresentados?
- Como comparar resultados por loja e período?
- Como acompanhar o resultado em relação às metas?

## Estrutura do relatório

| Página | Conteúdo apresentado |
| --- | --- |
| 1 | Visão de vendas, faturamento, comissões e gráficos por categoria |
| 2 | Resumo de faturamento, lucro e margem, com matriz por loja e categoria |
| 3 | Comissões por loja e categoria |
| 4 | Matriz intitulada “ICM por loja” |
| 5 | Matriz com total coincidente com o lucro do resumo; título a revisar |
| 6 | Acompanhamento de meta de lucro por loja |

O relatório inclui filtros de loja, ano e mês, conforme a página. As categorias apresentadas são Câmera, Celular, Notebook, Smart Watch e Tablet.

## Indicadores exibidos

| Indicador | Valor no resumo exportado |
| --- | ---: |
| Faturamento total | 139.146.860,10 |
| Lucro | 112.622.840,13 |
| Margem de lucro | 80,94% |
| Total de comissões na matriz | 5.852.458,92 |

Os valores são os exibidos no exercício. O PDF não permite validar as fórmulas ou a composição dos indicadores; o valor denominado lucro não deve ser interpretado como lucro líquido contábil sem conhecer sua definição.

## Principais observações

- **Notebook** apresenta o maior faturamento por categoria na matriz: **47.122.952,80**.
- **Smart Watch** apresenta o menor faturamento por categoria: **8.764.126,10**.
- Entre as 20 lojas da matriz, **Loja Sul 1** apresenta o maior faturamento: **7.677.517,20**.

Essas observações se referem ao recorte exportado e aos dados do exercício.

## Ferramenta e práticas

**Power BI**, com prática de:

- Organização de um relatório em múltiplas páginas.
- Apresentação de indicadores em cartões.
- Construção de tabelas e matrizes por loja e categoria.
- Comparação de resultados comerciais.
- Uso de segmentações de dados e visual de acompanhamento de metas.

## Visualização e interatividade

**[Visualizar o dashboard em PDF](./Exerc%C3%ADcio%20Pr%C3%A1tico%203.pdf)**

O PDF contém as seis páginas do relatório, com os indicadores, matrizes e acompanhamento de metas do exercício.

A exportação é estática. Os filtros dependem do relatório original; o arquivo `.pbix` e o link interativo ainda não estão disponíveis.

## Pontos para revisão no relatório original

- Conferir o título da página 5: ele repete “ICM por loja”, embora o total coincida com o lucro do resumo.
- Conferir o valor exato da meta, a direção do indicador e o contexto de cálculo do KPI da página 6 antes de interpretar seu desvio.
- Confirmar se o gráfico “Contagem de Quantidade por Categoria” deve contar registros ou somar unidades.
- Documentar a definição dos indicadores de lucro e ICM.

Esses pontos foram identificados na leitura do PDF e ainda não foram ajustados no relatório original.

## Créditos

- **Contexto:** exercício prático em sala de aula no Senac.
- **Desenvolvido por:** Kelvin Magno, como aluno do curso.

## Autor

[Kelvin Magno](https://github.com/kelvinmagno) — Analista de Prevenção à Fraude, desenvolvendo habilidades em Power BI, Excel e SQL.
