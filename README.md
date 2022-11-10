<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NINE-NINE!</title>

  <link rel="stylesheet" type="text/css" href="./assets/style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>

<body>
  <!--Barra de Navegação-->
  <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #ffffff">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img src="./assets/image/logo99.png" width="80" height="50" /></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: #010626">Início</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: #010626">Cast</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: #010626">Temporadas</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: #010626">Loja</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: #010626">Fale Conosco</a>
          </li>

          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#" style="color: #010626">Sobre</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-warning" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <!--Carrosel-->
  <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./assets/image/b99.jpg" class="d-block w-100" width="400" height="900" alt="...">
      </div>
      <div class="carousel-item">
        <img src="./assets/image/b992.webp" class="d-block w-100" width="400" height="900" alt="...">
      </div>
      <div class="carousel-item">
        <img src="./assets/image/b993.jpg" class="d-block w-100" width="400" height="900" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  <div class="container">
    <section id="historia">
      <p>
      <h1 class="historia" text="aling">
        BROOKLYN NINE-NINE
      </h1>
      </p>
      <p class="conteudo">
        Brooklyn Nine-Nine (abreviado como B99) é uma série de televisão de comédia policial americana criada por Dan
        Goor e Michael Schur. A série gira em torno de Jake Peralta (Andy Samberg), um imaturo, mas talentoso, detetive
        da polícia de Nova York na fictícia 99.ª Delegacia do Brooklyn, que muitas vezes entra em conflito com seu novo
        comandante, o sério e severo capitão Raymond Holt (Andre Braugher). O restante do elenco inclui Stephanie
        Beatriz como Rosa Diaz, Terry Crews como Terry Jeffords, Melissa Fumero como Amy Santiago, Joe Lo Truglio como
        Charles Boyle, Chelsea Peretti como Gina Linetti, Dirk Blocker como Michael Hitchcock e Joel McKinnon Miller
        como Norm Scully.



      </p>
    </section>
    <!--Lançamentos-->
    <Section id="lançamentos">
      <div class="row">
        <div class="col-sm-3">
          <div class="card" style="width: 18rem;">
            <img src="./assets/image/personagens.jpg" class="card-img-top" style="height: 200px;" alt="...">
            <div class="card-body">
              <h5 class="card-title">Personagens</h5>
              <p class="card-text">Ainda não sabe muito sobre seus personagens favoritos? Veja aqui tudo o que voce
                precisa saber!</p>
              <a href="#" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal">Ver Mais</a>
              <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                aria-hidden="true">
                <div class="modal-dialog">
                  <div class="modal-content">
                    <div class="modal-header">
                      <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                      <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                      <img src="./assets/image/pers.jpg" style="height: 600px;  width: 465px;">
                      <hr>
                      <h2>Jake Peralta </h2>
                      <p>Como o "protagonista" da série, enxergamos o mundo através de sua perspectiva. Peralta pode ser
                        um pouco imaturo e bobão, mas é um homem de excelente caráter, que está sempre disposto a
                        auxiliar seus amigos e se provar o melhor detetive do 99º Departamento </p>
                      <hr>
                      <h2> Amy</h2>
                      <p> Ela é muito apaixonada pelo seu trabalho e dedica todo o seu tempo a ele. Amy é uma grande
                        competidora, porque de fato, ela se esforça para sempre provar ser a melhor. Embora ela seja
                        inteligente e engenhosa, ela também pode ser má e condescendente, especialmente com Jake Peralta.
                      </p>
                    </div>
                    <div class="modal-footer">
                      <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Fechar</button>
                      <button type="button" class="btn btn-primary">Salvar</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="card" style="width: 18rem;">
            <img src="./assets/image/peraltiago.jpg" class="card-img-top" style="height: 200px;" alt="...">
            <div class="card-body">
              <h5 class="card-title">Casais</h5>
              <p class="card-text">Quer saber os melhores shipps? Atenção que aqui você pode encontrar MUITOS SPOILERS!!
              </p>
              <a href="#" class="btn btn-warning">Ver Mais</a>
            </div>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="card" style="width: 18rem;">
            <img src="./assets/image/temporada.jpg" class="card-img-top" style="height: 200px;" alt="...">
            <div class="card-body">
              <h5 class="card-title">Temporadas</h5>
              <p class="card-text"> Ao todo são 8 incríveis temporadas! Saiba em quais streams você pode maratonar para
                matar a saudade.</p>
              <a href="#" class="btn btn-warning">Ver Mais</a>
            </div>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="card" style="width: 18rem;">
            <img src="./assets/image/moment.jpg" class="card-img-top" style="height: 200px;" alt="...">
            <div class="card-body">
              <h5 class="card-title">Melhores Momentos</h5>
              <p class="card-text"> Saiba mais sobre os melhores momentos da série e em que episódios você pode
                encontrá-los!</p>
              <a href="#" class="btn btn-warning">Ver Mais</a>
            </div>
          </div>
        </div>
      </div>
    </Section>
    <!-----Um site dentro do outro-->
    <section class id="assinatura">
      <br />
      <H1 class="text-center">Assinatura</H1>
      <br />
      <table align="center">

        <tr>
          <td> <img class="sombra" src="./assets/image/fim5.jpg" width="900" height="500" /></td>
          <td></td>
          <td></td>
        </tr>
      </table>
    </section>

  </div>


  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
    integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"
    integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF"
    crossorigin="anonymous"></script>
</body>

</html>
