## Objetivo do Projeto

Desenvolver um agente de Inteligência Artificial capaz de auxiliar usuários com baixa familiaridade digital e financeira, oferecendo suporte para dúvidas do dia a dia relacionadas a serviços bancários, utilizando linguagem simples, acessível e didática.

---

## Etapas Desenvolvidas

### 1. Definição do Problema e Público-Alvo

Foi identificado o desafio de acessibilidade na compreensão de informações financeiras, especialmente para usuários com pouca experiência em tecnologia ou termos bancários.

**Público-alvo definido:**
- Usuários iniciantes em aplicativos bancários  
- Pessoas com dificuldade de interpretação financeira  
- Usuários que preferem comunicação simples e objetiva  

---

### 2. Estruturação da Arquitetura do Agente

Foi construído um fluxo estruturado contemplando:

- Interface de interação com o usuário  
- Construção de prompt (Prompt Engineering)  
- Processamento via modelo de linguagem (LLM)  
- Integração com base de conhecimento (RAG)  
- Validação e segurança das respostas  
- Loop de interação contínua  

Essa arquitetura permitiu simular um cenário mais próximo de aplicações reais.

---

### 3. Definição de Prompt e Regras do Agente

Foram estabelecidas diretrizes claras para o comportamento do agente:

- Uso de linguagem simples e acessível  
- Respostas curtas e didáticas  
- Tom acolhedor e não julgador  
- Proibição de aconselhamento financeiro avançado  
- Regras de segurança (não solicitar dados sensíveis)  

Além disso, foi adotada uma abordagem centrada no usuário, priorizando clareza sobre tecnicidade.

---

### 4. Criação de Cenários de Uso

Foram desenvolvidos cenários práticos para simular interações reais, como:

- Dúvidas sobre saldo disponível  
- Funcionamento da fatura do cartão de crédito  
- Situações de saldo negativo  

Esses cenários ajudaram a validar a capacidade do agente de traduzir conceitos financeiros para linguagem simples.

---

### 5. Tratamento de Edge Cases

Foram mapeadas situações fora do fluxo ideal, incluindo:

- Perguntas fora do escopo  
- Solicitações de aconselhamento financeiro  
- Tentativas de compartilhamento de dados sensíveis  

O agente foi configurado para responder com segurança, mantendo o foco no escopo definido.

---

## Testes e Validação

### Resultados observados

**Pontos positivos:**
- O agente foi executado com sucesso em ambiente local  
- Demonstrou capacidade de resposta coerente e contextualizada  
- Aplicou corretamente linguagem simplificada  

**Pontos de atenção:**
- Tempo de resposta elevado (superior a 5 minutos)  
- Respostas iniciais excessivamente longas  

---

## Melhorias Identificadas

Com base nos testes realizados, foram levantadas oportunidades de evolução:

- Otimização de desempenho (tempo de resposta)  
- Refinamento dos prompts para respostas mais objetivas  
- Realização de testes via API para maior controle e escalabilidade  
- Validação com usuários reais para coleta de feedback  
- Iteração contínua com novos testes locais  

---

## Próximos Passos

Para evolução do projeto, recomenda-se:

- Implementar testes automatizados do agente  
- Ajustar o prompt para controle de tamanho das respostas  
- Monitorar métricas de qualidade (clareza, tempo de resposta)  
- Expandir a base de cenários e edge cases  
- Explorar integração com interfaces mais amigáveis (ex: chatbot web)

---

## Conclusão

O projeto demonstrou, na prática, a aplicação dos conceitos de IA Generativa, incluindo Prompt Engineering, estruturação de agentes e boas práticas de segurança.

Além disso, evidenciou o potencial da IA como ferramenta de inclusão digital e financeira, ao tornar informações complexas mais acessíveis para diferentes perfis de usuários.
