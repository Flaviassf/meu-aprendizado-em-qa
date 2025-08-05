Aula 09 – Mapeamento de Funcionalidades com Storytelling (TodoMVC)

1️⃣ Contexto da Aula
Objetivo: Aprender a analisar um sistema já existente, documentar funcionalidades e criar User Stories claras usando a técnica de storytelling.

Sistema analisado: Projeto open source TodoMVC (versão React).

Ferramenta de apoio: Miro para organização visual.

Foco: Mapeamento de funcionalidades, definição de regras de negócio e critérios de aceite.

Desafio – Análise e Documentação de Funcionalidades
Este documento apresenta a análise das três funcionalidades propostas no desafio, incluindo User Stories, Regras de Negócio e Critérios de Aceite para cada uma.

1. Conclusão de itens de forma unitária
User Story

Como usuário, quero concluir um item individualmente para que eu possa organizar minha lista de forma gradual.

Regras de Negócio

Apenas itens pendentes podem ser marcados como concluídos.

Ao concluir um item, o sistema deve registrar a data/hora da ação.

Itens concluídos devem ter destaque visual (ex.: texto riscado ou cor diferente).

Deve ser possível reverter a conclusão (voltar para pendente).

Critérios de Aceite

Dado que existe um item pendente
Quando o usuário clicar no botão/conteúdo de “Concluir”
Então o sistema deve alterar o status para “Concluído” e aplicar a formatação visual.

Dado que existe um item concluído
Quando o usuário clicar para reverter
Então o sistema deve voltar o status para “Pendente”.

2. Conclusão de itens em lote
User Story

Como usuário, quero concluir vários itens ao mesmo tempo para economizar tempo na organização da lista.

Regras de Negócio

Apenas itens pendentes podem ser selecionados para conclusão.

O sistema deve permitir seleção múltipla de itens.

Ao confirmar a ação, todos os itens selecionados devem ser concluídos simultaneamente.

Deve haver destaque visual para os itens selecionados antes da ação final.

Critérios de Aceite

Dado que existem múltiplos itens pendentes
Quando o usuário selecionar dois ou mais itens e clicar em “Concluir”
Então todos devem ter o status alterado para “Concluído” e a formatação aplicada.

Dado que o usuário não selecionou nenhum item
Quando tentar concluir
Então o sistema deve exibir uma mensagem informando que é necessário selecionar pelo menos um item.

3. Limpar todos os itens concluídos
User Story

Como usuário, quero remover todos os itens concluídos de uma só vez para manter minha lista limpa e organizada.

Regras de Negócio

Apenas itens com status “Concluído” podem ser removidos nessa ação.

A remoção é permanente (não há opção de desfazer).

O sistema deve solicitar confirmação antes da exclusão.

Caso não existam itens concluídos, o botão/opção de limpeza deve estar desativado.

Critérios de Aceite

Dado que existem itens concluídos
Quando o usuário clicar em “Limpar concluídos” e confirmar
Então todos devem ser removidos da lista.

Dado que não existem itens concluídos
Quando o usuário acessar a opção
Então o sistema deve manter o botão desativado ou exibir mensagem “Nenhum item concluído para remover”.

📌 Observações finais
O formato User Story + Regras de Negócio + Critérios de Aceite segue as boas práticas de análise ágil.


