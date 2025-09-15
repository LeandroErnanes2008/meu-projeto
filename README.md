<div id="acessibilidade" class="menu-acessibilidade"> 
        <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao" aria-expanded="false">acessibilidade</button>
        <div id="opcoes-acessibilidade" class="opcoes-acessibilidade apresenta-lista">
                <button id="aumentar-fonte" class="btn btn-primary fw-bold" aria-label="Aumentar o tamanho da fonte">A+</button>
                <button id="diminuir-fonte" class="btn btn-primary fw-bold" aria-label="diminuir o tamanho da fonte">A-</button>
                <button id="alterna-contraste" class="btn btn-primary fw-bold" aria-label="Alterna o contraste de cores"> <i class="bi bi-shadows"></i></button>
        </div>
</div>:root {
    --laranja-claro: #FF862A;
    --alto-contraste-fundo: #000000;
    --alto-contraste-texto: #ffffff;
    --alto-contraste-link: #ffd700;
}.alto-contraste{
    background-color: var(--alto-contraste-fundo);
    color: var(--alto-contraste-texto);
}.alto-contraste header,
.alto-contraste footer,
.alto-contraste .formulario{
    background-color: var(--alto-contraste-fundo);
    color: var(--alto-contraste-texto);
}.alto-contraste .nav-link{
    color: var(--alto-contraste-link);
}.alto-contraste .botao-inicio,
.alto-contraste .formulario button,
.alto-contraste .btn-primary{
    background-color: var(--alto-contraste-link);
    color: var(--alto-contraste-fundo)
}.alto-contraste #tropicalia {
    background: none;
}.alto-contraste #galeria {
    background-color: var(--alto-contraste-fundo);
}.alto-contraste .fundo-galeria {
    background: none;
}<section id="galeria" tabindex="0" aria-label="Seção de galeria de imagens">
        <h2 class="text-center pt-5">Galeria</h2>
        <div class="container p-3 mt-3 fundo-galeria">

            <!-- Código omitido --> 

         </div>
</section>const alternaContraste = document.getElementById('alterna-contraste')alternaContraste.addEventListener('click', function(){
         document.body.classList.toggle('alto-contraste')
 })<div id="acessibilidade" class="menu-acessibilidade">
    <button id="botao-acessibilidade" class="btn btn-primary fw-bold
    rotacao-botao">acessibilidade</button>
    <div id="opcoes-acessibilidade" class="opcoes-acessibilidade apresenta-lista">
        <button id="aumentar-fonte" class="btn btn-primary fw-bold" aria-label="Aumentar
        o tamanho da fonte">A+</button>
        <button id="diminuir-fonte" class="btn btn-primary fw-bold" aria-label="Diminuir
        o tamanho da fonte">A-</button>
        <button id="alterna-contraste" class="btn btn-primary fw-bold"> <i class="bi
        bi-shadows"></i></button>
    </div>
</div><div id="acessibilidade" class="menu-acessibilidade">
    <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao" aria-expanded="false">acessibilidade</button>
</div>const botaoSelecionado = botaoDeAcessibilidade.getAttribute('aria-expanded') === 'true';const botaoSelecionado = botaoDeAcessibilidade.getAttribute('aria-expanded') === 'true';
botaoDeAcessibilidade.setAttribute('aria-expanded', !botaoSelecionado)<script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.js"></script>ScrollReveal().reveal('#inicio', { delay: 500 });ScrollReveal().reveal('#inicio', { delay: 500 });
ScrollReveal().reveal('#tropicalia', { delay: 500 });
ScrollReveal().reveal('#galeria', { delay: 500 });
ScrollReveal().reveal('#contato', { delay: 500 });# Site acessível sobre Tropicália
## Sobre
Refatoração de um site implementando recursos de acessibilidade no HTML, CSS e JS.
## Recursos de acessibilidade
- Atributos aria
- Alt
- Tab-index
- Menu de acessibilidade
## Tecnologias utilizadas
- Bootstrap
- ScrollReveal.js
- HTML
- CSS
- JS
