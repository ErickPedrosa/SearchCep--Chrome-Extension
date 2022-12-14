
<img src="https://img.shields.io/static/v1?label=Status&message=Finished&color=FFCB05&style=lat-square&logo=GoogleChrome"/> <img src="https://img.shields.io/static/v1?label=Version&message=v1.0&color=FF3333&style=lat-square&logo=GoogleChrome"/> <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=33DD33&style=lat-square&logo=GoogleChrome"/>    

<br>

<h1 align="center">
    <a href="https://erickpedrosa.github.io/SearchCep--Chrome-Extension/">🔗 Search Cep - Google Chrome Extension</a>
</h1>

<p align="center">Uma extensão do google chrome que permite que o usuário busque o endereço relacionado a um determinado CEP.</p>    

<br>
<br>

<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#desenvolvimento">Desenvolvimento</a> •
 <a href="#status">Status do Projeto</a> •
 <a href="#status">Pré-requisitos</a> •
 <a href="#status">Instalação</a> •
 <a href="#funcionamento">Features</a> • 
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#autor">Autor</a> 
</p>

<br>
<br>

<h2 id="objetivo">Objetivos</h2>
<p>Esse projeto foi desenvolvido para uso de aprendizagem sobre extensões do chrome e sobre a utilização de API's.</p>
<p><a href="https://developer.chrome.com/docs/extensions/" target="_blank">Link da documentação do Google Chrome sobre as extensões</a></p>
<p><a href="https://viacep.com.br/" target="_blank">Link da API utilizada</a></p>
<br>

<p>Estava decido a fazer uma extensão para que pudesse aprender como criá-la, porém não consegui ter nenhuma ideia sobre o qual tipo de extensão faria. Foi quando descobri a API Viacep, então decidi fazer uma pequena extensão que devolvia os endereços ao procurar por um cep. </p>
<br>


<br>
<br>

<h2 class="desenvolvimento">Desenvolvimento</h2>
<h3>Versão v1.0</h3>
<p>Para iniciar o projeto fiz um manifest.json, que é o arquivo que configura a extensão, o arquivo contém toda as informações necessárias para que a extensão funcione corretamente como nome da extensão, descrição, versão, permissões, entre outros.</p>
<p>Logo após isso comecei fazendo um html e css bem simples já que o foco da minha aplicação não é em seu design, mas em sua funcionalidade.</p>
<p>Então preparei-me para iniciar o JavaScript, começando pela função responsável por se comunicar com a API recebendo um cep como parâmetro e retornando um objeto. Logo após essa função criei a função que iria renderizar o endereço encontrado na tela, essa recebia como parâmetro um cep e internamente chamava a primeira para converté-lo em um objeto contendo o endereço que posteriormente será renderizado pela função. </p>
<br>

<br>
<br>

<h2 id="status">Status do Projeto</h2>
<p>O projeto se encontra concluído e está atualmente na sua versão 1.0.</p>

<br>
<br>

<h2 id="status">Pré-requisitos</h2>
<ul>
    <li>Google Chrome devidamente baixado e instalado em sua máquina.</li>
    <li>Acesso a internet (tanto para a instalação quanto para a conexão com a API)</li>
    <li></li>
</ul>

<br>
<br>

<h2 id="status">Instalação</h2>
<p>O projeto se encontra concluído e está atualmente na sua versão 1.0.</p>

<br>
<br>

<h2 id="funcionamento">Funcionamento</h2>
<p>O projeto é bem simples e de fácil utilização, as principais funcionalidades implementadas são:</p>
<ul>
    <li>Renderizar o pokémon</li>
    <li>Navegar para o anterior e o próximo pokémon</li>
    <li>Buscar um pokémon</li>
</ul>
<br>

<h3>Renderizar o pokémon</h3>
<p>A principal função da pokédex é mostrar o pokémon e suas características na tela, as características renderizadas pelo projeto são:</p>
<h4>* Nome do pokémon *</h4>
<h4>* Núm. do pokémon ou ID do pokémon *</h4>
<h4>* Tipo do pokémon *</h4>
<h4>* Altura (Height) *</h4>
<h4>* Peso (Weight) *</h4>
<h4>* Abilidades do pokémon *</h4>
<h4>* Tipos que o pokémon é fraco contra *</h4>
<h4>* Tipos que o pokémon tem vantagem contra *</h4>
<br>

<h3>Navegar para o anterior e o próximo pokémon</h3>
<p>Utilizando das setas no canto superior da tela é possível navegar para o próximo/anterior pokémon. A seta superior direita leva ao próximo pokémon, enquanto a seta superior esquerda leva ao pokemon anterior.</p>
<br>

<h3>Buscar um pokémon</h3>
<p>Ao clicar no ícone de busca uma caixa de pesquisa surge permitindo que você procure por um pokémon específico. A busca pode ocorrer por meio do nome do pokémon ou então pelo id.</p>

<br>
<br>

<h2 id="tecnologias">Tecnologias</h2>
<h3>As seguintes ferramentas foram usadas na construção do projeto:</h3>


<h4>Linguagens</h4>
<p><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML">HTML</a></p>
<p><a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript">JavaScript</a></p>
<p><a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS">CSS</a></p>
<br>

<h4>API's</h4>
<a href="https://pokeapi.co/">PokeAPI</a>
<br>

<h4>Referências</h4>
<a href="https://www.youtube.com/watch?v=SjtdH3dWLa8">Vídeo do Manual do Dev</a>

<br>
<br>
<br>

<h2 id="autor">Autor</h2>

<a href="https://github.com/ErickPedrosa/">
    <img style="border-radius: 100%; " src="https://avatars.githubusercontent.com/u/84411590?v=4" width="100px;" alt=""/>
    <br>
    <sub><strong>Erick Pedrosa</strong></sub>
</a> 

<a href="https://github.com/ErickPedrosa/" title="Rocketseat">🚀</a>

<br>
<br>

<!--[![Twitter Badge](https://img.shields.io/badge/-@tgmarinho-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/tgmarinho)](https://twitter.com/tgmarinho) -->

[![Linkedin Badge](https://img.shields.io/badge/-Erick-Pedrosa?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/erickpedrosabarreto/)](https://www.linkedin.com/in/erickpedrosabarreto/) 
[![Gmail Badge](https://img.shields.io/badge/-erick.pedrosa.b@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:erick.pedrosa.b@gmail.com)](mailto:erick.pedrosa.b@gmail.com)