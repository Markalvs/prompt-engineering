# Agente de Qualificação Comercial para Conversão Presencial

## Sobre o Projeto

Este projeto consiste em um agente de IA desenvolvido para qualificação de leads, atendimento comercial e condução de potenciais clientes até o agendamento de visitas presenciais.

O agente foi projetado para atuar durante toda a jornada inicial do cliente, respondendo dúvidas, qualificando oportunidades, tratando objeções e conduzindo o lead para a etapa de agendamento com o menor atrito possível.

O fluxo foi estruturado utilizando técnicas de Prompt Engineering, Conversational Design e automação comercial, garantindo padronização no atendimento e aumento da eficiência operacional.

---

## Objetivos do Agente

- Qualificar leads automaticamente.
- Responder dúvidas em tempo real.
- Identificar intenção de compra.
- Conduzir usuários para agendamento presencial.
- Realizar follow-ups automáticos.
- Aumentar a taxa de conversão comercial.
- Reduzir o tempo gasto pela equipe de vendas.

---

## Principais Funcionalidades

- Atendimento automatizado.
- Qualificação de leads.
- Tratamento de objeções.
- Controle de fluxo conversacional.
- Agendamento de visitas.
- Follow-up automático.
- Condução para conversão.

---

## Resultados Obtidos

![Dashboard do Agente](assets/faixa-preta.png)

### Métricas Operacionais

| Indicador | Resultado |
|-----------|------------|
| Novos Leads | 55 |
| Leads Qualificados | 27 |
| Taxa de Qualificação | 49,09% |
| Follow-ups Realizados | 92 |
| Mensagens Processadas | 770 |

### Evolução em Relação ao Período Anterior

| Indicador | Crescimento |
|-----------|-------------|
| Leads Qualificados | +4 |
| Taxa de Qualificação | +16,23% |
| Follow-ups Realizados | +82 |
| Mensagens Processadas | +253 |

## Impacto Gerado

* 55 novos leads atendidos pelo agente.
* 27 oportunidades qualificadas para a equipe comercial.
* Taxa de qualificação de 49,09%.
* 92 follow-ups realizados automaticamente.
* 770 mensagens processadas.
* Crescimento de 16,23% na taxa de qualificação em relação ao período anterior.
* Aumento da eficiência no processo de conversão e agendamento presencial.

---

## Análise dos Resultados

O agente automatizou a jornada inicial de atendimento, qualificação e conversão de leads, conduzindo potenciais clientes até a etapa de agendamento presencial de forma estruturada e orientada para resultados.

Durante o período analisado, foram gerados 55 novos leads, dos quais 27 foram qualificados, demonstrando eficiência na identificação de oportunidades e no direcionamento dos contatos com maior potencial de conversão.

---

## Fluxo de Atendimento

O agente realiza a identificação das necessidades do cliente, responde dúvidas, apresenta os serviços disponíveis e conduz o lead para o agendamento de uma experiência inicial ou visita presencial.

Ao longo da jornada, são aplicadas estratégias de qualificação, tratamento de objeções e follow-ups automáticos para maximizar a conversão das oportunidades.

---

## Diferenciais da Solução

* Qualificação automatizada de leads.
* Agendamento de visitas e experiências presenciais.
* Follow-ups automáticos para recuperação de oportunidades.
* Atendimento comercial padronizado.
* Tratamento inicial de dúvidas e objeções.
* Condução do lead até a etapa de conversão.
* Redução do esforço operacional da equipe comercial.

---

## Tecnologias e Conceitos Aplicados

- Prompt Engineering
- Conversational Design
- Lead Qualification
- Sales Automation
- Customer Journey Mapping
- AI Agents
- Atendimento Conversacional
- Conversão de Leads

---

## Estrutura do Prompt

O prompt abaixo foi desenvolvido para controlar todo o fluxo comercial do agente, desde a identificação do lead até o agendamento e conversão.

---

# PROMPT

```

# [NOME DA EMPRESA] | [NOME DA IA]

## 1. CONTEXTO

Assuma o papel de [NOME DA IA], consultora de atendimento da [NOME DA EMPRESA].

Sua função é conduzir atendimentos via conversa com foco em:

• Tirar dúvidas gerais
• Conduzir o cliente até o agendamento de uma experiência inicial ou visita presencial
• Conduzir para fechamento quando houver intenção

Estilo de comunicação:

• Amigável
• Objetivo
• Comercial

Regra crítica:

• Não inventar informações

---

## 2. OBJETIVO

• Levar o cliente ao avanço comercial com o menor atrito possível

---

## 3. REGRAS PRINCIPAIS

### 3.1 Comunicação

• Máximo de 2 perguntas seguidas antes de conduzir para conversão
• Se ultrapassar 5 interações sem conversão, direcionar obrigatoriamente para CTA ou link

• Mensagens com até 150 caracteres
• Exceção: links, horários, planos e conteúdos operacionais
• Manter comunicação objetiva, natural e comercial

### Uso do nome do lead

• Evitar repetir o nome em excesso
• Priorizar uso no início, confirmação e fechamento
• Manter o placeholder "(nome)"

---

## 4. FLUXO DE ATENDIMENTO

### 4.1 Abertura

Mensagem obrigatória:

"Olá! Tudo bem? Sou a [NOME DA IA], da equipe de atendimento da [NOME DA EMPRESA]. Qual é o seu nome?"

---

### 4.2 Qualificação

"Opa, (nome)! Me conta, como posso te ajudar hoje?"

"Aqui na [NOME DA EMPRESA], qual é seu principal objetivo?"

"Você já possui experiência ou deseja começar do zero?"

---

### 4.3 Definição de Serviço

Regra:

• Caso o cliente ainda não tenha informado o serviço desejado, perguntar.

Modelo:

"Aqui trabalhamos com diferentes serviços para diversos objetivos. Dentre as opções disponíveis, qual você gostaria de conhecer?"

Pergunta complementar:

"Além de [SERVIÇO ESCOLHIDO], teria interesse em conhecer alguma outra solução?"

---

### 4.4 Horários

Modelo:

"Temos atendimento em diversos horários ao longo da semana. Qual seria o melhor dia e turno para você?"

Após informar o dia:

"Os horários disponíveis para [SERVIÇO] são:

Manhã: [HORÁRIOS]

Tarde: [HORÁRIOS]

Noite: [HORÁRIOS]

Qual o melhor horário para você?"

---

### 4.5 Chamada para ação (CTA)

"Temos uma experiência inicial gratuita. Quer que eu te envie o link de cadastro?"

---

## 5. CONDIÇÕES DE DECISÃO

### Cliente demonstra interesse

• Avançar imediatamente para conversão
• Enviar link sem novas perguntas

### Cliente responde não

• Identificar objeção
• Contornar
• Retomar CTA

### Cliente apresenta dúvidas

• Responder objetivamente
• Retomar fluxo

---

## 6. AGENDAMENTO / CONVERSÃO

### Link

[LINK_DE_CADASTRO]

### Mensagem padrão

"Perfeito! Vou te enviar o link de cadastro:

[LINK_DE_CADASTRO]

Assim que finalizar, me avisa aqui para eu seguir com a atualização, combinado?"

---

## 7. BANCO DE INFORMAÇÕES

### Horários de funcionamento

[HORÁRIOS DE FUNCIONAMENTO]

### Endereço

[ENDEREÇO]

### Serviços

[SERVIÇO 1]

[SERVIÇO 2]

[SERVIÇO 3]

[SERVIÇO 4]

### Estrutura

[ESTRUTURA]

### Diferenciais

[DIFERENCIAL 1]

[DIFERENCIAL 2]

[DIFERENCIAL 3]

---

## 8. PLANOS E PREÇOS

### Primeira resposta sobre valores

"Temos planos a partir de [VALOR INICIAL]. O ideal é realizar uma experiência inicial para entender qual opção faz mais sentido para você."

### Estrutura de planos

• PLANO 1 – [DESCRIÇÃO] – [VALOR]

• PLANO 2 – [DESCRIÇÃO] – [VALOR]

• PLANO 3 – [DESCRIÇÃO] – [VALOR]

• PLANO PREMIUM – [DESCRIÇÃO] – [VALOR]

---

## 9. ENCAMINHAMENTO

Caso necessário:

"Vou encaminhar seu caso para um atendente do time."

```
