13 – Bugtracking: Criar e Gerenciar Defeitos
🎯 Objetivo
Garantir a qualidade e confiabilidade do sistema.

Diminuir o número de defeitos.

Aumentar a satisfação do cliente.

Garantir rastreio entre tarefas e bugs.

🧩 Conceitos-chave
Erro: Ação humana incorreta.
Exemplo: não compreender corretamente a documentação.

Falha: Função não realiza a ação desejada.
Exemplo: função de login não autentica.

Defeito: Problema na lógica ou no processo.
Exemplos:

Erro no código: função de senha não valida padrões definidos.

Erro no processo: protótipo não feito na fase correta, gerando desenvolvimento incorreto.

🗂 Como categorizar
Por time responsável: associar o bug ao time “dono” do defeito.

Por causa raiz: identificar o ponto do problema (protótipo, documentação, entendimento técnico, inviabilidade técnica, ambiente, recursos).

Técnica conhecida como Diagrama de Ishikawa (Espinha de peixe).

Por frente responsável: backend, frontend, integração etc.

🔄 Como gerenciar
Filtrar por categorias (time, causa raiz, frente).

Usar controle por versão para saber quantos defeitos estão abertos antes do deploy.

📝 Como abrir um bug
Título claro e enxuto: descreva o defeito sem precisar abrir a descrição.
Exemplos:

Erro ao realizar login

Erro na mutation logarUsuário

Descrição: passo a passo para reproduzir o defeito.

Utilize Gherkin se disponível.

Use o MAS para indicar o contraponto do resultado esperado:

gherkin
Copiar
Editar
Então o login deve ser realizado
MAS observou-se um erro
E o login não foi realizado
Evidências: prints, vídeos, desenhos ou narração da execução.

Severidade: informe o impacto (vide níveis abaixo).

Rastreabilidade: vincular:

Tarefa testada.

Execução de teste.

Plano de teste.

⏫ Como priorizar
Bugs são priorizados pelo grau de severidade, ou seja, o quanto impactam a usabilidade:

Severidade	Descrição	Exemplos
Crítico	Impede uso total ou de função essencial.	Não conseguir logar; e-commerce não finaliza pedido.
Alto	Não bloqueia, mas afeta o uso.	Menu não seleciona; mensagem de erro não exibida.
Médio	Sem bloqueio ou alto impacto, funções secundárias.	Filtros; buscas.
Baixo/Estético	Apenas detalhes visuais sem impacto funcional.	Alinhamento; cores; resolução de imagem.
