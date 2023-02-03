# Métricas

## Propriedades desejáveis

- Facilmente calculada e entendida
- Deve possuir uma unidade associada
- Obtida cedo no processo de desenvolvimento
- Automatizável
- Repetível e imparcial (em relação ao observador)

## Uma métrica deve ser

- **Válida:** Capaz de quantificar o que precisamos medir
- **Confiável:** Capaz de produzir os mesmos resultados, dadas certas condições
- **Prática:** Capaz de ser facilmente computada e interpretada

## Categorias de métricas

### Diretas (fundamentais ou básicas)

Medida em termos de atributos observados
	- E.g. Custo, esforço, linhas de código, capacidade de memória, número de diagramas

### Indiretas (derivadas)

Medidas obtidas a partir de outras métricas
	- E.g. Complexidade, eficiência, confiabilidade, facilidade de manutenção

### Orientadas a tamanho

Medidas diretas dos artefatos associados ao processo de desenvolvimento
	- E.g. Esforço, custo, KLOC, tamanho de documentação, número de erros

### Orientadas por função

Medida feita sob ponto de vista do usuário. Verifica quantidade de funcionalidades e complexidade do software

### De produtividade

Foco na saída do processo
	- E.g. Casos de uso por iteração

### De qualidade

Indicação de adequação do software à exigências implícitas e explícitas do cliente
	- E.g. Erros por fase

### Técnicas 

Foco nas características do SW e não no processo
	- E.g. Complexidade lógica e grau de manutenibilidade
- Utilização em casos rigorosos. É uma métrica poderosa, mas custosa se não houver forma de automatizá-la

## Problemas na utilização de métricas

A comparação direta de produtividade de desenvolvedores pode ser problemática. Por exemplo, a utilização de métricas de linhas de código para essa comparação não trará conclusões úteis e pode ser injusta.

- O que é uma linha de código válida?
	- Espaços, estilos de código, etc
- Qual é o contexto da medição?
	- Familiariazação com linguagem, framework, tecnologias
- Difícil capturar a qualidade de código (quantidade != qualidade)
	- Um código maior e mais descritivo será melhor que um código pequeno e de difícil leitura/manutenibilidade
- Como o resultado será interpretado?

## Papéis da medição

- Entender
	- Comportamento de processos, produtos e serviços
- Avaliar
	- Tomada de decisões, estabelecimento de padrões, metas, critérios de aceitação
- Controlar
	- Modificar e controlar processos, produtos e serviços
- Prever
	- Prazos, atributos, custo
