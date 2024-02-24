## BRANCHES

>:bulb: teste é o nome dado ao nome da branch, mas pode ser qualquer nome.

- Criar branche: `git branch teste`
- Mudar para branche: `git checkout teste`
- Criar branche e mudar para ela: `git checkout -b teste`
- Deletar a branche: `git branch -d teste`
- Deletar a branche com commites e sem fazer o merge: `git branch -D teste`
- Visualizar branches: `git branch`

>:warning: Para se fazer um `merge` você precisa estar na branch principal/de_destino.

Merge: `git branch teste`

## SOLUCIONANDO CONFLITOS

Passos para resolver um conflito em que duas pessoas em branches diferentas tentaram fazer uma mesma feature:

- Decida com a pessoa o que vão escolher no final das contas.
- Na parte do código em conflito faça as alterações manualmente.
- Na main execute:
    - `git add .`
    - `git commit -m` (não precisa passar nenhuma mensagem, o git já sabe que está resolvendo um conflito)

## PULL REQUEST

- Dar push em uma branche: `git push origin teste`

>:bulb: É recomendado excluir uma branche depois que você fez o merge com a main.

## FORK

O fork é bastante utilizado para contribuir com projetos open source.

- Visualizar histórico de um projeto: `git log --online`

- Passos para fazer um Pull Request no projeto:
 - Faça um fork
 - Clone o repositório
 - Faça suas features
 - Dê um merge na main caso tenha usado uma branche, caso contrário de um push na main direto.
 - Crie um PR no Github do seu repositório.
 - Em caso de você ser o gerente do projeto, basta aprovar o PR e confirmar a merge.

 ## ISSUES

 Issues são sugestões de outros pessoas no seu repositório.

 >:bulb: Para resolver uma issue de forma automática pelo terminal e referencir o commit na mudança, ao invés de fazer manual, realize as modicações sugeridas e quando for dar um commit utilize a sintaxe: `git commit -m "Nome do commit Fixed #1"`. O número após a # é relativo ao número da issue aberta no seu repositório.

