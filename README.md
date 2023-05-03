

	

	
	

	

</body>
</html>

<br />
<div align="center">
  <a href="https://github.com/Dizziolica/SuperMariioJs">
    <img src="/dizziolica.jpg" alt="Logo" width="80" height="80">
  </a>




<h1>Ubuntu Desktop Clone</h1>

  <h3 align="center">Ubuntu Desktop Clone</h3>

  <p align="center">
    Super Mario Project
    <br />
    <a href="https://github.com/Dizziolica/UbuntuCopy"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Dizziolica/UbuntuCopy">View Demo</a>
    
   
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Content</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href= "https://github.com/Dizziolica/SuperMariioJs" >Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#tools">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<p>Este projeto é uma cópia do desktop do sistema operacional Linux Ubuntu, recriado utilizando tecnologias web como HTML, CSS e JavaScript. O objetivo deste projeto é criar uma experiência semelhante ao ambiente de trabalho do Ubuntu em um navegador web, permitindo que os usuários possam explorar e interagir com uma versão simulada do sistema operacional.</p>

<h2>Como jogar</h2>
<p>Para utilizar este projeto, basta abrir o arquivo <code>index.html</code> em um navegador web moderno. A partir daí, você poderá explorar o desktop do Ubuntu simulado e interagir com suas funcionalidades.</p>

<h2>Funcionalidades</h2>

<ul>
<li>Barra de tarefas na parte superior da tela, com um menu de aplicativos e notificações do sistema.</li>
<li>Área de trabalho com ícones de aplicativos e arquivos.</li>
		
	
</ul>
<pre><code>

let sidebar = document.querySelector(".sidebar");
  let closeBtn = document.querySelector("#btn");
  let searchBtn = document.querySelector(".bx-search");

let mailBtn = document.querySelector(".email-section")
  closeBtn.addEventListener("click", ()=>{
    sidebar.classList.toggle("open");
    menuBtnChange();//calling the function(optional)
  });
</code></pre>
<p>Este código cria a variavel closeBtn que regasta do html o id= <code> btn</code>, que é adicionado a um event listener para o evento "click" no elemento closeBtn usando a função addEventListener(). Quando o evento ocorre, a classe open é alternada na lista de classes do elemento sidebar usando a função classList.toggle(), o que permite abrir ou fechar a barra lateral (dependendo do seu estado atual)</p>
<h2>Instalação</h2>
<p>Para executar a pagina localmente, siga as instruções abaixo:</p>
<ol>
  <li>Clone este repositório: <code>git clone https://github.com/Dizziolica/UbuntoCopy.git</code></li>
  <li>Abra o arquivo <code>index.html</code> em seu navegador da web.</li>
  
</ol>
<h2>Contribuição</h2>
<p>Sinta-se à vontade para contribuir com este projeto criando um pull request. Se você encontrar algum bug ou problema, por favor, crie uma issue.</p>
<h2>Créditos</h2>
<p> Este projeto foi inspirado no Linux Ubuntu. As imagens utilizadas neste projeto estão presente no repositorio .</p>
<h2>Licença</h2>


![](https://github.com/Dizziolica/UbuntuCopy/blob/main/UbuntuCopy.gif)

