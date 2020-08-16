# README-Model

Referêncas, Markdown, Icons para deizar se arquivo README,md legal.


<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" style="object-fit: cover; width:250px; height:250px;" src=".github/nlw.gif"  />
</h1>

<h2 align="center">
  <img src="https://img.shields.io/badge/Next%20Level%20Week-%232-blue?style=for-the-badge" alt="Nome e edição do evento" />
  <img src="https://img.shields.io/badge/web%3F-ok-blue?style=for-the-badge" alt="Sistema web Ok" />
  <img src="https://img.shields.io/badge/server%3F-ok-blue?style=for-the-badge" alt="Server Ok" />
  <img src="https://img.shields.io/badge/Mobile-OK-blue?style=for-the-badge" alt="Aplicativo mobile Ok" />
  <img src="https://img.shields.io/github/license/matheusfelipeog/proffy?color=blue&style=for-the-badge" alt="License" />
</h2>

## 👅 Línguas

- [README in English](README-EN.md)
- [README in German/Deustch](README-DE.md)
- [README in Japanese](README-JA.md)


## Ícones

- [Ícones](gistfile1.md)

## 📌 Index
<p align="center">
  <a href="#-sobre-o-projeto">Sobre o Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-issues">Issues</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-contribuições">Contribuições</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a> 
</p>

## 📌 Index em Arquivos
* [Sobre o projeto](#sobre-o-projeto)
* [Motivo](#motivo)
    *  [Utilitários](#utilitários)
    *  [Funcionalidades](#funcionalidades)
- [Screenshots](#screenshots)

## ❔ Sobre o projeto

Durante o evento Next Level Week #2, 

## 🧐 Motivo

Desenvolvimento do projet

### ***Utilitários***

- Protótipo: **[Figma](https://www.figma.com/)** &rarr; **<kbd>[Protótipo (Proffy)](https://www.figma.com/file/GHGS126t7WYjnPZdRKChJF/Proffy-Web/duplicate)</kbd>**

| Dia | Descriçao | tecnologias |
|:---:|---------|:-----------:|
|  03/08  |Acelerando sua evolução| ![npm](https://img.shields.io/npm/v/react?color=black&label=React&logo=react)  ![npm](https://img.shields.io/npm/v/typescript?color=black&label=Typescript&logo=typescript&logoColor=blue) |
|  **05/08**  |**A escolha da stack**|    ![npm](https://img.shields.io/npm/v/axios?color=black&label=Axios&logo=insomnia&logoColor=purple)   ![npm](https://img.shields.io/npm/v/sqlite3?color=black&label=Sqlite3&logo=sqlite&logoColor=Blue)       |
|  **07/08**  |**A milha extra**|             |


### Funcionalidades

#### Aula 1: Tema
- [x] Criando estrutura da landing page
- [ ] Estilizando landing page
- [ ] Autenticação
  - [x] Login / Logout 
  - [x] Permanecer logado - Token

[Detalhes](Aula03.md)


## 📸 Screenshots

### Web Responsive Interface
<p align="center">
  <img src=".github/appweb.gif" alt="Preferâencia por GIF" width="100%" />
</p>


## Citações

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be

### H1 Header (Underline)
=============

### H2 Header (Underline)
-------------

### Characters
                
----

~~Strikethrough~~ <s>Strikethrough (when enable html tag decode.)</s>
*Italic*      _Italic_
**Emphasis**  __Emphasis__
***Emphasis Italic*** ___Emphasis Italic___

Superscript: X<sub>2</sub>，Subscript: O<sup>2</sup>

### Code Blocks (Indented style)

Indented 4 spaces, like `<pre>` (Preformatted Text).

    <?php
        echo "Hello world!";
    ?>
    
Code Blocks (Preformatted text):

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |


### HTML code

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

### HTML entities

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot; 

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

### Escaping for Special Characters

\*literal asterisks\*

            
### TeX(LaTeX)
   
$$E=mc^2$$

Inline $$E=mc^2$$ Inline，Inline $$E=mc^2$$ Inline。

$$\(\sqrt{3x-1}+(1+x)^2\)$$
                    
$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$
                
                
### FlowChart

```flow
st=>start: Login
op=>operation: Login operation
cond=>condition: Successful Yes or No?
e=>end: To admin

st->op->cond
cond(yes)->e
cond(no)->op
```

### Sequence Diagram
                    
```seq
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

### End

## ⚙ Instalação e Start

### Comandos para instalar no MAC

| Tecnologia | Versão | Comando para instalar |
|:----------|------|---------------------|
|NodeJS| 12.18.2| ``` brew install node ``` |
|Yarn  |  1.17.3 | ```npm install -g yarn``` |
|Expo  |  3.23.1 |  ```yarn add global expo-cli```|

### Clonagem

Primeiro, clone o repositório para seu ambiente:

```bash
> git clone https://github.com/shyoutarou/proffy.git 
```

Depois, entre no repositório clonado e no diretório correspondente ao que quer testar (web, server).
Logo após, insira os seguintes comandos no seu terminal para cada diretório respectivamente:

### 📦 Executar Server API REST

```bash
# Entra no diretório "server"
> cd ./proffy/server

# Instala todas as dependências
> yarn install or npm install

```

## 🐛 Issues

Sinta-se à vontade para registrar um novo problema com o respectivo título e descrição no repositório Proffy. Se você já encontrou uma solução para seu problema, adoraria revisar sua solicitação de pull!

## 🤝 Contribuições

Siga os passos abaixo para contribuir:

1. Faça o *fork* do projeto (<https://github.com/shyoutarou/REPO.git>)

2. Clone o seu *fork* para sua maquína (`git clone https://github.com/user_name/REPO.git`)

3. Crie uma *branch* para realizar sua modificação (`git checkout -b feature/name_new_feature`)

4. Adicione suas modificações e faça o *commit* (`git commit -m "Descreva sua modificação"`)

5. *Push* (`git push origin feature/name_new_feature`)

6. Crie um novo *Pull Request*

7. Pronto, agora só aguardar a análise 🚀 

## ***:star2: AGRADECIMENTOS***

<div align=center>
  <table style="width:100%">
    <tr align=center>
      <th><strong>Rocketseat</strong></th>
      <th><strong>diego3g</strong></th>
    </tr>
    <tr align=center>
      <td>
        <a href="https://rocketseat.com.br/">
          <img width="200" height="180" src="https://user-images.githubusercontent.com/38081852/83981650-1e2e6680-a8f6-11ea-9f42-6df8fe809e4b.png">
        </a>
      </td>
      <td>
        <a href="https://github.com/diego3g">
          <img width="200" height="180" src="https://user-images.githubusercontent.com/38081852/83981712-b7f61380-a8f6-11ea-9099-bd3677e97e39.jpg">
        </a>
      </td>
    </tr>
  </table>
</div>

## ***:books: REFERÊNCIAS***

* MarkDown
    - [Editor.md](https://pandao.github.io/editor.md/en.html)
    - [Dillinger](https://dillinger.io/)
    - [Stackedit](https://stackedit.io/) 

- [Iniciando com React Native: Navegação e Autenticação com JWT](https://blog.rocketseat.com.br/react-native-autenticacao/)
- [Tipos de navegação no React Native](https://blog.rocketseat.com.br/navegacao-react-native/)
- [How I set up React and Node with JSON Web Token for Authentication](https://medium.com/@romanchvalbo/how-i-set-up-react-and-node-with-json-web-token-for-authentication-259ec1a90352)
- [React (without Redux) - JWT Authentication Tutorial & Example](https://jasonwatmore.com/post/2019/04/06/react-jwt-authentication-tutorial-example)
- [Scroll infinito no React Native](https://blog.rocketseat.com.br/scroll-infinito-no-react-native/)
- [Deploy NLW](https://www.notion.so/Deploy-NLW-56f2a980c20e41d6b1dd22a4d1348e6e)

## 📜 License

O projeto publicado em 2020 sobre a licença [MIT](./LICENSE) ❤️ 

Made with ❤️ by Shyoutarou

Gostou? Deixe uma estrelinha para ajudar o projeto ⭐


- [Voltar ao Início](#Index)