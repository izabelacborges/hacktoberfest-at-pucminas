# Boas Práticas

Esse documento contém dicas de como fazer commits, issues e PRs melhores!

## Política de Commits

- **Faça commits atômicos:** Sempre divida o trabalho em commits curtos e pontuais, fazendo com que cada commit implemente apenas uma funcionalidade.
- **Sempre escreva a mensagem dos commits em inglês:** A fim de deixar o projeto mais uniforme as mensagens dos commits devem estar em inglês.
- **Seguir a regra do 50/72:** As mensagens do commit devem possuir no máximo 50 caracteres. Caso seja necessário uma mensagem maior, escreva um resumo de até 50 caracteres, adicione uma linha em branco e descreva melhor o commit em quantas linhas forem necessárias, porém cada linha deve respeitar o tamanho máximo de 72 caracteres. Caso seu commit necessite mais espaço que isso ele não é atômico.

## Verificando e Criando Issues

- **Verifique as issues existentes:** Sempre olhe as issues existentes antes de fazer seu pull request. Talvez a necessidade de alteração já exista e alguém já esteja trabalhando nela.
- **Crie issues novas:** Caso você tenha uma proposta de adição de informação ou de conserto/melhoria, que não é contemplado por nenhuma das issues existentes, crie uma issue nova.
- **Use os templates de issues:** Ao criar uma issue nova, use os templates existentes. Atualmente temos os templates de "Solicitação de Informação" para PRs de adição de informação e "Necssidade de alteração" para PRs que melhoram nosso projetinho.

## Fazendo seu Pull Request

- **Faça PRs a partir de uma branch!** Depois de fazer seu fork, crie uma branch e faça o PR a partir dela ao invés da main do seu fork.
- **Use um template no seu pull request.** Assim como templates para issues, temos templates para pull requests, selecione o template desejado e complete com as informaçÕes necessárias.
- **Relacione seu PR à uma issue!** Você pode relacionar seu PR à uma issue usando as palavras reservadas:
  - close
  - closes
  - closed
  - fix
  - fixes
  - fixed
  - resolver
  - resolve
  - resolved
- **Revise o checklist no template do PR.** Revise o checklist e complete caso falta alguma coisa. Os commits feitos pra branch usada no PR aparecerão automaticamente no PR já feito!
