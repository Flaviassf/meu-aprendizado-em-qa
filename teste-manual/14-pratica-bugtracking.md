📘 14 – Prática: Bugtracking
🎯 Objetivo
Aplicar na prática o processo de registro e gerenciamento de defeitos usando o template de Plano de Teste como base para vinculação.

🛠 Passos da prática
1. Identificar o defeito
Execute os casos de teste definidos no Plano de Teste.

Ao encontrar um comportamento diferente do esperado, classifique como BUG.

2. Registrar no template
No Excel de Plano de Teste:

Preencha:

Título do defeito (resumo claro).

Descrição (passos para reproduzir).

Resultado obtido.

Resultado esperado.

Evidências (print, vídeo, logs).

Adicione Severidade (impacto).

Adicione Prioridade (urgência).

3. Vincular
Relacione o defeito à Execução de Teste e ao Plano de Teste.

Use a coluna de ID do Caso de Teste para rastreabilidade.

4. Acompanhar
Atualize o status conforme o defeito for corrigido ou reaberto.

Use filtros do Excel para:

Ver bugs por severidade.

Ver bugs por status.

Identificar bugs críticos pendentes antes do deploy.

📌 Exemplo de registro (resumo)
ID	Caso de Teste	Título do Defeito	Severidade	Prioridade	Status
001	CT-LOGIN-01	Erro ao logar com senha válida	Crítico	Alta	Aberto

💡 Boas práticas na prática
Registre o defeito assim que ele for identificado.

Mantenha um defeito por registro.

Sempre valide a reprodução antes de registrar.

Use nomes de arquivo claros para evidências (ex.: login_bug_2025-08-06.png).

