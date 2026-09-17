<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Examora — Prepare smarter. Perform better.</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=IBM+Plex+Sans:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
/* ============ TOKENS ============ */
:root{
  --paper:#F4F2EC;
  --paper-dim:#EAE7DE;
  --ink:#141B26;
  --ink-soft:#3B4452;
  --line:rgba(20,27,38,0.14);
  --line-strong:rgba(20,27,38,0.28);
  --surface:#FFFFFF;
  --surface-raised:#FDFCF9;
  --accent:#3E6E8E;
  --accent-strong:#2C5674;
  --accent-tint:rgba(62,110,142,0.12);
  --good:#4F7A5C;
  --good-tint:rgba(79,122,92,0.14);
  --bad:#A54F3F;
  --bad-tint:rgba(165,79,63,0.13);
  --mark:#B4863E;
  --mark-tint:rgba(180,134,62,0.15);
  --font-display:'Fraunces',serif;
  --font-ui:'IBM Plex Sans',sans-serif;
  --font-mono:'IBM Plex Mono',monospace;
  --radius:10px;
  --radius-sm:6px;
  --shadow-card:0 1px 2px rgba(20,27,38,0.05);
  color-scheme: light;
}
html[data-theme="dark"]{
  --paper:#0E1520;
  --paper-dim:#0A0F17;
  --ink:#EDEBE3;
  --ink-soft:#9AA6B5;
  --line:rgba(237,235,227,0.10);
  --line-strong:rgba(237,235,227,0.20);
  --surface:#161F2C;
  --surface-raised:#1B2635;
  --accent:#7CA7C4;
  --accent-strong:#9CC0DA;
  --accent-tint:rgba(124,167,196,0.14);
  --good:#7FAE8C;
  --good-tint:rgba(127,174,140,0.14);
  --bad:#C9786A;
  --bad-tint:rgba(201,120,106,0.14);
  --mark:#D3A868;
  --mark-tint:rgba(211,168,104,0.15);
  --shadow-card:0 1px 2px rgba(0,0,0,0.2);
  color-scheme: dark;
}

*{box-sizing:border-box;}
html,body{margin:0;padding:0;}
body{
  background:var(--paper);
  color:var(--ink);
  font-family:var(--font-ui);
  -webkit-font-smoothing:antialiased;
  min-height:100vh;
  transition:background .35s ease, color .35s ease;
}
::selection{background:var(--accent-tint);color:var(--ink);}
a{color:inherit;}
button{font-family:inherit;}
h1,h2,h3,h4{font-family:var(--font-display);margin:0;font-weight:600;letter-spacing:-0.01em;}
p{margin:0;}
.scrim-grid{
  position:fixed;inset:0;pointer-events:none;z-index:0;
  background-image:
    linear-gradient(var(--line) 1px, transparent 1px),
    linear-gradient(90deg, var(--line) 1px, transparent 1px);
  background-size:64px 64px;
  opacity:0.16;
  mask-image:radial-gradient(ellipse 80% 60% at 30% 0%, black, transparent 75%);
}
html[data-theme="light"] .scrim-grid{opacity:.22;}

/* ============ MOBILE TOPBAR ============ */
.topbar{
  display:none;
  position:sticky;top:0;z-index:40;
  align-items:center;justify-content:space-between;
  padding:14px 18px;border-bottom:1px solid var(--line);
  background:var(--paper);
}
.topbar .mark{font-family:var(--font-display);font-size:19px;font-weight:700;}
.menu-btn{
  width:36px;height:36px;border-radius:var(--radius-sm);border:1px solid var(--line-strong);
  background:var(--surface);display:flex;align-items:center;justify-content:center;cursor:pointer;
  flex-direction:column;gap:4px;
}
.menu-btn span{display:block;width:16px;height:1.5px;background:var(--ink);}
.rail-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.35);z-index:44;}
.rail-overlay.show{display:block;}

/* ============ SHELL ============ */
.shell{
  display:grid;
  grid-template-columns:232px 1fr;
  min-height:100vh;
  position:relative;
  z-index:1;
}
.rail{
  border-right:1px solid var(--line);
  padding:28px 18px 20px;
  display:flex;flex-direction:column;
  position:sticky;top:0;height:100vh;overflow-y:auto;
}
.rail-brand{
  display:flex;align-items:baseline;gap:8px;
  padding:0 6px 22px;
  border-bottom:1px solid var(--line);
  margin-bottom:18px;
}
.rail-brand .mark{
  font-family:var(--font-display);font-size:22px;font-weight:700;
}
.rail-brand .sub{font-size:10.5px;color:var(--ink-soft);font-family:var(--font-mono);letter-spacing:.03em;}
.rail-index-label{
  font-size:10.5px;color:var(--ink-soft);padding:0 6px;margin-bottom:8px;font-family:var(--font-mono);letter-spacing:.04em;
}
nav.rail-nav{display:flex;flex-direction:column;gap:1px;margin-bottom:20px;}
.rail-item{
  display:flex;align-items:center;gap:10px;
  padding:9px 8px;border-radius:var(--radius-sm);
  font-size:14px;color:var(--ink-soft);cursor:pointer;
  border:1px solid transparent;
  background:none;text-align:left;width:100%;
  transition:background .15s ease, color .15s ease;
  position:relative;
}
.rail-item .num{font-family:var(--font-mono);font-size:11px;width:16px;color:var(--ink-soft);opacity:.6;}
.rail-item:hover{background:var(--surface-raised);color:var(--ink);}
.rail-item.active{color:var(--ink);background:var(--surface-raised);border-color:var(--line);}
.rail-item.active::before{
  content:"";position:absolute;left:-19px;top:8px;bottom:8px;width:3px;background:var(--accent);border-radius:2px;
}
.rail-foot{margin-top:auto;display:flex;flex-direction:column;gap:10px;padding-top:14px;border-top:1px solid var(--line);}
.streak-chip{
  display:flex;align-items:center;justify-content:space-between;
  padding:9px 10px;border:1px solid var(--line);border-radius:var(--radius-sm);
  font-size:12px;color:var(--ink-soft);
}
.streak-chip b{font-family:var(--font-mono);color:var(--ink);font-size:13px;}
.theme-toggle{
  display:flex;border:1px solid var(--line);border-radius:var(--radius-sm);overflow:hidden;
}
.theme-toggle button{
  flex:1;padding:7px 0;background:none;border:none;color:var(--ink-soft);font-size:12px;cursor:pointer;font-family:var(--font-mono);
}
.theme-toggle button.on{background:var(--accent-tint);color:var(--ink);}

main.stage{
  padding:34px 44px 80px;
  max-width:1180px;
  min-width:0;
}
.view{display:none;animation:fadein .3s ease;}
.view.active{display:block;}
@keyframes fadein{from{opacity:0;transform:translateY(4px);}to{opacity:1;transform:none;}}

/* ============ RESPONSIVE ============ */
@media(max-width:920px){
  .shell{grid-template-columns:1fr;}
  .rail{
    position:fixed;top:0;left:0;height:100vh;width:250px;z-index:45;
    background:var(--paper);transform:translateX(-100%);transition:transform .25s ease;
  }
  .rail.open{transform:translateX(0);}
  .topbar{display:flex;}
}
@media(max-width:640px){
  main.stage{padding:20px 18px 60px;}
  .hero h1{font-size:32px;}
  .ledger{grid-template-columns:repeat(2,1fr);}
  .two-col{gap:26px;}
  .editor-head{flex-direction:column;gap:12px;}
  .reviewer-row{grid-template-columns:1fr;}
  .row-actions{justify-content:flex-start;}
  .exam-main{padding:18px 20px;}
  .exam-question{font-size:21px;}
  .exam-side{
    position:fixed;top:0;right:0;height:100%;width:250px;z-index:60;
    transform:translateX(100%);transition:transform .25s ease;background:var(--paper);
  }
  .exam-side.open{transform:translateX(0);}
  .exam-topbar{flex-wrap:wrap;gap:10px;}
  .results-hero{gap:22px;}
  .score-big{font-size:60px;}
  #examNavToggle{display:inline-flex !important;}
}

/* ============ TYPOGRAPHY UTIL ============ */
.eyebrow-meta{font-family:var(--font-mono);font-size:11px;color:var(--ink-soft);}
.hairline{border:none;border-top:1px solid var(--line);margin:22px 0;}
.section-head{display:flex;align-items:baseline;justify-content:space-between;gap:16px;margin-bottom:16px;}
.section-head h2{font-size:22px;}
.link-btn{background:none;border:none;color:var(--accent-strong);font-size:13px;cursor:pointer;padding:0;font-family:var(--font-ui);text-decoration:underline;text-underline-offset:3px;text-decoration-color:var(--line-strong);}
.link-btn:hover{text-decoration-color:var(--accent);}

/* ============ BUTTONS ============ */
.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:7px;
  padding:10px 16px;border-radius:var(--radius-sm);border:1px solid var(--line-strong);
  background:var(--surface);color:var(--ink);font-size:13.5px;cursor:pointer;font-weight:500;
  transition:transform .12s ease, background .15s ease, border-color .15s ease;
}
.btn:hover{background:var(--surface-raised);border-color:var(--ink-soft);}
.btn:active{transform:scale(.98);}
.btn-primary{background:var(--accent);border-color:var(--accent);color:#fff;}
.btn-primary:hover{background:var(--accent-strong);border-color:var(--accent-strong);}
.btn-ghost{border-color:transparent;background:none;}
.btn-ghost:hover{background:var(--surface-raised);border-color:var(--line);}
.btn-danger{color:var(--bad);}
.btn-sm{padding:6px 11px;font-size:12.5px;}
.btn-block{width:100%;}
.btn:disabled{opacity:.4;cursor:not-allowed;}

/* ============ HERO / OVERVIEW ============ */
.hero{padding:6px 0 30px;border-bottom:1px solid var(--line);margin-bottom:30px;}
.hero h1{font-size:44px;line-height:1.08;max-width:640px;font-weight:600;}
.hero .tagline{margin-top:12px;color:var(--ink-soft);font-size:15px;max-width:480px;}
.quick-actions{display:flex;gap:10px;margin-top:24px;flex-wrap:wrap;}

.ledger{display:grid;grid-template-columns:repeat(4,1fr);border-top:1px solid var(--line);border-left:1px solid var(--line);margin-bottom:34px;}
.ledger-cell{border-right:1px solid var(--line);border-bottom:1px solid var(--line);padding:16px 18px;}
.ledger-cell .num{font-family:var(--font-mono);font-size:28px;font-weight:600;}
.ledger-cell .lbl{font-size:12px;color:var(--ink-soft);margin-top:4px;}

.two-col{display:grid;grid-template-columns:1.3fr 1fr;gap:36px;align-items:start;}
@media(max-width:920px){.two-col{grid-template-columns:1fr;}}

.continue-card{
  border:1px solid var(--line);border-radius:var(--radius);padding:20px 22px;background:var(--surface);box-shadow:var(--shadow-card);
}
.continue-card .subj{font-family:var(--font-mono);font-size:11px;color:var(--accent-strong);text-transform:none;}
.continue-card h3{font-size:19px;margin-top:6px;}
.progress-track{height:5px;border-radius:3px;background:var(--paper-dim);margin-top:14px;overflow:hidden;border:1px solid var(--line);}
.progress-fill{height:100%;background:var(--accent);border-radius:3px;transition:width .4s ease;}
.continue-card .meta-row{display:flex;justify-content:space-between;font-size:12px;color:var(--ink-soft);margin-top:8px;}

.shelf{display:flex;flex-direction:column;}
.shelf-row{
  display:flex;align-items:center;justify-content:space-between;gap:12px;
  padding:13px 4px;border-bottom:1px solid var(--line);cursor:pointer;
}
.shelf-row:hover .shelf-title{color:var(--accent-strong);}
.shelf-title{font-family:var(--font-display);font-size:17px;font-weight:500;}
.shelf-count{font-family:var(--font-mono);font-size:11px;color:var(--ink-soft);white-space:nowrap;}

.activity-list{display:flex;flex-direction:column;gap:0;}
.activity-row{display:flex;gap:12px;padding:11px 0;border-bottom:1px solid var(--line);font-size:13px;}
.activity-row .dot{width:6px;height:6px;border-radius:50%;background:var(--accent);margin-top:6px;flex-shrink:0;}
.activity-row .t{color:var(--ink-soft);font-family:var(--font-mono);font-size:11px;}

.empty-state{
  border:1px dashed var(--line-strong);border-radius:var(--radius);padding:36px 24px;text-align:center;color:var(--ink-soft);
}
.empty-state h4{color:var(--ink);font-size:16px;margin-bottom:6px;}
.empty-state p{font-size:13px;margin-bottom:16px;}

/* ============ REVIEWER LIST ============ */
.toolbar{display:flex;gap:10px;margin-bottom:20px;align-items:center;flex-wrap:wrap;}
.search-input, .select-input, .text-input, textarea.text-input{
  background:var(--surface);border:1px solid var(--line-strong);border-radius:var(--radius-sm);
  padding:9px 12px;font-size:13.5px;color:var(--ink);font-family:var(--font-ui);outline:none;
}
.search-input{flex:1;min-width:180px;}
.search-input:focus, .select-input:focus, .text-input:focus, textarea.text-input:focus{border-color:var(--accent);}
.reviewer-table{border-top:1px solid var(--line);}
.reviewer-row{
  display:grid;grid-template-columns:1fr auto auto auto;gap:18px;align-items:center;
  padding:16px 4px;border-bottom:1px solid var(--line);
}
.reviewer-row .rt{
  font-family:var(--font-display);font-size:18px;font-weight:500;
}
.reviewer-row .rs{font-family:var(--font-mono);font-size:11px;color:var(--accent-strong);display:block;margin-bottom:3px;}
.reviewer-row .rmeta{font-size:12px;color:var(--ink-soft);margin-top:3px;}
.row-actions{display:flex;gap:6px;}
.icon-btn{
  background:none;border:1px solid var(--line);border-radius:var(--radius-sm);width:30px;height:30px;
  display:flex;align-items:center;justify-content:center;cursor:pointer;color:var(--ink-soft);
}
.icon-btn:hover{color:var(--ink);border-color:var(--ink-soft);}

/* ============ EDITOR ============ */
.editor-head{display:flex;gap:18px;margin-bottom:24px;}
.editor-head .field{flex:1;}
.field label{display:block;font-size:11px;font-family:var(--font-mono);color:var(--ink-soft);margin-bottom:6px;}
.field .text-input, .field .select-input{width:100%;}
.field textarea.text-input{width:100%;resize:vertical;min-height:64px;font-family:var(--font-ui);line-height:1.5;}

.q-editor-panel{
  display:grid;grid-template-columns:1fr 360px;gap:28px;align-items:start;
}
@media(max-width:980px){.q-editor-panel{grid-template-columns:1fr;}}
.q-list{display:flex;flex-direction:column;gap:10px;}
.q-item{
  border:1px solid var(--line);border-radius:var(--radius);padding:14px 16px;background:var(--surface);
}
.q-item-head{display:flex;justify-content:space-between;align-items:flex-start;gap:10px;}
.q-item-head .qtype{font-family:var(--font-mono);font-size:10.5px;color:var(--accent-strong);}
.q-item-head .qtext{font-size:14.5px;margin-top:4px;line-height:1.45;}
.q-item-actions{display:flex;gap:5px;flex-shrink:0;}
.q-item-answers{margin-top:9px;font-size:12.5px;color:var(--ink-soft);}
.q-item-answers .correct{color:var(--good);}

.builder-form{
  border:1px solid var(--line);border-radius:var(--radius);padding:18px;background:var(--surface-raised);
  position:sticky;top:20px;
}
.builder-form h4{font-size:14px;margin-bottom:14px;}
.builder-form .field{margin-bottom:12px;}
.opt-row{display:flex;gap:8px;align-items:center;margin-bottom:8px;}
.opt-row input[type=text]{flex:1;}
.opt-row input[type=radio],.opt-row input[type=checkbox]{accent-color:var(--accent);width:16px;height:16px;}

/* ============ QUIZ MODE ============ */
.exam-shell{position:fixed;inset:0;background:var(--paper);z-index:50;display:flex;overflow:hidden;}
.exam-shell.hidden{display:none;}
.exam-main{flex:1;display:flex;flex-direction:column;padding:26px 50px;overflow-y:auto;}
.exam-topbar{display:flex;justify-content:space-between;align-items:center;margin-bottom:28px;}
.exam-topbar .exit{font-size:13px;color:var(--ink-soft);cursor:pointer;background:none;border:none;}
.exam-timer{font-family:var(--font-mono);font-size:20px;letter-spacing:.02em;padding:6px 14px;border:1px solid var(--line-strong);border-radius:var(--radius-sm);}
.exam-timer.low{color:var(--bad);border-color:var(--bad);}
.exam-progress-line{height:3px;background:var(--paper-dim);border-radius:2px;margin-bottom:34px;overflow:hidden;}
.exam-progress-fill{height:100%;background:var(--accent);transition:width .3s ease;}
.exam-qmeta{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:14px;}
.exam-qnum{font-family:var(--font-mono);font-size:13px;color:var(--ink-soft);}
.exam-qtype{font-family:var(--font-mono);font-size:11px;color:var(--accent-strong);}
.exam-question{font-family:var(--font-display);font-size:27px;line-height:1.35;font-weight:500;max-width:720px;margin-bottom:30px;}
.exam-choices{display:flex;flex-direction:column;gap:10px;max-width:640px;}
.choice{
  display:flex;align-items:flex-start;gap:12px;padding:14px 16px;border:1px solid var(--line-strong);border-radius:var(--radius);
  cursor:pointer;font-size:15px;transition:border-color .15s ease, background .15s ease;
}
.choice:hover{border-color:var(--accent);}
.choice.selected{border-color:var(--accent);background:var(--accent-tint);}
.choice .letter{font-family:var(--font-mono);font-size:12px;color:var(--ink-soft);width:18px;flex-shrink:0;padding-top:1px;}
.choice.selected .letter{color:var(--accent-strong);}
.exam-freeform textarea, .exam-freeform input{
  max-width:640px;width:100%;padding:12px 14px;border:1px solid var(--line-strong);border-radius:var(--radius);
  background:var(--surface);color:var(--ink);font-size:15px;font-family:var(--font-ui);
}
.enum-row{display:flex;align-items:center;gap:10px;margin-bottom:8px;max-width:640px;}
.enum-row .idx{font-family:var(--font-mono);font-size:12px;color:var(--ink-soft);width:18px;}
.exam-bottombar{display:flex;justify-content:space-between;align-items:center;margin-top:auto;padding-top:26px;}
.exam-nav-btns{display:flex;gap:10px;}
.mark-toggle{display:flex;align-items:center;gap:7px;font-size:13px;color:var(--ink-soft);cursor:pointer;user-select:none;}
.mark-toggle input{accent-color:var(--mark);width:15px;height:15px;}

.exam-side{
  width:250px;border-left:1px solid var(--line);padding:26px 20px;overflow-y:auto;flex-shrink:0;
}
.exam-side h4{font-size:12px;font-family:var(--font-mono);color:var(--ink-soft);margin-bottom:14px;font-weight:500;}
.qnav-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:6px;}
.qnav-cell{
  aspect-ratio:1;border:1px solid var(--line-strong);border-radius:5px;display:flex;align-items:center;justify-content:center;
  font-family:var(--font-mono);font-size:11.5px;cursor:pointer;color:var(--ink-soft);background:var(--surface);
}
.qnav-cell.answered{background:var(--accent-tint);border-color:var(--accent);color:var(--ink);}
.qnav-cell.marked{border-color:var(--mark);}
.qnav-cell.marked::after{content:"";}
.qnav-cell.current{outline:2px solid var(--ink);outline-offset:1px;}
.qnav-legend{margin-top:16px;display:flex;flex-direction:column;gap:6px;font-size:11.5px;color:var(--ink-soft);}
.qnav-legend span.sw{display:inline-block;width:10px;height:10px;border-radius:2px;margin-right:6px;vertical-align:-1px;border:1px solid var(--line-strong);}

/* ============ RESULTS ============ */
.results-hero{display:flex;gap:40px;align-items:flex-end;border-bottom:1px solid var(--line);padding-bottom:26px;margin-bottom:26px;flex-wrap:wrap;}
.score-big{font-family:var(--font-display);font-size:84px;font-weight:600;line-height:1;}
.score-big small{font-size:28px;font-weight:400;color:var(--ink-soft);}
.results-stats{display:flex;gap:28px;flex-wrap:wrap;}
.results-stats .rs-item .num{font-family:var(--font-mono);font-size:20px;}
.results-stats .rs-item .lbl{font-size:11px;color:var(--ink-soft);}
.topic-bar-row{display:flex;align-items:center;gap:12px;margin-bottom:10px;}
.topic-bar-row .tname{width:150px;font-size:13px;flex-shrink:0;}
.topic-bar-track{flex:1;height:8px;background:var(--paper-dim);border-radius:4px;overflow:hidden;border:1px solid var(--line);}
.topic-bar-fill{height:100%;background:var(--accent);}
.topic-bar-row .tpct{font-family:var(--font-mono);font-size:12px;width:40px;text-align:right;color:var(--ink-soft);}
.review-item{border:1px solid var(--line);border-radius:var(--radius);padding:16px 18px;margin-bottom:10px;background:var(--surface);}
.review-item .qt{font-size:14.5px;margin-bottom:8px;}
.review-item .ans-line{font-size:13px;margin-bottom:3px;}
.review-item .ans-line b{font-weight:600;}
.review-item .ans-line.wrong{color:var(--bad);}
.review-item .ans-line.right{color:var(--good);}
.review-item .expl{font-size:12.5px;color:var(--ink-soft);margin-top:8px;padding-top:8px;border-top:1px dashed var(--line);}

/* ============ FLASHCARDS ============ */
.fc-wrap{display:flex;flex-direction:column;align-items:center;padding:30px 0;}
.fc-subject{font-family:var(--font-mono);font-size:11px;color:var(--accent-strong);margin-bottom:14px;}
.fc-card{
  width:100%;max-width:560px;height:320px;perspective:1400px;cursor:pointer;margin-bottom:22px;
}
.fc-inner{position:relative;width:100%;height:100%;transition:transform .5s cubic-bezier(.2,.8,.2,1);transform-style:preserve-3d;}
.fc-card.flipped .fc-inner{transform:rotateY(180deg);}
.fc-face{
  position:absolute;inset:0;backface-visibility:hidden;border:1px solid var(--line-strong);border-radius:14px;
  display:flex;align-items:center;justify-content:center;text-align:center;padding:36px;background:var(--surface);box-shadow:var(--shadow-card);
}
.fc-face .txt{font-family:var(--font-display);font-size:22px;line-height:1.4;font-weight:500;}
.fc-face.back{transform:rotateY(180deg);background:var(--surface-raised);}
.fc-face.back .txt{font-size:18px;font-family:var(--font-ui);font-weight:400;}
.fc-hint{font-size:11px;color:var(--ink-soft);position:absolute;bottom:14px;font-family:var(--font-mono);}
.fc-controls{display:flex;align-items:center;gap:16px;}
.fc-progress{font-family:var(--font-mono);font-size:12px;color:var(--ink-soft);}
.fc-master-row{margin-top:18px;}

/* ============ ERROR ARCHIVE ============ */
.err-item{border:1px solid var(--line);border-radius:var(--radius);padding:16px 18px;margin-bottom:12px;background:var(--surface);}
.err-item .qt{font-size:15px;margin-bottom:10px;font-family:var(--font-display);}
.err-item .subj{font-family:var(--font-mono);font-size:10.5px;color:var(--accent-strong);margin-bottom:6px;display:block;}
.err-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:10px;}
.err-box{border-radius:var(--radius-sm);padding:10px 12px;font-size:13px;}
.err-box.wrong{background:var(--bad-tint);color:var(--bad);}
.err-box.right{background:var(--good-tint);color:var(--good);}
.err-box .k{font-size:10px;font-family:var(--font-mono);display:block;margin-bottom:3px;opacity:.8;}

/* ============ SETTINGS ============ */
.settings-group{border:1px solid var(--line);border-radius:var(--radius);padding:20px 22px;margin-bottom:16px;background:var(--surface);}
.settings-group h4{font-size:14px;margin-bottom:14px;}
.settings-row{display:flex;justify-content:space-between;align-items:center;padding:10px 0;border-bottom:1px solid var(--line);}
.settings-row:last-child{border-bottom:none;}
.settings-row .lbl{font-size:13.5px;}
.settings-row .desc{font-size:12px;color:var(--ink-soft);margin-top:2px;}

/* toast */
.toast{
  position:fixed;bottom:22px;left:50%;transform:translateX(-50%) translateY(20px);
  background:var(--ink);color:var(--paper);padding:11px 20px;border-radius:var(--radius-sm);font-size:13px;
  opacity:0;pointer-events:none;transition:all .25s ease;z-index:200;font-family:var(--font-ui);
}
html[data-theme="dark"] .toast{background:var(--surface-raised);color:var(--ink);border:1px solid var(--line-strong);}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0);}

.subject-tag{
  display:inline-block;font-family:var(--font-mono);font-size:10.5px;padding:3px 8px;border-radius:20px;
  border:1px solid var(--line-strong);color:var(--ink-soft);
}
</style>
</head>
<body>
<div class="scrim-grid"></div>
<div class="topbar">
  <span class="mark">Examora</span>
  <button class="menu-btn" id="menuBtn" aria-label="Open menu"><span></span><span></span><span></span></button>
</div>
<div class="rail-overlay" id="railOverlay"></div>
<div class="shell">
  <aside class="rail" id="railAside">
    <div class="rail-brand">
      <span class="mark">Examora</span>
      <span class="sub">v1.0</span>
    </div>
    <div class="rail-index-label">Index</div>
    <nav class="rail-nav" id="railNav"></nav>
    <div class="rail-foot">
      <div class="streak-chip"><span>Study streak</span><b id="streakChip">0 days</b></div>
      <div class="theme-toggle">
        <button id="btnLight">Light</button>
        <button id="btnDark">Dark</button>
      </div>
    </div>
  </aside>
  <main class="stage" id="stage"></main>
</div>

<div class="exam-shell hidden" id="examShell">
  <div class="exam-main">
    <div class="exam-topbar">
      <button class="exit" id="examExit">&larr; Exit exam</button>
      <div style="display:flex;align-items:center;gap:10px;">
        <div class="exam-timer" id="examTimer" style="display:none;">--:--</div>
        <button class="btn btn-sm" id="examNavToggle" style="display:none;">Questions</button>
      </div>
    </div>
    <div class="exam-progress-line"><div class="exam-progress-fill" id="examProgressFill"></div></div>
    <div class="exam-qmeta">
      <span class="exam-qnum" id="examQNum">Question 1 of 10</span>
      <span class="exam-qtype" id="examQType">Multiple Choice</span>
    </div>
    <div class="exam-question" id="examQuestion"></div>
    <div id="examAnswerArea"></div>
    <div class="exam-bottombar">
      <label class="mark-toggle"><input type="checkbox" id="markReview"> Mark for review</label>
      <div class="exam-nav-btns">
        <button class="btn" id="examPrev">Previous</button>
        <button class="btn" id="examNext">Next</button>
        <button class="btn btn-primary" id="examSubmit" style="display:none;">Submit exam</button>
      </div>
    </div>
  </div>
  <div class="exam-side" id="examSide">
    <h4>Question navigator</h4>
    <div class="qnav-grid" id="qnavGrid"></div>
    <div class="qnav-legend">
      <div><span class="sw" style="background:var(--accent-tint);border-color:var(--accent);"></span>Answered</div>
      <div><span class="sw" style="border-color:var(--mark);"></span>Marked for review</div>
      <div><span class="sw"></span>Unanswered</div>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ============================================================
   STATE
   ============================================================ */
const STORAGE_KEY = 'examora_state_v1';
const QTYPES = {
  mcq: 'Multiple Choice',
  tf: 'True or False',
  id: 'Identification',
  enum: 'Enumeration'
};

function uid(){ return 'id_' + Math.random().toString(36).slice(2,10) + Date.now().toString(36); }

function defaultState(){
  return {
    reviewers: [],
    errorArchive: [],   // {id, questionText, type, subject, reviewerId, yourAnswer, correctAnswer, explanation, ts}
    activity: [],        // {ts, text}
    theme: 'dark',
    lastReviewerId: null,
    streak: {count:0, lastDate:null},
    mockDuration: 15 // minutes default
  };
}

let state = load();

function load(){
  try{
    const raw = localStorage.getItem(STORAGE_KEY);
    if(!raw) return defaultState();
    const parsed = JSON.parse(raw);
    return Object.assign(defaultState(), parsed);
  }catch(e){ return defaultState(); }
}
function persist(){
  try{ localStorage.setItem(STORAGE_KEY, JSON.stringify(state)); }catch(e){}
}
function logActivity(text){
  state.activity.unshift({ts:Date.now(), text});
  state.activity = state.activity.slice(0,30);
}
function bumpStreak(){
  const today = new Date().toDateString();
  if(state.streak.lastDate === today) return;
  const yesterday = new Date(Date.now()-86400000).toDateString();
  if(state.streak.lastDate === yesterday){ state.streak.count += 1; }
  else { state.streak.count = 1; }
  state.streak.lastDate = today;
}

/* ============================================================
   TOAST
   ============================================================ */
let toastTimer;
function toast(msg){
  const el = document.getElementById('toast');
  el.textContent = msg;
  el.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(()=>el.classList.remove('show'), 2400);
}

/* ============================================================
   THEME
   ============================================================ */
function applyTheme(){
  document.documentElement.setAttribute('data-theme', state.theme);
  document.getElementById('btnLight').classList.toggle('on', state.theme==='light');
  document.getElementById('btnDark').classList.toggle('on', state.theme==='dark');
}
document.getElementById('btnLight').addEventListener('click', ()=>{ state.theme='light'; persist(); applyTheme(); });
document.getElementById('btnDark').addEventListener('click', ()=>{ state.theme='dark'; persist(); applyTheme(); });

/* ============================================================
   MOBILE NAV DRAWER
   ============================================================ */
const railAside = document.getElementById('railAside');
const railOverlay = document.getElementById('railOverlay');
function openRail(){ railAside.classList.add('open'); railOverlay.classList.add('show'); }
function closeRail(){ railAside.classList.remove('open'); railOverlay.classList.remove('show'); }
document.getElementById('menuBtn').addEventListener('click', openRail);
railOverlay.addEventListener('click', closeRail);

/* Mobile toggle for the in-exam question navigator */
const examSideEl = document.getElementById('examSide');
document.getElementById('examNavToggle').addEventListener('click', ()=>{
  examSideEl.classList.toggle('open');
});

/* ============================================================
   NAV / ROUTING
   ============================================================ */
const NAV_ITEMS = [
  {id:'overview', label:'Overview'},
  {id:'reviewers', label:'My Reviewers'},
  {id:'practice', label:'Practice'},
  {id:'mock', label:'Mock Exams'},
  {id:'flashcards', label:'Flashcards'},
  {id:'errors', label:'Error Archive'},
  {id:'progress', label:'Progress'},
  {id:'settings', label:'Settings'},
];
let currentView = 'overview';

function buildRail(){
  const nav = document.getElementById('railNav');
  nav.innerHTML = '';
  NAV_ITEMS.forEach((item,i)=>{
    const b = document.createElement('button');
    b.className = 'rail-item' + (item.id===currentView ? ' active':'');
    b.innerHTML = `<span class="num">${String(i+1).padStart(2,'0')}</span><span>${item.label}</span>`;
    b.addEventListener('click', ()=>navigate(item.id));
    nav.appendChild(b);
  });
  document.getElementById('streakChip').textContent = state.streak.count + (state.streak.count===1?' day':' days');
}

function navigate(viewId, params){
  currentView = viewId;
  buildRail();
  render(viewId, params||{});
  window.scrollTo(0,0);
  closeRail();
}

function render(viewId, params){
  const stage = document.getElementById('stage');
  stage.innerHTML = '';
  const renderers = {
    overview: renderOverview,
    reviewers: renderReviewers,
    editor: renderEditor,
    practice: renderPracticeSelect,
    mock: renderMockSelect,
    flashcards: renderFlashcardsSelect,
    errors: renderErrors,
    progress: renderProgress,
    settings: renderSettings,
    results: renderResultsView,
  };
  (renderers[viewId] || renderOverview)(stage, params);
}

/* ============================================================
   HELPERS
   ============================================================ */
function el(tag, cls, html){
  const e = document.createElement(tag);
  if(cls) e.className = cls;
  if(html!==undefined) e.innerHTML = html;
  return e;
}
function subjects(){
  const s = {};
  state.reviewers.forEach(r=>{ s[r.subject] = (s[r.subject]||0) + r.questions.length; });
  return s;
}
function totalQuestions(){ return state.reviewers.reduce((a,r)=>a+r.questions.length,0); }
function findReviewer(id){ return state.reviewers.find(r=>r.id===id); }
function timeAgo(ts){
  const diff = Date.now()-ts;
  const m = Math.floor(diff/60000);
  if(m<1) return 'just now';
  if(m<60) return m+'m ago';
  const h = Math.floor(m/60);
  if(h<24) return h+'h ago';
  const d = Math.floor(h/24);
  return d+'d ago';
}
function escapeHtml(s){
  return (s||'').replace(/[&<>"']/g, c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
}

/* ============================================================
   OVERVIEW
   ============================================================ */
function renderOverview(stage){
  const hero = el('div','hero');
  hero.innerHTML = `
    <h1>Build your knowledge.<br>Test your limits.</h1>
    <p class="tagline">Examora is your personal study laboratory — build reviewers, run mock exams, and close every gap you find.</p>
    <div class="quick-actions">
      <button class="btn btn-primary" id="qaCreate">Create Reviewer</button>
      <button class="btn" id="qaPractice">Start Practice</button>
      <button class="btn" id="qaMock">Mock Exam</button>
      <button class="btn" id="qaFlash">Flashcards</button>
    </div>
  `;
  stage.appendChild(hero);

  const stats = computeStats();
  const ledger = el('div','ledger');
  ledger.innerHTML = `
    <div class="ledger-cell"><div class="num">${stats.answered}</div><div class="lbl">Questions Answered</div></div>
    <div class="ledger-cell"><div class="num">${stats.accuracy}%</div><div class="lbl">Accuracy</div></div>
    <div class="ledger-cell"><div class="num">${state.streak.count}</div><div class="lbl">Study Streak (days)</div></div>
    <div class="ledger-cell"><div class="num">${stats.completed}</div><div class="lbl">Completed Reviewers</div></div>
  `;
  stage.appendChild(ledger);

  const two = el('div','two-col');

  // left: continue + shelf
  const left = el('div');
  const head1 = el('div','section-head'); head1.innerHTML = `<h2>Continue studying</h2>`;
  left.appendChild(head1);

  const lastR = findReviewer(state.lastReviewerId) || state.reviewers[0];
  if(lastR){
    const done = lastR.attempts && lastR.attempts.length ? Math.max(...lastR.attempts.map(a=>a.pct)) : 0;
    const card = el('div','continue-card');
    card.innerHTML = `
      <span class="subj">${escapeHtml(lastR.subject)}</span>
      <h3>${escapeHtml(lastR.title)}</h3>
      <div class="progress-track"><div class="progress-fill" style="width:${done}%"></div></div>
      <div class="meta-row"><span>${lastR.questions.length} questions</span><span>Best score ${done}%</span></div>
    `;
    card.style.cursor='pointer';
    card.addEventListener('click', ()=>startQuiz(lastR.id,'practice'));
    left.appendChild(card);
  } else {
    left.appendChild(emptyState('No reviewers yet','Create your first reviewer to begin building your personal exam bank.','Create Reviewer', ()=>navigate('editor')));
  }

  const head2 = el('div','section-head'); head2.style.marginTop='34px';
  head2.innerHTML = `<h2>Subject index</h2><button class="link-btn" id="seeAllReviewers">See all reviewers</button>`;
  left.appendChild(head2);
  const shelf = el('div','shelf');
  const subj = subjects();
  const subjEntries = Object.entries(subj);
  if(subjEntries.length===0){
    shelf.appendChild(emptyState('Your bookshelf is empty','Subjects appear here as you create reviewers.'));
  } else {
    subjEntries.forEach(([name,count])=>{
      const row = el('div','shelf-row');
      row.innerHTML = `<span class="shelf-title">${escapeHtml(name)}</span><span class="shelf-count">${count} item${count===1?'':'s'}</span>`;
      row.addEventListener('click', ()=>navigate('reviewers',{subjectFilter:name}));
      shelf.appendChild(row);
    });
  }
  left.appendChild(shelf);
  two.appendChild(left);

  // right: recent activity
  const right = el('div');
  const head3 = el('div','section-head'); head3.innerHTML = `<h2>Recent activity</h2>`;
  right.appendChild(head3);
  const actList = el('div','activity-list');
  if(state.activity.length===0){
    actList.appendChild(emptyState('Nothing yet','Your study sessions will be logged here.'));
  } else {
    state.activity.slice(0,10).forEach(a=>{
      const row = el('div','activity-row');
      row.innerHTML = `<span class="dot"></span><div><div>${escapeHtml(a.text)}</div><div class="t">${timeAgo(a.ts)}</div></div>`;
      actList.appendChild(row);
    });
  }
  right.appendChild(actList);
  two.appendChild(right);

  stage.appendChild(two);

  document.getElementById('qaCreate').addEventListener('click', ()=>navigate('editor'));
  document.getElementById('qaPractice').addEventListener('click', ()=>navigate('practice'));
  document.getElementById('qaMock').addEventListener('click', ()=>navigate('mock'));
  document.getElementById('qaFlash').addEventListener('click', ()=>navigate('flashcards'));
  const seeAll = document.getElementById('seeAllReviewers');
  if(seeAll) seeAll.addEventListener('click', ()=>navigate('reviewers'));
}

function emptyState(title, desc, btnLabel, onClick){
  const e = el('div','empty-state');
  e.innerHTML = `<h4>${escapeHtml(title)}</h4><p>${escapeHtml(desc)}</p>`;
  if(btnLabel){
    const b = el('button','btn btn-primary', escapeHtml(btnLabel));
    b.addEventListener('click', onClick);
    e.appendChild(b);
  }
  return e;
}

function computeStats(){
  let answered=0, correct=0, completed=0;
  state.reviewers.forEach(r=>{
    (r.attempts||[]).forEach(a=>{
      answered += a.total;
      correct += a.correct;
    });
    if(r.attempts && r.attempts.length) completed++;
  });
  const accuracy = answered ? Math.round((correct/answered)*100) : 0;
  return {answered, accuracy, completed};
}

/* ============================================================
   REVIEWERS LIST
   ============================================================ */
function renderReviewers(stage, params){
  const head = el('div','section-head');
  head.innerHTML = `<h2>My Reviewers</h2>`;
  const btn = el('button','btn btn-primary','Create Reviewer');
  btn.addEventListener('click', ()=>navigate('editor'));
  head.appendChild(btn);
  stage.appendChild(head);

  const toolbar = el('div','toolbar');
  const search = el('input','search-input');
  search.placeholder = 'Search reviewers by title or subject…';
  search.value = params.subjectFilter || '';
  toolbar.appendChild(search);
  const filterSel = el('select','select-input');
  filterSel.innerHTML = `<option value="">All subjects</option>` + Object.keys(subjects()).map(s=>`<option ${s===params.subjectFilter?'selected':''}>${escapeHtml(s)}</option>`).join('');
  toolbar.appendChild(filterSel);
  stage.appendChild(toolbar);

  const table = el('div','reviewer-table');
  stage.appendChild(table);

  function renderList(){
    table.innerHTML = '';
    const q = search.value.trim().toLowerCase();
    const subjF = filterSel.value;
    const list = state.reviewers.filter(r=>{
      const matchQ = !q || r.title.toLowerCase().includes(q) || r.subject.toLowerCase().includes(q);
      const matchS = !subjF || r.subject===subjF;
      return matchQ && matchS;
    });
    if(list.length===0){
      table.appendChild(emptyState('No reviewers found','Try a different search, or create a new reviewer.','Create Reviewer', ()=>navigate('editor')));
      return;
    }
    list.forEach(r=>{
      const row = el('div','reviewer-row');
      const best = (r.attempts&&r.attempts.length) ? Math.max(...r.attempts.map(a=>a.pct))+'%' : '—';
      row.innerHTML = `
        <div>
          <span class="rs">${escapeHtml(r.subject)}</span>
          <span class="rt">${escapeHtml(r.title)}</span>
          <div class="rmeta">${r.questions.length} questions · Best score ${best}</div>
        </div>
      `;
      const actions = el('div','row-actions');
      const bPractice = iconBtn('&#9654;','Practice'); bPractice.addEventListener('click', ()=>startQuiz(r.id,'practice'));
      const bEdit = iconBtn('&#9998;','Edit'); bEdit.addEventListener('click', ()=>navigate('editor',{id:r.id}));
      const bDup = iconBtn('&#8862;','Duplicate'); bDup.addEventListener('click', ()=>{ duplicateReviewer(r.id); renderList(); });
      const bDel = iconBtn('&times;','Delete'); bDel.addEventListener('click', ()=>{ if(confirm('Delete "'+r.title+'"? This cannot be undone.')){ deleteReviewer(r.id); renderList(); } });
      actions.appendChild(bPractice); actions.appendChild(bEdit); actions.appendChild(bDup); actions.appendChild(bDel);
      row.appendChild(actions);
      table.appendChild(row);
    });
  }
  search.addEventListener('input', renderList);
  filterSel.addEventListener('change', renderList);
  renderList();
}
function iconBtn(html, title){
  const b = el('button','icon-btn', html);
  b.title = title;
  return b;
}
function duplicateReviewer(id){
  const r = findReviewer(id);
  if(!r) return;
  const copy = JSON.parse(JSON.stringify(r));
  copy.id = uid();
  copy.title = r.title + ' (copy)';
  copy.attempts = [];
  copy.questions.forEach(q=>q.id=uid());
  state.reviewers.push(copy);
  persist();
  toast('Reviewer duplicated');
}
function deleteReviewer(id){
  state.reviewers = state.reviewers.filter(r=>r.id!==id);
  persist();
  toast('Reviewer deleted');
}

/* ============================================================
   EDITOR
   ============================================================ */
function renderEditor(stage, params){
  let reviewer = params.id ? findReviewer(params.id) : null;
  const isNew = !reviewer;
  if(isNew){
    reviewer = { id: uid(), title:'', subject:'', questions:[], attempts:[], created:Date.now() };
  }
  // work on a draft copy, commit on save
  const draft = JSON.parse(JSON.stringify(reviewer));

  const head = el('div','section-head');
  head.innerHTML = `<h2>${isNew?'Create reviewer':'Edit reviewer'}</h2>`;
  stage.appendChild(head);

  const headFields = el('div','editor-head');
  headFields.innerHTML = `
    <div class="field"><label>Reviewer title</label><input class="text-input" id="fTitle" placeholder="e.g. Cell Biology Midterm" value="${escapeHtml(draft.title)}"></div>
    <div class="field"><label>Subject</label><input class="text-input" id="fSubject" placeholder="e.g. Biology" value="${escapeHtml(draft.subject)}"></div>
  `;
  stage.appendChild(headFields);

  const panel = el('div','q-editor-panel');
  const qListWrap = el('div');
  const qListHead = el('div','section-head'); qListHead.style.marginBottom='10px';
  qListHead.innerHTML = `<h2 style="font-size:16px;">Questions (<span id="qCount">${draft.questions.length}</span>)</h2>`;
  qListWrap.appendChild(qListHead);
  const qList = el('div','q-list');
  qListWrap.appendChild(qList);
  panel.appendChild(qListWrap);

  const formWrap = el('div','builder-form');
  panel.appendChild(formWrap);
  stage.appendChild(panel);

  const footer = el('div');
  footer.style.cssText='display:flex;gap:10px;margin-top:26px;';
  const saveBtn = el('button','btn btn-primary','Save reviewer');
  const cancelBtn = el('button','btn','Cancel');
  footer.appendChild(saveBtn); footer.appendChild(cancelBtn);
  stage.appendChild(footer);

  function renderQList(){
    qList.innerHTML='';
    document.getElementById('qCount').textContent = draft.questions.length;
    if(draft.questions.length===0){
      qList.appendChild(emptyState('No questions yet','Use the form on the right to add your first question.'));
      return;
    }
    draft.questions.forEach((q,i)=>{
      const item = el('div','q-item');
      let answerSummary = '';
      if(q.type==='mcq'){
        answerSummary = q.options.map((o,oi)=>`<span class="${oi===q.correctIndex?'correct':''}">${oi===q.correctIndex?'✓ ':''}${escapeHtml(o)}</span>`).join(' · ');
      } else if(q.type==='tf'){
        answerSummary = `<span class="correct">${q.correctBool ? 'True':'False'}</span>`;
      } else if(q.type==='id'){
        answerSummary = `<span class="correct">${escapeHtml(q.answer)}</span>`;
      } else if(q.type==='enum'){
        answerSummary = (q.answers||[]).map(a=>`<span class="correct">${escapeHtml(a)}</span>`).join(' · ');
      }
      item.innerHTML = `
        <div class="q-item-head">
          <div>
            <span class="qtype">${QTYPES[q.type]}</span>
            <div class="qtext">${i+1}. ${escapeHtml(q.text)}</div>
          </div>
        </div>
        <div class="q-item-answers">${answerSummary}</div>
      `;
      const actions = el('div','q-item-actions');
      const up = iconBtn('&#8593;','Move up'); up.addEventListener('click',()=>{ if(i>0){ [draft.questions[i-1],draft.questions[i]]=[draft.questions[i],draft.questions[i-1]]; renderQList(); } });
      const down = iconBtn('&#8595;','Move down'); down.addEventListener('click',()=>{ if(i<draft.questions.length-1){ [draft.questions[i+1],draft.questions[i]]=[draft.questions[i],draft.questions[i+1]]; renderQList(); } });
      const dup = iconBtn('&#8862;','Duplicate'); dup.addEventListener('click',()=>{ const c=JSON.parse(JSON.stringify(q)); c.id=uid(); draft.questions.splice(i+1,0,c); renderQList(); });
      const del = iconBtn('&times;','Delete'); del.addEventListener('click',()=>{ draft.questions.splice(i,1); renderQList(); });
      actions.appendChild(up); actions.appendChild(down); actions.appendChild(dup); actions.appendChild(del);
      item.querySelector('.q-item-head').appendChild(actions);
      qList.appendChild(item);
    });
  }

  function renderForm(){
    formWrap.innerHTML = `<h4>Add a question</h4>`;
    const typeField = el('div','field');
    typeField.innerHTML = `<label>Question type</label>
      <select class="select-input" id="newQType" style="width:100%;">
        <option value="mcq">Multiple Choice</option>
        <option value="tf">True or False</option>
        <option value="id">Identification</option>
        <option value="enum">Enumeration</option>
      </select>`;
    formWrap.appendChild(typeField);

    const textField = el('div','field');
    textField.innerHTML = `<label>Question text</label><textarea class="text-input" id="newQText" placeholder="Type the question…"></textarea>`;
    formWrap.appendChild(textField);

    const dynamicArea = el('div','field'); dynamicArea.id='dynamicArea';
    formWrap.appendChild(dynamicArea);

    const explField = el('div','field');
    explField.innerHTML = `<label>Explanation (optional)</label><textarea class="text-input" id="newQExpl" placeholder="Why is this the correct answer?"></textarea>`;
    formWrap.appendChild(explField);

    const addBtn = el('button','btn btn-primary btn-block','Add question');
    formWrap.appendChild(addBtn);

    const typeSel = document.getElementById('newQType');
    function renderDynamic(){
      const t = typeSel.value;
      const area = document.getElementById('dynamicArea');
      if(t==='mcq'){
        area.innerHTML = `<label>Options (select the correct one)</label>` +
          [0,1,2,3].map(i=>`
            <div class="opt-row">
              <input type="radio" name="correctOpt" value="${i}" ${i===0?'checked':''}>
              <input type="text" class="text-input" id="opt${i}" placeholder="Option ${String.fromCharCode(65+i)}">
            </div>`).join('');
      } else if(t==='tf'){
        area.innerHTML = `<label>Correct answer</label>
          <div class="opt-row"><input type="radio" name="tfVal" value="true" checked> True</div>
          <div class="opt-row"><input type="radio" name="tfVal" value="false"> False</div>`;
      } else if(t==='id'){
        area.innerHTML = `<label>Correct answer</label><input type="text" class="text-input" id="idAnswer" style="width:100%;" placeholder="e.g. Mitochondria">`;
      } else if(t==='enum'){
        area.innerHTML = `<label>Correct answers (one per line)</label><textarea class="text-input" id="enumAnswers" style="width:100%;" placeholder="Answer 1&#10;Answer 2&#10;Answer 3"></textarea>`;
      }
    }
    typeSel.addEventListener('change', renderDynamic);
    renderDynamic();

    addBtn.addEventListener('click', ()=>{
      const text = document.getElementById('newQText').value.trim();
      if(!text){ toast('Enter a question first'); return; }
      const t = typeSel.value;
      const expl = document.getElementById('newQExpl').value.trim();
      let q = { id: uid(), type:t, text, explanation:expl };
      if(t==='mcq'){
        const opts = [0,1,2,3].map(i=>document.getElementById('opt'+i).value.trim());
        if(opts.some(o=>!o)){ toast('Fill in all four options'); return; }
        const correctIndex = parseInt(document.querySelector('input[name=correctOpt]:checked').value,10);
        q.options = opts; q.correctIndex = correctIndex;
      } else if(t==='tf'){
        q.correctBool = document.querySelector('input[name=tfVal]:checked').value==='true';
      } else if(t==='id'){
        const ans = document.getElementById('idAnswer').value.trim();
        if(!ans){ toast('Enter the correct answer'); return; }
        q.answer = ans;
      } else if(t==='enum'){
        const raw = document.getElementById('enumAnswers').value.trim();
        const answers = raw.split('\n').map(a=>a.trim()).filter(Boolean);
        if(answers.length===0){ toast('Enter at least one answer'); return; }
        q.answers = answers;
      }
      draft.questions.push(q);
      renderQList();
      renderForm();
      toast('Question added');
    });
  }

  renderQList();
  renderForm();

  saveBtn.addEventListener('click', ()=>{
    const title = document.getElementById('fTitle').value.trim();
    const subject = document.getElementById('fSubject').value.trim();
    if(!title || !subject){ toast('Add a title and subject'); return; }
    if(draft.questions.length===0){ toast('Add at least one question'); return; }
    draft.title = title; draft.subject = subject;
    if(isNew){
      state.reviewers.push(draft);
      logActivity(`Created reviewer "${title}"`);
    } else {
      const idx = state.reviewers.findIndex(r=>r.id===draft.id);
      draft.attempts = reviewer.attempts || [];
      state.reviewers[idx] = draft;
      logActivity(`Updated reviewer "${title}"`);
    }
    persist();
    toast('Reviewer saved');
    navigate('reviewers');
  });
  cancelBtn.addEventListener('click', ()=>navigate('reviewers'));
}

/* ============================================================
   PRACTICE / MOCK SELECT SCREENS
   ============================================================ */
function renderPickerScreen(stage, title, desc, mode){
  const head = el('div','section-head');
  head.innerHTML = `<h2>${title}</h2>`;
  stage.appendChild(head);
  const p = el('p'); p.style.cssText='color:var(--ink-soft);font-size:14px;max-width:560px;margin-bottom:24px;';
  p.textContent = desc;
  stage.appendChild(p);

  if(mode==='mock'){
    const durField = el('div','field'); durField.style.cssText='max-width:220px;margin-bottom:22px;';
    durField.innerHTML = `<label>Exam duration (minutes)</label><input type="number" min="1" class="text-input" id="mockDur" style="width:100%;" value="${state.mockDuration}">`;
    stage.appendChild(durField);
    durField.querySelector('input').addEventListener('change', e=>{ state.mockDuration = Math.max(1, parseInt(e.target.value||15,10)); persist(); });
  }

  const table = el('div','reviewer-table');
  if(state.reviewers.length===0){
    table.appendChild(emptyState('No reviewers to study yet','Create a reviewer first — then come back here to start.','Create Reviewer', ()=>navigate('editor')));
  } else {
    state.reviewers.forEach(r=>{
      const row = el('div','reviewer-row');
      row.innerHTML = `
        <div>
          <span class="rs">${escapeHtml(r.subject)}</span>
          <span class="rt">${escapeHtml(r.title)}</span>
          <div class="rmeta">${r.questions.length} questions</div>
        </div>
      `;
      const actions = el('div','row-actions');
      const goBtn = el('button','btn btn-primary btn-sm', mode==='mock' ? 'Start mock exam':'Start practice');
      goBtn.addEventListener('click', ()=>startQuiz(r.id, mode));
      actions.appendChild(goBtn);
      row.appendChild(actions);
      table.appendChild(row);
    });
  }
  stage.appendChild(table);
}
function renderPracticeSelect(stage){
  renderPickerScreen(stage, 'Practice', 'Untimed, low-pressure review. Pick a reviewer to work through at your own pace.', 'practice');
}
function renderMockSelect(stage){
  renderPickerScreen(stage, 'Mock Exams', 'Simulate real exam conditions with a timer and no feedback until you submit.', 'mock');
}

/* ============================================================
   FLASHCARDS
   ============================================================ */
function renderFlashcardsSelect(stage){
  const head = el('div','section-head'); head.innerHTML=`<h2>Flashcards</h2>`;
  stage.appendChild(head);
  const p = el('p'); p.style.cssText='color:var(--ink-soft);font-size:14px;max-width:560px;margin-bottom:24px;';
  p.textContent = 'Flip through the questions and answers from any reviewer.';
  stage.appendChild(p);

  if(state.reviewers.length===0){
    stage.appendChild(emptyState('No reviewers yet','Create a reviewer to generate flashcards from its questions.','Create Reviewer', ()=>navigate('editor')));
    return;
  }
  const table = el('div','reviewer-table');
  state.reviewers.forEach(r=>{
    const row = el('div','reviewer-row');
    row.innerHTML = `
      <div>
        <span class="rs">${escapeHtml(r.subject)}</span>
        <span class="rt">${escapeHtml(r.title)}</span>
        <div class="rmeta">${r.questions.length} cards</div>
      </div>`;
    const actions = el('div','row-actions');
    const goBtn = el('button','btn btn-primary btn-sm','Study');
    goBtn.addEventListener('click', ()=>renderFlashcardSession(r.id));
    actions.appendChild(goBtn);
    row.appendChild(actions);
    table.appendChild(row);
  });
  stage.appendChild(table);
}
function questionAnswerText(q){
  if(q.type==='mcq') return q.options[q.correctIndex];
  if(q.type==='tf') return q.correctBool ? 'True':'False';
  if(q.type==='id') return q.answer;
  if(q.type==='enum') return (q.answers||[]).join(', ');
  return '';
}
function renderFlashcardSession(reviewerId){
  const r = findReviewer(reviewerId);
  if(!r) return;
  const stage = document.getElementById('stage');
  stage.innerHTML='';
  r.mastered = r.mastered || [];
  let idx = 0;

  const head = el('div','section-head');
  head.innerHTML = `<h2>${escapeHtml(r.title)}</h2>`;
  const backBtn = el('button','btn','Back to flashcards');
  backBtn.addEventListener('click', ()=>navigate('flashcards'));
  head.appendChild(backBtn);
  stage.appendChild(head);

  const wrap = el('div','fc-wrap');
  wrap.innerHTML = `
    <div class="fc-subject">${escapeHtml(r.subject)}</div>
    <div class="fc-card" id="fcCard">
      <div class="fc-inner">
        <div class="fc-face front"><div class="txt" id="fcFront"></div><div class="fc-hint">Tap card to flip</div></div>
        <div class="fc-face back"><div class="txt" id="fcBack"></div></div>
      </div>
    </div>
    <div class="fc-controls">
      <button class="btn" id="fcPrev">Previous</button>
      <span class="fc-progress" id="fcProgress"></span>
      <button class="btn" id="fcNext">Next</button>
    </div>
    <div class="fc-master-row">
      <button class="btn btn-sm" id="fcMaster">Mark as mastered</button>
    </div>
  `;
  stage.appendChild(wrap);

  const cardEl = wrap.querySelector('#fcCard');
  function draw(){
    const q = r.questions[idx];
    cardEl.classList.remove('flipped');
    wrap.querySelector('#fcFront').textContent = q.text;
    wrap.querySelector('#fcBack').textContent = questionAnswerText(q);
    wrap.querySelector('#fcProgress').textContent = (idx+1)+' / '+r.questions.length;
    const mastered = r.mastered.includes(q.id);
    wrap.querySelector('#fcMaster').textContent = mastered ? 'Mastered ✓' : 'Mark as mastered';
  }
  cardEl.addEventListener('click', ()=>cardEl.classList.toggle('flipped'));
  wrap.querySelector('#fcPrev').addEventListener('click', ()=>{ idx = (idx-1+r.questions.length)%r.questions.length; draw(); });
  wrap.querySelector('#fcNext').addEventListener('click', ()=>{ idx = (idx+1)%r.questions.length; draw(); });
  wrap.querySelector('#fcMaster').addEventListener('click', ()=>{
    const q = r.questions[idx];
    const pos = r.mastered.indexOf(q.id);
    if(pos>-1) r.mastered.splice(pos,1); else r.mastered.push(q.id);
    persist();
    draw();
  });
  draw();
}

/* ============================================================
   QUIZ ENGINE (Practice + Mock Exam)
   ============================================================ */
let quiz = null; // active quiz session state
let timerInterval = null;

function startQuiz(reviewerId, mode){
  const r = findReviewer(reviewerId);
  if(!r || r.questions.length===0){ toast('This reviewer has no questions'); return; }
  state.lastReviewerId = reviewerId;
  persist();
  quiz = {
    reviewerId,
    mode, // 'practice' | 'mock'
    order: shuffle(r.questions.map((q,i)=>i)),
    responses: {}, // qIndex -> answer
    marked: {},
    current: 0,
    startTs: Date.now(),
    durationSec: mode==='mock' ? state.mockDuration*60 : null,
    remaining: mode==='mock' ? state.mockDuration*60 : null,
  };
  openExamShell();
  drawQuestion();
  buildQNav();
  if(mode==='mock'){
    document.getElementById('examTimer').style.display='block';
    startTimer();
  } else {
    document.getElementById('examTimer').style.display='none';
  }
}
function shuffle(arr){ const a=arr.slice(); for(let i=a.length-1;i>0;i--){ const j=Math.floor(Math.random()*(i+1)); [a[i],a[j]]=[a[j],a[i]]; } return a; }

function openExamShell(){
  document.getElementById('examShell').classList.remove('hidden');
  document.getElementById('examSide').classList.remove('open');
}
function closeExamShell(){
  document.getElementById('examShell').classList.add('hidden');
  clearInterval(timerInterval);
}
document.getElementById('examExit').addEventListener('click', ()=>{
  if(confirm('Exit this exam? Your progress will be lost.')){ closeExamShell(); quiz=null; }
});

function startTimer(){
  updateTimerDisplay();
  timerInterval = setInterval(()=>{
    quiz.remaining -= 1;
    updateTimerDisplay();
    if(quiz.remaining<=0){ clearInterval(timerInterval); submitExam(); }
  },1000);
}
function updateTimerDisplay(){
  const t = document.getElementById('examTimer');
  const m = Math.floor(quiz.remaining/60), s = quiz.remaining%60;
  t.textContent = String(m).padStart(2,'0')+':'+String(s).padStart(2,'0');
  t.classList.toggle('low', quiz.remaining <= 60);
}

function currentQuestion(){
  const r = findReviewer(quiz.reviewerId);
  const qIndex = quiz.order[quiz.current];
  return {q:r.questions[qIndex], qIndex, reviewer:r};
}

function drawQuestion(){
  const {q, qIndex} = currentQuestion();
  document.getElementById('examQNum').textContent = `Question ${quiz.current+1} of ${quiz.order.length}`;
  document.getElementById('examQType').textContent = QTYPES[q.type];
  document.getElementById('examQuestion').textContent = q.text;
  document.getElementById('examProgressFill').style.width = ((quiz.current)/(quiz.order.length-1||1)*100)+'%';
  document.getElementById('markReview').checked = !!quiz.marked[qIndex];

  const area = document.getElementById('examAnswerArea');
  area.innerHTML='';
  const existing = quiz.responses[qIndex];

  if(q.type==='mcq'){
    const wrap = el('div','exam-choices');
    q.options.forEach((opt,i)=>{
      const c = el('div','choice'+(existing===i?' selected':''));
      c.innerHTML = `<span class="letter">${String.fromCharCode(65+i)}</span><span>${escapeHtml(opt)}</span>`;
      c.addEventListener('click', ()=>{ quiz.responses[qIndex]=i; drawQuestion(); buildQNav(); });
      wrap.appendChild(c);
    });
    area.appendChild(wrap);
  } else if(q.type==='tf'){
    const wrap = el('div','exam-choices');
    [['True',true],['False',false]].forEach(([label,val])=>{
      const c = el('div','choice'+(existing===val?' selected':''));
      c.innerHTML = `<span class="letter">${label[0]}</span><span>${label}</span>`;
      c.addEventListener('click', ()=>{ quiz.responses[qIndex]=val; drawQuestion(); buildQNav(); });
      wrap.appendChild(c);
    });
    area.appendChild(wrap);
  } else if(q.type==='id'){
    const wrap = el('div','exam-freeform');
    wrap.innerHTML = `<input type="text" id="idInput" placeholder="Type your answer…" value="${existing?escapeHtml(existing):''}">`;
    area.appendChild(wrap);
    wrap.querySelector('input').addEventListener('input', e=>{ quiz.responses[qIndex]=e.target.value; buildQNav(); });
  } else if(q.type==='enum'){
    const wrap = el('div','exam-freeform');
    const count = q.answers.length;
    const vals = existing || Array(count).fill('');
    for(let i=0;i<count;i++){
      const row = el('div','enum-row');
      row.innerHTML = `<span class="idx">${i+1}.</span><input type="text" data-i="${i}" placeholder="Answer ${i+1}" value="${escapeHtml(vals[i]||'')}">`;
      wrap.appendChild(row);
    }
    area.appendChild(wrap);
    wrap.querySelectorAll('input').forEach(inp=>{
      inp.addEventListener('input', e=>{
        const arr = quiz.responses[qIndex] || Array(count).fill('');
        arr[parseInt(e.target.dataset.i,10)] = e.target.value;
        quiz.responses[qIndex] = arr;
        buildQNav();
      });
    });
  }

  document.getElementById('examPrev').disabled = quiz.current===0;
  const isLast = quiz.current === quiz.order.length-1;
  document.getElementById('examNext').style.display = isLast ? 'none':'inline-flex';
  document.getElementById('examSubmit').style.display = isLast ? 'inline-flex':'none';
}

document.getElementById('examPrev').addEventListener('click', ()=>{ if(quiz.current>0){ quiz.current--; drawQuestion(); buildQNav(); } });
document.getElementById('examNext').addEventListener('click', ()=>{ if(quiz.current<quiz.order.length-1){ quiz.current++; drawQuestion(); buildQNav(); } });
document.getElementById('examSubmit').addEventListener('click', ()=>{
  const unanswered = quiz.order.length - Object.keys(quiz.responses).length;
  if(unanswered>0){
    if(!confirm(`You have ${unanswered} unanswered question(s). Submit anyway?`)) return;
  }
  submitExam();
});
document.getElementById('markReview').addEventListener('change', e=>{
  const {qIndex} = currentQuestion();
  if(e.target.checked) quiz.marked[qIndex]=true; else delete quiz.marked[qIndex];
  buildQNav();
});

function buildQNav(){
  const grid = document.getElementById('qnavGrid');
  grid.innerHTML='';
  quiz.order.forEach((qIndex, i)=>{
    const cell = el('div','qnav-cell');
    cell.textContent = i+1;
    if(quiz.responses.hasOwnProperty(qIndex)) cell.classList.add('answered');
    if(quiz.marked[qIndex]) cell.classList.add('marked');
    if(i===quiz.current) cell.classList.add('current');
    cell.addEventListener('click', ()=>{ quiz.current=i; drawQuestion(); buildQNav(); });
    grid.appendChild(cell);
  });
}

function isCorrect(q, given){
  if(given===undefined || given===null) return false;
  if(q.type==='mcq') return given===q.correctIndex;
  if(q.type==='tf') return given===q.correctBool;
  if(q.type==='id') return typeof given==='string' && given.trim().toLowerCase()===q.answer.trim().toLowerCase();
  if(q.type==='enum'){
    if(!Array.isArray(given)) return false;
    const norm = a => (a||'').trim().toLowerCase();
    const correctSet = q.answers.map(norm);
    const givenSet = given.map(norm).filter(Boolean);
    if(givenSet.length !== correctSet.length) return false;
    return correctSet.every(c=>givenSet.includes(c));
  }
  return false;
}
function correctAnswerLabel(q){
  if(q.type==='mcq') return q.options[q.correctIndex];
  if(q.type==='tf') return q.correctBool?'True':'False';
  if(q.type==='id') return q.answer;
  if(q.type==='enum') return q.answers.join(', ');
}
function givenAnswerLabel(q, given){
  if(given===undefined||given===null||given==='') return '(no answer)';
  if(q.type==='mcq') return q.options[given];
  if(q.type==='tf') return given?'True':'False';
  if(q.type==='id') return given;
  if(q.type==='enum') return Array.isArray(given) ? given.filter(Boolean).join(', ') || '(no answer)' : '(no answer)';
}

function submitExam(){
  clearInterval(timerInterval);
  const r = findReviewer(quiz.reviewerId);
  const timeUsed = Math.round((Date.now()-quiz.startTs)/1000);
  const details = quiz.order.map(qIndex=>{
    const q = r.questions[qIndex];
    const given = quiz.responses[qIndex];
    const correct = isCorrect(q, given);
    return {q, qIndex, given, correct};
  });
  const correctCount = details.filter(d=>d.correct).length;
  const total = details.length;
  const pct = Math.round((correctCount/total)*100);

  // topic breakdown (single subject reviewer, so 1 topic = subject)
  const topicStats = {};
  const topic = r.subject;
  topicStats[topic] = topicStats[topic] || {correct:0,total:0};
  topicStats[topic].total += total;
  topicStats[topic].correct += correctCount;

  // record attempt
  r.attempts = r.attempts || [];
  r.attempts.push({ts:Date.now(), correct:correctCount, total, pct, timeUsed, mode:quiz.mode});

  // error archive: add incorrect, remove ones now correct if retried directly
  details.filter(d=>!d.correct).forEach(d=>{
    state.errorArchive = state.errorArchive.filter(e=>!(e.reviewerId===r.id && e.questionId===d.q.id));
    state.errorArchive.unshift({
      id: uid(),
      questionId: d.q.id,
      reviewerId: r.id,
      questionText: d.q.text,
      type: d.q.type,
      subject: r.subject,
      yourAnswer: givenAnswerLabel(d.q, d.given),
      correctAnswer: correctAnswerLabel(d.q),
      explanation: d.q.explanation || '',
      ts: Date.now()
    });
  });
  // remove now-correct ones from archive
  details.filter(d=>d.correct).forEach(d=>{
    state.errorArchive = state.errorArchive.filter(e=>!(e.reviewerId===r.id && e.questionId===d.q.id));
  });

  bumpStreak();
  logActivity(`${quiz.mode==='mock'?'Completed mock exam':'Practiced'} "${r.title}" — ${pct}%`);
  persist();

  closeExamShell();
  navigate('results', {result:{reviewerId:r.id, reviewerTitle:r.title, subject:r.subject, correctCount, total, pct, timeUsed, details, topicStats}});
}

/* ============================================================
   RESULTS
   ============================================================ */
function renderResultsView(stage, params){
  const res = params.result;
  if(!res){ navigate('overview'); return; }

  const hero = el('div','results-hero');
  hero.innerHTML = `
    <div class="score-big">${res.pct}<small>%</small></div>
    <div class="results-stats">
      <div class="rs-item"><div class="num">${res.correctCount}/${res.total}</div><div class="lbl">Correct</div></div>
      <div class="rs-item"><div class="num">${formatDuration(res.timeUsed)}</div><div class="lbl">Time used</div></div>
      <div class="rs-item"><div class="num">${res.subject}</div><div class="lbl">Subject</div></div>
    </div>
  `;
  stage.appendChild(hero);

  const head = el('div','section-head'); head.innerHTML = `<h2 style="font-size:17px;">Performance by topic</h2>`;
  stage.appendChild(head);
  Object.entries(res.topicStats).forEach(([topic,st])=>{
    const pct = Math.round((st.correct/st.total)*100);
    const row = el('div','topic-bar-row');
    row.innerHTML = `<span class="tname">${escapeHtml(topic)}</span><div class="topic-bar-track"><div class="topic-bar-fill" style="width:${pct}%"></div></div><span class="tpct">${pct}%</span>`;
    stage.appendChild(row);
  });

  const actionsRow = el('div'); actionsRow.style.cssText='display:flex;gap:10px;margin:26px 0 32px;';
  const retryBtn = el('button','btn btn-primary','Try again');
  retryBtn.addEventListener('click', ()=>{
    if(findReviewer(res.reviewerId)) startQuiz(res.reviewerId, 'practice');
    else toast('This reviewer no longer exists');
  });
  const reviewBtn = el('button','btn','Review mistakes');
  reviewBtn.addEventListener('click', ()=>{
    document.getElementById('mistakesBlock').scrollIntoView({behavior:'smooth'});
  });
  const homeBtn = el('button','btn btn-ghost','Back to overview');
  homeBtn.addEventListener('click', ()=>navigate('overview'));
  actionsRow.appendChild(retryBtn); actionsRow.appendChild(reviewBtn); actionsRow.appendChild(homeBtn);
  stage.appendChild(actionsRow);

  const mHead = el('div','section-head'); mHead.id='mistakesBlock'; mHead.innerHTML = `<h2 style="font-size:17px;">Questions needing review</h2>`;
  stage.appendChild(mHead);
  const wrong = res.details.filter(d=>!d.correct);
  if(wrong.length===0){
    stage.appendChild(emptyState('Clean sweep','You answered every question correctly on this attempt.'));
  } else {
    wrong.forEach(d=>{
      const item = el('div','review-item');
      item.innerHTML = `
        <div class="qt">${escapeHtml(d.q.text)}</div>
        <div class="ans-line wrong"><b>Your answer:</b> ${escapeHtml(givenAnswerLabel(d.q,d.given))}</div>
        <div class="ans-line right"><b>Correct answer:</b> ${escapeHtml(correctAnswerLabel(d.q))}</div>
        ${d.q.explanation ? `<div class="expl">${escapeHtml(d.q.explanation)}</div>` : ''}
      `;
      stage.appendChild(item);
    });
  }
}
function formatDuration(sec){
  const m = Math.floor(sec/60), s = sec%60;
  return m+'m '+String(s).padStart(2,'0')+'s';
}

/* ============================================================
   ERROR ARCHIVE
   ============================================================ */
function renderErrors(stage){
  const head = el('div','section-head');
  head.innerHTML = `<h2>Error Archive</h2>`;
  if(state.errorArchive.length>0){
    const clearBtn = el('button','btn btn-danger btn-sm','Clear archive');
    clearBtn.addEventListener('click', ()=>{ if(confirm('Clear all archived mistakes?')){ state.errorArchive=[]; persist(); renderErrors(stage); } });
    head.appendChild(clearBtn);
  }
  stage.appendChild(head);
  const p = el('p'); p.style.cssText='color:var(--ink-soft);font-size:14px;max-width:560px;margin-bottom:22px;';
  p.textContent = 'Every question you have missed lives here until you answer it correctly again.';
  stage.appendChild(p);

  if(state.errorArchive.length===0){
    stage.appendChild(emptyState('Archive is empty','Missed questions from practice and mock exams will appear here for targeted review.'));
    return;
  }

  state.errorArchive.forEach(e=>{
    const item = el('div','err-item');
    item.innerHTML = `
      <span class="subj">${escapeHtml(e.subject)} · ${QTYPES[e.type]}</span>
      <div class="qt">${escapeHtml(e.questionText)}</div>
      <div class="err-grid">
        <div class="err-box wrong"><span class="k">Your answer</span>${escapeHtml(e.yourAnswer)}</div>
        <div class="err-box right"><span class="k">Correct answer</span>${escapeHtml(e.correctAnswer)}</div>
      </div>
      ${e.explanation ? `<div class="expl" style="font-size:12.5px;color:var(--ink-soft);margin-bottom:10px;">${escapeHtml(e.explanation)}</div>` : ''}
    `;
    const retryBtn = el('button','btn btn-sm','Retry this question');
    retryBtn.addEventListener('click', ()=>retrySingleQuestion(e));
    item.appendChild(retryBtn);
    stage.appendChild(item);
  });
}
function retrySingleQuestion(errEntry){
  const r = findReviewer(errEntry.reviewerId);
  if(!r){ toast('Original reviewer was deleted'); return; }
  const q = r.questions.find(qq=>qq.id===errEntry.questionId);
  if(!q){ toast('This question no longer exists'); return; }
  quiz = {
    reviewerId: r.id, mode:'practice',
    order:[r.questions.indexOf(q)],
    responses:{}, marked:{}, current:0, startTs:Date.now(), durationSec:null, remaining:null
  };
  openExamShell();
  document.getElementById('examTimer').style.display='none';
  drawQuestion();
  buildQNav();
}

/* ============================================================
   PROGRESS
   ============================================================ */
function renderProgress(stage){
  const head = el('div','section-head'); head.innerHTML = `<h2>Progress</h2>`;
  stage.appendChild(head);

  const stats = computeStats();
  const ledger = el('div','ledger');
  ledger.innerHTML = `
    <div class="ledger-cell"><div class="num">${state.reviewers.length}</div><div class="lbl">Reviewers built</div></div>
    <div class="ledger-cell"><div class="num">${totalQuestions()}</div><div class="lbl">Total questions</div></div>
    <div class="ledger-cell"><div class="num">${stats.accuracy}%</div><div class="lbl">Overall accuracy</div></div>
    <div class="ledger-cell"><div class="num">${state.errorArchive.length}</div><div class="lbl">Open mistakes</div></div>
  `;
  stage.appendChild(ledger);

  const head2 = el('div','section-head'); head2.innerHTML = `<h2 style="font-size:17px;">By reviewer</h2>`;
  stage.appendChild(head2);

  if(state.reviewers.length===0){
    stage.appendChild(emptyState('Nothing to show yet','Build and attempt a reviewer to see your progress here.'));
    return;
  }
  state.reviewers.forEach(r=>{
    const attempts = r.attempts||[];
    const best = attempts.length ? Math.max(...attempts.map(a=>a.pct)) : 0;
    const row = el('div','topic-bar-row');
    row.innerHTML = `<span class="tname">${escapeHtml(r.title)}</span><div class="topic-bar-track"><div class="topic-bar-fill" style="width:${best}%"></div></div><span class="tpct">${best}%</span>`;
    stage.appendChild(row);
  });
}

/* ============================================================
   SETTINGS
   ============================================================ */
function renderSettings(stage){
  const head = el('div','section-head'); head.innerHTML = `<h2>Settings</h2>`;
  stage.appendChild(head);

  const appearance = el('div','settings-group');
  appearance.innerHTML = `<h4>Appearance</h4>`;
  const row1 = el('div','settings-row');
  row1.innerHTML = `<div><div class="lbl">Theme</div><div class="desc">Switch between light and dark mode.</div></div>`;
  const tt = el('div','theme-toggle'); tt.style.width='140px';
  tt.innerHTML = `<button id="stLight">Light</button><button id="stDark">Dark</button>`;
  row1.appendChild(tt);
  appearance.appendChild(row1);
  stage.appendChild(appearance);
  document.getElementById('stLight').classList.toggle('on', state.theme==='light');
  document.getElementById('stDark').classList.toggle('on', state.theme==='dark');
  document.getElementById('stLight').addEventListener('click', ()=>{ state.theme='light'; persist(); applyTheme(); renderSettings(stage); });
  document.getElementById('stDark').addEventListener('click', ()=>{ state.theme='dark'; persist(); applyTheme(); renderSettings(stage); });

  const examGroup = el('div','settings-group');
  examGroup.innerHTML = `<h4>Exams</h4>`;
  const row2 = el('div','settings-row');
  row2.innerHTML = `<div><div class="lbl">Default mock exam duration</div><div class="desc">Applied when you start a new mock exam.</div></div>`;
  const durInput = el('input','text-input'); durInput.type='number'; durInput.min='1'; durInput.style.width='80px'; durInput.value=state.mockDuration;
  durInput.addEventListener('change', ()=>{ state.mockDuration = Math.max(1, parseInt(durInput.value||15,10)); persist(); toast('Saved'); });
  row2.appendChild(durInput);
  examGroup.appendChild(row2);
  stage.appendChild(examGroup);

  const dataGroup = el('div','settings-group');
  dataGroup.innerHTML = `<h4>Data</h4>`;
  const row3 = el('div','settings-row');
  row3.innerHTML = `<div><div class="lbl">Export study data</div><div class="desc">Download a JSON backup of all reviewers and progress.</div></div>`;
  const exportBtn = el('button','btn btn-sm','Export');
  exportBtn.addEventListener('click', ()=>{
    const blob = new Blob([JSON.stringify(state,null,2)], {type:'application/json'});
    const a = document.createElement('a');
    a.href = URL.createObjectURL(blob);
    a.download = 'examora-backup.json';
    a.click();
  });
  row3.appendChild(exportBtn);
  dataGroup.appendChild(row3);

  const row4 = el('div','settings-row');
  row4.innerHTML = `<div><div class="lbl">Reset all data</div><div class="desc">Permanently erase every reviewer, attempt, and archived mistake.</div></div>`;
  const resetBtn = el('button','btn btn-sm btn-danger','Reset');
  resetBtn.addEventListener('click', ()=>{
    if(confirm('This will permanently delete everything. Continue?')){
      state = defaultState();
      persist();
      applyTheme();
      buildRail();
      navigate('overview');
      toast('All data cleared');
    }
  });
  row4.appendChild(resetBtn);
  dataGroup.appendChild(row4);
  stage.appendChild(dataGroup);
}

/* ============================================================
   INIT
   ============================================================ */
applyTheme();
buildRail();
navigate('overview');

})();
</script>
</body>
</html>
