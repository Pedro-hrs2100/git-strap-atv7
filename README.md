# Getting Started with Create React App

1- Instalar dependências:
No terminal, execute os seguintes comandos para instalar o Reactstrap, Bootstrap e Popper:

npm install reactstrap react react-dom
npm install --save bootstrap
npm install react-popper @popperjs/core

2- Foi Configurado o Bootstrap:
Abra o arquivo index.js na pasta src e adicione a seguinte linha para importar o CSS do Bootstrap:

import 'bootstrap/dist/css/bootstrap.min.css';

3- Foi adicionado a barra de navegação (Navbar):
No arquivo App.js, apague o conteúdo entre as tags <header></header> e substitua pelo código abaixo:

import { Navbar, NavbarBrand } from 'reactstrap';

<Navbar dark color="primary">
  <div className="container">
    <NavbarBrand href="/">Ristorante Con Fusion</NavbarBrand>
    <div>Aluno: [Seu Nome]</div>
  </div>
</Navbar>

4- Atualizar o README com as alterações da atividade descrevendo passo a passo do que foi feito:
Incluindo a imagem do resuntado apois o npm start. 


![Texto alternativo](C:\Users\Aluno\Pictures\Screenshots\atv react.png)


5- Subir para o git hub toda a atividade.

