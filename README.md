<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>NICU Discharge Readiness Checklist</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&family=Great+Vibes&display=swap" rel="stylesheet">
<style>
:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--ink:#12324a;--mute:#4a6478;--aqua:#0aa5b8;--mint:#1fb98a;--lav:#7b6fd6;--blue:#2f7fe0;--amber:#b7791f;--line:#d5e6ee;--bg:#f2fbfd;--acc:var(--aqua)}
html{scroll-padding-top:150px}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;font-family:Nunito,system-ui,-apple-system,Segoe UI,sans-serif;color:var(--ink);line-height:1.5;background:var(--bg);
background-image:radial-gradient(circle at 8% 4%,#c9f3f2 0,transparent 32%),radial-gradient(circle at 95% 12%,#e2dcff 0,transparent 30%),radial-gradient(circle at 50% 100%,#d5ecff 0,transparent 40%);background-attachment:fixed}
.wrap{max-width:980px;margin:0 auto;padding:0 16px 40px}
.hero{position:relative;overflow:hidden;margin:16px 0;padding:28px 24px;border-radius:28px;background:linear-gradient(135deg,#e2fbf8,#e9f0ff 60%,#efe8ff);border:1px solid #fff;box-shadow:0 12px 34px rgba(47,127,224,.15)}
.hero svg.deco{position:absolute;right:-10px;top:0;width:min(60%,420px);height:100%;opacity:.9;pointer-events:none}
.hero .sub{font-weight:700;color:var(--lav);font-size:.95rem;letter-spacing:.04em}
.hero h1{margin:4px 0 6px;font-size:clamp(1.8rem,5.5vw,3rem);font-weight:800;line-height:1.1;letter-spacing:.01em;position:relative}
.hero p{margin:0 0 18px;color:var(--mute);font-size:1.05rem;position:relative}
.ring{display:flex;align-items:center;gap:16px;position:relative}
.ringbox{position:relative;width:96px;height:96px;flex:none}
.ringbox svg{transform:rotate(-90deg)}
.ringbox b{position:absolute;inset:0;display:grid;place-items:center;font-size:1.35rem}
.ring .lbl{font-weight:800;font-size:.95rem;color:var(--mute)}
.ring .pct{font-size:1.6rem;font-weight:800}
.dash{position:sticky;top:0;top:env(safe-area-inset-top,0px);z-index:20;margin:0 0 20px;padding:12px 16px;border-radius:20px;background:rgba(255,255,255,.82);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border:1px solid #fff;box-shadow:0 8px 26px rgba(18,50,74,.12)}
.dtop{display:flex;flex-wrap:wrap;gap:8px 18px;align-items:center;justify-content:space-between}
.dtop strong{font-size:1rem}
.counts{display:flex;flex-wrap:wrap;gap:6px 14px;font-weight:700;font-size:.92rem}
.bars{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:8px 16px;margin-top:10px}
.bar .t{display:flex;justify-content:space-between;font-size:.82rem;font-weight:700;color:var(--mute)}
.track{height:9px;border-radius:9px;background:#e3eef4;overflow:hidden;margin-top:3px}
.fill{height:100%;width:0;border-radius:9px;background:linear-gradient(90deg,var(--aqua),var(--mint));transition:width .5s ease}
.actions{display:flex;flex-wrap:wrap;gap:10px;margin:0 0 22px}
button{font:inherit;cursor:pointer}
.btn{min-height:48px;padding:10px 18px;border-radius:14px;border:2px solid var(--aqua);background:#fff;color:var(--ink);font-weight:800;box-shadow:0 3px 10px rgba(10,165,184,.12)}
.btn:hover{background:#e9fbfd}
.btn.pri{background:linear-gradient(135deg,var(--aqua),var(--blue));color:#fff;border-color:transparent}
.btn.warn{border-color:var(--amber)}
:focus-visible{outline:3px solid var(--blue);outline-offset:2px}
.sec{--acc:var(--aqua);margin:0 0 26px;padding:20px 18px;border-radius:26px;background:rgba(255,255,255,.78);backdrop-filter:blur(8px);-webkit-backdrop-filter:blur(8px);border:1px solid #fff;border-top:6px solid var(--acc);box-shadow:0 10px 30px rgba(18,50,74,.09);position:relative}
.sec.s2{--acc:var(--lav)}.sec.s3{--acc:var(--mint)}.sec.s4{--acc:var(--blue)}
.sec h2{margin:0;font-size:clamp(1.3rem,3.6vw,1.75rem);font-weight:800;color:var(--ink)}
.sec .ss{margin:2px 0 14px;color:var(--mute);font-weight:700}
.sec .secpct{position:absolute;right:16px;top:16px;font-weight:800;color:var(--acc);background:#fff;border:2px solid var(--acc);border-radius:20px;padding:2px 12px;font-size:.9rem}
.info{margin:0 0 14px;padding:14px 16px;border-radius:16px;background:#eef4ff;border:1px solid #cfe0fb;font-weight:600}
.item{border-radius:18px;background:#fff;border:2px solid var(--line);margin-bottom:10px;transition:border-color .3s,box-shadow .3s,background .3s}
.item.done{border-color:var(--mint);background:#f3fff9;box-shadow:0 0 0 4px rgba(31,185,138,.12)}
.item.na{background:#f4f6f8;border-style:dashed}
.item.pend{border-left:8px solid #e3a92a}
.row{display:flex;align-items:center;gap:12px;padding:10px 12px}
.cb{flex:none;width:44px;height:44px;border-radius:12px;border:3px solid var(--acc);background:#fff;display:grid;place-items:center;padding:0}
.cb svg{width:26px;height:26px;stroke:#fff;fill:none;stroke-width:4;stroke-linecap:round;stroke-linejoin:round;stroke-dasharray:30;stroke-dashoffset:30;transition:stroke-dashoffset .35s ease}
.done .cb{background:var(--mint);border-color:var(--mint)}
.done .cb svg{stroke-dashoffset:0}
.na .cb{border-color:#98a8b4;background:#e6ebef}
.ttl{flex:1;min-width:0;font-weight:700;font-size:1.05rem;text-align:left;background:none;border:0;color:var(--ink);padding:4px 0}
.na .ttl{color:#65788a;text-decoration:line-through}
.tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:4px}
.tag{font-size:.74rem;font-weight:800;padding:2px 9px;border-radius:20px;background:#efe9ff;color:#4b3fb0;border:1px solid #cfc6f5}
.tag.cr{background:#fff3d9;color:#7a4b00;border-color:#f0cf8b}
.st{flex:none;min-height:44px;min-width:118px;padding:6px 10px;border-radius:12px;border:2px solid;font-weight:800;font-size:.85rem;background:#fff}
.st.c{border-color:var(--mint);color:#0b6e50}.st.p{border-color:#e3a92a;color:#7a4b00;background:#fff8e6}.st.n{border-color:#98a8b4;color:#4a6478}
.exp{flex:none;width:44px;height:44px;border-radius:12px;border:2px solid var(--line);background:#fff;font-size:1.1rem;color:var(--mute);transition:transform .25s}
.item.open .exp{transform:rotate(180deg)}
.det{display:none;padding:0 14px 14px 68px;color:var(--mute);font-size:.95rem}
.item.open .det{display:block}
.det textarea{width:100%;min-height:56px;margin-top:8px;border-radius:10px;border:2px solid var(--line);padding:8px;font:inherit;color:var(--ink)}
.final{margin:0 0 26px;padding:22px;border-radius:26px;border:3px solid;background:#fff}
.final.ok{border-color:var(--mint);background:linear-gradient(135deg,#f0fff8,#fff)}
.final.rev{border-color:#e3a92a;background:linear-gradient(135deg,#fff9e8,#fff)}
.final h3{margin:0 0 6px;font-size:1.5rem}
.final ul{margin:8px 0 0;padding-left:22px}
.final .disc{margin-top:12px;font-weight:700;color:var(--mute)}
footer{text-align:center;padding:20px 0 30px;color:var(--mute)}
footer .sig{font-family:'Great Vibes','Snell Roundhand','Brush Script MT',cursive;font-size:2.6rem;color:#2b4d8f;line-height:1.1}
footer small{display:block;font-weight:700}
.toast{position:fixed;left:50%;bottom:calc(24px + env(safe-area-inset-bottom,0px));transform:translate(-50%,30px);opacity:0;z-index:60;background:#fff;border:2px solid var(--mint);border-radius:30px;padding:10px 22px;font-weight:800;color:#0b6e50;box-shadow:0 0 24px rgba(31,185,138,.45);pointer-events:none;transition:all .3s}
.toast.show{opacity:1;transform:translate(-50%,0)}
.ov{position:fixed;inset:0;z-index:80;background:rgba(18,50,74,.4);display:none;align-items:center;justify-content:center;padding:16px}
.ov.show{display:flex}
.modal{background:#fff;border-radius:24px;max-width:640px;width:100%;max-height:88vh;overflow:auto;padding:22px;box-shadow:0 20px 60px rgba(0,0,0,.3);animation:pop .3s ease}
.modal h3{margin:0 0 8px;font-size:1.5rem}
.modal pre{white-space:pre-wrap;font:inherit;background:#f2fbfd;border:1px solid var(--line);border-radius:12px;padding:12px;font-size:.92rem}
.mbtns{display:flex;flex-wrap:wrap;gap:10px;margin-top:14px;justify-content:flex-end}
@keyframes pop{from{transform:scale(.92);opacity:0}to{transform:none;opacity:1}}
.cele{position:fixed;inset:0;z-index:70;pointer-events:none;display:none;align-items:center;justify-content:center;flex-direction:column;overflow:hidden}
.cele.show{display:flex}
.cele .card{background:rgba(255,255,255,.95);border:3px solid var(--mint);border-radius:26px;padding:20px 36px;text-align:center;font-weight:800;font-size:1.6rem;box-shadow:0 0 40px rgba(31,185,138,.4);animation:pop .4s ease}
.cele .card small{display:block;font-size:.95rem;color:var(--mute)}
.bub{position:absolute;bottom:-40px;border-radius:50%;border:2px solid rgba(10,165,184,.5);background:rgba(160,235,240,.35);animation:rise 2.2s ease-in forwards}
@keyframes rise{to{transform:translateY(-110vh)}}
@media(max-width:640px){.st{min-width:0;font-size:.78rem}.det{padding-left:14px}.row{flex-wrap:wrap}.ttl{flex-basis:calc(100% - 110px)}.sec .secpct{position:static;display:inline-block;margin-bottom:8px}.hero svg.deco{opacity:.35}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
@media print{body{background:#fff}.dash,.actions,.toast,.ov,.cele,.exp{display:none!important}.sec,.hero,.final{box-shadow:none;break-inside:avoid}.det{display:block!important}.det textarea{border:1px solid #999}}
</style>
</head>
<body>
<div class="wrap">
<header class="hero">
<svg class="deco" viewBox="0 0 420 200" aria-hidden="true"><g fill="#fff" opacity=".8"><circle cx="330" cy="40" r="30"/><circle cx="380" cy="120" r="18"/><circle cx="260" cy="150" r="12"/></g><g fill="none" stroke="#0aa5b8" stroke-width="2.5" opacity=".6"><circle cx="330" cy="40" r="30"/><circle cx="380" cy="120" r="18"/><path d="M0 110h110l14-34 20 68 18-52 12 18h230" stroke-linecap="round" stroke-linejoin="round"/></g><g fill="#7b6fd6" opacity=".55"><path d="M290 90l4 9 10 1-8 7 3 10-9-6-9 6 3-10-8-7 10-1z"/><path d="M200 30l3 7 8 1-6 5 2 8-7-5-7 5 2-8-6-5 8-1z"/></g><g transform="translate(350 150)"><circle r="22" fill="#fdebd8" stroke="#0aa5b8" stroke-width="2"/><circle cx="-7" cy="-3" r="2" fill="#12324a"/><circle cx="7" cy="-3" r="2" fill="#12324a"/><path d="M-6 7q6 5 12 0" stroke="#12324a" stroke-width="2" fill="none" stroke-linecap="round"/><path d="M-14-16q14-14 28 0" stroke="#7b6fd6" stroke-width="4" fill="none" stroke-linecap="round"/></g></svg>
<div class="sub">Interactive Clinical Checklist</div>
<h1>NICU DISCHARGE READINESS</h1>
<p>Systematic assessment before NICU discharge</p>
<div class="ring"><div class="ringbox"><svg width="96" height="96" viewBox="0 0 96 96"><circle cx="48" cy="48" r="40" fill="none" stroke="#fff" stroke-width="10"/><circle id="ringc" cx="48" cy="48" r="40" fill="none" stroke="#0aa5b8" stroke-width="10" stroke-linecap="round" stroke-dasharray="251.3" stroke-dashoffset="251.3" style="transition:stroke-dashoffset .6s"/></svg><b id="ringt">0%</b></div>
<div><div class="lbl">DISCHARGE READINESS</div><div class="pct" id="heroPct">0% Complete</div></div></div>
</header>

<div class="dash" id="dash" aria-live="polite">
<div class="dtop"><strong>DISCHARGE READINESS: <span id="dPct">0%</span></strong>
<div class="counts"><span>🟢 Completed: <span id="cC">0</span></span><span>🟡 Pending: <span id="cP">0</span></span><span>⚪ Not applicable: <span id="cN">0</span></span></div></div>
<div class="bars" id="bars"></div>
</div>

<div class="actions">
<button class="btn warn" id="bAll">✓ Mark All Completed</button>
<button class="btn" id="bReset">↻ Reset Checklist</button>
<button class="btn" id="bOut">▣ View Outstanding Items</button>
<button class="btn pri" id="bSum">📋 Generate Discharge Checklist Summary</button>
</div>

<main id="secs"></main>
<section class="final" id="final" aria-live="polite"></section>

<footer>
<div class="sig">Dr Ahmed Tawfik</div>
<small>NICU Clinical Education &amp; Decision Support</small>
<small style="font-weight:600;margin-top:6px">Checklist and decision-support tool only. Not an official approval or electronic authorization.</small>
</footer>
</div>

<div class="toast" id="toast" role="status">✓ Completed</div>
<div class="cele" id="cele"><div class="card">✨ Section Complete<small id="celeS"></small></div></div>
<div class="ov" id="ov"><div class="modal" role="dialog" aria-modal="true" id="modal"></div></div>

<script>
const CR="Clinical review required",WI="When indicated",WA="When applicable",CS="Clinical/Social review";
const DATA=[
{id:"med",name:"Medical Readiness",title:"1. NEONATAL MEDICAL READINESS",sub:"Before discharge from NICU, the infant should have:",cls:"s1",items:[
["Open crib at weight 1600 g","Open crib at weight 1600 g"],
["Discharging weight 1700 g","Discharging weight 1700 g"],
["Stable temperature in open crib","Stable temperature in an open crib at normal room temperature (24–25°C) for at least 24 hours"],
["Neurophysiologic stability","Neurophysiologic stability",[CR]],
["Mature respiratory control","Mature respiratory control, with no apnea or bradycardia, for up to 5 days after discontinuation of caffeine therapy",[CR]],
["Mature oral feeding skills","Mature oral feeding skills by breast or bottle sufficient to provide adequate nutrition and support growth",[CR]],
["Consistent appropriate weight gain","Consistent appropriate weight gain for 3 days"],
["No ongoing NICU-level intensive care","No requirement for ongoing NICU-level intensive care",[CR]]]},
{id:"scr",name:"Screening & Prevention",title:"2. SCREENING, VACCINATION & PREVENTIVE CARE",sub:"Before discharge",cls:"s2",items:[
["Newborn metabolic screening","Newborn metabolic screening completed"],
["CCHD screening","CCHD screening completed"],
["Hearing screening","Hearing screening completed"],
["Red Reflex screening","Red Reflex screening completed"],
["ROP screening","ROP screening arranged/completed when indicated",[WI]],
["Immunizations","Appropriate immunizations according to chronological age"],
["RSV prophylaxis","Eligible infants should receive RSV prophylaxis according to the applicable guideline",[WI]],
["Imaging review in high-risk infants","In high-risk infants, appropriate imaging—e.g., cranial ultrasound when indicated—should be reviewed before discharge",[WI,CR]]]},
{id:"par",name:"Parental Readiness",title:"3. PARENTAL READINESS",sub:"Parents/caregivers should demonstrate:",cls:"s3",items:[
["Consistent involvement in care","Consistent involvement in the infant's care"],
["Competence with feeding","Competence with feeding"],
["Positioning and safe sleep","Appropriate positioning and safe sleep"],
["Medication administration","Medication administration"],
["Respiratory treatments","Respiratory treatments if required",[WA]],
["Gastrostomy/tracheostomy care training","Training in gastrostomy/tracheostomy care when applicable",[WA]],
["Home cardiorespiratory monitoring","Ability to use home cardiorespiratory monitoring equipment if prescribed",[WA]],
["CPR training","CPR training is advisable"],
["Home equipment/services arranged","Required home equipment/services—such as oxygen, ventilation, monitoring or feeding pumps—must be arranged before discharge",[WA]],
["Social/financial needs","Social/financial needs should be assessed",[CS]]]},
{id:"dis",name:"Discharge Planning",title:"4. FOLLOW-UP & DISCHARGE PLANNING",sub:"Before discharge",cls:"s4",intro:"The discharge process should be multidisciplinary and include physicians, nurses, respiratory therapists, rehabilitation staff and social workers.",items:[
["NICU course summarized","The complete NICU course should be summarized in the medical record"],
["Outstanding investigations reviewed","All outstanding investigations should be reviewed"],
["Subspecialist assessment","Relevant subspecialists should assess the infant before discharge when ongoing problems exist",[WA]],
["Primary-care and specialty follow-up","Primary-care and specialty follow-up should be arranged"],
["Nutrition and growth plans","Nutritional and growth-monitoring plans should be established"],
["Neurodevelopmental follow-up","High-risk/extremely preterm infants should have neurodevelopmental follow-up",[WA]],
["Follow-up visit in 3–7 days","A follow-up visit should be scheduled within 3–7 days after discharge, with additional specialty follow-up as required"]]}
];
DATA.forEach(s=>s.items.forEach(it=>{it[0]=it[1]}));
// state: c=completed, p=pending, n=not applicable
let S={},N={};
DATA.forEach(s=>s.items.forEach((it,i)=>{it.k=s.id+i;S[it.k]="p";N[it.k]=""}));
try{const r=sessionStorage.getItem("nicuChk");if(r){const o=JSON.parse(r);if(o.S)Object.assign(S,o.S);if(o.N)Object.assign(N,o.N)}}catch(e){}
const $=id=>document.getElementById(id);
const open={};
const ICON={c:"🟢 Completed",p:"🟡 Pending",n:"⚪ Not applicable"};
const CLS={c:"c",p:"p",n:"n"};
const RC={c:"done",p:"pend",n:"na"};
function save(){try{sessionStorage.setItem("nicuChk",JSON.stringify({S,N}))}catch(e){}}
function stats(sec){const a=sec?sec.items:DATA.flatMap(s=>s.items);let c=0,p=0,n=0;a.forEach(i=>{const v=S[i.k];v=="c"?c++:v=="n"?n++:p++});const req=c+p;return{c,p,n,total:a.length,pct:req?Math.round(c/req*100):(a.length?100:0),req}}
function esc(t){return String(t).replace(/[&<>"]/g,m=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[m]))}
function build(){
 $("secs").innerHTML=DATA.map(s=>`<section class="sec ${s.cls}" id="sec-${s.id}"><span class="secpct" id="sp-${s.id}">0%</span><h2>${s.title}</h2><div class="ss">${s.sub}</div>${s.intro?`<div class="info">ℹ️ ${s.intro}</div>`:""}${s.items.map(it=>`<div class="item" id="it-${it.k}">
<div class="row"><button class="cb" data-t="${it.k}" aria-label="Toggle completed: ${esc(it[0])}"><svg viewBox="0 0 30 30"><path d="M6 16l6 6 12-14"/></svg></button>
<div class="ttl"><span data-x="${it.k}" style="cursor:pointer">${esc(it[0])}</span>${it[2]?`<div class="tags">${it[2].map(t=>`<span class="tag ${t==CR?"cr":""}">${t==CR?"⚠ ":""}${t}</span>`).join("")}</div>`:""}</div>
<button class="st" data-s="${it.k}"></button>
<button class="exp" data-x="${it.k}" aria-label="Show details">▾</button></div>
<div class="det"><div>Details / clinician note</div><textarea data-n="${it.k}" placeholder="Optional clinician note (session only)" aria-label="Note">${esc(N[it.k])}</textarea></div></div>`).join("")}</section>`).join("");
 $("bars").innerHTML=DATA.map(s=>`<div class="bar"><div class="t"><span>${s.name}</span><span id="bp-${s.id}">0%</span></div><div class="track"><div class="fill" id="bf-${s.id}"></div></div></div>`).join("");
}
function render(){
 DATA.forEach(s=>{s.items.forEach(it=>{const el=$("it-"+it.k),v=S[it.k];el.className="item "+RC[v]+(open[it.k]?" open":"");const b=el.querySelector(".st");b.className="st "+CLS[v];b.textContent=ICON[v];b.setAttribute("aria-label","Status: "+ICON[v].slice(2)+". Tap to change");
 el.querySelector(".cb").setAttribute("aria-pressed",v=="c")});
 const st=stats(s);$("sp-"+s.id).textContent=st.pct+"%";$("bp-"+s.id).textContent=st.pct+"%";$("bf-"+s.id).style.width=st.pct+"%"});
 const t=stats();$("dPct").textContent=t.pct+"%";$("heroPct").textContent=t.pct+"% Complete";$("ringt").textContent=t.pct+"%";
 $("ringc").style.strokeDashoffset=251.3*(1-t.pct/100);$("cC").textContent=t.c;$("cP").textContent=t.p;$("cN").textContent=t.n;
 const out=outstanding(),f=$("final");
 if(!out.length&&t.c>0){f.className="final ok";f.innerHTML=`<h3>🟢 CHECKLIST COMPLETE</h3><div>All documented checklist items have been reviewed.</div><div class="disc">Final clinical discharge decision remains with the responsible NICU team.</div>`}
 else{f.className="final rev";f.innerHTML=`<h3>🟡 REVIEW REQUIRED</h3><div>Some checklist items remain incomplete or require clinical review before discharge.</div><div style="margin-top:10px;font-weight:800">Outstanding items</div><ul>${out.map(o=>`<li>${esc(o.it[0])}${o.it[2]&&o.it[2].includes(CR)?" <span class='tag cr'>"+CR+"</span>":""}</li>`).join("")}</ul><div class="disc">This checklist does not determine whether an infant is safe or unsafe for discharge.</div>`}
 save();
}
function outstanding(){return DATA.flatMap(s=>s.items.filter(i=>S[i.k]=="p").map(it=>({s,it})))}
function toast(){const t=$("toast");t.classList.add("show");clearTimeout(toast.h);toast.h=setTimeout(()=>t.classList.remove("show"),1300)}
function cele(name){const c=$("cele");$("celeS").textContent=name;c.querySelectorAll(".bub").forEach(b=>b.remove());
 for(let i=0;i<16;i++){const b=document.createElement("span");b.className="bub";const z=10+Math.random()*26;b.style.cssText=`left:${Math.random()*100}%;width:${z}px;height:${z}px;animation-delay:${Math.random()*.6}s`;c.appendChild(b)}
 c.classList.add("show");clearTimeout(cele.h);cele.h=setTimeout(()=>c.classList.remove("show"),2400)}
function setState(k,v){
 const sec=DATA.find(s=>s.items.some(i=>i.k==k)),was=stats(sec).pct==100&&stats(sec).c>0;
 S[k]=v;render();
 if(v=="c"){const now=stats(sec);if(now.pct==100&&!was&&now.p==0)cele(sec.name);else toast()}
}
const nextS={p:"c",c:"n",n:"p"};
document.addEventListener("click",e=>{
 const t=e.target.closest("[data-t],[data-s],[data-x]");if(!t)return;
 if(t.dataset.t){const k=t.dataset.t;setState(k,S[k]=="c"?"p":"c")}
 else if(t.dataset.s){const k=t.dataset.s;setState(k,nextS[S[k]])}
 else if(t.dataset.x){const k=t.dataset.x;open[k]=!open[k];$("it-"+k).classList.toggle("open",!!open[k])}
});
document.addEventListener("input",e=>{if(e.target.dataset&&e.target.dataset.n){N[e.target.dataset.n]=e.target.value;save()}});
function modal(html,btns){$("modal").innerHTML=html+`<div class="mbtns">${btns.map((b,i)=>`<button class="btn ${b.p?"pri":""}" data-mb="${i}">${b.l}</button>`).join("")}</div>`;
 $("ov").classList.add("show");$("modal").querySelectorAll("[data-mb]").forEach(el=>el.onclick=()=>{const b=btns[el.dataset.mb];if(b.keep!==true)closeM();if(b.f)b.f()});
 const f=$("modal").querySelector("button");if(f)f.focus()}
function closeM(){$("ov").classList.remove("show")}
$("ov").addEventListener("click",e=>{if(e.target.id=="ov")closeM()});
document.addEventListener("keydown",e=>{if(e.key=="Escape")closeM()});
function outList(){const o=outstanding();if(!o.length)return"<p>No outstanding items. All applicable items are marked completed.</p>";
 return DATA.map(s=>{const a=o.filter(x=>x.s==s);return a.length?`<div style="margin-top:8px"><b>${s.title}</b><ul>${a.map(x=>`<li>${esc(x.it[0])}${x.it[2]&&x.it[2].includes(CR)?" <span class='tag cr'>"+CR+"</span>":""}</li>`).join("")}</ul></div>`:""}).join("")}
$("bAll").onclick=()=>modal("<h3>Mark all completed?</h3><p>For demonstration and testing only. This marks every item as completed and does not reflect a real clinical assessment.</p>",[{l:"Cancel"},{l:"Mark all completed",p:1,f:()=>{DATA.forEach(s=>s.items.forEach(i=>S[i.k]="c"));render();cele("All sections")}}]);
$("bReset").onclick=()=>modal("<h3>Reset checklist?</h3><p>All statuses will return to Pending and notes will be cleared.</p>",[{l:"Cancel"},{l:"Reset",p:1,f:()=>{DATA.forEach(s=>s.items.forEach(i=>{S[i.k]="p";N[i.k]=""}));document.querySelectorAll("textarea").forEach(t=>t.value="");render()}}]);
$("bOut").onclick=()=>modal("<h3>▣ Outstanding items</h3>"+outList(),[{l:"Close",p:1}]);
function summaryText(){const t=stats(),L=[];const now=new Date().toLocaleString();
 L.push("NICU DISCHARGE READINESS – CHECKLIST SUMMARY","Generated: "+now,"Completion: "+t.pct+"% ("+t.c+" completed, "+t.p+" pending, "+t.n+" not applicable)","");
 const grp=(title,v)=>{L.push(title);let any=false;DATA.forEach(s=>s.items.forEach(i=>{if(S[i.k]==v){any=true;L.push("  - "+i[0]+(N[i.k]?" [Note: "+N[i.k]+"]":""))}}));if(!any)L.push("  (none)");L.push("")};
 grp("COMPLETED ITEMS","c");grp("PENDING ITEMS","p");grp("NOT APPLICABLE ITEMS","n");
 L.push("ITEMS REQUIRING CLINICAL REVIEW ("+CR+")");let any=false;DATA.forEach(s=>s.items.forEach(i=>{if(i[2]&&i[2].includes(CR)){any=true;L.push("  - "+i[0]+": "+(S[i.k]=="c"?"marked completed":S[i.k]=="n"?"marked not applicable":"pending"))}}));if(!any)L.push("  (none)");
 L.push("","Final clinical discharge decision remains with the responsible NICU team.","Designed by Dr Ahmed Tawfik – NICU Clinical Education & Decision Support");return L.join("\n")}
function showSummary(){const txt=summaryText();modal("<h3>📋 Checklist summary</h3><pre id='sumtxt'></pre>",[{l:"Print",f:()=>{const w=window.open("","_blank");if(!w){window.print();return}w.document.write("<pre style='font:14px/1.5 sans-serif;white-space:pre-wrap'>"+esc(txt)+"</pre>");w.document.close();w.print()},keep:true},{l:"Copy text",keep:true,f:()=>{const b=$("modal").querySelector("[data-mb='1']");const done=()=>{b.textContent="Copied ✓"};if(navigator.clipboard&&navigator.clipboard.writeText)navigator.clipboard.writeText(txt).then(done,()=>sel());else sel();function sel(){const r=document.createRange();r.selectNodeContents($("sumtxt"));const s=getSelection();s.removeAllRanges();s.addRange(r);try{document.execCommand("copy");done()}catch(e){b.textContent="Select and copy manually"}}}},{l:"Close",p:1}]);$("sumtxt").textContent=txt}
$("bSum").onclick=()=>{const o=outstanding();if(!o.length)return showSummary();
 modal("<h3>🟡 Review Required</h3><p>Some checklist items remain incomplete or require clinical review before discharge.</p><b>Outstanding items</b>"+outList(),[{l:"Close"},{l:"Generate summary anyway",p:1,f:showSummary}])};
build();render();
</script>
</body>
</html>
