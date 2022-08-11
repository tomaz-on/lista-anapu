<!-- <script>
    let hidden = true;
</script> -->

<header>
    <div class="logo">
        <a href="/#index.html">
        <img src="/logo.png" class="logo-ls" alt="logo da empresa">
        </a>
    </div>
    <h1>Laurensoft Apresenta</h1>
    <h2>Lista Anapu</h2>
    <!-- <div class="button">
        <button on:click={() => {hidden = !hidden}} aria-controls="content" aria-expanded={!hidden}>
        Segmentos
        </button>
    </div> -->
    
    <!-- <div id="content" {hidden}>
        <nav>
            <a href="/nav-links/acougues" rel="noopener noreferrer" sveltekit:prefetch>açougues</a>
            <a href="/nav-links/agropecuarias" rel="noopener noreferrer">agropecuárias</a>
            <a href="/nav-links/barbearias" rel="noopener noreferrer">barbearia</a>
            <a href="/nav-links/design-graficas" rel="noopener noreferrer" >design / gráfica</a>
            <a href="/nav-links/distri-agua-gas" rel="noopener noreferrer">distrib. água / gás</a>
            <a href="/nav-links/distri-bebidas" rel="noopener noreferrer">distrib. bebidas</a>
            <a href="/nav-links/eletricas" rel="noopener noreferrer">elétrica</a>
            <a href="/nav-links/espaco-mulher" rel="noopener noreferrer">espaço-mulher</a>
            <a href="/nav-links/farmacias" rel="noopener noreferrer">farmácias</a>
            <a href="/nav-links/informatica" rel="noopener noreferrer">informática</a>
            <a href="/nav-links/lanches" rel="noopener noreferrer">lanches</a>
            <a href="/nav-links/lo-celulares" rel="noopener noreferrer">lojas celulares</a>
            <a href="/nav-links/lo-importados" rel="noopener noreferrer">lojas importados</a>
            <a href="/nav-links/lo-presentes" rel="noopener noreferrer">lojas presente</a>
            <a href="/nav-links/lo-variedades" rel="noopener noreferrer">lojas variedades</a>
            <a href="/nav-links/malharias" rel="noopener noreferrer">malharias</a>
            <a href="/nav-links/mercados" rel="noopener noreferrer">mercados</a>
            <a href="/nav-links/metalurgicas" rel="noopen noreferrer">metalúrgicas</a>
            <a href="/nav-links/motores" rel="noopener noreferrer">motores</a>
            <a href="/nav-links/mototaxi" rel="noopener noreferrer">mototaxi</a>
            <a href="/nav-links/o-motos" rel="noopener noreferrer">oficinas moto</a>
            <a href="/nav-links/oticas" rel="noopener noreferrer" sveltekit:prefetch>óticas</a>
            <a href="/nav-links/papelarias" rel="noopener noreferrer">papelarias</a>
            <a href="/nav-links/peixarias" rel="noopener noreferrer">peixarias</a>
            <a href="//nav-links/refrigeracao" rel="noopener noreferrer" target="_blank">refrigerações</a>
            <a href="/nav-links/restaurantes" rel="noopener noreferrer">restaurantes</a>
            <a href="/nav-links/sorveterias" rel="noopener noreferrer">sorveterias</a>
        </nav>
    </div> -->
</header>


<!-- ------- STYLES ------- -->
<style>
    header {
        background-color: aquamarine;
        padding: 15px;
    }
    
    header .logo {
        display: flex;
        justify-content: center;
    }
    .logo-ls {
        width: 25vw;
        margin-bottom: 1rem;
    }

    header > h1 {
        margin: 0;
        font-family: "Brush Script MT", cursive;
        font-size: 2.6rem; /* 14 / 10 = 1.4 */
        text-align: center;
        text-decoration:overline;
    }
    
    header > h2 {
        text-align: center;
        text-transform: uppercase;
        margin-bottom: 0;
    }

    /* #content > nav {
        margin-top: .9rem;
        background-color: burlywood;
    }

    .button {
        display: flex;
        justify-content: center;
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
        background-color: #4CAF50;
        border: none;
        border-radius: 15px;
        box-shadow: 0 9px #999;
    }
    .button > button:hover {
        background-color: #3e8e41;
    }
    .button > button:active {
        background-color: #3e8e41;
        box-shadow: 0 5px #666;
        transform: translateY(4px);
    }

    nav {

        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(17rem, 1fr));
        gap: 1rem;
        justify-items: center;
        align-items: center;
        text-align: center;

    }
    nav a {
        text-decoration: none;

        background-color: whitesmoke;
        color: #d96f45;
        padding: .3rem 1.5rem;
        border: 5px solid #3f72af;
        border-radius: 30px;
        text-decoration: none;
        text-transform: uppercase;

        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: 1.2rem;
        font-style: italic;
        font-weight: bold;
        text-decoration: none;
        background: linear-gradient(to bottom right, #48cae4, #ade8f4);
        transition: all .25s linear;
        border: 3px solid #fff;
        border-radius: 30px;
        width: 100%;
    }
    nav a:hover {
        background: linear-gradient(to bottom right, #f86d6d, #f88e6d);
        color: #fff;
        box-shadow: 0 12px 24px rgba(0,0,0,0.5);
    }
    nav a:focus {
        background: #ad3636;
        box-shadow: 0 6px 12px rgba(0,0,0,0.5);
    }
    nav a:active {
        background: #d94545;
    } */

</style>