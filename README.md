# 📚 Miniguia de Arquitetura de Software com IA

## 🎯 Contexto e Objetivos

Este projeto tem como objetivo explorar o uso de Inteligência Artificial como ferramenta de apoio ao aprendizado ativo no estudo de Arquitetura de Software.

A proposta consiste na criação de um caderno temático utilizando o NotebookLM, com base em fontes confiáveis, promovendo:
- Desenvolvimento do pensamento crítico;
- Organização estruturada do conhecimento;
- Prática de engenharia de prompts;
- Consolidação de conceitos essenciais de arquitetura.

### Objetivos de Estudo:
- Compreender os principais estilos arquiteturais;
- Entender conceitos como escalabilidade, acoplamento e coesão;
- Explorar padrões como Microservices e Clean Architecture;
- Criar um material reutilizável para revisões futuras.

## 📖 Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM:

1. "Clean Architecture" – Robert C. Martin:
   https://github.com/serodriguez68/clean-architecture?utm_source=chatgpt.com
2. Martin Fowler – Microservices:
   https://martinfowler.com/articles/microservices.html
3. Microsoft Docs – Arquitetura de Software:
   https://learn.microsoft.com/en-us/azure/architecture/
4. AWS – Well-Architected Framework:
   https://aws.amazon.com/architecture/well-architected/

## 🤖 Engenharia de Prompts e Aprendizados

### Prompt 1:
"Explique os principais estilos de arquitetura de software de forma simples"

🔎 Resultado:
A IA apresentou arquiteturas como monolítica, microsserviços, limpa, orientada a serviços e baseada em células.

⚠️ Problema:
Resposta muito superficial.

🔁 Ajuste:
"Explique os estilos de arquitetura (monolítica, microsserviços, limpa, orientada a serviços e baseada em células) com vantagens, desvantagens e exemplos reais"

✅ Melhoria:
Resposta mais completa e comparativa.

---

### Prompt 2:
"Qual a diferença entre acoplamento e coesão?"

🔎 Resultado:
Boa explicação, porém sem exemplos.

🔁 Ajuste:
"Inclua exemplos práticos no contexto de APIs"

✅ Melhoria:
Facilitou muito o entendimento.

---

### Prompt 3:
"Explique Clean Architecture"

⚠️ Problema:
Resposta confusa.

🔁 Ajuste:
"Explique Clean Architecture como se eu fosse um desenvolvedor iniciante e inclua analogias"

✅ Resultado:
Muito mais didático.

---

### Aprendizados:
- Prompts específicos geram respostas melhores;
- Pedir exemplos melhora a compreensão;
- Iterar é essencial para qualidade;

## 📘 Miniguia de Estudo – Arquitetura de Software

### 🧩 Estilos Arquiteturais

#### 🏢 Arquitetura Monolítica

A arquitetura monolítica consiste em uma única aplicação onde todos os componentes (interface, lógica de negócio e acesso a dados) estão integrados em um único código-base e são implantados juntos.

**Vantagens:**

* Simplicidade no desenvolvimento inicial;
* Fácil deploy;
* Menor complexidade operacional.

**Desvantagens:**

* Dificuldade de escalabilidade;
* Alto acoplamento entre módulos;
* Manutenção mais complexa com o crescimento do sistema.

---

#### 🔗 Arquitetura de Microsserviços

A arquitetura de microsserviços divide a aplicação em pequenos serviços independentes, cada um responsável por uma funcionalidade específica.

**Vantagens:**

* Escalabilidade independente;
* Deploy isolado por serviço;
* Flexibilidade tecnológica.

**Desvantagens:**

* Complexidade de comunicação (APIs, mensageria);
* Maior esforço de monitoramento;
* Gerenciamento distribuído mais difícil.

---

#### 🧼 Arquitetura Limpa (Clean Architecture)

A arquitetura limpa organiza o sistema em camadas bem definidas, com foco na separação de responsabilidades e independência de frameworks.

**Princípios principais:**

* Regras de negócio no centro da aplicação;
* Dependências sempre apontam para dentro;
* Independência de banco de dados e frameworks.

**Vantagens:**

* Código mais testável;
* Alta manutenibilidade;
* Baixo acoplamento.

**Desvantagens:**

* Curva de aprendizado;
* Pode ser mais verbosa inicialmente.

---

#### 🔄 Arquitetura Orientada a Serviços (SOA)

A SOA (Service-Oriented Architecture) organiza o sistema em serviços reutilizáveis que se comunicam por meio de protocolos padronizados.

**Características:**

* Serviços reutilizáveis;
* Integração entre sistemas diferentes;
* Uso comum em ambientes corporativos.

**Vantagens:**

* Reutilização de serviços;
* Integração facilitada;
* Padronização.

**Desvantagens:**

* Pode gerar dependência de um barramento (ESB);
* Complexidade de governança.

---

#### 🧱 Arquitetura Baseada em Células (Cell-Based Architecture)

A arquitetura baseada em células organiza o sistema em unidades independentes (células), onde cada célula contém todos os componentes necessários para funcionar de forma isolada.

**Características:**

* Cada célula é autossuficiente;
* Isolamento de falhas;
* Escalabilidade horizontal.

**Vantagens:**

* Alta resiliência;
* Redução do impacto de falhas;
* Escalabilidade eficiente.

**Desvantagens:**

* Complexidade de implementação;
* Maior consumo de recursos;
* Exige maturidade arquitetural.

---

### ⚙️ Conceitos Fundamentais

* **Acoplamento:** nível de dependência entre componentes;
* **Coesão:** grau de responsabilidade única de um módulo;
* **Escalabilidade:** capacidade do sistema crescer;
* **Resiliência:** capacidade de lidar com falhas;
* **Disponibilidade:** tempo que o sistema permanece operacional.

---

### 📖 Glossário

* **Monolito:** aplicação única com todos os módulos integrados;
* **Microsserviço:** serviço pequeno e independente;
* **SOA:** arquitetura baseada em serviços reutilizáveis;
* **Clean Architecture:** abordagem focada em separação de responsabilidades;
* **Célula:** unidade independente dentro de uma arquitetura distribuída;
* **API:** interface de comunicação entre sistemas;
* **Deploy:** processo de publicação de software.

---

### ♻️ Prompts Reutilizáveis

* "Explique a arquitetura [X] com exemplos práticos"
* "Compare arquitetura monolítica vs microsserviços"
* "Quando devo usar arquitetura orientada a serviços?"
* "Quais são os trade-offs da arquitetura baseada em células?"
* "Explique arquitetura limpa como se eu fosse iniciante"
* "Quais erros comuns ao implementar microsserviços?"

---

### ⚙️ Conceitos Fundamentais

- Acoplamento: grau de dependência entre módulos;
- Coesão: o quanto um módulo é focado em uma única responsabilidade;
- Escalabilidade: capacidade de crescer;
- Resiliência: capacidade de lidar com falhas.
