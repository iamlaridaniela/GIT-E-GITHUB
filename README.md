# GIT-E-GITHUB
O GitHub é uma plataforma online usada para hospedagem de código-fonte e colaboração em projetos de software. Ele permite que desenvolvedores compartilhem, controlem versões e trabalhem juntos em projetos, utilizando o sistema de controle de versão Git. Além disso, o GitHub oferece recursos como repositórios, issues (problemas), pull requests e integração com outras ferramentas. É amplamente utilizado para projetos de código aberto e privado.
fonte:https://docs.github.com/
Principais Funções do Git e GitHub:

 Git: É um sistema de controle de versão distribuído que permite aos desenvolvedores rastrear mudanças no código ao longo do tempo. As principais funções do Git incluem:
  1. Rastrear alterações** no código.
  2. erenciar versões** do projeto, permitindo reverter para versões anteriores.
  3. Colaboração** entre vários desenvolvedores, facilitando o trabalho em paralelo.
  4. Branching e Merging**: criar ramos para desenvolver novas funcionalidades e, em seguida, mesclar as alterações de volta à versão principal.

GitHub: É uma plataforma online que hospeda repositórios Git, permitindo colaboração e controle de versões em projetos de software. Suas funções incluem:
  1. Hospedar repositórios** Git online.
  2. Facilitar a colaboração** entre desenvolvedores, com ferramentas como pull requests e issues.
  3. Gerenciar permissões de acesso** a repositórios (públicos ou privados).
  4. Documentação e integração** com outras ferramentas (CI/CD, automações, etc.).

Passos para Postar um Projeto no GitHub:

1. Criar um repositório**: Vá ao GitHub, clique em "New Repository" e preencha as informações básicas (nome, descrição, privacidade).
2. Inicializar Git no projeto local**: No terminal, no diretório do seu projeto, use `git init` para iniciar o controle de versão.
3. Adicionar arquivos ao repositório**: Utilize o comando `git add .` para adicionar todos os arquivos ao repositório local.
4. Commit das alterações**: Faça um commit com `git commit -m "Mensagem do commit"`.
5. Conectar ao repositório remoto no GitHub**: Use o comando `git remote add origin <URL-do-repositório>`.
6. Enviar o projeto para o GitHub**: Envie os arquivos com `git push -u origin main` (ou `master`, dependendo da configuração).
 Fonte:
- [GitHub Docs](https://docs.github.com/en/github)
