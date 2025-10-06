#  calculadora-cesar

<div align="center">
  <p><strong>Curso:</strong> Engenharia de Controle e Automação</p>
  <p><strong>Disciplina:</strong> Sistemas Computacionais I</p>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/status-concluído-green" alt="Status do Projeto: Concluído">
  <img src="https://img.shields.io/badge/linguagem-Assembly-blue" alt="Linguagem: Assembly">
</div>

---

## 📖 Descrição do Projeto

Este projeto apresenta a implementação de uma calculadora funcional para o **Computador Hipotético CESAR**. O repositório inclui o código-fonte em Assembly, desenvolvido para ser montado e executado no ambiente de simulação, e um relatório avaliativo detalhando o processo de desenvolvimento e os resultados alcançados.

A calculadora é capaz de realizar as quatro operações aritméticas básicas (soma, subtração, multiplicação e divisão) e processar números de múltiplos dígitos, superando as limitações básicas da arquitetura.

## 🎯 Objetivo e Desafios Técnicos

O principal objetivo deste projeto foi aplicar e aprofundar os conhecimentos de programação em baixo nível adquiridos na matéria de Sistemas Computacionais I.

A sua execução envolveu a superação de desafios importantes, como:

* **Manipulação de Entrada/Saída:** Converter caracteres ASCII recebidos do teclado em seus valores numéricos correspondentes para cálculo.
* **Algoritmos Aritméticos:** Criar algoritmos para multiplicação e divisão utilizando apenas somas e subtrações sucessivas, contornando a ausência de instruções nativas para essas operações na arquitetura CESAR.
* **Modularização:** Estruturar o software de forma modular, com o uso de sub-rotinas para organizar o código e facilitar a reutilização.
* **Conversão de Base:** Implementar uma função para converter o resultado final (em formato binário/numérico) de volta para uma representação decimal em ASCII, permitindo que seja exibido corretamente no visor do simulador.

## 🛠️ Ferramentas e Tecnologias Utilizadas

* **Linguagem:** Assembly para o Computador CESAR
* **Simulador:** Daedalus (para montar o código-fonte `.asm` em `.mem`)
* **Simulador:** CESAR (para executar o arquivo `.mem`)
* **Bibliotecas:** BibCesar (para rotinas de I/O)

## ⚙️ Como Executar

Para executar este projeto, é necessário ter os simuladores Daedalus e CESAR.

1.  **Montagem:** Utilize o simulador **Daedalus** para montar o arquivo de código-fonte (`.asm`). Isso irá gerar um arquivo de memória (`.mem`) que pode ser carregado pelo CESAR.
2.  **Execução:** Abra o simulador **CESAR**.
3.  **Carregar Memória:** Carregue o arquivo `.mem` gerado no passo anterior.
4.  **Rodar:** Inicie a execução do programa no simulador. A calculadora estará pronta para receber entradas pelo teclado virtual.

## 👥 Integrantes

* Davi Aguirre
* Gustavo Rolisola
* João Peres
