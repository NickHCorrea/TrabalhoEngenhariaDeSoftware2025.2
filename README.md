Repositório do grupo B para a disciplina de Engenharia de Software na UFRJ no período de 2025.2

A planilha Eng.Soft contém os 5 trabalhos pedidos, cada um em uma aba da planilha. 

Temos também a modelagem de dois processos da Livraria Resolve em BPMN.

# 📚 Sistema da Livraria Resolve — Documentação Teórica do Projeto

Este repositório registra o desenvolvimento acadêmico de um sistema para a **Livraria Resolve**, uma livraria especializada em livros raros e de arte que busca modernizar seus processos de vendas e atendimento ao cliente.  
Cada fase do projeto foi conduzida com base em técnicas e modelos da Engenharia de Software, aplicados conforme cronograma da disciplina.

---

## 🏛️ Cenário do Projeto

A Livraria Resolve atua com obras difíceis de encontrar, atendendo clientes do Brasil e do exterior.  
O objetivo do sistema é digitalizar as seguintes operações essenciais:

- Cadastro e manutenção de clientes
- Registros e requisições de livros a fornecedores
- Controle de pedidos e prazos
- Emissão de documentos e comunicação com clientes
- Integração com sistema financeiro e contador

Os problemas identificados no modelo atual sustentaram o estudo e aplicação das técnicas teóricas listadas a seguir.

---

## 📌 Etapas e Teorias Utilizadas

A documentação do projeto foi organizada em cinco entregas. Cada uma explorou um conceito teórico fundamental da Engenharia de Software.

---

### 📍 1️⃣ Partes Interessadas (Stakeholders)

**Conceito**:  
Stakeholders são indivíduos, grupos ou entidades que influenciam ou são impactados pelo sistema.  
Suas necessidades devem ser reconhecidas no desenvolvimento para garantir valor e aceitação do software.

**Teoria aplicada**:
- Identificação do interesse e papel de cada participante
- Impacto direto ou indireto nos requisitos

> Base: Engenharia de Requisitos — gerenciamento de stakeholders

---

### 📍 2️⃣ Classificação PLU (Poder, Legitimidade e Urgência)

**Conceito**:  
O Modelo de Saliência classifica stakeholders de acordo com:

| Atributo | Significado |
|---|---|
| **Poder** | Capacidade de influenciar decisões |
| **Legitimidade** | Relacionamento válido com o sistema |
| **Urgência** | Necessidade de resposta imediata |

A partir dessa análise, os stakeholders são categorizados em tipos como Dominante, Exigente, Definitivo etc.

> Base: Teoria de Mitchell, Agle e Wood (1997)

---

### 📍 3️⃣ Casos de Uso (Use Cases)

**Conceito**:  
Modelo que descreve **interações entre atores e o sistema**, representando comportamentos funcionais esperados.

**Elementos fundamentais**:
- Atores
- Objetivos do ator
- Fluxos principais e alternativos
- Pré e pós-condições


> Finalidade: levantar e validar requisitos funcionais 

---

### 📍 4️⃣ Histórias de Usuário (User Stories)

**Conceito**:  
Representam funcionalidades sob a perspectiva do usuário, com foco em valor de negócio.

**Modelo padrão (INVEST)**:

> Como `<ator>`,
> desejo `<funcionalidade>`,
> para `<benefício/valor>`.

**Características desejáveis**:  
Independentes, negociáveis, valiosas, estimáveis, pequenas e testáveis.

> Base: Métodos Ágeis — principalmente Scrum e XP

---

### 📍 5️⃣ Análise de Pontos de Função (APF) + BPMN

#### 🔹 Pontos de Função

**Conceito**:  
Método para **medir o tamanho funcional** do software de acordo com o que ele **entrega ao usuário**, independente da tecnologia adotada.

Classificação de funções:
- **ALI**: Arquivos Lógicos Internos
- **AIE**: Arquivos de Interface Externos
- **EE**: Entradas Externas
- **CE**: Consultas Externas
- **SE**: Saídas Externas

> Base: IFPUG — medição funcional padronizada

---

#### 🔹 BPMN – Business Process Model and Notation

**Conceito**:  
Notação gráfica para modelagem de processos de negócio,  
representando:

- Fluxo de atividades
- Participantes (pools/lanes)
- Gateways de decisão
- Eventos e interações externas

> Objetivo: compreender processos atuais e propor melhorias

---

## 🧩 Organização do Repositório
