# Otimização Multiobjetivo Supervisionada via Estimativa

Este repositório contém o material técnico desenvolvido para o estudo e análise do artigo científico **"Supervised Multi-objective Optimization Algorithm Using Estimation"**, publicado no *2022 IEEE Congress on Evolutionary Computation (CEC)*.

O trabalho responde à questão fundamental da disciplina: **quando métodos numéricos clássicos (como Newton-Raphson ou Busca Exaustiva) tornam-se inadequados devido ao custo computacional proibitivo?** O algoritmo de Takagi propõe contornar essa limitação utilizando soluções conhecidas como "atalhos" para mapear a fronteira de Pareto.

## 👥 Equipe
* Davi de França
* Edmilson Filho
* Flavio da Silva
* Luiz Fernando
* Rafael Alves
* Rodrigo Herminio

## 📂 Estrutura do Repositório
* **Sintese_Tecnica.pdf**: Documento com a síntese dos conceitos, metodologia e análise dos resultados.
* **Pareto_Optimization.pdf**: Slides utilizados na apresentação oral.
* **Contraexemplo/**: Pasta com o arquivo `Pareto.ipynb`, demonstrando por que a interpolação linear simples falha em capturar a curvatura da fronteira (justificando o uso de RBNN).
* **USO_DE_IA.md**: Relatório de transparência sobre o uso de ferramentas de IA no suporte à estruturação do material.

## 📄 Artigo Base
Toda a pesquisa foi desenvolvida com base no estudo:

* **Título:** Supervised Multi-objective Optimization Algorithm Using Estimation
* **Autores:** Tomoaki Takagi, Keiki Takamada, Hiroyuki Sato
* **Evento:** 2022 IEEE Congress on Evolutionary Computation (CEC)
* **DOI:** 10.1109/CEC55065.2022.9870375

## 🎯 Abordagem Técnica e Crítica
O foco do trabalho está na transição do cálculo numérico tradicional para modelos de estimativa:
* **Metodologia de Superfície de Resposta (RSM):** Uso de Redes Neurais de Base Radial (RBNN) para estimar a fronteira.
* **Eficiência em Dados Escassos:** Obtenção de resultados com apenas 10 soluções iniciais e 150 avaliações de função.
* **Análise Crítica:** O grupo identificou que a principal limitação do método reside no fenômeno de *ill-scaledness*. Discutimos como a sensibilidade numérica do modelo exige uma curadoria rigorosa dos dados supervisionados iniciais, pois o "atalho" neural é tão bom quanto as referências que recebe.

---
*Este repositório foi criado para fins acadêmicos no âmbito da disciplina **Métodos Numéricos**, do curso de Ciência da Computação da **Universidade Católica de Pernambuco (UNICAP)**.*
