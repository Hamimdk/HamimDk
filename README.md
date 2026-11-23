It's me!
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Hamim — Hameemverse | Developer &amp; Maker (preview)</title>
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#f6f4ef;--fg:#16161d;--mut:#6a6a75;--line:#d9d5cb;--card:#fffdf8;--ac:#e0445a;--ac2:#3a5cff;--on:#fff;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#101116;--fg:#f1efe9;--mut:#9a9aa8;--line:#2a2b36;--card:#181922;--ac:#ff6b81;--ac2:#7d93ff}}
:root[data-theme="dark"]{--bg:#101116;--fg:#f1efe9;--mut:#9a9aa8;--line:#2a2b36;--card:#181922;--ac:#ff6b81;--ac2:#7d93ff}
html{scroll-behavior:smooth;scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--fg);font:16px/1.6 "Plus Jakarta Sans",system-ui,sans-serif;overflow-x:hidden}
.serif,.si{font-family:"Instrument Serif",Georgia,serif;font-style:italic;font-weight:400;color:var(--ac)}
.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
section{padding:80px 0}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:10;display:flex;justify-content:center;padding:12px}
.pill{display:flex;align-items:center;gap:6px;background:var(--card);border:1px solid var(--line);border-radius:99px;padding:6px 8px 6px 18px;max-width:100%;overflow-x:auto}
.brand{font-weight:800;color:var(--fg);text-decoration:none;margin-right:10px;white-space:nowrap}.brand b{color:var(--ac)}
.pill a.l{color:var(--mut);text-decoration:none;font-size:14px;padding:6px 12px;border-radius:99px;white-space:nowrap}
.pill a.l:hover{background:var(--bg);color:var(--fg)}
#tt{border:1px solid var(--line);background:var(--bg);color:var(--fg);border-radius:99px;width:36px;height:36px;cursor:pointer;font-size:16px;flex:none}
.meta{display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px;font-size:13px;color:var(--mut)}
.dot{display:inline-block;width:8px;height:8px;border-radius:50%;background:#2fbf71;margin-right:6px;animation:p 1.6s infinite}
@keyframes p{50%{opacity:.3}}
.role{display:inline-block;margin-left:8px;font-size:12px;font-weight:700;letter-spacing:.08em;background:var(--fg);color:var(--bg);padding:3px 10px;border-radius:99px}
.stage{position:relative;height:auto;margin:6px 0 20px}
.mega{font-weight:800;font-size:clamp(90px,27vw,330px);line-height:.9;margin:0;letter-spacing:-.04em;text-align:center;color:var(--fg)}
.hero-grid{display:flex;justify-content:space-between;gap:24px;flex-wrap:wrap;align-items:flex-end}
.hero-grid p{max-width:520px;color:var(--mut);margin:0 0 18px}
.btn{display:inline-block;border-radius:99px;padding:11px 22px;font-weight:600;font-size:14px;text-decoration:none;border:1px solid var(--fg);cursor:pointer;background:none;color:var(--fg);font-family:inherit;transition:transform .15s}
.btn:hover{transform:translateY(-2px)}
.btn.p{background:var(--fg);color:var(--bg)}.btn.s{padding:8px 16px;font-size:13px}
.eb{font-size:12px;letter-spacing:.12em;color:var(--ac);font-weight:700;display:block;margin-bottom:6px}
h2.t{font-size:clamp(30px,5vw,52px);line-height:1.1;margin:0 0 28px;font-weight:700}
.stmt{font-size:clamp(24px,4vw,42px);line-height:1.25;font-weight:600;margin:0 0 44px}
.mg{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px}
.mc{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:22px}
.mn{font-size:44px;font-weight:800;display:block;line-height:1}.ml{color:var(--mut);font-size:14px}
.orbit{position:relative;height:440px;display:grid;place-items:center;overflow:hidden;border:1px dashed var(--line);border-radius:24px;background:var(--card)}
.ring{position:absolute;width:min(380px,80vw);aspect-ratio:1;border-radius:50%;border:1px dashed var(--line)}
.spin{position:absolute;width:min(380px,80vw);aspect-ratio:1;animation:o var(--spd,20s) linear infinite}
@keyframes o{to{transform:rotate(360deg)}}
.node{position:absolute;left:50%;top:50%;font-size:12px;font-weight:600;background:var(--bg);border:1px solid var(--line);border-radius:99px;padding:4px 10px;white-space:nowrap}
.node span{display:block;animation:o var(--spd,20s) linear infinite reverse}
.hint{text-align:center;color:var(--mut);font-size:13px;margin-top:12px}
.acc{border-top:1px solid var(--line)}
.acc button{all:unset;box-sizing:border-box;width:100%;display:flex;justify-content:space-between;padding:20px 4px;cursor:pointer;font-weight:700;font-size:20px}
.acc button:focus-visible,.btn:focus-visible,#tt:focus-visible{outline:2px solid var(--ac2);outline-offset:2px}
.panel{display:none;padding:0 4px 20px}.acc.open .panel{display:block}
.chip{display:inline-block;margin:0 6px 8px 0;padding:5px 12px;border:1px solid var(--line);border-radius:8px;font-size:13px;background:var(--card)}
.lab{margin-top:40px;background:var(--card);border:1px solid var(--line);border-radius:20px;padding:24px}
.lab h3{margin:0 0 16px}.row{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px;margin-top:16px}
.cm{display:flex;justify-content:space-between;align-items:center;font-size:14px;margin-bottom:8px}
input[type=range]{width:100%;accent-color:var(--ac)}
.bar{height:12px;border-radius:99px;background:var(--bg);border:1px solid var(--line);overflow:hidden}
.bar i{display:block;height:100%;background:linear-gradient(90deg,var(--ac2),var(--ac));width:72%;transition:width .5s}
.pg{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:16px}
.pc{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:24px;display:flex;flex-direction:column;gap:10px}
.pc h3{margin:0;font-size:20px}.pc a{color:var(--ac2)}.pc p{margin:0;color:var(--mut);font-size:15px}
.pt{display:flex;justify-content:space-between;font-size:12px;color:var(--mut)}.pt b{color:var(--ac);letter-spacing:.08em}
.pf{margin-top:auto;display:flex;justify-content:space-between;align-items:center;gap:8px;flex-wrap:wrap}
.pf small span{margin-right:8px;color:var(--mut);font-size:12px}
.tl{display:grid;grid-template-columns:150px 1fr;gap:6px 24px;padding:22px 0;border-top:1px solid var(--line)}
.tl h3{margin:0 0 4px;font-size:18px}.tl p{margin:0;color:var(--mut)}.td{color:var(--mut);font-size:14px}
@media(max-width:600px){.tl{grid-template-columns:1fr}}
.ct{text-align:center}.ct h2{font-size:clamp(36px,7vw,72px);line-height:1.05;margin:0 0 14px}
.em{display:inline-flex;align-items:center;gap:12px;flex-wrap:wrap;justify-content:center;background:var(--card);border:1px solid var(--line);border-radius:99px;padding:8px 8px 8px 22px;margin:20px 0}
.soc{display:flex;gap:10px;justify-content:center;flex-wrap:wrap}
footer{display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px;margin-top:60px;font-size:13px;color:var(--mut)}footer a{color:var(--mut)}
#toast{position:fixed;left:50%;bottom:calc(20px + env(safe-area-inset-bottom,0px));transform:translate(-50%,120px);background:var(--fg);color:var(--bg);padding:10px 18px;border-radius:99px;font-size:14px;transition:transform .3s;z-index:20}
#toast.on{transform:translate(-50%,0)}

/* ---- Sakuga components (from the video) ---- */
:root{--ink:#1b1a4a;--lav:#8d8ff0;--pk:#ff4f9a}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--ink:#e9e8ff}}
:root[data-theme="dark"]{--ink:#e9e8ff}
.btn,.btn.p{background:var(--card);color:var(--ink);border:2.5px solid var(--ink);box-shadow:4px 4px 0 var(--lav);font-style:italic;font-weight:700;transition:transform .12s,box-shadow .12s}
.btn.p{box-shadow:4px 4px 0 var(--pk)}
.btn:hover{transform:translate(-1px,-1px);box-shadow:6px 6px 0 var(--lav)}
.btn.p:hover{box-shadow:6px 6px 0 var(--pk)}
.btn:active,.btn.p:active{transform:translate(3px,3px);box-shadow:1px 1px 0 var(--lav)}
#tt.sw{position:relative;width:62px;height:34px;border:2.5px solid var(--ink);background:#c9cbe0;box-shadow:3px 3px 0 var(--lav);padding:0;transition:background .25s}
#tt.sw[aria-checked=true]{background:var(--lav)}
.sw .kn{position:absolute;top:2px;left:2px;width:24px;height:24px;border-radius:50%;background:#fff;border:2px solid var(--ink);transition:transform .3s cubic-bezier(.34,1.8,.5,1)}
.sw[aria-checked=true] .kn{transform:translateX(28px)}
.lab{border:2.5px solid var(--ink);box-shadow:6px 6px 0 var(--lav)}
.ck{position:relative;display:inline-flex;align-items:center;gap:10px;cursor:pointer;font-weight:600}
.ck input{position:absolute;opacity:0}
.ck .bx{width:28px;height:28px;border:2.5px solid var(--ink);border-radius:8px;background:var(--card);box-shadow:3px 3px 0 var(--lav);display:grid;place-items:center;color:transparent;transition:.15s}
.ck input:checked+.bx{background:var(--lav);color:#fff}
.ck input:focus-visible+.bx{outline:2px solid var(--ac2);outline-offset:2px}
.sr{position:relative;padding-top:34px}
.tip{position:absolute;top:0;transform:translateX(-50%);background:var(--card);color:var(--ink);border:2px solid var(--ink);border-radius:10px;padding:0 8px;font-size:12px;font-weight:800;font-style:italic;box-shadow:2px 2px 0 var(--lav);line-height:22px}
#sl{-webkit-appearance:none;appearance:none;display:block;width:100%;height:14px;border-radius:99px;border:2.5px solid var(--ink);background:linear-gradient(var(--lav),var(--lav)) 0 0/var(--p,50%) 100% no-repeat,var(--card)}
#sl::-webkit-slider-thumb{-webkit-appearance:none;width:22px;height:22px;border-radius:50%;background:#fff;border:2.5px solid var(--ink);margin-top:-7px;cursor:grab}
#sl::-moz-range-thumb{width:18px;height:18px;border-radius:50%;background:#fff;border:2.5px solid var(--ink)}
#sl:focus-visible{outline:2px solid var(--ac2);outline-offset:4px}
.bar{height:22px;border:2.5px solid var(--ink);box-shadow:3px 3px 0 var(--lav);background:var(--card)}
.bar i{background:repeating-linear-gradient(115deg,rgba(255,255,255,.4) 0 6px,transparent 6px 14px),var(--pk);transition:width .08s linear}
.cmp{display:inline-block;border:2.5px solid var(--ink);background:var(--card);color:var(--ink);font-weight:800;font-style:italic;padding:2px 14px;transform:skewX(-8deg);box-shadow:3px 3px 0 var(--pk);font-size:14px}
#toast{display:flex;align-items:center;gap:10px;white-space:nowrap;max-width:92vw;background:var(--card);color:var(--ink);border:2.5px solid var(--ink);box-shadow:4px 4px 0 var(--lav);border-radius:14px;font-weight:700;font-style:italic;padding:10px 12px}
#toast .tc{font-style:normal;width:24px;height:24px;border-radius:50%;background:var(--lav);color:#fff;display:grid;place-items:center;font-size:13px}
#toast button{all:unset;cursor:pointer;padding:0 4px;font-size:20px}
#toast button:focus-visible{outline:2px solid var(--ac2)}
.burst{position:fixed;z-index:30;pointer-events:none;font:900 italic 40px/1 "Plus Jakarta Sans","Hiragino Sans","Noto Sans JP",sans-serif;color:var(--ink);text-shadow:3px 3px 0 var(--pk);transform:translate(-50%,-100%) rotate(-8deg);animation:bst .8s forwards}
@keyframes bst{0%{opacity:0;transform:translate(-50%,-60%) scale(.3) rotate(-8deg)}25%{opacity:1;transform:translate(-50%,-110%) scale(1.25) rotate(-8deg)}100%{opacity:0;transform:translate(-50%,-160%) scale(1) rotate(-8deg)}}
.pt2{position:fixed;z-index:30;pointer-events:none;width:8px;height:8px;background:var(--pk);transform:rotate(45deg);animation:pt .7s forwards}
@keyframes pt{to{opacity:0;transform:translate(var(--dx),var(--dy)) rotate(225deg) scale(.3)}}
.puff{position:fixed;z-index:30;pointer-events:none;border:2px solid var(--ink);border-radius:50%;background:#fff;animation:pf .8s forwards}
@keyframes pf{to{opacity:0;transform:translate(var(--dx),var(--dy)) scale(1.6)}}

/* ---- Animated background ---- */
.bg{position:fixed;inset:0;z-index:-1;pointer-events:none;overflow:hidden}
.bg:before{content:"";position:absolute;inset:0;background-image:radial-gradient(var(--lav) 1.6px,transparent 2.2px);background-size:22px 22px;opacity:.3;-webkit-mask-image:radial-gradient(ellipse at 85% 25%,#000,transparent 65%);mask-image:radial-gradient(ellipse at 85% 25%,#000,transparent 65%)}
.bg svg{position:absolute;inset:0;width:100%;height:100%}
.bg canvas{position:absolute;inset:0;width:100%;height:100%}
.bg:after{content:"";position:absolute;inset:0;background-image:radial-gradient(var(--pk) 1.8px,transparent 2.4px);background-size:22px 22px;opacity:.75;-webkit-mask-image:radial-gradient(circle 200px at var(--mx,75%) var(--my,25%),#000,transparent);mask-image:radial-gradient(circle 200px at var(--mx,75%) var(--my,25%),#000,transparent)}
.gl{fill:none;stroke:var(--line);stroke-width:1.2}
.gl.d{stroke-dasharray:6 10;transform-box:fill-box;transform-origin:center;animation:o 80s linear infinite}
.sln{position:absolute;left:0;height:3px;width:32vw;border-radius:3px;background:linear-gradient(90deg,transparent,var(--pk),transparent);opacity:.35;animation:sd 10s linear infinite}
@keyframes sd{from{transform:translateX(-40vw)}to{transform:translateX(130vw)}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<div class="bg" aria-hidden="true">
<svg viewBox="0 0 1440 900" preserveAspectRatio="xMidYMid slice"><circle cx="1120" cy="420" r="340" class="gl"/><circle cx="1120" cy="420" r="220" class="gl d"/><line x1="0" y1="210" x2="1440" y2="210" class="gl"/><line x1="0" y1="730" x2="1440" y2="730" class="gl"/><line x1="260" y1="0" x2="260" y2="900" class="gl"/><line x1="1120" y1="0" x2="1120" y2="900" class="gl"/><line x1="140" y1="900" x2="980" y2="0" class="gl" opacity=".5"/></svg>
<canvas id="bgc"></canvas>
<i class="sln" style="top:18%"></i><i class="sln" style="top:52%;animation-delay:-4s;width:22vw"></i><i class="sln" style="top:81%;animation-delay:-7s"></i>
</div>

<nav><div class="pill">
<a href="#home" class="brand">Hameemverse<b>.</b></a>
<a class="l" href="#about">About</a><a class="l" href="#toolkit">Toolkit</a><a class="l" href="#projects">Projects</a><a class="l" href="#experience">Experience</a><a class="l" href="#contact">Contact</a>
<button id="tt" class="sw" type="button" role="switch" aria-checked="false" aria-label="Toggle light and dark theme"><i class="kn"></i></button>
</div></nav>

<main>
<section id="home" style="padding-top:30px"><div class="wrap">
<div class="meta"><span><i class="dot"></i>Open to collaborations &amp; custom builds</span><span>Tongi, Gazipur, Bangladesh</span></div>
<p style="margin:28px 0 0">Hello, I’m <span class="role" id="role">FULL-STACK WEB DEVELOPER</span></p>
<div class="stage">
<h1 class="mega">HAMIM</h1>
</div>
<div class="hero-grid"><div>
<p>A builder who turns ideas into interactive digital &amp; hardware realities — from anime-inspired web interfaces to custom e-commerce storefronts and embedded electronics.</p>
<a href="#projects" class="btn p">View selected work →</a> <a href="#toolkit" class="btn">360° skill orbit</a></div>
<span style="font-size:12px;letter-spacing:.1em;color:var(--mut)">SCROLL TO EXPLORE ↓</span></div>
</div></section>

<section id="about"><div class="wrap">
<h2 class="stmt">I craft <span class="si">interactive web systems</span>, operate live online commerce at <span class="si">Agrova</span>, and engineer <span class="si">custom circuits</span> that bridge clean code with everyday hardware.</h2>
<div class="mg">
<div class="mc"><span class="mn" data-t="18" data-s="+">0</span><span class="ml">Projects &amp; builds</span></div>
<div class="mc"><span class="mn" data-t="100" data-s="%">0</span><span class="ml">Hand-crafted code</span></div>
<div class="mc"><span class="mn" data-t="360" data-s="°">0</span><span class="ml">Interactive motion</span></div>
<div class="mc"><span class="mn" data-t="3" data-s=" yrs">0</span><span class="ml">Web &amp; hardware lab</span></div>
</div></div></section>

<section id="toolkit"><div class="wrap">
<div style="display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:12px">
<div><span class="eb">INTERACTIVE 360° SHOWCASE</span><h2 class="t">The toolkit <span class="serif">behind the work.</span></h2></div>
<div style="text-align:right;font-size:12px;color:var(--mut)">TURNAROUND ANGLE<br><b id="ang" style="font-size:24px;color:var(--fg)">000°</b></div></div>
<div class="orbit"><div class="ring"></div><div class="spin" id="spin"></div>
<svg viewBox="0 0 200 300" style="height:300px;position:relative" id="turn" aria-label="Placeholder rotating avatar">
<path d="M60 150 Q100 120 140 150 L150 280 H50Z" fill="#3a5cff"/><circle cx="100" cy="85" r="46" fill="#ffd9c2"/>
<path d="M54 85 Q60 30 100 32 Q142 30 148 88 Q130 60 100 62 Q72 60 54 85Z" fill="#2a1f3d"/>
<circle cx="84" cy="90" r="6" fill="#16161d"/><circle cx="116" cy="90" r="6" fill="#16161d"/></svg></div>
<p class="hint">Scroll to rotate • in the live site, hover any orbiting node to inspect</p>
</div></section>

<section style="padding-top:0"><div class="wrap">
<div id="accs"></div>
<div class="lab">
<span class="eb">INTERACTIVE SAKUGA VFX CONTROLS</span><h3>Test the anime UI physics</h3>
<label class="ck"><input type="checkbox" id="fx" checked><span class="bx"><svg viewBox="0 0 24 24" width="18" height="18" fill="none" stroke="currentColor" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Enable manga SFX &amp; particles</label>
<div class="row">
<div><div class="cm"><span>Orbit speed multiplier</span></div><div class="sr"><output id="sb" class="tip">50%</output><input type="range" id="sl" min="10" max="100" value="50" aria-label="Orbit speed multiplier"></div></div>
<div><div class="cm"><span>Build compiler charge</span><button class="btn s" id="ch" type="button">Charge 100%</button></div><div class="bar"><i id="fill"></i></div><div style="margin-top:14px"><span class="cmp" id="pp">72%</span></div></div>
</div></div></div></section>

<section id="projects"><div class="wrap">
<span class="eb">SELECTED WORK</span><h2 class="t">Featured <span class="serif">projects.</span></h2>
<div class="pg">
<article class="pc"><div class="pt"><b>E-COMMERCE PLATFORM</b><span>2025 – 2026</span></div><h3>Agrova (<a href="https://agrovabd.com" target="_blank" rel="noopener">agrovabd.com</a>)</h3><p>Full-stack online plant, seed, and hydroponic storefront serving growers across Bangladesh with bilingual product specifications, tiered weight pricing, and custom botanical photography.</p><div class="pf"><small><span>E-Commerce</span><span>Bilingual UX</span><span>Catalog</span></small><a class="btn p s" href="https://agrovabd.com" target="_blank" rel="noopener">Visit live ↗</a></div></article>
<article class="pc"><div class="pt"><b>INTERACTIVE PORTFOLIO</b><span>2026</span></div><h3>Hameemverse (<a href="https://hameemverse.qd.je" target="_blank" rel="noopener">hameemverse.qd.je</a>)</h3><p>Editorial developer showcase engineered from scratch with vanilla HTML, CSS, and Canvas 2D — blending a 360° scroll-driven anime turnaround with Sakuga manga micro-interactions.</p><div class="pf"><small><span>Canvas 2D</span><span>Scroll kinematics</span></small><a class="btn p s" href="#toolkit">Inspect 360°</a></div></article>
<article class="pc"><div class="pt"><b>EMBEDDED &amp; POWER</b><span>2026</span></div><h3>Smart Display Power Bank &amp; LoRa Link</h3><p>Custom lithium-ion power pack paired with an ESP32 display bridge for real-time telemetry, alongside 900MHz LoRa transceiver experiments for off-grid walkie-talkie messaging.</p><div class="pf"><small><span>ESP32</span><span>900MHz LoRa</span><span>Li-Ion BMS</span></small><button class="btn s" type="button" id="specs">Specs ✓</button></div></article>
</div></div></section>

<section id="experience"><div class="wrap">
<span class="eb">JOURNEY</span><h2 class="t">The path, <span class="serif">so far.</span></h2>
<div class="tl"><div class="td">2025 – present</div><div><h3>Founder &amp; Operator, Agrova</h3><p>Built and scaled an online seed and horticultural supply platform, managing digital storefront architecture, product media workflows, and nationwide fulfillment from Gazipur.</p></div></div>
<div class="tl"><div class="td">2026</div><div><h3>Creative Web &amp; Sakuga UI Engineering, Hameemverse</h3><p>Designed and deployed custom domains on GitHub Pages, exploring procedural 360° character animation, scroll-linked 3D constellations, and responsive manga motion libraries.</p></div></div>
<div class="tl"><div class="td">2024 – present</div><div><h3>Independent Electronics &amp; Embedded Prototyping</h3><p>Diagnosing and rebuilding power supply boards, USB-C PD charging circuits, ESP32 display interfaces, and long-range LoRa radio modules.</p></div></div>
</div></section>

<section id="contact" class="ct"><div class="wrap">
<span class="eb">GET IN TOUCH</span>
<h2>Have an idea?<br><span class="serif">Let’s make it happen.</span></h2>
<p style="color:var(--mut)">Web development, interactive UI animation, e-commerce builds, or hardware collaborations — reach out directly.</p>
<div class="em"><span>contact@hameemverse.qd.je</span><button class="btn p" id="cp" type="button">Copy email</button></div>
<div class="soc"><a class="btn s" href="https://github.com/HamimDk" target="_blank" rel="noopener">GitHub (@HamimDk) ↗</a><a class="btn s" href="https://agrovabd.com" target="_blank" rel="noopener">Agrova store ↗</a></div>
<footer><span>© 2026 Hamim (Hameemverse). Crafted with Sakuga motion.</span><a href="#home">Back to top ↑</a></footer>
</div></section>
</main>

<div id="toast" role="status" aria-live="polite"><i class="tc">✓</i><span id="tm"></span><button type="button" id="tx" aria-label="Close notification">×</button></div>

<script>
var $=function(s){return document.querySelector(s)};
var root=document.documentElement;
function toast(m){$("#tm").textContent=m;$("#toast").classList.add("on");clearTimeout(toast.t);toast.t=setTimeout(function(){$("#toast").classList.remove("on")},2600)}
$("#tx").onclick=function(){$("#toast").classList.remove("on")};
function on(){return $("#fx").checked}
function sparks(el,n){if(!on())return;n=n||8;var r=el.getBoundingClientRect(),x=r.left+r.width/2,y=r.top+r.height/2;for(var i=0;i<n;i++){var a=i/n*6.28,d=document.createElement("i");d.className="pt2";d.style.left=x+"px";d.style.top=y+"px";d.style.setProperty("--dx",Math.cos(a)*50+"px");d.style.setProperty("--dy",Math.sin(a)*50+"px");document.body.appendChild(d);setTimeout(function(e){e.remove()},700,d)}}
function fx(el,txt){if(!on())return;var r=el.getBoundingClientRect(),b=document.createElement("div");b.className="burst";b.textContent=txt;b.style.left=r.left+r.width/2+"px";b.style.top=r.top+"px";document.body.appendChild(b);setTimeout(function(){b.remove()},850);sparks(el,10)}
function puff(x,y){if(!on())return;var p=document.createElement("i"),s=10+Math.random()*12;p.className="puff";p.style.cssText="left:"+x+"px;top:"+y+"px;width:"+s+"px;height:"+s+"px;--dx:"+(-20-Math.random()*30)+"px;--dy:"+(-10-Math.random()*20)+"px";document.body.appendChild(p);setTimeout(function(){p.remove()},800)}
$("#fx").onchange=function(){if(this.checked)fx(this.parentNode,"ズバッ!")};
function isDark(){return getComputedStyle(root).getPropertyValue("--bg").trim()==="#101116"}
$("#tt").setAttribute("aria-checked",isDark());
$("#tt").onclick=function(){var d=isDark();root.setAttribute("data-theme",d?"light":"dark");this.setAttribute("aria-checked",!d);sparks(this,8)};
// role cycler
var roles=["FULL-STACK WEB DEVELOPER","ELECTRONICS TINKERER","E-COMMERCE OPERATOR"],ri=0;
setInterval(function(){ri=(ri+1)%roles.length;$("#role").textContent=roles[ri]},2600);
// accordion
var data=[["Frontend & Anime Motion",["HTML5 Semantic","CSS3 Keyframes & Grid","Vanilla JavaScript (ES6+)","HTML5 Canvas 2D","Sakuga Micro-Interactions"]],["E-Commerce & Web Deployment",["GitHub Pages & Custom DNS","Agrova Catalog Architecture","Bilingual EN / BN UX","SEO & Performance Tuning"]],["Electronics, Power & Wireless",["Custom Li-Ion Power Banks","ESP32 & Display Bridges","900MHz LoRa Comms","USB-C PD & Circuit Repair","12V SLA & Charging ICs"]],["AI Workflows & Systems",["Google AI Studio & Gemini","Generative Product Media","Windows / Linux Multiboot","Python Scripting"]]];
var box=$("#accs");
data.forEach(function(d,i){var a=document.createElement("div");a.className="acc"+(i?"":" open");
a.innerHTML='<button type="button" aria-expanded="'+(!i)+'"><span>'+d[0].replace(/&/g,"&amp;")+'</span><span style="color:var(--mut)">0'+d[1].length+'</span></button><div class="panel">'+d[1].map(function(c){return '<span class="chip">'+c.replace(/&/g,"&amp;")+'</span>'}).join("")+'</div>';
a.firstChild.onclick=function(){var o=a.classList.toggle("open");this.setAttribute("aria-expanded",o)};box.appendChild(a)});
// orbit nodes
var all=[].concat.apply([],data.map(function(d){return d[1]})).slice(0,12),sp=$("#spin");
all.forEach(function(n,i){var ang=i/all.length*360,e=document.createElement("div");e.className="node";
e.style.transform="translate(-50%,-50%) rotate("+ang+"deg) translateX(min(190px,40vw)) rotate("+(-ang)+"deg)";
e.innerHTML="<span>"+n.replace(/&/g,"&amp;")+"</span>";sp.appendChild(e)});
function speed(){var v=+$("#sl").value;root.style.setProperty("--spd",(40-v*.35)+"s")}
var lastPuff=0;
function tip(){var s=$("#sl"),p=(s.value-s.min)/(s.max-s.min);$("#sb").textContent=s.value+"%";$("#sb").style.left="calc("+p*100+"% + "+(11-p*22)+"px)";s.style.setProperty("--p",(p*100)+"%")}
$("#sl").oninput=function(){tip();speed();var n=Date.now();if(n-lastPuff>70){lastPuff=n;var r=this.getBoundingClientRect(),p=(this.value-this.min)/(this.max-this.min);puff(r.left+11+p*(r.width-22),r.top+r.height/2)}};tip();speed();
// scroll rotation
addEventListener("scroll",function(){var r=$("#toolkit").getBoundingClientRect(),h=innerHeight+r.height,p=Math.min(1,Math.max(0,(innerHeight-r.top)/h)),a=Math.round(p*360);
$("#ang").textContent=String(a).padStart(3,"0")+"°";$("#turn").style.transform="scaleX("+Math.cos(a*Math.PI/180)+")"},{passive:true});
// counters
var io=new IntersectionObserver(function(es){es.forEach(function(e){if(!e.isIntersecting)return;io.unobserve(e.target);var el=e.target,t=+el.dataset.t,s=el.dataset.s,st=performance.now();
(function f(n){var k=Math.min(1,(n-st)/1200);el.textContent=Math.round(t*k)+s;if(k<1)requestAnimationFrame(f)})(st)})},{threshold:.5});
document.querySelectorAll(".mn").forEach(function(e){io.observe(e)});
// charge bar
var pv=72,busy=0;
function setP(v){pv=v;$("#fill").style.width=v+"%";$("#pp").textContent=v>=100?"Complete ✓":Math.round(v)+"%"}
$("#ch").onclick=function(){if(busy)return;busy=1;if(pv>=100)setP(0);var t=setInterval(function(){setP(Math.min(100,pv+2.5));var r=$("#fill").getBoundingClientRect();puff(r.right,r.top+r.height/2);if(pv>=100){clearInterval(t);busy=0;fx($("#fill"),"ドン!");toast("Build complete")}},60)};
// specs / copy email
$("#specs").onclick=function(){toast("Preview only: the live site opens specs here")};
$("#cp").onclick=function(){fx(this,"ドン!");var t="contact@hameemverse.qd.je";try{navigator.clipboard.writeText(t).then(function(){toast("Copied successfully!")},function(){toast(t)})}catch(e){toast(t)}};
// interactive background
(function(){
var c=$("#bgc"),x=c.getContext("2d"),W,H,ps=[],m={x:-999,y:-999},dpr=Math.min(2,devicePixelRatio||1),rm=matchMedia("(prefers-reduced-motion:reduce)").matches,t=0;
var cs=getComputedStyle(root),lav=cs.getPropertyValue("--lav").trim(),pk=cs.getPropertyValue("--pk").trim();
function rs(){W=innerWidth;H=innerHeight;c.width=W*dpr;c.height=H*dpr;x.setTransform(dpr,0,0,dpr,0,0);var n=Math.round(Math.min(70,W*H/20000));ps=[];for(var i=0;i<n;i++)ps.push({x:Math.random()*W,y:Math.random()*H,vx:0,vy:0,s:2+Math.random()*3,k:Math.random()<.35,a:Math.random()*6.28});if(rm)draw()}
function star(px,py,r){x.beginPath();x.moveTo(px,py-r);x.quadraticCurveTo(px,py,px+r,py);x.quadraticCurveTo(px,py,px,py+r);x.quadraticCurveTo(px,py,px-r,py);x.quadraticCurveTo(px,py,px,py-r);x.fill()}
function draw(){t++;x.clearRect(0,0,W,H);
for(var i=0;i<ps.length;i++){var p=ps[i],dx=p.x-m.x,dy=p.y-m.y,d=Math.hypot(dx,dy)||1;
if(d<140){var f=(140-d)/140;p.vx+=dx/d*f*.5;p.vy+=dy/d*f*.5}
p.vx*=.96;p.vy*=.96;p.a+=.03;
p.x+=p.vx+Math.sin(p.a*.5)*.25;p.y+=p.vy+.18;
if(p.y>H+10)p.y=-10;if(p.x<-10)p.x=W+10;if(p.x>W+10)p.x=-10;
for(var j=i+1;j<ps.length;j++){var q=ps[j],l=Math.hypot(p.x-q.x,p.y-q.y);if(l<110){x.globalAlpha=(1-l/110)*.35;x.strokeStyle=lav;x.lineWidth=1;x.beginPath();x.moveTo(p.x,p.y);x.lineTo(q.x,q.y);x.stroke()}}
if(d<170){x.globalAlpha=(1-d/170)*.6;x.strokeStyle=pk;x.lineWidth=1.2;x.beginPath();x.moveTo(p.x,p.y);x.lineTo(m.x,m.y);x.stroke()}
x.globalAlpha=.45+.5*Math.sin(p.a);
if(p.k){x.fillStyle=pk;star(p.x,p.y,p.s*2.6)}else{x.fillStyle=lav;x.beginPath();x.arc(p.x,p.y,p.s*.6,0,6.28);x.fill()}}
x.globalAlpha=1}
function loop(){draw();requestAnimationFrame(loop)}
addEventListener("resize",rs);
addEventListener("pointermove",function(e){m.x=e.clientX;m.y=e.clientY;root.style.setProperty("--mx",m.x+"px");root.style.setProperty("--my",m.y+"px")},{passive:true});
addEventListener("pointerdown",function(e){ps.forEach(function(p){var dx=p.x-e.clientX,dy=p.y-e.clientY,d=Math.hypot(dx,dy)||1;if(d<260){var f=(260-d)/260*9;p.vx+=dx/d*f;p.vy+=dy/d*f}})},{passive:true});
rs();if(!rm)loop();
})();
</script>
</body>
</html>
