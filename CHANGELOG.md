# Histórico público — AsterTI

Este histórico resume marcos confirmados no projeto privado sem reproduzir
detalhes de implementação.

## 2.02 — 16/10/2026

- a Remessa passou a ser um conceito do Aster Estoque, utilizável também pelo
  AsterTI, com documento e planilha próprios do estoque;
- entrada e saída de usuários passaram a aparecer no histórico contextual por
  unidade, inclusive para perfis sem unidade fixa;
- cada solicitação ou cadastro de usuário ganhou um bloco de histórico na
  notificação correspondente;
- unificado o campo de posição ou função do ativo, com limite curto de
  caracteres, e a edição pela ficha deixou de trocar o responsável;
- o Mover Ativo pede confirmação, no próprio modal, para movimentações com
  consequência externa;
- as exportações em Excel passaram a buscar o texto em todas as colunas;
- aprimorados os dados de demonstração, com a forma de uma implantação real.

## 2.01 — 01/10/2026

- reforçadas a privacidade e a segurança: aviso de proteção de dados na tela de
  acesso, política de retenção e anonimização, acesso restrito às cópias de
  segurança, ícones servidos pela própria aplicação com política de conteúdo
  mais fechada e procedimento de resposta a incidentes;
- CPF e data de nascimento deixaram de ser coletados;
- exportações que cruzam módulos passaram a ficar visíveis e bloqueadas quando
  falta um módulo;
- materiais passaram a ser tratados como catálogo, com atalho para gerenciar o
  estoque;
- o cadastro de ativo passou a definir o tipo a partir do modelo;
- cadastros novos passaram a aparecer nos formulários sem recarregar a página;
- contagem de registros nas abas de usuários e da estrutura institucional.

## 2.00 — 30/09/2026

- consolidação do produto: movimentações com fluxo em painel lateral,
  realocação sem duplicidade e box de origem e destino;
- contagem de estoque com conferentes, registro no histórico e documento;
- catálogo de materiais compartilhado entre almoxarifados;
- relatório de ativos sob responsabilidade e novos relatórios de exportação;
- numeração única de documentos, com sigla por tipo;
- bloco de entidades externas, com classificação entre contratadas e parcerias;
- o vínculo externo do ativo passou a bloquear chamado e realocação.

## 1.98 e 1.99 — 19/09/2026

- manutenção em empresa contratada passou a gerar as movimentações de envio e
  de retorno, ligadas ao chamado;
- estoque com tipo de consumo e busca contextual;
- documentos gerados por evento, com pré-visualização em PDF do próprio
  documento;
- movimentações com ciclos de dois registros (saída e devolução),
  exportação e impressão direta da tabela e busca corrigida;
- exportações com período na própria barra.

## 1.95 a 1.97 — 15 e 16/09/2026

- relato de problemas pelo usuário, visível ao administrador da plataforma, com
  limite de envios;
- seletor de estoque técnico e modal de conclusão de manutenção ampliados;
- busca do inventário ampliada;
- corrigido o ícone de tipo de equipamento no inventário;
- suíte de testes contra PostgreSQL substancialmente mais rápida.

## 1.88 a 1.93 — 13 a 15/09/2026

- redesenho das badges de situação, tipo, status e estado;
- agrupamento de remessas nas movimentações;
- separação entre empresas contratadas e órgãos parceiros;
- widgets de estoque na página inicial do almoxarifado;
- padronização das cores de vínculo do equipamento;
- reserva automática por estoque técnico em remessas e transferências.

## 1.80 a 1.87 — 30/08 a 10/09/2026

- central de exportações e documentos formais revisados;
- custódia por pessoa, setor ou box/guichê na realocação interna;
- o suporte técnico passou a cadastrar ativos, sem movimentação automática;
- vínculo externo para ativos de outro órgão, gestão de box e guichê e remessa
  retroativa;
- termo de responsabilidade e workspace de estoque com painel de detalhes, baixa
  e exclusão;
- gráfico de vínculo na página inicial;
- coluna "De" das movimentações com o responsável da origem;
- refinamentos de remessa, chamados, setores e histórico a partir de uso real.

## 1.73 a 1.77 — 26 a 29/08/2026

- remessas disponíveis como relatório de exportação, com pré-visualização do
  documento;
- entradas e saídas com badges, consolidação por remessa e marca do fabricante
  como campo próprio;
- estoque técnico como destino de item de estoque;
- custódia institucional por box ou guichê, reorganização do inventário e dos
  usuários, e validação extensa por fluxos cruzados.

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
