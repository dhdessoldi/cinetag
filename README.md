# Cinetag

Este projeto foi desenvolvido como uma página para salvar e favoritar seus vídeos, filmes e séries favoritos.

### Tecnologias utilizadas

* React com JavaScript;
* CSS Modules;

## Desenvolvimento

O projeto foi desenvolvido utilizando React com JavaScript, inicializado com [Create React App](https://github.com/facebook/create-react-app). \
Algumas páginas foram criadas e a navegação entre elas é realizada pelo [react-router-dom](https://reactrouter.com/en/main). \
Os elementos das páginas foram componentizados para manter a semântica, facilitar o entendimento e a manutenção do código. \
A estilização de cada componente e das páginas foi feita utilizando [CSS Modules](https://github.com/css-modules/css-modules). \
Para facilitar a navegação entre as páginas, foi utilizado o elemento <Link> do [react-router-dom](https://reactrouter.com/en/main) e um elemento Scroll to Top para melhorar a usuabilidade do site. \
Para prover as informações de quais são os vídeos favoritados, foi utilizado [useContext](https://react.dev/reference/react/useContext);

## Vídeos
  
  Para a criação dos os vídeos, um arquivo JSON foi criado com as informações sobre cada vídeo. 
  Essas informações são mapeadas e estão presentes em cada postagem sobre meu trabalho.
  Elas estão sendo extraídas de outro [repositório](https://github.com/dhdessoldi/cinetag-api).

Para rodar a aplicação será necessário instalar:

* [Visual Studio Code](https://code.visualstudio.com/) ou algum outro editor de código;
* [Node.js](https://nodejs.org/en);
* [Git](https://git-scm.com/downloads);

Após baixar instalar os programas acime a baixar o código, abra a pasta da aplicação pelo Visual Studio Code, com ela aberta siga os seguintes passos:

* Pressiona **Ctrl + '** para abrir o terminal;
* Digite **npm install** para instalar as dependências do projeto;
* Digite **npm start** para rodar a aplicação e abri-la em seu navegador.


### ScreenShots

![image](https://github.com/dhdessoldi/cinetag/assets/110476564/961042ae-1394-4ae0-b205-5966b2a5afea)

