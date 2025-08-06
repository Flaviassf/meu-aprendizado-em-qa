📘 11 – Plano de Teste
✅ O que aprendi
Plano de Teste é o documento que planeja e organiza as validações a serem realizadas em um sistema.

Pode ser usado para:

Novas implementações.

Testes regressivos em sistemas já implantados.

Serve como mapa das validações e fornece rastreabilidade dos testes.

🎯 Objetivos do Plano de Teste
Mapear e monitorar riscos nas implementações.

Ter marcos bem definidos no projeto.

Definir fases de entrega, andamento dos testes e cronograma.

Gerenciar a alocação de recursos.

🛠️ Composição do Plano de Teste
Introdução – definições, abreviações, referências, escopo, objetivos.

Requisitos que serão testados – ideal ter uma suíte para cada requisito.

Estratégia de teste – tipos de teste, ferramentas e abordagem.

Recursos – hardware, software, ambientes e equipe.

Cronograma – alinhado com os marcos do projeto.

✍️ Formas de escrita de testes
Textual: descrição livre, sem padronização.

Gherkin: escrita universal, reutilizável em automação.

Três níveis macro:

Cenário: alto nível, uma linha por teste.

Caso de teste: nível intermediário, mais detalhes, pouco retrabalho.

Script de teste: detalhado passo a passo, indicado para iniciantes.

📊 Exemplo de escrita
Cenário:
Realizar login na aplicação.

Caso de teste:
gherkin
Copiar
Editar
DADO que me encontro no login
QUANDO logo através de ...
ENTÃO sou logada na aplicação
Script de teste:
gherkin
Copiar
Editar
DADO que me encontro na tela de login
E adiciono o usuário no campo de usuário
E adiciono a senha no campo de senha
QUANDO clico em logar
ENTÃO o login é realizado
E sou redirecionada para a tela de home
📌 Checklist para criar um Plano de Teste
Ter a suíte de teste relativa à funcionalidade.

Escrever cenário, caso ou script de teste.

Definir massa de teste.

Descrever ambiente de teste.

Definir prioridade e severidade.

Executar o teste.

Anexar evidência.

Abrir/vincular defeito, se houver.

Finalizar execução quando não houver mais defeitos.

🚦 Prioridade x Severidade
Prioridade: urgência de execução (Altíssima, Alta, Média, Baixa, Baixíssima) → definida pela área de negócio.

Severidade: impacto no sistema (Alta, Média, Baixa) → definida pelo QA com visão do produto.

