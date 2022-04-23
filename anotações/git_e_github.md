# Git e Github
![Alt ou título da imagem](/imagens/gitgithub.png)  
## O que é Git?  

Sistema para controle de versão (VCS). Versionamento de software.

Criado pelo engenheiro de software Linus Torvalds, conhecido por ter desenvolvido, também, o núcleo Linux, o GIT é um Sistema de Controle de Versões Distribuído — ou DVCS.

Muito importante para lidar com diversas versões de um mesmo projeto enquanto esta sendo desenvolvido pois ele salva cada alteracão no projeto, registra o momento exato das modificações quando fazemos um commit, uma das maiores vantagens de usar o GIT é a economia de tempo e recursos, uma vez que a consulta de diferentes versões de uma mesma aplicação é muito recorrente no trabalho do(a) programador(a).
Existem outros VCS's mas o git tem sido o mais utilizado por ser um sistema distribuído.
Isso significa que, diferentemente de outros sistemas de controle de versionamento populares na época em que foi lançado, o GIT possui repositórios, e não somente um único local com o histórico de seu trabalho.

Para auxiliar o trabalho em equipe, recursos como o fluxo de desenvolvimento do Gitflow também trazem muitos benefícios, inclusive porque pode ser acessado por qualquer membro do time em qualquer lugar.

## Alguns comandos git:  

**git init**: Cria um repositório git;  
**git clone**: este comando clona o código de um repositório para sua manipulação em outro ambiente;  
**git status**: Analisar o status do repositório;  
**git add**: este comando adiciona um arquivo alterado a uma staging area, ou seja, o prepara para ser vinculado a um commit;
**git ignore**: Ignorar determinada linha ao comitar no projeto;  
**git add ou git ..**: Adiciona a alteração realizada no diretório;  
**git commit -m "inserir o que for realizado"**: Para comitar no projeto;  
**git push**: utilizado para enviar as alterações com commit para repositórios remotos como o github;   
**git pull**: Trazer as alterações realizadas no ambiente remoto, como github, para o ambiente local;  
**git merge**: este comando serve para unir arquivos alterados ao arquivo original de um projeto. Em outras palavras, é ele quem une os branchs as commits;
**git log**: este comando permite a visualização do histórico de commits de um arquivo ou usuário, ou o acesso de uma versão específica.


## O que é Github?

GitHub é uma plataforma totalmente online (semelhante a uma rede social) onde podemos criar repositórios e hospedar neles projetos, colaborar com softwares open source, seguir outros(as) programadores(as) e interagir com códigos de terceiros, utilizando para isso a tecnologia do git.Ele é, também, o maior repositório de softwares de código aberto de toda a internet.

## Benefícios em usar o Github:

* Possibilidade de acompanhar e colaborar com projetos de diferentes equipes;
* Aprender programação na prática ao observar o avanço do desenvolvimento de aplicações de terceiros;
* Participar de discussões a respeito de novas tecnologias;
* Obter auxílio de outros programadores para resolver problemas relacionados a seus projetos;
* Controlar as diferentes versões de um código com armazenamento em nuvem;
* Registrar ações e projetos desenvolvidos por você em uma espécie de portfólio online, etc.

## subindo um arquivo Git no Github:  

1. Salvar a edição no editor (vs code por exemplo);  
2. Abrir o projeto no terminal;  
3. Adicionar o arquivo (git add nomedoarquivo ou git add .) para adicionar todas as alterações do projeto;  
4. git commit -m "informar o que foi realizado" (esse processo é o que de fato salvará o projeto no git);  
5. git push origin (informar qual branch) para realizar o envio ao github.  

# Os conceitos do Git
Para começar a utilizar o GIT, é importante compreender alguns dos principais conceitos utilizados pela ferramenta.

Repositório:  
Os repositórios são os ambientes criados para armazenar códigos.

Podemos possuir um ou mais repositórios, públicos ou privados, locais ou remotos, e eles podem armazenar não somente os próprios códigos a serem modificados, mas também imagens, áudios, arquivos e outros elementos relacionados ao projeto.

É através dos repositórios públicos que outros programadores poderão ter acesso aos nossos códigos no GitHub, podendo, inclusive, cloná-los para adicionar melhorias.

Branch:  
Branch é o nome dado a uma versão (ramificação) do projeto. 

Isso é útil porque possibilita gerenciar múltiplas alterações acontecendo simultaneamente. Por exemplo, podemos fazer com que cada equipe de desenvolvimento seja responsável por uma parte do projeto sem que interfira no projeto como um todo antes que todas as definicões estejam prontas. 

Merge
Para unir as modificações feitas em um branch ao código original, utilizamos o comando merge.

Com esta funcionalidade, todas as alterações feitas em cópias manipuláveis são inseridas, após aprovadas, no código-fonte original sem complicações.

Fork
Quando um profissional desenvolvedor precisa começar a trabalhar em um projeto, seu primeiro passo é copiar este repositório para a sua máquina.

Este processo é realizado pelo comando fork.

O fork também é uma funcionalidade útil quando um membro da equipe precisa pegar um código público para manuseá-lo em um editor de código local ou interno.

**Fonte**: [Kenzie, por Ugo Roveda.](https://kenzie.com.br/blog/o-que-e-git/)