# 🏗️ OCR em Medição e Orçamento de Obras

Este projeto apresenta uma aplicação desktop inovadora desenvolvida para otimizar os processos de medição e orçamento na construção civil, focando em pequenas empresas e profissionais autônomos. A solução utiliza a tecnologia **OCR (Reconhecimento Óptico de Caracteres)** para automatizar a extração de dados de medições manuscritas.

## 🎯 O Problema
Estudos de campo realizados em empresas do setor revelaram que a medição de obras ainda é feita predominantemente de forma manual (cadernos e calculadoras). Isso gera:
* Processos demorados e propensos a erros humanos.
* Dificuldade na integração entre a medição de campo e o orçamento final.
* Baixa produtividade na gestão de dados.

## ✨ A Solução
A aplicação centraliza todo o fluxo de trabalho em um único sistema desktop, oferecendo:
1.  **Modo Manual:** Inserção tradicional de dados de medição.
2.  **Modo Semiautomático (OCR):** O usuário faz o upload de fotos de anotações manuscritas. O sistema utiliza a biblioteca **Tesseract OCR** para converter a imagem em texto e regras lógicas para separar serviços e medidas automaticamente.
3.  **Integração com SINAPI:** Base de dados voltada para a tabela nacional de custos da construção civil.

---

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** C++ (Orientação a Objetos)
* **Framework UI:** Qt Creator
* **Processamento de Imagem:** Tesseract OCR e Leptonica
* **Banco de Dados:** MySQL
* **Modelagem:** MySQL Workbench
* **Versionamento:** GIT

---

## 📊 Engenharia de Software
O desenvolvimento seguiu rigorosos padrões para garantir a confiabilidade do software:

* **Modelagem UML:** Diagramas de Classe, Casos de Uso e Entidade-Relacionamento (DER).
* **Plano de Testes:** Validações de persistência de dados, testes de integração do OCR e regras de negócio (como validação de CPF/CNPJ e segurança de senhas).
* **Metodologia Ágil:** Gestão de tarefas via Kanban.

## 🚀 Func
