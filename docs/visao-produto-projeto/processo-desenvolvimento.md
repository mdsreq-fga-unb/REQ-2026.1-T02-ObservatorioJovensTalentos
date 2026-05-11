# Processo de Desenvolvimento de Software

##  Estratégias de Engenharia de Software

### Estratégia Priorizada

| Campo | Decisão |
|-------|---------|
| **Abordagem** | Dirigida por Plano |
| **Ciclo de Vida** | Sequencial |
| **Processo** | Modelo V com Prototipagem |

A abordagem dirigida por plano foi escolhida por enfatizar a previsibilidade, a estrutura e a documentação detalhada em todas as fases do desenvolvimento de software. O Ciclo de Vida sequencial será de alta importância por facilitar o desenvolvimento assíncrono da solução após a fase inicial de Requisitos e Prototipação, que serão feitas juntamente ao representante do cliente. A inclusão de uma fase de prototipagem de alta fidelidade como marco de validação complementa a abordagem, garantindo que a interface, usabilidade e fluxo das funcionalidades estejam alinhados com as expectativas dos stakeholders. O desenvolvimento do código-fonte será acompanhado por testes, estabelecendo uma rastreabilidade clara entre requisitos, protótipo e implementação, evitando retrabalho custoso e garantindo qualidade interna além da validação visual.

### Quadro Comparativo

| Critério | Cascata | Modelo V | Unified Process (UP) |
| --- | --- | --- | --- |
| **Estrutura de Fases** | Sequencial linear (Req → Design → Impl → Teste → Entrega) | Sequencial com correspondência teste-desenvolvimento (estrutura em V) | Iterativo com fases sequenciais (Inception, Elaboration, Construction, Transition) |
| **Foco em Testes** | Testes após desenvolvimento completo | Testes planejados em paralelo com desenvolvimento, correspondência direta requisito-teste | Testes integrados em cada iteração |
| **Níveis de Teste** | Teste de sistema e aceitação | Testes em múltiplos níveis (unidade, integração, sistema, aceitação) | Testes em múltiplos níveis por iteração |
| **Rastreabilidade** | Requisitos → Documentação → Código | Requisitos → Testes (cada nível de requisito tem teste correspondente) | Requisitos → Artefatos → Código (por iteração) |
| **Validação com Cliente** | Formal ao final da fase de requisitos | Formal ao final de requisitos + contínua durante testes | Contínua em cada iteração |
| **Gestão de Mudanças** | Rigorosa e formal | Rigorosa com propagação para planos de teste | Formal mas adaptável |
| **Documentação** | Muito abrangente | Muito abrangente | Abrangente com foco em essencial |
| **Início da Codificação** | Após aprovação completa de requisitos | Após aprovação de requisitos e planejamento de testes | Progressivo, por iteração |
| **Adequação a Requisitos Estáveis** | Alta | Alta | Moderada |
| **Adequação a Requisitos Parcialmente Definidos** | Baixa | Baixa | Alta |
| **Detecção Precoce de Problemas** | Moderada (descoberta tardia) | Alta (testes planejados antecipadamente) | Alta (feedback contínuo) |
| **Redução de Retrabalho** | Moderada | Alta (problemas detectados cedo) | Alta (iterações curtas) |
| **Adequação ao Contexto Acadêmico** | Alta | Alta | Alta |
| **Adequação a Equipes Pequenas** | Moderada | Moderada | Alta |
| **Complexidade do Processo** | Baixa | Moderada | Alta |

### Justificativa

A escolha pelo **Modelo V como Ciclo de Vida** fundamenta-se em três argumentos principais:

**Validação em múltiplos níveis:** O Modelo V estabelece uma correspondência direta entre cada nível de requisito e seu respectivo nível de teste. Esta estrutura garante que a funcionalidade seja validada não apenas do ponto de vista do usuário (através do protótipo), mas também internamente em cada camada da arquitetura, reduzindo significativamente o risco de defeitos não detectados.

**Detecção precoce de problemas através da rastreabilidade:** Ao contrário do Cascata tradicional, onde testes ocorrem apenas após o desenvolvimento completo, o Modelo V planeja os testes em paralelo com o desenvolvimento. Esta abordagem permite que ambiguidades ou inconsistências nos requisitos sejam identificadas cedo, durante a elaboração dos planos de teste, evitando retrabalho custoso nas fases posteriores, o que também gera indicações cedo de problemas referentes à capacidade técnica da equipe ou de algum processo. 

**Desenvolvimento Assíncrono:** Com a estratégia definida, a equipe poderá desfrutar de um modelo base (protótipo) para realizar o desenvolvimento sem o envolvimento direto do cliente em diversas instâncias para esclarecimento ou desenvolvimento de requisitos. Quando necessário, o acordo feito pelo aceite do protótipo pode sempre ser revisado com novos requisitos ou desejos, desde que devidamente comunicado e aceito também pela equipe de desenvolvimento.

---

## Engenharia de Requisitos

### Atividades e Técnicas de ER

As atividades da Engenharia de Requisitos foram mapeadas para se alinharem à estrutura do Modelo V, garantindo que cada etapa produza os artefatos necessários para a fase subsequente e que testes sejam planejados em paralelo com o desenvolvimento.

**Elicitação e Descoberta**

Entrevistas e Discussões: Reuniões periódicas para levantar necessidades, expectativas e restrições do negócio de forma aprofundada.

Análise de documentos e tecnologias existentes: Revisão de materiais teóricos e dados sobre a evasão de jovens aprendizes para embasar a solução, assim como tecnologias utilizadas no contexto da solução.

Brainstorming: A Equipe, junto e separado do cliente, irá gerar ideias e visões gerais para então serem acordadas com o cliente.

**Análise e Consenso**

MoSCoW: Técnica de priorização para definir claramente o escopo do que deve estar presente na versão final.

Prototipagem: Técnica para representar a compreensão do requisito e moldar conforme feedback dos envolvidos.

Entrevista: Reuniões com o cliente para discussão dos requisitos e viabilidade dos mesmos.

**Declaração**

Especificação Formal: Documentação detalhada dos requisitos funcionais e não funcionais, servindo como contrato para o desenvolvimento e como base para os planos de teste.

User Stories: Descrições focadas no valor entregue aos instrutores e orientadores, complementadas por critérios de aceitação testáveis.

**Representação**

Prototipagem: Criação de interfaces interativas e navegáveis que representam fielmente o produto final, servindo como validação dos requisitos de negócio.

Wireframes: Esboços iniciais para validação rápida de estrutura antes da alta fidelidade.

**Verificação e Validação**

Inspeção Técnica / Revisão: Revisão interna da equipe sobre a documentação gerada, incluindo verificação de completude, consistência e testabilidade dos requisitos.

Feedback do Protótipo: Sessões com o cliente para aprovação dos requisitos de negócio através do protótipo de alta fidelidade, marco essencial para o avanço do projeto.

Execução de Testes em Múltiplos Níveis: Durante o desenvolvimento, testes são executados em diversos níveis, estabelecendo correspondência direta com os requisitos.

Rastreamento de Defeitos: Mapeamento de defeitos encontrados durante testes de volta aos requisitos que os geraram, facilitando correção e aprendizado.

**Organização e Atualização**

Matriz de Rastreabilidade Completa: Mapeamento entre os requisitos declarados, as telas do protótipo, os módulos de código e os testes correspondentes.

Controle de Mudanças Formal: Qualquer alteração solicitada após a aprovação do protótipo passará por análise de impacto, considerando não apenas o código, mas também os planos de teste correspondentes, mantendo a integridade da estrutura em V.

### Mapeamento ER × Processo

| Fase do Processo (Modelo V) | Atividade ER | Técnica Principal | Resultado Esperado |
| --- | --- | --- | --- |
| **1. Requisitos** | Elicitação e Análise | Entrevistas e Discussões + Brainstorming | Lista abrangente de necessidades, desejos e frustrações |
| **1. Requisitos** | Análise e Consenso | Prototipagem + Entrevista | Escopo definido, priorizado e estruturado por níveis |
| **1. Requisitos** | Declaração | Especificação Formal + User Stories | Documento de Requisitos v2.0 com rastreabilidade |
| **1. Requisitos** | Organização e Atualização | Matriz de Rastreabilidade | Mapeamento dos requisitos com objetivos e características |
| **2. Design/Prototipagem** | Representação | Protótipo de Alta Fidelidade + Wireframes | Protótipo navegável + Planos de teste em paralelo |
| **3. Validação** | Verificação e Validação | Revisão + Feedback | Protótipo de Alta Fidelidade aprovado para desenvolvimento |
| **4. Implementação** | Verificação e Validação | Inspeção Técnica/Revisão + Testes + Rastreamento de Defeitos | Código com testes de unidade passando |
| **4. Implementação** | Organização e Atualização | Matriz de Rastreabilidade | Rastreamento dos testes e seus resultados |
| **5. Integração** | Verificação e Validação | Inspeção Técnica/Revisão + Testes | Módulos integrados com testes de sistema passando |
| **5. Integração** | Organização e Atualização | Matriz de Rastreabilidade | Rastreamento dos testes e seus resultados |
| **6. Testes de Aceitação** | Verificação e Validação | Testes de Aceitação baseados no protótipo | Software validado contra requisitos e protótipo |
| **7. Entrega** | Verificação e Validação | Feedback | Cliente aprova a entrega completa ou realize o último pedido de ajustes rápidos |
| **7. Entrega** | Organização e Atualização | Matriz de Rastreabilidade Completa | MVP em produção com documentação completa |

## Histórico de versões

| Versão | Data | Descrição | 
|:--------:|:-------:|:-------------------:|
| 1.0 | 13/04 | Versão inicial do documento|
| 2.0 | 05/05 | Mudança na Estratégia de Desenvolvimento e ajustes correspondentes |