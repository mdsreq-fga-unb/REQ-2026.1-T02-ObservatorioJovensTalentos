# Requisitos Não Funcionais

| ID | Categoria | Requisito Não Funcional |
|---|---|---|
| RNF01 | Usabilidade | A interface deve permitir que os novos usuários consigam concluir o registro de frequência e relatos em até 5 minutos, dispensando treinamento formal prévio |
| RNF02 | Usabilidade | A interface deve utilizar linguagem natural e adequada ao público jovem e educacional |
| RNF03 | Acessibilidade | A aplicação deve apresentar as mesmas respostas para dispositivos móveis(320px) e desktops(1920px) |
| RNF04 | Desempenho | Os dashboards devem carregar suas informações principais em até 2 segundos quando o sistema estiver sem carga elevada ou em manutenção |
| RNF05 | Desempenho | O sistema deve suportar picos simultâneos de registro de frequência conforme volume de turmas ativas, até um valor de 250 acessos simultâneos |
| RNF06 | Confiabilidade | O sistema deve manter disponibilidade mínima de 99,5% durante o horário de funcionamento das atividades formativas (até 4 horas consecutivas) |
| RNF07 | Confiabilidade | O banco de dados deve possuir rotina de backup automático diário |
| RNF08 | Segurança | A comunicação entre cliente e servidor deve utilizar HTTPS em produção |
| RNF09 | Segurança | O sistema deve controlar acesso às funcionalidades conforme papel do usuário |
| RNF10 | Segurança / Legalidade | O sistema deve tratar dados pessoais e relatos sensíveis conforme princípios de privacidade e proteção de dados (LGPD) |
| RNF11 | Privacidade | Relatos anônimos não devem exibir a identidade do aprendiz para usuários não autorizados |
| RNF12 | Auditabilidade | O sistema deve registrar logs de ações críticas |
| RNF13 | Manutenibilidade | O código deve possuir testes automatizados para funcionalidades críticas |
| RNF14 | Portabilidade | A aplicação deve ser conteinerizada para facilitar implantação e manutenção |
| RNF15 | Restrição de Implementação | O front-end deve ser desenvolvido em React |
| RNF16 | Restrição de Implementação | O back-end deve ser desenvolvido em Python com Flask |
| RNF17 | Restrição de Implementação | O banco de dados relacional deve utilizar PostgreSQL |
| RNF18 | Integridade | Alterações em registros de frequência devem manter histórico de alteração |
| RNF19 | Ética e Transparência | Alertas de risco de evasão devem permitir análise humana dos fatores considerados |
| RNF20 | Segurança Operacional | A validação de presença deve seguir regra institucional definida |
| RNF21 | Usabilidade | O sistema deve ser capaz de filtrar indicadores do dashboard por turma, aprendiz, período e estágio |
| RNF22 | Implementação | O sistema deve calcular pontuação e progresso do aprendiz |

## Histórico de versões

| Versão | Data | Descrição | 
|:--------:|:-------:|:-------------------:|
| 1.0 | 18/05 | Versão inicial do documento|