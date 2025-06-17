<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HTML CSS + BOSTRAP</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet"/>
  <!-- Custom CSS -->
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">html y boostrap</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
        data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link active" href="#">Inicio</a></li>
          <li class="nav-item"><a class="nav-link" href="#formulario">fomulario</a></li>
          <li class="nav-item"><a class="nav-link" href="#info">Información</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero d-flex align-items-center text-center text-white">
    <div class="container">
      <h1 class="display-4 animate-fadein">Bienvenido</h1>
      <p class="lead animate-fadein delay-1">HTML Y BOOSTRAP</p>
      <a href="#formulario" class="btn btn-light btn-lg mt-3 animate-fadein delay-2"><i class="bi bi-box-arrow-in-right"></i> Iniciar sesión</a>
    </div>
  </section>

  <!-- Formulario -->
  <section class="container py-5" id="formulario">
    <div class="row justify-content-center">
      <div class="col-md-6">
        <div class="card shadow-sm border-0 card-custom">
          <div class="card-body">
            <h4 class="mb-4 text-center">Inicia sesión</h4>
            <form>
              <div class="mb-3">
                <label for="email" class="form-label">Correo electrónico</label>
                <input type="email" class="form-control" id="email" placeholder="@.com" required>
              </div>
              <div class="mb-3">
                <label for="password" class="form-label">Contraseña</label>
                <input type="password" class="form-control" id="password" placeholder="********" required>
              </div>
              <div class="d-grid">
                <button type="submit" class="btn btn-primary btn-lg">Entrar</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Información -->
  <section class="container py-5" id="info">
    <div class="row g-4 text-center">
      <div class="col-md-4">
        <div class="card card-custom">
          <div class="card-body">
            <i class="bi bi-bootstrap-fill fs-1 text-primary"></i>
            <h5 class="mt-3">Boostrp</h5>
            <p>saber mas.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card card-custom">
          <div class="card-body">
            <i class="bi bi-shield-lock-fill fs-1 text-success"></i>
            <h5 class="mt-3">Seguridad</h5>
            <p>Campos protegidos y validación integrada.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card card-custom">
          <div class="card-body">
            <i class="bi bi-lightning-fill fs-1 text-warning"></i>
            <h5 class="mt-3">Velocidad</h5>
            <p>Rápido, ligero y fácil de usar en cualquier dispositivo.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer text-center py-4">
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
