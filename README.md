# Checklist_Auditoria

Repositório desenvolvido para apoiar a realização de **Checklist de Auditoria de Acessibilidade** em páginas HTML5 e CSS3, com foco em avaliação prática de interfaces web utilizando o **Google Lighthouse** no navegador Chrome.

## Objetivo

Este projeto tem como finalidade servir de base para auditorias de acessibilidade em laboratório prático da disciplina **Engenharia de Interfaces**, permitindo validar critérios essenciais de usabilidade, semântica e acessibilidade em aplicações web.

## Contexto Acadêmico

Atividade prática voltada para inspeção criteriosa de uma interface web, com análise dos principais aspectos de acessibilidade, incluindo:

- Estrutura semântica do documento
- Navegação por teclado
- Associação entre `label` e campos de formulário
- Validação de formulários
- Conteúdo multimídia
- Responsividade
- Contraste e legibilidade

## Como executar o projeto

### Pré-requisitos

- [Visual Studio Code](https://code.visualstudio.com/)
- Extensão **Live Server**
- Navegador **Google Chrome**

### Passos para execução

1. Baixe ou clone este repositório na sua máquina.
2. Abra a pasta do projeto no **VS Code**.
3. Instale e ative a extensão **Live Server**.
4. Execute o projeto com o Live Server.
5. Abra a aplicação no navegador **Chrome**.
6. Utilize a ferramenta **Lighthouse** para realizar a auditoria de acessibilidade.

## Como realizar a auditoria

A auditoria deve ser conduzida com bastante rigor, observando os critérios descritos no checklist. Após a análise:

1. Preencha o checklist com os campos:
   - **OK**
   - **Problema Identificado**
   - **Observações**
2. Gere ou capture o **print da auditoria Lighthouse**.
3. Envie o print juntamente com o checklist preenchido para a responsável pela implementação do código.

## Estrutura de avaliação

### 1. Estrutura Semântica do Documento
Verifica se a página utiliza corretamente elementos semânticos como:

- `<main>`
- `<section>`
- `<article>`
- `<header>`
- `<nav>`
- `<footer>`
- Hierarquia correta de títulos (`h1`, `h2`, `h3`)

### 2. Navegação por Teclado
Analisa se:

- Todos os campos podem ser acessados com `TAB`
- A ordem do foco acompanha a ordem visual
- Existe foco visível
- Botões e controles funcionam com `ENTER` ou `SPACE`

### 3. Associação entre Label e Campo
Valida se:

- Todos os inputs possuem `<label>`
- `for` e `id` estão corretamente associados
- O clique no label direciona corretamente para o campo

### 4. Validação de Formulários
Confirma se:

- Campos obrigatórios usam `required`
- Campos específicos usam `pattern`
- As mensagens de erro são compreensíveis
- O envio é bloqueado quando houver dados inválidos

### 5. Mídia e Conteúdo Multimídia
Verifica se:

- O elemento `<video>` possui `controls`
- Existem múltiplos formatos de vídeo
- Há legendas com `<track>`
- Existe conteúdo alternativo em caso de não compatibilidade

### 6. Responsividade
Avalia se:

- Os campos se adaptam a telas menores
- Não há rolagem horizontal no mobile
- O texto continua legível
- Labels e inputs reorganizam corretamente em telas pequenas

### 7. Contraste e Legibilidade
Observa se:

- O contraste entre texto e fundo é adequado
- Links e botões são distinguíveis visualmente
- O tamanho da fonte favorece a leitura
- Elementos interativos são fáceis de identificar

## Ferramentas utilizadas

- **HTML5**
- **CSS3**
- **Visual Studio Code**
- **Live Server**
- **Google Chrome Lighthouse**
