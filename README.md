# App Oficina Segura

## Sobre o Projeto

O **App Oficina Segura** é uma aplicação desenvolvida com o objetivo de ajudar mulheres a evitarem abusos financeiros e falta de transparência em oficinas mecânicas.

O aplicativo permitirá consultar valores médios de serviços, registrar orçamentos recebidos e comparar preços, promovendo mais segurança, informação e autonomia.

---

## Problema

Muitas mulheres relatam:
- Falta de transparência nos orçamentos
- Valores inconsistentes para o mesmo serviço
- Linguagem técnica difícil de compreender
- Sensação de insegurança ao contratar serviços mecânicos

O projeto busca reduzir a assimetria de informação entre cliente e oficina.

---

## Público-Alvo

- Mulheres entre 18 e 60 anos
- Donas de veículos
- Pessoas com pouco conhecimento técnico automotivo
- Moradoras de áreas urbanas

---

## Proposta de Valor

O aplicativo permitirá:

- Consulta de valores médios por tipo de serviço
- Registro de orçamentos recebidos
- Comparação entre valores
- Explicação simplificada de peças e serviços
- Histórico de serviços realizados

---

## Funcionalidades (MVP)

- Cadastro de usuário
- Cadastro de serviço/orçamento
- Listagem de valores médios
- Comparação de preços
- Histórico de registros

---

## Estrutura de Dados

### Possíveis dados coletados:

- id_usuario (INT - PK)
- nome (VARCHAR)
- email (VARCHAR)
- tipo_servico (VARCHAR)
- valor_orcamento (FLOAT)
- cidade (VARCHAR)
- data_registro (DATE)

---

## Possíveis Análises de Dados

- Média de preço por cidade
- Serviço com maior variação de preço
- Identificação de valores fora do padrão
- Ranking de serviços mais solicitados

---

## Arquitetura Proposta

- Front-end: (Definir tecnologia)
- Back-end: (Definir tecnologia)
- Banco de Dados: (Definir SGBD)
- API REST

---

## Organização do Projeto

- Branch por funcionalidade
- Pull Request obrigatório
- Uso de Issues
- Kanban (GitHub Projects)

---

## Modelagem de Banco

Entregáveis obrigatórios:
- DER
- Modelo Lógico
- Definição de chaves primárias e estrangeiras

---

## Ética e Responsabilidade

- Dados devem ser protegidos
- Não expor informações pessoais
- Garantir segurança das informações

---

## Roadmap

Semana 1 – Pesquisa e definição do problema  
Semana 2 – Modelagem e protótipo  
Semana 3 – Backend  
Semana 4 – Frontend  
Semana 5 – Integração  
Semana 6 – Apresentação final  

---

## Equipe

(Adicionar nomes dos integrantes)

# App Oficina Segura – Pesquisa do Problema

## Equipe
**Integrantes:**  
- Nome 1  
- Nome 2  
- Nome 3  
- Nome 4  

---

# Objetivo da Semana 1

Nesta etapa **não será desenvolvido o aplicativo**.

O foco será realizar uma **pesquisa estruturada e fundamentada** sobre o problema que o projeto pretende resolver.

A equipe deve responder:

- O problema realmente existe?
- Ele é estrutural ou pontual?
- Pode ser analisado com dados?
- Pode ser tratado com Ciência de Dados?

---

# Compreender o Problema Estrutural

## Conceito Central: Assimetria de Informação

### Pesquisar:

- O que é assimetria de informação?
- Como isso afeta mercados de serviços?
- Por que serviços técnicos têm maior risco de abuso?
- Como a informação reduz desigualdade de poder?

### Produto Esperado:

- Explicação clara do conceito
- Conexão direta com oficinas mecânicas
- Aplicação prática do conceito ao projeto

---

# Existe Evidência de Discriminação de Preço?

## Investigar:

- Mulheres pagam mais caro em oficinas?
- Há estudos acadêmicos sobre isso?
- Existe diferença de abordagem quando o cliente demonstra desconhecimento técnico?

## Fontes para pesquisa:

- Experimentos sociais  
- Artigos acadêmicos  
- Reportagens investigativas  
- Dados do Procon  

A equipe deve apresentar evidências documentadas.

---

# Mapeamento do Problema no Brasil

Pesquisar evidências reais em:

- Reclamações registradas no Procon  
- Avaliações no Google Maps de oficinas  
- Reclamações no Reclame Aqui  
- Processos judiciais envolvendo oficinas  

## Pergunta Científica:

> O problema é percepção subjetiva ou possui base estatística?

A resposta deve ser fundamentada com dados.

---

# Formulação de Hipóteses

A equipe deve propor **hipóteses testáveis**, baseadas na pesquisa realizada.

## Exemplos:

- **H1** – Existe grande variação de preço para o mesmo serviço na mesma cidade.  
- **H2** – Serviços mais técnicos apresentam maior dispersão de preço.  
- **H3** – A falta de padronização de preços aumenta a insegurança do consumidor.  
- **H4** – Regiões centrais possuem maior média de preço.  

## Requisitos das hipóteses:

- Devem ser claras  
- Devem ser mensuráveis  
- Devem ter base teórica  
- Devem permitir análise estatística futura  

---

# Pesquisa sobre Variáveis Relevantes

Refletir:

> O preço depende apenas do serviço?

## Possíveis variáveis:

- Cidade  
- Bairro  
- Tipo da oficina (concessionária vs independente)  
- Tipo do carro  
- Marca  
- Ano  
- Urgência do serviço  
- Tipo de peça (original ou paralela)  

A equipe deve propor um **modelo inicial de variáveis para análise futura**.

---

# Pesquisa sobre Comportamento do Consumidor
Pesquisar conceitos como:

- Psicologia do consumo  
- Medo de parecer ignorante  
- Linguagem técnica como barreira  
- Confiança como fator econômico  

Objetivo: compreender o aspecto humano além do aspecto estatístico.

---
