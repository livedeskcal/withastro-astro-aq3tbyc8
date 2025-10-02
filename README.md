<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>Live Desk Cal - Outlook and Google Calendar on Windows</title>
  <meta name="description" content="Live Desk Cal keeps Outlook and Google Calendar visible on Windows. Plan faster, prevent conflicts, and reduce app switching with a lightweight desktop widget." />
  <link rel="canonical" href="https://livedeskcal.com/" />

  <!-- Open Graph -->
  <meta property="og:title" content="Live Desk Cal - Outlook and Google Calendar on Windows" />
  <meta property="og:description" content="Keep Outlook and Google events visible on Windows with a lightweight desktop widget that reduces switching and prevents conflicts." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://livedeskcal.com/" />

  <!-- Basic styles for readable layout -->
  <style>
    :root {
      --fg: #0f172a;
      --muted: #475569;
      --bg: #ffffff;
      --brand: #2563eb;
      --card: #f8fafc;
      --border: #e2e8f0;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      color: var(--fg);
      background: var(--bg);
      line-height: 1.6;
    }
    header {
      padding: 48px 20px 16px;
      text-align: center;
      background: linear-gradient(180deg, #eef2ff 0%, #ffffff 100%);
      border-bottom: 1px solid var(--border);
    }
    header h1 {
      margin: 0 0 8px 0;
      font-size: clamp(28px, 4vw, 40px);
      letter-spacing: -0.02em;
    }
    header p {
      margin: 0 auto;
      max-width: 820px;
      color: var(--muted);
      font-size: clamp(15px, 2.2vw, 18px);
    }
    main {
      max-width: 920px;
      margin: 0 auto;
      padding: 28px 20px 72px;
      display: grid;
      gap: 28px;
    }
    section {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 22px 20px;
    }
    section h2 {
      margin: 0 0 12px 0;
      font-size: 22px;
    }
    p { margin: 0 0 12px 0; }
    ul, ol { margin: 0 0 12px 20px; }
    li { margin: 4px 0; }
    a { color: var(--brand); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .grid {
      display: grid;
      gap: 14px;
    }
    .grid.two {
      grid-template-columns: 1fr;
    }
    @media (min-width: 760px) {
      .grid.two { grid-template-columns: 1fr 1fr; }
    }
    .note {
      font-size: 14px;
      color: var(--muted);
    }
    pre {
      background: #0b1021;
      color: #e6edf3;
      padding: 14px;
      border-radius: 10px;
      overflow-x: auto;
      border: 1px solid #111827;
      margin: 0 0 12px 0;
    }
    code, pre code {
      font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace;
      font-size: 14px;
    }
    footer {
      text-align: center;
      padding: 28px 20px;
      color: var(--muted);
      border-top: 1px solid var(--border);
    }
  </style>

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "SoftwareApplication",
    "name": "Live Desk Cal",
    "operatingSystem": "Windows 10, Windows 11",
    "applicationCategory": "BusinessApplication",
    "description": "Live Desk Cal places Outlook and Google Calendar on your Windows desktop in a single, always visible widget.",
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    },
    "url": "https://livedeskcal.com/"
  }
  </script>
</head>
<body>
  <header>
    <h1>Live Desk Cal: Outlook and Google Calendar on Windows</h1>
    <p>Keep your schedule visible on the Windows desktop. Plan faster, prevent conflicts, and reduce app switching with a lightweight, always visible calendar widget.</p>
  </header>

  <main>
    <section aria-labelledby="overview">
      <h2 id="overview">Quick overview</h2>
      <p>Live Desk Cal places your calendar directly on the desktop so your next steps are always in sight. Outlook and Google events appear together with familiar colors, so work and personal plans stay aligned.</p>
      <ul>
        <li>Always visible schedule that prevents double booking</li>
        <li>Combined view for Outlook and Google</li>
        <li>Fewer clicks and less context switching</li>
        <li>Lightweight performance on laptops and multi monitor setups</li>
      </ul>
    </section>

<!-- Intro section -->
<section aria-labelledby="intro">
      <h2 id="intro">Introduction</h2>
      <p>Calendar checks should take seconds. Live Desk Cal creates a calm, glanceable panel that sits where your eyes naturally land. No browser tabs. No full application launch. When you need to edit, click any entry to open the event in your source calendar.</p>
    </section>

<!-- Features section -->
<section aria-labelledby="features">
      <h2 id="features">Key features</h2>
      <div class="grid two">
        <ul>
          <li>Unified Outlook and Google view with source colors</li>
          <li>Day, Week, and Agenda modes</li>
          <li>Resizable and movable to any corner or display</li>
          <li>Opacity and typography controls for readability</li>
        </ul>
        <ul>
          <li>Click through to edit in Outlook or Google</li>
          <li>Optional secondary time zone</li>
          <li>Startup launch with Windows</li>
          <li>Low resource usage for smooth performance</li>
        </ul>
      </div>
    </section>

<!-- Quick start section -->
<section class="steps" aria-labelledby="quick-start">
      <h2 id="quick-start">Quick start</h2>
      <ol>
        <li>Install Live Desk Cal on Windows 10 or Windows 11.</li>
        <li>Sign in to Microsoft and select Outlook calendars.</li>
        <li>Sign in to Google and select calendars to include.</li>
        <li>Choose a default view and set preferred opacity.</li>
        <li>Pin the widget near the system clock for fast checks.</li>
      </ol>

<p class="note">Tip: Use Agenda view during deep work. Switch to Day view on heavy meeting days.</p>
<pre><code># Example: keep a personal setup list in a text file

1. Place widget at right edge near the clock
2. Set opacity to about 85 percent
3. Use consistent colors across Outlook and Google
4. Enable a secondary time zone if you meet globally
</code></pre>
    </section>

<!-- Learn more -->
<section aria-labelledby="learn">
      <h2 id="learn">Learn more and updates</h2>
      <p>Guides, setup tutorials, and release notes are published on the <a href="https://livedeskcal.com/blog/" rel="noopener">Live Desk Cal blog</a>. Visit for best practices, deployment tips, and product news.</p>
    </section>

<!-- FAQ -->
<section aria-labelledby="faq">
      <h2 id="faq">FAQ</h2>
      <details>
        <summary>Does it work offline</summary>
        <p>Yes. Recent data remains visible and changes sync when you reconnect.</p>
      </details>
      <details>
        <summary>Is it heavy on resources</summary>
        <p>No. It is engineered for smooth scrolling, quick navigation, and minimal footprint.</p>
      </details>
      <details>
        <summary>Can I choose specific calendars</summary>
        <p>Yes. Select the calendars you want from both accounts.</p>
      </details>
      <details>
        <summary>Can it stay behind active windows</summary>
        <p>Yes. Choose layered behavior for a calm wallpaper effect or set always on top during heavy scheduling.</p>
      </details>
    </section>
  </main>

  <footer>
    <p>© <span id="year"></span> Live Desk Cal. All rights reserved.</p>
  </footer>

  <script>
    // Simple year injection for the footer
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
