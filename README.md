# Júpiter Agente: Especialista de Soluções NEOOH 🚀

Este projeto é um **Agente de Inteligência Artificial Conversacional** desenvolvido como Trabalho de Conclusão de Curso (TCC) da especialização em **LLMs e AI Agents**, realizada pela **SoulCode Academy** e **Martech Academy** em parceria com a **NEOOH**.

O **Júpiter Agente** atua como um consultor híbrido, operando na intersecção estratégica entre a tecnologia de mídia digital e o mercado financeiro.

---

## 🎯 O Problema
Projetos de mídia **Phygital** e **Ofertas Públicas** de investimento possuem alta complexidade técnica e regulatória. A fragmentação de dados em MediaKits e Editais extensos gera:
* **Fricção Comercial:** Lentidão no suporte a dúvidas técnicas.
* **Riscos de Compliance:** Erros em durações de vídeo ou perfis de investidor.
* **Assimetria de Informação:** Dificuldade de extração de dados críticos de documentos densos.

## ✨ A Solução
O agente utiliza arquitetura **RAG (Retrieval-Augmented Generation)** para fornecer respostas instantâneas e precisas baseadas em fontes oficiais da NEOOH, unificando dois pilares estratégicos:

### 1. Consultoria Phygital & Pré-Venda
* **Orientação Técnica:** Validação de resoluções, formatos e durações de vídeo para redes (Aeroportos, Terminais e WeWork).
* **Insights Criativos:** Sugestão de interatividade (QR Codes, Sensores) baseada em cases reais de campanhas anteriores.
* **Rigor Operacional:** Aplicação de diretrizes de logística (prazo de 48h) e correção de erros críticos de veiculação.

### 2. Mercado de Capitais (Ofertas Públicas)
* **Suporte Especializado:** Pré-venda da 1ª Emissão de Notas Comerciais da LRC 247 Participações.
* **Conformidade CVM:** Explicação do Rito CVM 160 e filtragem de público-alvo para Investidores Profissionais (Resolução CVM 30).
* **Transparência Financeira:** Detalhamento de garantias firmes e identificação de avalistas da operação.

---

## 🛠️ Tecnologias Utilizadas
* **Google Dialogflow CX:** Orquestração de fluxos, páginas e Playbooks.
* **Vertex AI Search (RAG):** Indexação de MediaKits (PDF) e base de conhecimento técnica.
* **Few-Shot Learning:** Treinamento especializado via exemplos para eliminar alucinações.
* **Tool Orchestration:** Integração entre DataStores e fontes externas (Site oficial).

---

## 📂 Estrutura do Repositório
* `/agent-export`: Arquivo compactado para importação no Dialogflow CX.
* `/docs`: Exemplos de MediaKits e documentos públicos (LRC 247) utilizados no RAG.
* `/tests`: Documentação dos **Test Cases** que validam a eficácia do agente.

---

## 👀 Demonstração em Vídeo
![Demonstração do Júpiter Agente](./assets/demonstracao-jupiter.gif)


> **Nota Técnica:** Este agente foi configurado para priorizar a veracidade dos dados (Anti-Hallucination), admitindo a necessidade de validação humana caso a informação não conste nas bases oficiais indexadas.
