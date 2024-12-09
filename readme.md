Principais Funções do Git e do Github:

O Git é um sistema de controle de versão distribuído que permite aos desenvolvedores rastrear mudanças no código e colaborar em projetos de software. Sendo um sistema de controle de versão, ou VCS, ele monitora o histórico de alterações à medida que as pessoas e equipes colaboram em projetos em conjunto, fazendo com que qualquer versão anterior do projeto pode ser recuperada a qualquer momento.
Dentre algumas funções do Git, podemos citar a Branching e Merging, que facilita a criação de ramificações (branches) para desenvolver novas funcionalidades isoladamente e mesclar (merge) essas mudanças de volta ao código principal de forma organizada. Por ser um sistema distribuído, significa que o Git permite que cada desenvolvedor tenha uma cópia completa do repositório em seu próprio computador, permitindo trabalhar offline.

Já o GitHub se trata de uma plataforma de hospedagem de repositórios Git na web, fornecendo aos desenvolvedores ferramentas para enviar um código melhor por meio das funcionalidades de linha de comando, problemas(discussões encadeadas), pull requests, revisão de código ou o uso de uma coleção de aplicativos grátis e para compra em GitHub Marketplace.
Ao usar o fluxo GitHub, os desenvolvedores simplesmente criam um branch para trabalhar nas atualizações, enviar alterações para salvá-las, abrir um pull request para propor e discutir alterações, e fazer merge de pull requests quando todos estiverem na mesma página.

Postagem de um projeto em um repositório no GitHub:

Para iniciar a postagem do repositório é necessário colocar alguns comandos, podendo utilizar o próprio terminal da ferramenta de editor de código (como o Visual Code). Mas antes é preciso, ainda, configurar o Git, utilizando os comandos:

git config --global user.email "seuemail@example.com"
git config --global user.name "Seu Nome" 

Com a conta configurada, abra o arquivo do projeto no editor de código e abra o terminal. Depois, inicie os seguintes comandos, na ordem:

    git init
    git add 
    git commit -m "mensagem"
    git branch -M "main"

Agora crie o repositório no GitHub e copie o link deste repositório. Depois, insira os seguintes comandos: 

    git remote add origin (link do repositório)
    git push -u origin main
