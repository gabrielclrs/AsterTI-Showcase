# Arquitetura

## Visão de alto nível

O AsterTI é uma aplicação web modular. A arquitetura pública pode ser entendida
em quatro responsabilidades:

1. **Experiência:** telas de operação, consulta, formulários e painéis;
2. **Aplicação:** coordenação dos casos de uso e das regras do ciclo de vida;
3. **Proteção e governança:** autenticação, autorização, escopo e auditoria;
4. **Persistência:** armazenamento relacional dos dados operacionais e
   referências a documentos protegidos.

## Organização por domínio

Os workspaces são separados por finalidade — inventário, suporte,
movimentações, estrutura, usuários, histórico e análise — mas compartilham
identidade, navegação, controle de acesso e contexto organizacional.

## Fluxo conceitual

Uma ação iniciada na interface é validada segundo a sessão, o perfil, o escopo e
as regras do domínio. Somente depois dessas validações a informação operacional
é persistida. Eventos relevantes alimentam a trilha de auditoria e as visões
consolidadas.

## Dados e arquivos

A versão atual utiliza persistência relacional em SQLite. Documentos e imagens
associados ao sistema são tratados como recursos protegidos e seguem as mesmas
restrições de acesso do registro relacionado.

## Evolução arquitetural

A versão 1.01 iniciou a separação progressiva de um núcleo compartilhado para o
ecossistema Aster. A fronteira ainda está em evolução e partes adicionais
dependem de decisões registradas no projeto privado.

## O que foi omitido

Este documento não divulga estrutura de pastas, rotas, modelos de dados,
consultas, formatos de payload, nomes de componentes internos ou procedimentos
de implantação.
