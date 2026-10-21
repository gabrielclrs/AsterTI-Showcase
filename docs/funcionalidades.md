# Funcionalidades

Funcionalidades confirmadas na versão 2.02. As capturas de tela de cada área
estão no [tour visual](../README.md#tour-visual).

## Acesso e experiência

- autenticação institucional, com aviso de privacidade e proteção de dados
  (LGPD) na tela de acesso;
- redefinição de senha com fluxo controlado;
- busca global por equipamentos e modelos, de qualquer tela, com destaque do
  termo encontrado;
- filtro de "Visualização" por local, que restringe todos os painéis ao escopo
  escolhido;
- notificações com pendências administrativas e solicitações de criação de
  usuário, com aceite ou recusa na própria lista;
- relato de problemas pelo próprio usuário, com limite de envios para evitar
  excesso;
- tema claro e escuro, com preferência salva por usuário;
- modo compacto de visualização para telas menores.

## Dashboard

- visão consolidada de equipamentos, usuários, chamados, pendências e
  transferências;
- distribuição do inventário por tipo de equipamento, agrupada por família;
- análise de chamados por faixa de tempo sem atualização;
- Central Operacional com atalhos para as ações mais frequentes;
- painéis editáveis, com disposição ajustável pelo usuário;
- filtro de visualização conforme escopo autorizado.

## Inventário

- cadastro e consulta de ativos de TI, em duas etapas, com resumo em tempo real;
- classificação por tipo e modelo, e foto do modelo;
- procedência do equipamento: adquirido, cedido, alugado ou externo, com as
  cores e ícones correspondentes;
- vínculo com local, setor, pessoa responsável ou box/guichê;
- estados operacionais como em uso, manutenção, com defeito, reserva e
  desativado, com indicadores por estado;
- identificação, serial, endereço de rede, sistema operacional e demais
  especificações técnicas por tipo;
- campo de posição ou função do ativo;
- última alteração com o nome de quem a fez;
- ficha do ativo com movimentação atual, devolução em um clique e histórico
  completo do equipamento;
- histórico de suprimentos de impressoras, com ciclo médio e previsão da
  próxima troca;
- componentes instalados e histórico de componentes;
- filtros, pesquisa em várias colunas, paginação e atualização das listagens.

## Suporte Técnico

- abertura e acompanhamento de chamados, em ficha de consulta com linha de
  atualizações;
- prioridade, situação e responsável atual, com visões de chamados próprios,
  sem responsável e enviados à empresa;
- atendimento interno ou encaminhamento formal a empresa contratada ou órgão
  parceiro, com bloqueio dos dados principais após o envio;
- registro de conclusão, solução aplicada e justificativa de atraso;
- catálogo unificado de defeitos por tipo de equipamento;
- indicadores de chamados em aberto, em andamento, atrasados, em espera e
  concluídos.

## Movimentações

- empréstimo, cedência, posse, transferência (realocação interna ou externa),
  manutenção externa, recebimento e devolução;
- fluxo em tela única, com origem preenchida pelo sistema, destino por local,
  setor e pessoa e resumo prévio do registro;
- ida e volta de empresa contratada registradas como duas movimentações ligadas
  ao mesmo chamado;
- acompanhamento de prazos, atrasos e pendências por situação;
- numeração e documento formais por movimentação;
- rastreamento do percurso completo de um equipamento por busca;
- agrupamento de remessas e exportação ou impressão direta da tabela;
- bloqueios e confirmações para preservar a coerência de vínculos operacionais.

## Remessas

- envio ou recebimento de um lote de ativos e/ou material entre unidades numa
  única operação;
- origem, destino e estoque de destino explícitos por item;
- numeração e documento próprios;
- registro de auditoria consolidado em um único evento;
- repetição de uma remessa com os mesmos itens.

## Aster Estoque

- cadastro e consulta de material de consumo e de componentes, por almoxarifado
  e por estoque técnico;
- classificação do item por natureza operacional: reutilizável, consumo
  permanente ou consumo cíclico, com unidade de quantificação;
- alertas de reposição, saldo baixo, itens sem movimentação e sem estoque;
- entradas, saídas e baixas, com origem, destino (pessoa, setor e unidade, ou o
  equipamento que recebeu o item) e responsável;
- troca de suprimento e instalação de componente diretamente na ficha do ativo;
- contagem física do estoque com conferentes, registro no histórico e documento;
- catálogo de materiais compartilhado entre almoxarifados;
- módulo opcional por instalação, integrado ao restante do sistema.

## Documentos formais

- movimentação de ativo, termo de responsabilidade, envio para manutenção,
  ativos sob responsabilidade, contagem de estoque e remessa;
- numeração única por ano, com sigla do tipo de documento;
- pré-visualização em PDF do próprio documento, antes de gerar;
- geração apenas quando faz sentido para o tipo de movimentação.

## Estrutura Institucional

- painel de cadastros em quatro áreas: Organização Institucional (locais,
  setores, pessoas e usuários), Catálogo Técnico (tipos, modelos e estoque
  técnico), Entidades Externas (empresas contratadas e órgãos parceiros, com
  suas pessoas e usuários vinculados) e Estoque;
- cada pessoa com setor, unidade, cargo, vínculo (interno, terceirizado,
  temporário, estagiário ou cedido) e situação;
- relacionamento entre pessoa e conta de acesso;
- box e guichê de atendimento por setor;
- ativação e inativação controladas.

## Reserva e Armazenamento

- estoque técnico associado a local e setor;
- contagem de ativos guardados e reserva automática em remessas e
  transferências;
- escolha de destino de estoque em devoluções;
- bloqueios para preservar vínculos operacionais.

## Usuários e Permissões

- administração de contas, perfis e níveis de acesso, agrupados por área de
  responsabilidade;
- escopo global ou local;
- situação da conta: ativa, pendente, bloqueada ou desativada;
- promoção de pessoa a usuário e aprovação de solicitações;
- fluxo de redefinição administrativa de senha;
- controle de acesso por recurso e histórico de acessos e sessões.

## Histórico, auditoria e atividade

- trilha de ações relevantes, em linguagem operacional, por categoria: acessos,
  sistema, chamados, movimentações e inventário;
- consulta geral ou contextual, por unidade;
- linha do tempo de cada ativo;
- histórico das solicitações de usuário;
- resumo de atividades do próprio usuário.

## Análise Operacional

- conformidade operacional e distribuição de pendências por gravidade;
- tendência de chamados por período (hoje, semana, mês, ano);
- pendências que exigem atenção;
- concentração operacional: unidade mais sobrecarregada, técnico mais acionado,
  modelo com mais falhas e taxa de resolução, com rankings completos;
- atualização parcial das visualizações.

## Exportações

- relatórios e documentos para usuários autorizados, em Excel e PDF;
- pré-visualização, período e busca de texto em todas as colunas;
- relatórios de inventário, movimentações, termos, métricas por modelo,
  chamados por setor, estoque, remessas, consumo por setor e ciclo de troca por
  ativo, além de cadastros institucionais;
- exportações que dependem de um módulo ausente ficam visíveis e bloqueadas;
- aplicação de perfil e escopo ao conteúdo exportado e acesso protegido aos
  arquivos relacionados.

## Privacidade e proteção de dados

- aviso de privacidade na tela de acesso;
- política de retenção e anonimização de dados pessoais e de acesso;
- minimização: CPF e data de nascimento deixaram de ser coletados;
- cópias de segurança com acesso restrito;
- procedimento de resposta a incidentes.

## Não apresentado como funcionalidade atual

Presets persistentes de análise e uma central de análise operacional
configurável pelo próprio usuário permanecem pendentes. Não são apresentados
como recursos disponíveis.
