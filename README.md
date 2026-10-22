# Desafio 01 - Tratamento de Dados

## Análise de Produtividade em Telecomunicações

Projeto da trilha de **Ciência de Dados** desenvolvido no **Google Sheets**, com uma base de dados fictícia de atividades operacionais em telecomunicações. O objetivo foi transformar registros desorganizados em informações úteis para o acompanhamento de prazos e a tomada de decisões.

### Acesse a planilha

**[Abrir a planilha no Google Sheets](https://docs.google.com/spreadsheets/d/1ECCxDMsZihKRYddHsuhye09U7OYbclpXpMEs40logkc/edit?usp=sharing)**

A planilha contém três abas:
- **BASE CRUA:** registros originais para comparação;
- **DADOS TRATADOS:** padronização, validações e identificação de atrasos;
- **DASHBOARD:** indicadores, comparações e gráficos.

> **Observação:** o acesso para qualquer pessoa com o link deve estar configurado como **Leitor** no Google Sheets. O link, sozinho, não garante essa permissão.

## Problema e público-alvo

Supervisores e coordenadores de operações precisam identificar atividades atrasadas, comparar o cumprimento de prazos entre equipes e acompanhar a qualidade dos registros. A base fictícia simula esse cenário, sem expor informações empresariais.

## Tratamento realizado

- Padronização de datas, equipes, tipos de serviço e status;
- Remoção de uma linha duplicada e de linhas totalmente vazias;
- Avaliação de campos ausentes, sem inventar valores numéricos;
- Estruturação da tabela com filtros, menus suspensos e formatação condicional;
- Criação de colunas auxiliares de qualidade dos dados e situação do prazo.

## Ferramentas e funções

**Google Sheets:** `SE`, `OU`, `CONT.SE`, `CONT.SES`, `CONT.VALORES`, `SOMA` e `SEERRO`, além de filtros, validação de dados, formatação condicional e gráficos.

## Principais resultados

| Indicador | Resultado |
|---|---:|
| Atividades registradas após o tratamento | 40 |
| Atividades concluídas | 34 |
| Atividades pendentes | 6 |
| Concluídas com prazo avaliável | 33 |
| Atividades atrasadas | 16 |
| Atividades concluídas no prazo | 17 |
| Taxa de cumprimento do prazo | 51,52% |
| Taxa de atraso da Equipe Norte | 76,92% |
| Taxa de atraso em Manutenção | 60,00% |

A taxa de cumprimento do prazo foi calculada como **17 / (17 + 16)**, excluindo atividades abertas e uma atividade concluída sem tempo suficiente para avaliação.

## Conclusões

A Equipe Norte apresentou a maior taxa de atraso entre as equipes identificadas; Manutenção apresentou a maior taxa entre os tipos de serviço. Esses resultados indicam pontos de investigação, **não comprovam as causas dos atrasos**. Também se evidenciou a importância de registros completos e categorias padronizadas para produzir indicadores confiáveis.

## Apresentação

A versão final do trabalho, em PDF (até 5 slides), deve ficar na pasta [`apresentacao/`](apresentacao/). 

## Autoria

Ana Patrícia Braga Garros · 2026

**Nota:** dados fictícios, utilizados exclusivamente para fins educacionais.
