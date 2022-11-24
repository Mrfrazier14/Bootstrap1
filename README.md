# Bootstrap1
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Add link to Bootstrap CDN below: -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>News Website</title>
</head>

<body>
    <div class="container">
        <header class="sticky-top">
            <div class="row flex-nowrap justify-content-between align-items-center bg-dark">
                <div class="col-4 pt-1">
                    <button type="button" class="btn btn-sm btn-outline-primary">Subscribe</button>
                </div>
                <div class="col-4 text-center">
                    <h1 class="text-white" href="#">News</h1>
                </div>
                <div class="col-4 d-flex justify-content-end align-items-center">
                    <a class="btn btn-sm btn-outline-light" href="#">Log In</a>
                </div>
            </div>
            <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <a class="navbar-brand mx-auto" href="#">Categories:</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <div class="navbar-nav mx-auto">
                        <a class="p-2 text-muted" href="#">US</a>
                        <a class="p-2 text-muted" href="#">Foreign</a>
                        <a class="p-2 text-muted" href="#">Technology</a>
                        <a class="p-2 text-muted" href="#">Business</a>
                        <a class="p-2 text-muted" href="#">Culture</a>
                        <a class="p-2 text-muted" href="#">ics</a>
                        <a class="p-2 text-muted" href="#">Opinion</a>
                        <a class="p-2 text-muted" href="#">Health</a>
                        <a class="p-2 text-muted" href="#">Economics</a>
                    </div>
                </div>
            </nav>
        </header>

        <div class="row">
            <div class="col-12">
                <div class="jumbotron p-3 p-md-5 rounded" style="background-image: url('https://content.codecademy.com/courses/learn-bootstrap-4/student-reading.jpg'); background-size: cover;">
                    <div class="col-12" style="background-color: rgba(0,0,0, 0.4);">
                        <h1 class="display-4 text-white">Kids Love to Read!</h1>
                        <p class="lead text-light my-3">Teachers say it starts at home! You should begin reading to
                            your children consistently at a young age.</p>
                        <p class="lead mb-0"><a href="#" class="text-white font-weight-bold">Continue reading...</a></p>
                    </div>
                </div>
            </div>
        </div>

        <div class="row mb-2">
            <div class="col-12 col-md-6">
                <div class="card mb-4 box-shadow">
                    <img class="card-img-top img-fluid" src="https://content.codecademy.com/courses/learn-bootstrap-4/recycle.jpg" alt="Card image cap">
                    <div class="card-body d-flex flex-column align-items-start">
                            <p class="d-inline-block mb-2 text-info font-weight-bold">Foreign</p>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Filling the Gaps</a>
                        </h3>
                        <div class="mb-1 text-muted">Nov 12</div>
                        <p class="card-text">Developed countries have reduced their plastic usage and
                            adopted sustainable living practices. This change has slowed down the effects of
                            climate change for developing nations.</p>
                        <a href="#">Read More</a>
                    </div>
                </div>
            </div>
            
            <div class="col-12 col-md-6">
                <div class="card mb-4 box-shadow">
                    <img class="card-img-top img-fluid" src="https://content.codecademy.com/courses/learn-bootstrap-4/polling-station.jpg" alt="Card image cap">
                    <div class="card-body d-flex flex-column align-items-start">
                        <p class="d-inline-block mb-2 text-warning font-weight-bold">Politics</p>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Record High for Young US Voters</a>
                        </h3>
                        <div class="mb-1 text-muted">Nov 11</div>
                        <p class="card-text">American voters under 30 years old came out in droves for
                            the last election. This trend is inspiring the youths of other democratic nations.</p>
                        <a href="#">Read More</a>
                    </div>
                </div>
            </div>
        </div>
            
        
        <div class="row">
            <div class="col-12">
                <div class="p-3 mb-3 bg-light rounded">
                    <h4>About</h4>
                    <p class="mb-0"><span class="font-italic">Your news fast and accurate!</span> At News, we take the news very
                        seriously. We guarantee real news from certified, experience journalists.</p>
                </div>
            </div>
        </div>
        
        <div class="row">    
            <div class="col-6">
                <h4 class="font-italic">Archives</h4>
                <ol class="list-unstyled">
                    <li><a href="#">October 2018</a></li>
                    <li><a href="#">September 2018</a></li>
                    <li><a href="#">August 2018</a></li>
                    <li><a href="#">July 2018</a></li>
                </ol>
            </div>
            <div class="col-6">
                <h4 class="font-italic">Social</h4>
                <ol class="list-unstyled">
                    <li><a href="#">YouTube</a></li>
                    <li><a href="#">Twitter</a></li>
                    <li><a href="#">Facebook</a></li>
                </ol>
            </div>
        </div>
    </div>

    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
</body>

</html>
