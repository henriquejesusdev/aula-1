# Boas Práticas para Git e GitHub

Este repositório serve como um guia de referência para adotar boas práticas no uso de Git e GitHub, promovendo um fluxo de trabalho eficiente, organizado e colaborativo.

## Sobre o Guia

Este documento descreve três práticas essenciais para trabalhar com Git e GitHub, ajudando a manter o controle de versão claro e facilitar a colaboração em projetos. As práticas abordadas são:

1. Escrever mensagens de commit claras e descritivas.
2. Usar branches para organizar o fluxo de trabalho.
3. Manter o repositório organizado e bem documentado.

## Boas Práticas

### 1. Mensagens de Commit Claras e Descritivas

- **O que fazer**: Escreva mensagens de commit que expliquem o propósito da mudança e o contexto. Por exemplo: \`Adicionar validação de email no formulário de cadastro\` em vez de apenas \`Correção\`.
- **Por quê**: Facilita o entendimento do histórico do projeto, especialmente em equipes.
- **Dica**: Use verbos no infinitivo (ex.: "Corrigir", "Implementar", "Atualizar") e mantenha mensagens curtas, mas informativas.

### 2. Uso de Branches para Fluxo de Trabalho

- **O que fazer**: Crie branches específicas para cada funcionalidade ou correção (ex.: \`feature/login\`, \`bugfix/erro-api\`). Use pull requests (PRs) no GitHub para revisar e mesclar mudanças.
- **Por quê**: Evita conflitos, organiza o desenvolvimento e permite revisões de código antes de integrar ao branch principal (\`main\` ou \`master\`).
- **Dica**: Nomeie branches de forma clara e delete-os após a mesclagem para manter o repositório limpo.

### 3. Repositório Organizado e Documentado

- **O que fazer**: Inclua um \`README.md\` com instruções claras sobre o projeto. Use um arquivo \`.gitignore\` para evitar versionar arquivos desnecessários (ex.: pastas de dependências, arquivos temporários). Faça commits frequentes, mas lógicos.
- **Por quê**: Um repositório bem documentado facilita a colaboração e a manutenção. Commits menores ajudam a rastrear mudanças e reverter erros, se necessário.
- **Dica**: Atualize o \`README\` regularmente e descreva como configurar e contribuir para o projeto.

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch para sua contribuição (\`git checkout -b sua-contribuicao\`).
3. Faça suas alterações e commit com mensagens descritivas.
4. Envie um pull request explicando suas mudanças.

## Exemplo de Uso

\`\`\`bash

# Criar uma nova branch

git checkout -b feature/nova-funcionalidade

# Adicionar mudanças

git add .

# Commit com mensagem descritiva

git commit -m "Adicionar funcionalidade de login com autenticação"

# Enviar para o GitHub

git push origin feature/nova-funcionalidade
\`\`\`

Depois, abra um pull request no GitHub para revisão.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
EOF
