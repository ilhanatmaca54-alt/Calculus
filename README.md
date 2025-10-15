<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Calculus Büroservice – Buchhaltung & Büroorganisation in Stuttgart</title>
  <meta name="description" content="Calculus Büroservice unterstützt Selbständige und KMU in Stuttgart bei Finanzbuchhaltung, Lohn, Belegmanagement und Büroorganisation." />
  <meta name="robots" content="index,follow" />
  <meta property="og:title" content="Calculus Büroservice" />
  <meta property="og:description" content="Buchhaltung & Büroservice für Stuttgart und Umgebung." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="/logo.png" />
  <link rel="icon" href="/favicon.ico" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              DEFAULT: '#0f172a',
              light: '#1e293b',
              accent: '#00a36c'
            }
          }
        }
      }
    }
  </script>
</head>
<body class="bg-slate-50 text-slate-800">
  <div class="w-full bg-brand text-white text-sm">
    <div class="mx-auto max-w-7xl px-4 py-2 flex flex-wrap items-center justify-between gap-2">
      <span>📍 Zahn‑Nopper‑Straße 1–3, 70435 Stuttgart</span>
      <a class="underline underline-offset-2" href="mailto:info@calculus-bueroservice.de">info@calculus-bueroservice.de</a>
    </div>
  </div>

  <header class="sticky top-0 z-40 bg-white/80 backdrop-blur border-b border-slate-200">
    <div class="mx-auto max-w-7xl px-4 py-3 flex items-center justify-between">
      <a href="#" class="flex items-center gap-3">
        <img src="/logo.png" alt="Logo Calculus Büroservice" class="h-10 w-10 object-contain" />
        <span class="font-semibold tracking-tight">Calculus Büroservice</span>
      </a>
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#leistungen" class="hover:text-brand-accent">Leistungen</a>
        <a href="#branchen" class="hover:text-brand-accent">Branchen</a>
        <a href="#ueber" class="hover:text-brand-accent">Über uns</a>
        <a href="#kontakt" class="hover:text-brand-accent">Kontakt</a>
      </nav>
      <a href="#kontakt" class="ml-4 inline-flex items-center rounded-xl bg-brand-accent px-4 py-2 text-white text-sm font-medium shadow hover:opacity-90">Kostenlos anfragen</a>
    </div>
  </header>

  <section class="relative overflow-hidden">
    <div class="absolute inset-0 bg-gradient-to-br from-brand to-brand-light opacity-95"></div>
    <svg class="absolute right-[-10%] top-[-10%] h-[60rem] w-[60rem] opacity-10" viewBox="0 0 1024 1024" fill="none" aria-hidden="true">
      <defs>
        <linearGradient id="g" x1="0" x2="1" y1="0" y2="1">
          <stop stop-color="#ffffff" />
          <stop offset="1" stop-color="#00a36c" />
        </linearGradient>
      </defs>
      <circle cx="512" cy="512" r="512" fill="url(#g)" />
    </svg>
    <div class="relative mx-auto max-w-7xl px-4 py-24 md:py-32 grid lg:grid-cols-2 gap-10 items-center">
      <div class="text-white">
        <h1 class="text-4xl md:text-5xl font-bold leading-tight">Buchhaltung, die mitdenkt.
          <span class="block text-brand-accent">Damit Sie sich aufs Geschäft konzentrieren.</span>
        </h1>
        <p class="mt-6 text-white/90 max-w-xl">Wir übernehmen Finanzbuchhaltung, Lohn & Gehaltsabrechnung, Belegmanagement und Büroorganisation für Selbständige und KMU in Stuttgart und Umgebung.</p>
        <div class="mt-8 flex flex-wrap gap-3">
          <a href="#kontakt" class="inline-flex items-center rounded-xl bg-brand-accent px-5 py-3 font-medium text-white shadow hover:opacity-90">Termin anfragen</a>
          <a href="#leistungen" class="inline-flex items-center rounded-xl px-5 py-3 font-medium bg-white/10 ring-1 ring-white/30 hover:bg-white/20">Leistungen ansehen</a>
        </div>
        <div class="mt-6 text-sm text-white/80">✔️ Transparent · ✔️ Digital · ✔️ Persönlich</div>
      </div>
      <div class="bg-white rounded-2xl shadow-xl p-6 md:p-8">
        <h2 class="text-lg font-semibold">Schnellanfrage</h2>
        <p class="text-sm text-slate-600 mt-1">Wir melden uns innerhalb eines Werktags.</p>
        <form class="mt-6 grid grid-cols-1 gap-4" action="#" method="post">
          <div>
            <label class="block text-sm font-medium">Name</label>
            <input required type="text" name="name" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" placeholder="Ihr Name" />
          </div>
          <div>
            <label class="block text-sm font-medium">E‑Mail</label>
            <input required type="email" name="email" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" placeholder="name@firma.de" />
          </div>
          <div>
            <label class="block text-sm font-medium">Thema</label>
            <select name="topic" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent">
              <option>Finanzbuchhaltung</option>
              <option>Lohn & Gehalt</option>
              <option>Belegmanagement</option>
              <option>Existenzgründung</option>
              <option>Sonstiges</option>
            </select>
          </div>
          <div>
            <label class="block text-sm font-medium">Nachricht (optional)</label>
            <textarea name="message" rows="3" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" placeholder="Wie können wir helfen?"></textarea>
          </div>
          <button type="submit" class="mt-2 inline-flex justify-center rounded-xl bg-brand-accent px-5 py-3 font-medium text-white shadow hover:opacity-90">Absenden</button>
          <p class="text-xs text-slate-500">Mit dem Absenden akzeptieren Sie unsere <a href="#datenschutz" class="underline">Datenschutzerklärung</a>.</p>
        </form>
      </div>
    </div>
  </section>

  <!-- Leistungen -->
  <section id="leistungen" class="mx-auto max-w-7xl px-4 py-20">
    <div class="text-center">
      <h2 class="text-3xl md:text-4xl font-bold">Unsere Leistungen</h2>
      <p class="mt-3 text-slate-600">Modular, transparent und digital.</p>
    </div>
    <div class="mt-10 grid gap-6 sm:grid-cols-2 lg:grid-cols-3">
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <h3 class="font-semibold">Finanzbuchhaltung (FiBu)</h3>
        <p class="mt-2 text-sm text-slate-600">Belegbuchung, Debitoren/Kreditoren, USt‑Voranmeldungen, Auswertungen.</p>
      </div>
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <h3 class="font-semibold">Lohn & Gehalt</h3>
        <p class="mt-2 text-sm text-slate-600">Monatliche Abrechnungen, Meldungen an SV, Bescheinigungen.</p>
      </div>
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <h3 class="font-semibold">Belegmanagement</h3>
        <p class="mt-2 text-sm text-slate-600">Digitale Belegkreisläufe, GoBD‑konform, vorbereitende Buchführung.</p>
      </div>
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <h3 class="font-semibold">Jahresabschluss‑Vorbereitung</h3>
        <p class="mt-2 text-sm text-slate-600">Abschlussfähige Buchhaltung für Ihren Steuerberater.</p>
      </div>
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <h3 class="font-semibold">Gründer‑Service</h3>
        <p class="mt-2 text-sm text-slate-600">Rechtsform‑Check, Behördenschnittstellen, Software‑Setup.</p>
      </div>
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <h3 class="font-semibold">Beratung & Prozesse</h3>
        <p class="mt-2 text-sm text-slate-600">Controlling‑Reports, Zahlungsabläufe, Workflow‑Automatisierung.</p>
      </div>
    </div>
  </section>

  <!-- Branchen -->
  <section id="branchen" class="bg-slate-100">
    <div class="mx-auto max-w-7xl px-4 py-20">
      <div class="grid lg:grid-cols-2 gap-10 items-center">
        <div>
          <h2 class="text-3xl md:text-4xl font-bold">Spezialisiert auf Ihr Geschäft</h2>
          <p class="mt-3 text-slate-600">Gastronomie, Einzelhandel, Taxi/Transport, Handwerk, Dienstleistungen, E‑Commerce u. v. m.</p>
          <ul class="mt-6 space-y-2 text-slate-700 list-disc list-inside">
            <li>Digitale Kassendaten & Z‑Berichte integrieren</li>
            <li>Bewirtung, Trinkgeld, Lieferservice sauber abbilden</li>
            <li>Fahrtenbücher & Tankbelege prüfsicher organisieren</li>
          </ul>
        </div>
        <div class="rounded-2xl border bg-white p-6 shadow-sm">
          <h3 class="font-semibold">Warum Calculus?</h3>
          <div class="mt-4 grid sm:grid-cols-2 gap-4 text-sm">
            <div class="rounded-xl border p-4">
              <p class="font-medium">Schnelle Reaktionszeiten</p>
              <p class="mt-1 text-slate-600">Antwort in der Regel am nächsten Werktag.</p>
            </div>
            <div class="rounded-xl border p-4">
              <p class="font-medium">Transparente Preise</p>
              <p class="mt-1 text-slate-600">Pauschalen oder faire Monatsabos.</p>
            </div>
            <div class="rounded-xl border p-4">
              <p class="font-medium">Digital & vor Ort</p>
              <p class="mt-1 text-slate-600">Cloud‑Belege oder Abholung in Stuttgart.</p>
            </div>
            <div class="rounded-xl border p-4">
              <p class="font-medium">Erfahren & persönlich</p>
              <p class="mt-1 text-slate-600">Direkter Draht zu Ihrem Ansprechpartner.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Über uns -->
  <section id="ueber" class="mx-auto max-w-7xl px-4 py-20">
    <div class="grid lg:grid-cols-2 gap-10 items-start">
      <div>
        <h2 class="text-3xl md:text-4xl font-bold">Über uns</h2>
        <p class="mt-3 text-slate-700">Wir sind ein modernes Buchhaltungs‑ und Büroservice‑Team aus Stuttgart. Mit Fokus auf digitale Prozesse machen wir Ihre Zahlen verständlich und Ihr Backoffice leicht.</p>
        <div class="mt-6 rounded-2xl border bg-white p-6 shadow-sm">
          <p class="font-medium">Zertifikate & Tools</p>
          <p class="mt-2 text-sm text-slate-600">DATEV / Agenda / Lexware · GoBD‑konforme Prozesse · E‑Rechnung</p>
        </div>
      </div>
      <div class="rounded-2xl overflow-hidden border shadow-sm">
        <img src="https://images.unsplash.com/photo-1554224155-3a589877462f?q=80&w=1200&auto=format&fit=crop" alt="Modernes Büro in Stuttgart" class="w-full h-full object-cover" />
      </div>
    </div>
  </section>

  <!-- Call to Action -->
  <section class="bg-brand text-white">
    <div class="mx-auto max-w-7xl px-4 py-16 text-center">
      <h2 class="text-3xl md:text-4xl font-bold">Bereit, Zeit zu sparen?</h2>
      <p class="mt-3 text-white/90">Schicken Sie uns Ihre Unterlagen digital – wir kümmern uns um den Rest.</p>
      <a href="#kontakt" class="mt-6 inline-flex items-center rounded-xl bg-brand-accent px-6 py-3 font-medium text-white shadow hover:opacity-90">Jetzt kostenlos anfragen</a>
    </div>
  </section>

  <!-- Kontakt -->
  <section id="kontakt" class="mx-auto max-w-7xl px-4 py-20">
    <div class="grid lg:grid-cols-2 gap-10">
      <div>
        <h2 class="text-3xl md:text-4xl font-bold">Kontakt</h2>
        <p class="mt-3 text-slate-600">Wir freuen uns auf Ihre Nachricht.</p>
        <ul class="mt-6 space-y-2 text-slate-700">
          <li>📞 <a class="underline" href="tel:+4915129664909">0151 29664909</a></li>
          <li>✉️ <a class="underline" href="mailto:info@calculus-bueroservice.de">info@calculus-bueroservice.de</a></li>
          <li>📍 Zahn‑Nopper‑Straße 1–3, 70435 Stuttgart</li>
        </ul>
      </div>
      <div class="rounded-2xl border bg-white p-6 shadow-sm">
        <form class="grid grid-cols-1 gap-4" action="#" method="post">
          <div class="grid gap-4 sm:grid-cols-2">
            <div>
              <label class="block text-sm font-medium">Vorname</label>
              <input type="text" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" />
            </div>
            <div>
              <label class="block text-sm font-medium">Nachname</label>
              <input type="text" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" />
            </div>
          </div>
          <div>
            <label class="block text-sm font-medium">E‑Mail</label>
            <input type="email" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" />
          </div>
          <div>
            <label class="block text-sm font-medium">Ihre Nachricht</label>
            <textarea rows="4" class="mt-1 w-full rounded-xl border-slate-300 focus:border-brand-accent focus:ring-brand-accent" placeholder="Worum geht es?"></textarea>
          </div>
          <button type="submit" class="mt-2 inline-flex justify-center rounded-xl bg-brand-accent px-5 py-3 font-medium text-white shadow hover:opacity-90">Nachricht senden</button>
          <p class="text-xs text-slate-500">HINWEIS: Dieses Formular ist ein Platzhalter – für echte Zustellung bitte E‑Mail verwenden.</p>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="border-t bg-white">
    <div class="mx-auto max-w-7xl px-4 py-8 flex flex-wrap items-center justify-between gap-4 text-sm text-slate-600">
      <p>© <span id="year"></span> Calculus Büroservice – Stuttgart</p>
      <nav class="flex gap-4">
        <a href="#impressum" class="underline">Impressum</a>
        <a href="#datenschutz" class="underline">Datenschutz</a>
      </nav>
    </div>
  </footer>

  <!-- Cookie Banner -->
  <div id="cookie" class="fixed bottom-4 inset-x-4 md:inset-x-auto md:right-4 md:max-w-xl hidden">
    <div class="rounded-2xl border bg-white p-4 shadow-lg">
      <p class="text-sm">Diese Website verwendet nur technisch notwendige Cookies. Mit Klick auf „Verstanden“ akzeptieren Sie dies.</p>
      <div class="mt-3 flex justify-end">
        <button onclick="acceptCookie()" class="rounded-xl bg-brand-accent px-4 py-2 text-white text-sm">Verstanden</button>
      </div>
    </div>
  </div>

</section>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
  const acceptCookie = () => { localStorage.setItem('cookieAccepted','1'); document.getElementById('cookie').classList.add('hidden'); }
  if(!localStorage.getItem('cookieAccepted')) { document.getElementById('cookie').classList.remove('hidden'); }
</script>

</body>
</html>
