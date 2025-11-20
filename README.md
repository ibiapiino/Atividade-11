# RAG-LLM
# Atividade 11 RAG: Assistente de Compliance com IA da empresa fictícia Avengers

Este projeto apresenta uma solução de **RAG (Retrieval-Augmented Generation)** desenvolvida para a disciplina de Inteligência Artificial. O objetivo é demonstrar como LLMs podem ser utilizados para responder perguntas sobre documentos corporativos internos.

## O Problema
Dúvidas frequentes de funcionários que demandam tempo do time responsável e que o ideal neste cenário para poupar desgaste dos colaboradores do time com dúvidas sobre o código de ética.

## A Solução
Fiz um sistema RAG utilizando a biblioteca **Hugging Face** e o modelo **TinyLlama-1.1B**. O sistema:
1. Lê um Código de Ética (PDF).
2. Realiza a busca semântica pelo trecho mais relevante.
3. Instrui a IA a responder apenas com base naquele contexto, em português.

## Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** `transformers`, `sentence-transformers`, `pypdf`, `torch`
* **Modelo LLM:** `TinyLlama/TinyLlama-1.1B-Chat-v1.0`
* **Ambiente:** Google Colab

## Como Executar
1. Abra o arquivo `.ipynb` deste repositório no Google Colab.
2. Faça o upload do arquivo `baseConhecimentoAtividade11.pdf`.
3. Execute as células para instalar as dependências e rodar o assistente.

## Exemplos de Uso
**Pergunta:** "Posso aceitar presentes de fornecedores?"
**Resposta aproximada da IA:** "É proibido aceitar presentes, benefício de parceiros/fornecedores..."

---
*Desenvolvido por Larissa Ibiapino*
