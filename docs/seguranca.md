# Segurança

## Princípios adotados

O AsterTI aplica segurança em camadas, considerando identidade, sessão, perfil,
escopo organizacional, recurso solicitado e registro de eventos.

## Controles confirmados

- autenticação com proteção de senha por algoritmo moderno de derivação;
- autorização por perfil e capacidade;
- aplicação do escopo no servidor;
- proteção contra requisições forjadas;
- limitação de tentativas em operações sensíveis;
- políticas de segurança para conteúdo entregue ao navegador;
- validação e restrição de arquivos;
- sessão com configurações reforçadas para produção;
- trilha de auditoria para eventos relevantes;
- redefinição de senha com fluxo controlado;
- bloqueio de contas e credenciais de demonstração no ambiente produtivo;
- aviso de privacidade e proteção de dados (LGPD) na tela de acesso;
- política de retenção e anonimização de dados pessoais e de acesso;
- minimização de dados: CPF e data de nascimento não são coletados;
- cópias de segurança com acesso restrito;
- procedimento de resposta a incidentes.

## Perfis

Administrador Global, Supervisor Local, Suporte Técnico e Auditor possuem
responsabilidades diferentes. A interface reflete as permissões, mas a decisão
final de acesso ocorre no servidor.

## Arquivos e documentos

O acesso a imagens, anexos, documentos e exportações considera o mesmo perfil e
escopo do recurso de origem. O simples conhecimento de uma referência não deve
conceder acesso.

## Auditoria

A trilha de histórico registra ações institucionais relevantes e pode ser
consultada conforme o nível de acesso. O conteúdo é apresentado em linguagem
operacional para apoiar investigação e prestação de contas.

## Limites da divulgação

Não são publicados parâmetros, segredos, valores de configuração, regras
detalhadas de detecção, endereços, infraestrutura ou procedimentos que aumentem
a superfície de ataque.

## Nota

Segurança é um processo contínuo. Esta descrição registra controles existentes,
mas não substitui auditoria independente, análise de risco nem política
institucional.
