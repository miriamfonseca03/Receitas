# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto: Receitas
- Integrantes: Daniel Teixeira, Eline Matos, Geovana Mendes, Joaquim Duarte, Miriram Fonseca  
- Repositório: (https://github.com/miriamfonseca03/Receitas.git)


## Branches Criadas
Descreva as branches criadas e o objetivo de cada uma:
- Primeiro criamos os branches para cada receita pois cada membro do grupo criou uma receita diferente,
tambem criamos branches dos passos do modo de preparação para a receita colaborativa.

Informe como os merges foram realizados (com PR? Revisão?):
- Todas as integrações na main foram feitas através de Pull Requests, conforme a regra 3
do CONTRIBUTING.md, que exige a solicitação de revisão a outro integrante antes do merge.


## Histórico de Commits
Exemplo de boas mensagens de commit.
- O grupo fez commits com mensagens claras e simples do que era alterado ao longo do projeto,
- Exemplo:
"Rename receita-Bolo_de_cenoura.md to receita-bolo_de_cenoura.md";
"Criada a receita vegana - Chili Vegano de Feijao".

- Print ou link do gráfico de contribuições:
https://github.com/miriamfonseca03/Receitas/graphs/contributors?from=18%2F04%2F2026


## Issues Criadas
Liste as issues criadas e quem ficou responsável por cada uma.

Criamos 7 issues:
1. Criar receita do pao de queijo ("assignees: joaquimfduarte") 
2. Criar receita de bolo de cenoura com cobertura de chocolate ("assignees: miriamfonseca03") 
3. Revisar README.md ("assignees: miriamfonseca03") 
4. Padronizar nomes dos arquivos de receita ("assignees: todos os elementos do grupo") 
5. Corrigir erro de digitação em receita de pão de queijo ("assignees: tDniel") 
6. Discutir inclusão de receitas veganas ("assignees: todos os elementos do grupo") 
  - sub issue- "acho importante ter uma receita vegana - higeovaland"
7. Adicionar receita colaborativa ("assignees: todos os elementos do grupo") 


## Pull Requests
Descreva o processo de revisão e merges realizados.

O processo de contribuição seguido pelo grupo foi:
- Abertura do Pull Request no GitHub, com descrição do que foi feito
- Atribuição de um revisor (outro integrante do grupo, nunca o próprio autor)
- Revisão por outro integrante do grupo, que podia aprovar ou pedir alterações
- Merge para a main após aprovação.
- Foram abertos 13 Pull Requests, todos revistos por pelo menos um colega antes do merge, 11 PR foram integrados
com sucesso e 2 foram fechados em merge porque as branches não eram necessárias e as alterações já tinham sido
feitas noutras branches entretanto.


## Conflitos e Resoluções
Explique se houve conflitos e como foram resolvidos.

- Onde aconteceu o conflito: No ficheiro receitas-veganas/receita-chili_vegano_feijao.md, na secção
"Modo de Preparação" (a lista de passos da receita).
- O que causou o conflito: Duas branches diferentes estavam a editar a mesma lista de passos em paralelo. 
Como ambas as branches alteravam a mesma zona do ficheiro, ao tentar fazer merge de volta para a main 
surgiu um conflito de linhas.
- Como foi resolvido: Um elemento do grupo resolveu o conflito manualmente, através de dois merges sucessivos 
da branch main para "geovanaModoPreparo", combinando corretamente todos os passos das duas versões pela ordem certa, 
o próprio confirmou isto na conversa da PR com o comentário: "Resolvido o conflito entre as linhas". 


## Dificuldades Enfrentadas
Dúvidas ou problemas que surgiram.

- Além do conflito já descrito, tivemos dificuldades em manter a organização dos branches, ao longo do projeto foram 
criadas mais branches do que as realmente necessárias. 
- Como o trabalho dessas branches acabou por não ser necessário, essas branches e PRs foram eliminadas/fechadas sem merge. 
Isso levou nos a perceber a importância de planear melhor a criação de branches antes de começar a trabalhar.


## Principais Comandos Git Utilizados
Liste e comente comandos importantes usados no projeto.

- git clone; 
-Para obter o repositório localmente; 
- git pull origin main;
-Para atualizar a main local com as alterações mais recentes do remoto, 
evitando trabalhar com código desatualizado;
- git checkout -b <branch>;
-Para criar um branch novo por receita/tarefa; 
- git add .;
-Para preparar todas as alterações feitas antes do commit;
- git commit -m “Adiciona receita de bolo de cenoura”;
-Para registar as alterações no histórico com uma mensagem clara;
- git push -u origin <branch>; 
-Para enviar o branch pela primeira vez ao repositório remoto, 
associando ao branch remoto correspondente;
- git push origin <branch>;
-Para enviar novos commits feitos.


## Conclusão
Aprendizados principais do grupo com a atividade.

-Na prática aprendemos o fluxo de trabalho colaborativo com Git e GitHub: 
- Criação de branches por tarefa, commits com mensagens claras, uso de issues para organizar o trabalho, 
revisão por pares antes do merge via Pull Request e resolução de um conflito real de merge.
A principal lição foi a importância de sincronizar frequentemente as branches com a main para evitar trabalho desnecessário. 







