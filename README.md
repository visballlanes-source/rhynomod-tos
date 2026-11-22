# rhynomod-tos
Página web de Términos de Servicio de Rhynomod
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Términos de Servicio — Rhynomod</title>
  <style>
    :root {
      --bg: #0b0f17;
      --surface: #121826;
      --border: #1e293b;
      --text: #e2e8f0;
      --muted: #94a3b8;
      --accent: #38bdf8;
      --accent-soft: rgba(56, 189, 248, 0.12);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Inter, Helvetica, Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.7;
      -webkit-font-smoothing: antialiased;
    }

    header {
      border-bottom: 1px solid var(--border);
      background: rgba(11, 15, 23, 0.85);
      backdrop-filter: blur(10px);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .header-inner {
      max-width: 960px;
      margin: 0 auto;
      padding: 1.1rem 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 1rem;
    }

    .brand {
      font-weight: 700;
      font-size: 1.15rem;
      letter-spacing: -0.02em;
      color: #f8fafc;
      display: flex;
      align-items: center;
      gap: 0.6rem;
    }

    .brand-badge {
      font-size: 0.72rem;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      padding: 0.2rem 0.55rem;
      border-radius: 999px;
      background: var(--accent-soft);
      color: var(--accent);
      border: 1px solid rgba(56, 189, 248, 0.25);
    }

    .updated {
      font-size: 0.85rem;
      color: var(--muted);
    }

    main {
      max-width: 960px;
      margin: 0 auto;
      padding: 3rem 1.5rem 5rem;
    }

    .hero {
      margin-bottom: 2.75rem;
      padding-bottom: 2rem;
      border-bottom: 1px solid var(--border);
    }

    .hero h1 {
      font-size: clamp(1.85rem, 3.5vw, 2.5rem);
      font-weight: 800;
      letter-spacing: -0.03em;
      color: #f8fafc;
      margin-bottom: 0.75rem;
    }

    .hero p {
      color: var(--muted);
      font-size: 1.05rem;
      max-width: 68ch;
    }

    .toc {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.25rem 1.5rem;
      margin-bottom: 2.5rem;
    }

    .toc-title {
      font-size: 0.82rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--muted);
      font-weight: 700;
      margin-bottom: 0.75rem;
    }

    .toc-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 0.45rem 1.25rem;
      list-style: none;
    }

    .toc-grid a {
      color: var(--accent);
      text-decoration: none;
      font-size: 0.93rem;
    }

    .toc-grid a:hover {
      text-decoration: underline;
    }

    section {
      margin-bottom: 2.25rem;
      scroll-margin-top: 5rem;
    }

    section h2 {
      font-size: 1.25rem;
      font-weight: 700;
      color: #f8fafc;
      margin-bottom: 0.65rem;
      letter-spacing: -0.01em;
    }

    section p {
      color: var(--text);
      margin-bottom: 0.75rem;
      font-size: 0.98rem;
    }

    section ul {
      padding-left: 1.35rem;
      margin-bottom: 0.75rem;
      color: var(--text);
      font-size: 0.98rem;
    }

    section li {
      margin-bottom: 0.4rem;
    }

    .notice {
      background: var(--surface);
      border-left: 3px solid var(--accent);
      border-radius: 0 8px 8px 0;
      padding: 1rem 1.25rem;
      margin: 1.5rem 0;
      color: var(--muted);
      font-size: 0.94rem;
    }

    footer {
      border-top: 1px solid var(--border);
      padding: 2rem 1.5rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.88rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="header-inner">
      <div class="brand">
        Rhynomod
        <span class="brand-badge">Legal</span>
      </div>
      <div class="updated">Última actualización: 18 de noviembre de 2026</div>
    </div>
  </header>

  <main>
    <div class="hero">
      <h1>Términos de Servicio</h1>
      <p>
        Estos Términos de Servicio regulan el acceso y uso de <strong>Rhynomod</strong>, incluyendo sus herramientas,
        comandos, funciones de moderación, automatizaciones y servicios asociados. Al utilizar Rhynomod, aceptas
        quedar sujeto a las condiciones descritas en este documento.
      </p>
    </div>

    <nav class="toc" aria-label="Índice de secciones">
      <div class="toc-title">Contenido</div>
      <ul class="toc-grid">
        <li><a href="#aceptacion">1. Aceptación de los términos</a></li>
        <li><a href="#descripcion">2. Descripción del servicio</a></li>
        <li><a href="#uso-aceptable">3. Uso aceptable y restricciones</a></li>
        <li><a href="#privacidad">4. Datos y privacidad</a></li>
        <li><a href="#disponibilidad">5. Disponibilidad y modificaciones</a></li>
        <li><a href="#responsabilidad">6. Limitación de responsabilidad</a></li>
        <li><a href="#terminacion">7. Suspensión y terminación</a></li>
        <li><a href="#contacto">8. Contacto</a></li>
      </ul>
    </nav>

    <section id="aceptacion">
      <h2>1. Aceptación de los términos</h2>
      <p>
        Al añadir, configurar o interactuar con Rhynomod en cualquier servidor o entorno compatible, confirmas que has
        leído, comprendido y aceptado estos Términos de Servicio, así como los Términos de Servicio y Directrices de la
        Comunidad de Discord.
      </p>
      <p>
        Si utilizas Rhynomod en nombre de una comunidad u organización, declaras contar con la autoridad necesaria para
        vincular a dicha entidad con estos términos.
      </p>
    </section>

    <section id="descripcion">
      <h2>2. Descripción del servicio</h2>
      <p>
        Rhynomod es un servicio de asistencia y moderación diseñado para ayudar a los administradores y miembros de
        comunidades en Discord mediante funciones de gestión, registro de eventos, automatización y utilidades generales.
      </p>
      <p>
        Las funcionalidades específicas pueden variar según la configuración aplicada por los administradores de cada
        servidor.
      </p>
    </section>

    <section id="uso-aceptable">
      <h2>3. Uso aceptable y restricciones</h2>
      <p>Te comprometes a utilizar Rhynomod de forma lícita y respetuosa. Queda estrictamente prohibido:</p>
      <ul>
        <li>Utilizar el servicio para acosar, discriminar, amenazar o vulnerar derechos de terceros.</li>
        <li>Intentar explotar vulnerabilidades, realizar ingeniería inversa o interferir con la infraestructura del bot.</li>
        <li>Automatizar peticiones abusivas (spam, sobrecarga de comandos o ataques de denegación de servicio).</li>
        <li>Emplear Rhynomod para distribuir contenido ilegal, malware o material que infrinja las políticas de Discord.</li>
      </ul>
    </section>

    <section id="privacidad">
      <h2>4. Datos y privacidad</h2>
      <p>
        Rhynomod procesa únicamente la información técnica estrictamente necesaria para ejecutar sus funciones (como
        identificadores de servidor, canal, usuario y configuraciones propias del servicio).
      </p>
      <div class="notice">
        No vendemos, alquilamos ni comercializamos datos de usuarios o servidores con terceros bajo ninguna circunstancia.
      </div>
    </section>

    <section id="disponibilidad">
      <h2>5. Disponibilidad y modificaciones</h2>
      <p>
        Rhynomod se ofrece "tal cual" y "según disponibilidad". Nos reservamos el derecho de actualizar, modificar,
        suspender temporalmente o discontinuar cualquier función del servicio sin previo aviso, ya sea por mantenimiento,
        mejoras técnicas o motivos de seguridad.
      </p>
    </section>

    <section id="responsabilidad">
      <h2>6. Limitación de responsabilidad</h2>
      <p>
        En la máxima medida permitida por la ley aplicable, el equipo responsable de Rhynomod no será responsable por
        daños directos, indirectos, incidentales o consecuentes derivados del uso o la imposibilidad de uso del servicio,
        ni por las acciones de moderación ejecutadas por administradores de servidores mediante la herramienta.
      </p>
    </section>

    <section id="terminacion">
      <h2>7. Suspensión y terminación</h2>
      <p>
        Podemos restringir o revocar el acceso de cualquier usuario o servidor a Rhynomod de manera inmediata si se
        detecta un incumplimiento de estos Términos de Servicio o un uso que ponga en riesgo la estabilidad del sistema.
      </p>
    </section>

    <section id="contacto">
      <h2>8. Contacto</h2>
      <p>
        Si tienes dudas, solicitudes relacionadas con tus datos o reportes sobre estos Términos de Servicio, puedes
        comunicarte directamente con el equipo de administración de <strong>Rhynomod</strong> a través de los canales
        oficiales del servidor.
      </p>
    </section>
  </main>

  <footer>
    &copy; 2026 Rhynomod. Todos los derechos reservados.
  </footer>
</body>
</html>
