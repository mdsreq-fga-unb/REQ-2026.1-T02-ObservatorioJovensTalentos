# Definition of Ready (DoR) e Definition of Done (DoD)

Esta seção define os critérios de qualidade e de aceite adotados pela equipe para a transição entre as fases de Especificação, Prototipagem e Implementação da solução, seguindo a abordagem dirigida por plano (Modelo V).

---

# Definition of Ready (DoR)

O DoR é o conjunto de critérios que define quando a especificação de um requisito (seja em formato formal ou de História de Usuário) está madura e estável o suficiente para sair da fase de Declaração e entrar na fase de Implementação.

Critérios do DoR:

| Critério | Descrição |
|---|---|
| Clareza e Formalização | O requisito deve estar formalmente declarado no Documento de Requisitos (podendo utilizar o formato de User Story como apoio para a empatia do usuário), contendo detalhes suficientes e sem ambiguidades para a equipe técnica. |
| Critérios de Aceitação | Os critérios de aceitação devem estar definidos de forma mensurável e alinhados aos planos de testes que serão executados nas fases posteriores do Modelo V. |
| Rastreabilidade Inicial | O requisito deve estar mapeado na Matriz de Rastreabilidade, conectado diretamente a um objetivo de negócio e às suas características. |
| Dependência | Todas as dependências técnicas ou lógicas do requisito precisam ser identificadas para viabilizar o desenvolvimento sequencial. |
| Validação Visual | O requisito deve possuir representação correspondente aprovada no Protótipo de Alta Fidelidade revisado junto ao representante do cliente. |
| Tamanho / Esforço | O requisito precisa ter seu esforço estimado e adequado para ser completado dentro do cronograma da fase de implementação. |

---

# Definition of Done (DoD)

O Definition of Done (DoD) garante a qualidade e a consistência da entrega técnica, atestando que a implementação cumpriu todas as validações progressivas exigidas pelo Modelo V antes de avançar para a fase de Entrega.

Critérios de DoD:

| Critério | Descrição |
|---|---|
| Código segue os padrões do projeto | O código deve respeitar a padronização das tecnologias escolhidas (React no Front-end, Python/Flask no Back-end, PostgreSQL e Docker) e convenções da equipe (Ref: RNF14 a RNF17). |
| Testes do Modelo V executados | O código deve passar pelas fases de verificação do Modelo V: Testes de Unidade, Testes de Integração e Testes de Aceitação (Ref: RNF13). |
| Conformidade com os Critérios de Aceite | A funcionalidade desenvolvida deve atender a 100% dos critérios de aceitação, regras de negócio e Restrições de Qualidade (como LGPD e tráfego HTTPS) estabelecidos na Especificação Formal (Ref: RNF08 e RNF10). |
| Fidelidade ao Protótipo Validado | O código deve ser idêntico ao Protótipo de Alta Fidelidade aprovado, ser totalmente responsivo (resoluções de 320px a 1920px) e seguir as diretrizes de acessibilidade (Ref: RNF03). |
| Matriz de Rastreabilidade Atualizada | A Matriz de Rastreabilidade Completa deve estar atualizada, conectando o requisito aprovado ao seu respectivo módulo de código e ao resultado dos testes de sistema. |
| Código aprovado por Inspeção Técnica | O código deve passar por uma inspeção técnica (revisão) por outro membro da equipe para rastreamento de defeitos antes da integração. |
| Documentação Técnica Finalizada | O MVP em produção deve estar acompanhado da documentação completa (APIs, manuais e logs). |