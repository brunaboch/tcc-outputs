# Outputs Completos – TextualDB

## 🧩 Descrição Geral

Este repositório contém os **outputs completos dos LLM)** avaliados no Trabalho de Conclusão de Curso intitulado:

> **TextualDB: uso de inteligência artificial aplicada na tradução automatizada de diagramas de banco de dados conceituais em texto acessível para pessoas com deficiência visual**  
> *Instituto Federal Sul-rio-grandense (IFSul) – Campus Sapucaia do Sul*  
> *Autora: Bruna Rafaela Boch*  
> *Orientador: Prof. Dr. Alex Mulattieri Suarez Orozco*  
> *Ano: 2025*

---

## 🎯 Objetivo

Este repositório apresenta as **respostas completas geradas por cinco LLMs** aplicados na tarefa de converter **diagramas conceituais de banco de dados** em **descrições textuais acessíveis**.

O propósito é **tornar transparente e reprodutível** o processo experimental conduzido no TCC, permitindo que outros pesquisadores, docentes e estudantes:

- Analizem a **qualidade e coerência semântica** dos textos gerados;
- Compare o **desempenho entre diferentes LLMs**;
- Consultem os **outputs originais** utilizados nas análises qualitativas apresentadas no trabalho.

---

## 🧠 Modelos de Linguagem avaliados

| Modelo | Desenvolvedora |
|--------|----------------|
| **Grok** | xAI |
| **Gemini** |  Google DeepMind |
| **GPT** | OpenAI |
| **DeepSeek** | DeepSeek AI |
| **Claude** | Anthropic |

Cada modelo recebeu as mesmas instruções e imagens, a fim de garantir **condições experimentais equivalentes**.

---

## 🖼️ Tipos de diagramas utilizados

Foram utilizados três tipos de representações visuais dos mesmos diagramas conceituais de banco de dados:

1. **Livro digital** — diagrama vetorial, extraído diretamente de material didático.  
2. **Escaneado** — imagem obtida a partir de um material impresso digitalizado.  
3. **Fotografia** — foto de um diagrama em papel, com variações de luz e perspectiva.

Esses três formatos foram escolhidos para **simular diferentes condições de acessibilidade e qualidade de imagem**.

---

## 💬 Tipos de prompts aplicados

Cada modelo recebeu dois tipos de prompts distintos:

- 🧠 **Prompt técnico** – voltado a especialistas em banco de dados, utilizando linguagem técnica e formal;  
- 💬 **Prompt acessível** – voltado a estudantes e pessoas com deficiência visual, com linguagem simples e foco descritivo.

Para cada combinação de modelo × formato de imagem × tipo de prompt, foi gerado um **output textual independente**.

Total: **18 combinações**.

---

## 📂 Estrutura das pastas

A estrutura de diretórios do repositório segue o padrão abaixo:

/grok/  
grok\_digital\_prof.txt  
grok\_digital\_est.txt  
grok\_scan\_prof.txt  
grok\_scan\_est.txt  
grok\_photo\_prof.txt  
grok\_photo\_est.txt

/gemini/  
gemini\_digital\_prof.txt  
gemini\_digital\_est.txt  
...

/gpt/  
gpt\_digital\_prof.txt  
gpt\_digital\_est.txt  
...

/deepseek/  
deepseek\_digital\_prof.txt  
deepseek\_digital\_est.txt  
...

/claude/  
claude\_digital\_prof.txt  
claude\_digital\_est.txt  
...

/claude/
claude_digital_prof.txt
claude_digital_est.txt
...

### Convenção de nomes dos arquivos

**Exemplo:**
- `gpt_escaneado_prof.txt` → Output do modelo GPT com diagrama escaneado e prompt técnico.  
- `claude_foto_est.txt` → Output do modelo Claude com diagrama em fotografia e prompt acessível.

---

## 📘 Formato dos arquivos

- Todos os arquivos estão em **texto simples (.txt)**, codificação **UTF-8**.  
- Acentos e caracteres especiais do português foram preservados.  
- O conteúdo foi mantido **sem qualquer modificação**, refletindo exatamente as respostas originais dos modelos.

---

## 📊 Organização experimental

Cada arquivo representa uma resposta textual gerada automaticamente por um LLM em um contexto experimental definido por:

| Fator | Valores possíveis |
|-------|-------------------|
| Modelo | Grok, Gemini, GPT, DeepSeek, Claude |
| Formato do diagrama | Livro digital, Escaneado, Fotografia |
| Tipo de prompt | Técnico, Acessível |

As análises comparativas entre os outputs foram realizadas quanto a aspectos como:
- Clareza e completude da descrição textual;  
- Preservação das relações entre entidades;  
- Adequação da linguagem ao público-alvo (técnico ou acessível).

---

## 🧾 Licença de uso

Os conteúdos deste repositório são disponibilizados **exclusivamente para fins acadêmicos e de pesquisa**.  
Os direitos sobre os textos gerados pertencem às respectivas plataformas de IA utilizadas.

> **Uso autorizado apenas para consulta e fins não comerciais.**

---

## 🧑‍💻 Contato

**Autora:** Bruna Rafaela Boch  
**Instituição:** Instituto Federal Sul-rio-grandense (IFSul) — Campus Sapucaia do Sul  
**Curso:** Tecnologia em Análise e Desenvolvimento de Sistemas
**Ano:** 2025  
**Orientador:** Prof. Dr. Alex Mulattieri Suarez Orozco  
**E-mail:** brunarbochifsul@gmail.com

---

📘 *Este repositório faz parte do Trabalho de Conclusão de Curso apresentado ao Instituto Federal Sul-rio-grandense (IFSul), como requisito parcial para obtenção do título de Tecnóloga em Análise e Desenvolvimento de Sistemas.*
