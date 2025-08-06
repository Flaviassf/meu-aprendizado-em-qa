# 📘 14 – Prática: Bugtracking

## 🎯 Objetivo
Aplicar na prática o processo de **registro e gerenciamento de defeitos** usando planilhas ou ferramentas de bugtracking e vinculando-os ao Plano de Teste.

---

## 🛠 Passos da prática

### 1. Identificar o defeito
- Execute os casos de teste do Plano de Teste.
- Ao encontrar comportamento diferente do esperado, classifique como **BUG**.

### 2. Registrar
- Em ferramenta (ex.: Jira, Trello, Azure DevOps) ou no template Excel:
  - **Título** claro.
  - **Descrição** com passos para reproduzir.
  - **Resultado obtido**.
  - **Resultado esperado**.
  - **Evidências** (print, vídeo, logs).
  - **Severidade** (impacto).
  - **Prioridade** (urgência).

### 3. Vincular
- Relacione o bug ao **ID do Caso de Teste** no Plano de Teste.
- Vincule à execução de teste.

### 4. Acompanhar
- Atualize o status conforme progresso da correção.
- Reabra caso o problema persista.

---

## 📌 Exemplo
| ID  | Caso de Teste    | Título do Defeito                    | Severidade | Prioridade | Status |
|-----|------------------|--------------------------------------|------------|------------|--------|
| 001 | CT-LOGIN-01      | Erro ao logar com senha válida       | Crítico    | Alta       | Aberto |

---

## 💡 Boas práticas
- Um defeito por registro.
- Confirmar que o bug é **reproduzível** antes de registrar.
- Nome de arquivo de evidência claro (ex.: `login_bug_2025-08-06.png`).


