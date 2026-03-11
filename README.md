# GABRIELRAMOS-Aula5-pi
# **Repositório:** 
É o "QG" do projeto. O baú onde tudo fica guardado, com o histórico de quem mexeu no quê desde o primeiro dia,
é um local de armazenamento na nuvem (remoto) usado para guardar códigos-fonte, arquivos e o histórico de revisões de um projeto.
Como criar no GitHub:
No canto superior direito, clique em + e depois em New repository (Novo repositório).
Dê um nome ao repositório (ex: meu-projeto).
Adicione uma descrição opcional.
Escolha entre Público ou Privado.
Inicialize com um arquivo README (recomendado para descrição).
https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp
https://docs.github.com/assets/cb-89988/mw-1440/images/help/repository/create-repository-name.webp
https://terminalroot.com.br/assets/img/cursos/git.jpg
# **Clone do repositório:** 
É o ato de baixar o projeto. Você tira uma cópia idêntica da nuvem e coloca no seu computador para poder trabalhar,
significa criar uma cópia local exata de um projeto remoto no seu computador, incluindo todo o histórico de versões.Isso permite trabalhar no código, realizar commits e sincronizar alterações com o repositório original.Obtenha a URL: No GitHub, vá ao repositório desejado, clique no botão "<> Code" e copie a URL (HTTPS ou SSH).
Abra o terminal: Abra o Git Bash, terminal ou prompt de comando e navegue até a pasta onde deseja salvar o projeto.
Execute o comando: Digite git clone seguido da URL copiada.
Acesse o projeto: Entre na nova pasta criada com cd nome-do-repositorio. 
https://docs.github.com/assets/cb-13128/mw-1440/images/help/repository/code-button.webp
https://docs.github.com/assets/cb-60499/mw-1440/images/help/repository/https-url-clone-cli.webp
# **Branch:**
É uma "linha do tempo alternativa". Serve para você testar ideias novas sem o risco de quebrar a versão principal que já está funcionando. no Git é uma linha de desenvolvimento separada, permitindo trabalhar em novas funcionalidades ou correções sem alterar o código principal (main ou master). Ele atua como um "snapshot" isolado do seu projeto. Como Criar uma Branch no GitHub:Acesse o GitHub e vá para a página principal do seu repositório.
No canto superior esquerdo da lista de arquivos, clique no menu suspenso que diz main (ou o nome do branch atual).
Digite o nome da sua nova branch no campo de texto,
Clique na opção Create branch: [nome] que aparecerá abaixo.
https://docs.github.com/assets/cb-2058/mw-1440/images/help/branches/pr-retargeting-diagram1.webp
https://docs.github.com/assets/cb-2581/mw-1440/images/help/branches/pr-retargeting-diagram2.webp
# **Commits:**
É o "check-point" do videogame. Você salva um estado do seu código e coloca uma etiqueta explicando o que mudou (ex: "ajustei o botão de login"). é um "instantâneo" (snapshot) do seu código no Git, registrando alterações em arquivos com uma mensagem explicativa.
Como criar um Commit no GitHub (via Terminal):
Adicionar alterações (Staging): Antes de comitar, indique quais arquivos alterados serão incluídos.
Criar o commit: Salve as alterações localmente com uma mensagem descritiva.
Enviar para o GitHub (Push): Envie o commit da sua máquina para o repositório remoto.
https://docs.github.com/assets/cb-48469/mw-1440/images/help/commits/commits-page.webp
https://docs.github.com/assets/cb-17733/mw-1440/images/help/commits/commit-message-link.webp
https://docs.github.com/assets/cb-15839/mw-1440/images/help/commits/commit-branch-indicator.webp
https://docs.github.com/assets/cb-17593/mw-1440/images/help/commits/commit-tag-label.webp
# **Envio das alterações (push):**
É o upload. Você pega os seus commits locais e sobe para o servidor, para que o resto do time consiga ver.
é o comando Git utilizado para enviar os commits realizados no seu computador (repositório local) para um repositório remoto no GitHub.
Inicialize o Git na sua pasta local (se ainda não fez):
Adicione o repositório remoto do GitHub
Adicione e comite suas alterações localmente
Faça o Push para o GitHub.
https://docs.github.com/assets/cb-17787/mw-1440/images/help/desktop/push-to-origin.webp
https://docs.github.com/assets/cb-49098/mw-1440/images/help/desktop/mac-preview-pull-request.webp
# **Atualização do repositório local (pull):**
É o download das novidades. Você verifica se alguém da equipe enviou algo novo e traz essas melhorias para o seu PC.
Faça Fork/Clone: Clone o repositório ou faça um fork para sua conta.
Crie um Branch: Trabalhe em uma nova ramificação (git checkout -b minha-feature).
Commit e Push: Faça as alterações, git add, git commit e envie com git push origin minha-feature.
Abra o PR: No GitHub, clique no botão "Compare & pull request" que aparece.
Detalhes: Adicione um título claro e descrição das alterações.
Criar: Clique em "Create pull request" para enviar para revisão.
https://docs.github.com/assets/cb-87213/mw-1440/images/help/pull_requests/pull-request-review-edit-branch.webp
https://docs.github.com/assets/cb-29825/mw-1440/images/help/pull_requests/branch-dropdown.webp
https://docs.github.com/assets/cb-34097/mw-1440/images/help/pull_requests/pull-request-compare-pull-request.webp
# **Criação de Issues**
É o "mural de avisos" ou a lista de tarefas. Onde se discute bugs, sugestões e o que precisa ser feito a seguir.
Como Criar uma Issue no GitHub
Acesse o Repositório: Vá para a página principal do projeto no GitHub.
Abra a aba Issues: Clique na aba Issues, localizada logo abaixo do nome do repositório.
Nova Issue: Clique no botão verde New issue (Novo problema).
Título e Descrição:
Title: Digite um título claro e conciso.
Body: Descreva o problema, o que deve ser feito ou os passos para reproduzir o erro. Você pode usar formatação Markdown, inserir código e anexar imagens.
Adicionar Metadados (Opcional): Na barra lateral direita, você pode definir:
Assignees: Atribuir a pessoa responsável.
Labels: Adicionar etiquetas (ex: bug, documentation, enhancement).
Projects/Milestones: Associar a um projeto maior ou meta de tempo.
Enviar: Clique em Submit new issue
https://docs.github.com/assets/cb-51267/mw-1440/images/help/repository/repo-tabs-issues-global-nav-update.webp
https://docs.github.com/assets/cb-57633/mw-1440/images/help/pull_requests/kebab-in-pull-request-review-comment.webp
https://docs.github.com/assets/cb-51242/mw-1440/images/help/discussions/repository-discussions-tab-global-nav-update.webp
https://docs.github.com/assets/cb-33946/mw-1440/images/help/discussions/create-issue-from-discussion.webp
# **Organização com Milestone**
É o "objetivo da fase". Um marco que ajuda a entender se o projeto está chegando perto de uma grande entrega ou versão (ex: v1.0).
https://docs.github.com/assets/cb-51787/mw-1440/images/help/repository/repo-settings-issues-pull-requests-global-nav-update.webp
https://docs.github.com/assets/cb-49741/mw-1440/images/help/issues/issues-milestone-button.webp
https://docs.github.com/assets/cb-34637/mw-1440/images/help/repository/edit-milestone.webp
https://docs.github.com/assets/cb-34708/mw-1440/images/help/repository/delete-milestone.webp
# **Gerenciamento com Project**
É o quadro (tipo Kanban). Serve para ver o fluxo de trabalho: o que está pendente, o que está sendo feito e o que já terminou.
Como Criar um Projeto (Project) no GitHub:
Acesse o GitHub: Vá para a sua página de perfil ou da organização.
Menu Projects: Clique na aba Projects no menu superior.
Novo Projeto: Clique no botão New project (Novo projeto).
Escolha o Modelo: Selecione um modelo como "Tabela" (Table) ou "Quadro" (Board/Kanban) para iniciar.
Nomeie e Crie: Digite um nome para o projeto e clique em Create project.
Adicionar Itens: Clique em + para adicionar issues ou pull requests existentes, ou crie rascunhos de tarefas.
https://docs.github.com/assets/cb-4169/mw-1440/images/help/projects-v2/tab-projects.webp
https://docs.github.com/assets/cb-13593/mw-1440/images/help/profile/profile-button-avatar-menu-global-nav-update.webp
https://docs.github.com/assets/cb-4169/mw-1440/images/help/projects-v2/tab-projects.webp
# **Abertura de Pull Request**
É o "pedido de revisão". Você avisa aos colegas: "Terminei minha parte na minha branch, podem dar uma olhada antes de eu juntar com o projeto principal?".
Como criar um Pull Request no GitHub:
Faça Push da sua Branch: Suba sua branch modificada para o repositório remoto: git push origin minha-feature.
Abra o GitHub: Vá até o repositório no GitHub.
Compare e Solicite: O GitHub geralmente exibe um banner amarelo sugerindo a criação; clique no botão "Compare & pull request".
Configure a PR:
Selecione o branch base (ex: main) e o branch de comparação (minha-feature).
Adicione um Título claro e uma Descrição detalhando o que foi feito.
Finalize: Clique em "Create pull request". 
# **Realização de Merge**
 É o aperto de mão final. É quando as alterações aprovadas saem da branch de teste e se fundem oficialmente ao código principal.
Criar a Branch: Desenvolva suas alterações em uma branch separada, não na main.
Fazer o Push: Envie a branch para o repositório no GitHub (git push origin sua-branch).
Abrir o Pull Request (PR):
No GitHub, vá para a aba "Pull requests" do seu repositório.
Clique no botão verde "New pull request".
Selecione a branch que você alterou para comparar com a main.
Clique em "Create pull request", adicione uma descrição e confirme.
Realizar o Merge:
Após a revisão, clique no botão "Merge pull request".
Clique em "Confirm merge".
Excluir a Branch (Opcional): Após o merge, o GitHub oferece a opção de excluir a branch original que foi mesclada
https://docs.github.com/assets/cb-5402/mw-1440/images/help/pull_requests/standard-merge-commit-diagram.webp
https://docs.github.com/assets/cb-5742/mw-1440/images/help/pull_requests/commit-squashing-diagram.webp




