# GIT - O Guia Divertido para Iniciantes Absolutos!

Imagine que o Git é uma espécie de máquina do tempo para os seus códigos, permitindo que você volte no tempo quando algo dá errado (e acredite, às vezes, vai dar). Aqui vamos explicar tudo como se você tivesse acabado de descobrir que pode salvar mais de uma versão dos seus documentos, em vez de salvar tudo como "versão_final_revisada2_FINALMESMO.docx".

## Estados do Código no Universo Paralelo do GIT

- **Modificado (modified):** "Ei, mudei alguma coisa aqui!"
- **Preparado (staged/index):** "Olha só, pronto para a ação!"
- **Consolidado (comitted):** "Tá seguro agora, pode confiar!"

## Pedindo Ajuda ao Sábio GIT

#### Para saber tudo que o GIT pode fazer:
`git help`

#### Se estiver querendo detalhes sobre um feitiço... ops, comando específico:
`git help <esse_comando_aqui>`
Por exemplo:
`git help add`
`git help commit`
`git help <qualquer_comando_git>`

## Configurando sua Caverna Mágica

Antes de começar a brincadeira, vamos ajustar a sua caverna mágica (sim, é assim que vamos chamar o seu ambiente de trabalho agora).

#### Nome e Email (para os pergaminhos de créditos)
`git config --global user.name "Seu Nome Aqui"`
`git config --global user.email seuemail@exemplo.com`

#### Escolhendo sua Varinha... Quer Dizer, Editor:
`git config --global core.editor nome_do_editor`

#### Definindo a Ferramenta de Merge (quando dois feitiços colidem)
`git config --global merge.tool nome_da_ferramenta`

#### Ignorando Objetos Mágicos Indesejados
`git config --global core.excludesfile ~/.gitignore`

#### Para Espiar o Livro de Feitiços (suas configurações)
`git config --list`

### Livro dos Invisíveis (Ignorar Arquivos)

O **.gitignore** é tipo o Capa da Invisibilidade; ele esconde os arquivos que você não quer que apareçam no seu repositório.

## Criando seu Próprio Mundo (Repositório Local)

#### Para invocar um novo mundo:
`git init`

#### Para ver como estão as coisas no seu mundo:
`git status`

#### Adicionando coisas ao Palco (Staged Area)
`git add nome_do_arquivo_ou_pasta`
Ou, para adicionar tudo:
`git add .`

#### Fazendo a Mágica Acontecer (Commit)
Para salvar o estado atual do seu mundo com uma mensagem explicando o que foi feito:
`git commit -m "Aqui vai a explicação do feitiço"`

### Viajando para Outros Mundos (Repositório Remoto)

#### Para vincular seu mundo a um universo paralelo:
`git remote add origin endereço_do_universo_remoto.git`

#### Para enviar suas mágicas para o universo paralelo:
`git push -u origin master`
E, para atualizar seu mundo com as mágicas do universo paralelo:
`git pull`

### Desfazendo Feitiços (Quando as Coisas Dão Errado)

#### Se você só mexeu nas coisas, mas ainda não preparou o feitiço (staged):
`git checkout -- nome_do_arquivo`

#### Se você já preparou o feitiço, mas quer desfazer:
`git reset HEAD nome_do_arquivo`
`git checkout nome_do_arquivo`

## Branches: Criando Realidades Paralelas

Para criar uma nova realidade paralela:
`git branch nome_da_realidade`
Para trocar entre realidades:
`git checkout nome_da_realidade`
E para juntar duas realidades em uma:
`git merge nome_da_realidade`

## Conclusão

Pronto! Agora você tem o básico para começar a brincar de Deus dos Códigos com o GIT, criando, salvando e manipulando universos paralelos com facilidade. Lembre-se, com grandes poderes vêm grandes responsabilidades. Use seu poder para o bem, jovem Padawan!
