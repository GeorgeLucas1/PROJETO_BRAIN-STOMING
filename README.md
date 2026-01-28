# Brainstorming – Sistema de Apoio à Gestão de Reuniões

Projeto front-end desenvolvido em Vue.js, concebido como uma iniciativa autoral para evolução futura em uma plataforma de apoio à gestão de projetos.

Nesta versão, o sistema é exclusivamente front-end, sem integração com back-end. Os dados são temporários e podem ser perdidos ao recarregar a aplicação.
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/9a393024-0b66-4994-ac64-30df2dcbe33a" />


## Conceito Central

O sistema adota uma abordagem em que a **reunião é o núcleo do fluxo organizacional**, servindo como ponto de origem para decisões, ações e rastreabilidade.

## Princípios do Sistema

### 1. Reunião como núcleo do sistema

Diferentemente de ferramentas tradicionais, onde reuniões são tratadas como elementos secundários, este sistema posiciona a reunião como o elemento central do processo.

A partir de cada reunião, o sistema permite:
- Geração de tarefas
- Registro de decisões
- Identificação de riscos
- Criação de indicadores relacionados a projetos e áreas

A reunião passa a ser o ponto inicial para a organização e acompanhamento das atividades.

### 2. Rastreabilidade total

Todas as decisões registradas em reuniões podem ser vinculadas a:
- Tarefas
- Épicos
- Sprints
- Cronogramas
- Responsáveis

O sistema mantém histórico auditável, permitindo rastrear:
- Quem tomou a decisão
- Quando a decisão foi tomada
- Qual foi o impacto gerado

Esse modelo garante transparência, controle e consistência na evolução dos projetos.

## Observações Técnicas

- Aplicação exclusivamente front-end  
- Persistência de dados temporária (memória ou local storage)  
- Foco em prototipação, validação de fluxos e usabilidade  
- Evolução futura prevista com integração back-end(autenticação,banco de dados e etc)
