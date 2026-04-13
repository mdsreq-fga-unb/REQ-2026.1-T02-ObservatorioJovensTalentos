# Visão do Produto

## 1. Cenário Atual do Cliente e do Negócio

### 1.1 Identificação do Cliente/Parceiro

| Campo | Informação |
|-------|-----------|
| **Nome** | Anderson Brito de Figueiredo |
| **Tipo** | Pessoa Física — Instrutor de projeto com jovens aprendizes |
| **Representante** | Ana das Graças Ferreira Rodrigues (Líder de equipe) |
| **Forma de contato** | Reuniões periódicas e canal de mensagem instantânea |
| **Vínculo com o projeto** | Cliente real e parte interessada principal |

### 1.2 Introdução ao Negócio e Contexto

O **Observatório de Talentos do Transporte** é um ecossistema integrado de gestão da jornada do aprendiz, idealizado em 2026 por estudantes do SEST SENAT B093, em Luzânia. O projeto é voltado para empresas do setor de transporte e jovens em formação profissional, com o objetivo de oferecer uma **plataforma tecnológica com modelo de negócio sustentável** capaz de mitigar a evasão escolar e fomentar o engajamento por meio de reconhecimento.

A solução opera conectando o ambiente educacional presencial com os sistemas das empresas parceiras, realizando integração via API e por meio de um aplicativo próprio — o **"Jornada Transporte +"** — que centraliza dados de frequência, desempenho e engajamento dos aprendizes.

A missão central do projeto é transformar as primeiras semanas profissionais dos jovens aprendizes, promovendo um acolhimento humanizado capaz de erradicar a invisibilidade que esses jovens frequentemente enfrentam, aumentando suas chances de efetivação na carreira e reduzindo a taxa de evasão atual de 30%, com meta de atingir um ROI de 94% para as organizações parceiras.

### 1.3 Rich Picture

O diagrama a seguir representa o cenário atual da evasão, intitulado **"O Cenário da Evasão: A Jornada Desconectada do Aprendiz"**. Ele ilustra os principais atores, fluxos de informação e pontos de ruptura que motivam a proposta do projeto.

![Rich Picture - Cenário da Evasão](../assets/images/rich-picture.png)

*Figura 1: O Cenário da Evasão — A Jornada Desconectada do Aprendiz.*

### 1.4 Identificação da Oportunidade ou Problema

A necessidade de mitigar a alta evasão de jovens aprendizes no setor de transporte constitui um problema complexo, motivado por empecilhos de natureza organizacional e tecnológica. Três categorias principais de causas foram identificadas:

**Falhas de processo** — Carência de um acolhimento estruturado nas primeiras semanas e invisibilidade do desempenho dos aprendizes perante as organizações parceiras e a própria instituição de ensino.

**Limitações tecnológicas** — Ausência de canais de comunicação humanizados entre aprendizes, instrutores e gestores, combinada com a falta de integração entre os sistemas das instituições de ensino e das organizações parceiras.

**Lacunas de indicadores** — Inexistência de dados rastreáveis sobre o ROI da formação de aprendizes e desmotivação gerada pela falta de feedbacks estruturados ao longo da jornada.

![Diagrama de Ishikawa](../assets/images/ishikawa-diagram.png)

*Figura 2: Diagrama de Ishikawa — Causas da Evasão de Jovens Aprendizes.*

### 1.5 Desafios do Projeto

| Desafio | Impacto Atual |
|---------|--------------|
| **Baixa retenção dos jovens** | Taxa de evasão de ~25% nas primeiras semanas |
| **Processos manuais** | ~5h/mês em chamadas manuais por instrutor |
| **Baixo engajamento** | Sensação de invisibilidade e ausência de canal de suporte |
| **Falta de dados rastreáveis** | 0% de dados sobre efetivação pós-curso |

### 1.6 Mapa de Stakeholders

| Stakeholder | Relação com a Solução | Interesses e Expectativas | Nível de Influência | Participação |
|---|---|---|---|---|
| **Instrutores e orientadores** | Usuários principais | Otimização do tempo, melhoria no acompanhamento | Alto | Uso diário |
| **Jovens aprendizes** | Usuários secundários | Reconhecimento, acolhimento, visibilidade | Médio | Gamificação |
| **Gestores institucionais** | Parceiros estratégicos | Dados de efetivação, fortalecimento | Alto | Decisões estratégicas |
| **Organizações parceiras** | Beneficiários de resultados | Redução de custos, formação de qualidade | Baixo | Relatórios de desempenho |

### 1.7 Segmentação de Clientes

=== "Segmento 1 — Cliente"

    **Gestores, Profissionais de RH e Instrutores Pedagógicos**

    Este segmento é composto pelos profissionais responsáveis pelo acolhimento, treinamento e liderança dos jovens aprendizes dentro das instituições de ensino e das organizações parceiras.

    Enfrentam a ausência de ferramentas integradas para acompanhar a jornada dos aprendizes de forma contínua, o que dificulta a identificação precoce de riscos de evasão e a demonstração de resultados para as organizações parceiras.

=== "Segmento 2 — Usuário Final"

    **Jovens Aprendizes (14 a 24 anos)**

    Jovens em processo de formação profissional, muitas vezes com baixa familiaridade com ambientes corporativos e com necessidades de suporte emocional e orientação prática.

    Tendem a se desmotivar rapidamente diante de ambientes impessoais, mas são altamente responsivos a mecânicas de gamificação, reconhecimento de conquistas e comunicação direta e humanizada.

---

## 2. Solução Proposta

### 2.1 Objetivo Geral do Produto

O produto proposto tem como objetivo geral **mitigar as causas da evasão de jovens aprendizes** no setor de transporte, aumentando a retenção e o engajamento por meio de um sistema de pontuação e reconhecimento.

### 2.2 Objetivos Específicos

| ID | Objetivo Específico |
|----|---------------------|
| **OE1** | Reduzir a evasão por meio de comunicação, acolhimento e suporte contínuo |
| **OE2** | Demonstrar o valor da retenção para as organizações parceiras por meio de métricas de ROI |
| **OE3** | Monitorar continuamente o desempenho, a assiduidade e a evolução dos aprendizes |
| **OE4** | Aumentar o engajamento dos jovens por meio de mecânicas de gamificação |
| **OE5** | Otimizar o tempo de trabalho dos instrutores, reduzindo tarefas manuais repetitivas |
| **OE6** | Viabilizar a tomada de decisão estratégica baseada em dados |

### 2.3 Características do Produto

| OE Principal | ID | Característica | Descrição | Valor de Negócio |
|:---:|:---:|---|---|---|
| OE4 | C1 | **Sistema de Gamificação** | Pontuação, conquistas e ranking por frequência e desempenho | Engajamento e redução da invisibilidade |
| OE3 | C2 | **Dashboard Educacional** | Painel em tempo real com indicadores individuais e coletivos | Visibilidade do progresso |
| OE1 | C3 | **Alertas Preditivos de Evasão** | Identificação automática de padrões de risco com notificações | Intervenção precoce |
| OE1 | C4 | **Canal de Acolhimento** | Comunicação humanizada com FAQ e suporte a dúvidas | Redução do abandono nas primeiras semanas |
| OE5 | C5 | **Automatização de Frequência** | Registro automatizado de presença integrado ao sistema | Economia de ~5h/mês por instrutor |
| OE2 | C6 | **Gerador de Relatórios** | Relatórios automáticos de desempenho, retenção e ROI | Embasamento para decisões estratégicas |

### 2.4 Tecnologias Utilizadas

| Camada | Tecnologia | Justificativa |
|--------|-----------|---------------|
| **Front-end** | React | Ecossistema maduro, componentes reutilizáveis |
| **Back-end** | Flask (Python) | Framework leve, adequado para APIs REST |
| **Banco de Dados** | PostgreSQL | Banco relacional robusto e escalável |
| **Testes** | pytest | Framework de testes para Python |
| **Deploy** | Docker | Containerização para portabilidade |

### 2.5 Análise Competitiva

| Solução | Gamificação | Alerta Preditivo | Foco em Aprendizes |
|---------|:-----------:|:----------------:|:------------------|
| Ludos Pro | ✅ | ❌ | ❌ |
| Feedz (TOTVS) | ✅ | ❌ | ❌ |
| Niduu (Gupy) | Parcial | ❌ | ❌ |
| Taqe | ❌ | ❌ | ✅ |
| **Observatório de Talentos** | ✅ | ✅ | ✅ |

### 2.6 Viabilidade da Proposta

A viabilidade técnica da proposta é considerada **alta**, uma vez que a equipe possui experiência prévia com as tecnologias selecionadas. O escopo do MVP será deliberadamente delimitado para ser entregável dentro do prazo do semestre letivo, priorizando as características de maior impacto (C1, C3 e C5).

### 2.7 Benefícios Esperados

**Para o cliente (gestores, instrutores e organizações parceiras):** Redução do tempo em tarefas administrativas manuais, acesso a dados consolidados de desempenho e retenção, e relatórios de ROI que demonstram objetivamente o retorno do investimento em formação.

**Para os usuários finais (jovens aprendizes):** Ambiente de aprendizagem mais acolhedor e transparente, reconhecimento contínuo do esforço, redução da sensação de abandono e aumento das chances de efetivação ao final do programa.
