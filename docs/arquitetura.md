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
movimentações, estoque, estrutura, usuários, histórico e análise — mas
compartilham identidade, navegação, controle de acesso e contexto
organizacional. O Aster Estoque é um módulo próprio, opcional por instalação,
sobre o mesmo núcleo compartilhado.

## Fluxo conceitual

Uma ação iniciada na interface é validada segundo a sessão, o perfil, o escopo e
as regras do domínio. Somente depois dessas validações a informação operacional
é persistida. Eventos relevantes alimentam a trilha de auditoria e as visões
consolidadas.

## Dados e arquivos

A persistência relacional aceita SQLite, usado em desenvolvimento, ou
PostgreSQL, validado e aprovado para uso em produção. Documentos e imagens
associados ao sistema são tratados como recursos protegidos e seguem as mesmas
restrições de acesso do registro relacionado.

## Evolução arquitetural

A separação de um núcleo compartilhado para o ecossistema Aster, iniciada na
versão 1.01, está concluída: o núcleo hoje sustenta dois módulos reais e
independentes, o AsterTI e o Aster Estoque, este último opcional por
instalação. Extensões adicionais desse núcleo dependem de decisões
registradas no projeto privado.

## O que foi omitido

Este documento não divulga estrutura de pastas, rotas, modelos de dados,
consultas, formatos de payload, nomes de componentes internos ou procedimentos
de implantação.
