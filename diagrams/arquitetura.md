# Diagrama conceitual da arquitetura

## Visão em camadas

**Pessoas usuárias e perfis autorizados**

↓

**Interface web**

Workspaces de dashboard, inventário, suporte, movimentações, estrutura,
usuários, histórico e análise.

↓

**Aplicação web em Python e Flask**

Casos de uso, validações e coordenação dos fluxos operacionais.

↓

**Núcleo modular do ecossistema Aster**

Contratos compartilhados em separação progressiva, com os domínios do AsterTI
preservando suas responsabilidades específicas.

↓

**Segurança e governança**

Autenticação, sessão, perfis, escopo, proteção de recursos e auditoria.

↓

**Persistência atual em SQLite**

Dados relacionais, histórico e referências protegidas a documentos.

## Relações principais

| Origem | Relação | Destino |
|---|---|---|
| Inventário | fornece contexto | Movimentações e chamados |
| Estrutura institucional | delimita | Localização, responsabilidade e escopo |
| Usuários e perfis | condicionam | Ações e visualizações permitidas |
| Operações | geram | Histórico, notificações e indicadores |
| Dados consolidados | alimentam | Dashboard e Análise Operacional |

Este diagrama é propositalmente conceitual. Ele não representa componentes,
interfaces internas, infraestrutura ou modelo físico de dados.
