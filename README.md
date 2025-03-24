<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <title>Tropicália</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class=" p-5">

        <nav class="container d-flex justify-content-between align-items-center" >
            <img src="img/logo.png" class="nav-img " loading="lazy">
            <ul class="nav mt-5">
                <li class="nav-item"><a class="nav-link" href="#inicio">Início</a></li>
                <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li>
                <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
            </ul>
            
        </nav>
       
    </header>


    <main class="container my-5">

        <section id="inicio" class="my-5">
            <div class="inicio-fundo d-flex justify-content-between align-items-center">
                <div class="esquerda-conteudo">
                    <h1 class="display-4 text-white fst-italic fw-bold">Boas-vindas a</h1>
                    <img src="img/logo-2.png" class="mb-3" width="563"
                        height="278" loading="lazy">
                    <a href="#tropicalia"
                        class="btn btn-primary btn-lg botao-inicio fw-semibold">Quero
                        conhecer!</a>
                </div>
                <img src="img/lossy-page1-640px-Os_Mutantes.tif (1).png" alt="A imagem apresenta o grupo musical Os mutantes, sao tres pessoas cantando em  dois microfones" title="Os mutantes - CC0 Domínio Público / Acervo Arquivo Nacional" class="img-fluid img-inicio">

              </div>
        </section>

        <section id="tropicalia" class="my-5 pt-6 secao-tropicalia">
            <div class="container d-flex align-items-center ">
                <div class="col-4 d-flex justify-content-center">
                    <img src="img/image (1).png" class="rounded-pill" alt="" width="273" height="331" loading="lazy">
                </div>
                <div class="col-5">
                    <h2>O que foi a Tropicália?</h2>
                    <p class="p-2">A Tropicália, também conhecida como Tropicalismo, foi um movimento cultural
                        brasileiro que surgiu na década de 1960, tendo seu auge entre 1967 e 1968. Esse movimento
                        abrangeu várias expressões artísticas, como a música, o cinema, o teatro e as artes plásticas, e
                        teve como principal característica a mistura de elementos da cultura brasileira tradicional com
                        influências estrangeiras, especialmente do rock e da música pop. Fonte: Site Toda a matéria</p>
                </div>
            </div>
        </section>

        <section id="galeria">
            <h2 class="text-center pt-5">Galeria</h2>
            <div class="container p-3 mt-3 fundo-galeria ">

                <div class="row justify-content-md-center">
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Jorge_Ben_e_o_Trio_Mocotó_no_Teatro_da_Lagoa,_1971.tif.jpg"
                            class="img-fluid rounded-5" loading="lazy">
                    </div>
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Os_Mutantes_2.tif.jpg" class="img-fluid rounded-5"
                            loading="lazy">
                    </div>
                </div>
                <div class="row mt-4  justify-content-md-center">
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Gilberto_Gil_nos_anos_1960.tif.jpg" class="img-fluid rounded-5" loading="lazy">
                    </div>
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Caetano_Veloso_no_III_Festival_da_Música_Popular.tif.jpg"
                            class="img-fluid rounded-5" loading="lazy">
                    </div>
                </div>
             </div>
        </section>

        <section id="contato">
            <div class="container p-5 d-flex justify-content-center">
                <div class="col-md-8 col-lg-10 rounded-5 formulario"> <!-- Caixa do formulário com 60% de largura -->
                    <h2 class="mb-3">Entre em contato</h2>
                    <form>
                        <div class="form-group mb-3">
                            <label for="nome">Nome</label>
                            <input type="text" id="nome" name="nome" class="form-control rounded-3 mt-1"
                                placeholder="Digite seu nome completo">
                        </div>
                        <div class="form-group mb-3">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" class="form-control rounded-3 mt-1"
                                placeholder="Digite seu email">
                        </div>
                        <div class="form-group mb-3">
                            <label for="mensagem">Mensagem</label>
                            <textarea id="mensagem" name="mensagem" class="form-control rounded-4 mt-2" rows="4"
                                placeholder="Escreva sua mensagem"></textarea>
                        </div>
                        <div class="d-grid gap-2">
                            <button type="submit" class="btn btn-primary btn-lg rounded-pill">Enviar
                                mensagem</button>
                        </div>
                    </form>
                </div>
            </div>
        </section>
    </main>
    <footer class="text-center p-3 fst-italic">
        <p>Acesse nossas redes:</p>
        <i class="bi bi-whatsapp"></i>
        <i class="bi bi-instagram"></i>
        <i class="bi bi-tiktok"></i>
        <p class="mt-3">Desenvolvido por Start by Alura. Projeto fictício sem fins comerciais.</p>
    </footer>
    
    <script src="script.js"></script>
  
</body>

</html>
