# Histórico público — AsterTI

Este histórico resume marcos confirmados no projeto privado sem reproduzir
detalhes de implementação.

## 1.72 — 26/08/2026

- entregue o módulo de Remessa: envio e recebimento de um lote de ativos
  e/ou material entre unidades numa única operação, com numeração e
  documento formal próprios;
- corrigida uma inconsistência de posse em que um ativo marcado como
  disponível para reserva podia manter um responsável vinculado;
- consolidado o registro de auditoria de uma remessa em um único evento,
  em vez de um evento por ativo movimentado;
- aprimorada a seleção automática de almoxarifado por unidade de
  visualização e a ordenação da tela de entradas e saídas.

## 1.71 — 24/08/2026

- corrigida uma falha que impedia a geração de documentos formais
  (movimentação, termo de posse, devolução, envio para manutenção);
- reorganizados os quatro documentos formais, com papéis mais claros
  entre movimentação e devolução;
- entregue o primeiro conjunto de exportações e métricas do Aster
  Estoque por modelo de ativo;
- corrigida uma condição de corrida na renovação de sessão.

## 1.70 — 22/08/2026

- entregue uma linha do tempo consolidada do histórico de cada ativo;
- unificados os catálogos de defeito técnico do Suporte Técnico;
- reformulado o cadastro de item de estoque em duas etapas;
- diversas correções pontuais de movimentações, cadastros e interface.

## 1.60 a 1.66 — 18 a 19/08/2026

- reestruturado o workspace de chamado técnico em ficha de consulta e
  acompanhamento de ação;
- ampliado o povoamento de demonstração do Aster Estoque;
- revisados desempenho de interface, mascaramento de dado sensível e
  índices de performance do histórico de ações;
- padronizado o comprimento mínimo de justificativa em ações sensíveis.

## 1.55 a 1.57 — 13 a 17/08/2026

- o Aster Estoque passou a compartilhar a mesma camada de persistência e
  o mesmo motor de permissões do núcleo compartilhado;
- entregue a primeira integração funcional entre Inventário e Aster
  Estoque — naturezas operacionais, componentes reutilizáveis e
  previsão de troca de suprimento;
- redesenhado o fluxo de movimentação de ativo em tela única.

## 1.35 a 1.50 — 10 a 12/08/2026

- o Aster Estoque passou a ser um módulo real e opcional da plataforma,
  habilitável por instalação;
- entregues o papel de Administrador da Plataforma e o painel de
  gerenciamento de módulos;
- ampliado o suporte a múltiplos almoxarifados.

## 1.10 a 1.20 — 03 a 07/08/2026

- concluída a separação arquitetural entre o núcleo compartilhado do
  ecossistema Aster e o produto AsterTI;
- validada a compatibilidade com PostgreSQL como persistência
  alternativa ao SQLite.

## 1.02 a 1.09 — agosto de 2026

- consolidada a fronteira entre o núcleo compartilhado e as regras
  próprias do AsterTI, sem alteração perceptível de funcionalidade.

## 1.01 — 29/07/2026

- criada a primeira fronteira do núcleo compartilhado do ecossistema Aster;
- entregue a Central de Análise Operacional com indicadores, tendências,
  rankings e alertas;
- aprimorada a clareza das notificações e do histórico;
- reorganizado o fluxo visual de destino das movimentações;
- unificado o indicador de etapas dos formulários;
- ajustada a atribuição de chamados entre contextos autorizados.

## 1.00 — 27/07/2026

- concluído o plano de estabilização funcional;
- consolidados inventário, chamados, movimentações, reserva, usuários e
  auditoria sobre SQLite;
- aprimorados os cadastros de pessoas e usuários;
- ampliados os dados de demonstração e as validações de integridade;
- corrigidos pontos de responsividade, navegação e consistência de histórico.

## 0.99 — 26/07/2026

- ampliado o domínio persistente de chamados;
- aprimorados filtros e agrupamentos de histórico;
- refinada a apresentação de movimentações e atividades.

## 0.98 — 25/07/2026

- concluída uma rodada de validação assistida dos perfis de acesso;
- aprimorada a auditoria de cadastros e chamados.

## 0.97 — 23/07/2026

- consolidado o fluxo de reserva e armazenamento;
- reforçadas regras do ciclo de vida dos ativos;
- aprimorados cadastros, tabelas e histórico.

## 0.94 a 0.96 — julho de 2026

- reforçadas autenticação, permissões, escopo e segurança;
- reorganizada a navegação;
- aprimorados credenciais temporárias, perfil pessoal e proteção de arquivos.

## Observação

Alterações ainda não publicadas no projeto privado não fazem parte deste
histórico público.
