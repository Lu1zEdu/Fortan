# Projetos em Fortran

Este repositório contém uma coleção de projetos desenvolvidos em Fortran, abordando uma variedade de tópicos e problemas de programação. Abaixo está uma descrição geral dos projetos, suas funcionalidades, e como executar o código.

## Requisitos

Para executar os projetos, você precisará de:

- Um compilador Fortran (exemplo: GFortran)
- Um ambiente de desenvolvimento para compilar e executar os programas

## Como compilar e executar

Para compilar e executar qualquer projeto:

1. Navegue até o diretório do projeto desejado.
2. Use o comando de compilação:
   ```bash
   gfortran -o nome_do_programa nome_do_programa.f95
   ```
3. Execute o programa compilado:
   ```bash
   ./nome_do_programa
   ```

## Projetos

### 1. Jogo da Forca

- **Descrição**: Este projeto implementa o clássico jogo da forca em Fortran. O programa seleciona aleatoriamente uma palavra de uma lista e o jogador tenta adivinhar a palavra antes de completar 6 erros. O boneco vai sendo desenhado progressivamente a cada erro.
- **Funcionalidades**:
  - Seleção aleatória de palavras
  - Verificação de letras corretas
  - Desenho do boneco a cada erro
- **Como rodar**:
  ```bash
  gfortran -o forca forca.f95
  ./forca
  ```

### 2. Calculadora de Matrizes

- **Descrição**: Este projeto implementa uma calculadora de matrizes que realiza operações como soma, subtração e multiplicação de matrizes. O usuário pode inserir as dimensões das matrizes e os valores dos elementos, e o programa calculará o resultado.
- **Funcionalidades**:
  - Operações de soma, subtração e multiplicação de matrizes
  - Manipulação de matrizes com diferentes dimensões
- **Como rodar**:
  ```bash
  gfortran -o calculadora_matriz calculadora_matriz.f95
  ./calculadora_matriz
  ```

### 3. Simulação de Sistemas Físicos

- **Descrição**: Este projeto simula sistemas físicos simples, como o movimento de um corpo em queda livre ou o movimento de um pêndulo. O usuário pode definir as condições iniciais e o programa calculará o movimento ao longo do tempo.
- **Funcionalidades**:
  - Simulação de movimento em tempo discreto
  - Entrada de condições iniciais pelo usuário
  - Exibição gráfica dos resultados (se aplicável)
- **Como rodar**:
  ```bash
  gfortran -o simulacao_fisica simulacao_fisica.f95
  ./simulacao_fisica
  ```

### 4. Análise Estatística de Dados

- **Descrição**: Um projeto focado em realizar análises estatísticas de conjuntos de dados fornecidos pelo usuário. O programa calcula estatísticas como média, mediana, desvio padrão, variância, etc.
- **Funcionalidades**:
  - Entrada de dados pelo usuário
  - Cálculo de métricas estatísticas básicas
  - Suporte a grandes conjuntos de dados
- **Como rodar**:
  ```bash
  gfortran -o analise_estatistica analise_estatistica.f95
  ./analise_estatistica
  ```

### 5. Processamento de Texto

- **Descrição**: Este projeto implementa um sistema de processamento de texto em Fortran. Ele permite ao usuário inserir, modificar e analisar textos. Funcionalidades incluem contagem de palavras, busca de padrões, e substituição de palavras.
- **Funcionalidades**:
  - Manipulação e análise de texto
  - Contagem de palavras e caracteres
  - Busca e substituição de padrões
- **Como rodar**:
  ```bash
  gfortran -o processamento_texto

  processamento_texto.f95
  ./processamento_texto
  ```

## Estrutura do Repositório

- Cada projeto está em seu próprio diretório com os arquivos `.f95` correspondentes.
- O nome de cada diretório corresponde ao projeto (exemplo: `forca`, `calculadora_matriz`, etc.).

## Contribuições

Contribuições são bem-vindas! Se você encontrar algum problema ou quiser adicionar novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.

