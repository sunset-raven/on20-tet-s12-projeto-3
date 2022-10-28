<h1 align="center">
  <img src="assets/reprograma-fundos-claros.png" alt="logo reprograma" width="500">
</h1>

# on20-TodasEmTech-ProjetoIII

Esta é a 12ª semana da turma online: Todas em Tech on20 - Front-end, nesta aula do dia 22/10/2022 faremos um projeto utilizando nossos conhecimentos no ES6:

- Neste projeto, iremos criar uma aplicação que usa a API GitHub para buscar informações da usuária quando um nome de usuária válido é inserido. Nossa aplicação deve exibir avatar, nome de usuário, contagem de seguidores e contagem de repositórios.
## Apresentação

### Quem é a professora Lilit?

<img src='./assets/lilit.jpeg' width=500 alt='Selfie da Lilit com cabelos cacheados longos pretos, blusa preta e ao fundo parede clara'>

[Lilit Bandeira](https://www.instagram.com/lilitravesti), é uma travesti paraibana residente no São Paulo, trabalho como Software Engineer no Nubank, ex-aluna e professora {reprograma} e professora também no minas programam, estudante de Analise e Desenvolvimento de Sistemas na Mackenzie;

#### Contatos

- [E-mail](devlilitbandeira@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/lilitbandeira)
- [GitHub](https://github.com/lilitbandeira)

### Quem são as monitoras?

<img src='./assets/misa.jpeg' width=700 alt='personagem misa misa do anime death note, tem cabelos loiros e lisos longos e olhos castanhos claros e usa batom vermelho. Veste blusa preta e gargantinha com spikes.'>

### Quem são as alunas?

<img src='./assets/bokunohero.jpeg' width=700 alt='5 personagens do anime Boku no hero, todas estão sorridentes e em fila indiana e vestem roupas colegiais típicas do japão.'>

## Acordos

- Enviar dúvidas no chat com as monitoras;
- Levantar a mão sempre que desejar falar, o que pode ser feito a qualquer momento;
- Manter microfones desligados sempre que alguém estiver falando;
- Manter as câmeras ligadas o máximo de tempo possível;
- Antes de começar, vamos organizar nosso setup.
  * Fork esse [repositório](https://github.com/reprograma/on20-tet-s9-javascript-3) 
  * Clone o fork na sua máquina (Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`)
  * Entre na pasta do seu repositório (Para isso basta abrir o seu terminal e digitar `cd nome-do-seu-repositorio-forkado`)
  * Altere as pastas chamadas "nome-aluna" para o seu nome-sobrenome, estes são os únicos locais onde você deve realizar alterações 

# Plano de aula

## Fase 1
- [ ] Criar o layout seguindo o Figma disponibilizado.
- [ ] O Input recebe o username de um usuário. Quando clicar no botão de pesquisa, caso o usuário exista dentro da base de dados da API, a aplicação deve mostrar os dados desta forma: 
   - Exibir o avatar.
   - Nome do usuário.
   - Username
   - Bio
   - Total de seguidores
   - Total de repositórios

**Exemplo**: 
<p align="center">
  <img src="./assets/profile.png" />
</p>

- [ ] Validar campo de texto para não entrar texto vazio
- [ ] Limpar campo de texto depois que inserir o nome de usuária
- [ ] A usuária deve receber um alerta se o nome de usuária não for válido 
  

**Exemplo**: 
<p align="center">
  <img src="./assets/not-found.png" />
</p>



## Fase 2 - Extra

- [ ] Exibir todos repositórios da usuária, com as informações:
    - Titulo
    - Descrição
    - Linguagem utilizada
    - Total de estrelas
- [ ] A página deve exibir um alerta caso a usuária pesquisada não tenha repositórios públicos  

**Exemplo**: 
<p align="center">
  <img src="./assets/profile-repos.png" />
</p>
<p align="center">
  <img src="./assets/repos-nao-encontrado.png" />
</p>

## Como vou entregar o projeto?
- Forke o projeto, depois faça uma pasta com o seu nome ex. lilit-bandeira dentro da pasta entrega-projeto. Suba as alterações commitadas e quando finalizado, faça um Pull Request. 

- Importante: Tudo bem se você não conseguir finalizar o desafio todo ou não realizar a parte Extra, o importante é realizar tudo que conseguir! Se ajudem entre si e confiem no que aprenderam 💜

# Links e recursos úteis

- [Layout do projeto](https://www.figma.com/file/UjuUSqwVpb7OtbWysQZffj/github-search?node-id=0%3A1)
- [Documentação - API GitHub](https://docs.github.com/pt/rest)

