## BRANCHES

>:bulb: teste é o nome dado ao nome da branch, mas pode ser qualquer nome.

- Criar branche: `git branch teste`
- Mudar para branche: `git checkout teste`
- Crirar branche e ir mudar para ela: `git checkout -b teste`
- Deletar a branche: `git branch -d teste`
- Deletar a branche com commites e sem fazer o merge: `git branch -D teste`

>:warning: Para se fazer um `merge` você precisa estar na branch principal ou na de destino.

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

>:buld: É recomendado excluir uma branche depois que você fez o merge com a main.


