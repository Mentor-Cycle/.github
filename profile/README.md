






<p align="center">
	<h1 align="center">Mentor Cycle</h1>
</p>

<div align="center">
	<img src="https://github.com/Mentor-Cycle/.github/assets/57500163/b3ad1239-93d6-4b1c-b758-900f0cb6ab64" />
</div>

<br>

## 💻 Projeto

O Mentor Cycle é um projeto open-source cujo objetivo é conectar pessoas na área de T.I que estão aprendendo, com profissionais com experiência de mercado, fazendo o match entre aprendiz e mentor. Isso faz com que o iniciante tenha uma pessoa que já vivenciou aquilo que o mesmo está procurando aprender, facilitando sua jornada de estudos e metas.

Para entender melhor o projeto, você pode assistir esse vídeo que mostra uma visão macro da plataforma:

[CLIQUE PARA VER O VÍDEO](https://youtu.be/mIt9n-BdLYY)


## 🤔 Como contribuir

**Agora que você já sabe como funciona, bora ver os passos para contribuir com o projeto! 🚀🚀🚀**

> Para tarefas de UI/UX, siga os processos baseados no time, caso tenha dúvida entre em contato pelo Discord ou na Comunidade Whatsapp.

Antes de tudo precisamos ter as seguintes ferramentas instaladas na sua máquina:

- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/) ou similar

> Caso você esteja fazendo uma tarefa Front-end e necessite do Layout, role até o fim da página e acesse o link do figma.

 1. Entre no [Github Projects](https://github.com/orgs/Mentor-Cycle/projects/1/views/1) e veja as tarefas que estão na coluna **"A Fazer"**, lá você pode escolher um card, clicar nele, assine-o para você e arraste a tarefa para a coluna **"Em Progresso"**. A partir daí você já estará responsável pela entrega desta tarefa OBS: se você não for um membro, apenas coloque um comentário que está responsavel por essa task: 
 
![image](https://github.com/Mentor-Cycle/mentor-cycle-be/assets/57500163/2d855028-c715-4623-b482-fc6ae2e3040c)
    
 2. Agora vá até a aba **"Repositórios"** e escolha um repositório, lembrando que existem repositórios **Front-end** e **Back-end**, baseado na tarefa que você escolheu você irá fazer um **"Fork"** da aplicação, para isso você precisa abrir o repositório escolhido e clicar em **"fork"**, do lado superior direito conforme na imagem:
 
![image](https://user-images.githubusercontent.com/57500163/216629255-034809cf-1041-4ee7-9a60-63722b4ab08d.png)
	
O Fork visa criar um clone desse repositório na sua conta GitHub, e é lá que você irá trabalhar no projeto, nunca submeta PRs diretamente do repositório da organização, existe uma trava que não permitirá que você faça isso, então caso tenha algum erro, reveja esse passo. Após fazer o fork você deverá ter um repositório com o seguinte nome: 
`seu_nome_de_usuario/nome_do_repositorio` como está aqui: 

![image](https://user-images.githubusercontent.com/57500163/216630241-9e83c4cc-082b-441c-949e-cd0f3daf7312.png)
	
 3.   Após fazer o Fork, você irá clonar o repositório criado da sua conta, lembrando, você deve clonar o repositório `seu_nome_de_usuario/nome_do_repositorio` e não o `Mentor-Cycle/nome_do_repositorio`. 

> Clonar um repositório significa baixa-lo para a sua máquina mantendo uma conexão com o GitHub

 
 Para clonar basta você clicar no botão **"<> Code"** e copiar o link que aparecerá na tela, após isso va até seu terminal e digite o seguinte comando: 
```bash
git clone codigo_que_voce_copiou
```
No meu caso estou clonando o repositório Back-end como exemplo, então o comando ficará assim: 
```bash
git clone https://github.com/oliveirabalsa/mentor-cycle-be.git
```

4. Com repositório na sua máquina, basta você abri-lo com seu editor de código favorito, em seguida executar o comando:
```bash
yarn
```
Isso fará com que o gerenciador de pacotes do node, baixe todas as dependências necessárias para rodar, finalizado a instalação rode o comando:
```bash
yarn dev
```
e para o Back-end:
```bash
yarn start:dev
```
5. Agora com tudo instalado e rodando, basta você criar a sua **branch**, executar a sua tarefa e após finalizado lembre se adicionar ao **stage** como o comando:

Criar branch:
```bash
git checkout -b nome_da_branch
```
Adicionando arquivos:
```bash
git add .
```
Adicione uma mensagem de commit com o comando: 
```bash
git commit -m "sua_mensagem_aqui"
```
> Neste passo lembre-se de utilizar uma mensagem em inglês e também descrevendo o que você fez com poucas palavras e o padrão de commits, por exemplo "feat: create user endpoint"

e em seguida suba as alterações para o seu repositório fork com o comando:
```bash
git push
```
6. Hora da pull request, após dar o `git push`, ao abrir o seu repositório fork na página do GitHub, você notará que existe uma mensagem logo no topo assim como essa: 
7. 
![image](https://user-images.githubusercontent.com/57500163/216635436-f2bfba76-a084-45b7-9b42-d8abe97a7062.png)

Vendo isso, clique no botão **"Compare & pull request"**, isso começara o processo de abertura de uma **PR(Pull Request**) e lembre se de apontar sempre para a branch `dev` do projeto Mentor Cycle  e também adicionar 2 pessoas para revisar a sua tarefa. Esse passo é muito importante, pois essas pessoas irão validar o que você fez e caso tenha algo errado ou que possa ser melhorado elas irão comentar. Isso ajudará muito na sua evolução.

Lembre se de colocar o título conforme o tipo da tarefa, uma mensagem que descreva o que você fez, se possível anexar uma captura de tela e colocar o Link do card da tarefa do Trello que você pegou, pode seguir este modelo ficando mais ou menos assim: 

![image](https://user-images.githubusercontent.com/57500163/216638205-a473736a-6dbb-453c-948f-2b7712df7d4a.png)


**Pronto, feito isso, é só aguardar a análise da sua PR, você será notificado caso seja aprovada ou o revisor solicite alguma alteração, BORA PRA CIMA!!!! 🚀🚀🚀**

## Nossas redes sociais

<p align="center">
  <a href="https://discord.gg/tuBshbtPNU">
  	<img  src="https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://www.linkedin.com/company/mentor-cycle/">
  	<img  src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin"> 
  </a>
  <a href="https://chat.whatsapp.com/Li9mljuXiPG6Rr2uU9VTsi">
  	<img  src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Whatsapp"> 
  </a>
  <a href="https://www.figma.com/file/KnsardnDQ2lDKUYo58G8Pf/Mentor-Cycle?node-id=11%3A6&t=JbtjqQL0XQJ1x054-1">
  	<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"> 
  </a>
  <a href="https://trello.com/invite/b/BJtM6SNZ/ATTI17cc38fcef42713d12a1f57d1d7130e4F920225C/tarefas">
  	<img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white" alt="Trello"> 
  </a>
</p>


---

<p align="center">Developed by <a href="https://www.linkedin.com/in/leonardo-balsalobre/">Leonardo Balsalobre</a> :copyright:
