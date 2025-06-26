<!DOCTYPE html>
<!--[if lte IE 9]> <html class="no-js lt-ie10 oldie"> <![endif]-->
<!--[if gt IE 8]><!--> <html class="no-js"> <!--<![endif]-->
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <meta name="theme-color" content="#000000">

  <title>Resn - Creative Digital Agency | Ideation, Design, and Development</title>
  <meta name="description" content="Resn is a digital experience agency specializing in creative ideation, digital strategy, user experience, Web3, content strategy, content creation, art direction, design, motion design, animation & 3D, audio and music design, copywriting, web development, e-commerce, game concept and creation, digital installations and activations, advanced interactive 3D graphics, dynamic interactive video content tools, and dynamic social content creation." />
  <meta name="keywords" content="creative digital agency, ideation, design, development, digital strategy, user experience, Web3, content strategy, content creation, art direction, motion design, animation, 3D, audio, music design, copywriting, web development, e-commerce, game concept, digital installations, activations, interactive graphics, video content, social content creation" />

  <!-- Open Graph -->
  <meta property="og:title" content="Resn - Digital Experience Agency | Ideation, Design, and Development" />
  <meta property="og:description" content="Resn is a digital experience agency specializing in creative ideation, digital strategy, user experience, Web3, content strategy, content creation, art direction, design, motion design, animation & 3D, audio and music design, copywriting, web development, e-commerce, game concept and creation, digital installations and activations, advanced interactive 3D graphics, dynamic interactive video content tools, and dynamic social content creation." />
  <meta property="og:image" content="http://resn.co.nz/resn-share.jpg?bar=2" />
  <meta property="og:type" content="website">
  <meta property="og:url" content="http://resn.co.nz" />

  <!-- Twitter -->
  <meta name="twitter:card" content="summary">
  <meta name="twitter:title" content="Resn">
  <meta name="twitter:description" content="Resn is a digital experience agency...">
  <meta name="twitter:image" content="http://resn.co.nz/resn-share.jpg?bar=2">

  <!-- Schema.org -->
  <meta itemprop="name" content="Resn">
  <meta itemprop="description" content="Resn is a digital experience agency...">
  <meta itemprop="image" content="http://resn.co.nz/resn-share.jpg?bar=2">

  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, minimal-ui, viewport-fit=cover">

  <!-- Optional JS polyfills -->
  <script src="./20250408221006_1_0_17063ca/js/libs/es6-shim.min.js"></script>
  <script src="./20250408221006_1_0_17063ca/js/libs/modernizr-2.5.3.min.js"></script>

  <!-- Loader styles -->
  <style>
    #oldie_message {
      position: fixed;
      left: 0; top: 0;
      width: 100%; height: 100%;
      background: #121212;
      text-align: center;
      z-index: 10000;
      display: none;
    }
    #oldie_message img {
      position: absolute;
      left: 50%; top: 50%;
      width: 552px; height: 168px;
      margin-left: -276px; margin-top: -123px;
    }

    body {
      background: black;
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      cursor: none;
    }

    .loader {
      position: absolute;
      left: 0; top: 0;
      width: 100%; height: 100%;
      z-index: 10;
    }

    .loader__inner {
      position: absolute;
      text-align: center;
      overflow: hidden;
      opacity: 0;
      z-index: -1;
    }

    .loader__drop {
      display: inline-block;
      width: 24px; height: 22px;
      fill: #fff;
    }

    @media screen and (orientation: landscape) {
      .loader__drop { width: 30px; height: 30px; }
    }

    .loader__bar-wrapper {
      position: absolute;
      width: 100%; height: 1px;
      bottom: 0;
    }

    .bar-progress, .bar-background {
      position: absolute;
      width: 100%; height: 100%;
      left: 0; top: 0;
    }

    .bar-background { background-color: rgb(40, 40, 40); }
    .bar-progress { background-color: white; z-index: 1 !important; }

    /* Animation & Cursor Styles from Demo */
    .cursor {
      position: fixed;
      top: 0; left: 0;
      width: 30px; height: 30px;
      border: 2px solid white;
      border-radius: 50%;
      pointer-events: none;
      transform: translate(-50%, -50%);
      transition: transform 0.15s ease, background-color 0.3s ease;
      z-index: 1000;
      mix-blend-mode: difference;
    }

    .container {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      perspective: 800px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    h1 {
      font-size: clamp(3rem, 8vw, 6rem);
      line-height: 1.1;
      font-weight: 900;
      margin-bottom: 1rem;
      cursor: pointer;
      user-select: none;
      transform-style: preserve-3d;
    }

    p {
      font-size: clamp(1rem, 2vw, 1.5rem);
      opacity: 0.8;
      font-weight: 300;
      max-width: 600px;
    }

    .background-shapes {
      position: absolute;
      top: 50%; left: 50%;
      width: 150vw; height: 150vw;
      max-width: 1500px;
      max-height: 1500px;
      pointer-events: none;
      transform: translate(-50%, -50%);
      mix-blend-mode: screen;
      filter: blur(40px);
      z-index: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 300px;
      opacity: 0.15;
    }

    .shape {
      width: 250px; height: 250px;
      background: linear-gradient(135deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
      border-radius: 50%;
      animation: float 8s ease-in-out infinite;
    }

    .shape:nth-child(2) {
      animation-delay: 4s;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0) translateX(0) }
      50% { transform: translateY(-40px) translateX(20px) }
    }
  </style>
</head>
<body>
  <script id="hs-script-loader" async defer src="//js.hs-scripts.com/5452172.js"></script>

  <div id="oldie_message">
    <img src="./20250408221006_1_0_17063ca/img/old-browser.png" />
  </div>

  <div class="cursor"></div>

  <div class="background-shapes">
    <div class="shape"></div>
    <div class="shape"></div>
  </div>

  <div class="container">
    <h1 id="title">RESN Inspired Animation</h1>
    <p>Learning modern interactive web animations with HTML, CSS, and JavaScript.</p>
  </div>

  <!-- GSAP for animation -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>

  <script>
    // Show old browser message
    if (document.documentElement.className.includes('oldie') || Function('/@cc_on return document.documentMode===10@/')()) {
      document.getElementById('oldie_message').style.display = 'block';
    } else {
      const scriptTag = document.createElement('script');
      scriptTag.setAttribute('data-main', './20250408221006_1_0_17063ca/js/loader');
      scriptTag.setAttribute('src', './20250408221006_1_0_17063ca/js/libs/require.js');
      document.body.appendChild(scriptTag);
    }

    // Cursor
    const cursor = document.querySelector('.cursor');
    window.addEventListener('mousemove', e => {
      cursor.style.left = e.clientX + 'px';
      cursor.style.top = e.clientY + 'px';
    });

    // Tilt effect
    const title = document.getElementById('title');
    const maxRot = 30;
    window.addEventListener('mousemove', e => {
      const x = (e.clientX / window.innerWidth - 0.5) * 2 * maxRot;
      const y = (e.clientY / window.innerHeight - 0.5) * 2 * maxRot;
      gsap.to(title, {
        duration: 0.3,
        rotationX: -y,
        rotationY: x,
        transformPerspective: 800,
        transformOrigin: "center"
      });
    });

    window.addEventListener('mouseleave', () => {
      gsap.to(title, { duration: 0.5, rotationX: 0, rotationY: 0 });
    });

    // Entry animations
    gsap.from(".container h1", { opacity: 0, y: 50, duration: 1.5, ease: "power3.out" });
    gsap.from(".container p", { opacity: 0, y: 70, duration: 1.5, delay: 0.3, ease: "power3.out" });
  </script>
</body>
</html>
