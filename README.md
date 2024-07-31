<h1> LinkCentral </h1>
<h1 align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/Captura de tela 2024-07-30 180302.png"/>
</h1>
 <a id="sobre"></a>
 <p> LinkCentral é a sua central personalizada de links, onde você pode reunir e divulgar todos os seus conteúdos importantes em uma única página. Com uma interface intuitiva e fácil de usar, o LinkCentral permite que você organize e compartilhe seus perfis de redes sociais, portfólios, blogs, sites favoritos e muito mais. Ideal para influenciadores, criadores de conteúdo, profissionais e qualquer pessoa que deseja ter todos os seus links em um só lugar, facilitando o acesso e a divulgação de suas informações online. </p>

<a name="ancora"></a>
# Tópicos
- [Sobre](#sobre)
- [Como Configurar](#como-configurar)
  - [Pré- Requisitos](#pre-requisitos)
  - [Local Files](#local-files)
- [Tecnologias](#tecnologias)

<a id="como-configurar"></a>
<h2>Como Configurar</h2>
<p>- Como alterar o título da página: Basta mudar o parâmetro da tag "title".</p>
<p>Ex: </p>

```
    <title>Links do Richard</title>
```
<p>* Mude o que está entre as tags</p>

<p>- Editar nome, foto de perfil e o sobre mim:</p>
<p>* Nome: Alterar o parâmetro dentro da tag h1.</p>

```
<h1>Richard Muler</h1>
```
<p>* Foto de perfil: Alterar o parâmetro dentro da tag img.</p>

```
<img src="images/perfil.jpg" alt="Foto de Perfil" id="perfil">
```
<p>* Sobre mim: Alterar o parâmetro dentro da tag p (Caso queira deixá-la em seu tamanho padrão, basta retirar a tag "small").</p>

```
<p id="sobre"><small>ESTUDANTE DE CIÊNCIA DA COMPUTAÇÃO</small></p>
```

<p>- Adicionar ou remover links: Basta utilizas as div`s já criadas.</p>
<p>Ex:</p>

```
<div>
  <a href="https://github.com/rmuler" target="_blank"><img src="images/github.png" alt="Logo do Github">Github</a>
</div>
```
<p>* Após o "href=", basta inserir o link desejado.</p>
<p>* Após o "img src=", basta inserir o link do icon desejado, seja ele hospedado na pasta local ou hospedado em algum site fixo (lembre-se, caso opte pela segunda opção, há risco da imagem cair caso seja retirada se deu link oficial.</p>

<a id="features"></a>

<p>- Adicionar meu currículo para usuários baixarem: Coloque seu arquivo como nome " curriculo " em formato pdf na pasta `archives`.</p>

<a id="pre-requisitos"></a>
<h2>Pré Requisitos</h2>
<p>- Visual Studio Code;</p>
<p>- Hospedagem para seu LinkCentral;</p>
<p>- Domínio para seu LinkCentral (OPCIONAL);</p>

<a id="local-files"></a>
<h2>Local Files</h2>
<p>- Pasta "images": icons armazenados localmente;</p>
<p>- Pasta "archives": curriculo armazenado localmente para download dos usuários;</p>
<p>- index.html: arquivo com a estrutura da página;</p>
<p>- style.css: arquivo com a estilização da página;</p>

<a id="tecnologias"></a>
<h2>Tecnologias Utilizadas</h2>
<p>- HTML5</p>
<p>- CSS3</p>
