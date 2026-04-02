# Otimização Multiobjetivo Supervisionada via Estimativa

Este repositório contém o material técnico desenvolvido para o estudo e análise do artigo científico **"Supervised Multi-objective Optimization Algorithm Using Estimation"**, publicado no 2022 IEEE Congress on Evolutionary Computation (CEC).

O objetivo deste trabalho é explorar algoritmos que utilizam soluções não-dominadas conhecidas (dados supervisionados) para mapear a fronteira de Pareto de forma eficiente em problemas de alto custo computacional.

## 👥 Equipe
* **Davi de França**
* **Edmilson Filho**
* **Flavio da Silva**
* **Luiz Fernando**
* **Rafael Alves**
* **Rodrigo Herminio**

## 📂 Estrutura do Repositório

O repositório está organizado da seguinte forma:

* **`Sintese_Tecnica.pdf`**: Documento detalhado com a síntese dos conceitos, metodologia (RBNN, Espaço de Objetivos vs. Variáveis) e análise dos resultados experimentais.
* **`Pareto_Optimization.pdf`**: Material visual utilizado para a exposição técnica do algoritmo.
* **`Contraexemplo/`**: Pasta dedicada à demonstração de limitações do método, como o fenómeno de *ill-scaledness*.
* **`USO_DE_IA.md`**: Relatório de transparência sobre a utilização de ferramentas de Inteligência Artificial no suporte à compreensão e estruturação dos materiais.

## 🎯 Abordagem Técnica
O trabalho foca-se nos seguintes pontos:
1.  **Metodologia de Superfície de Resposta:** Uso de Redes Neurais de Base Radial (RBNN) para estimar o conjunto de Pareto.
2.  **Eficiência em Dados Escassos:** Como obter aproximações de qualidade com apenas 10 soluções iniciais e 150 avaliações de função.
3.  **Análise de Desempenho:** Avaliação baseada nas suítes de teste standard DTLZ e WFG.

*Este repositório foi criado para fins estritamente académicos no âmbito da disciplina Métodos Númericos, do curso de Ciência da Computação da Universidade Católica de Pernambuco (UNICAP)*
