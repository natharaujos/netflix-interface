# netflix-interface
Recriando a interface da Netlflix, utilizando HTML, CSS, JavaScript, e alguns plugins JQuery

## Link
<a href="https://natharaujos.github.io/netflix-interface/">Netflix Interface</a>
  <p>
    Aqui está um exemplo de documentação para o Github de um projeto que recria
    a interface da Netflix, utilizando HTML, CSS, JavaScript e alguns plugins
    JQuery:
  </p>
  <h1>Recriando a interface da Netflix</h1>
  <p>
    Este projeto é uma recriação da interface da Netflix, utilizando HTML, CSS,
    JavaScript e alguns plugins JQuery para adicionar funcionalidades à página.
    O objetivo deste projeto é demonstrar habilidades em desenvolvimento web
    front-end, incluindo layout responsivo, animações e interações do usuário.
  </p>
  <h2>Tecnologias utilizadas</h2>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>JQuery</li>
    <li>Owl Carousel (plugin JQuery para slider de carrossel)</li>
    <li>Font Awesome (biblioteca de ícones)</li>
  </ul>
  <h2>Funcionalidades</h2>
  <ul>
    <li>
      Criação de uma página responsiva que reproduz a aparência da interface da
      Netflix.
    </li>
    <li>
      Adição de um slider de carrossel para os destaques da página inicial.
    </li>
    <li>
      Adição de funcionalidades de hover em elementos de conteúdo, como botões
      de play, cartões de filme e de séries.
    </li>
    <li>
      Implementação de uma barra de navegação responsiva com menu dropdown.
    </li>
    <li>
      Adição de ícones da Font Awesome para botões de navegação e outros
      elementos de interface.
    </li>
  </ul>
  <h2>Como rodar o projeto</h2>
  <p>Para rodar o projeto localmente, siga os seguintes passos:</p>
  <ol>
    <li>Clone este repositório para o seu computador.</li>
    <li>Abra o arquivo <code>index.html</code> no seu navegador.</li>
  </ol>
  <h2>Como utilizar o carrossel Owl Carousel</h2>
  <p>
    O Owl Carousel é um plugin JQuery para criação de carrosséis responsivos.
    Para utilizar o Owl Carousel em sua página, você precisa seguir os seguintes
    passos:
  </p>
  <ol>
    <li>
      Instale o plugin Owl Carousel utilizando o comando
      <code>npm install owl.carousel</code>.
    </li>
    <li>Importe os arquivos CSS e JS do Owl Carousel em sua página HTML.</li>
    <li>
      Crie um elemento HTML para o carrossel, como uma div com uma classe
      específica.
    </li>
    <li>
      Inicialize o plugin Owl Carousel em seu script JavaScript, passando as
      opções de configuração, como número de itens por slide, tempo de transição
      e navegação.
    </li>
  </ol>
  <pre><div class="bg-black mb-4 rounded-md"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans"><span class="">javascript</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-javascript">$(<span class="hljs-string">'.owl-carousel'</span>).<span class="hljs-title function_">owlCarousel</span>({
    <span class="hljs-attr">loop</span>:<span class="hljs-literal">true</span>,
    <span class="hljs-attr">margin</span>:<span class="hljs-number">10</span>,
    <span class="hljs-attr">nav</span>:<span class="hljs-literal">true</span>,
    <span class="hljs-attr">responsive</span>:{
        <span class="hljs-number">0</span>:{
            <span class="hljs-attr">items</span>:<span class="hljs-number">1</span>
        },
        <span class="hljs-number">600</span>:{
            <span class="hljs-attr">items</span>:<span class="hljs-number">3</span>
        },
        <span class="hljs-number">1000</span>:{
            <span class="hljs-attr">items</span>:<span class="hljs-number">5</span>
        }
    }
})
</code></div></div></pre>

