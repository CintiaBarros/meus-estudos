# **Terminal**

![Alt ou título da imagem](/imagens/ilustracao_terminal.jpeg)


## O que é?

O terminal é o computador sem a interface gráfica.
Na interface gráfica usamos o mouse para clicar, no terminal usamos o teclado para digitar comandos.  

Por volta da década de 1980, os terminais eram associados a sistemas muito simples, sem unidade de processamento central própria. Isso significa que eles não tinham a capacidade de processar comandos de maneira independente de um servidor de terminais, isto é, uma máquina muito mais potente. Portanto, esse tipo de terminal, chamada de terminal burro, era apenas um monitor de vídeo e teclado ligados a um servidor de terminais, como na imagem abaixo.  

A princípio há vários motivos para ainda usarmos o bom e velho terminal. Vamos conhecer alguns deles:

**São mais leves e rápidos!**  
Exibir coisas visuais como botões, imagens e ícones consome recursos do computador, como memória e processamento. Por outro lado, quando um programa é executado em linha de comando, ele economiza recursos, possibilitando uma melhoria na performance.

**Terminais são simples de serem usados**  
Essas telas onde escrevemos comandos podem assustar em um primeiro momento. Mas acredite, elas são mais simples!

Em um software cheio de funcionalidades, você precisa procurar no menu onde está o botão para executar a funcionalidade que você quer. Se acaso não encontrar, o próximo passo é recorrer ao Google.

Ao passo que em terminais, basta saber o nome do comando e escrevê-lo. Se acaso você não se lembrar, existe a possibilidade de mandar o programa exibir a sua lista de comandos. Se a lista for muito grande, você ainda tem a possibilidade de filtrar para exibir exatamente o que você está procurando.
**Podemos automatizar qualquer coisa**  

Programas que são executados a partir do terminal são acionados por comandos que escrevemos no próprio terminal. E podemos deixar esses comandos salvos em um arquivo para executá-los depois. Assim, podemos ter várias tarefas automatizadas.

**Várias funcionalidades do seu Sistema Operacional são acessíveis pelo terminal, e muitas delas só podem ser acessadas dessa maneira. Ou seja, muitas possibilidades novas!**  

A maioria dos sistemas operacionais previne que você faça uma bagunça nos processos centrais do sistema. O Windows conta com um sistema de proteção e o MacOS tem o SIP (System Integrity Protection – Proteção da Integridade do Sistema). Com isso, você não vai poder fazer certas tarefas que estão protegidas pelo próprio sistema. É por isso que, com o CLI, você ganha controle total sobre o seu sistema de escolha.

## **Algumas das sintaxes no prompt de comando:**

- **Modificar um Diretório:**  

Para navegar para um diretório ou pasta específica pelo prompt de comando, use CD [caminho]. Garanta que tenha um espaço antes de colocar o caminho (path) que você quer alcançar. Por exemplo:  

>CD C:\Program Files

- **Renomear um Arquivo:**  

Para renomear um arquivo dentro de uma pasta específica, use REN [drive:][caminho] [fonte] [alvo]. Se você mencionar o local (path), isso significa que o arquivo renomeado será salvo na mesma pasta mencionada. Por exemplo:
>REN d:untitled.txt untitled1.txt  

- **Apagar um Arquivo:**  

Para apagar um arquivo pelo prompt de comando, use DEL [nomedoarquivo]. Se você quer forçar a exclusão de um arquivo, é só adicionar o comando certo antes do nome do arquivo. Por exemplo:  
>DEL /F untitled.txt  

- **Renomear um Disco:**  

Para editar o nome de um disco específico, use LABEL [drive:][novo nome do disco]. Saiba que, aqui, você pode usar até 32 caracteres no volume NTFS e 11 caracteres no volume FAT. Por exemplo:
>D:\ > LABEL d:MyData  

## Bash
Bash é o acrônimo para Bourne Again Shell. Ele foi desenvolvido pela Free Software Foundation. 

O Bash é um tipo de shell usado no MacOS e outras distribuições do Linux. Porém, você também pode usar o Bash Linux no Windows 10, se quiser.

No Linux, o Bash shell é só um dos muitos tipos de shell que o Linux pode usar. Outros tipos bem conhecidos são o Techs shell, Ksh shell e Zsh shell. 

Na maioria das distribuições Linux, o shell é localizado no menu Utilities (Utilidades). Se você usar o desktop Gnome, o nome será Terminal. Mas, se você usar o KDE, o nome será Konsole. 

Enquanto isso, no MacOS, o programa é o Terminal.app. Para rodar esse programa, vá em Application > Utilities > Terminal. Ou simplesmente digite Terminal usando a busca pelo software Spotlight. 

Assim que o terminal abrir, você já pode começar a colocar seus primeiros comandos. Basicamente, a maioria dos comandos consiste em: o comando em si, o argumento e a opção.  

Enquanto o comando contém a instrução que queremos desempenhar, é o argumento que diz onde o comando deve operar. Já a opção faz o pedido para a modificação do resultado do comando.

**Basicamente, os comandos são divididos em:**

- Comandos que gerenciam os processos;  
- Comandos que gerenciam os arquivos.  

**Para entender a sintaxe de comando no MacOS, vamos aprender alguns exemplos:**

- **Listar Todos os Arquivos em uma Pasta**  

Para saber quais arquivos estão em uma pasta, use ls. O comando padrão vai excluir os arquivos escondidos. Para mostrar todos os arquivos, você deve adicionar um -a. Por exemplo:
>ls -a

![Alt ou título da imagem](/imagens/ls.png)  
- **Mudar de Diretório**  

Para mover para mudar para um diretório específico, use cd destino. Por exemplo:
>cd ~/Desktop  

![](/imagens/mudar_diretorio.jpeg)  


- **Renomear Arquivos**  

Para renomear um arquivo dentro de uma pasta específica, use mv fonte destino. Neste caso, você precisa saber qual o nome do arquivo e a extensão dele. Por exemplo:  
>mv ~/Desktop/untitled.rtf ~/Desktop/untitled1.rtf  

![](/imagens/renomear_arquivo.png)

- **Apagar Arquivos**

Para apagar um arquivo em uma pasta específica, use rm nome do arquivo. Para evitar deletar arquivos que você não quer, garanta que você mova estes arquivos para a pasta certa antes. Por exemplo:  

>rm untitled.rtf  

![](/imagens/apagar_arquivos.jpeg)

## Conclusão  

Digitar o comando certo é crucial. Isso significa que você deve prestar atenção em cada caractere que for usar. Além disso, use o comando certo para cada caso.

E se por algum motivo você quiser parar de usar o Prompt de Comando ou o Bash, é só digitar Control+C. Você vai sair das telas deles e voltar ao sistema operacional normalmente.  



Fonte: [Treino Web, por Akira Hanashiro](https://www.treinaweb.com.br/blog/por-que-ainda-usamos-o-terminal) e 
[Hostinger, por Andrei L](https://www.hostinger.com.br/tutoriais/o-que-e-cli)