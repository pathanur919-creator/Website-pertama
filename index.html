<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>StudyAbroad Tracker — Persiapan Kuliah Luar Negeri</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=DM+Sans:wght@300;400;500;600&display=swap">
<style>
:root{
  --bg:#09111F;
  --surface:#0F1C2E;
  --surface2:#162236;
  --surface3:#1D2E44;
  --gold:#F5A623;
  --gold-dim:#C47F0F;
  --teal:#14B8A6;
  --red:#EF4444;
  --green:#22C55E;
  --purple:#A855F7;
  --blue:#3B82F6;
  --orange:#F97316;
  --text:#E8EDF5;
  --text-dim:#8A9BB5;
  --border:#1E3050;
  --radius:14px;
  --transition:0.25s cubic-bezier(.4,0,.2,1);
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:'DM Sans',sans-serif;min-height:100vh;overflow-x:hidden}

/* ── NOISE OVERLAY ── */
body::before{
  content:'';position:fixed;inset:0;
  background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.03'/%3E%3C/svg%3E");
  pointer-events:none;z-index:0;opacity:0.4;
}

/* ── SIDEBAR ── */
.sidebar{
  position:fixed;top:0;left:0;width:240px;height:100vh;
  background:var(--surface);border-right:1px solid var(--border);
  display:flex;flex-direction:column;z-index:100;
  padding:0 0 20px;overflow-y:auto;
}
.sidebar-logo{
  padding:28px 24px 20px;
  border-bottom:1px solid var(--border);
}
.sidebar-logo h1{
  font-family:'Playfair Display',serif;font-size:1.3rem;
  font-weight:900;line-height:1.2;color:var(--gold);
}
.sidebar-logo span{display:block;font-size:0.72rem;color:var(--text-dim);margin-top:4px;letter-spacing:0.05em;text-transform:uppercase}
.nav-section{padding:18px 14px 6px;font-size:0.65rem;color:var(--text-dim);letter-spacing:0.12em;text-transform:uppercase;font-weight:600}
.nav-item{
  display:flex;align-items:center;gap:12px;
  padding:11px 20px;cursor:pointer;
  border-radius:10px;margin:2px 10px;
  font-size:0.88rem;font-weight:500;color:var(--text-dim);
  transition:var(--transition);border:1px solid transparent;
}
.nav-item:hover{background:var(--surface2);color:var(--text)}
.nav-item.active{background:linear-gradient(135deg,rgba(245,166,35,.15),rgba(20,184,166,.08));color:var(--gold);border-color:rgba(245,166,35,0.2)}
.nav-item .nav-icon{width:20px;text-align:center;font-size:1rem}
.nav-badge{margin-left:auto;font-size:0.7rem;background:var(--gold);color:#000;padding:2px 7px;border-radius:20px;font-weight:700}

/* ── OVERALL PROGRESS ON SIDEBAR ── */
.sidebar-progress{margin:20px 14px 0;padding:14px;background:var(--surface2);border-radius:var(--radius);border:1px solid var(--border)}
.sidebar-progress label{font-size:0.72rem;color:var(--text-dim);text-transform:uppercase;letter-spacing:0.05em}
.sidebar-progress .pct{font-size:1.5rem;font-weight:700;color:var(--gold);font-family:'Playfair Display',serif}
.sidebar-progress .bar{height:5px;background:var(--surface3);border-radius:99px;margin-top:8px;overflow:hidden}
.sidebar-progress .bar-fill{height:100%;background:linear-gradient(90deg,var(--gold),var(--teal));border-radius:99px;transition:width 0.8s cubic-bezier(.4,0,.2,1)}

/* ── MAIN ── */
.main{margin-left:240px;min-height:100vh;position:relative;z-index:1}
.page{display:none;padding:36px 40px;animation:fadeIn .3s ease}
.page.active{display:block}
@keyframes fadeIn{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
.page-header{margin-bottom:32px}
.page-title{font-family:'Playfair Display',serif;font-size:2.2rem;font-weight:900;line-height:1.1}
.page-title span{color:var(--gold)}
.page-sub{color:var(--text-dim);font-size:0.92rem;margin-top:6px}

/* ── CARDS ── */
.cards-grid{display:grid;gap:18px}
.cards-4{grid-template-columns:repeat(4,1fr)}
.cards-3{grid-template-columns:repeat(3,1fr)}
.cards-2{grid-template-columns:repeat(2,1fr)}
.card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:22px;
  transition:var(--transition);position:relative;overflow:hidden;
}
.card:hover{border-color:rgba(245,166,35,0.3);transform:translateY(-2px)}
.card::before{content:'';position:absolute;inset:0;opacity:0;background:radial-gradient(circle at 0% 0%,rgba(245,166,35,.06),transparent 60%);transition:var(--transition);pointer-events:none}
.card:hover::before{opacity:1}
.card-icon{font-size:1.8rem;margin-bottom:10px}
.card-label{font-size:0.75rem;color:var(--text-dim);text-transform:uppercase;letter-spacing:0.07em;font-weight:600}
.card-value{font-size:2rem;font-weight:700;font-family:'Playfair Display',serif;margin:4px 0;line-height:1}
.card-sub{font-size:0.8rem;color:var(--text-dim)}
.card-bar{height:4px;background:var(--surface3);border-radius:99px;margin-top:12px;overflow:hidden}
.card-bar-fill{height:100%;border-radius:99px;transition:width 0.8s ease}

/* ── STAT ACCENT ── */
.accent-gold .card-value{color:var(--gold)}
.accent-gold .card-bar-fill{background:var(--gold)}
.accent-teal .card-value{color:var(--teal)}
.accent-teal .card-bar-fill{background:var(--teal)}
.accent-green .card-value{color:var(--green)}
.accent-green .card-bar-fill{background:var(--green)}
.accent-purple .card-value{color:var(--purple)}
.accent-purple .card-bar-fill{background:var(--purple)}
.accent-blue .card-value{color:var(--blue)}
.accent-blue .card-bar-fill{background:var(--blue)}
.accent-orange .card-value{color:var(--orange)}
.accent-orange .card-bar-fill{background:var(--orange)}

/* ── SECTION HEADERS ── */
.section-header{
  display:flex;align-items:center;gap:12px;
  margin:32px 0 16px;
}
.section-header h2{font-family:'Playfair Display',serif;font-size:1.35rem;font-weight:700}
.section-header .chip{
  padding:4px 12px;border-radius:99px;font-size:0.75rem;font-weight:600;
}
.chip-gold{background:rgba(245,166,35,.15);color:var(--gold);border:1px solid rgba(245,166,35,.3)}
.chip-teal{background:rgba(20,184,166,.12);color:var(--teal);border:1px solid rgba(20,184,166,.3)}
.chip-green{background:rgba(34,197,94,.12);color:var(--green);border:1px solid rgba(34,197,94,.3)}
.chip-purple{background:rgba(168,85,247,.12);color:var(--purple);border:1px solid rgba(168,85,247,.3)}
.chip-red{background:rgba(239,68,68,.12);color:var(--red);border:1px solid rgba(239,68,68,.3)}
.chip-blue{background:rgba(59,130,246,.12);color:var(--blue);border:1px solid rgba(59,130,246,.3)}
.chip-orange{background:rgba(249,115,22,.12);color:var(--orange);border:1px solid rgba(249,115,22,.3)}

/* ── CHECKLIST ── */
.checklist{display:flex;flex-direction:column;gap:6px}
.check-phase{
  background:linear-gradient(135deg,var(--surface2),var(--surface3));
  border-radius:var(--radius);overflow:hidden;border:1px solid var(--border);
  margin-top:16px;
}
.check-phase-header{
  display:flex;align-items:center;gap:12px;padding:14px 18px;
  cursor:pointer;user-select:none;
}
.check-phase-header:hover{background:rgba(255,255,255,.03)}
.phase-icon{font-size:1.2rem}
.phase-title{font-weight:600;font-size:0.95rem;flex:1}
.phase-counter{font-size:0.78rem;color:var(--text-dim);background:var(--surface);padding:3px 10px;border-radius:20px}
.phase-toggle{color:var(--text-dim);transition:var(--transition);font-size:0.8rem}
.phase-open .phase-toggle{transform:rotate(180deg)}
.phase-body{display:none;padding:6px 18px 14px}
.phase-open .phase-body{display:block}
.check-item{
  display:flex;align-items:flex-start;gap:12px;
  padding:10px 12px;border-radius:10px;cursor:pointer;
  transition:var(--transition);margin-bottom:4px;
  border:1px solid transparent;
}
.check-item:hover{background:rgba(255,255,255,.04);border-color:var(--border)}
.check-item.done{opacity:0.6}
.check-item.done .check-label{text-decoration:line-through;color:var(--text-dim)}
.check-box{
  width:20px;height:20px;min-width:20px;border-radius:6px;
  border:2px solid var(--border);display:flex;align-items:center;justify-content:center;
  transition:var(--transition);margin-top:1px;
  background:var(--surface);
}
.check-item.done .check-box{background:var(--green);border-color:var(--green)}
.check-box svg{display:none;width:12px;height:12px;stroke:white;stroke-width:2.5;fill:none}
.check-item.done .check-box svg{display:block}
.check-label{font-size:0.88rem;flex:1;line-height:1.4}
.check-meta{font-size:0.75rem;color:var(--text-dim);margin-top:2px}
.check-week{
  font-size:0.7rem;padding:2px 8px;border-radius:20px;white-space:nowrap;
  background:var(--surface3);color:var(--text-dim);margin-top:2px;
}

/* ── PROGRESS BAR WIDE ── */
.progress-wide{background:var(--surface2);border-radius:var(--radius);padding:16px 20px;border:1px solid var(--border);margin-bottom:18px}
.progress-wide label{font-size:0.8rem;color:var(--text-dim);display:flex;justify-content:space-between}
.progress-wide label span{color:var(--gold);font-weight:600}
.progress-track{height:8px;background:var(--surface3);border-radius:99px;margin-top:8px;overflow:hidden}
.progress-fill{height:100%;border-radius:99px;transition:width 0.8s ease}

/* ── FINANCIAL ── */
.finance-input{
  background:var(--surface2);border:1px solid var(--border);
  border-radius:10px;padding:10px 14px;color:var(--text);
  font-family:'DM Sans',sans-serif;font-size:0.95rem;
  width:100%;transition:var(--transition);outline:none;
}
.finance-input:focus{border-color:var(--gold);box-shadow:0 0 0 3px rgba(245,166,35,.12)}
.finance-label{font-size:0.78rem;color:var(--text-dim);margin-bottom:6px;text-transform:uppercase;letter-spacing:0.05em;font-weight:600}
.finance-row{display:grid;grid-template-columns:1fr 1fr 1fr;gap:14px;margin-bottom:14px}
.finance-cell{display:flex;flex-direction:column}
.finance-total{
  background:linear-gradient(135deg,rgba(245,166,35,.1),rgba(20,184,166,.05));
  border:1px solid rgba(245,166,35,.25);border-radius:var(--radius);
  padding:18px 22px;display:flex;align-items:center;justify-content:space-between;
}
.finance-total-label{font-size:0.85rem;color:var(--text-dim)}
.finance-total-value{font-size:1.5rem;font-weight:700;color:var(--gold);font-family:'Playfair Display',serif}

/* ── TABLE ── */
.table-wrap{border-radius:var(--radius);overflow:hidden;border:1px solid var(--border)}
table{width:100%;border-collapse:collapse}
th{background:var(--surface2);padding:12px 16px;font-size:0.75rem;text-transform:uppercase;letter-spacing:0.07em;color:var(--text-dim);font-weight:600;text-align:left;white-space:nowrap}
td{padding:12px 16px;font-size:0.87rem;border-bottom:1px solid var(--border)}
tr:last-child td{border-bottom:none}
tr:hover td{background:rgba(255,255,255,.025)}
.td-center{text-align:center}

/* ── SCHOLARSHIP CARDS ── */
.sch-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.sch-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:20px;transition:var(--transition);
  display:flex;flex-direction:column;gap:10px;position:relative;overflow:hidden;
}
.sch-card:hover{border-color:rgba(245,166,35,.3);transform:translateY(-3px);box-shadow:0 12px 40px rgba(0,0,0,.4)}
.sch-card::after{
  content:'';position:absolute;top:0;right:0;width:80px;height:80px;
  background:radial-gradient(circle,rgba(245,166,35,.08),transparent 70%);
  pointer-events:none;
}
.sch-header{display:flex;align-items:flex-start;gap:12px}
.sch-flag{font-size:2rem;line-height:1}
.sch-info h3{font-size:1rem;font-weight:700;line-height:1.2}
.sch-info p{font-size:0.78rem;color:var(--text-dim);margin-top:2px}
.sch-status-select{
  border:1px solid var(--border);border-radius:8px;padding:6px 10px;
  background:var(--surface2);color:var(--text);font-family:'DM Sans',sans-serif;
  font-size:0.82rem;cursor:pointer;width:100%;outline:none;transition:var(--transition);
}
.sch-status-select:focus{border-color:var(--gold)}
.sch-tags{display:flex;flex-wrap:wrap;gap:6px}
.sch-tag{font-size:0.7rem;padding:3px 9px;border-radius:20px;font-weight:500}
.sch-benefits{font-size:0.82rem;color:var(--text-dim);line-height:1.6;border-top:1px solid var(--border);padding-top:10px}
.sch-deadline{
  display:flex;align-items:center;gap:6px;
  font-size:0.8rem;background:rgba(239,68,68,.1);color:#FCA5A5;
  padding:6px 12px;border-radius:8px;border:1px solid rgba(239,68,68,.2);
}

/* ── DEADLINE COUNTDOWN ── */
.deadline-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:16px 18px;
  display:flex;align-items:center;gap:16px;
  transition:var(--transition);
}
.deadline-card:hover{border-color:rgba(245,166,35,.3)}
.deadline-dots{width:10px;height:10px;border-radius:50%;flex-shrink:0}
.dl-urgent{background:var(--red);box-shadow:0 0 8px var(--red)}
.dl-soon{background:var(--orange);box-shadow:0 0 8px var(--orange)}
.dl-later{background:var(--green);box-shadow:0 0 8px var(--green)}
.deadline-info{flex:1}
.deadline-name{font-size:0.9rem;font-weight:600}
.deadline-when{font-size:0.78rem;color:var(--text-dim);margin-top:2px}
.deadline-badge{
  font-size:0.72rem;font-weight:700;padding:4px 10px;border-radius:20px;white-space:nowrap;
}

/* ── NOTES ── */
.notes-area{
  background:var(--surface2);border:1px solid var(--border);
  border-radius:var(--radius);padding:16px;color:var(--text);
  font-family:'DM Sans',sans-serif;font-size:0.9rem;
  min-height:180px;resize:vertical;width:100%;outline:none;
  transition:var(--transition);line-height:1.7;
}
.notes-area:focus{border-color:var(--gold);box-shadow:0 0 0 3px rgba(245,166,35,.1)}
.notes-list{display:flex;flex-direction:column;gap:10px}
.note-item{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:16px;position:relative;
  animation:slideIn .3s ease;
}
@keyframes slideIn{from{opacity:0;transform:translateX(-10px)}to{opacity:1;transform:translateX(0)}}
.note-item-header{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:8px}
.note-item-title{font-weight:600;font-size:0.9rem;color:var(--gold)}
.note-item-del{background:none;border:none;cursor:pointer;color:var(--text-dim);font-size:1.1rem;padding:0;line-height:1;transition:var(--transition)}
.note-item-del:hover{color:var(--red)}
.note-item-body{font-size:0.85rem;color:var(--text-dim);line-height:1.6}
.note-item-date{font-size:0.72rem;color:var(--text-dim);margin-top:8px;opacity:0.7}

/* ── BUTTONS ── */
.btn{
  padding:10px 20px;border-radius:10px;font-family:'DM Sans',sans-serif;
  font-weight:600;font-size:0.88rem;cursor:pointer;border:none;
  transition:var(--transition);display:inline-flex;align-items:center;gap:8px;
}
.btn-gold{background:var(--gold);color:#000}
.btn-gold:hover{background:#f0b030;transform:translateY(-1px);box-shadow:0 6px 20px rgba(245,166,35,.35)}
.btn-ghost{background:var(--surface2);color:var(--text);border:1px solid var(--border)}
.btn-ghost:hover{border-color:var(--gold);color:var(--gold)}
.btn-red{background:rgba(239,68,68,.15);color:var(--red);border:1px solid rgba(239,68,68,.3)}
.btn-red:hover{background:var(--red);color:white}

/* ── TIPS BOX ── */
.tips-box{
  background:linear-gradient(135deg,rgba(20,184,166,.08),rgba(245,166,35,.05));
  border:1px solid rgba(20,184,166,.2);border-radius:var(--radius);
  padding:16px 20px;margin-bottom:20px;
}
.tips-box h4{font-size:0.85rem;color:var(--teal);font-weight:700;margin-bottom:8px}
.tips-box p,.tips-box li{font-size:0.83rem;color:var(--text-dim);line-height:1.7}
.tips-box ul{padding-left:16px}

/* ── INFO TABLE ── */
.info-box{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);padding:20px}
.info-row{display:flex;justify-content:space-between;padding:10px 0;border-bottom:1px solid var(--border);align-items:center;font-size:0.87rem}
.info-row:last-child{border-bottom:none}
.info-key{color:var(--text-dim)}
.info-val{font-weight:600;text-align:right}

/* ── DIVIDER ── */
.divider{height:1px;background:var(--border);margin:28px 0}

/* ── TOAST ── */
.toast{
  position:fixed;bottom:30px;right:30px;z-index:999;
  background:var(--surface2);border:1px solid var(--border);
  border-radius:12px;padding:14px 20px;
  font-size:0.88rem;color:var(--text);
  box-shadow:0 8px 32px rgba(0,0,0,.5);
  display:flex;align-items:center;gap:10px;
  animation:slideUp .3s ease;
  pointer-events:none;
}
@keyframes slideUp{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
.toast.hidden{display:none}

/* ── RESPONSIVE ── */
@media(max-width:1200px){.cards-4{grid-template-columns:repeat(2,1fr)}}
@media(max-width:900px){
  .sidebar{width:60px}
  .sidebar-logo h1,.sidebar-logo span,.nav-item span,.nav-badge,.nav-section,.sidebar-progress{display:none}
  .nav-item{padding:14px;justify-content:center}
  .main{margin-left:60px}
  .page{padding:24px 20px}
  .cards-4,.cards-3,.cards-2{grid-template-columns:1fr}
  .sch-grid{grid-template-columns:1fr}
  .finance-row{grid-template-columns:1fr}
}

/* ── IELTS SCORE ESTIMATOR ── */
.score-box{
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--radius);padding:22px;
}
.score-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin:16px 0}
.score-module{text-align:center}
.score-module label{font-size:0.72rem;color:var(--text-dim);text-transform:uppercase;letter-spacing:0.05em;display:block;margin-bottom:8px}
.score-input{
  width:80px;padding:10px;text-align:center;border-radius:10px;
  border:2px solid var(--border);background:var(--surface2);
  color:var(--text);font-size:1.3rem;font-weight:700;
  font-family:'Playfair Display',serif;outline:none;transition:var(--transition);
}
.score-input:focus{border-color:var(--gold)}
.score-overall{
  text-align:center;padding:16px;
  background:linear-gradient(135deg,rgba(245,166,35,.1),rgba(20,184,166,.06));
  border-radius:var(--radius);border:1px solid rgba(245,166,35,.25);
}
.score-overall-num{font-size:3rem;font-weight:900;font-family:'Playfair Display',serif;color:var(--gold)}
.score-overall-label{font-size:0.8rem;color:var(--text-dim);margin-top:4px}

/* ── SAVINGS WHEEL ── */
.savings-visual{text-align:center;padding:10px}
.savings-visual svg{overflow:visible}

/* ── MODAL ── */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.7);z-index:200;display:flex;align-items:center;justify-content:center;backdrop-filter:blur(4px)}
.modal-overlay.hidden{display:none}
.modal{background:var(--surface);border:1px solid var(--border);border-radius:20px;padding:28px;width:90%;max-width:520px;max-height:90vh;overflow-y:auto;animation:fadeIn .25s ease}
.modal h3{font-family:'Playfair Display',serif;font-size:1.3rem;margin-bottom:16px}
.modal-actions{display:flex;gap:10px;margin-top:20px;justify-content:flex-end}
.form-row{margin-bottom:14px}
.form-row label{display:block;font-size:0.78rem;color:var(--text-dim);margin-bottom:6px;text-transform:uppercase;letter-spacing:0.05em;font-weight:600}
.form-control{
  width:100%;background:var(--surface2);border:1px solid var(--border);
  border-radius:10px;padding:10px 14px;color:var(--text);
  font-family:'DM Sans',sans-serif;font-size:0.9rem;outline:none;transition:var(--transition);
}
.form-control:focus{border-color:var(--gold);box-shadow:0 0 0 3px rgba(245,166,35,.12)}
textarea.form-control{min-height:100px;resize:vertical}
</style>
</head>
<body>
<!-- SIDEBAR -->
<nav class="sidebar">
  <div class="sidebar-logo">
    <h1>StudyAbroad<br>Tracker</h1>
    <span>Persiapan Kuliah Luar Negeri</span>
  </div>
  <div class="nav-section">Menu Utama</div>
  <div class="nav-item active" onclick="showPage('dashboard',this)"><span class="nav-icon">🏠</span><span>Dashboard</span></div>
  <div class="nav-item" onclick="showPage('ielts',this)"><span class="nav-icon">📚</span><span>Belajar IELTS</span><span class="nav-badge" id="badge-ielts">0%</span></div>
  <div class="nav-item" onclick="showPage('keuangan',this)"><span class="nav-icon">💰</span><span>Keuangan</span></div>
  <div class="nav-item" onclick="showPage('dokumen',this)"><span class="nav-icon">📋</span><span>Dokumen</span><span class="nav-badge" id="badge-dok">0%</span></div>
  <div class="nav-item" onclick="showPage('beasiswa',this)"><span class="nav-icon">🎓</span><span>Beasiswa</span></div>
  <div class="nav-section">Info</div>
  <div class="nav-item" onclick="showPage('negara',this)"><span class="nav-icon">🌍</span><span>Info Negara</span></div>
  <div class="nav-item" onclick="showPage('tips',this)"><span class="nav-icon">💡</span><span>Tips & Strategi</span></div>
  <div class="nav-item" onclick="showPage('catatan',this)"><span class="nav-icon">📝</span><span>Catatan</span></div>
  <div class="sidebar-progress">
    <label>Total Progress</label>
    <div class="pct" id="sidebar-pct">0%</div>
    <div class="bar"><div class="bar-fill" id="sidebar-bar" style="width:0%"></div></div>
  </div>
</nav>

<!-- MAIN -->
<main class="main">

<!-- ══════════ DASHBOARD ══════════ -->
<section class="page active" id="page-dashboard">
  <div class="page-header">
    <div class="page-title">Dashboard <span>Utama</span></div>
    <div class="page-sub">Pantau semua persiapan studi luar negeri kamu dalam satu tampilan</div>
  </div>

  <div class="cards-grid cards-4" style="margin-bottom:24px">
    <div class="card accent-gold">
      <div class="card-icon">📚</div>
      <div class="card-label">Progress IELTS</div>
      <div class="card-value" id="dash-ielts-pct">0%</div>
      <div class="card-sub" id="dash-ielts-sub">0 dari 46 sesi</div>
      <div class="card-bar"><div class="card-bar-fill" id="dash-ielts-bar" style="width:0%"></div></div>
    </div>
    <div class="card accent-teal">
      <div class="card-icon">💰</div>
      <div class="card-label">Dana Terkumpul</div>
      <div class="card-value" id="dash-dana">Rp0</div>
      <div class="card-sub">Target: Rp30.000.000</div>
      <div class="card-bar"><div class="card-bar-fill" id="dash-dana-bar" style="width:0%"></div></div>
    </div>
    <div class="card accent-green">
      <div class="card-icon">📋</div>
      <div class="card-label">Dokumen Selesai</div>
      <div class="card-value" id="dash-dok-pct">0%</div>
      <div class="card-sub" id="dash-dok-sub">0 dari 30 dokumen</div>
      <div class="card-bar"><div class="card-bar-fill" id="dash-dok-bar" style="width:0%"></div></div>
    </div>
    <div class="card accent-purple">
      <div class="card-icon">🎓</div>
      <div class="card-label">Beasiswa Dilamar</div>
      <div class="card-value" id="dash-sch">0</div>
      <div class="card-sub">dari 12 opsi tersedia</div>
      <div class="card-bar"><div class="card-bar-fill" id="dash-sch-bar" style="width:0%"></div></div>
    </div>
  </div>

  <!-- IELTS score estimator -->
  <div class="section-header"><h2>Estimator Skor IELTS</h2><span class="chip chip-gold">Real-time</span></div>
  <div class="score-box">
    <p style="font-size:0.85rem;color:var(--text-dim);margin-bottom:4px">Masukkan skor simulasi tiap modul (0-9) untuk melihat estimasi skor overall:</p>
    <div class="score-grid">
      <div class="score-module"><label>Listening</label><input class="score-input" type="number" min="0" max="9" step="0.5" value="0" id="sc-l" oninput="calcScore()"></div>
      <div class="score-module"><label>Reading</label><input class="score-input" type="number" min="0" max="9" step="0.5" value="0" id="sc-r" oninput="calcScore()"></div>
      <div class="score-module"><label>Writing</label><input class="score-input" type="number" min="0" max="9" step="0.5" value="0" id="sc-w" oninput="calcScore()"></div>
      <div class="score-module"><label>Speaking</label><input class="score-input" type="number" min="0" max="9" step="0.5" value="0" id="sc-s" oninput="calcScore()"></div>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
      <div class="score-overall">
        <div class="score-overall-num" id="sc-overall">0.0</div>
        <div class="score-overall-label">Skor Overall IELTS</div>
      </div>
      <div class="info-box" style="padding:14px">
        <div class="info-row"><span class="info-key">Target</span><span class="info-val" style="color:var(--gold)">7.0</span></div>
        <div class="info-row"><span class="info-key">Gap</span><span class="info-val" id="sc-gap" style="color:var(--red)">-7.0</span></div>
        <div class="info-row"><span class="info-key">Status</span><span class="info-val" id="sc-status">Mulai Latihan</span></div>
      </div>
    </div>
  </div>

  <!-- Deadlines -->
  <div class="section-header"><h2>Deadline Beasiswa</h2><span class="chip chip-red">Perhatikan!</span></div>
  <div class="cards-grid cards-2">
    <div class="checklist">
      <div class="deadline-card"><div class="deadline-dots dl-urgent"></div><div class="deadline-info"><div class="deadline-name">🇹🇷 Turkiye Burslari</div><div class="deadline-when">Januari – Februari</div></div><div class="deadline-badge chip-red">Segera!</div></div>
      <div class="deadline-card"><div class="deadline-dots dl-urgent"></div><div class="deadline-info"><div class="deadline-name">🇷🇺 Russian Gov. Quota</div><div class="deadline-when">Februari – Maret</div></div><div class="deadline-badge chip-red">Segera!</div></div>
      <div class="deadline-card"><div class="deadline-dots dl-urgent"></div><div class="deadline-info"><div class="deadline-name">🇹🇼 MOE Taiwan Scholarship</div><div class="deadline-when">Februari – Maret</div></div><div class="deadline-badge chip-red">Segera!</div></div>
      <div class="deadline-card"><div class="deadline-dots dl-urgent"></div><div class="deadline-info"><div class="deadline-name">🇧🇳 BDGS Brunei</div><div class="deadline-when">Januari – Maret</div></div><div class="deadline-badge chip-red">Segera!</div></div>
    </div>
    <div class="checklist">
      <div class="deadline-card"><div class="deadline-dots dl-urgent"></div><div class="deadline-info"><div class="deadline-name">🇭🇺 Stipendium Hungaricum</div><div class="deadline-when">Januari – Maret (via Kemendikbud)</div></div><div class="deadline-badge chip-red">Segera!</div></div>
      <div class="deadline-card"><div class="deadline-dots dl-soon"></div><div class="deadline-info"><div class="deadline-name">🇮🇳 ICCR India</div><div class="deadline-when">Maret (via Kedutaan India)</div></div><div class="deadline-badge chip-orange">1-2 bulan</div></div>
      <div class="deadline-card"><div class="deadline-dots dl-soon"></div><div class="deadline-info"><div class="deadline-name">🇨🇳 CSC China Jalur B</div><div class="deadline-when">Maret – April (univ. masing2)</div></div><div class="deadline-badge chip-orange">1-2 bulan</div></div>
      <div class="deadline-card"><div class="deadline-dots dl-later"></div><div class="deadline-info"><div class="deadline-name">🇷🇴 MFA Rumania</div><div class="deadline-when">April – Juni (studyinromania.ro)</div></div><div class="deadline-badge chip-green">3+ bulan</div></div>
    </div>
  </div>

  <div class="divider"></div>

  <!-- Quick tips -->
  <div class="tips-box">
    <h4>⚡ Tips Strategi Cepat</h4>
    <ul>
      <li><strong>Profil "Biasa" Bukan Hambatan</strong> — Negara seperti Rumania, Azerbaijan, Brunei tidak mensyaratkan medali olimpiade. Fokus pada Motivation Letter yang kuat.</li>
      <li><strong>IELTS 7.0 = Keunggulan Kompetitif</strong> — Kandidat dengan nilai akademis rata-rata tapi skor IELTS 7.0 memiliki posisi jauh lebih kuat dari kandidat berprestasi tanpa kemampuan bahasa.</li>
      <li><strong>Rp2.500.000/bulan</strong> — Target menabung minimal untuk mencapai Rp30 juta dalam 12 bulan. Mulai side hustle sekarang.</li>
      <li><strong>Pre-Admission Letter (China)</strong> — Hubungi profesor di universitas China sebelum mendaftar CSC. Ini adalah "kunci masuk" yang sering diabaikan.</li>
    </ul>
  </div>
</section>
<!-- ══════════ IELTS ══════════ -->
<section class="page" id="page-ielts">
  <div class="page-header">
    <div class="page-title">Tracker <span>Belajar IELTS</span></div>
    <div class="page-sub">Target Skor 7.0 — Program 12 Minggu Terstruktur | Centang ✔ setiap sesi yang selesai</div>
  </div>
  <div class="progress-wide">
    <label>Progress Keseluruhan Program IELTS <span id="ielts-prog-label">0 / 46 sesi (0%)</span></label>
    <div class="progress-track"><div class="progress-fill" id="ielts-prog-bar" style="width:0%;background:linear-gradient(90deg,var(--gold),var(--teal))"></div></div>
  </div>

  <div class="tips-box">
    <h4>📌 Panduan Belajar Efektif</h4>
    <ul>
      <li><strong>Sumber Gratis:</strong> BBC Learning English (grammar), IELTS Liz YouTube (strategi), Cambridge IELTS Book Series (soal resmi), IDP Official App</li>
      <li><strong>Biaya Tes 2026:</strong> British Council & IDP = Rp3.490.000 · IELTS for UKVI = Rp3.951.500 · IELTS Life Skills B1 = Rp3.021.000</li>
      <li><strong>Format:</strong> 4 modul — Listening (30 mnt, 40 soal) · Reading (60 mnt, 40 soal) · Writing (60 mnt, 2 task) · Speaking (11-14 mnt, 3 bagian)</li>
      <li><strong>Skor 7.0:</strong> "Good User" — kemampuan operasional bahasa yang baik, meski kadang ada ketidakakuratan di situasi kompleks</li>
    </ul>
  </div>

  <div id="ielts-checklist"></div>
</section>

<!-- ══════════ KEUANGAN ══════════ -->
<section class="page" id="page-keuangan">
  <div class="page-header">
    <div class="page-title">Tracker <span>Keuangan</span></div>
    <div class="page-sub">Target Rp30.000.000 dalam 12 bulan — Rp2.500.000/bulan</div>
  </div>

  <!-- Savings circle -->
  <div class="cards-grid cards-3" style="margin-bottom:24px">
    <div class="card accent-gold" style="grid-column:span 1">
      <div class="card-icon">🎯</div>
      <div class="card-label">Dana Terkumpul</div>
      <div class="card-value" id="fin-collected">Rp0</div>
      <div class="card-sub">Target: Rp30.000.000</div>
      <div class="card-bar"><div class="card-bar-fill" id="fin-bar" style="width:0%"></div></div>
    </div>
    <div class="card accent-teal">
      <div class="card-icon">📅</div>
      <div class="card-label">Rata-rata / Bulan</div>
      <div class="card-value" id="fin-avg">Rp0</div>
      <div class="card-sub" id="fin-avg-sub">Belum ada data</div>
      <div class="card-bar"><div class="card-bar-fill" id="fin-avg-bar" style="width:0%;background:var(--teal)"></div></div>
    </div>
    <div class="card accent-green">
      <div class="card-icon">📆</div>
      <div class="card-label">Estimasi Selesai</div>
      <div class="card-value" id="fin-eta">—</div>
      <div class="card-sub">jika konsisten</div>
    </div>
  </div>

  <!-- Monthly input -->
  <div class="section-header"><h2>Rekap Tabungan Bulanan</h2><span class="chip chip-teal">Input Manual</span></div>
  <div class="table-wrap">
    <table id="fin-table">
      <thead><tr><th>Bulan</th><th>Pemasukan (Rp)</th><th>Tabungan (Rp)</th><th>Pengeluaran Prep (Rp)</th><th>Side Hustle (Rp)</th><th>Catatan</th></tr></thead>
      <tbody id="fin-tbody"></tbody>
      <tfoot><tr style="background:var(--surface2)">
        <td style="font-weight:700;padding:12px 16px">TOTAL</td>
        <td style="font-weight:700;padding:12px 16px;color:var(--teal)" id="fin-tot-income">Rp0</td>
        <td style="font-weight:700;padding:12px 16px;color:var(--gold)" id="fin-tot-save">Rp0</td>
        <td style="font-weight:700;padding:12px 16px;color:var(--red)" id="fin-tot-exp">Rp0</td>
        <td style="font-weight:700;padding:12px 16px;color:var(--green)" id="fin-tot-hustle">Rp0</td>
        <td></td>
      </tr></tfoot>
    </table>
  </div>

  <div class="divider"></div>

  <!-- Expense estimator -->
  <div class="section-header"><h2>Estimasi Biaya Persiapan</h2><span class="chip chip-orange">Perlu Disiapkan</span></div>
  <div class="tips-box">
    <h4>💡 Dana darurat Rp10 juta adalah yang paling krusial!</h4>
    <p>Tunjangan beasiswa (stipend) biasanya baru cair 4-8 minggu setelah tiba di negara tujuan. Kamu butuh dana hidup mandiri di bulan pertama.</p>
  </div>
  <div class="table-wrap">
    <table>
      <thead><tr><th>#</th><th>Kategori Biaya</th><th>Min (Rp)</th><th>Maks (Rp)</th><th>✔ Dibayar</th><th>Keterangan</th></tr></thead>
      <tbody id="expense-tbody"></tbody>
    </table>
  </div>

  <div class="divider"></div>

  <!-- Side hustle -->
  <div class="section-header"><h2>Potensi Side Hustle Jakarta</h2><span class="chip chip-green">Tambah Penghasilan</span></div>
  <div class="sch-grid" id="hustle-grid"></div>
</section>

<!-- ══════════ DOKUMEN ══════════ -->
<section class="page" id="page-dokumen">
  <div class="page-header">
    <div class="page-title">Tracker <span>Dokumen</span></div>
    <div class="page-sub">Legalisasi · Apostille · Terjemahan Tersumpah · Pemeriksaan Kesehatan</div>
  </div>
  <div class="progress-wide">
    <label>Progress Dokumen <span id="dok-prog-label">0 / 30 dokumen (0%)</span></label>
    <div class="progress-track"><div class="progress-fill" id="dok-prog-bar" style="width:0%;background:linear-gradient(90deg,var(--green),var(--teal))"></div></div>
  </div>
  <div class="tips-box">
    <h4>⚖️ Sistem Apostille vs Legalisasi Konvensional</h4>
    <ul>
      <li><strong>Apostille (Kemenkumham):</strong> Cukup 1 stiker. Via <em>ahu.go.id</em> (AHU Online). Biaya Rp150.000/dokumen. Berlaku untuk semua negara anggota Konvensi Apostille.</li>
      <li><strong>China — 4 Tahap Wajib:</strong> Notaris → Kemenkumham → Kemenlu RI → Kedutaan Besar China. China BUKAN anggota Apostille.</li>
      <li><strong>Terjemahan Tersumpah:</strong> Rp150.000-350.000/halaman. Harus dilakukan oleh Penerjemah Tersumpah resmi yang diakui pemerintah.</li>
      <li><strong>Dokumen Kesehatan:</strong> Hanya berlaku 6 bulan! Jangan terlalu awal melakukan pemeriksaan.</li>
    </ul>
  </div>
  <div id="dok-checklist"></div>
</section>

<!-- ══════════ BEASISWA ══════════ -->
<section class="page" id="page-beasiswa">
  <div class="page-header">
    <div class="page-title">Tracker <span>Beasiswa</span></div>
    <div class="page-sub">12 Program Beasiswa Inklusif — Terbuka untuk Kandidat Tanpa Prestasi Olimpiade</div>
  </div>
  <div class="tips-box">
    <h4>🧭 Strategi Memilih Beasiswa yang Tepat</h4>
    <ul>
      <li><strong>Kandidat Akademis Rata-rata?</strong> Fokus ke Rumania (nilai min 7/10), ICCR India (tanpa IELTS), Turkiye Burslari (tanpa IELTS/TOEFL), dan BDGS Brunei.</li>
      <li><strong>Motivation Letter adalah kunci.</strong> Ceritakan: latar belakang → masalah di Indonesia → solusi dari studi ini → kenapa negara tersebut → rencana kontribusi setelah pulang.</li>
      <li><strong>China CSC Tipe B:</strong> Hubungi profesor di universitas China lebih dulu. Dapatkan Pre-Admission Letter sebelum daftar online.</li>
      <li><strong>Update status</strong> beasiswa secara rutin menggunakan dropdown di setiap kartu beasiswa.</li>
    </ul>
  </div>
  <div class="sch-grid" id="sch-grid"></div>
</section>

<!-- ══════════ INFO NEGARA ══════════ -->
<section class="page" id="page-negara">
  <div class="page-header">
    <div class="page-title">Info <span>Negara Tujuan</span></div>
    <div class="page-sub">Detail lengkap setiap negara: biaya hidup, iklim, bahasa, budaya</div>
  </div>
  <div id="negara-grid"></div>
</section>

<!-- ══════════ TIPS ══════════ -->
<section class="page" id="page-tips">
  <div class="page-header">
    <div class="page-title">Tips <span>& Strategi</span></div>
    <div class="page-sub">Panduan lengkap untuk kandidat dengan profil akademis rata-rata</div>
  </div>
  <div id="tips-content"></div>
</section>

<!-- ══════════ CATATAN ══════════ -->
<section class="page" id="page-catatan">
  <div class="page-header">
    <div class="page-title">📝 <span>Catatan Pribadi</span></div>
    <div class="page-sub">Simpan reminder, informasi penting, dan tindak lanjut</div>
  </div>
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:24px;align-items:start">
    <div>
      <div class="section-header" style="margin-top:0"><h2>Tulis Catatan Baru</h2></div>
      <div class="form-row"><label>Judul / Topik</label><input class="form-control" id="note-title" placeholder="cth: Reminder deadline Hungaria..."></div>
      <div class="form-row"><label>Isi Catatan</label><textarea class="form-control" id="note-body" placeholder="Tulis catatan penting di sini..."></textarea></div>
      <button class="btn btn-gold" onclick="addNote()">+ Simpan Catatan</button>
    </div>
    <div>
      <div class="section-header" style="margin-top:0"><h2>Catatan Tersimpan</h2><span class="chip chip-gold" id="note-count">0 catatan</span></div>
      <div class="notes-list" id="notes-list">
        <div style="color:var(--text-dim);font-size:0.87rem;text-align:center;padding:40px">Belum ada catatan. Tulis catatan pertamamu! 📝</div>
      </div>
    </div>
  </div>
</section>

</main>

<!-- TOAST -->
<div class="toast hidden" id="toast"><span id="toast-msg">✅ Tersimpan!</span></div>

<!-- Modal Note Edit -->
<div class="modal-overlay hidden" id="modal-overlay" onclick="closeModal(event)">
  <div class="modal" onclick="event.stopPropagation()">
    <h3>Edit Catatan</h3>
    <div class="form-row"><label>Judul</label><input class="form-control" id="edit-title"></div>
    <div class="form-row"><label>Isi</label><textarea class="form-control" id="edit-body"></textarea></div>
    <input type="hidden" id="edit-idx">
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal()">Batal</button>
      <button class="btn btn-gold" onclick="saveEdit()">Simpan</button>
    </div>
  </div>
</div>
<script>
// ══════════════════════════════════════════════════
// DATA
// ══════════════════════════════════════════════════
const IELTS_PHASES = [
  {title:"FASE 1: Fondasi & Diagnostik",color:"var(--teal)",icon:"🔍",week:"Minggu 1-4",sessions:[
    {w:"M1",t:"Simulasi tes IELTS lengkap — ukur kemampuan awal (baseline)",tip:"Gunakan Cambridge IELTS Book terbaru"},
    {w:"M1",t:"Pelajari format & struktur 4 modul IELTS secara menyeluruh",tip:"Tonton IELTS Liz YouTube: Overview All Modules"},
    {w:"M1",t:"Grammar: Tenses — Simple, Continuous, Perfect, Perfect Continuous",tip:"BBC Learning English: Grammar Series"},
    {w:"M1",t:"Grammar: Artikel (a / an / the) — kesalahan paling sering di Writing",tip:"Latihan 30 soal artikel setiap hari"},
    {w:"M2",t:"Grammar: Preposisi (in/on/at/by/with) & Conjunctions (although/however/therefore)",tip:""},
    {w:"M2",t:"Vocabulary tematik: Lingkungan (climate change, sustainability, pollution)",tip:"Buat kartu vocab atau pakai Anki"},
    {w:"M2",t:"Vocabulary tematik: Pendidikan (curriculum, pedagogy, lifelong learning)",tip:""},
    {w:"M2",t:"BBC Learning English — tonton 5 episode grammar, catat struktur kalimat",tip:"bbc.co.uk/learningenglish"},
    {w:"M2",t:"IELTS Liz YouTube — pelajari tips & trik untuk semua modul",tip:"youtube.com/ieltsliz"},
    {w:"M3",t:"Vocabulary tematik: Teknologi (artificial intelligence, automation, digital divide)",tip:""},
    {w:"M3",t:"Vocabulary tematik: Sosiologi & Kesehatan (urbanization, mental health, inequality)",tip:""},
    {w:"M3",t:"Listening: Kenalan dengan aksen British — latihan 30 menit setiap hari",tip:"Gunakan BBC Podcasts atau TED Talks"},
    {w:"M3",t:"Reading: Latihan dasar Skimming (baca cepat untuk ide pokok tiap paragraf)",tip:"Latih dengan artikel berita dalam bahasa Inggris"},
    {w:"M3",t:"Buat vocabulary notebook tematik — targetkan 100 kata baru di Fase 1",tip:"Tulis kata + definisi + contoh kalimat"},
    {w:"M4",t:"Simulasi tes ke-2 — ukur progress dan identifikasi area yang masih lemah",tip:"Kondisi seperti ujian sungguhan: tanpa gangguan"},
    {w:"M4",t:"Analisis kesalahan simulasi ke-2 secara mendalam — buat daftar pola kesalahan",tip:"Pahami MENGAPA jawaban salah, bukan hanya apa yang salah"},
    {w:"M4",t:"Pelajari format Computer-based IELTS via IDP Official App",tip:"ieltsindonesia.com/preparation"},
    {w:"M4",t:"Review & rangkum seluruh materi Fase 1 — siapkan diri untuk Fase 2",tip:""},
  ]},
  {title:"FASE 2: Strategi Modular — Listening & Reading",color:"var(--orange)",icon:"👂",week:"Minggu 5-8",sessions:[
    {w:"M5",t:"Listening: Latihan multi-aksen — British, Australian, American, Scottish",tip:"Aksen berbeda muncul dalam 4 section tes"},
    {w:"M5",t:"Listening: Teknik note-taking & identifikasi kata kunci (keywords) saat audio diputar",tip:"Baca soal dulu sebelum audio dimulai!"},
    {w:"M5",t:"Listening: Cambridge IELTS Book — kerjakan 2 tes penuh dengan timer",tip:"Analisis kesalahan setelah selesai"},
    {w:"M5",t:"Listening: Section 3 & 4 (academic discussion & lecture) — paling sulit",tip:"Fokus pada signal words: however, therefore, but..."},
    {w:"M6",t:"Reading: Strategi Skimming — baca 1 teks panjang dalam 3 menit, tangkap ide pokok",tip:"Baca judul, subtitle, kalimat pertama tiap paragraf"},
    {w:"M6",t:"Reading: Strategi Scanning — cari informasi spesifik (nama, tanggal, angka) dengan cepat",tip:"Jangan baca kata per kata saat scanning"},
    {w:"M6",t:"Reading: Kuasai tipe soal Multiple Choice & Matching Headings",tip:"Matching Headings: kerjakan TERAKHIR"},
    {w:"M6",t:"Reading: Kuasai True / False / Not Given — tipe soal paling menjebak!",tip:"Not Given ≠ False. NGI hanya jika info TIDAK ada di teks sama sekali"},
    {w:"M7",t:"Reading: Cambridge Book — latihan 3 teks per sesi dalam 60 menit (timed)",tip:"Teks 1 paling mudah, teks 3 paling sulit"},
    {w:"M7",t:"Reading: Tipe soal Sentence Completion, Summary, & Diagram Labelling",tip:""},
    {w:"M7",t:"Listening: Simulasi 30 menit penuh + analisis kesalahan mendalam",tip:""},
    {w:"M7",t:"Academic Word List (AWL) — hafalkan 200 kata akademik paling sering muncul",tip:"Cari AWL Sublist 1-4 di internet, gratis!"},
    {w:"M8",t:"Simulasi gabungan Listening + Reading dalam kondisi ujian sesungguhnya (timed)",tip:"Total 90 menit tanpa jeda"},
    {w:"M8",t:"Analisis pola kesalahan Listening & Reading — buat action plan perbaikan",tip:"Catat: apakah karena bahasa, strategi, atau konsentrasi?"},
  ]},
  {title:"FASE 3: Writing & Speaking",color:"var(--purple)",icon:"✍️",week:"Minggu 9-10",sessions:[
    {w:"M9",t:"Writing Task 1: Cara mendeskripsikan grafik garis, bar chart, dan pie chart",tip:"Gunakan kata: increased, decreased, peaked, fluctuated"},
    {w:"M9",t:"Writing Task 1: Cara mendeskripsikan tabel, proses (diagram), dan peta",tip:"Proses: gunakan passive voice dan kalimat kronologis"},
    {w:"M9",t:"Writing Task 1: Kosakata perbandingan & tren data (significantly, slightly, dramatically)",tip:"Variasikan vocabulary, jangan ulangi kata yang sama"},
    {w:"M9",t:"Writing Task 2: Struktur esai standar (intro 2 kalimat, 2 body paragraf, conclusion)",tip:"Gunakan PEEL: Point → Evidence → Explain → Link"},
    {w:"M9",t:"Writing Task 2: Latihan nulis esai 250 kata dalam 40 menit — tema lingkungan",tip:"Target: selesai dalam 35 menit + 5 menit review"},
    {w:"M9",t:"Writing Task 2: Latihan esai tema teknologi & pendidikan dalam 40 menit",tip:""},
    {w:"M9",t:"Writing: Belajar cohesion & coherence — penggunaan linking words yang natural",tip:"Jangan overuse: Furthermore, Moreover, Additionally"},
    {w:"M10",t:"Speaking Part 1: Latihan menjawab topik personal (hobi, keluarga, pekerjaan) dengan elaboratif",tip:"Jawab dalam 3-4 kalimat, jangan hanya 1 kata"},
    {w:"M10",t:"Speaking Part 2: Cue Card — latihan bicara 2 menit tanpa jeda tentang 1 topik",tip:"Pakai 1 menit persiapan untuk buat outline singkat"},
    {w:"M10",t:"Speaking Part 3: Diskusi abstrak & ungkapan opini (society, future, global issues)",tip:"Gunakan: I believe that... / From my perspective... / It seems to me that..."},
    {w:"M10",t:"Speaking: Rekam diri sendiri & evaluasi intonasi, pengucapan, dan kelancaran",tip:"Bandingkan dengan native speaker di YouTube"},
    {w:"M10",t:"Speaking: Latihan idiom & phrasal verbs untuk meningkatkan skor Lexical Resource",tip:"cth: 'hit the nail on the head', 'up in the air', 'on the fence'"},
  ]},
  {title:"FASE 4: Simulasi Intensif & Finalisasi",color:"var(--green)",icon:"🏁",week:"Minggu 11-12",sessions:[
    {w:"M11",t:"Simulasi penuh kondisi ujian: Listening + Reading (90 menit, no cheating!)",tip:"Matikan HP, simulasi di meja belajar bersih"},
    {w:"M11",t:"Simulasi Writing: 2 task dalam 60 menit (Task 1: 20 mnt, Task 2: 40 mnt)",tip:"Tulis tangan jika mau tes Paper-based"},
    {w:"M11",t:"Simulasi Speaking: Rekam video wawancara lengkap (Part 1, 2, dan 3)",tip:"Minta teman native/fasih untuk feedback"},
    {w:"M11",t:"Analisis mendalam semua kesalahan dari simulasi Minggu 11",tip:"Prioritaskan perbaikan di area yang gap-nya paling besar"},
    {w:"M12",t:"Simulasi kondisi ujian asli — Set A: semua modul dalam 1 hari",tip:"Mulai pagi seperti jadwal ujian sungguhan"},
    {w:"M12",t:"Simulasi kondisi ujian asli — Set B: semua modul, hari berbeda",tip:""},
    {w:"M12",t:"Review final: grammar rules yang sering salah, vocabulary penting, strategi tiap modul",tip:"Baca catatan sendiri, bukan buku baru"},
    {w:"M12",t:"✅ BOOKING SLOT UJIAN IELTS — British Council atau IDP Education",tip:"Daftar di ieltsindonesia.com · Harga: Rp3.490.000 · Siapkan paspor"},
  ]},
];

const DOCS = [
  {section:"📄 Dokumen Akademik Utama",color:"var(--teal)",items:[
    {name:"Ijazah / STTB Terakhir",leg:"Apostille Kemenkumham",country:"Semua",est:"Rp150.000"},
    {name:"Transkrip Nilai Akademik",leg:"Apostille Kemenkumham",country:"Semua",est:"Rp150.000"},
    {name:"Terjemahan Ijazah (Tersumpah)",leg:"Penerjemah Tersumpah",country:"Semua",est:"Rp200.000-350.000/hal"},
    {name:"Terjemahan Transkrip (Tersumpah)",leg:"Penerjemah Tersumpah",country:"Semua",est:"Rp200.000-350.000/hal"},
    {name:"Sertifikat IELTS / TOEFL (7.0+)",leg:"Original / Scan Berwarna",country:"Semua",est:"Sudah bayar saat tes"},
    {name:"Surat Rekomendasi Dosen 1",leg:"Asli + Scan PDF",country:"Semua",est:"Gratis"},
    {name:"Surat Rekomendasi Dosen 2",leg:"Asli + Scan PDF",country:"Semua",est:"Gratis"},
    {name:"Surat Rekomendasi Atasan/Kerja",leg:"Asli + Scan PDF",country:"Opsional",est:"Gratis"},
  ]},
  {section:"🪪 Dokumen Identitas & Administrasi",color:"var(--orange)",items:[
    {name:"Paspor (berlaku min. 18 bulan)",leg:"Asli — bawa selalu",country:"Semua",est:"Rp350.000 (baru) / Rp300.000 (perpanjang)"},
    {name:"KTP / Kartu Identitas Nasional",leg:"Apostille atau Notaris",country:"Semua",est:"Rp150.000"},
    {name:"Akta Kelahiran",leg:"Apostille Kemenkumham",country:"Semua",est:"Rp150.000"},
    {name:"Terjemahan Akta Kelahiran (Tersumpah)",leg:"Penerjemah Tersumpah",country:"Semua",est:"Rp200.000-350.000"},
    {name:"Kartu Keluarga (KK)",leg:"Apostille (jika diminta)",country:"Beberapa negara",est:"Rp150.000"},
    {name:"Foto 4×6 Background Biru/Putih (10 lembar)",leg:"Foto Studio Resmi",country:"Semua",est:"Rp30.000-50.000"},
  ]},
  {section:"🏥 Dokumen Kesehatan",color:"var(--red)",items:[
    {name:"Medical Check-Up Lengkap (Formulir Resmi Pemberi Beasiswa)",leg:"RS Pemerintah Terakreditasi",country:"China/Rusia/Azerbaijan",est:"Rp1.500.000-2.500.000"},
    {name:"Tes HIV / AIDS",leg:"Laboratorium Terakreditasi",country:"China/Rusia/AZ",est:"Termasuk MCU"},
    {name:"Tes Hepatitis B & C",leg:"Laboratorium Terakreditasi",country:"China/Rusia/AZ",est:"Termasuk MCU"},
    {name:"Foto Rontgen Dada (deteksi TBC)",leg:"RS Pemerintah",country:"China/Rusia",est:"Termasuk MCU"},
    {name:"EKG (Elektrokardiogram)",leg:"RS Pemerintah",country:"China/Rusia",est:"Termasuk MCU"},
    {name:"Surat Bebas Narkoba",leg:"BNN atau RS Pemerintah",country:"Beberapa program",est:"Rp200.000-500.000"},
    {name:"Surat Sehat Jiwa (jika diminta)",leg:"RS Jiwa Pemerintah",country:"Opsional",est:"Rp150.000-300.000"},
  ]},
  {section:"📝 Dokumen Motivasi & Pendukung",color:"var(--green)",items:[
    {name:"Motivation Letter (Surat Motivasi) Bahasa Inggris",leg:"Tulis sendiri — maks 1-2 hal",country:"Semua",est:"Gratis — Tulis dengan hati!"},
    {name:"CV / Resume Akademik (Bahasa Inggris)",leg:"Format standar internasional",country:"Semua",est:"Gratis"},
    {name:"Personal Statement (jika diminta)",leg:"Bahasa Inggris",country:"Beberapa beasiswa",est:"Gratis"},
    {name:"Bukti Rekening / Tabungan (jika diminta)",leg:"Terjemahan jika perlu",country:"Opsional",est:"Rp0-150.000"},
    {name:"Surat Izin / Persetujuan Orang Tua",leg:"Notaris (jika diminta)",country:"Opsional",est:"Rp50.000-100.000"},
  ]},
  {section:"⚠️ Legalisasi Khusus China (4 Tahap WAJIB)",color:"var(--navy,#1B3A6B)",items:[
    {name:"STEP 1: Legalisasi Notaris Lokal",leg:"Notaris Terakreditasi",country:"🇨🇳 China ONLY",est:"Rp200.000-500.000/dok"},
    {name:"STEP 2: Legalisasi Kemenkumham RI",leg:"Kemenkumham (bukan Apostille!)",country:"🇨🇳 China ONLY",est:"Rp150.000/dok"},
    {name:"STEP 3: Legalisasi Kementerian Luar Negeri RI",leg:"Kemenlu RI",country:"🇨🇳 China ONLY",est:"Rp50.000-150.000/dok"},
    {name:"STEP 4: Legalisasi Kedutaan Besar China",leg:"KBRI / Kedubes RRT di Jakarta",country:"🇨🇳 China ONLY",est:"USD 10-30/dok"},
  ]},
];

const SCHOLARSHIPS = [
  {flag:"🇭🇺",name:"Stipendium Hungaricum",country:"Hungaria",level:"S1 / S2 / S3",deadline:"Januari – Maret",portal:"DreamApply.com",status:"Belum Daftar",
   cover:"Full tuition + asrama + uang saku bulanan + asuransi kesehatan",
   req:"Minimal lulus SMA/D3/S1 sesuai jenjang. Tidak ada syarat IELTS minimum resmi (7.0+ disarankan). Motivasi yang kuat.",
   tips:"Daftar via portal Kemendikbudristek Indonesia. Bisa pilih 2 program studi di 2 universitas berbeda. Motivation letter yang menceritakan kontribusi untuk Indonesia sangat penting.",
   tags:["Full Beasiswa","Via Kemendikbud","DreamApply","Eropa Tengah"],colors:["chip-gold","chip-teal","chip-blue","chip-green"]},
  {flag:"🇨🇳",name:"CSC China — Jalur Universitas (Tipe B)",country:"China",level:"S1 / S2 / S3",deadline:"Maret – April",portal:"Website Universitas Masing-masing",status:"Belum Daftar",
   cover:"Full tuition + asrama gratis + asuransi + tunjangan CNY 2.500 (S1) hingga CNY 3.500 (S3) per bulan",
   req:"Pre-Admission Letter dari Profesor adalah KUNCI untuk Tipe B. Sertifikat bahasa (IELTS/HSK). Dokumen kesehatan berlaku 6 bulan.",
   tips:"Email profesor Cina yang relevan dengan research interest kamu. Perkenalkan diri dan tanya apakah mereka menerima mahasiswa internasional. Siapkan VPN sebelum berangkat ke China!",
   tags:["Full Beasiswa","Kontak Profesor Dulu","VPN Penting","4 Tahap Legalisasi"],colors:["chip-red","chip-orange","chip-purple","chip-gold"]},
  {flag:"🇷🇴",name:"MFA Rumania — Kementerian Luar Negeri",country:"Rumania",level:"S1 / S2 / S3",deadline:"April – Juni",portal:"studyinromania.ro",status:"Belum Daftar",
   cover:"Full tuition + asrama + tunjangan bulanan €65-85 (S1) atau €85 (S2/S3). Tidak termasuk tiket pesawat.",
   req:"Nilai rata-rata ijazah minimal 7/10 atau predikat 'Good'. Ini sangat inklusif! Tidak mensyaratkan IELTS, namun kemampuan bahasa Inggris diperlukan untuk wawancara.",
   tips:"Pendaftaran 100% online via studyinromania.ro. Ada 1 tahun kursus bahasa Rumania GRATIS sebelum kuliah. Tidak tersedia untuk Kedokteran, Kedokteran Gigi, Farmasi.",
   tags:["Nilai Min 7/10","1 Th Bahasa Gratis","Full Online","Eropa Timur"],colors:["chip-teal","chip-gold","chip-green","chip-blue"]},
  {flag:"🇦🇿",name:"Heydar Aliyev International Education Grant",country:"Azerbaijan",level:"S1 / S2",deadline:"April – Mei",portal:"SIACAS + Nominasi Kemendikbud",status:"Belum Daftar",
   cover:"Full tuition + 800 AZN/bulan (≈ USD 470) + tiket pesawat PP tahunan + asuransi kesehatan + biaya visa",
   req:"Batas usia S1: di bawah 35 tahun. Indonesia mendapat prioritas sebagai anggota OKI. Tidak ada syarat IELTS resmi.",
   tips:"Daftar melalui dua tahap: (1) nominasi oleh Kemendikbud/Kemenlu Indonesia, (2) pendaftaran online di portal SIACAS. Batas usia fleksibel — sangat cocok jika sudah lulus beberapa tahun.",
   tags:["Prioritas OKI","Usia s/d 35 th","Tunjangan USD 470/bln","PP + Visa"],colors:["chip-purple","chip-gold","chip-teal","chip-green"]},
  {flag:"🇷🇺",name:"Russian Government Quota (Pemerintah Rusia)",country:"Rusia",level:"S1 / S2 / S3",deadline:"Februari – Maret",portal:"Kedutaan Rusia / Rumah Rusia Jakarta",status:"Belum Daftar",
   cover:"Full tuition + kursus bahasa Rusia 1 tahun gratis + asrama (untuk sebagian universitas) + uang saku terbatas",
   req:"Rapor SMA rata-rata minimal 85 (atau 7.5/10). IELTS/TOEFL tidak wajib untuk pendaftaran awal.",
   tips:"Kunjungi Kedutaan Besar Rusia atau Rumah Rusia (Russian House) di Jakarta untuk informasi terbaru. Ada juga jalur 'Open Doors Olympiad' khusus S2/S3 via seleksi portofolio online.",
   tags:["Rapor Min 85","Bahasa Rusia Gratis","Full Tuition","Via Kedutaan"],colors:["chip-red","chip-orange","chip-blue","chip-gold"]},
  {flag:"🇷🇺",name:"Open Doors Olympiad — Rusia (S2/S3)",country:"Rusia",level:"S2 / S3",deadline:"September – Januari",portal:"olymp.hse.ru",status:"Belum Daftar",
   cover:"Bebas biaya kuliah penuh di universitas riset terkemuka Rusia (HSE, MIPT, SPbU, dsb)",
   req:"Portofolio akademik + ujian online berbasis masalah (problem-solving). Tidak ada syarat IELTS minimum.",
   tips:"Cocok untuk kandidat S2/S3 yang memiliki portofolio penelitian meski nilai akademis rata-rata. Seleksi dilakukan sepenuhnya online. Daftar awal lebih baik!",
   tags:["S2/S3 Only","Seleksi Online","Portofolio","Univ. Riset Top"],colors:["chip-red","chip-purple","chip-teal","chip-orange"]},
  {flag:"🇹🇼",name:"ICDF Taiwan Scholarship",country:"Taiwan",level:"S1 / S2",deadline:"Februari – Maret",portal:"icdf.org.tw",status:"Belum Daftar",
   cover:"Full tuition + asrama atau tunjangan akomodasi + NT$15.000 (S1) atau NT$18.000 (S2) per bulan",
   req:"Tersedia hanya untuk 32 program studi tertentu di 22 universitas mitra. Semua program dalam bahasa Inggris.",
   tips:"Pilih program sesuai bidang pembangunan (kesehatan, agrikultur, lingkungan, dll.). TOCFL (Mandarin) tidak wajib tapi sangat menambah nilai aplikasi.",
   tags:["32 Program Studi","22 Univ. Mitra","Bahasa Inggris","NT$15-18rb/bln"],colors:["chip-blue","chip-teal","chip-gold","chip-green"]},
  {flag:"🇹🇼",name:"MOE Taiwan Scholarship",country:"Taiwan",level:"S1 / S2 / S3",deadline:"Februari – Maret",portal:"Kedubes Taiwan / Univ. Masing-masing",status:"Belum Daftar",
   cover:"Tunjangan bulanan NT$15.000-25.000. Biaya kuliah ditanggung sebagian atau penuh tergantung universitas.",
   req:"Daftar mandiri ke universitas Taiwan terlebih dahulu, lalu ajukan beasiswa. TOCFL disarankan (bukan wajib untuk program Inggris).",
   tips:"Lebih fleksibel dalam pemilihan universitas dibanding ICDF. Banyak program teknologi dan teknik tersedia dalam bahasa Inggris.",
   tags:["Bebas Pilih Univ.","TOCFL Disarankan","Fleksibel","Asia Timur"],colors:["chip-blue","chip-purple","chip-gold","chip-teal"]},
  {flag:"🇹🇭",name:"TIPP Thailand — TICA Scholarship",country:"Thailand",level:"S2",deadline:"Februari – Maret",portal:"tica.thaigov.net",status:"Belum Daftar",
   cover:"Full tuition + biaya hidup bulanan + asrama atau tunjangan akomodasi + asuransi kesehatan",
   req:"Gelar S1 dengan IPK baik. Fokus pada bidang pembangunan berkelanjutan, lingkungan, dan manajemen. Tidak mensyaratkan IELTS secara ketat.",
   tips:"TICA = Thailand International Cooperation Agency. Program ini memprioritaskan kandidat dari negara berkembang ASEAN. Cocok untuk bidang agrikultur, lingkungan, public health.",
   tags:["S2 Only","ASEAN Priority","Pembangunan","Full Coverage"],colors:["chip-green","chip-teal","chip-gold","chip-blue"]},
  {flag:"🇮🇳",name:"ICCR India — Indian Council Scholarship",country:"India",level:"S1 / S2 / S3",deadline:"Maret",portal:"Kedutaan India Jakarta / iccr.gov.in",status:"Belum Daftar",
   cover:"Full tuition + tunjangan hidup bulanan + asrama di universitas. Tidak termasuk tiket pesawat.",
   req:"TIDAK PERLU IELTS/TOEFL — diganti dengan esai akademik 500 kata dalam bahasa Inggris. 131+ universitas pilihan!",
   tips:"Ini salah satu beasiswa PALING INKLUSIF yang tidak mensyaratkan IELTS. Esai 500 kata adalah kunci. Pilih universitas IIT, IIM, atau universitas nasional bergengsi untuk meningkatkan nilai CV.",
   tags:["Tanpa IELTS!","131+ Univ","Esai 500 Kata","Asia Selatan"],colors:["chip-gold","chip-orange","chip-red","chip-green"]},
  {flag:"🇧🇳",name:"BDGS Brunei Darussalam Government Scholarship",country:"Brunei",level:"D3 / S1 / S2",deadline:"Januari – Maret",portal:"Kemendikbudristek RI",status:"Belum Daftar",
   cover:"Full tuition + asrama + tunjangan makan tahunan + tunjangan buku tahunan + uang saku bulanan",
   req:"Nilai akademis baik. Tidak ada syarat IELTS minimum yang ketat. Kedekatan budaya dengan Indonesia memudahkan adaptasi.",
   tips:"Daftar melalui Kemendikbudristek Indonesia. Brunei sangat dekat budaya dan bahasa dengan Indonesia. Pilihan bagus untuk kandidat yang khawatir dengan culture shock.",
   tags:["D3/S1/S2","Via Kemendikbud","Dekat Indonesia","Full Coverage"],colors:["chip-gold","chip-teal","chip-green","chip-blue"]},
  {flag:"🇹🇷",name:"Türkiye Bursları — Turkish Government Scholarship",country:"Turki",level:"S1 / S2 / S3",deadline:"Januari – Februari",portal:"turkiyeburslari.gov.tr",status:"Belum Daftar",
   cover:"Full tuition + asrama + uang saku bulanan (TRY 1.700-2.200 S1, TRY 2.200 S2/S3) + tiket pesawat PP + asuransi kesehatan",
   req:"TIDAK WAJIB IELTS/TOEFL untuk pendaftaran! Ada 1 tahun kursus bahasa Turki gratis. Daftar di turkiyeburslari.gov.tr langsung.",
   tips:"Salah satu beasiswa paling populer di Indonesia. Penempatan universitas dilakukan secara otomatis oleh panitia berdasarkan profil. Ikut olimpiade sains tambah nilai, tapi bukan syarat.",
   tags:["Tanpa IELTS!","1 Th Bahasa Turki","Tiket PP","Paling Populer"],colors:["chip-red","chip-orange","chip-gold","chip-purple"]},
];

const EXPENSES = [
  {cat:"Tes IELTS (1-2 kali)",min:4000000,max:7500000,desc:"Rp3.490.000/tes + transport ke lokasi tes (BC atau IDP)"},
  {cat:"Legalisasi & Apostille (5-10 dokumen)",min:1500000,max:3000000,desc:"Rp150.000/dokumen via AHU Online (ahu.go.id)"},
  {cat:"Terjemahan Tersumpah (5-10 dokumen)",min:1000000,max:3000000,desc:"Rp150.000 – 350.000/halaman dari Penerjemah Tersumpah resmi"},
  {cat:"Medical Check-Up Lengkap",min:1500000,max:2500000,desc:"HIV, Hep B/C, Rontgen, EKG, Bebas Narkoba — di RS Pemerintah"},
  {cat:"Paspor 10 Tahun (jika belum punya)",min:350000,max:350000,desc:"Di kantor Imigrasi atau online via M-Paspor"},
  {cat:"Visa Studi (tergantung negara)",min:500000,max:3000000,desc:"Beberapa beasiswa menanggung biaya visa. Cek detail beasiswamu."},
  {cat:"Foto Resmi & Percetakan Dokumen",min:200000,max:500000,desc:"Foto 4x6 studio, print dokumen, map plastik, bolak-balik fotokopi"},
  {cat:"⚠️ Dana Darurat Bulan Pertama",min:10000000,max:10000000,desc:"PALING KRUSIAL! Stipend baru cair 4-8 minggu setelah tiba."},
  {cat:"Buffer / Biaya Tak Terduga (10%)",min:1000000,max:2000000,desc:"Cadangan untuk biaya yang tidak terduga selama proses"},
];

const HUSTLES = [
  {icon:"✍️",title:"Freelance Writing & Social Media Admin",range:"Rp500rb – 2jt/klien",desc:"Kelola konten Instagram atau TikTok untuk UMKM lokal. 2-4 klien = Rp1-8 juta/bulan. Bisa dikerjakan remote dari mana saja.",platform:"Fastwork, Projects.co.id, Instagram direct"},
  {icon:"🖥️",title:"Virtual Assistant (VA) Klien Internasional",range:"Rp3jt – 5jt/bulan",desc:"Tangani tugas administratif jarak jauh untuk profesional atau perusahaan luar negeri. Modal utama: bahasa Inggris aktif. Latihan IELTS juga meningkatkan skill ini!",platform:"Upwork, Fiverr, LinkedIn"},
  {icon:"📖",title:"Tutor Online / Guru Les Privat",range:"Rp80rb – 150rb/jam",desc:"Ajar mata pelajaran SMP/SMA atau bahasa Inggris. 10-15 jam/minggu = Rp800rb-2,25jt. Jam fleksibel.",platform:"Ruangguru, Zenius, Quipper, atau mandiri via WA"},
  {icon:"🛵",title:"Driver Online / Kurir (Akhir Pekan)",range:"Rp300rb – 600rb/hari",desc:"Manfaatkan waktu kosong di akhir pekan atau malam hari. Tidak butuh modal besar. Fleksibel sesuai jadwal.",platform:"Gojek, Grab, ShopeeFood"},
  {icon:"⌨️",title:"Data Entry & Pengetikan Freelance",range:"Rp1,5jt – 3jt/bulan",desc:"Cocok untuk mahasiswa karena sangat fleksibel. Bisa dikerjakan kapan saja dan di mana saja.",platform:"Projects.co.id, Freelancer.com, Sribulancer"},
  {icon:"🎨",title:"Desain Grafis & Konten Visual",range:"Rp200rb – 2jt/proyek",desc:"Jika punya skill Canva atau Adobe, buat konten visual untuk UMKM atau personal brand. Permintaan sangat tinggi.",platform:"Fiverr, 99designs, Freelancer"},
];

const COUNTRIES = [
  {flag:"🇭🇺",name:"Hungaria",capital:"Budapest",lang:"Hungaria (Inggris tersedia)",currency:"Forint (HUF)",biaya:"Rp4-7jt/bulan (lebih murah dari Jakarta!)",iklim:"Empat musim. Musim dingin bisa -10°C hingga -15°C.",kuliner:"Paprikash, Goulash — daging banyak. Makanan halal tersedia di Budapest.",tips:"Beli baju hangat tebal sebelum berangkat. Kota terkenal: Debrecen, Miskolc, Pécs.",univ:"University of Debrecen, Budapest Metropolitan Univ, Óbuda Univ"},
  {flag:"🇨🇳",name:"China",capital:"Beijing / Shanghai / kota terpilih",lang:"Mandarin (HSK penting). Inggris terbatas di luar kota besar.",currency:"Yuan CNY",biaya:"Rp4-9jt/bulan tergantung kota (Beijing/Shanghai mahal)",iklim:"Sangat bervariasi. Beijing sangat dingin di musim dingin, panas di musim panas.",kuliner:"Sangat beragam. Halal tersedia di area Muslim, tapi butuh usaha.",tips:"⚠️ Siapkan VPN SEBELUM tiba! Google, WhatsApp, IG, YouTube diblokir. Alipay/WeChat Pay wajib.",univ:"Tsinghua, PKU, Fudan, Zhejiang, SJTU, BUAA"},
  {flag:"🇷🇴",name:"Rumania",capital:"Bucharest",lang:"Rumania (1 th kursus gratis) + Inggris tersedia",currency:"Leu RON",biaya:"Rp3-5jt/bulan — salah satu yang termurah di Eropa!",iklim:"Empat musim. Musim dingin -5°C hingga -15°C.",kuliner:"Murtaur, Mici, Sarmale — berbasis daging. Makanan halal tersedia di kota besar.",tips:"Bergabunglah dengan komunitas mahasiswa Indonesia. Bucharest punya kehidupan malam yang seru.",univ:"Univ. of Bucharest, USAMVB, Univ. Babes-Bolyai Cluj"},
  {flag:"🇦🇿",name:"Azerbaijan",capital:"Baku",lang:"Azerbaijan (ada kursus). Inggris tersedia di univ.",currency:"Manat AZN",biaya:"Rp5-8jt/bulan. Tunjangan USD 470 biasanya cukup.",iklim:"Empat musim. Musim dingin tidak setahu Rusia. -5°C di musim dingin.",kuliner:"Masakan halal! Plov, Dolma, Kebab — sangat ramah Muslim.",tips:"Negara mayoritas Muslim. Tidak ada masalah halal. Baku adalah kota modern & aman.",univ:"Azerbaijan State University, Baku State Univ., ADA University"},
  {flag:"🇷🇺",name:"Rusia",capital:"Moscow / Saint Petersburg / dll.",lang:"Rusia (1 th kursus gratis). Inggris sangat terbatas.",currency:"Ruble RUB",biaya:"Rp5-10jt/bulan tergantung kota",iklim:"Musim dingin sangat ekstrem! Moscow bisa -20°C hingga -35°C.",kuliner:"Sup, daging, roti. Makanan halal tersedia di komunitas Muslim.",tips:"Siapkan mental untuk musim dingin. Beli pakaian winter berkualitas. VPN juga disarankan.",univ:"MGU, MIPT, HSE, SPbU, MSTU Bauman"},
  {flag:"🇹🇼",name:"Taiwan",capital:"Taipei",lang:"Mandarin (umum). Banyak program S2/S3 full bahasa Inggris.",currency:"New Taiwan Dollar NTD",biaya:"Rp7-12jt/bulan. Tunjangan NT$15-18rb biasanya cukup.",iklim:"Tropis/subtropis. Mirip Indonesia. Tidak ada musim dingin ekstrem.",kuliner:"Beragam! Nightmarket terkenal. Halal certified tersedia di kota besar.",tips:"Sistem transportasi luar biasa. MRT Taipei sangat nyaman. Bubble tea original!",univ:"NTU, NCKU, NTHU, NYCU, NSYSU"},
  {flag:"🇹🇭",name:"Thailand",capital:"Bangkok / kota terpilih",lang:"Thai (terbatas). Program TICA menggunakan bahasa Inggris.",currency:"Baht THB",biaya:"Rp4-7jt/bulan. Lebih terjangkau dari Taiwan.",iklim:"Tropis. Mirip Indonesia. Tidak ada musim dingin.",kuliner:"Tom Yum, Pad Thai, Mango Rice. Halal tersedia khususnya di selatan Thailand.",tips:"Paling mudah adaptasi untuk orang Indonesia. Budaya dan iklim mirip.",univ:"Mahidol, Chulalongkorn, KU, AIT Bangkok"},
  {flag:"🇮🇳",name:"India",capital:"New Delhi / tergantung universitas",lang:"Inggris tersedia di universitas top. Hindi di luar kampus.",currency:"Rupee INR",biaya:"Rp3-6jt/bulan. Sangat terjangkau!",iklim:"Beragam — dari tropis hingga Himalaya. Iklim ekstrem di beberapa wilayah.",kuliner:"Makanan vegetarian melimpah. Halal tersedia. Rempah-rempah kuat.",tips:"Pilih IIT atau IIM untuk networking terbaik. Banyak komunitas Indonesia di sana.",univ:"IIT Bombay, IIT Delhi, IIM, JNU, Univ. of Delhi"},
  {flag:"🇧🇳",name:"Brunei",capital:"Bandar Seri Begawan",lang:"Melayu + Inggris. Sangat mudah untuk orang Indonesia!",currency:"Dolar Brunei BND",biaya:"Rp6-9jt/bulan. Mahal tapi stipend biasanya cukup.",iklim:"Tropis. Sama seperti Indonesia.",kuliner:"Makanan halal EVERYWHERE. Ambuyat, Nasi Katok — mirip masakan Melayu.",tips:"Negara paling mudah adaptasi. Bahasa, budaya, makanan mirip Indonesia.",univ:"Universiti Brunei Darussalam (UBD), Univ. Islam Sultan Sharif Ali"},
  {flag:"🇹🇷",name:"Turki",capital:"Ankara / Istanbul",lang:"Turki (1 th kursus gratis). Inggris cukup tersedia di univ.",currency:"Lira TRY",biaya:"Rp4-8jt/bulan. Nilai Lira fluktuatif, pastikan cek terbaru.",iklim:"Empat musim. Ankara dingin (-10°C musim dingin), Istanbul lebih moderat.",kuliner:"Makanan halal! Kebab, Baklava, Meze — surga bagi Muslim!",tips:"Turki jembatan Eropa-Asia. Nilai historis dan budaya sangat kaya. Komunitas Indonesia besar.",univ:"Bogazici Univ, METU, Istanbul Univ, Bilkent, Hacettepe"},
];

const TIPS_DATA = [
  {icon:"🎯",title:"Strategi Kandidat Tanpa Prestasi Olimpiade",content:[
    "Ketiadaan medali olimpiade BUKAN akhir dari segalanya. Beasiswa dari Hungaria, Rumania, Azerbaijan, Brunei, India (ICCR), dan Turki tidak mensyaratkan prestasi kompetisi akademik.",
    "Negara-negara ini lebih menghargai: (1) Motivation Letter yang autentik dan visioner, (2) Relevansi program studi dengan kebutuhan pembangunan Indonesia, (3) Bukti kemandirian dan ketangguhan pribadi.",
    "Skor IELTS 7.0 akan menjadi 'prestasi' pengganti yang sangat kuat. Kandidat dengan nilai akademis rata-rata tapi IELTS 7.0 jauh lebih kompetitif dari kandidat berprestasi tanpa bukti kemampuan bahasa.",
    "Pengalaman kerja dan kegiatan sosial/relawan juga dihitung sebagai bukti kematangan dan kemampuan adaptasi.",
  ]},
  {icon:"✍️",title:"Formula Menulis Motivation Letter yang Menang",content:[
    "PARAGRAF 1 — Latar Belakang: Siapa kamu? Dari mana? Apa yang telah kamu pelajari dan lakukan? Buat menarik dan personal.",
    "PARAGRAF 2 — Masalah: Identifikasi masalah konkret di Indonesia yang relevan dengan bidang studi yang kamu pilih. Tunjukkan kepedulianmu yang tulus.",
    "PARAGRAF 3 — Mengapa Studi Ini: Jelaskan secara spesifik bagaimana program studi yang kamu pilih akan memberi kamu tools untuk memecahkan masalah di Paragraf 2.",
    "PARAGRAF 4 — Mengapa Negara Ini: Jelaskan secara spesifik kenapa negara TERSEBUT (bukan sembarang negara). Riset keunggulan akademik, industri, atau hubungan bilateral dengan Indonesia.",
    "PARAGRAF 5 — Rencana Kontribusi: Apa yang akan kamu lakukan setelah kembali ke Indonesia? Konkret, terukur, dan ambisius namun realistis.",
    "TIPS KRUSIAL: Hindari kalimat klise seperti 'Since I was a child, I dreamed of...' atau 'I am very passionate about...'. Buat SPESIFIK dan BERBEDA.",
  ]},
  {icon:"📄",title:"Tips Surat Rekomendasi yang Kuat",content:[
    "Minta dari dosen atau atasan yang BENAR-BENAR MENGENAL kamu — bukan dari pejabat tinggi yang tidak tahu siapa kamu.",
    "Berikan 'briefing' kepada dosen/atasan: ceritakan program beasiswa yang kamu lamar, dan minta mereka menyebutkan contoh konkret perilaku atau prestasi spesifik.",
    "Surat rekomendasi yang kuat menjawab: Bagaimana performa akademis/kerja kandidat? Apa karakter uniknya? Mengapa dia cocok untuk program ini?",
    "Berikan cukup waktu — minimal 3-4 minggu sebelum deadline — jangan meminta mendadak.",
    "Kirim reminder yang sopan 1 minggu sebelum deadline.",
  ]},
  {icon:"💡",title:"Strategi Pre-Admission Letter untuk CSC China",content:[
    "Pre-Admission Letter (PAL) dari profesor adalah 'kunci emas' untuk lolos CSC Tipe B bagi kandidat dengan profil rata-rata.",
    "Cara mendapatkannya: (1) Cari profesor yang bidang penelitiannya relevan dengan kamu di website universitas China tujuan.",
    "Email template yang efektif: Perkenalkan diri singkat, sebutkan minat penelitian yang SPESIFIK sesuai research mereka, lampirkan CV dan transkrip, tanyakan apakah mereka menerima mahasiswa S2/S3 internasional.",
    "Kirim email ke 5-10 profesor berbeda. Tidak perlu malu. Ini adalah praktik yang sangat umum dan diterima di akademia internasional.",
    "Jika seorang profesor membalas positif, minta secara sopan surat Pre-Admission Letter untuk keperluan beasiswa.",
  ]},
  {icon:"💰",title:"Rencana Keuangan: Rp30 Juta dalam 12 Bulan",content:[
    "Formula sederhana: Rp30.000.000 ÷ 12 bulan = Rp2.500.000/bulan yang harus ditabung konsisten.",
    "Instrumen keuangan yang disarankan: Reksa Dana Pasar Uang (imbal hasil 4-6%/tahun, bisa dicairkan kapan saja) atau Tabungan Berjangka dengan fitur auto-debet.",
    "Strategi 'Pay Yourself First': Langsung transfer Rp2.500.000 ke rekening tabungan khusus di hari gajian, sebelum pengeluaran apapun.",
    "DANA DARURAT Rp10 JUTA adalah yang paling krusial. Simpan terpisah, jangan disentuh. Ini adalah 'nafas' kamu di bulan pertama ketika stipend belum cair.",
    "Lacak pengeluaran harian selama 1-2 bulan pertama untuk identifikasi mana yang bisa dipotong.",
  ]},
];

// ═══════════════════════ STATE ═══════════════════════
const state = {
  ielts: JSON.parse(localStorage.getItem('ielts_checks')||'{}'),
  docs:  JSON.parse(localStorage.getItem('doc_checks')||'{}'),
  sch:   JSON.parse(localStorage.getItem('sch_status')||'{}'),
  fin:   JSON.parse(localStorage.getItem('fin_data')||'{}'),
  exp:   JSON.parse(localStorage.getItem('exp_done')||'{}'),
  notes: JSON.parse(localStorage.getItem('notes')||'[]'),
};
function save(key){localStorage.setItem(key,JSON.stringify(state[key]))}

// ═══════════════════════ RENDER ═══════════════════════
function renderIELTS(){
  const el=document.getElementById('ielts-checklist');
  let total=0,done=0,html='';
  IELTS_PHASES.forEach((ph,pi)=>{
    let pdone=0;
    let items='';
    ph.sessions.forEach((s,si)=>{
      const key=`${pi}-${si}`;
      const checked=state.ielts[key];
      total++; if(checked)done++;pdone+=checked?1:0;
      items+=`<div class="check-item ${checked?'done':''}" onclick="toggleIELTS('${key}',this)">
        <div class="check-box"><svg viewBox="0 0 12 12"><polyline points="1,6 4,9 11,2"/></svg></div>
        <div>
          <div class="check-label">${s.t}</div>
          ${s.tip?`<div class="check-meta">💡 ${s.tip}</div>`:''}
        </div>
        <div class="check-week">${s.w}</div>
      </div>`;
    });
    html+=`<div class="check-phase">
      <div class="check-phase-header" onclick="togglePhase(this)">
        <span class="phase-icon">${ph.icon}</span>
        <div>
          <div class="phase-title">${ph.title}</div>
          <div style="font-size:0.75rem;color:var(--text-dim)">${ph.week}</div>
        </div>
        <span class="phase-counter" style="border:1px solid ${ph.color};color:${ph.color}">${pdone}/${ph.sessions.length}</span>
        <span class="phase-toggle">▼</span>
      </div>
      <div class="phase-body">${items}</div>
    </div>`;
  });
  el.innerHTML=html;
  updateIELTSProgress(done,total);
}

function toggleIELTS(key,el){
  state.ielts[key]=!state.ielts[key];
  save('ielts');
  el.classList.toggle('done',state.ielts[key]);
  renderIELTS(); updateDashboard(); toast('✅ Progress IELTS diperbarui!');
}
function togglePhase(header){
  const ph=header.parentElement;
  ph.classList.toggle('phase-open');
}
function updateIELTSProgress(done,total){
  const pct=total?Math.round(done/total*100):0;
  document.getElementById('ielts-prog-label').textContent=`${done} / ${total} sesi (${pct}%)`;
  document.getElementById('ielts-prog-bar').style.width=pct+'%';
  document.getElementById('badge-ielts').textContent=pct+'%';
}

function renderDocs(){
  const el=document.getElementById('dok-checklist');
  let total=0,done=0,html='';
  DOCS.forEach((sec,si)=>{
    let items='';let sdone=0;
    sec.items.forEach((d,di)=>{
      const key=`${si}-${di}`;const checked=state.docs[key];
      total++;if(checked)done++;sdone+=checked?1:0;
      items+=`<div class="check-item ${checked?'done':''}" onclick="toggleDoc('${key}',this)">
        <div class="check-box"><svg viewBox="0 0 12 12"><polyline points="1,6 4,9 11,2"/></svg></div>
        <div style="flex:1">
          <div class="check-label">${d.name}</div>
          <div class="check-meta">🏷️ ${d.leg} &nbsp;·&nbsp; 🌍 ${d.country} &nbsp;·&nbsp; 💸 ${d.est}</div>
        </div>
      </div>`;
    });
    html+=`<div class="check-phase">
      <div class="check-phase-header" onclick="togglePhase(this)">
        <span class="phase-icon">📁</span>
        <div class="phase-title">${sec.section}</div>
        <span class="phase-counter" style="border:1px solid ${sec.color};color:${sec.color}">${sdone}/${sec.items.length}</span>
        <span class="phase-toggle">▼</span>
      </div>
      <div class="phase-body">${items}</div>
    </div>`;
  });
  el.innerHTML=html;
  const pct=total?Math.round(done/total*100):0;
  document.getElementById('dok-prog-label').textContent=`${done} / ${total} dokumen (${pct}%)`;
  document.getElementById('dok-prog-bar').style.width=pct+'%';
  document.getElementById('badge-dok').textContent=pct+'%';
  const ds=`${done} dari ${total} dokumen`;
  if(document.getElementById('dash-dok-sub')) document.getElementById('dash-dok-sub').textContent=ds;
}
function toggleDoc(key,el){
  state.docs[key]=!state.docs[key];save('docs');
  renderDocs();updateDashboard();toast('📋 Status dokumen diperbarui!');
}

function renderScholarships(){
  const el=document.getElementById('sch-grid');
  el.innerHTML=SCHOLARSHIPS.map((s,i)=>{
    const status=state.sch[i]||s.status;
    const statusColor={
      'Belum Daftar':'color:var(--text-dim)',
      'Sedang Riset':'color:var(--blue)',
      'Sedang Proses':'color:var(--orange)',
      'Dilamar':'color:var(--gold)',
      'Lolos':'color:var(--green)',
      'Ditolak':'color:var(--red)',
    }[status]||'';
    const tags=s.tags.map((t,ti)=>`<span class="sch-tag ${s.colors[ti]||'chip-teal'}">${t}</span>`).join('');
    return `<div class="sch-card">
      <div class="sch-header">
        <div class="sch-flag">${s.flag}</div>
        <div class="sch-info"><h3>${s.name}</h3><p>${s.country} · ${s.level}</p></div>
      </div>
      <div class="sch-deadline">⏰ Deadline: ${s.deadline}</div>
      <div style="font-size:0.8rem;color:var(--text-dim)"><strong style="color:var(--text)">💰 Coverage:</strong> ${s.cover}</div>
      <div style="font-size:0.8rem;color:var(--text-dim)"><strong style="color:var(--text)">📋 Syarat:</strong> ${s.req}</div>
      <div style="font-size:0.8rem;color:var(--teal)"><strong>💡 Tips:</strong> ${s.tips}</div>
      <div class="sch-tags">${tags}</div>
      <div>
        <div style="font-size:0.75rem;color:var(--text-dim);margin-bottom:6px;text-transform:uppercase;letter-spacing:.05em;font-weight:600">Status Pendaftaranmu</div>
        <select class="sch-status-select" style="${statusColor}" onchange="updateSchStatus(${i},this.value,this)">
          <option ${status=='Belum Daftar'?'selected':''}>Belum Daftar</option>
          <option ${status=='Sedang Riset'?'selected':''}>Sedang Riset</option>
          <option ${status=='Sedang Proses'?'selected':''}>Sedang Proses</option>
          <option ${status=='Dilamar'?'selected':''}>Dilamar</option>
          <option ${status=='Lolos'?'selected':''}>Lolos ✅</option>
          <option ${status=='Ditolak'?'selected':''}>Ditolak</option>
        </select>
      </div>
      <div class="info-row" style="border:none;padding:4px 0;font-size:0.78rem"><span class="info-key">🌐 Portal:</span><span class="info-val" style="color:var(--teal);font-size:0.78rem">${s.portal}</span></div>
    </div>`;
  }).join('');
}
function updateSchStatus(i,val,sel){
  state.sch[i]=val;save('sch');
  const colors={'Belum Daftar':'color:var(--text-dim)','Sedang Riset':'color:var(--blue)','Sedang Proses':'color:var(--orange)','Dilamar':'color:var(--gold)','Lolos':'color:var(--green)','Ditolak':'color:var(--red)'};
  sel.style=colors[val]||'';
  updateDashboard();toast('🎓 Status beasiswa diperbarui!');
}

function renderFinance(){
  const months=['Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember'];
  const tbody=document.getElementById('fin-tbody');
  tbody.innerHTML=months.map((m,i)=>{
    const d=state.fin[i]||{};
    return `<tr>
      <td style="font-weight:500">${m}</td>
      <td><input class="finance-input" type="text" placeholder="0" value="${d.income||''}" oninput="saveFin(${i},'income',this.value)" style="width:140px"></td>
      <td><input class="finance-input" type="text" placeholder="0" value="${d.save||''}" oninput="saveFin(${i},'save',this.value)" style="width:140px;color:var(--gold)"></td>
      <td><input class="finance-input" type="text" placeholder="0" value="${d.exp||''}" oninput="saveFin(${i},'exp',this.value)" style="width:140px;color:var(--red)"></td>
      <td><input class="finance-input" type="text" placeholder="0" value="${d.hustle||''}" oninput="saveFin(${i},'hustle',this.value)" style="width:140px;color:var(--green)"></td>
      <td><input class="finance-input" type="text" placeholder="Catatan..." value="${d.note||''}" oninput="saveFin(${i},'note',this.value)" style="width:160px"></td>
    </tr>`;
  }).join('');
  updateFinTotals();

  // Expense table
  const etbody=document.getElementById('expense-tbody');
  etbody.innerHTML=EXPENSES.map((e,i)=>{
    const done=state.exp[i];
    return `<tr>
      <td class="td-center" style="color:var(--text-dim)">${i+1}</td>
      <td style="font-weight:${e.cat.includes('⚠️')?700:400};color:${e.cat.includes('⚠️')?'var(--gold)':'inherit'}">${e.cat}</td>
      <td style="color:var(--teal)">${fmtRp(e.min)}</td>
      <td style="color:var(--orange)">${fmtRp(e.max)}</td>
      <td class="td-center">
        <span onclick="toggleExp(${i},this)" style="cursor:pointer;font-size:1.3rem">${done?'✅':'⬜'}</span>
      </td>
      <td style="color:var(--text-dim);font-size:0.82rem">${e.desc}</td>
    </tr>`;
  }).join('');

  // Hustle grid
  document.getElementById('hustle-grid').innerHTML=HUSTLES.map(h=>`
    <div class="sch-card">
      <div style="font-size:2rem">${h.icon}</div>
      <h3 style="font-size:0.95rem;font-weight:700">${h.title}</h3>
      <div style="font-size:1.1rem;font-weight:700;color:var(--gold)">${h.range}</div>
      <div style="font-size:0.83rem;color:var(--text-dim);line-height:1.6">${h.desc}</div>
      <div style="font-size:0.78rem;color:var(--teal)">📱 Platform: ${h.platform}</div>
    </div>`).join('');
}
function toggleExp(i,el){
  state.exp[i]=!state.exp[i];save('exp');
  el.textContent=state.exp[i]?'✅':'⬜';
  toast('💰 Status biaya diperbarui!');
}
function saveFin(i,field,val){
  if(!state.fin[i])state.fin[i]={};
  state.fin[i][field]=val;
  save('fin');
  updateFinTotals();
}
function updateFinTotals(){
  let totInc=0,totSave=0,totExp=0,totHus=0,count=0;
  for(let i=0;i<12;i++){
    const d=state.fin[i]||{};
    const inc=parseNum(d.income),sv=parseNum(d.save),ex=parseNum(d.exp),hu=parseNum(d.hustle);
    totInc+=inc;totSave+=sv;totExp+=ex;totHus+=hu;
    if(sv>0)count++;
  }
  document.getElementById('fin-tot-income').textContent=fmtRp(totInc);
  document.getElementById('fin-tot-save').textContent=fmtRp(totSave);
  document.getElementById('fin-tot-exp').textContent=fmtRp(totExp);
  document.getElementById('fin-tot-hustle').textContent=fmtRp(totHus);
  document.getElementById('fin-collected').textContent=fmtRp(totSave);
  const pct=Math.min(100,Math.round(totSave/30000000*100));
  document.getElementById('fin-bar').style.width=pct+'%';
  const avg=count>0?Math.round(totSave/count):0;
  document.getElementById('fin-avg').textContent=fmtRp(avg);
  document.getElementById('fin-avg-sub').textContent=`Rata-rata dari ${count} bulan`;
  document.getElementById('fin-avg-bar').style.width=Math.min(100,avg/2500000*100)+'%';
  const remaining=30000000-totSave;
  const eta=avg>0?Math.ceil(remaining/avg):0;
  document.getElementById('fin-eta').textContent=eta>0?`~${eta} bln`:'Tercapai! 🎉';
  updateDashboard();
}
function parseNum(v){if(!v)return 0;return parseInt(v.toString().replace(/[^0-9]/g,''))||0;}
function fmtRp(n){if(n>=1000000)return'Rp'+(n/1000000).toFixed(n%1000000===0?0:1)+'jt';if(n>=1000)return'Rp'+(n/1000).toFixed(0)+'rb';return'Rp'+n;}
function fmtRpFull(n){return'Rp'+n.toLocaleString('id-ID')}

function renderNegara(){
  document.getElementById('negara-grid').innerHTML=`<div class="sch-grid">${COUNTRIES.map(c=>`
    <div class="sch-card">
      <div style="font-size:2.5rem;margin-bottom:4px">${c.flag}</div>
      <h3 style="font-size:1.1rem;font-weight:800">${c.name}</h3>
      <div style="font-size:0.78rem;color:var(--text-dim)">🏛️ ${c.capital}</div>
      <div class="info-box" style="padding:12px;gap:0">
        <div class="info-row" style="padding:7px 0"><span class="info-key">🗣️ Bahasa</span><span class="info-val" style="font-size:0.82rem">${c.lang}</span></div>
        <div class="info-row" style="padding:7px 0"><span class="info-key">💵 Biaya Hidup</span><span class="info-val" style="color:var(--gold);font-size:0.82rem">${c.biaya}</span></div>
        <div class="info-row" style="padding:7px 0"><span class="info-key">🌡️ Iklim</span><span class="info-val" style="font-size:0.82rem;text-align:right">${c.iklim}</span></div>
        <div class="info-row" style="padding:7px 0"><span class="info-key">🍽️ Kuliner</span><span class="info-val" style="font-size:0.82rem;text-align:right">${c.kuliner}</span></div>
        <div class="info-row" style="padding:7px 0;border:none"><span class="info-key">🏫 Univ. Populer</span><span class="info-val" style="color:var(--teal);font-size:0.78rem;text-align:right">${c.univ}</span></div>
      </div>
      <div style="font-size:0.82rem;background:rgba(245,166,35,.08);border:1px solid rgba(245,166,35,.2);border-radius:10px;padding:10px;color:var(--text-dim)">💡 ${c.tips}</div>
    </div>`).join('')}</div>`;
}

function renderTips(){
  document.getElementById('tips-content').innerHTML=TIPS_DATA.map(t=>`
    <div class="check-phase" style="margin-bottom:16px">
      <div class="check-phase-header phase-open" onclick="togglePhase(this)">
        <span class="phase-icon">${t.icon}</span>
        <div class="phase-title" style="font-size:1rem">${t.title}</div>
        <span class="phase-toggle">▼</span>
      </div>
      <div class="phase-body phase-open" style="display:block">
        ${t.content.map((c,i)=>`<div style="display:flex;gap:12px;padding:10px 12px;border-radius:10px;margin-bottom:6px;background:var(--surface2);border:1px solid var(--border)">
          <span style="color:var(--gold);font-weight:700;font-size:0.85rem;min-width:20px">${i+1}.</span>
          <p style="font-size:0.87rem;color:var(--text-dim);line-height:1.7">${c}</p>
        </div>`).join('')}
      </div>
    </div>`).join('');
}

function renderNotes(){
  const list=document.getElementById('notes-list');
  if(!state.notes.length){list.innerHTML='<div style="color:var(--text-dim);font-size:0.87rem;text-align:center;padding:40px">Belum ada catatan. Tulis catatan pertamamu! 📝</div>';return;}
  document.getElementById('note-count').textContent=state.notes.length+' catatan';
  list.innerHTML=state.notes.map((n,i)=>`<div class="note-item">
    <div class="note-item-header">
      <div class="note-item-title">${n.title||'Catatan'}</div>
      <div style="display:flex;gap:8px">
        <button class="note-item-del" onclick="editNote(${i})" title="Edit">✏️</button>
        <button class="note-item-del" onclick="delNote(${i})" title="Hapus">🗑️</button>
      </div>
    </div>
    <div class="note-item-body">${(n.body||'').replace(/\n/g,'<br>')}</div>
    <div class="note-item-date">${n.date||''}</div>
  </div>`).join('');
}
function addNote(){
  const title=document.getElementById('note-title').value.trim();
  const body=document.getElementById('note-body').value.trim();
  if(!title&&!body)return;
  state.notes.unshift({title,body,date:new Date().toLocaleDateString('id-ID',{day:'numeric',month:'long',year:'numeric'})});
  save('notes');
  document.getElementById('note-title').value='';
  document.getElementById('note-body').value='';
  renderNotes();toast('📝 Catatan tersimpan!');
}
function delNote(i){state.notes.splice(i,1);save('notes');renderNotes();toast('🗑️ Catatan dihapus');}
function editNote(i){
  const n=state.notes[i];
  document.getElementById('edit-title').value=n.title||'';
  document.getElementById('edit-body').value=n.body||'';
  document.getElementById('edit-idx').value=i;
  document.getElementById('modal-overlay').classList.remove('hidden');
}
function saveEdit(){
  const i=parseInt(document.getElementById('edit-idx').value);
  state.notes[i].title=document.getElementById('edit-title').value;
  state.notes[i].body=document.getElementById('edit-body').value;
  save('notes');closeModal();renderNotes();toast('✏️ Catatan diperbarui!');
}
function closeModal(e){
  if(e&&e.target!==document.getElementById('modal-overlay'))return;
  document.getElementById('modal-overlay').classList.add('hidden');
}

function calcScore(){
  const vals=['sc-l','sc-r','sc-w','sc-s'].map(id=>parseFloat(document.getElementById(id).value)||0);
  const raw=vals.reduce((a,b)=>a+b,0)/4;
  const banded=Math.round(raw*2)/2;
  document.getElementById('sc-overall').textContent=banded.toFixed(1);
  const gap=(banded-7).toFixed(1);
  const gapEl=document.getElementById('sc-gap');
  gapEl.textContent=gap>=0?'+'+gap:gap;
  gapEl.style.color=gap>=0?'var(--green)':'var(--red)';
  const statusEl=document.getElementById('sc-status');
  if(banded>=7){statusEl.textContent='✅ Target Tercapai!';statusEl.style.color='var(--green)'}
  else if(banded>=6){statusEl.textContent='🔥 Hampir Sampai!';statusEl.style.color='var(--orange)'}
  else{statusEl.textContent='💪 Terus Berlatih';statusEl.style.color='var(--red)'}
}

function updateDashboard(){
  // IELTS
  const ieltsTotal=IELTS_PHASES.reduce((a,p)=>a+p.sessions.length,0);
  const ieltsDone=Object.values(state.ielts).filter(Boolean).length;
  const ieltsPct=ieltsTotal?Math.round(ieltsDone/ieltsTotal*100):0;
  document.getElementById('dash-ielts-pct').textContent=ieltsPct+'%';
  document.getElementById('dash-ielts-sub').textContent=`${ieltsDone} dari ${ieltsTotal} sesi`;
  document.getElementById('dash-ielts-bar').style.width=ieltsPct+'%';
  // Finance
  let totSave=0;for(let i=0;i<12;i++){totSave+=parseNum((state.fin[i]||{}).save);}
  const danaPct=Math.min(100,Math.round(totSave/30000000*100));
  document.getElementById('dash-dana').textContent=fmtRp(totSave);
  document.getElementById('dash-dana-bar').style.width=danaPct+'%';
  // Docs
  const docTotal=DOCS.reduce((a,d)=>a+d.items.length,0);
  const docDone=Object.values(state.docs).filter(Boolean).length;
  const docPct=docTotal?Math.round(docDone/docTotal*100):0;
  document.getElementById('dash-dok-pct').textContent=docPct+'%';
  document.getElementById('dash-dok-sub').textContent=`${docDone} dari ${docTotal} dokumen`;
  document.getElementById('dash-dok-bar').style.width=docPct+'%';
  // Scholarship
  const schActive=Object.values(state.sch).filter(v=>['Sedang Proses','Dilamar','Lolos'].includes(v)).length;
  document.getElementById('dash-sch').textContent=schActive;
  document.getElementById('dash-sch-bar').style.width=Math.min(100,schActive/12*100)+'%';
  // Sidebar
  const overall=Math.round((ieltsPct+danaPct+docPct)/3);
  document.getElementById('sidebar-pct').textContent=overall+'%';
  document.getElementById('sidebar-bar').style.width=overall+'%';
  document.getElementById('badge-ielts').textContent=ieltsPct+'%';
  document.getElementById('badge-dok').textContent=docPct+'%';
}

// NAV
function showPage(id,navEl){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  if(navEl)navEl.classList.add('active');
}

// TOAST
let toastTimer;
function toast(msg){
  const t=document.getElementById('toast');
  const m=document.getElementById('toast-msg');
  m.textContent=msg;t.classList.remove('hidden');
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>t.classList.add('hidden'),2200);
}

// INIT
document.addEventListener('DOMContentLoaded',()=>{
  renderIELTS();renderDocs();renderScholarships();
  renderFinance();renderNegara();renderTips();renderNotes();
  updateDashboard();
});
</script>
</body></html>
