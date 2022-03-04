<template>
<div class="master">

        <header class="header">
            <span class="legenda">Selecionar Voz: </span>
            <select id="listaDeVozes"></select>   
        </header>

        <div class="conteudo">

            <h1 class="titulo">Tabela periotica referte aos elementos</h1>
            
            <div class="d-flex">
                <div id="bt-html" class="mini-card verde">html</div>
                <div class="espacador"></div>
                <div class="mini-card laranja">col</div>
                <div class="mini-card laranja">table</div>
            </div>
            
            <div class="d-flex">
                <div class="mini-card azul">head</div>
                <div class="mini-card amarelo">span</div>
                <div class="espacador"></div>
                <div class="mini-card laranja">div</div>
                <div class="mini-card verde">fieldset</div>
                <div class="mini-card verde">form</div>
                <div class="mini-card azul">body</div>
                <div class="mini-card azul">h1</div>
                <div class="mini-card azul">section</div>
                <div class="mini-card laranja">colgroup</div>
                <div class="mini-card laranja">tr</div>   
            </div>
    
            <div class="d-flex">
                <div class="mini-card azul">title</div>
                <div class="mini-card amarelo">a</div>
                <div class="espacador"></div>
                <div class="mini-card laranja">pre</div>
                <div class="mini-card verde">meter</div>
                <div class="mini-card verde">select</div>
                <div class="mini-card azul">aside</div>
                <div class="mini-card azul">h2</div>
                <div class="mini-card azul">header</div>
                <div class="mini-card laranja">caption</div>
                <div class="mini-card laranja">td</div>
            </div>

            <div class="d-flex">
                <div class="mini-card azul">meta</div>
                <div class="mini-card amarelo">rt</div>
                <div class="mini-card amarelo">dfn</div>
                <div class="mini-card amarelo">em</div>
                <div class="mini-card amarelo">i</div>
                <div class="mini-card amarelo">smal</div>
                <div class="mini-card amarelo">ins</div>
                <div class="mini-card amarelo">s</div>
                <div class="mini-card laranja">br</div>
                <div class="mini-card laranja">p</div>
                <div class="mini-card laranja">blockquote</div>
                <div class="espacador"></div>
                <div class="mini-card verde">legend</div>
                <div class="mini-card verde">optgroup</div>
                <div class="mini-card azul">address</div>
                <div class="mini-card azul">h3</div>
                <div class="mini-card azul">nav</div>
                <div class="mini-card branco">menu</div>
                <div class="mini-card laranja">th</div>
            </div>
            
            <div class="d-flex">
                <div class="mini-card azul">base</div>
                <div class="mini-card amarelo">rp</div>
                <div class="mini-card amarelo">abbr</div>
                <div class="mini-card amarelo">time</div>
                <div class="mini-card amarelo">b</div>
                <div class="mini-card amarelo">strong</div>
                <div class="mini-card amarelo">del</div>
                <div class="mini-card amarelo">kbd</div>
                <div class="mini-card laranja">hr</div>
                <div class="mini-card laranja">ol</div>
                <div class="mini-card laranja">dl</div>
                <div class="mini-card verde">label</div>
                <div class="mini-card verde">option</div>
                <div class="mini-card verde">details</div>
                <div class="mini-card azul">h4</div>
                <div class="mini-card azul">article</div>
                <div class="mini-card branco">command</div>
                <div class="mini-card laranja">tbody</div>
            </div>
    
            <div class="d-flex">
                <div class="mini-card azul">link</div>
                <div class="mini-card azul">noscript</div>
                <div class="mini-card amarelo">q</div>
                <div class="mini-card amarelo">var</div>
                <div class="mini-card amarelo">sub</div>
                <div class="mini-card amarelo">mark</div>
                <div class="mini-card amarelo">bdi</div>
                <div class="mini-card amarelo">wbr</div>
                <div class="mini-card laranja">figcaption</div>
                <div class="mini-card laranja">ul</div>
                <div class="mini-card laranja">dt</div>
                <div class="mini-card verde">input</div>
                <div class="mini-card verde">output</div>
                <div class="mini-card verde">keygen</div>
                <div class="mini-card azul">h5</div>
                <div class="mini-card azul">footer</div>
                <div class="mini-card branco">summary</div>
                <div class="mini-card laranja">thead</div>
            </div>

            <div class="d-flex">
                <div class="mini-card azul">style</div>
                <div class="mini-card azul">script</div>
                <div class="mini-card amarelo">cite</div>
                <div class="mini-card amarelo">samp</div>
                <div class="mini-card amarelo">sup</div>
                <div class="mini-card amarelo">ruby</div>
                <div class="mini-card amarelo">bdo</div>
                <div class="mini-card amarelo">code</div>
                <div class="mini-card laranja">figure</div>
                <div class="mini-card laranja">li</div>
                <div class="mini-card laranja">dd</div>
                <div class="mini-card verde">textarea</div>
                <div class="mini-card verde">button</div>
                <div class="mini-card verde">progress</div>
                <div class="mini-card azul">h6</div>
                <div class="mini-card azul">hgroup</div>
                <div class="mini-card branco">details</div>
                <div class="mini-card laranja">tfoot</div>
            </div>
    
            <div class="d-flex mt">            
                <div class="espacador"></div>
                <div class="mini-card rosa">img</div>
                <div class="mini-card rosa">area</div>
                <div class="mini-card rosa">map</div>
                <div class="mini-card rosa">embed</div>
                <div class="mini-card rosa">object</div>
                <div class="mini-card rosa">param</div>
                <div class="mini-card rosa">source</div>
                <div class="mini-card rosa">iframe</div>
                <div class="mini-card rosa">canvas</div>
                <div class="mini-card rosa">tr</div>
                <div class="mini-card rosa">audio</div>
                <div class="mini-card rosa">video</div>
            </div>
            
        </div>

    </div>
  
</template>

<script>
export default {

}
</script>

<style>
.header {
    background-color: black;
    position: fixed;
    top: 0px;
    left: 0px;
    right: 0px;
    
}

.legenda {
    color: aliceblue;
}

.master {
    background-image: url("../assets/imgFundo.jpg");
    position: fixed;
    top: 0px;
    left: 0px;
    right: 0px;
    bottom: 0;
}

.cabecario {
    font-family: initial;
    color: rgb(255, 6, 6);
    text-align: center;
}

.titulo {
    font-family: initial;
    text-align: center;
    color: seashell;
}

.conteudo  {
    padding: 0 30px;
}

.verde {
    background-color: rgb(25, 153, 25);
}

.verde:hover {
    background-color: rgb(6, 117, 6);
}

.azul {
    background-color: rgb(47, 47, 218);
}

.azul:hover {
    background-color: rgb(30, 30, 170);
}

.amarelo {
    background-color: rgb(233, 233, 38);
}

.amarelo:hover {
    background-color: rgb(184, 184, 55);
}

.laranja {
    background-color: rgba(248, 64, 18, 0.849);
}

.laranja:hover {
    background-color: rgba(179, 77, 51, 0.849);
}

.rosa {
    background-color: orchid;
}

.rosa:hover {
    background-color: rgb(158, 91, 156);
}

.branco {
    background-color: rgb(255, 251, 251);
}

.branco:hover {
    background-color: rgb(148, 148, 148);
}

.mini-card {
    width: 5%;
    height: 65px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 4px;
    font-family: none;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;
    box-shadow: -1px 0px 2px 0px rgb(207 204 198 / 58%);
}

.d-flex {
    display: flex;
}

.espacador {
    margin-inline-start: auto;
}

.mt {
    margin-top: 50px;
}
</style>