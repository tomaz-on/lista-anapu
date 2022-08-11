<script>
    let hidden = true;
</script>

<h1>Óticas</h1>
<!-- ----- FIRST CLIENT ----- -->
<h2>ótica central</h2>
<img src="/src/lib/img-nav/o-central.webp" alt="imagem do estabelecimento">
<div class="info">
    <p class="card-line">segmento: óculos de sol, óculos de grau, lentes, relógios</p>
    <h3>horário de funcionamento</h3>
    <p>08:00 às 18:00 seg-sex</p>
    <p>08:00 às 13:00 sábados</p>
    <p>faz entrega: sim</p>
    <p>máquina de cartão: sim</p>
    <p class="important">chave PIX: 93 9 8400-7989</p>
    <p class="important">(91) 9 9174-8278</p>
    <div class="socials">
        <a class="zap" href="https://api.whatsapp.com/send?1=pt_BR&phone=5591991748278" target="_blank" rel="noopener noreferrer">whatsapp</a>
        <a class="insta" href="https://www.instagram.com/oticacentralanapu/" target="_blank" rel="noopener noreferrer">instagram</a>
    </div>
</div>
<div class="button">
    <button on:click={() => {hidden = !hidden}} aria-controls="content" aria-expanded={!hidden}>
    Consulta e Ofertas
    </button>
</div>
<div id="content" {hidden}>
    <div class="marketing">
        <h3>Consulta dia 17/08 próxima quarta-feira, agende conosco e já marque a sua consulta</h3>
    </div>
</div>

<!-- ------- STYLE CSS ------- -->
<style>
h1 {
    text-align: center;
    background-color:burlywood;
}
h2 {
    text-align: center;
    text-transform: uppercase;
    background: linear-gradient(to bottom right, #d94545, #d96f45);

    border-radius: 15px;
    /* border-width: 5px; */
    /* margin-left: 7rem; */
    /* margin-right: 7rem;  */
}
img {
    display: block;
    width: 100%;
    align-self: center;
    justify-self: center;
}

.info {
    font-family: "Brush Script MT", cursive;
    font-size: 1.6rem; /* 14 / 10 = 1.4 */
    text-align: center;
}
.card-line {
    padding: .3rem;

    font-size: 1.6rem; /* 14 / 10 = 1.4 */
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    line-height: 2.4rem;
    font-style: italic;
    font-weight: bold;
    
    background: linear-gradient(to bottom right, #d94545, #d96f45);
    box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px, rgba(10, 37, 64, 0.35) 0px -2px 6px 0px inset;
    border-radius: 1rem;
}
.info > .important {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.socials {
    display: flex;
    justify-content: space-evenly;
    /* max-width: 70vw; */
    background: linear-gradient(to bottom right, #d94545, #d96f45);

    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 1.6rem;
    font-weight: 300;
    text-decoration: none;
    text-transform: uppercase;
    transition: all .25s linear;
    color: #fff;
    line-height: 1.6;
    border: .4rem solid crimson;
}

a {
    text-decoration: none;
    color: darkred;

    border: 3px solid white;

    
    border-right: 4px solid white;
    padding: 0 3rem;
}

.zap {
    background-color: green;
}
.insta {
    background-color: #405de6;
}

.button {
        display: flex;
        justify-content: center;

        margin: .7rem 0;
    }
    .button > button {
        display: inline-block;
        padding: 15px 25px;
        font-size: 24px;
        cursor: pointer;
        text-align: center;
        text-decoration: none;
        outline: none;
        color: #fff;
        background-color:#405de6;
        border: none;
        border-radius: 15px;
        box-shadow: 0 9px darkgray;
    }
    .button > button:hover {
        background-color:brown;
        box-shadow: 0 9px #666;

    }
    .button > button:active {
        background-color: #3e8e41;
        box-shadow: 0 5px #666;
        transform: translateY(4px);
    }

    #content > .marketing {
        text-align: center;

        background: linear-gradient(to bottom right, #d94545, #d96f45);
        box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px, rgba(10, 37, 64, 0.35) 0px -2px 6px 0px inset;
        border-radius: 1rem;
    }

    /* ------- MEDIA QUERIES SECTION ------- */

    @media screen and (min-width: 800px) {
    .info {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 2rem;
    }
    img {
        display: flex;
        flex-direction: column;
        align-self: center;
        width: 50vw;
        margin-left: 20vw;
        margin-right: 20vw;
    }    
}
</style>