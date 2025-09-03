<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sportivus</title>

  <!-- (Optional) Preload to reduce flicker -->
  <link rel="preload" as="image" href="bg-desktop.jpg">
  <link rel="preload" as="image" href="bg-mobile.jpg">

  <style>
    /* Reset + base */
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color: #fff;
      background: url("bg-desktop.jpg") center/cover no-repeat fixed;
      position: relative;
      overflow: hidden;
    }

    /* Swap to a mobile background below 768px if you provided one */
    @media (max-width: 768px) {
      body { background: url("bg-mobile.jpg") center/cover no-repeat fixed; }
    }

    /* WhatsApp button */
    .wa-btn {
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      bottom: 12vh;                  /* move up/down to match your design */
      display: inline-block;
      padding: 14px 28px;
      font-weight: 700;
      font-size: clamp(14px, 1.6vw, 18px);
      text-decoration: none;
      color: #fff;
      background: #7c3aed;           /* purple */
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0,0,0,.35);
      transition: filter .2s ease, transform .05s ease;
      min-width: 200px;
      text-align: center;
      touch-action: manipulation;
    }
    .wa-btn:hover { filter: brightness(1.05); }
    .wa-btn:active { transform: translateX(-50%) scale(0.98); }

    /* Accessibility focus outline */
    .wa-btn:focus { outline: 3px solid rgba(124,58,237,.6); outline-offset: 4px; }

    /* Respect reduced motion */
    @media (prefers-reduced-motion: reduce) {
      .wa-btn { transition: none; }
    }
  </style>
</head>
<body>

  <!-- Centered button sitting on top of your background design -->
  <a
    class="wa-btn"
    href="https://wa.me/258847602916?text=Ol%C3%A1%20Sportivus!%20Quero%20saber%20mais."
    target="_blank"
    rel="noopener"
    aria-label="Falar no WhatsApp"
  >
    WHATSAPP
  </a>

</body>
</html>
