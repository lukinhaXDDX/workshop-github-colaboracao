# Workshop TecnoMonte — Colaboração no GitHub

## Objetivo
Praticar o fluxo **Issue → Fork → Clone → Branch → Commit → Pull Request → Revisão → Integração**, em duplas, usando o GitHub Desktop.

## Pré-requisitos
- Conta GitHub ativa e e-mail confirmado.
- GitHub Desktop autenticado (Windows ou macOS).
- Editor de texto e internet.

## Atividade passo a passo
1. Forme uma dupla e escolha um arquivo livre em `participantes/` (não use `demo.md`). Cada pessoa deve escolher um arquivo diferente.
2. No repositório original, abra **Issues > New issue**. Crie uma issue com título `Adicionar apresentação ao arquivo participante-XX`, descrição e critérios de aceitação. Aplique as labels `exercício` e `boa primeira issue` se disponíveis.
3. Clique em **Fork > Create fork** para criar uma cópia em sua conta.
4. No **GitHub Desktop**, escolha **File > Clone repository** e clone **seu fork**, não o repositório original.
5. Em **Current Branch > New Branch**, crie `add-apresentacao-XX`.
6. Edite apenas `participantes/participante-XX.md`. Preencha título, nome ou apelido, seção **Sobre mim** (2–3 linhas) e seção **Dica** com uma ferramenta e sua utilidade.
7. Salve o arquivo, confira as alterações na aba **Changes** e faça um commit com mensagem clara, como `Adiciona apresentação do participante 01`.
8. Clique em **Publish branch** e depois em **Create Pull Request**.
9. Confirme que o destino é a branch `main` do **repositório original**, não do fork. Descreva a mudança e inclua `Closes #N` (substitua N pelo número real da issue).
10. Peça à sua dupla que revise o PR na aba **Files changed**, deixe um comentário útil e envie a revisão.
11. Responda ao comentário e, se necessário, faça novo commit na **mesma branch**. O PR será atualizado automaticamente.
12. Após a revisão, um mantenedor autorizado verifica os critérios e integra o PR.

## Critérios de conclusão
- [ ] Issue com descrição e critérios verificáveis.
- [ ] PR apontando para o repositório original e ligado à issue.
- [ ] Apenas o arquivo individual foi editado.
- [ ] Revisão com comentário relevante.
- [ ] Autor respondeu ao feedback.
- [ ] Contribuição integrada pelo mantenedor.

## Exemplo de issue e PR
Consulte [`exemplos/issue-modelo.md`](exemplos/issue-modelo.md) e [`exemplos/pull-request-modelo.md`](exemplos/pull-request-modelo.md).

## Evitando conflitos
Cada pessoa edita exclusivamente seu próprio arquivo. Não altere o arquivo de outra pessoa nem `participantes/demo.md`.

## Organização
Leandro é o responsável indicado no roteiro por permissões, labels e merges. Os apresentadores devem receber acesso apropriado antes da oficina. As permissões de organização incluem Write/Maintain; em repositórios pessoais, os níveis disponíveis podem ser diferentes.

Leia também [CONTRIBUTING.md](CONTRIBUTING.md) e [CONFIGURACAO-GITHUB.md](CONFIGURACAO-GITHUB.md).
