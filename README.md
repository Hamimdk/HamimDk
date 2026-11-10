(●'◡'●)
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>HamimDk</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#141414; --bg-deep:#2b2b2b; --ink:#ffffff; --muted:#d4d4d4; --pink:#ff0a5c;
  box-sizing:border-box; color-scheme:dark;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
html{scroll-padding-top:env(safe-area-inset-top,0px);height:auto}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Poppins,system-ui,sans-serif;line-height:1.7;position:relative;overflow-x:hidden}
a{color:inherit;text-decoration:none}

/* build effect: elements start invisible, cursors reveal them */
.js [data-b]{opacity:0;transform:translateY(8px) scale(.985);transition:opacity .9s ease,transform .9s ease}
.js [data-b].in{opacity:1;transform:none}
.drawbox{position:absolute;z-index:90;border:1px solid;pointer-events:none;transition:opacity .5s}
.drawbox span{position:absolute;right:0;top:100%;margin-top:4px;color:#111;font:600 11px Poppins,sans-serif;padding:1px 6px;border-radius:3px;white-space:nowrap}
.pen{position:absolute;z-index:90;pointer-events:none;overflow:visible;transition:opacity .5s}
.guide{position:absolute;z-index:80;pointer-events:none;transition:opacity .5s}
.js [data-b][data-type]:not([data-box]){opacity:1;transform:none;transition:none}
.w{display:inline-block;white-space:nowrap}
.caret{display:inline-block;width:2px;height:1em;margin-right:-2px;vertical-align:-.14em;background:var(--pink);animation:blink .5s steps(1) infinite}
.btn .caret,.links .caret{background:#fff}
@keyframes blink{50%{opacity:0}}
.ch{opacity:0}.ch.on{opacity:1;transition:opacity .12s}
.cur{position:absolute;left:0;top:0;z-index:100;pointer-events:none;will-change:transform;transition:transform .6s cubic-bezier(.4,0,.2,1),opacity .3s;opacity:0}
.cur svg{display:block;width:20px;height:20px;fill:var(--c);transform-origin:2px 1px;transition:transform .35s ease}
.cur span{position:absolute;left:16px;top:18px;background:var(--c);color:#111;font-size:12px;font-weight:600;padding:1px 8px;border-radius:10px;white-space:nowrap}

nav{position:fixed;top:0;left:0;right:0;z-index:50;display:flex;justify-content:space-between;align-items:center;padding:calc(14px + env(safe-area-inset-top,0px)) 5vw 14px;background:rgba(30,30,30,.92)}
.logo{font-weight:600;font-size:1.5rem;font-style:italic;color:var(--pink);letter-spacing:.5px}
nav ul{display:flex;gap:28px;list-style:none;margin:0;padding:0;font-size:.8rem;font-weight:500}
nav a.active{color:var(--pink)}

.hero{position:relative;min-height:560px;margin-top:56px;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:90px 6vw 120px;overflow:hidden;border-radius:0 0 50% 50% / 0 0 24% 24%}
.hero-bg{position:absolute;inset:0;background:
  radial-gradient(circle at 18% 70%,rgba(255,10,92,.35),transparent 28%),
  radial-gradient(circle at 80% 30%,rgba(255,160,60,.30),transparent 26%),
  radial-gradient(circle at 60% 85%,rgba(60,200,255,.22),transparent 30%),
  linear-gradient(160deg,#1c1d27,#3b3340 55%,#2a2a2a)}
.hero>*:not(.hero-bg){position:relative}
h1{font-size:clamp(2.6rem,7vw,4.4rem);font-weight:500;margin:0 0 6px;line-height:1.15}
.sub{max-width:20ch;margin:0 auto 22px;font-size:1rem}
.btn{display:inline-block;background:var(--pink);color:#fff;font-weight:600;font-size:.75rem;padding:10px 28px;border-radius:3px}

.about{max-width:1000px;margin:70px auto;padding:0 6vw;display:grid;grid-template-columns:minmax(0,300px) 1fr;gap:56px;align-items:center}
.frame{position:relative;padding:0 0 0 0}
.frame .pink{background:var(--pink);padding:14px 14px 14px 14px;position:relative}
.photo{background:linear-gradient(#1b1b1b,#2d2d2d);aspect-ratio:3/4;display:flex;align-items:flex-end;justify-content:center;overflow:hidden}
.photo svg{width:78%;fill:#555}
.badge{position:absolute;left:-18px;bottom:36px;background:var(--pink);width:104px;padding:12px 8px;text-align:center;font-size:.8rem;line-height:1.3;box-shadow:0 0 0 4px var(--bg)}
.badge b{display:block;font-size:1.3rem}
.rule{width:64px;height:3px;background:var(--pink);margin-bottom:14px}
h2{font-size:1.7rem;font-weight:500;margin:0 0 14px}
.text p{margin:0 0 18px;color:var(--muted);font-size:.9rem;max-width:56ch}
.text h3{font-size:1.05rem;font-weight:600;margin:24px 0 6px}
.hobbies{margin:0 0 22px;padding-left:20px;color:var(--muted);font-size:.9rem}
.hobbies li::marker{color:var(--pink)}
.links{display:flex;flex-wrap:wrap;gap:10px}
.links a{border:2px solid var(--pink);padding:6px 20px;font-size:.8rem;font-weight:500;border-radius:3px;transition:background .2s}
.links a:hover,.links a:focus-visible{background:var(--pink)}
a:focus-visible,button:focus-visible{outline:2px solid #fff;outline-offset:3px}

.tip{position:absolute;z-index:300;transform:translate(-50%,calc(-100% + 6px));background:#1d1d1d;border:1px solid var(--pink);border-radius:8px;padding:7px 14px;font-size:.78rem;line-height:1.5;text-align:center;white-space:nowrap;box-shadow:0 6px 18px rgba(0,0,0,.5);opacity:0;pointer-events:none;transition:opacity .2s,transform .2s}
.tip.show{opacity:1;transform:translate(-50%,-100%)}
.tip b{display:block;color:var(--pink);font-weight:600}
.tip::after{content:"";position:absolute;left:50%;bottom:-6px;width:10px;height:10px;background:#1d1d1d;border:solid var(--pink);border-width:0 1px 1px 0;transform:translateX(-50%) rotate(45deg)}
#replay{position:fixed;right:16px;bottom:calc(16px + env(safe-area-inset-bottom,0px));z-index:200;background:#111;color:#fff;border:1px solid #555;border-radius:20px;padding:8px 16px;font:500 .75rem Poppins,sans-serif;cursor:pointer}

@media (max-width:760px){
  nav ul{gap:14px;font-size:.7rem}
  nav ul li:nth-child(n+4){display:none}
  .about{grid-template-columns:1fr;gap:40px}
  .frame{max-width:300px;margin:0 auto}
  .badge{left:-8px}
}
@media (prefers-reduced-motion:reduce){.js [data-b]{transition:none}}
</style>
</head>
<body>
<script>document.documentElement.classList.add('js')</script>

<nav>
  <a class="logo" href="#" data-b data-type>HamimDk</a>
  <ul>
    <li><a class="active" href="#" data-b data-type>Home</a></li>
    <li><a href="#about" data-b data-type>About</a></li>
    <li><a href="#hobbies" data-b data-type>Hobbies</a></li>
    <li><a href="#links" data-b data-type>Contact</a></li>
  </ul>
</nav>

<header class="hero">
  <div class="hero-bg"></div>
  <h1 data-b data-type data-guide="h">Hi, I’m HamimDk</h1>
  
  
</header>

<main class="about" id="about">
  <div class="frame" data-b data-draw>
    <div class="pink">
      <!-- Replace the silhouette with your photo: <img src="me.jpg" alt="HamimDk"> -->
      <div class="photo">
        <svg viewBox="0 0 100 120" aria-hidden="true"><circle cx="50" cy="38" r="22"/><path d="M6 120c0-30 20-48 44-48s44 18 44 48z"/></svg>
      </div>
    </div>
    
  </div>

  <div class="text">
    <div class="rule" data-b></div>
    <h2 data-b data-type data-guide="v">Introduction About Me</h2>
    <p data-b data-type>Welcome to my corner of the internet. I am passionate about creating, coding, and exploring new technologies.</p>
    <h3 id="hobbies" data-b data-type>My Hobbies</h3>
    <ul class="hobbies">
      <li data-b data-type>Full stack web development</li>
      <li data-b data-type>Exploring AI and automation</li>
      <li data-b data-type>Gaming and tech tinkering</li>
    </ul>
    <div class="links" id="links">
      <!-- Instagram opens your real profile. Facebook and WhatsApp show a small "developer is sleeping" bubble: when you have real links, change href="#" to the real address, add target="_blank" rel="noopener", and delete data-soon -->
      <a href="#" data-soon data-b data-type data-box data-pen>Facebook</a>
      <a href="https://www.instagram.com/professional_hamim/" target="_blank" rel="noopener" data-b data-type data-box data-pen>Instagram</a>
      <a href="#" data-soon data-b data-type data-box data-pen>WhatsApp</a>
    </div>
  </div>
</main>

<div class="tip" id="tip" aria-hidden="true"><b>Developer is sleeping 💤</b>Check later.</div>
<button id="replay" type="button">Replay build</button>

<script>
(function(){
  var els=[].slice.call(document.querySelectorAll('[data-b]'));
  els.forEach(function(e){if(e.hasAttribute('data-type')){var t=e.textContent;e.textContent='';t.split(' ').forEach(function(w,i){if(i)e.appendChild(document.createTextNode(' '));var ws=document.createElement('span');ws.className='w';w.split('').forEach(function(ch){var c=document.createElement('span');c.className='ch';c.textContent=ch;ws.appendChild(c)});e.appendChild(ws)})}});
  var sleep=function(ms){return new Promise(function(r){setTimeout(r,ms)})};
  var reduce=matchMedia('(prefers-reduced-motion: reduce)').matches;
  var people=[['Hamim','#ff0a5c'],['Sam','#22d3ee'],['Nora','#facc15'],['Leo','#a3e635'],['Mia','#c084fc'],['Zed','#fb923c'],['Ava','#38bdf8'],['Kai','#f472b6'],['Ravi','#34d399'],['Ivy','#fde047'],['Omar','#60a5fa'],['Lena','#f87171']];
  var cursors=people.map(function(p){
    var c=document.createElement('div');c.className='cur';c.style.setProperty('--c',p[1]);
    c.innerHTML='<svg viewBox="0 0 20 20"><path d="M2 1l15 8-6.5 1.8L8 17z"/></svg><span>'+p[0]+'</span>';
    document.body.appendChild(c);return c;
  });
  var btn=document.getElementById('replay'),running=false;

  function revealAll(){els.forEach(function(e){e.classList.add('in');[].forEach.call(e.querySelectorAll('.ch'),function(c){c.classList.add('on')})});cursors.forEach(function(c){c.style.opacity=0})}

  var rnd=function(a,b){return a+Math.random()*(b-a)};
  var wanderId=0,lastMove=0,following=false,cx=innerWidth/2,cy=innerHeight/2,sx=cx,sy=cy;
  function aim(x,y){var n=Date.now();if(n-lastMove>700)wakeAll(n);if(!following){sx=x;sy=y}cx=x;cy=y;lastMove=n}
  function touchAim(e){var t=e.touches[0];if(t)aim(t.clientX,t.clientY)}
  addEventListener('pointermove',function(e){aim(e.clientX,e.clientY)},{passive:true});
  addEventListener('pointerdown',function(e){aim(e.clientX,e.clientY)},{passive:true});
  addEventListener('touchstart',touchAim,{passive:true});
  addEventListener('touchmove',touchAim,{passive:true});
  addEventListener('scroll',function(){if(following)lastMove=Date.now()},{passive:true});
  function wander(){
    var id=++wanderId;
    cursors.forEach(function(c){(async function(){
      await sleep(rnd(0,900));
      while(id===wanderId){
        if(document.hidden){await sleep(800);continue}
        if(following){await sleep(120);continue}
        var d=rnd(1800,3800);
        var x=rnd(10,Math.max(60,innerWidth-110));
        var y=Math.random()<.65?scrollY+rnd(20,innerHeight-60):rnd(20,Math.max(80,document.documentElement.scrollHeight-80));
        c.style.transition='transform '+d+'ms cubic-bezier(.45,.05,.25,1),opacity .3s';
        point(c,x,y);c.style.transform='translate('+x+'px,'+y+'px)';
        var end=Date.now()+d+rnd(0,500);
        while(id===wanderId&&Date.now()<end&&!following)await sleep(120);
        level(c);
      }
    })()});
  }
  var st=cursors.map(function(c,i){return{x:0,y:0,vx:0,vy:0,on:false,wake:0,rad:rnd(30,115),ang:rnd(0,6.283),spin:rnd(.0005,.0014)*(i%2?1:-1),kS:rnd(2.2e-5,5e-5),damp:rnd(.88,.93),maxV:rnd(1,2.1)}}),last=performance.now();
  function wakeAll(n){st.forEach(function(q){q.wake=n+rnd(0,350)})}
  function frame(now){
    var dt=Math.min(50,now-last);last=now;var n=Date.now();
    following=!reduce&&!running&&n-lastMove<10000;
    if(following){
      var sm=1-Math.pow(.88,dt/16.7);sx+=(cx-sx)*sm;sy+=(cy-sy)*sm;
      for(var a=0;a<cursors.length;a++)for(var b=a+1;b<cursors.length;b++){
        var A=st[a],B=st[b];if(!A.on||!B.on)continue;
        var dx=A.x-B.x,dy=A.y-B.y,d=Math.hypot(dx,dy);
        if(d<44){if(d<1){dx=Math.random()-.5;dy=Math.random()-.5;d=Math.hypot(dx,dy)||1}
          var p=(44-d)/44*.008*dt/d;A.vx+=dx*p;A.vy+=dy*p;B.vx-=dx*p;B.vy-=dy*p}
      }
    }
    for(var i=0;i<cursors.length;i++){
      var c=cursors[i],q=st[i];
      if(following){
        if(!q.on){var m=new DOMMatrix(getComputedStyle(c).transform);q.x=m.e;q.y=m.f;q.vx=0;q.vy=0;q.on=true;c.style.transition='none';c.firstChild.style.transition='none';c.style.opacity=1}
        q.ang+=q.spin*dt;
        if(n>=q.wake){
          q.vx+=(sx+scrollX+Math.cos(q.ang)*q.rad-q.x)*q.kS*dt;
          q.vy+=(sy+scrollY+Math.sin(q.ang)*q.rad-q.y)*q.kS*dt;
        }
        var f=Math.pow(q.damp,dt/16.7);q.vx*=f;q.vy*=f;
        var sp=Math.hypot(q.vx,q.vy);if(sp>q.maxV){q.vx*=q.maxV/sp;q.vy*=q.maxV/sp}
        var r0=c._r||0;
        if(sp>.15){var df=((Math.atan2(q.vy,q.vx)*57.3+135-r0+540)%360)-180;c._r=r0+df*(1-Math.pow(.8,dt/16.7))}
        else{c._r=r0+(Math.round(r0/360)*360-r0)*(1-Math.pow(.92,dt/16.7))}
        c.firstChild.style.transform='rotate('+c._r+'deg)';
        q.x+=q.vx*dt;q.y+=q.vy*dt;put(c,q.x,q.y);
      }else if(q.on){q.on=false;c.style.transition='';c.firstChild.style.transition='';level(c)}
    }
    requestAnimationFrame(frame);
  }
  requestAnimationFrame(frame);
  function ease(t){return t<.5?2*t*t:1-Math.pow(-2*t+2,2)/2}
  function tween(d,fn){return new Promise(function(res){var t0=performance.now();(function f(n){var t=Math.min(1,(n-t0)/d);fn(ease(t));if(t<1)requestAnimationFrame(f);else res()})(t0)})}
  function mk(cls,css){var d=document.createElement('div');d.className=cls;d.style.cssText=css;document.body.appendChild(d);return d}
  function put(cur,x,y){cur.style.transform='translate('+x+'px,'+y+'px)'}
  function turn(c,deg){var r=c._r||0,d=((deg-r+540)%360)-180;c._r=r+d;c.firstChild.style.transform='rotate('+c._r+'deg)'}
  function point(c,x,y){var m=new DOMMatrix(getComputedStyle(c).transform),dx=x-m.e,dy=y-m.f;if(Math.hypot(dx,dy)>8)turn(c,Math.atan2(dy,dx)*57.3+135)}
  function level(c){turn(c,Math.round((c._r||0)/360)*360)}
  function pput(c,x,y){point(c,x,y);put(c,x,y)}
  async function dragBox(el,cur,col){
    var r=el.getBoundingClientRect(),x0=r.left+scrollX,y0=r.top+scrollY,w=r.width,h=r.height;
    var b=mk('drawbox','left:'+x0+'px;top:'+y0+'px;width:0;height:0;border-color:'+col+';background:'+col+'1f');
    var tag=document.createElement('span');tag.style.background=col;b.appendChild(tag);
    cur.style.transition='none';
    await tween(650,function(t){b.style.width=w*t+'px';b.style.height=h*t+'px';tag.textContent=Math.round(w*t)+' \u00d7 '+Math.round(h*t);put(cur,x0+w*t,y0+h*t)});
    cur.style.transition='';el.classList.add('in');
    setTimeout(function(){b.style.opacity=0},150);setTimeout(function(){b.remove()},700);
  }
  async function penBorder(el,cur,col){
    var r=el.getBoundingClientRect(),x0=r.left+scrollX,y0=r.top+scrollY,w=r.width,h=r.height;
    var s=document.createElementNS('http://www.w3.org/2000/svg','svg');
    s.setAttribute('class','pen');s.style.cssText='left:'+(x0-2)+'px;top:'+(y0-2)+'px;width:'+(w+4)+'px;height:'+(h+4)+'px';
    s.innerHTML='<rect x="2" y="2" width="'+w+'" height="'+h+'" rx="3" fill="none" stroke="'+col+'" stroke-width="2" pathLength="100" stroke-dasharray="100" stroke-dashoffset="100"/>';
    document.body.appendChild(s);var rc=s.firstChild;
    cur.style.transition='none';
    await tween(600,function(t){rc.style.strokeDashoffset=100*(1-t);var p=t*2*(w+h),px,py;
      if(p<w){px=x0+p;py=y0}else if((p-=w)<h){px=x0+w;py=y0+p}else if((p-=h)<w){px=x0+w-p;py=y0+h}else{p-=w;px=x0;py=y0+h-p}
      put(cur,px,py)});
    cur.style.transition='';el.classList.add('in');
    setTimeout(function(){s.style.opacity=0},150);setTimeout(function(){s.remove()},700);
  }
  async function guide(el,cur,dir){
    var r=el.getBoundingClientRect(),X=r.left+scrollX,Y=r.top+scrollY,g,len;
    if(dir==='v'){var ab=document.getElementById('about');len=ab.offsetHeight;g=mk('guide','left:'+X+'px;top:'+ab.offsetTop+'px;width:1px;height:0;background:#22d3ee');put(cur,X,ab.offsetTop);await sleep(300);
      cur.style.transition='none';await tween(550,function(t){g.style.height=len*t+'px';put(cur,X,ab.offsetTop+len*t)})}
    else{len=innerWidth;var gy=Y+r.height;g=mk('guide','left:0;top:'+gy+'px;width:0;height:1px;background:#22d3ee');put(cur,0,gy);await sleep(300);
      cur.style.transition='none';await tween(550,function(t){g.style.width=len*t+'px';put(cur,len*t,gy)})}
    cur.style.transition='';return g;
  }
  async function run(){
    if(running)return;running=true;wanderId++;btn.disabled=true;
    els.forEach(function(e){e.classList.remove('in');[].forEach.call(e.querySelectorAll('.ch'),function(c){c.classList.remove('on')})});
    window.scrollTo(0,0);await sleep(60);
    var lr=els[0].getBoundingClientRect();
    cursors.forEach(function(c){
      c.style.transition='none';
      put(c,lr.left+scrollX+rnd(-30,150),lr.top+scrollY+rnd(-10,50));
      void c.offsetWidth;c.style.transition='';
      setTimeout(function(){c.style.opacity=1},Math.random()*250);
    });
    await sleep(600);
    var queue=els.slice(),scrolling=false;
    await Promise.all(cursors.map(function(cur,k){return (async function(){
      var col=people[k][1];
      await sleep(Math.random()*250);
      while(queue.length){
        var el=queue.shift();
        var r=el.getBoundingClientRect(),top=r.top+scrollY;
        if((r.bottom>innerHeight-60||r.top<70)&&!scrolling){scrolling=true;window.scrollTo({top:top-innerHeight*.35,behavior:'smooth'});setTimeout(function(){scrolling=false},350)}
        var corner=el.hasAttribute('data-draw')||el.hasAttribute('data-pen');
        pput(cur,r.left+scrollX+(corner?0:r.width*rnd(.2,.8)),top+(corner?0:r.height*rnd(.3,.7)));
        await sleep(rnd(450,650));level(cur);
        var g=null;
        if(el.hasAttribute('data-guide'))g=await guide(el,cur,el.getAttribute('data-guide'));
        if(el.hasAttribute('data-draw'))await dragBox(el,cur,col);
        else if(el.hasAttribute('data-pen'))await penBorder(el,cur,col);
        if(el.hasAttribute('data-type')){var chs=el.querySelectorAll('.ch'),cr=document.createElement('span'),slow=el.classList.contains('logo')||el.tagName==='H1';cr.className='caret';if(el.hasAttribute('data-box'))el.classList.add('in');for(var j=0;j<chs.length;j++){chs[j].classList.add('on');chs[j].after(cr);await sleep(slow?rnd(40,60):rnd(14,28))}cr.remove();el.classList.add('in')}
        else{setTimeout(function(){el.classList.add('in')},60)}
        if(g){var gg=g;setTimeout(function(){gg.style.opacity=0},500);setTimeout(function(){gg.remove()},1100)}
        await sleep(rnd(120,280));
      }
    })()}));
    await sleep(500);
    running=false;btn.disabled=false;wander();
  }

  var tip=document.getElementById('tip'),tipTimer;
  function hideTip(){tip.classList.remove('show');tip.setAttribute('aria-hidden','true')}
  function showTip(a){var r=a.getBoundingClientRect();tip.style.left=Math.min(Math.max(r.left+scrollX+r.width/2,100),innerWidth-100)+'px';tip.style.top=(r.top+scrollY-10)+'px';tip.setAttribute('aria-hidden','false');tip.classList.add('show');clearTimeout(tipTimer);tipTimer=setTimeout(hideTip,2600)}
  [].forEach.call(document.querySelectorAll('a[data-soon]'),function(a){a.addEventListener('click',function(e){e.preventDefault();showTip(a)})});
  addEventListener('pointerdown',function(e){if(!e.target.closest('a[data-soon]'))hideTip()});
  addEventListener('keydown',function(e){if(e.key==='Escape')hideTip()});

  btn.addEventListener('click',run);
  if(reduce){revealAll();btn.hidden=true}else{run()}
})();
</script>
</body>
</html>
