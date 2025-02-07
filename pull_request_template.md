name: Bug / Nova Feature
description: Template para reportar bugs ou solicitar novas funcionalidades.
title: "[BUG/FEATURE] Descreva o problema ou funcionalidade"
labels: []
assignees: []

body:
  - type: markdown
    attributes:
      value: "## 🛠️ Alteração da lib dos blocks"

  - type: textarea
    id: descricao
    attributes:
      label: "📝 Descrição"
      description: "Descreva a tarefa ou mudança necessária."
      placeholder: "Exemplo: Precisamos alterar a biblioteca X para Y..."
    validations:
      required: true

  - type: textarea
    id: problemas
    attributes:
      label: "🐛 Problemas Encontrados"
      description: "Se aplicável, descreva o problema que motivou essa alteração."
      placeholder: "Exemplo: A biblioteca X apresentava falhas na compatibilidade..."
    validations:
      required: false

  - type: textarea
    id: testes
    attributes:
      label: "🧪 Observação para Testes"
      description: "Alguma observação ou consideração especial para os testes?"
      placeholder: "Exemplo: Testar o comportamento com múltiplos usuários..."
    validations:
      required: false

  - type: checkboxes
    id: checklist
    attributes:
      label: "✅ Checklist"
      options:
        - label: "Testes realizados"
        - label: "Remoção de código desnecessário"
        - label: "Refatoração concluída"
        - label: "Fluxo do processo testado e aprovado"
