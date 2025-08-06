10 – Gherkin: Do Básico ao Avançado
✅ O que aprendi:
Gherkin é uma linguagem universal para escrever cenários de teste, usada tanto em testes manuais quanto automatizados.

É independente de linguagem de programação, mas muito utilizada dentro da metodologia BDD (Behavior Driven Development).

Traz clareza, padronização e reuso para os testes.

🔑 Keywords básicas:
DADO (Given) → Define o contexto inicial.

QUANDO (When) → Descreve a ação principal.

ENTÃO (Then) → Define o resultado esperado.

E (And) → Agrupa ações ou condições adicionais.

MAS (But) → Acrescenta um contraponto ou resultado negativo esperado.

Exemplo simples:

gherkin
Copiar
Editar
DADO que sou aluno da plataforma Qualiters Club
QUANDO adiciono meus dados de acesso corretos
ENTÃO o login é realizado na plataforma
📈 Keywords intermediárias:
Funcionalidade (Feature) → Define o objetivo geral a ser testado.

Cenário (Scenario) → Agrupa os passos de um teste específico.

Contexto (Background) → Passos comuns a vários cenários.

Esquema do Cenário (Scenario Outline) → Permite reutilizar o mesmo cenário com diferentes massas de teste.

Exemplo com Contexto:

gherkin
Copiar
Editar
Funcionalidade: Login no sistema
  Contexto:
    DADO que estou na página de login

  Cenário: Login com credenciais corretas
    QUANDO insiro usuário válido e senha correta
    ENTÃO o acesso é permitido
⚙️ Keywords avançadas e recursos adicionais:
Strings ("") → Para textos.

Tabelas (| |) → Para dados estruturados.

Tags (@) → Para identificar ou filtrar testes.

Comentários (#) → Ignorados pelo interpretador.

Asterisco (*) → Step coringa que pode assumir qualquer tipo de step.

💡 Benefícios do uso de Gherkin:
Facilita a comunicação entre times técnicos e não técnicos.

Evita ambiguidades na documentação de testes.

Permite reuso de cenários na automação.

Cria documentação viva que acompanha o produto.

🧠 Exemplo prático de cenário com Esquema:
gherkin
Copiar
Editar
Funcionalidade: Login com múltiplos perfis

  Esquema do Cenário: Validar acesso por perfil de usuário
    DADO que estou na página de login
    QUANDO insiro <usuario> e <senha>
    ENTÃO o acesso é permitido

  Exemplos:
    | usuario   | senha      |
    | admin     | 123456     |
    | suporte   | abcdef     |
    | usuario   | senhauser  |
