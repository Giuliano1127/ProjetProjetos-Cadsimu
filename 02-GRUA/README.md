# 🏗️ GRUA DE CARGA E DESCARGA (PROJETO DE AUTOMAÇÃO)

## 📌 Visão Geral

Projeto acadêmico com foco na modelagem e simulação do controle de uma Grua de Carga e Descarga. O sistema realiza o movimento vertical (M1) e horizontal (M2) para completar os ciclos de transporte.

* [cite_start]**Tipo de Projeto:** Acadêmico[cite: 3].
* [cite_start]**Modelagem Principal:** Rede de Petri (RP)[cite: 17].
* [cite_start]**Simulação/Desenvolvimento:** CadSimu [cite: 35] [cite_start](Linguagem Ladder [cite: 36]).

## 🎯 Objetivo

[cite_start]Modelar um sistema de controle de movimentação para a grua, realizando o trajeto completo de ida (Ciclo 1) e volta (Ciclo 2)[cite: 3, 7, 8].

## ⚙️ Componentes Chave

[cite_start]O controle dos movimentos é baseado no acionamento de dois motores e seis Fim de Curso (FC)[cite: 4]:

* [cite_start]**M1:** Movimentos na **Vertical** (Sobe/Desce)[cite: 4].
* [cite_start]**M2:** Movimentos na **Horizontal** (Direita/Esquerda)[cite: 4].
* [cite_start]**Fins de Curso (FC1 - FC6):** Posicionam e orientam os motores[cite: 4].
* [cite_start]**Temporizador (T1):** Utilizado para temporizar o tempo de espera na posição de descarga[cite: 34].

## 📝 Lógica Sequencial

[cite_start]A lógica sequencial foi validada usando a Rede de Petri [cite: 17] [cite_start]e implementada no circuito Ladder[cite: 35, 36]. [cite_start]O sistema comuta entre a **Posição de Repouso (1)** e a **Posição de Carga/Descarga (2)**[cite: 11, 15].

## 📂 Arquivos do Projeto

Todos os arquivos de modelagem e simulação estão contidos no repositório.

* [cite_start]`GRUA VIA PR (1).pdf` (Diagramas esquemático, Rede de Petri e Circuito Ladder [cite: 1, 35]).
* *Arquivos de Simulação CadSimu/PCSIMU (Não inclusos neste README, mas presume-se a existência).*

## 💡 Aprendizado

* [cite_start]Modelagem de sistemas de automação via Rede de Petri[cite: 17].
* [cite_start]Desenvolvimento de lógica sequencial em Linguagem Ladder[cite: 36].
* Integração e acionamento de múltiplos atuadores (motores) coordenados por sensores de Fim de Curso.

## ✒️ Autor

* [cite_start]**Autor:** Giuliano Barone [cite: 1]
* [cite_start]**Data:** 10/2025 [cite: 2]
