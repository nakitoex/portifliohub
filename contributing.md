# Guia de Contribuição e Políticas de Segurança

Agradeceço o interesse em colaborar com o **PortfolioHUB**. Para manter a integridade, a segurança e a organização do projeto, estabeleci as seguintes políticas de segurança e práticas de colaboração. 

## 🛡️ Políticas de Segurança (Proteção da Branch Principal)
Para garantir a conformidade com as melhores práticas, este repositório possui regras estritas para a branch `main` (que reflete o ambiente de produção no GitHub Pages):

1. **Bloqueio de Commits Diretos:** Nenhum usuário, inclusive administradores, tem permissão para fazer *push* direto na branch `main`.
2. **Exigência de Pull Requests (PR):** Todo e qualquer novo código, correção de bug ou nova funcionalidade deve ser enviado por meio de um *Pull Request*.
3. **Revisão Obrigatória:** Os *Pull Requests* devem ser revisados antes de serem mesclados (*merged*) à branch principal.

## 🌿 Fluxo de Trabalho (Branching Model)
Se você for contribuir para este projeto, siga o padrão abaixo:

1. Certifique-se de estar na branch mais atualizada: `git pull origin main`
2. Crie uma branch a partir da `main` descrevendo o que você vai fazer:
   * Para novas funcionalidades: `git checkout -b feature/nome-da-funcionalidade`
   * Para correções: `git checkout -b fix/nome-da-correcao`
3. Faça suas alterações de código.
4. Envie a branch para o repositório remoto: `git push origin nome-da-sua-branch`
5. Abra um *Pull Request* no GitHub detalhando as mudanças realizadas.
Felipe esteve aqui
## 💻 Padrões de Código
* Mantenha a estrutura de **HTML semântico** estabelecida.
* Todo CSS deve manter as variáveis globais (ex: `--brand`, `--surface`) localizadas no root para consistência visual.
* O design deve ser mantido **100% responsivo**, garantindo o funcionamento em dispositivos móveis.
* Se estiver em dúvida sobre a melhor abordagem lógica ou semântica, utilize o **Google Gemini** para validar seu código antes de abrir o Pull Request, mantendo o alinhamento com a proposta original da implantação.

## 👥 Gestão de Usuários e Acesso
O controle de acesso é gerido pelas configurações de *Collaborators* do GitHub. Apenas membros autorizados possuem permissão de escrita (*Write*) para aprovar e mesclar Pull Requests na produção.
