<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Dhruv Sharma — Builder & Operator</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,200;0,9..144,400;0,9..144,600;1,9..144,200;1,9..144,400&family=Geist:wght@300;400;500&family=Geist+Mono:wght@300;400&display=swap" rel="stylesheet"/>

<style>
/* ═══════════════════════════════════════════════
   ROOT & RESET
═══════════════════════════════════════════════ */
:root {
  /* Winter Chill palette */
  --ice:    #EEF8FA;   /* near white */
  --c0:     #B8E3E9;   /* light blue */
  --c1:     #93B1B5;   /* muted teal */
  --c2:     #4F7C82;   /* deep teal — primary accent */
  --ink:    #0B2E33;   /* dark green — text/headings */
  --ink70:  rgba(11,46,51,.7);
  --ink40:  rgba(11,46,51,.4);
  --ink15:  rgba(11,46,51,.08);
  --ink08:  rgba(11,46,51,.05);

  --f-display: 'Fraunces', Georgia, serif;
  --f-body:    'Geist', sans-serif;
  --f-mono:    'Geist Mono', monospace;

  --ease:    cubic-bezier(.22,1,.36,1);
  --ease2:   cubic-bezier(.4,0,.2,1);
  --t-fast:  .25s;
  --t-mid:   .55s;
  --t-slow:  .9s;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { font-size: 16px; scroll-behavior: smooth; }

body {
  font-family: var(--f-body);
  font-weight: 300;
  color: var(--ink);
  background: var(--ice);
  overflow-x: hidden;
  cursor: none;
  -webkit-font-smoothing: antialiased;
}

a { color: inherit; text-decoration: none; }
img { display: block; max-width: 100%; }

/* ═══════════════════════════════════════════════
   CUSTOM CURSOR
═══════════════════════════════════════════════ */
#cur {
  position: fixed; width: 8px; height: 8px;
  background: var(--c2); border-radius: 50%;
  pointer-events: none; z-index: 9999;
  transform: translate(-50%,-50%);
  transition: width .35s var(--ease), height .35s var(--ease), background .3s;
  mix-blend-mode: multiply;
}
#cur-r {
  position: fixed; width: 32px; height: 32px;
  border: 1.5px solid rgba(79,124,130,.35);
  border-radius: 50%; pointer-events: none; z-index: 9998;
  transform: translate(-50%,-50%);
  transition: width .4s var(--ease), height .4s var(--ease), border-color .3s;
}
body.hov #cur { width: 14px; height: 14px; background: var(--c2); }
body.hov #cur-r { width: 52px; height: 52px; border-color: rgba(79,124,130,.5); }

/* ═══════════════════════════════════════════════
   LOADER
═══════════════════════════════════════════════ */
#loader {
  position: fixed; inset: 0; background: var(--ice); z-index: 8888;
  display: flex; flex-direction: column;
  align-items: center; justify-content: center; gap: 2.5rem;
  transition: opacity .8s var(--ease), visibility .8s var(--ease);
}
#loader.gone { opacity: 0; visibility: hidden; pointer-events: none; }
.ld-logo {
  font-family: var(--f-display); font-weight: 200; font-style: italic;
  font-size: clamp(2rem,5vw,3.5rem);
  color: var(--ink); letter-spacing: .06em; overflow: hidden;
}
.ld-logo span {
  display: inline-block; opacity: 0;
  transform: translateY(60%);
  animation: letter-rise .65s var(--ease) forwards;
}
.ld-track {
  width: 180px; height: 1px; background: var(--c0); overflow: hidden; position: relative;
}
.ld-fill {
  position: absolute; top: 0; left: -100%; width: 100%; height: 100%;
  background: linear-gradient(90deg, var(--c1), var(--c2));
  animation: load-sweep 1.6s .4s var(--ease2) forwards;
}
@keyframes letter-rise { to { opacity: 1; transform: translateY(0); } }
@keyframes load-sweep  { to { left: 0; } }

/* ═══════════════════════════════════════════════
   NOISE GRAIN (subtle texture)
═══════════════════════════════════════════════ */
body::before {
  content: '';
  position: fixed; inset: 0; pointer-events: none; z-index: 999;
  opacity: .018;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
}

/* ═══════════════════════════════════════════════
   NAV
═══════════════════════════════════════════════ */
nav {
  position: fixed; top: 0; left: 0; right: 0; z-index: 500;
  display: flex; justify-content: space-between; align-items: center;
  padding: 1.5rem 5rem;
  transition: padding var(--t-mid) var(--ease), background var(--t-mid), box-shadow var(--t-mid);
}
nav.scrolled {
  padding: 1rem 5rem;
  background: rgba(238,248,250,.82);
  backdrop-filter: blur(16px);
  -webkit-backdrop-filter: blur(16px);
  box-shadow: 0 1px 0 rgba(11,46,51,.06);
}
.n-logo {
  font-family: var(--f-display); font-style: italic; font-weight: 200;
  font-size: 1.15rem; color: var(--ink); letter-spacing: .04em;
  transition: color var(--t-fast);
}
.n-menu {
  display: flex; gap: 2.8rem; list-style: none;
  font-family: var(--f-mono); font-size: .6rem;
  letter-spacing: .18em; text-transform: uppercase;
}
.n-menu a {
  color: var(--ink40);
  transition: color var(--t-fast);
  position: relative; padding-bottom: 2px;
}
.n-menu a::after {
  content: '';
  position: absolute; bottom: 0; left: 0; right: 0;
  height: 1px; background: var(--c2);
  transform: scaleX(0); transform-origin: left;
  transition: transform var(--t-mid) var(--ease);
}
.n-menu a:hover, .n-menu a.on { color: var(--ink); }
.n-menu a:hover::after, .n-menu a.on::after { transform: scaleX(1); }

/* ═══════════════════════════════════════════════
   SECTION BASE
═══════════════════════════════════════════════ */
section {
  position: relative;
  padding: 9rem 5rem 7rem;
  border-bottom: 1px solid var(--ink15);
}

.s-tag {
  font-family: var(--f-mono); font-size: .58rem;
  letter-spacing: .24em; text-transform: uppercase;
  color: var(--c2); margin-bottom: 2rem;
  display: flex; align-items: center; gap: .8rem;
  opacity: 0; transform: translateY(12px);
  transition: opacity var(--t-slow) var(--ease), transform var(--t-slow) var(--ease);
}
.s-tag.in { opacity: 1; transform: none; }
.s-tag::before {
  content: ''; width: 24px; height: 1px; background: var(--c2); flex-shrink: 0;
}

/* ═══════════════════════════════════════════════
   REVEAL SYSTEM
═══════════════════════════════════════════════ */
.rv {
  opacity: 0; transform: translateY(22px);
  transition:
    opacity var(--t-slow) var(--ease),
    transform var(--t-slow) var(--ease);
}
.rv.in { opacity: 1; transform: translateY(0); }
.d1 { transition-delay: .08s; }
.d2 { transition-delay: .18s; }
.d3 { transition-delay: .28s; }
.d4 { transition-delay: .4s;  }
.d5 { transition-delay: .52s; }
.d6 { transition-delay: .64s; }

/* ═══════════════════════════════════════════════
   HERO
═══════════════════════════════════════════════ */
#hero {
  min-height: 100vh;
  display: flex; flex-direction: column; justify-content: flex-end;
  padding: 0 5rem 6rem;
  overflow: hidden;
  background: linear-gradient(160deg, var(--ice) 0%, #DFF3F7 55%, #CBE9EE 100%);
}

/* Hero canvas */
#hero-canvas {
  position: absolute; inset: 0; z-index: 0; pointer-events: none;
}

/* Mesh gradient blobs */
.h-blob {
  position: absolute; border-radius: 50%;
  filter: blur(70px); pointer-events: none; z-index: 0;
  animation: blob-drift 16s ease-in-out infinite alternate;
}
.h-blob-1 {
  width: 500px; height: 500px;
  background: rgba(184,227,233,.45);
  top: -10%; right: 5%;
  animation-delay: 0s;
}
.h-blob-2 {
  width: 380px; height: 380px;
  background: rgba(147,177,181,.3);
  bottom: 5%; right: 25%;
  animation-delay: -5s;
}
.h-blob-3 {
  width: 300px; height: 300px;
  background: rgba(79,124,130,.12);
  top: 30%; left: 10%;
  animation-delay: -9s;
}
@keyframes blob-drift {
  0%   { transform: translate(0,0) scale(1); }
  100% { transform: translate(30px,20px) scale(1.08); }
}

.h-top {
  position: absolute; top: 5.5rem; left: 5rem; right: 5rem;
  display: flex; justify-content: space-between; align-items: flex-start; z-index: 2;
}
.h-pill {
  font-family: var(--f-mono); font-size: .58rem; letter-spacing: .18em; text-transform: uppercase;
  color: var(--c2); border: 1px solid rgba(79,124,130,.3);
  padding: .4rem .9rem; background: rgba(238,248,250,.7);
  backdrop-filter: blur(8px);
  opacity: 0; animation: fade-up 1s .8s var(--ease) forwards;
}
.h-loc {
  font-family: var(--f-mono); font-size: .58rem; letter-spacing: .12em;
  color: var(--ink40); text-align: right; line-height: 1.9;
  opacity: 0; animation: fade-up 1s .9s var(--ease) forwards;
}

.h-inner { position: relative; z-index: 2; }

.h-eyebrow {
  font-family: var(--f-mono); font-size: .62rem; letter-spacing: .2em;
  text-transform: uppercase; color: var(--c2); margin-bottom: 1.6rem;
  opacity: 0; animation: fade-up 1s .7s var(--ease) forwards;
}

.h-name {
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(4.5rem, 12vw, 11rem);
  line-height: .92; letter-spacing: -.02em;
  color: var(--ink); margin-bottom: 3rem;
}
.h-name .row { display: block; overflow: hidden; }
.h-name .row span {
  display: block; opacity: 0; transform: translateY(100%);
  animation: rise 1.1s var(--ease) forwards;
}
.h-name .row:nth-child(1) span { animation-delay: .85s; }
.h-name .row:nth-child(2) span { animation-delay: 1s; }
.h-name .row:nth-child(3) span {
  animation-delay: 1.15s;
  font-style: italic; color: var(--c2);
}

.h-sub {
  display: flex; gap: 2.5rem; align-items: center; flex-wrap: wrap;
  font-family: var(--f-mono); font-size: .62rem;
  letter-spacing: .14em; text-transform: uppercase; color: var(--ink40);
  opacity: 0; animation: fade-up 1s 1.4s var(--ease) forwards;
}
.h-sep { width: 3px; height: 3px; background: var(--c1); border-radius: 50%; }

.h-cta {
  margin-top: 2.5rem;
  opacity: 0; animation: fade-up 1s 1.6s var(--ease) forwards;
  display: flex; gap: 1rem; align-items: center; flex-wrap: wrap;
}

/* Buttons */
.btn {
  display: inline-block; padding: .75rem 1.8rem;
  font-family: var(--f-mono); font-size: .6rem;
  letter-spacing: .16em; text-transform: uppercase;
  border-radius: 2px; transition: all var(--t-mid) var(--ease);
  position: relative; overflow: hidden;
}
.btn-primary {
  background: var(--ink); color: var(--ice);
  box-shadow: 0 2px 16px rgba(11,46,51,.14);
}
.btn-primary:hover {
  background: var(--c2);
  transform: translateY(-2px);
  box-shadow: 0 6px 28px rgba(79,124,130,.28);
}
.btn-ghost {
  border: 1px solid rgba(11,46,51,.18); color: var(--ink70);
}
.btn-ghost:hover {
  border-color: var(--c2); color: var(--c2);
  transform: translateY(-2px);
  background: rgba(79,124,130,.05);
}

/* Scroll indicator */
.h-scroll-hint {
  position: absolute; bottom: 3.5rem; right: 5rem; z-index: 2;
  display: flex; flex-direction: column; align-items: center; gap: .7rem;
  font-family: var(--f-mono); font-size: .52rem; letter-spacing: .2em;
  text-transform: uppercase; color: var(--ink40);
  opacity: 0; animation: fade-up 1s 2s var(--ease) forwards;
}
.h-scroll-bar {
  width: 1px; height: 52px;
  background: rgba(11,46,51,.12); overflow: hidden; position: relative;
}
.h-scroll-bar::after {
  content: ''; position: absolute; top: -100%; left: 0;
  width: 100%; height: 100%;
  background: linear-gradient(to bottom, transparent, var(--c2));
  animation: scroll-fall 2.5s 2.4s infinite ease-in-out;
}
@keyframes scroll-fall { 0% { top: -100%; } 100% { top: 100%; } }

/* ═══════════════════════════════════════════════
   ABOUT
═══════════════════════════════════════════════ */
#about { background: var(--ice); }
.ab-wrap {
  display: grid; grid-template-columns: 1fr 1.6fr; gap: 8rem;
  margin-top: 4rem; align-items: start;
}
.ab-sticky { position: sticky; top: 8rem; }
.ab-hl {
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(2.2rem, 4vw, 3.6rem);
  line-height: 1.1; letter-spacing: -.02em; color: var(--ink); margin-bottom: 2rem;
}
.ab-hl em { font-style: italic; color: var(--c2); }
.ab-chips { display: flex; flex-wrap: wrap; gap: .45rem; }
.chip {
  font-family: var(--f-mono); font-size: .54rem;
  letter-spacing: .12em; text-transform: uppercase;
  border: 1px solid rgba(79,124,130,.22);
  padding: .32rem .72rem; color: var(--c2); border-radius: 2px;
  transition: all var(--t-fast) var(--ease);
  background: rgba(79,124,130,.04);
}
.chip:hover {
  background: var(--c2); color: var(--ice);
  border-color: var(--c2);
  transform: translateY(-1px);
  box-shadow: 0 4px 14px rgba(79,124,130,.2);
}
.ab-body p {
  font-size: .92rem; color: var(--ink70); line-height: 1.95; margin-bottom: 1.4rem;
}
.ab-body p strong { color: var(--ink); font-weight: 500; }
.vitals {
  display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem; margin-top: 2.8rem;
}
.vt {
  border-top: 1px solid var(--ink15); padding-top: 1rem;
  transition: border-color var(--t-fast);
}
.vt:hover { border-color: var(--c2); }
.vt-l {
  font-family: var(--f-mono); font-size: .52rem; letter-spacing: .18em;
  text-transform: uppercase; color: var(--ink40); margin-bottom: .3rem;
}
.vt-v { font-size: .88rem; font-weight: 500; color: var(--ink); }

/* ═══════════════════════════════════════════════
   WORK EXPERIENCE
═══════════════════════════════════════════════ */
#work { background: var(--ice); }
.wk-intro {
  display: grid; grid-template-columns: auto 1fr; gap: 6rem;
  align-items: end; margin: 4rem 0 5rem;
}
.wk-big {
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(5rem, 11vw, 10rem); line-height: .88; letter-spacing: -.03em;
  color: rgba(11,46,51,.06);
}
.wk-note {
  font-size: .9rem; color: var(--ink70); line-height: 1.9; max-width: 380px;
}

/* Timeline */
.tl { position: relative; padding-left: .5rem; }
.tl::before {
  content: ''; position: absolute; left: 0; top: 0; bottom: 0;
  width: 1px;
  background: linear-gradient(to bottom, var(--c0), var(--c1) 50%, var(--c0));
}
.job {
  padding: 2.8rem 0 2.8rem 3.5rem;
  border-bottom: 1px solid var(--ink15); position: relative;
  transition: background var(--t-mid);
  border-radius: 0 8px 8px 0;
}
.job:hover { background: rgba(184,227,233,.1); }
.job::before {
  content: ''; position: absolute; left: -4.5px; top: 3.4rem;
  width: 9px; height: 9px; border-radius: 50%;
  background: var(--ice); border: 1.5px solid var(--c1);
  transition: background var(--t-fast), border-color var(--t-fast), box-shadow var(--t-fast);
}
.job:hover::before {
  background: var(--c2); border-color: var(--c2);
  box-shadow: 0 0 0 4px rgba(79,124,130,.15);
}
.jm { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 1rem; flex-wrap: wrap; gap: .5rem; }
.jco {
  font-family: var(--f-display); font-weight: 400; font-size: 1.4rem;
  letter-spacing: .01em; color: var(--ink);
}
.jp {
  font-family: var(--f-mono); font-size: .55rem; letter-spacing: .14em;
  text-transform: uppercase; color: var(--c2);
  border: 1px solid rgba(79,124,130,.25); padding: .28rem .65rem;
  align-self: center; border-radius: 2px;
  background: rgba(79,124,130,.05);
}
.jr { font-family: var(--f-mono); font-size: .6rem; font-weight: 400; letter-spacing: .14em; text-transform: uppercase; color: var(--ink40); margin-bottom: 1.4rem; }
.jpts { list-style: none; }
.jpts li {
  display: grid; grid-template-columns: 1.2rem 1fr; gap: .7rem;
  font-size: .86rem; color: var(--ink70); line-height: 1.8;
  padding: .45rem 0; border-bottom: 1px solid rgba(11,46,51,.04);
  transition: color var(--t-fast);
}
.jpts li:hover { color: var(--ink); }
.jpts li::before { content: '→'; color: var(--c1); font-size: .7rem; margin-top: .04rem; }
.jpts li strong { color: var(--ink); font-weight: 500; }

/* ═══════════════════════════════════════════════
   V-GTHR
═══════════════════════════════════════════════ */
#vgthr {
  background: linear-gradient(175deg, #DFF3F7 0%, var(--ice) 100%);
}

.vg-hero {
  display: grid; grid-template-columns: 1fr 1.4fr; gap: 6rem;
  margin: 4rem 0 5rem; align-items: end;
}
.vg-wordmark {
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(5rem, 13vw, 12rem);
  line-height: .88; letter-spacing: -.03em; color: var(--ink);
  position: relative; overflow: hidden;
}
.vg-wordmark .wm-fill {
  display: block;
  background: linear-gradient(135deg, var(--ink) 0%, var(--c2) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.vg-wordmark .wm-tag {
  display: block; font-size: .35em; letter-spacing: .05em;
  font-style: italic; color: var(--c1); -webkit-text-fill-color: var(--c1);
  margin-top: .2em;
}
.vg-right {}
.vg-desc {
  font-size: .95rem; color: var(--ink70); line-height: 1.95;
  margin-bottom: 2rem;
}
.vg-desc strong { color: var(--ink); font-weight: 500; }
.vg-status {
  display: inline-flex; align-items: center; gap: .5rem;
  font-family: var(--f-mono); font-size: .58rem; letter-spacing: .16em;
  text-transform: uppercase; color: var(--c2);
  border: 1px solid rgba(79,124,130,.25); padding: .4rem .9rem;
  border-radius: 20px; background: rgba(79,124,130,.05);
}
.vg-status-dot {
  width: 6px; height: 6px; border-radius: 50%;
  background: var(--c2); animation: pulse 2.5s ease infinite;
}
@keyframes pulse {
  0%, 100% { opacity: 1; transform: scale(1); }
  50%        { opacity: .5; transform: scale(.7); }
}

/* Skills grid */
.vg-grid-label {
  font-family: var(--f-display); font-style: italic; font-weight: 200;
  font-size: clamp(1.5rem, 2.5vw, 2rem);
  color: var(--ink); margin-bottom: 2.5rem;
}
.vg-grid {
  display: grid; grid-template-columns: repeat(3,1fr);
  gap: 1px; background: rgba(11,46,51,.07);
  border: 1px solid rgba(11,46,51,.07);
  border-radius: 4px; overflow: hidden;
}
.vgc {
  background: var(--ice); padding: 2.4rem;
  transition: background var(--t-mid) var(--ease), transform var(--t-mid) var(--ease), box-shadow var(--t-mid) var(--ease);
  position: relative;
}
.vgc:hover {
  background: rgba(184,227,233,.25);
  transform: translateY(-2px);
  z-index: 1; box-shadow: 0 8px 32px rgba(11,46,51,.08);
}
.vgc-n {
  font-family: var(--f-mono); font-size: .54rem; letter-spacing: .18em;
  color: var(--c2); margin-bottom: 1rem;
}
.vgc-t {
  font-family: var(--f-display); font-weight: 400; font-size: 1.05rem;
  line-height: 1.25; color: var(--ink); margin-bottom: .8rem;
}
.vgc-b { font-size: .82rem; color: var(--ink70); line-height: 1.82; }

/* Positioning */
.vg-pos {
  margin-top: 5rem; padding: 3.5rem;
  background: linear-gradient(135deg, rgba(184,227,233,.35) 0%, rgba(147,177,181,.2) 100%);
  border: 1px solid rgba(79,124,130,.15);
  border-radius: 4px;
  display: grid; grid-template-columns: 1fr 2fr; gap: 5rem; align-items: center;
}
.vg-pos-l {
  font-family: var(--f-display); font-style: italic; font-weight: 200;
  font-size: clamp(1.6rem, 2.5vw, 2.2rem); line-height: 1.2; color: var(--c2);
}
.vg-pos-r {
  font-size: .92rem; color: var(--ink70); line-height: 1.95;
  border-left: 1px solid rgba(79,124,130,.2); padding-left: 3rem;
}

/* Auxiciux */
.aux-row {
  margin-top: 3.5rem; padding: 2.5rem;
  border: 1px solid rgba(11,46,51,.08);
  border-radius: 4px; display: flex; justify-content: space-between;
  align-items: center; gap: 2rem; flex-wrap: wrap;
  transition: border-color var(--t-fast), box-shadow var(--t-fast);
  background: rgba(238,248,250,.6);
}
.aux-row:hover {
  border-color: rgba(79,124,130,.3);
  box-shadow: 0 4px 20px rgba(11,46,51,.06);
}
.aux-co { font-family: var(--f-display); font-weight: 400; font-size: 1.3rem; color: var(--ink); }
.aux-badge {
  font-family: var(--f-mono); font-size: .54rem; letter-spacing: .16em;
  text-transform: uppercase; color: var(--c2);
  border: 1px solid rgba(79,124,130,.25); padding: .3rem .7rem;
  border-radius: 2px; background: rgba(79,124,130,.06);
}
.aux-txt { font-size: .86rem; color: var(--ink70); line-height: 1.85; max-width: 540px; }

/* ═══════════════════════════════════════════════
   SKILLS
═══════════════════════════════════════════════ */
#skills { background: var(--ice); }
.sk-top {
  display: grid; grid-template-columns: 1fr 1fr; gap: 4rem;
  margin: 4rem 0 3.5rem; align-items: start;
}
.sk-hl {
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(2rem, 3.5vw, 3rem); line-height: 1.1; letter-spacing: -.01em; color: var(--ink);
}
.sk-hl em { font-style: italic; color: var(--c2); }
.sk-note { font-size: .88rem; color: var(--ink70); line-height: 1.95; }

.sk-cols { display: grid; grid-template-columns: repeat(3,1fr); gap: 1px; background: rgba(11,46,51,.07); border: 1px solid rgba(11,46,51,.07); border-radius: 4px; overflow: hidden; }
.skc { background: var(--ice); padding: 2.2rem 2rem; }
.skc-h {
  font-family: var(--f-mono); font-size: .56rem; letter-spacing: .2em; text-transform: uppercase;
  color: var(--c2); padding-bottom: 1rem; margin-bottom: 1.4rem;
  border-bottom: 1px solid rgba(11,46,51,.08);
}
.ski {
  font-size: .84rem; color: var(--ink70); line-height: 1;
  padding: .65rem 0; border-bottom: 1px solid rgba(11,46,51,.05);
  transition: color var(--t-fast), padding-left var(--t-fast) var(--ease);
  display: flex; align-items: center; gap: .6rem; cursor: default;
}
.ski:hover { color: var(--c2); padding-left: .3rem; }
.ski::before {
  content: ''; width: 3px; height: 3px;
  background: rgba(11,46,51,.2); border-radius: 50%; flex-shrink: 0;
  transition: background var(--t-fast);
}
.ski:hover::before { background: var(--c2); }

.tools-row { display: flex; flex-wrap: wrap; gap: .55rem; margin-top: 2.8rem; }
.tool {
  font-family: var(--f-mono); font-size: .57rem; letter-spacing: .12em; text-transform: uppercase;
  border: 1px solid rgba(11,46,51,.1); padding: .36rem .82rem; color: var(--ink40);
  border-radius: 2px; transition: all var(--t-fast) var(--ease);
  background: rgba(238,248,250,.6);
}
.tool:hover {
  border-color: var(--c2); color: var(--c2);
  background: rgba(79,124,130,.06);
  transform: translateY(-1px);
}

/* ═══════════════════════════════════════════════
   EDUCATION
═══════════════════════════════════════════════ */
#edu {
  background: linear-gradient(175deg, var(--ice) 0%, #DFF3F7 100%);
}
.ed-sp { display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; margin-top: 4rem; }
.edx {
  border: 1px solid rgba(11,46,51,.08);
  padding: 2.5rem; border-radius: 4px;
  transition: border-color var(--t-fast), box-shadow var(--t-fast), transform var(--t-mid) var(--ease);
  background: rgba(238,248,250,.7);
}
.edx:hover {
  border-color: rgba(79,124,130,.3);
  box-shadow: 0 8px 32px rgba(11,46,51,.07);
  transform: translateY(-2px);
}
.edx-d { font-family: var(--f-display); font-weight: 400; font-size: 1.15rem; line-height: 1.2; margin-bottom: .5rem; color: var(--ink); }
.edx-i { font-size: .82rem; color: var(--ink40); margin-bottom: .3rem; }
.edx-y { font-family: var(--f-mono); font-size: .56rem; letter-spacing: .16em; text-transform: uppercase; color: var(--c2); }

.certs { margin-top: 3.5rem; padding-top: 2.5rem; border-top: 1px solid var(--ink15); }
.certs-l { font-family: var(--f-mono); font-size: .56rem; letter-spacing: .2em; text-transform: uppercase; color: var(--c2); margin-bottom: 1.6rem; }
.certs-w { display: flex; flex-wrap: wrap; gap: .65rem; }
.cert {
  border: 1px solid rgba(11,46,51,.1); padding: .6rem 1.1rem;
  font-size: .78rem; color: var(--ink70); border-radius: 2px;
  transition: all var(--t-fast) var(--ease);
  background: rgba(238,248,250,.6);
}
.cert:hover {
  border-color: var(--c2); color: var(--c2);
  background: rgba(79,124,130,.05);
  transform: translateY(-1px);
  box-shadow: 0 4px 14px rgba(79,124,130,.12);
}

/* ═══════════════════════════════════════════════
   LEADERSHIP
═══════════════════════════════════════════════ */
#leadership { background: var(--ice); }
.ld-g { display: grid; grid-template-columns: repeat(3,1fr); gap: 1.5rem; margin-top: 4rem; }
.lc {
  border: 1px solid rgba(11,46,51,.08);
  padding: 2.5rem; border-radius: 4px;
  transition: all var(--t-mid) var(--ease);
  background: rgba(238,248,250,.7); position: relative; overflow: hidden;
}
.lc::after {
  content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px;
  background: linear-gradient(90deg, var(--c1), var(--c2));
  transform: translateX(-100%); transition: transform var(--t-slow) var(--ease);
}
.lc:hover {
  border-color: rgba(79,124,130,.25);
  box-shadow: 0 8px 32px rgba(11,46,51,.07);
  transform: translateY(-3px);
}
.lc:hover::after { transform: translateX(0); }
.lc-i { font-family: var(--f-mono); font-size: .55rem; letter-spacing: .18em; text-transform: uppercase; color: var(--c2); margin-bottom: 1rem; }
.lc-t { font-family: var(--f-display); font-size: 1.1rem; font-weight: 400; line-height: 1.3; margin-bottom: .65rem; color: var(--ink); }
.lc-s { font-size: .82rem; color: var(--ink70); line-height: 1.78; }

.int-strip {
  margin-top: 4rem; padding-top: 2rem; border-top: 1px solid var(--ink15);
  display: flex; align-items: center; gap: 2rem; flex-wrap: wrap;
}
.int-l { font-family: var(--f-mono); font-size: .55rem; letter-spacing: .2em; text-transform: uppercase; color: var(--ink40); flex-shrink: 0; }
.int-w { display: flex; gap: 1.4rem; flex-wrap: wrap; }
.int-w span {
  font-size: .84rem; color: var(--ink40);
  transition: color var(--t-fast); cursor: default;
}
.int-w span:hover { color: var(--c2); }

/* ═══════════════════════════════════════════════
   CONTACT
═══════════════════════════════════════════════ */
#contact {
  min-height: 80vh; display: flex; flex-direction: column; justify-content: center;
  overflow: hidden;
  background: linear-gradient(160deg, #D0EDF2 0%, var(--c0) 60%, #A8D4DC 100%);
}
.ct-ghost {
  position: absolute; right: -2rem; bottom: -3rem;
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(10rem, 22vw, 22rem);
  color: rgba(11,46,51,.05); pointer-events: none; user-select: none;
  letter-spacing: -.04em;
}
.ct-inner { position: relative; z-index: 2; }
.ct-hl {
  font-family: var(--f-display); font-weight: 200;
  font-size: clamp(3.5rem, 9vw, 8rem);
  line-height: .92; letter-spacing: -.02em; color: var(--ink); margin-bottom: 3.5rem;
}
.ct-hl em { font-style: italic; color: var(--c2); }
.ct-row { display: flex; gap: 1rem; flex-wrap: wrap; margin-bottom: 3rem; }
.cl {
  display: inline-block; padding: .85rem 2rem;
  border: 1px solid rgba(11,46,51,.18);
  font-family: var(--f-mono); font-size: .58rem;
  letter-spacing: .16em; text-transform: uppercase; color: var(--ink70);
  border-radius: 2px; position: relative; overflow: hidden;
  transition: color var(--t-mid) var(--ease), border-color var(--t-mid);
  background: rgba(238,248,250,.5); backdrop-filter: blur(4px);
}
.cl::before {
  content: ''; position: absolute; inset: 0;
  background: var(--ink); transform: translateY(101%);
  transition: transform var(--t-mid) var(--ease); z-index: 0;
}
.cl span { position: relative; z-index: 1; transition: color var(--t-mid); }
.cl:hover { border-color: var(--ink); }
.cl:hover::before { transform: translateY(0); }
.cl:hover span { color: var(--ice); }
.cl.pri {
  background: var(--ink); border-color: var(--ink);
}
.cl.pri span { color: var(--ice); }
.cl.pri::before { background: var(--c2); }
.cl.pri:hover span { color: var(--ice); }

.ct-detail {
  font-family: var(--f-mono); font-size: .64rem;
  letter-spacing: .1em; color: var(--ink40); line-height: 2.1;
}

/* ═══════════════════════════════════════════════
   FOOTER
═══════════════════════════════════════════════ */
footer {
  padding: 2rem 5rem;
  display: flex; justify-content: space-between; align-items: center;
  font-family: var(--f-mono); font-size: .55rem;
  letter-spacing: .12em; text-transform: uppercase; color: var(--ink40);
  border-top: 1px solid var(--ink15);
  background: var(--ice);
}

/* ═══════════════════════════════════════════════
   GLASSMORPHISM PANEL (hero stat)
═══════════════════════════════════════════════ */
.glass-panel {
  background: rgba(238,248,250,.55);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255,255,255,.6);
  border-radius: 6px;
  box-shadow: 0 4px 24px rgba(11,46,51,.07);
}

/* ═══════════════════════════════════════════════
   KEYFRAMES
═══════════════════════════════════════════════ */
@keyframes rise    { to { opacity: 1; transform: translateY(0); } }
@keyframes fade-up { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: none; } }

/* ═══════════════════════════════════════════════
   RESPONSIVE
═══════════════════════════════════════════════ */
@media(max-width: 960px) {
  nav { padding: 1.2rem 2rem; }
  nav.scrolled { padding: 1rem 2rem; }
  .n-menu { display: none; }
  section { padding: 6.5rem 2rem 5rem; }
  #hero { padding: 0 2rem 5rem; }
  .h-top { left: 2rem; right: 2rem; }
  .h-scroll-hint { display: none; }
  .ab-wrap, .wk-intro, .sk-top, .ed-sp, .vg-hero, .vg-pos { grid-template-columns: 1fr; gap: 2.5rem; }
  .ab-sticky { position: static; }
  .wk-big { display: none; }
  .vg-grid, .sk-cols, .ld-g { grid-template-columns: 1fr; }
  footer { flex-direction: column; gap: .8rem; text-align: center; padding: 1.8rem 2rem; }
  .vg-pos-r { border-left: none; padding-left: 0; border-top: 1px solid rgba(79,124,130,.2); padding-top: 2rem; }
}
</style>
</head>
<body>

<!-- Cursor -->
<div id="cur"></div>
<div id="cur-r"></div>

<!-- Loader -->
<div id="loader">
  <div class="ld-logo" id="ld-logo"></div>
  <div class="ld-track"><div class="ld-fill"></div></div>
</div>

<!-- ══════════════════════════════════════
     NAV
══════════════════════════════════════ -->
<nav id="nav">
  <div class="n-logo">D. Sharma</div>
  <ul class="n-menu">
    <li><a href="#about">About</a></li>
    <li><a href="#work">Work</a></li>
    <li><a href="#vgthr">V-GTHR</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#edu">Education</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- ══════════════════════════════════════
     HERO
══════════════════════════════════════ -->
<section id="hero">
  <canvas id="hero-canvas"></canvas>
  <div class="h-blob h-blob-1"></div>
  <div class="h-blob h-blob-2"></div>
  <div class="h-blob h-blob-3"></div>

  <div class="h-top">
    <span class="h-pill">Open · Founder's Office</span>
    <div class="h-loc">Ajmer, Rajasthan<br/>+91 90799 07146</div>
  </div>

  <div class="h-inner">
    <p class="h-eyebrow">Dhruv Sharma — Portfolio</p>
    <h1 class="h-name">
      <span class="row"><span>Builder.</span></span>
      <span class="row"><span>Operator.</span></span>
      <span class="row"><span>Founder.</span></span>
    </h1>
    <div class="h-sub">
      <span>1.8+ yrs B2B Sales</span>
      <span class="h-sep"></span>
      <span>Founder — V-GTHR</span>
      <span class="h-sep"></span>
      <span>B.Tech AI &amp; DS</span>
    </div>
    <div class="h-cta">
      <a href="#vgthr" class="btn btn-primary">View My Work</a>
      <a href="#contact" class="btn btn-ghost">Let's Talk</a>
    </div>
  </div>

  <div class="h-scroll-hint">
    <span>Scroll</span>
    <div class="h-scroll-bar"></div>
  </div>
</section>

<!-- ══════════════════════════════════════
     ABOUT
══════════════════════════════════════ -->
<section id="about">
  <p class="s-tag">About</p>
  <div class="ab-wrap">
    <div class="ab-sticky">
      <h2 class="ab-hl rv">
        Designed for<br/>
        <em>execution.</em><br/>
        Built for<br/>
        <em>the long run.</em>
      </h2>
      <div class="ab-chips rv d2">
        <span class="chip">B2B Sales</span>
        <span class="chip">Consultative</span>
        <span class="chip">Community Design</span>
        <span class="chip">0→1 Founder</span>
        <span class="chip">AI &amp; Data Science</span>
        <span class="chip">Systems thinker</span>
      </div>
    </div>
    <div class="ab-body">
      <p class="rv d1">
        1.8+ years in <strong>B2B sales, client consulting, and cross-functional project execution</strong>.
        I map requirements before pitching solutions — a discipline that shapes every brief I take on.
      </p>
      <p class="rv d2">
        Alongside professional work, I'm building <strong>V-GTHR</strong> — a trust-driven platform
        connecting strangers over shared meals through structured micro-community experiences.
        Currently at <strong>MVP stage</strong>, working toward beta.
        Co-founded <strong>Auxiciux Consultancies LLP</strong>.
      </p>
      <p class="rv d3">
        I want to work in a <strong>Founder's Office</strong> — contributing to real decisions,
        taking ownership, and building for the long term. Not chasing a title.
        Looking for the room that makes the work meaningful.
      </p>
      <div class="vitals">
        <div class="vt rv d2"><div class="vt-l">Experience</div><div class="vt-v">1.8+ Years</div></div>
        <div class="vt rv d3"><div class="vt-l">Domain</div><div class="vt-v">B2B &amp; BD</div></div>
        <div class="vt rv d4"><div class="vt-l">Degree</div><div class="vt-v">B.Tech AI &amp; DS</div></div>
        <div class="vt rv d5"><div class="vt-l">Building</div><div class="vt-v">V-GTHR — MVP</div></div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════
     WORK
══════════════════════════════════════ -->
<section id="work">
  <p class="s-tag">Work Experience</p>
  <div class="wk-intro">
    <div class="wk-big rv">Work.</div>
    <p class="wk-note rv d2">
      Two roles — consultative sales at scale, and enterprise field project coordination across three states.
      Each sharpened a different edge.
    </p>
  </div>
  <div class="tl">
    <div class="job rv d1">
      <div class="jm">
        <div class="jco">Kraft-Obench</div>
        <div class="jp">Sep 2024 – Dec 2025</div>
      </div>
      <div class="jr">Senior Business Development Executive</div>
      <ul class="jpts">
        <li><span>Led <strong>consultative sales</strong> across corporate, co-working &amp; education sectors</span></li>
        <li><span>Conducted client requirement assessments; prepared <strong>solution specs, proposals &amp; quotations</strong></span></li>
        <li><span>Coordinated ops, logistics &amp; design for <strong>multi-city installations</strong></span></li>
        <li><span>Managed <strong>Zoho CRM pipelines</strong> and tracked KPIs for performance monitoring</span></li>
        <li><span>Trained and mentored <strong>2 junior executives</strong></span></li>
        <li><span>Developed <strong>corporate sales pitch formats</strong> and contributed to conversion-improving assets</span></li>
        <li><span>Supported on-table <strong>deal closures</strong> and field project execution</span></li>
      </ul>
    </div>
    <div class="job rv d2">
      <div class="jm">
        <div class="jco">Garud Survey Pvt. Ltd.</div>
        <div class="jp">Jan 2024 – Jun 2024</div>
      </div>
      <div class="jr">Business Development Associate / Project Coordinator</div>
      <ul class="jpts">
        <li><span>Managed <strong>field research and enterprise client projects</strong> across MP, Jharkhand &amp; Rajasthan</span></li>
        <li><span>Coordinated execution teams ensuring <strong>timely project delivery</strong></span></li>
        <li><span>Handled <strong>project documentation, reporting &amp; requirement capture</strong> end-to-end</span></li>
      </ul>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════
     V-GTHR
══════════════════════════════════════ -->
<section id="vgthr">
  <p class="s-tag">Entrepreneurial Work</p>

  <div class="vg-hero">
    <div class="rv">
      <div class="vg-wordmark">
        <span class="wm-fill">V-GTHR</span>
        <span class="wm-tag">— in build.</span>
      </div>
    </div>
    <div class="vg-right rv d2">
      <p class="vg-desc">
        A platform connecting strangers over shared meals through <strong>trust-driven micro-communities</strong>
        and structured social experiences. Built on cafés as physical infrastructure for connection,
        bridging offline experience with a scalable digital platform.
      </p>
      <p class="vg-desc">
        Core thesis: converting unstructured social interactions into intentional connections
        by solving the trust gap between strangers. Currently at <strong>MVP stage</strong>.
      </p>
      <span class="vg-status">
        <span class="vg-status-dot"></span>
        MVP Stage — Working Toward Beta
      </span>
    </div>
  </div>

  <p class="vg-grid-label rv">Skills built through V-GTHR.</p>
  <div class="vg-grid">
    <div class="vgc rv d1">
      <p class="vgc-n">01</p>
      <h3 class="vgc-t">Human Behavior &amp; Social Dynamics</h3>
      <p class="vgc-b">Analyzed stranger behavior in unfamiliar social environments. Designed mechanisms to reduce friction, hesitation, and trust gaps between people who've never met.</p>
    </div>
    <div class="vgc rv d2">
      <p class="vgc-n">02</p>
      <h3 class="vgc-t">Community Design &amp; Experience Architecture</h3>
      <p class="vgc-b">Designed host-led, curated gathering frameworks. Shifted from "events" to experience systems — focused on consistency, quality control, and repeatability.</p>
    </div>
    <div class="vgc rv d3">
      <p class="vgc-n">03</p>
      <h3 class="vgc-t">Zero-to-One Product Thinking</h3>
      <p class="vgc-b">Took V-GTHR from idea → structured product vision. Defined the full user journey: discovery → trust → join → experience → retention. Built host filtering for quality.</p>
    </div>
    <div class="vgc rv d1">
      <p class="vgc-n">04</p>
      <h3 class="vgc-t">Business Model &amp; Strategic Thinking</h3>
      <p class="vgc-b">Designed a B2B2C model — cafés as paying partners, users join free. Structured clear value exchange across all stakeholders and thought through scalability constraints.</p>
    </div>
    <div class="vgc rv d2">
      <p class="vgc-n">05</p>
      <h3 class="vgc-t">Product Management &amp; Execution</h3>
      <p class="vgc-b">Translated vision into features, flows, and execution roadmap. Coordinated UI/UX and React development. End-to-end ownership across multiple functions simultaneously.</p>
    </div>
    <div class="vgc rv d3">
      <p class="vgc-n">06</p>
      <h3 class="vgc-t">Brand Thinking &amp; Narrative</h3>
      <p class="vgc-b">Defined brand identity: clean, safe, intentional, community-first. Built narrative around meaningful social connection. Aligned product experience with brand perception.</p>
    </div>
    <div class="vgc rv d1">
      <p class="vgc-n">07</p>
      <h3 class="vgc-t">Growth Strategy &amp; Distribution</h3>
      <p class="vgc-b">Designed organic growth loops driven by community. Positioned events as a distribution channel. Trust-first growth over vanity metrics — low-cost, high-retention entry points.</p>
    </div>
    <div class="vgc rv d2">
      <p class="vgc-n">08</p>
      <h3 class="vgc-t">Partnerships &amp; Ecosystem Building</h3>
      <p class="vgc-b">Developed café onboarding approach. Structured win-win partnership models. Initiated co-hosted experience collaborations and leveraged external networks for credibility.</p>
    </div>
    <div class="vgc rv d3">
      <p class="vgc-n">09 — 10</p>
      <h3 class="vgc-t">Decision-Making &amp; Founder Mindset</h3>
      <p class="vgc-b">Made strategic calls without complete data. Maintained momentum despite setbacks — including a Founders Meet that couldn't execute. Iterated, owned the outcome, kept building.</p>
    </div>
  </div>

  <div class="vg-pos rv d2">
    <div class="vg-pos-l">What V-GTHR<br/>built in me.</div>
    <p class="vg-pos-r">
      Building V-GTHR developed my ability to design human-centric systems, structure community-driven
      experiences, and translate ambiguous ideas into scalable business models — while operating with
      full ownership in uncertain, early-stage environments.
      I design systems. I run them. I extract the signal.
    </p>
  </div>

  <div class="aux-row rv d2">
    <div>
      <div class="aux-co">Auxiciux Consultancies LLP</div>
      <span class="aux-badge" style="display:inline-block;margin-top:.4rem">Co-Founder</span>
    </div>
    <p class="aux-txt">
      Co-founded a multi-domain service delivery consultancy with partner service providers.
      Also ran an internal front-end development programme.
    </p>
  </div>
</section>

<!-- ══════════════════════════════════════
     SKILLS
══════════════════════════════════════ -->
<section id="skills">
  <p class="s-tag">Professional Skills</p>
  <div class="sk-top">
    <h2 class="sk-hl rv">What I<br/>bring<br/><em>to the table.</em></h2>
    <p class="sk-note rv d2">Commercial, operational, and technical capabilities — built through client-facing work, startup building, and self-directed learning. A map of real muscle, not a keyword list.</p>
  </div>
  <div class="sk-cols">
    <div class="skc rv d1">
      <div class="skc-h">Commercial</div>
      <div class="ski">B2B Sales &amp; Business Development</div>
      <div class="ski">Client Consulting &amp; Req. Analysis</div>
      <div class="ski">Cold Calling &amp; Lead Qualification</div>
      <div class="ski">Proposal Development</div>
      <div class="ski">Corporate Sales Pitching</div>
      <div class="ski">Market Research</div>
    </div>
    <div class="skc rv d2">
      <div class="skc-h">Operations</div>
      <div class="ski">CRM Management &amp; KPI Tracking</div>
      <div class="ski">Project Coordination</div>
      <div class="ski">Cross-functional Team Ops</div>
      <div class="ski">Field Operations Execution</div>
      <div class="ski">Business Analysis &amp; Reporting</div>
      <div class="ski">Team Mentoring</div>
    </div>
    <div class="skc rv d3">
      <div class="skc-h">Technical</div>
      <div class="ski">Python &amp; SQL</div>
      <div class="ski">Power BI</div>
      <div class="ski">ML APIs for Data Extraction</div>
      <div class="ski">Flutter (Mobile Dev)</div>
      <div class="ski">Front-End Development</div>
      <div class="ski">Business Analyst Practices</div>
    </div>
  </div>
  <div class="tools-row rv d2">
    <span class="tool">Zoho CRM</span>
    <span class="tool">Google Workspace</span>
    <span class="tool">Microsoft Office</span>
    <span class="tool">Canva</span>
    <span class="tool">PowerDirector</span>
    <span class="tool">ChatGPT</span>
    <span class="tool">Google Colab</span>
    <span class="tool">React (coordination)</span>
  </div>
</section>

<!-- ══════════════════════════════════════
     EDUCATION
══════════════════════════════════════ -->
<section id="edu">
  <p class="s-tag">Education</p>
  <div class="ed-sp">
    <div class="edx rv d1">
      <div class="edx-d">B.Tech — Artificial Intelligence &amp; Data Science</div>
      <div class="edx-i">Poornima Institute of Engineering &amp; Technology</div>
      <div class="edx-y">2020 – 2024</div>
    </div>
    <div class="edx rv d2">
      <div class="edx-d">10+2 — Science (Mathematics)</div>
      <div class="edx-i">Kendriya Vidyalaya No. 2, Ajmer</div>
      <div class="edx-y">Pre-2020</div>
    </div>
  </div>
  <div class="certs rv d2">
    <div class="certs-l">Certifications &amp; Programmes</div>
    <div class="certs-w">
      <span class="cert">Flutter Mobile App Dev</span>
      <span class="cert">Front-End Dev — Auxiciux LLP</span>
      <span class="cert">Python</span>
      <span class="cert">SQL</span>
      <span class="cert">Power BI</span>
      <span class="cert">ML APIs for Data Extraction</span>
      <span class="cert">Business Analyst Practices — Madrid Softwares, Delhi</span>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════
     LEADERSHIP
══════════════════════════════════════ -->
<section id="leadership">
  <p class="s-tag">Leadership &amp; Beyond</p>
  <div class="ld-g">
    <div class="lc rv d1">
      <div class="lc-i">Student Council</div>
      <div class="lc-t">Co-Chair</div>
      <div class="lc-s">Poornima Institute — council operations, event coordination, and campus representation.</div>
    </div>
    <div class="lc rv d2">
      <div class="lc-i">Photography Club</div>
      <div class="lc-t">Vice Captain — Perfect Pixels</div>
      <div class="lc-s">Managed club direction, shoots, and creative output alongside a team of photographers.</div>
    </div>
    <div class="lc rv d3">
      <div class="lc-i">School Council</div>
      <div class="lc-t">Badge Holder — 7 Consecutive Years</div>
      <div class="lc-s">Held school council responsibilities across seven academic years — consistency and initiative from the start.</div>
    </div>
  </div>
  <div class="int-strip rv d2">
    <span class="int-l">Outside Work</span>
    <div class="int-w">
      <span>Drums</span><span>Photography</span><span>Poetry</span>
      <span>Dance</span><span>Video Editing</span><span>Driving</span>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════
     CONTACT
══════════════════════════════════════ -->
<section id="contact">
  <div class="ct-ghost">Let's.</div>
  <div class="ct-inner">
    <p class="s-tag rv">Contact</p>
    <h2 class="ct-hl rv d1">
      Let's<br/><em>connect.</em>
    </h2>
    <div class="ct-row rv d2">
      <a href="mailto:dhruv.90799@gmail.com" class="cl pri"><span>dhruv.90799@gmail.com</span></a>
      <a href="tel:+919079907146" class="cl"><span>+91 90799 07146</span></a>
      <a href="https://www.linkedin.com/in/dhruv-sharma-821387203/" target="_blank" class="cl"><span>LinkedIn →</span></a>
    </div>
    <div class="ct-detail rv d3">
      Based in Ajmer, Rajasthan &nbsp;·&nbsp;
      Open to Founder's Office roles &nbsp;·&nbsp; Building V-GTHR
    </div>
  </div>
</section>

<footer>
  <span>Dhruv Sharma</span>
  <span>Ajmer, Rajasthan · 2025</span>
  <span>Portfolio</span>
</footer>

<!-- ══════════════════════════════════════
     JAVASCRIPT
══════════════════════════════════════ -->
<script>
/* ─── Loader ─── */
(function(){
  const el = document.getElementById('ld-logo');
  'Dhruv Sharma'.split('').forEach((ch, i) => {
    const s = document.createElement('span');
    s.textContent = ch === ' ' ? '\u00A0' : ch;
    s.style.animationDelay = (0.04 + i * 0.055) + 's';
    el.appendChild(s);
  });
  window.addEventListener('load', () => {
    setTimeout(() => document.getElementById('loader').classList.add('gone'), 2100);
  });
})();

/* ─── Cursor ─── */
(function(){
  const dot = document.getElementById('cur');
  const ring = document.getElementById('cur-r');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    dot.style.left = mx + 'px'; dot.style.top = my + 'px';
  });
  (function tick(){
    rx += (mx - rx) * .1;
    ry += (my - ry) * .1;
    ring.style.left = rx + 'px'; ring.style.top = ry + 'px';
    requestAnimationFrame(tick);
  })();
  document.querySelectorAll('a,button,.vgc,.job,.lc,.ski,.tool,.cert,.cl,.chip,.edx,.vt').forEach(el => {
    el.addEventListener('mouseenter', () => document.body.classList.add('hov'));
    el.addEventListener('mouseleave', () => document.body.classList.remove('hov'));
  });
})();

/* ─── Nav scroll + active ─── */
(function(){
  const nav = document.getElementById('nav');
  window.addEventListener('scroll', () => {
    nav.classList.toggle('scrolled', window.scrollY > 60);
  }, { passive: true });
  const links = document.querySelectorAll('.n-menu a');
  document.querySelectorAll('section[id]').forEach(sec => {
    new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          links.forEach(a => a.classList.remove('on'));
          const a = document.querySelector(`.n-menu a[href="#${e.target.id}"]`);
          if (a) a.classList.add('on');
        }
      });
    }, { threshold: .35 }).observe(sec);
  });
})();

/* ─── Scroll reveal ─── */
(function(){
  const obs = new IntersectionObserver(entries => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('in'); });
  }, { threshold: .07 });
  document.querySelectorAll('.rv, .s-tag').forEach(el => obs.observe(el));
})();

/* ─── Hero canvas — soft floating nodes ─── */
(function(){
  const canvas = document.getElementById('hero-canvas');
  const ctx = canvas.getContext('2d');
  let W, H, nodes;
  const COUNT = 50;
  const DIST = 160;

  function resize() {
    W = canvas.width = canvas.offsetWidth;
    H = canvas.height = canvas.offsetHeight;
  }

  function mkNode() {
    return {
      x: Math.random() * W, y: Math.random() * H,
      vx: (Math.random() - .5) * .35,
      vy: (Math.random() - .5) * .35,
      r: Math.random() * 1.5 + .5,
      a: Math.random() * Math.PI * 2,
      as: (Math.random() - .5) * .008,
    };
  }

  function init() { resize(); nodes = Array.from({ length: COUNT }, mkNode); }

  function draw() {
    ctx.clearRect(0, 0, W, H);
    nodes.forEach(n => {
      n.a += n.as;
      n.x += n.vx + Math.sin(n.a) * .15;
      n.y += n.vy + Math.cos(n.a) * .1;
      if (n.x < 0) n.x = W; if (n.x > W) n.x = 0;
      if (n.y < 0) n.y = H; if (n.y > H) n.y = 0;
    });
    // lines
    for (let i = 0; i < nodes.length; i++) {
      for (let j = i + 1; j < nodes.length; j++) {
        const a = nodes[i], b = nodes[j];
        const dx = a.x - b.x, dy = a.y - b.y;
        const d = Math.sqrt(dx * dx + dy * dy);
        if (d < DIST) {
          const alpha = (1 - d / DIST) * .12;
          ctx.beginPath();
          ctx.moveTo(a.x, a.y); ctx.lineTo(b.x, b.y);
          ctx.strokeStyle = `rgba(79,124,130,${alpha})`;
          ctx.lineWidth = .7;
          ctx.stroke();
        }
      }
    }
    // dots
    nodes.forEach(n => {
      ctx.beginPath();
      ctx.arc(n.x, n.y, n.r, 0, Math.PI * 2);
      ctx.fillStyle = 'rgba(79,124,130,.35)';
      ctx.fill();
    });
    requestAnimationFrame(draw);
  }

  window.addEventListener('resize', resize, { passive: true });
  init(); draw();
})();

/* ─── Smooth parallax on hero blobs (scroll) ─── */
window.addEventListener('scroll', () => {
  const y = window.scrollY;
  document.querySelectorAll('.h-blob').forEach((b, i) => {
    b.style.transform = `translateY(${y * (.04 + i * .025)}px)`;
  });
}, { passive: true });
</script>
</body>
</html>
