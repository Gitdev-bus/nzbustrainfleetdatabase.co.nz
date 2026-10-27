
:root {
  --ink: #12232d;
  --muted: #657680;
  --line: #dce7ea;
  --paper: #f3f7f8;
  --card: #fff;
  --accent: #087a8f;
  --accent-dark: #075467;
  --dark: #081d26;
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  scroll-behavior: auto;
  margin: 0;
  padding: 0;
  width: 100%;
  max-width: 100%;
  overflow-x: clip;
}

body {
  margin: 0;
  padding: 0;
  width: 100%;
  max-width: 100%;
  background: var(--paper);
  color: var(--ink);
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", sans-serif;
  line-height: 1.5;
  overflow-x: clip;
}

/* Header and teal hero */
.hero {
  width: 100%;
  min-height: 100vh;
  min-height: 100svh;
  color: #fff;
  background:
    radial-gradient(ellipse at 85% 15%, rgba(44, 211, 207, 0.2), transparent 38%),
    linear-gradient(120deg, #06232d 0%, #087589 62%, #10a0a7 100%);
  position: relative;
  isolation: isolate;
  overflow: hidden;
  padding-bottom: 60px;
}

.hero::after {
  content: "";
  position: absolute;
  right: -180px;
  top: -240px;
  width: 620px;
  height: 620px;
  border: 1px solid rgba(255, 255, 255, 0.2);
  border-radius: 50%;
  box-shadow:
    0 0 0 55px rgba(255, 255, 255, 0.045),
    0 0 0 110px rgba(255, 255, 255, 0.025);
  pointer-events: none;
  z-index: -1;
}

/* Compact header on Contact Us and Request a Change pages */
body:has(.contact-shell) .hero,
body:has(.request-shell) .hero {
  min-height: 0;
  height: auto;
  padding-bottom: 0;
}

body:has(.contact-shell) .hero::after,
body:has(.request-shell) .hero::after {
  display: none;
}

/* Navigation */
.nav {
  width: 100%;
  max-width: 1500px;
  margin: 0 auto;
  padding: 14px 40px;
  display: flex;
  align-items: center;
  gap: 24px;
  position: relative;
  z-index: 2;
}

/* Website logo and title */
.brand {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  min-width: 0;
  flex-shrink: 1;
  font-weight: 850;
  color: #fff;
  text-decoration: none;
  letter-spacing: -.025em;
}

.brand-logo {
  display: block;
  width: 44px;
  height: 44px;
  flex: 0 0 44px;
  object-fit: contain;
}

/* Navigation links */
.navlinks {
  margin-left: auto;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: 30px;
  min-width: 0;
  transform: translateX(15px);
}

.navlinks a {
  color: #dff4f5;
  text-decoration: none;
  font-size: .92rem;
  white-space: nowrap;
  transition: color .18s ease;
}

.navlinks a:hover {
  color: #fff;
  text-decoration: underline;
}

/* Main hero content */
.hero-inner {
  width: 100%;
  max-width: 1500px;
  margin: 0 auto;
  padding: 25px 40px 65px;
  position: relative;
  z-index: 1;
}

.hero-copy {
  width: 100%;
  max-width: 1050px;
  min-width: 0;
}

.eyebrow {
  margin: 0 0 10px;
  font-size: .72rem;
  font-weight: 850;
  letter-spacing: .17em;
  opacity: .76;
}

h1 {
  width: 100%;
  max-width: 1050px;
  font-size: clamp(2.55rem, 6vw, 5.35rem);
  line-height: .98;
  letter-spacing: -.06em;
  overflow-wrap: break-word;
  margin: 0 0 24px;
}

.subtitle {
  width: 100%;
  max-width: 800px;
  color: #d8eff2;
  font-size: 1.1rem;
}

.hero-actions {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 26px;
}

.button {
  display: inline-block;
  max-width: 100%;
  padding: 12px 20px;
  border-radius: 10px;
  background: #fff;
  color: var(--accent-dark);
  text-decoration: none;
  font-weight: 800;
  box-shadow: 0 5px 18px rgba(0, 0, 0, .12);
  transition: transform .2s ease, box-shadow .2s ease, background .2s ease;
}

.button.secondary {
  background: rgba(255, 255, 255, .1);
  color: #fff;
  border: 1px solid rgba(255, 255, 255, .3);
}

.button:hover {
  opacity: 1;
  transform: translateY(-2px);
  box-shadow: 0 9px 24px rgba(0, 0, 0, .18);
}

/* Quick statistics */
.quick-stats {
  width: 100%;
  max-width: 1500px;
  margin: 35px auto 0;
  padding: 0 40px;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
  position: relative;
  z-index: 2;
}

.stat {
  min-width: 0;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 14px;
  padding: 12px 22px;
  box-shadow: 0 5px 18px rgba(9, 51, 62, .045);
  transition: transform .2s ease, box-shadow .2s ease, border-color .2s ease;
}

.stat strong {
  display: block;
  font-size: 1.75rem;
  letter-spacing: -.04em;
}

.stat span {
  color: var(--muted);
  font-size: .85rem;
}

.stat:hover {
  border-color: #b7d7dc;
  box-shadow: 0 10px 28px rgba(9, 51, 62, .09);
}

/* Main sections */
.types,
.database,
.about {
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
  padding: 86px 40px;
}

.section-heading {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 30px;
  margin-bottom: 26px;
}

h2 {
  margin: 0;
  font-size: clamp(1.9rem, 4vw, 3rem);
  letter-spacing: -.05em;
  line-height: 1.02;
}

.muted {
  color: var(--muted);
}

/* Vehicle type cards */
.type-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 14px;
}

.type-card {
  min-width: 0;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 5px 18px rgba(9, 51, 62, .045);
  transition: transform .2s ease, box-shadow .2s ease, border-color .2s ease;
}

.type-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 16px 36px rgba(9, 51, 62, .13);
}

.type-image-wrap {
  height: 185px;
  background: #d9e8eb;
  position: relative;
  overflow: hidden;
}

.type-image-wrap img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform .35s ease;
}

.type-card:hover .type-image-wrap img {
  transform: scale(1.035);
}

.type-image-wrap.image-fallback::before {
  content: "🇳🇿";
  font-size: 4rem;
  position: absolute;
  inset: 0;
  display: grid;
  place-items: center;
}

.image-label {
  position: absolute;
  bottom: 9px;
  left: 9px;
  background: rgba(5, 29, 38, .76);
  color: #fff;
  padding: 4px 7px;
  border-radius: 6px;
  font-size: .65rem;
  font-weight: 750;
}

.type-body {
  padding: 17px;
}

.type-body h3 {
  margin: 0 0 5px;
  font-size: 1.05rem;
}

.type-body p {
  margin: 0 0 10px;
  color: var(--muted);
  font-size: .88rem;
}

.type-body a {
  font-size: .82rem;
  color: var(--accent);
  font-weight: 750;
  text-decoration: none;
}

/* Fleet database */
.database {
  border-top: 1px solid var(--line);
  scroll-margin-top: 12px;
}

.types,
.about {
  scroll-margin-top: 12px;
}

.controls {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 300px;
  gap: 10px;
}

.search-wrap {
  min-width: 0;
  display: flex;
  align-items: center;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 11px;
  padding: 0 13px;
}

.search-wrap span {
  flex-shrink: 0;
  font-size: 1.4rem;
  color: var(--muted);
}

input,
select {
  width: 100%;
  min-width: 0;
  font: inherit;
  color: var(--ink);
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 11px;
  outline: none;
  padding: 14px 13px;
}

input {
  border: 0;
  padding-left: 10px;
}

.search-wrap:focus-within,
input:focus,
select:focus {
  border-color: #82bbc4;
  box-shadow: 0 0 0 3px rgba(8, 122, 143, .1);
}

.result-bar {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  gap: 8px;
  margin: 17px 2px 9px;
  color: var(--muted);
  font-size: .82rem;
}

.result-bar button {
  border: 0;
  background: transparent;
  color: var(--accent);
  font-weight: 800;
  cursor: pointer;
}

.results {
  display: grid;
  gap: 8px;
}

.record {
  min-width: 0;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 12px;
  padding: 15px 17px;
  display: grid;
  grid-template-columns: 105px minmax(0, 1fr) auto;
  gap: 16px;
  align-items: center;
  box-shadow: 0 5px 18px rgba(9, 51, 62, .045);
  transition: transform .2s ease, box-shadow .2s ease, border-color .2s ease;
}

.record:hover {
  border-color: #b7d7dc;
  box-shadow: 0 10px 28px rgba(9, 51, 62, .09);
}

.fleet {
  font-size: 1.12rem;
  font-weight: 900;
  color: var(--accent-dark);
  overflow-wrap: anywhere;
}

.record-main {
  min-width: 0;
}

.record-main h3 {
  font-size: .96rem;
  margin: 0;
  overflow-wrap: anywhere;
}

.record-main p {
  font-size: .84rem;
  color: var(--muted);
  margin: 3px 0 0;
  overflow-wrap: anywhere;
}

.record-actions {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 9px;
}

.tag {
  font-size: .64rem;
  font-weight: 900;
  letter-spacing: .1em;
  color: var(--accent);
  border: 1px solid #b7d7dc;
  border-radius: 999px;
  padding: 5px 8px;
}

.change-help {
  margin: 14px 0;
  color: var(--muted);
  font-size: .9rem;
}

.change-request {
  display: inline-block;
  font-size: .78rem;
  font-weight: 800;
  color: var(--accent-dark);
  background: #e8f5f6;
  border: 1px solid #c4e2e5;
  border-radius: 8px;
  padding: 7px 10px;
  text-decoration: none;
  white-space: nowrap;
  transition: background .18s ease, border-color .18s ease;
}

.change-request:hover {
  background: #d8eef0;
  border-color: #9bcbd2;
}

.no-results {
  text-align: center;
  padding: 30px;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 12px;
  color: var(--muted);
}

/* About section */
.about {
  border-top: 1px solid var(--line);
}

.about > p:not(.eyebrow) {
  max-width: 780px;
  color: var(--muted);
  font-size: 1.03rem;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 12px;
  margin-top: 28px;
}

.feature-grid > div {
  min-width: 0;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 13px;
  padding: 19px;
  box-shadow: 0 5px 18px rgba(9, 51, 62, .045);
  transition: transform .2s ease, box-shadow .2s ease, border-color .2s ease;
}

.feature-grid > div:hover {
  border-color: #b7d7dc;
  box-shadow: 0 10px 28px rgba(9, 51, 62, .09);
}

.icon {
  display: block;
  font-size: 1.5rem;
  margin-bottom: 10px;
}

.feature-grid b,
.feature-grid small {
  display: block;
}

.feature-grid small {
  color: var(--muted);
  margin-top: 4px;
}

/* Footer */
footer {
  width: 100%;
  background: linear-gradient(120deg, #06232d 0%, #087589 62%, #10a0a7 100%);
  color: #fff;
  padding: 27px max(24px, calc((100% - 1200px) / 2));
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 20px;
  font-size: .82rem;
}

footer span {
  color: #d8eff2;
  display: block;
  margin-top: 3px;
}

/* Tablet and smaller laptop screens */
@media (max-width: 900px) {
  .nav {
    padding-right: 24px;
    padding-left: 24px;
    gap: 16px;
  }

  .navlinks {
    gap: 16px;
    transform: none;
  }

  .hero-inner {
    padding-right: 24px;
    padding-left: 24px;
  }

  .quick-stats {
    padding-right: 24px;
    padding-left: 24px;
  }

  .types,
  .database,
  .about {
    padding: 70px 24px;
  }

  .type-grid,
  .feature-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .record {
    grid-template-columns: 90px minmax(0, 1fr);
  }

  .record-actions {
    grid-column: 1 / -1;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }
}

/* Smaller screens */
@media (max-width: 700px) {
  .hero {
    min-height: 100vh;
    min-height: 100svh;
  }

  body:has(.contact-shell) .hero,
  body:has(.request-shell) .hero {
    min-height: 0;
    height: auto;
  }

  .nav {
    padding: 14px 20px;
    align-items: center;
  }

  .navlinks {
    display: none;
  }

  .hero-inner {
    padding: 25px 20px 45px;
  }

  h1 {
    font-size: clamp(2.4rem, 10vw, 4rem);
    overflow-wrap: break-word;
  }

  .subtitle {
    font-size: 1rem;
  }

  .quick-stats {
    grid-template-columns: minmax(0, 1fr);
    margin-top: 12px;
    padding: 0 20px;
  }

  .types,
  .database,
  .about {
    padding: 60px 20px;
  }

  .section-heading {
    display: block;
  }

  .controls {
    grid-template-columns: minmax(0, 1fr);
  }

  .record {
    grid-template-columns: minmax(0, 1fr) auto;
    gap: 12px;
  }

  .record-main {
    grid-column: 1 / -1;
    grid-row: 2;
  }

  .tag {
    grid-column: 2;
    grid-row: 1;
  }

  .record-actions {
    grid-column: 1 / -1;
    grid-row: 3;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
  }

  .change-request {
    white-space: normal;
  }

  footer {
    padding: 27px 20px;
  }
}

/* Small phones */
@media (max-width: 470px) {
  .brand {
    gap: 8px;
    font-size: .92rem;
  }

  .brand-logo {
    width: 36px;
    height: 36px;
    flex-basis: 36px;
  }

  .type-grid,
  .feature-grid {
    grid-template-columns: minmax(0, 1fr);
  }

  .hero-actions {
    align-items: flex-start;
    flex-direction: column;
  }

  footer {
    display: block;
  }

  footer > span {
    margin-top: 12px;
  }
}
