index.htmnl


<html lang="pt-BR"></html>

<head>
    <link rel="Stylesheet" href="Styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>Aluraflix</title>
</head>

<body>
    <header>Volleyball Tube</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>BRASIL 3 X 0 JAPÃO | MELHORES MOMENTOS | VÔLEI | OLIMPÍADAS 2024</h1>
            <p>#brasilnasolímpiadas</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/msVi9N-vGRg?si=vXBfdFp8wcXNOGcI"
             title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
            referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

    <section class="categoria">
        <h2>Outros vídeos</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=yxfybf6WKYA">
                <img src="https://img.youtube.com/vi/yxfybf6WKYA/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=Pb48J-Wxxrw">
                <img src="https://img.youtube.com/vi/Pb48J-Wxxrw/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=c9zk56CpjQs">
                <img src="https://img.youtube.com/vi/c9zk56CpjQs/maxresdefault.jpg" />
            </a>
        </div>
    </section>

</body>

</html>


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Styles.css

body {
    color: white;
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
    }
    
    header {
    border-bottom: solid 2px rgb(255, 0, 0);
    padding: 20px;
    font-size: 32px;
    color: rgb(255, 0, 0);
    }
    
    .chamada {
    background: rgb(0, 0, 0);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
    }
    
    .chamada-texto {
    margin-right: 5%;
    }
    
    h1 {
    font-size: 40px;
    }
    
    p {
    font-size: 20px;
    }
    
    .categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
    }
    
    .categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
    }
    
    .categoria-videos img {
    opacity: 0.5;
    height: 200px;
    }
    
    .categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
    }
    
    .categoria h2 {
    color: rgb(255, 0, 0);
    }
