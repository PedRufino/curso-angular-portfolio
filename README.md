<h1 align="center">
  <img src="https://vidafullstack.com.br/wp-content/uploads/2020/07/angular.png" alt="" width="150">
  <br>
    Projeto Prático: Portfólio
  <br>
  https://pedrufino.github.io/curso-angular-portfolio/
</h1>

---

## :book: Descrição do Projeto

Este é um projeto prático desenvolvido durante o curso de Angular, com o objetivo de criar um portfólio online. O projeto visa apresentar as habilidades adquiridas no desenvolvimento web, com foco em Angular, GitHub Pages e práticas de deploy contínuo. O portfólio inclui informações sobre o desenvolvedor, projetos, tecnologias utilizadas e formas de contato.

---

## :rocket: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **[Angular](https://angular.io/)**: Framework para criação de aplicações web modernas.
- **[GitHub Pages](https://pages.github.com/)**: Plataforma para hospedar sites estáticos diretamente do repositório GitHub.
- **[npm](https://www.npmjs.com/)**: Gerenciador de pacotes para JavaScript.
- **[Angular CLI](https://angular.io/cli)**: Ferramenta de linha de comando para facilitar o desenvolvimento em Angular.
- **[angular-cli-ghpages](https://www.npmjs.com/package/angular-cli-ghpages)**: Pacote para deploy de aplicações Angular no GitHub Pages.

---

## :gear: Instalação e Configuração

Para rodar o projeto localmente, siga os passos abaixo:

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/seu-repo.git
    ```

2. **Navegue até a pasta do projeto:**
    ```bash
    cd seu-repo
    ```

3. **Instale as dependências:**
    ```bash
    npm install
    ```

4. **Rode o projeto localmente:**
    ```bash
    ng serve
    ```

5. **Acesse o portfólio no seu navegador:**
    Abra o navegador e acesse `http://localhost:4200`.

---

## :custard: Aprenda a Subir o Seu Código no GitHub Pages

Siga os passos abaixo para realizar o deploy do seu projeto Angular no GitHub Pages:

1. **Instale o angular-cli-ghpages:**
    ```bash
    npm i -g angular-cli-ghpages
    ```

2. **Execute o comando para gerar a build de produção:**
    ```bash
    ng build --configuration production --base-href="./[seu-repo]"
    ```

3. **Realize o deploy com o comando abaixo:**
    ```bash
    angular-cli-ghpages --dir=dist/[seu-projeto]
    ```

4. **Faça o deploy final:**
    ```bash
    ng deploy --base-href https://SEU_PERFIL_GITHUB.github.io/SEU_REPO_GITHUB/browser/
    ```

Com isso, seu portfólio estará acessível através do GitHub Pages.

---

## :heart: Agradecimentos

Com ♥ Pedro Rufino :wave:  
[LinkedIn](https://www.linkedin.com/in/pedro-rufino-da-mata-neto/)