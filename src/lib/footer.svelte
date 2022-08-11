<script>
    const date = new Date().getFullYear();
</script>

<footer>
    <div class="logo">
        <a href="/#index.html">
        <img src="/logo-white.png" class="logo-ls" alt="logo da empresa"></a>
    </div>
    <p>Quer cadastrar seu negócio ? Não perca tempo, fale conosco, atendemos das 08:00 ás 21hrs de seg a sex</p>
    <div class="cta">
        <a class="zap" href="https://wa.me/message/XMHETKBM2C55O1" target="_blank" rel="noopener noreferrer">Whatsapp</a>
        <a class="tele" href="https://t.me/laurensoft" target="_blank" rel="noopener noreferrer">Telegram</a>
    </div>
    <address> 93 9 8447-8357</address>
    <address> Anapu - PA</address>
    <div class="enterprise">
        <p>Laurensoft Serviços em Tecnologia da Informação LTDA</p>
        <small>CNPJ 42.741.786/0001-48</small>
    </div>
    <div class="rights">copyright {date}</div>
</footer>

<style>
    footer{
        font-family: "Brush Script MT", cursive;
        font-size: 1.6rem; /* 14 / 10 = 1.4 */
        text-align: center;
        display: flex;
        flex-direction: column;
        background-color: black;
        color: white;
    }
    .logo {
            display: flex;
            justify-content: center;
    }
    .logo-ls {
        width: 25vw;
        margin-bottom: 1rem;
    }
    footer p {
        font-family: "Brush Script MT", cursive;
        font-size: 1.6rem; /* 14 / 10 = 1.4 */
        text-align: center;
    }
    .cta {
        display: flex;
        justify-content: space-evenly;
        background-color: azure;
        /* max-width: 70vw; */
        /* background: linear-gradient(to bottom right, #d94545, #d96f45); */

        font-family: Verdana, Geneva, Tahoma, sans-serif;
        font-size: 1rem;
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
    .tele {
        background-color: #405de6;
    }
    .enterprise  > p, small {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        font-size: 1rem;
        margin: 0;
    }    
    .rights {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        font-size: 1rem;
        margin-bottom: .5rem;
        color: whitesmoke;
        background-color: black;

        display: flex;
        justify-content: center;
    }
</style>