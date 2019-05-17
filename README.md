# hello-word
  # Git e contribuições para projetos Open Source

<h1>Sobre este curso</h1>
  <h2>Aprenda desde o controle de versão, ferramentas como Git e GitHub, e como contribuir com projetos Open Source.</h2>
  <a>
O curso é voltado para iniciantes e aqueles que nunca tiveram contato com Git e GitHub. Aqueles que já possuem experiência com Git também poderão estar aprendendo conceitos novos com o curso. Como Git é uma ferramenta de colaboração, você pode ter uma experiência mais interessante fazendo as aulas do curso junto com outras pessoas.

Na primeira seção do curso você aprenderá os conceitos básicos de Gerência de Configuração, um tema onde o Git está inserido como ferramenta. Vai entender as motivações de se aplicar controle de versão e usar Git.

Depois, na segunda seção, você vai começar a usar Git a partir dos comandos básicos, criar o primeiro repositório e fazer os primeiros commits no GitHub. 

Na terceira seção, você vai ver sobre o histórico do Git e como resolver conflitos que acontecem quando duas pessoas editam o mesmo arquivo.

A quarta seção é dedicada para você aprender sobre Branchs e com isso organizar melhor o desenvolvimento do seu projeto. Você aprenderá quando usar Rebase e Merge para juntar branchs e assim como nas outras seções, praticará com exercícios.

Na quinta seção você irá aprender mais sobre o GitHub, uma rede social incrível que permite vários desenvolvedores contribuírem com projetos Open Source. Você verá como estar atento a projetos, contribuir com eles e gerenciar seu projeto no GitHub também.

Na última seção você aprenderá tópicos mais avançados de Git e GitHub. Tópicos que não muito usado por iniciantes mas são bastante úteis.

O que você aprenderá
Fundamentos básicos sobre Controle de Versão.
 + Git para controle de versão.
 + Git para trabalhar em equipe.
 + Contribuindo com projetos Open Source no GitHub.
 
Há algum requisito ou pré-requisito para o curso?  
 +  Não há nenhum pré-requisito para este curso, você não precisa ser um programador para entender o curso.
 
Para quem é este curso:
 + Qualquer pessoa que queira aprender sobre Controle de Versão e Git.
 + Não programadores envolvidos com tecnologia, como Designers.
 + Quem está procurando uma ferramenta para trabalho colaborativo.</a>

# Início do curso

<h1>git command line intructions</h1> 

  <h2>Configuraçõa Global do Git</h2>
    <a>
  + git config --global user.name"name"
  + git config --global user.email"email"</a>

   <h2>Criar novo repositório</h2>
    <a>
  + git add * | " para adicionar todos os conteúdo "
  + git commit -m "comentário" 
  + git pus - u origin master 
    <i>o primeiro repositório é ciado com o usuário master</i> </a>  
    <h2>Clone repositório</h2>
    <a>
  + git clone https:// .
  + cd pasta  | " Na pasta do clone ".
  + git add * | " para adicionar todos os conteúdo ".
  + git commit -m "comentário" .
  + git pus - u origin "dev" ou "master"| "se diver o branch como master dev".
    </a>
    <h1> 1 - Como criar uma nova branch</h1>
    <h5> 2 - Clique na botão no topo escrito "branch:master"</h5>
    <h5> 3 - Adiciona um nome na descrição :ex readme-edits</h5>
    <h5> 4 - Seleciona o campo azul na Caixa branch</h5>
<a>Agora você tem dois ramos mastere e ex readme-edits . Eles parecem exatamente o mesmo, mas não por muito tempo! Em seguida, adicionaremos nossas alterações à nova ramificação.</a>

# Vamos lá como fazer commit na sua Branch:master
<h1>command line</h1>
<a>

  + git checkout origin/readme-edits . ira aparece uma mesagem assim:
  HEAD is now at 8a57281 v.1.0
    M       README.md
    
  + cd pasta  | " Na pasta do clone ".
  + git init 
  + git add * | " para adicionar todos os conteúdo ".
  + git commit -m "comentário" .
  + git pus - u origin  origin/"readme-edits"| "se diver o branch como master dev".
    </a>