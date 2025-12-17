<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Acesso Exclusivo +18</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#000;
      --card:#0f0f10;
      --red:#e31b23;
      --red-dark:#b8161a;
      --white:#fff;
      --muted:#bdbdbd;
      --radius:16px;
      --glass:rgba(255,255,255,.03);
      --shadow:0 6px 30px rgba(0,0,0,.6);
      --ease:cubic-bezier(.2,.9,.3,1);
    }

    *{box-sizing:border-box}
    html,body{
      margin:0;
      height:100%;
      font-family:Inter,system-ui;
      background:linear-gradient(180deg,#000,#050505);
      color:var(--white);
    }

    .wrap{
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:28px;
    }

    .card{
      width:100%;
      max-width:920px;
      background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,.01));
      border-radius:24px;
      box-shadow:var(--shadow);
      padding:28px;
      display:grid;
      grid-template-columns:1fr 420px;
      gap:28px;
      border:1px solid rgba(255,255,255,.03);
    }

    .content h1{
      margin:0 0 8px;
      font-size:clamp(24px,6vw,46px);
      letter-spacing:2px;
      font-weight:800;
    }

    .subtitle{
      color:var(--red);
      font-weight:700;
      margin-bottom:16px;
    }

    .content p{
      color:var(--muted);
      line-height:1.5;
    }

    .actions{
      margin-top:16px;
      display:flex;
      gap:12px;
      flex-wrap:wrap;
    }

    .btn{
      background:var(--red);
      border:0;
      color:#fff;
      padding:12px 18px;
      border-radius:12px;
      font-weight:700;
      cursor:pointer;
    }

    .btn:hover{background:var(--red-dark)}

    .btn.ghost{
      background:transparent;
      border:1px solid rgba(255,255,255,.1);
      color:var(--muted);
    }

    .qr-box{
      background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,.01));
      border-radius:16px;
      padding:18px;
      display:flex;
      flex-direction:column;
      align-items:center;
      gap:14px;
      border:1px solid rgba(255,255,255,.05);
    }

    .qr-wrap{
      background:var(--glass);
      padding:14px;
      border-radius:18px;
      width:100%;
      display:flex;
      justify-content:center;
    }

    .qr-wrap img{
      width:100%;
      max-width:260px;
      border-radius:18px;
      border:6px solid rgba(255,255,255,.03);
      box-shadow:0 6px 18px rgba(0,0,0,.6);
    }

    .qr-caption{
      font-size:13px;
      color:var(--muted);
      text-align:center;
    }

    .secret{
      margin-top:18px;
      padding:16px;
      border-radius:12px;
      background:rgba(255,255,255,.02);
      border:1px solid rgba(255,255,255,.05);
      max-height:0;
      overflow:hidden;
      opacity:0;
      transition:.4s;
    }

    .secret.open{
      max-height:300px;
      opacity:1;
    }

    @media(max-width:900px){
      .card{grid-template-columns:1fr}
    }
  </style>
</head>

<body>
  <div class="wrap">
    <main class="card">

      <section class="content">
        <h1>ACESSO EXCLUSIVO +18</h1>
        <div class="subtitle">Conteúdo privado — fotos e vídeos</div>

        <p>
          Para liberar o acesso ao conteúdo exclusivo, confirme o pagamento via PIX.
          Escaneie o QR Code ao lado e depois clique em <strong>Já paguei</strong>.
        </p>

        <div class="actions">
          <button id="unlockBtn" class="btn">Já paguei — Liberar acesso</button>
          <button class="btn ghost">Precisa de ajuda?</button>
        </div>

        <div id="secret" class="secret">
          <h3>ACESSO LIBERADO 🔓</h3>
          <p>Pagamento confirmado. Clique abaixo para entrar no conteúdo.</p>
          <button class="btn">Entrar no Conteúdo</button>
        </div>
      </section>

      <aside class="qr-box">
        <small>Pagamento via PIX</small>

        <div class="qr-wrap">
          <img
            src="https://i.postimg.cc/yNT3rXYY/Screenshot-20251217-192821-76X-Slots.jpg"
            alt="QR Code PIX Bradesco"
          />
        </div>

        <div class="qr-caption">
          Escaneie com o app do seu banco
        </div>
      </aside>

    </main>
  </div>

  <script>
    const btn = document.getElementById("unlockBtn");
    const secret = document.getElementById("secret");

    btn.onclick = () => {
      secret.classList.add("open");
    };
  </script>
</body>
</html>
