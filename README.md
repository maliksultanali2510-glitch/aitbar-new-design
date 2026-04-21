
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Aetbar – Hire Verified Home Workers in Pakistan</title>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
:root{
  --g:#1D9E75;--gd:#0F6E56;--gl:#E1F5EE;--gll:#f0faf6;
  --pur:#7C3AED;--purl:#EDE9FE;
  --ora:#F97316;--oral:#FFF0E6;
  --pin:#EC4899;--pinl:#FCE7F3;
  --amb:#EF9F27;--ambl:#FAEEDA;
  --red:#E24B4A;--redl:#FCEBEB;
  --blu:#378ADD;--blul:#E6F1FB;
  --teal:#0EA5E9;--teall:#E0F2FE;
  --bg:#F7F8FA;--card:#fff;--border:#E8EAED;
  --txt:#111;--txt2:#555;--txt3:#999;
  --sidebar:240px;
}
html{scroll-behavior:smooth}
body{font-family:'Plus Jakarta Sans',sans-serif;background:var(--bg);color:var(--txt)}
.view{display:none!important}.view.active{display:block!important}

/* ══ TOAST ══════════════════════════════════════════════════════ */
.toast{position:fixed;bottom:28px;right:28px;padding:13px 22px;border-radius:14px;font-size:13px;font-weight:700;z-index:9999;transform:translateY(90px);transition:transform .3s cubic-bezier(.34,1.56,.64,1);box-shadow:0 8px 30px rgba(0,0,0,.2);background:#111;color:#fff}
.toast.show{transform:translateY(0)}
.toast.success{background:var(--g)}.toast.error{background:var(--red)}.toast.info{background:var(--blu)}

/* ══ LANDING NAV ════════════════════════════════════════════════ */
.lnav{background:rgba(255,255,255,.95);backdrop-filter:blur(12px);padding:0 6%;height:68px;display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid rgba(0,0,0,.06);position:sticky;top:0;z-index:200;box-shadow:0 2px 20px rgba(0,0,0,.06)}
.logo{font-size:24px;font-weight:800;color:var(--g);display:flex;align-items:center;gap:8px;text-decoration:none;cursor:pointer}
.logo span{background:linear-gradient(135deg,var(--g),var(--teal));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.lnav-links{display:flex;gap:6px;align-items:center}
.lnav-links a{font-size:14px;font-weight:600;color:var(--txt2);text-decoration:none;cursor:pointer;padding:8px 14px;border-radius:10px;transition:all .15s}
.lnav-links a:hover{color:var(--g);background:var(--gl)}
.btn{padding:10px 22px;border-radius:12px;font-family:inherit;font-weight:700;font-size:14px;cursor:pointer;border:none;transition:all .2s;letter-spacing:.1px}
.btn-g{background:linear-gradient(135deg,var(--g),var(--gd));color:#fff;box-shadow:0 4px 14px rgba(29,158,117,.35)}
.btn-g:hover{transform:translateY(-2px);box-shadow:0 6px 20px rgba(29,158,117,.45)}
.btn-o{background:#fff;color:var(--g);border:2px solid var(--g)}
.btn-o:hover{background:var(--gl)}
.btn-r{background:var(--red);color:#fff}
.btn-sm{padding:8px 16px;font-size:13px;border-radius:10px}
.btn-xs{padding:5px 12px;font-size:11px;border-radius:8px}
.btn-w{background:rgba(255,255,255,.18);color:#fff;border:1.5px solid rgba(255,255,255,.45);backdrop-filter:blur(4px)}
.btn-w:hover{background:rgba(255,255,255,.3)}

/* ══ HERO ════════════════════════════════════════════════════════ */
.hero{background:linear-gradient(135deg,#0F6E56 0%,#1D9E75 40%,#0EA5E9 100%);padding:90px 6% 110px;display:grid;grid-template-columns:1.1fr 1fr;gap:60px;align-items:center;position:relative;overflow:hidden}
.hero::before{content:'';position:absolute;inset:0;background:url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.04'%3E%3Ccircle cx='30' cy='30' r='4'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");pointer-events:none}
.hero-blob{position:absolute;width:400px;height:400px;border-radius:50%;background:radial-gradient(circle,rgba(255,255,255,.08),transparent 70%);top:-100px;right:-50px;pointer-events:none}
.hero h1{font-size:50px;font-weight:800;color:#fff;line-height:1.12;margin-bottom:18px;position:relative}
.hero h1 .highlight{background:linear-gradient(135deg,#FFE566,#FFB800);-webkit-background-clip:text;-webkit-text-fill-color:transparent;display:inline-block}
.hero p{font-size:17px;color:rgba(255,255,255,.88);line-height:1.75;margin-bottom:30px}
.hero-btns{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:28px}
.hero-badges{display:flex;gap:10px;flex-wrap:wrap}
.hbadge{background:rgba(255,255,255,.16);color:#fff;border:1px solid rgba(255,255,255,.3);border-radius:20px;padding:6px 14px;font-size:12px;font-weight:600;backdrop-filter:blur(4px)}
.hero-card{background:rgba(255,255,255,.12);backdrop-filter:blur(16px);border:1.5px solid rgba(255,255,255,.25);border-radius:24px;padding:28px}
.hero-card .big{font-size:56px;text-align:center;margin-bottom:20px}
.hstat-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.hstat{background:rgba(255,255,255,.15);border-radius:14px;padding:14px;text-align:center;border:1px solid rgba(255,255,255,.2)}
.hstat .n{font-size:24px;font-weight:800;color:#fff}
.hstat .l{font-size:10px;color:rgba(255,255,255,.75);margin-top:2px;font-weight:500}

/* ══ STATS BAR ══════════════════════════════════════════════════ */
.stats-bar{background:#fff;border-bottom:1px solid var(--border);display:flex;justify-content:space-around;padding:28px 6%;flex-wrap:wrap;gap:16px}
.stat-item .n{font-size:30px;font-weight:800;background:linear-gradient(135deg,var(--g),var(--teal));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.stat-item .l{font-size:12px;color:var(--txt2);margin-top:3px;font-weight:500}

/* ══ SECTIONS ═══════════════════════════════════════════════════ */
.section{padding:70px 6%}
.section-title{font-size:34px;font-weight:800;text-align:center;margin-bottom:10px;background:linear-gradient(135deg,var(--txt),#444);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.section-sub{font-size:16px;color:var(--txt2);text-align:center;margin-bottom:44px;line-height:1.6}
.section-badge{display:inline-block;background:var(--gl);color:var(--gd);font-size:12px;font-weight:700;padding:5px 14px;border-radius:20px;margin-bottom:12px;letter-spacing:.3px}

/* ══ SERVICE CARDS ══════════════════════════════════════════════ */
.services-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.service-card{border-radius:20px;padding:28px 18px;text-align:center;cursor:pointer;transition:all .25s;position:relative;overflow:hidden;border:1.5px solid transparent}
.service-card:hover{transform:translateY(-6px);box-shadow:0 20px 40px rgba(0,0,0,.12)}
.service-card::before{content:'';position:absolute;inset:0;border-radius:20px;opacity:0;transition:opacity .25s;z-index:0}
.service-card>*{position:relative;z-index:1}
.sc-1{background:linear-gradient(145deg,#E1F5EE,#B2DFDB);border-color:#9FE1CB}.sc-1:hover{box-shadow:0 20px 40px rgba(29,158,117,.2)}
.sc-2{background:linear-gradient(145deg,#FFF3E0,#FFE0B2);border-color:#FFCC80}.sc-2:hover{box-shadow:0 20px 40px rgba(239,159,39,.2)}
.sc-3{background:linear-gradient(145deg,#EDE7F6,#D1C4E9);border-color:#B39DDB}.sc-3:hover{box-shadow:0 20px 40px rgba(124,58,237,.2)}
.sc-4{background:linear-gradient(145deg,#E8F5E9,#C8E6C9);border-color:#A5D6A7}.sc-4:hover{box-shadow:0 20px 40px rgba(29,158,117,.2)}
.sc-5{background:linear-gradient(145deg,#FCE4EC,#F8BBD9);border-color:#F48FB1}.sc-5:hover{box-shadow:0 20px 40px rgba(236,72,153,.2)}
.sc-6{background:linear-gradient(145deg,#E3F2FD,#BBDEFB);border-color:#90CAF9}.sc-6:hover{box-shadow:0 20px 40px rgba(55,138,221,.2)}
.sc-7{background:linear-gradient(145deg,#E0F7FA,#B2EBF2);border-color:#80DEEA}.sc-7:hover{box-shadow:0 20px 40px rgba(14,165,233,.2)}
.sc-8{background:linear-gradient(145deg,#F1F8E9,#DCEDC8);border-color:#C5E1A5}.sc-8:hover{box-shadow:0 20px 40px rgba(29,158,117,.15)}
.service-card .ico{font-size:44px;margin-bottom:14px;display:block;filter:drop-shadow(0 4px 8px rgba(0,0,0,.1))}
.service-card h3{font-size:15px;font-weight:700;margin-bottom:7px;color:var(--txt)}
.service-card p{font-size:12px;color:var(--txt2);line-height:1.5}

/* ══ WORKER CARDS ═══════════════════════════════════════════════ */
.workers-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.worker-card{border-radius:22px;overflow:hidden;cursor:pointer;transition:all .25s;box-shadow:0 4px 16px rgba(0,0,0,.07);border:1.5px solid var(--border)}
.worker-card:hover{transform:translateY(-6px);box-shadow:0 20px 50px rgba(0,0,0,.13)}
.wc-top{padding:22px 20px;display:flex;align-items:center;gap:16px;position:relative;overflow:hidden}
.wc-top::after{content:'';position:absolute;top:-20px;right:-20px;width:80px;height:80px;border-radius:50%;background:rgba(255,255,255,.12)}
.wc-av{width:58px;height:58px;border-radius:50%;background:rgba(255,255,255,.25);border:2.5px solid rgba(255,255,255,.5);display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:800;color:#fff;flex-shrink:0;box-shadow:0 4px 12px rgba(0,0,0,.15)}
.wc-info h4{color:#fff;font-size:16px;font-weight:800}
.wc-info p{color:rgba(255,255,255,.85);font-size:12px;margin-top:3px}
.wc-verified{position:absolute;top:14px;right:14px;background:rgba(255,255,255,.2);color:#fff;font-size:10px;font-weight:700;padding:3px 9px;border-radius:12px;border:1px solid rgba(255,255,255,.35)}
.wc-body{padding:18px;background:#fff}
.wc-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:14px}
.wcs{background:var(--bg);border-radius:12px;padding:10px;text-align:center}
.wcs .n{font-size:15px;font-weight:800;color:var(--g)}
.wcs .l{font-size:9px;color:var(--txt2);margin-top:2px;font-weight:600;text-transform:uppercase;letter-spacing:.3px}
.stars{color:var(--amb);font-size:12px;letter-spacing:1px}
.badge{font-size:10px;font-weight:700;padding:3px 10px;border-radius:20px;display:inline-block;letter-spacing:.2px}
.bg{background:var(--gl);color:var(--gd)}
.ba{background:var(--ambl);color:#633806}
.bb{background:var(--blul);color:#0C447C}
.br{background:var(--redl);color:#A32D2D}
.bw{background:#f0f0f0;color:var(--txt2)}
.bpur{background:var(--purl);color:var(--pur)}
.bpin{background:var(--pinl);color:var(--pin)}

/* ══ HOW IT WORKS ═══════════════════════════════════════════════ */
.how-bg{background:linear-gradient(160deg,#F0FDF9,#E0F2FE)}
.how-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:24px}
.how-card{background:#fff;border-radius:20px;padding:28px 20px;text-align:center;box-shadow:0 4px 20px rgba(0,0,0,.06);border:1px solid var(--border);transition:all .2s}
.how-card:hover{transform:translateY(-4px);box-shadow:0 12px 32px rgba(29,158,117,.12)}
.how-num{width:52px;height:52px;border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:800;color:#fff;margin:0 auto 16px;box-shadow:0 6px 16px rgba(0,0,0,.15)}
.how-card h3{font-size:15px;font-weight:700;margin-bottom:8px}
.how-card p{font-size:13px;color:var(--txt2);line-height:1.6}

/* ══ TRUST SECTION ══════════════════════════════════════════════ */
.trust-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.trust-card{background:#fff;border-radius:20px;padding:28px;box-shadow:0 4px 20px rgba(0,0,0,.06);border:1px solid var(--border);text-align:center}
.trust-icon{font-size:48px;margin-bottom:14px;display:block}
.trust-card h3{font-size:16px;font-weight:700;margin-bottom:8px}
.trust-card p{font-size:13px;color:var(--txt2);line-height:1.6}

/* ══ TESTIMONIALS ════════════════════════════════════════════════ */
.testimonials{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.tcard{background:#fff;border-radius:18px;padding:24px;box-shadow:0 4px 20px rgba(0,0,0,.06);border:1px solid var(--border)}
.tcard .quote{font-size:32px;color:var(--gl);font-weight:800;line-height:1;margin-bottom:10px}
.tcard p{font-size:14px;color:var(--txt2);line-height:1.7;font-style:italic;margin-bottom:16px}
.tcard-author{display:flex;align-items:center;gap:10px}
.tav{width:40px;height:40px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;flex-shrink:0}

/* ══ CTA SECTION ════════════════════════════════════════════════ */
.cta-section{background:linear-gradient(135deg,var(--pur) 0%,var(--blu) 50%,var(--teal) 100%);padding:80px 6%;text-align:center;position:relative;overflow:hidden}
.cta-section::before{content:'';position:absolute;inset:0;background:url("data:image/svg+xml,%3Csvg width='80' height='80' viewBox='0 0 80 80' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23ffffff' fill-opacity='0.05'%3E%3Ccircle cx='40' cy='40' r='20'/%3E%3C/g%3E%3C/svg%3E")}
.cta-section h2{color:#fff;font-size:36px;font-weight:800;margin-bottom:14px;position:relative}
.cta-section p{color:rgba(255,255,255,.85);font-size:17px;margin-bottom:32px;position:relative}
.cta-btns{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;position:relative}
.btn-white{background:#fff;color:var(--pur);font-size:15px;padding:14px 36px;font-weight:800;border-radius:14px;cursor:pointer;border:none;font-family:inherit;transition:all .2s;box-shadow:0 6px 20px rgba(0,0,0,.2)}
.btn-white:hover{transform:translateY(-3px);box-shadow:0 10px 30px rgba(0,0,0,.25)}

/* ══ FOOTER ══════════════════════════════════════════════════════ */
footer{background:#0D1117;color:#8B949E;padding:50px 6% 28px}
.footer-grid{display:grid;grid-template-columns:2.2fr 1fr 1fr 1fr;gap:40px;margin-bottom:40px}
.footer-brand .logo-f{font-size:22px;font-weight:800;color:#fff;margin-bottom:12px;display:flex;align-items:center;gap:8px}
.footer-brand p{font-size:13px;line-height:1.8;margin-bottom:18px}
.footer-social{display:flex;gap:10px}
.fsocial{width:36px;height:36px;border-radius:10px;background:#1C2128;display:flex;align-items:center;justify-content:center;font-size:16px;cursor:pointer;transition:background .15s;border:1px solid #30363D}
.fsocial:hover{background:var(--g)}
.footer-col h4{color:#fff;font-size:12px;font-weight:700;margin-bottom:14px;text-transform:uppercase;letter-spacing:.8px}
.footer-col a{display:block;font-size:13px;color:#8B949E;text-decoration:none;margin-bottom:9px;cursor:pointer;transition:color .15s}
.footer-col a:hover{color:var(--g)}
.footer-bottom{border-top:1px solid #1C2128;padding-top:24px;display:flex;justify-content:space-between;align-items:center;font-size:12px;flex-wrap:wrap;gap:10px}
.footer-cities{display:flex;gap:8px;flex-wrap:wrap}
.fcity{background:#1C2128;border:1px solid #30363D;border-radius:8px;padding:4px 10px;font-size:11px;color:#8B949E}

/* ══ APP SHELL ═══════════════════════════════════════════════════ */
.app{display:flex;flex-direction:column;min-height:100vh}
.topbar{background:#fff;border-bottom:1px solid var(--border);padding:0 24px;height:64px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:150;box-shadow:0 2px 12px rgba(0,0,0,.06)}
.tb-logo{font-size:20px;font-weight:800;color:var(--g);display:flex;align-items:center;gap:6px}
.tb-right{display:flex;align-items:center;gap:12px}
.tb-notif{position:relative;cursor:pointer;background:var(--bg);border:1px solid var(--border);width:38px;height:38px;border-radius:11px;display:flex;align-items:center;justify-content:center;font-size:17px;transition:all .15s}
.tb-notif:hover{background:var(--gl);border-color:var(--g)}
.tb-notif .ndot{position:absolute;top:6px;right:6px;width:8px;height:8px;background:var(--red);border-radius:50%;border:2px solid #fff}
.user-chip{display:flex;align-items:center;gap:8px;background:var(--gl);border-radius:12px;padding:7px 14px;cursor:pointer;font-size:13px;font-weight:700;color:var(--gd);transition:all .15s;border:1px solid #9FE1CB}
.user-chip:hover{background:#C8F0DC}
.user-av{width:26px;height:26px;border-radius:50%;background:var(--g);color:#fff;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:800}
.app-tabs{display:flex;border-bottom:1px solid var(--border);background:#fff;overflow-x:auto;padding:0 24px;gap:4px}
.app-tabs::-webkit-scrollbar{height:0}
.atab{padding:14px 18px;font-size:13px;font-weight:600;color:var(--txt2);cursor:pointer;border-bottom:3px solid transparent;white-space:nowrap;transition:all .15s;border-radius:0}
.atab:hover{color:var(--g);background:var(--gll)}
.atab.on{color:var(--g);border-bottom-color:var(--g);font-weight:800}

/* ══ SEARCH PAGE ════════════════════════════════════════════════ */
.search-wrap{max-width:1140px;margin:0 auto;padding:28px 24px}
.search-box{display:flex;align-items:center;gap:10px;background:#fff;border:1.5px solid var(--border);border-radius:14px;padding:12px 18px;transition:border .15s;box-shadow:0 2px 8px rgba(0,0,0,.05)}
.search-box:focus-within{border-color:var(--g);box-shadow:0 4px 16px rgba(29,158,117,.12)}
.search-box input{border:none;background:none;outline:none;flex:1;font-size:15px;font-family:inherit;color:var(--txt)}
.search-box input::placeholder{color:var(--txt3)}
.filter-row{display:flex;gap:8px;margin-bottom:20px;flex-wrap:wrap}
.fchip{padding:7px 16px;border-radius:20px;font-size:12px;font-weight:700;cursor:pointer;border:1.5px solid var(--border);background:#fff;transition:all .2s;white-space:nowrap}
.fchip:hover{border-color:var(--g);color:var(--g)}
.fchip.on{background:var(--g);color:#fff;border-color:var(--g);box-shadow:0 4px 10px rgba(29,158,117,.3)}
.results-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:16px}
.rcard{background:#fff;border-radius:18px;border:1.5px solid var(--border);padding:20px;cursor:pointer;transition:all .2s}
.rcard:hover{border-color:var(--g);box-shadow:0 8px 28px rgba(29,158,117,.12);transform:translateY(-2px)}
.rav{width:54px;height:54px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:800;flex-shrink:0}
.rcard-rate{font-size:17px;font-weight:800;color:var(--g)}
.rcard-rate small{font-size:11px;color:var(--txt3);font-weight:500}
.skills-row{display:flex;flex-wrap:wrap;gap:5px;margin-top:12px}

/* ══ WORKER DETAIL ══════════════════════════════════════════════ */
.detail-wrap{max-width:960px;margin:0 auto;padding:28px 24px}
.detail-hero{border-radius:24px;padding:32px;margin-bottom:24px;display:flex;gap:24px;align-items:center;flex-wrap:wrap;position:relative;overflow:hidden}
.detail-hero::after{content:'';position:absolute;top:-40px;right:-40px;width:180px;height:180px;border-radius:50%;background:rgba(255,255,255,.08)}
.dh-av{width:84px;height:84px;border-radius:50%;background:rgba(255,255,255,.2);border:3px solid rgba(255,255,255,.45);display:flex;align-items:center;justify-content:center;font-size:30px;font-weight:800;color:#fff;flex-shrink:0;box-shadow:0 8px 24px rgba(0,0,0,.15);position:relative;z-index:1}
.dh-info{position:relative;z-index:1}
.dh-info h2{color:#fff;font-size:26px;font-weight:800}
.dh-info p{color:rgba(255,255,255,.85);font-size:14px;margin-top:5px}
.dh-stats{display:flex;gap:14px;margin-top:14px;flex-wrap:wrap}
.dhs{background:rgba(255,255,255,.18);border-radius:12px;padding:10px 18px;text-align:center;border:1px solid rgba(255,255,255,.25);backdrop-filter:blur(4px)}
.dhs .n{font-size:18px;font-weight:800;color:#fff}
.dhs .l{font-size:10px;color:rgba(255,255,255,.75);margin-top:2px;font-weight:600}
.detail-grid{display:grid;grid-template-columns:1fr 350px;gap:24px}
.detail-tabs{display:flex;gap:4px;background:#f0f0f0;border-radius:14px;padding:4px;margin-bottom:16px}
.dtab{flex:1;padding:10px;border-radius:11px;text-align:center;font-size:13px;font-weight:600;cursor:pointer;color:var(--txt2);transition:all .15s;border:none;background:none;font-family:inherit}
.dtab.on{background:#fff;color:var(--g);box-shadow:0 2px 10px rgba(0,0,0,.1);font-weight:800}
.detail-card{background:#fff;border-radius:18px;border:1px solid var(--border);padding:22px;margin-bottom:16px;box-shadow:0 2px 10px rgba(0,0,0,.04)}
.book-box{background:#fff;border-radius:20px;border:1.5px solid var(--border);padding:22px;position:sticky;top:80px;box-shadow:0 4px 24px rgba(0,0,0,.08)}
.book-box h3{font-size:17px;font-weight:800;margin-bottom:18px}
.form-group{margin-bottom:14px}
.flabel{font-size:11px;font-weight:700;color:var(--txt2);margin-bottom:6px;display:block;text-transform:uppercase;letter-spacing:.5px}
.finput{width:100%;padding:11px 14px;border-radius:11px;border:1.5px solid var(--border);font-family:inherit;font-size:14px;color:var(--txt);outline:none;transition:all .15s;background:#fff}
.finput:focus{border-color:var(--g);box-shadow:0 0 0 3px rgba(29,158,117,.1)}
select.finput{appearance:none;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='10' height='7'%3E%3Cpath d='M1 1l4 4 4-4' stroke='%23999' stroke-width='1.5' fill='none'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 14px center}
.notice{border-radius:12px;padding:12px 14px;font-size:12px;display:flex;gap:10px;align-items:flex-start;margin-bottom:12px;line-height:1.5}
.notice-g{background:var(--gl);border:1px solid #9FE1CB;color:var(--gd)}
.notice-a{background:var(--ambl);border:1px solid #FAC775;color:#633806}
.notice-r{background:var(--redl);border:1px solid #F7C1C1;color:#A32D2D}

/* ══ BOOKINGS ═══════════════════════════════════════════════════ */
.bookings-wrap{max-width:820px;margin:0 auto;padding:28px 24px}
.bcard{background:#fff;border-radius:18px;border:1.5px solid var(--border);padding:20px;margin-bottom:14px;border-left:5px solid var(--g);box-shadow:0 2px 12px rgba(0,0,0,.05);transition:all .2s}
.bcard:hover{box-shadow:0 6px 24px rgba(0,0,0,.09)}
.bcard.done{border-left-color:var(--amb)}
.bcard.pending{border-left-color:var(--blu)}
.bcard.cancelled{border-left-color:var(--red)}
.bav{width:48px;height:48px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:700;flex-shrink:0}
.bcard-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:14px;padding-top:14px;border-top:1px solid var(--border)}

/* ══ CHAT ════════════════════════════════════════════════════════ */
.chat-wrap{display:grid;grid-template-columns:300px 1fr;height:calc(100vh - 125px)}
.chat-list{border-right:1px solid var(--border);background:#fff;overflow-y:auto}
.chat-list::-webkit-scrollbar{width:0}
.chat-item{padding:14px 18px;cursor:pointer;border-bottom:1px solid var(--border);transition:background .15s}
.chat-item:hover,.chat-item.active{background:var(--gll)}
.ci-av{width:44px;height:44px;border-radius:50%;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:800}
.ci-info h4{font-size:13px;font-weight:700}
.ci-info p{font-size:11px;color:var(--txt2);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.chat-main{display:flex;flex-direction:column;background:#f0f4f8}
.chat-header{background:#fff;border-bottom:1px solid var(--border);padding:14px 22px;display:flex;align-items:center;gap:12px;box-shadow:0 2px 8px rgba(0,0,0,.05)}
.chat-messages{flex:1;overflow-y:auto;padding:20px;display:flex;flex-direction:column;gap:10px}
.chat-messages::-webkit-scrollbar{width:0}
.msg{max-width:70%;padding:12px 16px;border-radius:18px;font-size:13px;line-height:1.55}
.msg-in{background:#fff;border:1px solid var(--border);border-bottom-left-radius:4px;align-self:flex-start;box-shadow:0 2px 6px rgba(0,0,0,.06)}
.msg-out{background:linear-gradient(135deg,var(--g),var(--gd));color:#fff;border-bottom-right-radius:4px;align-self:flex-end;box-shadow:0 4px 12px rgba(29,158,117,.25)}
.msg-time{font-size:10px;opacity:.6;margin-top:5px}
.chat-input{background:#fff;border-top:1px solid var(--border);padding:14px 18px;display:flex;gap:10px;align-items:center}
.chat-input input{flex:1;border:1.5px solid var(--border);border-radius:24px;padding:11px 18px;font-family:inherit;font-size:14px;outline:none;transition:border .15s}
.chat-input input:focus{border-color:var(--g)}
.send-btn{width:44px;height:44px;border-radius:50%;background:linear-gradient(135deg,var(--g),var(--gd));border:none;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0;box-shadow:0 4px 12px rgba(29,158,117,.35);transition:all .2s}
.send-btn:hover{transform:scale(1.08)}

/* ══ PROFILE ════════════════════════════════════════════════════ */
.profile-wrap{max-width:720px;margin:0 auto;padding:28px 24px}
.profile-hero{border-radius:24px;padding:32px;text-align:center;margin-bottom:24px;position:relative;overflow:hidden}
.ph-av{width:80px;height:80px;border-radius:50%;background:rgba(255,255,255,.2);border:3px solid rgba(255,255,255,.45);display:flex;align-items:center;justify-content:center;font-size:28px;font-weight:800;color:#fff;margin:0 auto 14px;box-shadow:0 8px 24px rgba(0,0,0,.15)}
.profile-hero h2{color:#fff;font-size:22px;font-weight:800}
.profile-hero p{color:rgba(255,255,255,.78);font-size:14px;margin-top:5px}
.wallet-box{background:linear-gradient(135deg,#0F6E56,#1D9E75);border-radius:20px;padding:22px;color:#fff;margin-bottom:18px;box-shadow:0 8px 28px rgba(29,158,117,.3)}
.wallet-box .bal{font-size:34px;font-weight:800;margin:8px 0;letter-spacing:-1px}
.menu-card{background:#fff;border-radius:20px;border:1.5px solid var(--border);overflow:hidden;margin-bottom:16px;box-shadow:0 2px 12px rgba(0,0,0,.05)}
.menu-item{display:flex;align-items:center;justify-content:space-between;padding:16px 20px;cursor:pointer;border-bottom:1px solid var(--border);transition:background .15s}
.menu-item:last-child{border-bottom:none}
.menu-item:hover{background:var(--gll)}
.menu-item-left{display:flex;align-items:center;gap:14px;font-size:14px;font-weight:600}

/* ══ ADMIN ═══════════════════════════════════════════════════════ */
.admin-layout{display:flex;min-height:100vh}
.admin-sidebar{width:var(--sidebar);background:linear-gradient(180deg,#0A1628 0%,#0F2240 100%);position:fixed;top:0;left:0;height:100vh;z-index:100;overflow-y:auto}
.as-logo{padding:22px 20px;border-bottom:1px solid rgba(255,255,255,.08)}
.as-logo h2{color:#fff;font-size:20px;font-weight:800;display:flex;align-items:center;gap:8px}
.as-logo p{color:rgba(255,255,255,.4);font-size:11px;margin-top:3px}
.as-nav{padding:14px 8px}
.as-section{font-size:10px;font-weight:700;color:rgba(255,255,255,.3);padding:12px 12px 5px;letter-spacing:1.2px;text-transform:uppercase}
.as-item{display:flex;align-items:center;gap:10px;padding:10px 12px;border-radius:10px;cursor:pointer;color:rgba(255,255,255,.65);font-size:13px;font-weight:500;transition:all .15s;margin-bottom:2px}
.as-item:hover{background:rgba(255,255,255,.1);color:#fff}
.as-item.on{background:linear-gradient(135deg,rgba(29,158,117,.4),rgba(14,165,233,.3));color:#fff;font-weight:700;border:1px solid rgba(29,158,117,.3)}
.as-item .ico{font-size:15px;width:20px;text-align:center}
.admin-main{margin-left:var(--sidebar);flex:1;background:var(--bg)}
.admin-topbar{background:#fff;border-bottom:1px solid var(--border);padding:0 26px;height:60px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:50;box-shadow:0 2px 10px rgba(0,0,0,.05)}
.admin-topbar h2{font-size:16px;font-weight:800}
.admin-content{padding:24px;display:none}
.admin-content.on{display:block}
.ag{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;margin-bottom:22px}
.astat{background:#fff;border-radius:16px;border:1px solid var(--border);padding:20px;position:relative;overflow:hidden;box-shadow:0 2px 12px rgba(0,0,0,.05)}
.astat::before{content:'';position:absolute;left:0;top:0;width:4px;height:100%;border-radius:4px 0 0 4px}
.astat.g::before{background:linear-gradient(180deg,var(--g),var(--teal))}
.astat.a::before{background:linear-gradient(180deg,var(--amb),var(--ora))}
.astat.b::before{background:linear-gradient(180deg,var(--blu),var(--pur))}
.astat.r::before{background:linear-gradient(180deg,var(--red),var(--pin))}
.astat .n{font-size:28px;font-weight:800;margin:8px 0}
.astat .l{font-size:11px;color:var(--txt2);font-weight:700;text-transform:uppercase;letter-spacing:.4px}
.astat .ch{font-size:11px;color:var(--g);font-weight:600}
.astat .em{font-size:28px;position:absolute;top:16px;right:16px;opacity:.15}
.atable{background:#fff;border-radius:16px;border:1px solid var(--border);overflow:hidden;margin-bottom:18px;box-shadow:0 2px 10px rgba(0,0,0,.04)}
.atable-head{padding:16px 20px;display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid var(--border);background:#fafafa}
.atable-head h3{font-size:15px;font-weight:700}
table{width:100%;border-collapse:collapse}
th{background:#f7f8fa;font-size:10px;font-weight:700;color:var(--txt2);text-transform:uppercase;letter-spacing:.5px;padding:10px 16px;text-align:left;border-bottom:1px solid var(--border)}
td{padding:12px 16px;font-size:12px;border-bottom:1px solid var(--border);color:var(--txt)}
tr:last-child td{border-bottom:none}
tr:hover td{background:#fafbfc}
.filter-row2{display:flex;gap:8px;margin-bottom:16px;flex-wrap:wrap}
.finput2{padding:9px 14px;border-radius:10px;border:1.5px solid var(--border);font-family:inherit;font-size:12px;outline:none;background:#fff;transition:border .15s}
.finput2:focus{border-color:var(--g)}

/* ══ MODALS ══════════════════════════════════════════════════════ */
.overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:300;align-items:center;justify-content:center;padding:16px;backdrop-filter:blur(3px)}
.overlay.open{display:flex}
.modal{background:#fff;border-radius:24px;padding:30px;width:100%;max-width:460px;max-height:90vh;overflow-y:auto;box-shadow:0 24px 80px rgba(0,0,0,.25);animation:modalIn .25s cubic-bezier(.34,1.56,.64,1)}
@keyframes modalIn{from{opacity:0;transform:scale(.92) translateY(20px)}to{opacity:1;transform:scale(1) translateY(0)}}
.modal h3{font-size:20px;font-weight:800;margin-bottom:22px}
.modal-close{float:right;cursor:pointer;font-size:20px;color:var(--txt3);background:var(--bg);border:none;width:32px;height:32px;border-radius:8px;display:flex;align-items:center;justify-content:center;transition:all .15s}
.modal-close:hover{background:var(--redl);color:var(--red)}

/* ══ MISC ════════════════════════════════════════════════════════ */
.divider{height:1px;background:var(--border);margin:16px 0}
.sec-title{font-size:17px;font-weight:800;margin-bottom:12px}
.online-dot{width:10px;height:10px;background:#22C55E;border-radius:50%;border:2px solid #fff;flex-shrink:0}

/* ══ GRADIENT HELPERS ════════════════════════════════════════════ */
.grad-green{background:linear-gradient(135deg,var(--g),var(--gd))}
.grad-blue{background:linear-gradient(135deg,var(--blu),var(--pur))}
.grad-orange{background:linear-gradient(135deg,var(--ora),var(--amb))}
.grad-pink{background:linear-gradient(135deg,var(--pin),var(--pur))}
.grad-teal{background:linear-gradient(135deg,var(--teal),var(--g))}
.grad-multi{background:linear-gradient(135deg,var(--g) 0%,var(--teal) 50%,var(--blu) 100%)}

@media(max-width:900px){
  .hero{grid-template-columns:1fr}.hero-card{display:none}
  .services-grid{grid-template-columns:repeat(2,1fr)}
  .workers-grid,.trust-grid,.testimonials{grid-template-columns:1fr}
  .how-grid{grid-template-columns:repeat(2,1fr)}
  .footer-grid{grid-template-columns:1fr 1fr}
  .detail-grid{grid-template-columns:1fr}
  .chat-wrap{grid-template-columns:1fr}
  .admin-sidebar{display:none}
  .admin-main{margin-left:0}
  .ag{grid-template-columns:repeat(2,1fr)}
}
</style>
</head>
<body>
<div class="toast" id="toast"></div>

<!-- ════════════════════════════════════════
  VIEW: LANDING PAGE
════════════════════════════════════════ -->
<div class="view active" id="v-landing" style="min-height:100vh;display:flex;flex-direction:column">

  <!-- NAV -->
  <nav class="lnav">
    <a class="logo" onclick="scrollToTop()">🏠 <span>Aetbar</span></a>
    <div class="lnav-links">
      <a onclick="scrollToId('sec-services')">Services</a>
      <a onclick="scrollToId('sec-workers')">Workers</a>
      <a onclick="scrollToId('sec-how')">How It Works</a>
      <a onclick="scrollToId('sec-trust')">Why Aetbar</a>
      <a onclick="showPage('about')">About Us</a>
      <a onclick="showPage('contact')">Contact</a>
      <a onclick="showModal('login-modal')">Login</a>
      <button class="btn btn-g btn-sm" onclick="showModal('register-modal')">Get Started →</button>
    </div>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-blob"></div>
    <div>
      <div style="display:inline-flex;align-items:center;gap:8px;background:rgba(255,255,255,.15);border:1px solid rgba(255,255,255,.3);border-radius:20px;padding:6px 14px;margin-bottom:20px">
        <span style="width:7px;height:7px;background:#22C55E;border-radius:50%"></span>
        <span style="font-size:12px;color:#fff;font-weight:600">Now available in Islamabad, Lahore & Karachi</span>
      </div>
      <h1>Find <span class="highlight">Trusted</span> Home Workers Across Pakistan</h1>
      <p>Pakistan's first verified platform for maids, cooks, electricians & more. Every worker is CNIC-checked, background-screened and police-cleared.</p>
      <div class="hero-btns">
        <button class="btn btn-g" style="font-size:15px;padding:14px 28px" onclick="showModal('register-modal')">Hire a Worker →</button>
        <button class="btn btn-w" style="font-size:15px;padding:14px 28px" onclick="showModal('worker-register-modal')">Join as Worker</button>
      </div>
      <div class="hero-badges">
        <span class="hbadge">✓ CNIC Verified</span>
        <span class="hbadge">🛡️ Police Cleared</span>
        <span class="hbadge">💳 Secure Payments</span>
        <span class="hbadge">⭐ 4.8 Avg Rating</span>
      </div>
    </div>
    <div class="hero-card">
      <div class="big">🏠</div>
      <div class="hstat-grid">
        <div class="hstat"><div class="n">432+</div><div class="l">Verified Workers</div></div>
        <div class="hstat"><div class="n">1,284</div><div class="l">Happy Families</div></div>
        <div class="hstat"><div class="n">1,842</div><div class="l">Jobs Completed</div></div>
        <div class="hstat"><div class="n">4.8★</div><div class="l">Avg Rating</div></div>
      </div>
    </div>
  </section>

  <!-- STATS BAR -->
  <div class="stats-bar">
    <div class="stat-item" style="text-align:center"><div class="n">432+</div><div class="l">Verified Workers</div></div>
    <div class="stat-item" style="text-align:center"><div class="n">1,284+</div><div class="l">Employers</div></div>
    <div class="stat-item" style="text-align:center"><div class="n">1,842</div><div class="l">Bookings Done</div></div>
    <div class="stat-item" style="text-align:center"><div class="n">Rs 2.4L</div><div class="l">Paid to Workers</div></div>
    <div class="stat-item" style="text-align:center"><div class="n">94%</div><div class="l">Satisfaction Rate</div></div>
  </div>

  <!-- SERVICES -->
  <section class="section" id="sec-services" style="background:#fff">
    <div style="text-align:center;margin-bottom:8px"><span class="section-badge">🛠️ Our Services</span></div>
    <div class="section-title">Find Any Home Service</div>
    <div class="section-sub">12 professional categories · Hundreds of verified workers ready to hire today</div>
    <div class="services-grid" style="grid-template-columns:repeat(4,1fr)">
      <div class="service-card sc-1" onclick="goToApp('search','maid')"><span class="ico">🧹</span><h3>Maid / Housemaid</h3><p>Full cleaning, laundry, ironing & daily household work</p></div>
      <div class="service-card sc-2" onclick="goToApp('search','cook')"><span class="ico">👨‍🍳</span><h3>Cook / Chef</h3><p>Pakistani, continental & BBQ for daily meals or occasions</p></div>
      <div class="service-card sc-3" onclick="goToApp('search','clothes_wash')"><span class="ico">👔</span><h3>Clothes Washer</h3><p>Hand wash, machine wash, drying & ironing services</p></div>
      <div class="service-card sc-4" onclick="goToApp('search','dishwasher')"><span class="ico">🍽️</span><h3>Dishwasher</h3><p>Daily kitchen cleaning and dishwashing service</p></div>
      <div class="service-card sc-5" onclick="goToApp('search','security')"><span class="ico">🔒</span><h3>Security Guard</h3><p>Ex-army trained guards for homes, offices & events</p></div>
      <div class="service-card sc-6" onclick="goToApp('search','electrician')"><span class="ico">⚡</span><h3>Electrician</h3><p>Wiring, AC installation, fan & emergency electrical repairs</p></div>
      <div class="service-card sc-7" onclick="goToApp('search','plumber')"><span class="ico">🔧</span><h3>Plumber</h3><p>Pipe repairs, fitting installation & drainage solutions</p></div>
      <div class="service-card sc-8" onclick="goToApp('search','gardener')"><span class="ico">🌿</span><h3>Gardener</h3><p>Lawn care, plant maintenance & garden design</p></div>
      <div class="service-card" style="background:linear-gradient(145deg,#FEF3C7,#FDE68A);border-color:#FCD34D" onclick="goToApp('search','labourer')"><span class="ico">⛏️</span><h3>Labourer on Wages</h3><p>Daily wage workers for loading, construction & general labour work</p></div>
      <div class="service-card" style="background:linear-gradient(145deg,#FCE7F3,#FBCFE8);border-color:#F9A8D4" onclick="goToApp('search','babysitter')"><span class="ico">👶</span><h3>Baby Sitter</h3><p>Caring, experienced child minders for infants and toddlers</p></div>
      <div class="service-card" style="background:linear-gradient(145deg,#ECFDF5,#D1FAE5);border-color:#6EE7B7" onclick="goToApp('search','carpenter')"><span class="ico">🪚</span><h3>Carpenter</h3><p>Furniture making, wood repairs, door fitting & custom woodwork</p></div>
      <div class="service-card" style="background:linear-gradient(145deg,#EFF6FF,#DBEAFE);border-color:#93C5FD" onclick="goToApp('search','painter')"><span class="ico">🎨</span><h3>Painter</h3><p>Interior & exterior wall painting, polish & finishing work</p></div>
    </div>
  </section>

  <!-- TOP WORKERS -->
  <section class="section" id="sec-workers" style="background:linear-gradient(160deg,#F8FAFC,#EFF8F4)">
    <div style="text-align:center;margin-bottom:8px"><span class="section-badge">⭐ Top Rated</span></div>
    <div class="section-title">Meet Our Best Workers</div>
    <div class="section-sub">Islamabad's most trusted household professionals — all CNIC-verified & police-cleared</div>
    <div class="workers-grid" id="landing-workers"></div>
    <div style="text-align:center;margin-top:36px">
      <button class="btn btn-g" style="padding:14px 40px;font-size:15px" onclick="goToApp('search','')">View All Workers →</button>
    </div>
  </section>

  <!-- HOW IT WORKS -->
  <section class="section how-bg" id="sec-how">
    <div style="text-align:center;margin-bottom:8px"><span class="section-badge">🚀 Simple Process</span></div>
    <div class="section-title">How Aetbar Works</div>
    <div class="section-sub">Get a verified home worker in just 4 simple steps</div>
    <div class="how-grid">
      <div class="how-card">
        <div class="how-num grad-green">1</div>
        <h3>Search & Browse</h3>
        <p>Browse verified workers by category, rating, price and location near your home</p>
      </div>
      <div class="how-card">
        <div class="how-num grad-blue">2</div>
        <h3>Book Online</h3>
        <p>View full profiles, read reviews, choose your schedule and book instantly</p>
      </div>
      <div class="how-card">
        <div class="how-num grad-orange">3</div>
        <h3>Pay Securely</h3>
        <p>Pay via Easypaisa or JazzCash. Funds held in escrow until job is complete</p>
      </div>
      <div class="how-card">
        <div class="how-num grad-pink">4</div>
        <h3>Rate & Rehire</h3>
        <p>Rate the worker, build a long-term relationship and rehire with one tap</p>
      </div>
    </div>
  </section>

  <!-- TRUST -->
  <section class="section" id="sec-trust" style="background:#fff">
    <div style="text-align:center;margin-bottom:8px"><span class="section-badge">🛡️ Why Choose Us</span></div>
    <div class="section-title">Pakistan's Most Trusted Platform</div>
    <div class="section-sub">We take safety and reliability seriously so you don't have to worry</div>
    <div class="trust-grid">
      <div class="trust-card">
        <span class="trust-icon">🪪</span>
        <h3>CNIC Verified</h3>
        <p>Every worker's national identity is verified against NADRA records before they can join the platform</p>
      </div>
      <div class="trust-card">
        <span class="trust-icon">👮</span>
        <h3>Police Cleared</h3>
        <p>We require and verify a police clearance certificate from every worker before they appear in search results</p>
      </div>
      <div class="trust-card">
        <span class="trust-icon">💳</span>
        <h3>Escrow Payments</h3>
        <p>Your payment is held securely and only released to the worker after you confirm the job is done</p>
      </div>
      <div class="trust-card">
        <span class="trust-icon">⭐</span>
        <h3>Verified Reviews</h3>
        <p>Only people who actually booked and completed a job can leave a review — no fake ratings</p>
      </div>
      <div class="trust-card">
        <span class="trust-icon">🔎</span>
        <h3>Background Screening</h3>
        <p>We conduct thorough personal background checks and reference verification on every worker before approval</p>
      </div>
      <div class="trust-card">
        <span class="trust-icon">📞</span>
        <h3>24/7 Support</h3>
        <p>Our dedicated support team is available round the clock to help resolve any issues quickly</p>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section class="section" style="background:linear-gradient(160deg,#F5F3FF,#EFF8F4)">
    <div style="text-align:center;margin-bottom:8px"><span class="section-badge">💬 Reviews</span></div>
    <div class="section-title">What Families Are Saying</div>
    <div class="section-sub">Real reviews from real Aetbar customers across Pakistan</div>
    <div class="testimonials">
      <div class="tcard"><div class="quote">"</div><p>Fatima baji has been coming to our home for 4 months. She is punctual, thorough and completely trustworthy. Aetbar made it so easy to find her!</p><div class="tcard-author"><div class="tav" style="background:#E1F5EE;color:#0F6E56">AR</div><div><div style="font-size:13px;font-weight:700">Ahmed Raza</div><div style="font-size:11px;color:var(--txt3)">G-10, Islamabad ⭐⭐⭐⭐⭐</div></div></div></div>
      <div class="tcard"><div class="quote">"</div><p>The electrician Zahid fixed our wiring issue in 2 hours. Knowing he was CNIC-verified and police-cleared gave us complete peace of mind.</p><div class="tcard-author"><div class="tav" style="background:#FAEEDA;color:#633806">SK</div><div><div style="font-size:13px;font-weight:700">Sara Khan</div><div style="font-size:11px;color:var(--txt3)">F-7, Islamabad ⭐⭐⭐⭐⭐</div></div></div></div>
      <div class="tcard"><div class="quote">"</div><p>Muhammad Ali is the best cook we have hired. The escrow payment system is genius — I only paid once I was happy with the food. 10/10!</p><div class="tcard-author"><div class="tav" style="background:#E6F1FB;color:#0C447C">OM</div><div><div style="font-size:13px;font-weight:700">Omar Malik</div><div style="font-size:11px;color:var(--txt3)">DHA, Lahore ⭐⭐⭐⭐⭐</div></div></div></div>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta-section">
    <h2>Ready to Hire? Join 1,284+ Families on Aetbar</h2>
    <p>Pakistan's most trusted platform for verified household workers</p>
    <div class="cta-btns">
      <button class="btn-white" onclick="showModal('register-modal')">🏠 Hire a Worker Today</button>
      <button class="btn btn-w" style="font-size:15px;padding:14px 32px" onclick="showModal('worker-register-modal')">👷 Register as Worker</button>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-grid">
      <div class="footer-brand">
        <div class="logo-f">🏠 Aetbar</div>
        <p>Pakistan's trusted platform to hire verified household workers and skilled professionals. Every worker is CNIC-checked, background-screened and police-cleared for your peace of mind.</p>
        <div class="footer-social">
          <div class="fsocial">📘</div>
          <div class="fsocial">📸</div>
          <div class="fsocial">🐦</div>
          <div class="fsocial">▶️</div>
        </div>
      </div>
      <div class="footer-col">
        <h4>Services</h4>
        <a onclick="goToApp('search','maid')">Maid / Housemaid</a>
        <a onclick="goToApp('search','cook')">Cook / Chef</a>
        <a onclick="goToApp('search','electrician')">Electrician</a>
        <a onclick="goToApp('search','plumber')">Plumber</a>
        <a onclick="goToApp('search','security')">Security Guard</a>
      </div>
      <div class="footer-col">
        <h4>Company</h4>
        <a onclick="showPage('about')">About Us</a>
        <a onclick="showPage('careers')">Careers</a>
        <a onclick="showPage('blog')">Blog</a>
        <a onclick="showPage('contact')">Contact Us</a>
      </div>
      <div class="footer-col">
        <h4>Support</h4>
        <a>Help Centre</a>
        <a>Safety Guidelines</a>
        <a onclick="showPage('privacy')">Privacy Policy</a>
        <a onclick="showPage('terms')">Terms of Service</a>
        <a onclick="showPage('report')">Report an Issue</a>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2025 Aetbar Technologies. Made with ❤️ in Pakistan 🇵🇰</span>
      <div class="footer-cities">
        <div class="fcity">Islamabad</div>
        <div class="fcity">Rawalpindi</div>
        <div class="fcity">Lahore</div>
        <div class="fcity">Karachi</div>
      </div>
    </div>
  </footer>
</div>

<!-- ════════════════════════════════════════
  PAGE OVERLAYS (About, Contact, etc.)
════════════════════════════════════════ -->
<div class="overlay" id="page-about">
  <div class="modal" style="max-width:640px">
    <button class="modal-close" onclick="closeModal('page-about')">✕</button>
    <div style="display:flex;align-items:center;gap:14px;margin-bottom:24px">
      <div style="width:56px;height:56px;background:linear-gradient(135deg,var(--g),var(--teal));border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:26px;flex-shrink:0">🏠</div>
      <div><h3 style="margin-bottom:4px">About Aetbar</h3><p style="font-size:13px;color:var(--txt2)">Pakistan's trusted home services platform</p></div>
    </div>
    <p style="font-size:15px;font-weight:700;margin-bottom:10px;color:var(--g)">Our Story</p>
    <p style="font-size:14px;color:var(--txt2);line-height:1.8;margin-bottom:18px">Aetbar was founded with a simple but powerful idea — every Pakistani family deserves to find reliable, trustworthy home workers without worry or risk. We saw that millions of households struggled to find maids, cooks, electricians and other workers they could actually trust, and millions of skilled workers had no platform to show their abilities and earn fairly.</p>
    <p style="font-size:14px;color:var(--txt2);line-height:1.8;margin-bottom:18px">The name <strong>Aetbar</strong> (اعتبار) means <em>trust</em> in Urdu — and that is exactly what we are built on. We verify every worker's CNIC through NADRA, require a police clearance certificate, conduct background checks and confirm references before anyone appears on our platform.</p>
    <p style="font-size:15px;font-weight:700;margin-bottom:10px;color:var(--g)">Our Mission</p>
    <p style="font-size:14px;color:var(--txt2);line-height:1.8;margin-bottom:18px">To create a safe, transparent and fair marketplace where Pakistani families can hire with complete confidence, and where hardworking people can earn a decent, stable income.</p>
    <p style="font-size:15px;font-weight:700;margin-bottom:10px;color:var(--g)">What Makes Us Different</p>
    <div style="display:grid;gap:10px;margin-bottom:20px">
      <div style="background:var(--gll);border-radius:12px;padding:14px;display:flex;gap:12px;align-items:flex-start"><span style="font-size:20px">🪪</span><div><div style="font-size:13px;font-weight:700">Real CNIC Verification</div><div style="font-size:12px;color:var(--txt2);margin-top:3px">Every worker is matched against NADRA records — not just photographed</div></div></div>
      <div style="background:#EFF6FF;border-radius:12px;padding:14px;display:flex;gap:12px;align-items:flex-start"><span style="font-size:20px">💳</span><div><div style="font-size:13px;font-weight:700">Escrow Payment Protection</div><div style="font-size:12px;color:var(--txt2);margin-top:3px">Your money is safe until you confirm the job is done to your satisfaction</div></div></div>
      <div style="background:var(--ambl);border-radius:12px;padding:14px;display:flex;gap:12px;align-items:flex-start"><span style="font-size:20px">⭐</span><div><div style="font-size:13px;font-weight:700">Honest Review System</div><div style="font-size:12px;color:var(--txt2);margin-top:3px">Only verified customers can leave reviews — no fake or purchased ratings</div></div></div>
    </div>
    <p style="font-size:13px;color:var(--txt3);text-align:center">Currently operating in Islamabad, Rawalpindi, Lahore & Karachi</p>
  </div>
</div>

<div class="overlay" id="page-contact">
  <div class="modal" style="max-width:560px">
    <button class="modal-close" onclick="closeModal('page-contact')">✕</button>
    <div style="display:flex;align-items:center;gap:14px;margin-bottom:24px">
      <div style="width:56px;height:56px;background:linear-gradient(135deg,var(--blu),var(--pur));border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:26px;flex-shrink:0">📞</div>
      <div><h3 style="margin-bottom:4px">Contact Us</h3><p style="font-size:13px;color:var(--txt2)">We are here to help — reach out any time</p></div>
    </div>
    <div style="background:linear-gradient(135deg,var(--gl),#D1FAE5);border-radius:16px;padding:20px;margin-bottom:20px;border:1px solid #9FE1CB">
      <div style="font-size:12px;font-weight:700;color:var(--gd);text-transform:uppercase;letter-spacing:.6px;margin-bottom:12px">Direct Contact</div>
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:12px">
        <div style="width:44px;height:44px;background:var(--g);border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0">👤</div>
        <div><div style="font-size:15px;font-weight:800;color:var(--txt)">Sultan Ali</div><div style="font-size:12px;color:var(--txt2);margin-top:2px">Founder & Chief Executive</div></div>
      </div>
      <a href="tel:03315506907" style="display:flex;align-items:center;gap:10px;background:#fff;border-radius:12px;padding:14px 16px;text-decoration:none;border:1px solid #9FE1CB;margin-bottom:10px;transition:all .15s" onmouseover="this.style.background='var(--gl)'" onmouseout="this.style.background='#fff'">
        <span style="font-size:22px">📱</span>
        <div><div style="font-size:14px;font-weight:800;color:var(--txt)">0331-5506907</div><div style="font-size:11px;color:var(--txt2)">Call or WhatsApp — Mon to Sat, 9am–7pm</div></div>
      </a>
      <a href="https://wa.me/923315506907" style="display:flex;align-items:center;gap:10px;background:#25D366;border-radius:12px;padding:14px 16px;text-decoration:none;margin-bottom:0" target="_blank">
        <span style="font-size:22px">💬</span>
        <div style="color:#fff"><div style="font-size:14px;font-weight:800">WhatsApp Us</div><div style="font-size:11px;opacity:.85">Quick replies on WhatsApp</div></div>
      </a>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:20px">
      <div style="background:#f7f8fa;border-radius:12px;padding:16px;text-align:center;border:1px solid var(--border)"><div style="font-size:24px;margin-bottom:8px">📧</div><div style="font-size:12px;font-weight:700;margin-bottom:4px">Email</div><div style="font-size:12px;color:var(--txt2)">contact@aetbar.pk</div></div>
      <div style="background:#f7f8fa;border-radius:12px;padding:16px;text-align:center;border:1px solid var(--border)"><div style="font-size:24px;margin-bottom:8px">📍</div><div style="font-size:12px;font-weight:700;margin-bottom:4px">Office</div><div style="font-size:12px;color:var(--txt2)">Islamabad, Pakistan</div></div>
    </div>
    <div style="background:var(--ambl);border-radius:12px;padding:14px;border:1px solid #FAC775;font-size:13px;color:#633806">
      <strong>Worker Registration Queries?</strong> Call Sultan Ali directly on the number above. We will guide you through the verification process step by step.
    </div>
  </div>
</div>

<div class="overlay" id="page-careers">
  <div class="modal" style="max-width:640px">
    <button class="modal-close" onclick="closeModal('page-careers')">✕</button>
    <div style="display:flex;align-items:center;gap:14px;margin-bottom:24px">
      <div style="width:56px;height:56px;background:linear-gradient(135deg,var(--pur),var(--pin));border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:26px;flex-shrink:0">💼</div>
      <div><h3 style="margin-bottom:4px">Careers at Aetbar</h3><p style="font-size:13px;color:var(--txt2)">Build Pakistan's most trusted home services platform with us</p></div>
    </div>
    <p style="font-size:14px;color:var(--txt2);line-height:1.8;margin-bottom:22px">We are a young, ambitious Pakistani startup on a mission to transform how families hire home workers. We value hard work, honesty, and a genuine desire to help people. If that sounds like you, we would love to hear from you.</p>
    <p style="font-size:15px;font-weight:700;margin-bottom:14px;color:var(--pur)">Open Positions</p>
    <div style="display:grid;gap:12px;margin-bottom:22px">
      <div style="background:#fff;border:1.5px solid var(--border);border-radius:14px;padding:18px;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--pur)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px">
          <div><div style="font-size:14px;font-weight:800">Field Verification Officer</div><div style="font-size:12px;color:var(--txt2);margin-top:4px">Visit workers at home, verify CNIC documents and collect police clearance certificates. Motorbike required.</div></div>
          <span style="background:var(--gl);color:var(--gd);font-size:10px;font-weight:700;padding:3px 10px;border-radius:10px;white-space:nowrap">Full Time</span>
        </div>
        <div style="margin-top:10px;display:flex;gap:6px"><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Islamabad</span><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Rs 40,000–55,000/month</span></div>
      </div>
      <div style="background:#fff;border:1.5px solid var(--border);border-radius:14px;padding:18px;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--pur)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px">
          <div><div style="font-size:14px;font-weight:800">Customer Support Executive</div><div style="font-size:12px;color:var(--txt2);margin-top:4px">Handle employer and worker queries via phone and WhatsApp. Resolve booking disputes and ensure satisfaction.</div></div>
          <span style="background:var(--blul);color:#0C447C;font-size:10px;font-weight:700;padding:3px 10px;border-radius:10px;white-space:nowrap">Full Time</span>
        </div>
        <div style="margin-top:10px;display:flex;gap:6px"><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Remote / Islamabad</span><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Rs 35,000–50,000/month</span></div>
      </div>
      <div style="background:#fff;border:1.5px solid var(--border);border-radius:14px;padding:18px;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--pur)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px">
          <div><div style="font-size:14px;font-weight:800">City Growth Manager — Lahore</div><div style="font-size:12px;color:var(--txt2);margin-top:4px">Lead Aetbar's expansion in Lahore. Onboard workers, build employer relationships and grow the local user base.</div></div>
          <span style="background:var(--ambl);color:#633806;font-size:10px;font-weight:700;padding:3px 10px;border-radius:10px;white-space:nowrap">Full Time</span>
        </div>
        <div style="margin-top:10px;display:flex;gap:6px"><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Lahore</span><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Rs 60,000–90,000/month</span></div>
      </div>
      <div style="background:#fff;border:1.5px solid var(--border);border-radius:14px;padding:18px;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--pur)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px">
          <div><div style="font-size:14px;font-weight:800">Flutter Mobile Developer</div><div style="font-size:12px;color:var(--txt2);margin-top:4px">Build and maintain the Aetbar Android and iOS apps. Experience with Firebase, REST APIs and clean code required.</div></div>
          <span style="background:var(--gl);color:var(--gd);font-size:10px;font-weight:700;padding:3px 10px;border-radius:10px;white-space:nowrap">Full Time</span>
        </div>
        <div style="margin-top:10px;display:flex;gap:6px"><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Remote</span><span style="font-size:11px;background:#f0f0f0;color:var(--txt2);padding:3px 9px;border-radius:8px">Rs 80,000–140,000/month</span></div>
      </div>
    </div>
    <div style="background:var(--gll);border-radius:12px;padding:16px;text-align:center;border:1px solid #9FE1CB">
      <p style="font-size:13px;color:var(--txt2);margin-bottom:10px">Send your CV to <strong>careers@aetbar.pk</strong> or WhatsApp</p>
      <a href="tel:03315506907" style="display:inline-flex;align-items:center;gap:8px;background:var(--g);color:#fff;padding:10px 22px;border-radius:10px;font-size:13px;font-weight:700;text-decoration:none">📱 0331-5506907</a>
    </div>
  </div>
</div>

<div class="overlay" id="page-blog">
  <div class="modal" style="max-width:660px">
    <button class="modal-close" onclick="closeModal('page-blog')">✕</button>
    <div style="display:flex;align-items:center;gap:14px;margin-bottom:24px">
      <div style="width:56px;height:56px;background:linear-gradient(135deg,var(--ora),var(--amb));border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:26px;flex-shrink:0">📝</div>
      <div><h3 style="margin-bottom:4px">Aetbar Blog</h3><p style="font-size:13px;color:var(--txt2)">Tips, guides and stories from the world of home services</p></div>
    </div>
    <div style="display:grid;gap:16px">
      <div style="border:1.5px solid var(--border);border-radius:16px;overflow:hidden;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--g)';this.style.boxShadow='0 6px 20px rgba(29,158,117,.1)'" onmouseout="this.style.borderColor='var(--border)';this.style.boxShadow=''">
        <div style="background:linear-gradient(135deg,var(--g),var(--teal));padding:20px"><div style="font-size:11px;color:rgba(255,255,255,.75);font-weight:600;text-transform:uppercase;letter-spacing:.5px;margin-bottom:8px">Safety Guide · 5 min read</div><div style="font-size:17px;font-weight:800;color:#fff">How to Safely Hire a Maid or Cook in Pakistan — 7 Things to Always Check</div></div>
        <div style="padding:16px"><p style="font-size:13px;color:var(--txt2);line-height:1.7">Before letting anyone into your home, there are seven critical checks every Pakistani family should make. From CNIC verification to reference calls — we explain exactly what to do and why Aetbar handles all of it for you automatically.</p><div style="margin-top:12px;display:flex;align-items:center;justify-content:space-between"><span style="font-size:11px;color:var(--txt3)">January 15, 2025 · By Aetbar Team</span><span style="font-size:12px;color:var(--g);font-weight:700">Read More →</span></div></div>
      </div>
      <div style="border:1.5px solid var(--border);border-radius:16px;overflow:hidden;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--blu)';this.style.boxShadow='0 6px 20px rgba(55,138,221,.1)'" onmouseout="this.style.borderColor='var(--border)';this.style.boxShadow=''">
        <div style="background:linear-gradient(135deg,var(--blu),var(--pur));padding:20px"><div style="font-size:11px;color:rgba(255,255,255,.75);font-weight:600;text-transform:uppercase;letter-spacing:.5px;margin-bottom:8px">Worker Guide · 4 min read</div><div style="font-size:17px;font-weight:800;color:#fff">How Much Should You Pay a Maid, Cook or Electrician in Islamabad in 2025?</div></div>
        <div style="padding:16px"><p style="font-size:13px;color:var(--txt2);line-height:1.7">Wages for household workers vary widely across Pakistan. We break down fair daily, weekly and monthly rates for different service categories in major cities so you always pay the right amount.</p><div style="margin-top:12px;display:flex;align-items:center;justify-content:space-between"><span style="font-size:11px;color:var(--txt3)">January 8, 2025 · By Aetbar Team</span><span style="font-size:12px;color:var(--blu);font-weight:700">Read More →</span></div></div>
      </div>
      <div style="border:1.5px solid var(--border);border-radius:16px;overflow:hidden;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--amb)';this.style.boxShadow='0 6px 20px rgba(239,159,39,.1)'" onmouseout="this.style.borderColor='var(--border)';this.style.boxShadow=''">
        <div style="background:linear-gradient(135deg,var(--amb),var(--ora));padding:20px"><div style="font-size:11px;color:rgba(255,255,255,.75);font-weight:600;text-transform:uppercase;letter-spacing:.5px;margin-bottom:8px">For Workers · 3 min read</div><div style="font-size:17px;font-weight:800;color:#fff">5 Ways Aetbar is Helping Pakistani Workers Earn More and Get Treated Fairly</div></div>
        <div style="padding:16px"><p style="font-size:13px;color:var(--txt2);line-height:1.7">From escrow payment protection to verified reviews that build your reputation — we explain how Aetbar gives Pakistan's household workers real power and dignity in the workplace.</p><div style="margin-top:12px;display:flex;align-items:center;justify-content:space-between"><span style="font-size:11px;color:var(--txt3)">December 28, 2024 · By Aetbar Team</span><span style="font-size:12px;color:var(--amb);font-weight:700">Read More →</span></div></div>
      </div>
    </div>
  </div>
</div>

<div class="overlay" id="page-privacy">
  <div class="modal" style="max-width:620px">
    <button class="modal-close" onclick="closeModal('page-privacy')">✕</button>
    <h3 style="margin-bottom:6px">Privacy Policy</h3>
    <p style="font-size:12px;color:var(--txt3);margin-bottom:22px">Last updated: January 2025</p>
    <div style="font-size:13px;color:var(--txt2);line-height:1.85;display:grid;gap:16px">
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">1. Information We Collect</div>When you register on Aetbar, we collect your name, phone number, email address and city. For workers, we additionally collect your CNIC number, selfie photograph and police clearance certificate. We also collect information about how you use the app, including bookings, messages and payments.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">2. How We Use Your Information</div>We use your information to create and manage your account, match employers with suitable workers, process payments securely through escrow, send booking confirmations and notifications, verify worker identities for safety purposes, and improve our platform and services.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">3. CNIC and Identity Documents</div>Worker CNIC information is used solely for identity verification. We do not share CNIC numbers with employers or any third parties. Documents are stored securely and can be deleted upon account closure after a mandatory 90-day retention period required by Pakistan's digital services regulations.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">4. Payment Information</div>Aetbar does not store credit card or bank account details. Payments are processed through Easypaisa and JazzCash using their secure gateways. We only store transaction references and amounts for your records and our auditing purposes.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">5. Sharing of Information</div>We do not sell your personal data. We share limited information with workers and employers only as necessary to complete a booking — for example, sharing your area/neighbourhood (not full address) with workers before booking confirmation.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">6. Contact for Privacy Concerns</div>To request deletion of your data or raise a privacy concern, contact us at <strong>privacy@aetbar.pk</strong> or call <strong>0331-5506907</strong>.</div>
    </div>
  </div>
</div>

<div class="overlay" id="page-terms">
  <div class="modal" style="max-width:620px">
    <button class="modal-close" onclick="closeModal('page-terms')">✕</button>
    <h3 style="margin-bottom:6px">Terms of Service</h3>
    <p style="font-size:12px;color:var(--txt3);margin-bottom:22px">Last updated: January 2025 · Applicable under the laws of Pakistan</p>
    <div style="font-size:13px;color:var(--txt2);line-height:1.85;display:grid;gap:16px">
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">1. Acceptance of Terms</div>By registering or using the Aetbar platform (website or mobile application), you agree to these Terms of Service. If you do not agree, please do not use our services.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">2. User Accounts</div>You must be at least 18 years old to use Aetbar. You are responsible for keeping your login credentials secure. You agree to provide accurate and truthful information. False information, including fake CNIC details, will result in immediate permanent account suspension.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">3. Worker Verification</div>Workers must submit genuine CNIC documents, a recent selfie and a valid police clearance certificate. Aetbar reserves the right to reject or suspend any worker profile at its discretion. Verification does not guarantee employment and is not an endorsement.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">4. Bookings and Payments</div>All payments go through Aetbar's escrow system. Payment is released to the worker only after the employer marks the job as completed. Cancellation refunds are subject to our cancellation policy. A 10% platform service fee applies to all completed bookings.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">5. Prohibited Conduct</div>You may not use Aetbar to harass, threaten or mistreat workers or employers. You may not arrange payments outside the platform to avoid service fees. Any attempt to bypass our verification system is strictly prohibited and will result in permanent banning.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">6. Dispute Resolution</div>Disputes between employers and workers should first be raised through the Aetbar platform. Our team will investigate and mediate within 72 hours. Aetbar's decision in disputes is final for matters related to escrow payments.</div>
      <div><div style="font-size:14px;font-weight:700;color:var(--txt);margin-bottom:6px">7. Contact</div>For terms-related questions: <strong>legal@aetbar.pk</strong> · <strong>0331-5506907</strong></div>
    </div>
  </div>
</div>

<div class="overlay" id="page-report">
  <div class="modal" style="max-width:520px">
    <button class="modal-close" onclick="closeModal('page-report')">✕</button>
    <div style="display:flex;align-items:center;gap:14px;margin-bottom:24px">
      <div style="width:56px;height:56px;background:linear-gradient(135deg,var(--red),#C2140F);border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:26px;flex-shrink:0">🚨</div>
      <div><h3 style="margin-bottom:4px">Report an Issue</h3><p style="font-size:13px;color:var(--txt2)">We take all reports seriously and respond within 24 hours</p></div>
    </div>
    <div style="background:var(--redl);border-radius:12px;padding:14px;border:1px solid #F7C1C1;font-size:13px;color:#A32D2D;margin-bottom:20px">
      <strong>For urgent safety issues</strong> — call Sultan Ali directly on <strong>0331-5506907</strong>
    </div>
    <div class="form-group"><label class="flabel">Issue Type</label>
      <select class="finput">
        <option>Worker behaved inappropriately</option>
        <option>Employer mistreated a worker</option>
        <option>Fake or fraudulent profile</option>
        <option>Payment dispute</option>
        <option>Technical problem with the app</option>
        <option>Wrong information on a profile</option>
        <option>Other issue</option>
      </select>
    </div>
    <div class="form-group"><label class="flabel">Your Phone Number</label><input class="finput" placeholder="0300-XXXXXXX" type="tel"></div>
    <div class="form-group"><label class="flabel">Describe the Issue</label><textarea class="finput" rows="4" placeholder="Please provide as much detail as possible so we can investigate quickly..."></textarea></div>
    <button class="btn btn-r" style="width:100%;padding:13px;font-size:15px" onclick="toast('Report submitted. We will contact you within 24 hours.','info');closeModal('page-report')">Submit Report</button>
  </div>
</div>

<!-- ════════════════════════════════════════
  VIEW: APP (after login)
════════════════════════════════════════ -->
<div class="view" id="v-app">
  <div class="app">
    <div class="topbar">
      <div class="tb-logo">🏠 Aetbar</div>
      <div class="app-tabs" style="flex:1;margin:0 16px;border-bottom:none">
        <div class="atab on" onclick="appTab('home')">🏠 Home</div>
        <div class="atab" onclick="appTab('search')">🔍 Search</div>
        <div class="atab" onclick="appTab('bookings')">📅 Bookings</div>
        <div class="atab" onclick="appTab('messages')">💬 Messages</div>
        <div class="atab" onclick="appTab('profile')">👤 Profile</div>
      </div>
      <div class="tb-right">
        <button class="tb-notif" onclick="appTab('notifications')">🔔<div class="ndot" id="notif-dot" style="display:none"></div></button>
        <div class="user-chip" onclick="appTab('profile')">
          <div class="user-av" id="user-av-chip">AR</div>
          <span id="user-name-chip">Ahmed</span>
        </div>
      </div>
    </div>

    <!-- HOME -->
    <div id="tab-home" style="padding:28px 6%;max-width:1200px;margin:0 auto;width:100%">
      <div style="display:flex;align-items:flex-end;justify-content:space-between;margin-bottom:24px;flex-wrap:wrap;gap:12px">
        <div>
          <p style="font-size:11px;color:var(--txt3);font-weight:700;text-transform:uppercase;letter-spacing:.8px">GOOD MORNING</p>
          <h2 id="home-greeting" style="font-size:26px;font-weight:800;margin-top:4px">Ahmed Raza 👋</h2>
          <p style="font-size:13px;color:var(--txt2);margin-top:4px">📍 G-10, Islamabad · Hire verified workers near you</p>
        </div>
        <button class="btn btn-g btn-sm" onclick="appTab('search')">+ New Booking</button>
      </div>
      <div class="search-box" style="margin-bottom:24px;max-width:560px" onclick="appTab('search')">
        <span style="font-size:18px">🔍</span>
        <input placeholder="Search maid, cook, electrician..." readonly style="cursor:pointer;font-size:14px">
        <span style="background:var(--gl);color:var(--gd);font-size:11px;font-weight:700;padding:4px 10px;border-radius:8px">Search</span>
      </div>
      <p class="sec-title">Services</p>
      <div class="services-grid" style="margin-bottom:28px;grid-template-columns:repeat(4,1fr)">
        <div class="service-card sc-1" style="padding:18px 10px" onclick="appTabFilter('search','maid')"><span class="ico" style="font-size:32px">🧹</span><h3 style="font-size:13px">Maid</h3></div>
        <div class="service-card sc-2" style="padding:18px 10px" onclick="appTabFilter('search','cook')"><span class="ico" style="font-size:32px">👨‍🍳</span><h3 style="font-size:13px">Cook</h3></div>
        <div class="service-card sc-3" style="padding:18px 10px" onclick="appTabFilter('search','clothes_wash')"><span class="ico" style="font-size:32px">👔</span><h3 style="font-size:13px">Clothes</h3></div>
        <div class="service-card sc-4" style="padding:18px 10px" onclick="appTabFilter('search','dishwasher')"><span class="ico" style="font-size:32px">🍽️</span><h3 style="font-size:13px">Dishes</h3></div>
        <div class="service-card sc-5" style="padding:18px 10px" onclick="appTabFilter('search','security')"><span class="ico" style="font-size:32px">🔒</span><h3 style="font-size:13px">Security</h3></div>
        <div class="service-card sc-6" style="padding:18px 10px" onclick="appTabFilter('search','electrician')"><span class="ico" style="font-size:32px">⚡</span><h3 style="font-size:13px">Electrician</h3></div>
        <div class="service-card sc-7" style="padding:18px 10px" onclick="appTabFilter('search','plumber')"><span class="ico" style="font-size:32px">🔧</span><h3 style="font-size:13px">Plumber</h3></div>
        <div class="service-card sc-8" style="padding:18px 10px" onclick="appTabFilter('search','gardener')"><span class="ico" style="font-size:32px">🌿</span><h3 style="font-size:13px">Gardener</h3></div>
        <div class="service-card" style="background:linear-gradient(145deg,#FEF3C7,#FDE68A);border-color:#FCD34D;padding:18px 10px" onclick="appTabFilter('search','labourer')"><span class="ico" style="font-size:32px">⛏️</span><h3 style="font-size:13px">Labourer</h3></div>
        <div class="service-card" style="background:linear-gradient(145deg,#FCE7F3,#FBCFE8);border-color:#F9A8D4;padding:18px 10px" onclick="appTabFilter('search','babysitter')"><span class="ico" style="font-size:32px">👶</span><h3 style="font-size:13px">Baby Sitter</h3></div>
        <div class="service-card" style="background:linear-gradient(145deg,#ECFDF5,#D1FAE5);border-color:#6EE7B7;padding:18px 10px" onclick="appTabFilter('search','carpenter')"><span class="ico" style="font-size:32px">🪚</span><h3 style="font-size:13px">Carpenter</h3></div>
        <div class="service-card" style="background:linear-gradient(145deg,#EFF6FF,#DBEAFE);border-color:#93C5FD;padding:18px 10px" onclick="appTabFilter('search','painter')"><span class="ico" style="font-size:32px">🎨</span><h3 style="font-size:13px">Painter</h3></div>
      </div>
      <p class="sec-title">Top Rated Near You</p>
      <div style="display:flex;gap:14px;overflow-x:auto;padding-bottom:10px;margin-bottom:28px" id="home-workers-scroll"></div>
      <p class="sec-title">Active Bookings</p>
      <div id="home-bookings"></div>
    </div>

    <!-- SEARCH -->
    <div id="tab-search" style="display:none;padding:24px;max-width:1200px;margin:0 auto;width:100%">
      <div style="display:flex;gap:12px;margin-bottom:16px;flex-wrap:wrap">
        <div class="search-box" style="flex:1">
          <span style="font-size:16px">🔍</span>
          <input id="search-input" placeholder="Search workers by name, skill or city..." oninput="renderSearch()">
        </div>
        <select class="finput" id="sort-select" onchange="renderSearch()" style="width:180px">
          <option value="rating">⭐ Top Rated</option>
          <option value="price_low">💰 Lowest Price</option>
          <option value="price_high">💎 Highest Price</option>
        </select>
      </div>
      <div class="filter-row" id="cat-filters"></div>
      <p style="font-size:12px;color:var(--txt3);margin-bottom:16px;font-weight:500" id="search-count"></p>
      <div class="results-grid" id="search-results"></div>
    </div>

    <!-- DETAIL -->
    <div id="tab-detail" style="display:none">
      <div class="detail-wrap">
        <button onclick="appTab('search')" style="display:flex;align-items:center;gap:6px;background:none;border:none;cursor:pointer;font-size:14px;font-weight:600;color:var(--txt2);margin-bottom:16px;padding:8px 0"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="15 18 9 12 15 6"/></svg> Back to Search</button>
        <div id="detail-hero" class="detail-hero"></div>
        <div class="detail-grid">
          <div>
            <div class="detail-tabs"><button class="dtab on" id="dt-about" onclick="detailTab('about')">About</button><button class="dtab" id="dt-reviews" onclick="detailTab('reviews')">Reviews</button></div>
            <div id="dp-about"></div>
            <div id="dp-reviews" style="display:none"></div>
          </div>
          <div id="book-box-container"></div>
        </div>
      </div>
    </div>

    <!-- BOOKINGS -->
    <div id="tab-bookings" style="display:none">
      <div class="bookings-wrap">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:20px;flex-wrap:wrap;gap:12px">
          <h2 style="font-size:22px;font-weight:800">My Bookings</h2>
          <div style="display:flex;gap:6px;flex-wrap:wrap">
            <span class="fchip on" id="bf-all" onclick="filterBookings('all')">All</span>
            <span class="fchip" id="bf-active" onclick="filterBookings('active')">🟢 Active</span>
            <span class="fchip" id="bf-completed" onclick="filterBookings('completed')">✅ Completed</span>
            <span class="fchip" id="bf-pending" onclick="filterBookings('pending')">⏳ Pending</span>
          </div>
        </div>
        <div id="bookings-list"></div>
      </div>
    </div>

    <!-- MESSAGES -->
    <div id="tab-messages" style="display:none">
      <div class="chat-wrap">
        <div class="chat-list" id="chat-list"></div>
        <div class="chat-main" id="chat-main" style="display:flex;align-items:center;justify-content:center;flex-direction:column;gap:12px;color:var(--txt3)">
          <span style="font-size:52px">💬</span>
          <p style="font-size:14px;font-weight:500">Select a conversation to start chatting</p>
        </div>
      </div>
    </div>

    <!-- PROFILE -->
    <div id="tab-profile" style="display:none">
      <div class="profile-wrap">
        <div class="profile-hero grad-multi">
          <div class="ph-av" id="profile-av">AR</div>
          <h2 id="profile-name">Ahmed Raza</h2>
          <p id="profile-email">ahmed.raza@gmail.com</p>
          <div style="display:flex;gap:8px;justify-content:center;margin-top:12px;flex-wrap:wrap">
            <span class="hbadge">Employer Account</span>
            <span class="hbadge">✓ CNIC Verified</span>
          </div>
        </div>
        <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:20px" id="profile-stats"></div>
        <div class="wallet-box">
          <div style="font-size:11px;opacity:.7;font-weight:700;letter-spacing:.8px;text-transform:uppercase">AETBAR WALLET</div>
          <div class="bal" id="wallet-bal">Rs 5,200</div>
          <div style="display:flex;gap:10px;margin-top:12px;flex-wrap:wrap">
            <button class="btn btn-w btn-sm" onclick="showModal('topup-modal')">+ Add Money</button>
            <button class="btn btn-w btn-sm">Transaction History</button>
          </div>
        </div>
        <div class="menu-card">
          <div class="menu-item" onclick="showModal('worker-register-modal')"><div class="menu-item-left"><span style="font-size:20px">👷</span>Register as Worker</div><span style="color:var(--txt3)">›</span></div>
          <div class="menu-item" onclick="showView('admin');renderAdmin()"><div class="menu-item-left"><span style="font-size:20px">📊</span>Admin Panel</div><span class="badge bg" style="font-size:9px">Admin</span></div>
          <div class="menu-item"><div class="menu-item-left"><span style="font-size:20px">💳</span>Payment Methods</div><div style="display:flex;align-items:center;gap:6px"><span class="badge bg" style="font-size:9px">Easypaisa ✓</span><span style="color:var(--txt3)">›</span></div></div>
          <div class="menu-item"><div class="menu-item-left"><span style="font-size:20px">🆔</span>CNIC Verification</div><div style="display:flex;align-items:center;gap:6px"><span class="badge bg" style="font-size:9px">Verified ✓</span><span style="color:var(--txt3)">›</span></div></div>
          <div class="menu-item"><div class="menu-item-left"><span style="font-size:20px">🔔</span>Notification Settings</div><span style="color:var(--txt3)">›</span></div>
          <div class="menu-item"><div class="menu-item-left"><span style="font-size:20px">🌐</span>Language / زبان</div><span style="font-size:13px;color:var(--txt2)">English</span></div>
          <div class="menu-item"><div class="menu-item-left"><span style="font-size:20px">❓</span>Help & Support</div><span style="color:var(--txt3)">›</span></div>
          <div class="menu-item" onclick="logout()"><div class="menu-item-left" style="color:var(--red)"><span style="font-size:20px">🚪</span>Sign Out</div></div>
        </div>
        <p style="text-align:center;font-size:11px;color:var(--txt3);margin-top:8px">Aetbar v1.0 · Made in Pakistan 🇵🇰</p>
      </div>
    </div>

    <!-- NOTIFICATIONS -->
    <div id="tab-notifications" style="display:none">
      <div style="max-width:640px;margin:0 auto;padding:28px 24px">
        <h2 style="font-size:22px;font-weight:800;margin-bottom:20px">Notifications</h2>
        <div id="notif-list"></div>
      </div>
    </div>
  </div>
</div>

<!-- ════════════════════════════════════════
  VIEW: ADMIN PANEL
════════════════════════════════════════ -->
<div class="view" id="v-admin">
  <div class="admin-layout">
    <aside class="admin-sidebar">
      <div class="as-logo"><h2>🏠 Aetbar</h2><p>Admin Control Panel</p></div>
      <nav class="as-nav">
        <div class="as-section">Overview</div>
        <div class="as-item on" onclick="adminTab('dashboard')"><span class="ico">📊</span>Dashboard</div>
        <div class="as-item" onclick="adminTab('analytics')"><span class="ico">📈</span>Analytics</div>
        <div class="as-section">People</div>
        <div class="as-item" onclick="adminTab('employers')"><span class="ico">👥</span>Employers</div>
        <div class="as-item" onclick="adminTab('workers')"><span class="ico">👷</span>Workers</div>
        <div class="as-item" onclick="adminTab('verify')"><span class="ico">🛡️</span>Verification <span id="pending-badge" style="background:var(--red);color:#fff;font-size:9px;padding:2px 7px;border-radius:10px;margin-left:auto"></span></div>
        <div class="as-section">Operations</div>
        <div class="as-item" onclick="adminTab('bookings-admin')"><span class="ico">📅</span>Bookings</div>
        <div class="as-item" onclick="adminTab('payments-admin')"><span class="ico">💰</span>Payments</div>
        <div class="as-item" onclick="adminTab('disputes')"><span class="ico">⚖️</span>Disputes</div>
        <div class="as-section">System</div>
        <div class="as-item" onclick="adminTab('settings')"><span class="ico">⚙️</span>Settings</div>
        <div class="as-item" onclick="showView('app');appTab('home')"><span class="ico">↩️</span>Back to App</div>
      </nav>
    </aside>
    <main class="admin-main">
      <div class="admin-topbar">
        <h2 id="admin-page-title">Dashboard</h2>
        <div style="display:flex;align-items:center;gap:10px">
          <div style="width:8px;height:8px;background:#22C55E;border-radius:50%"></div>
          <span class="badge bg" style="padding:5px 12px;font-size:11px">Super Admin</span>
        </div>
      </div>
      <div class="admin-content on" id="ac-dashboard"></div>
      <div class="admin-content" id="ac-analytics"></div>
      <div class="admin-content" id="ac-employers"></div>
      <div class="admin-content" id="ac-workers"></div>
      <div class="admin-content" id="ac-verify"></div>
      <div class="admin-content" id="ac-bookings-admin"></div>
      <div class="admin-content" id="ac-payments-admin"></div>
      <div class="admin-content" id="ac-disputes"></div>
      <div class="admin-content" id="ac-settings"></div>
    </main>
  </div>
</div>

<!-- ════════════════════════════════════════
  MODALS
════════════════════════════════════════ -->
<div class="overlay" id="login-modal">
  <div class="modal">
    <button class="modal-close" onclick="closeModal('login-modal')">✕</button>
    <div style="text-align:center;margin-bottom:24px">
      <div style="font-size:40px;margin-bottom:8px">🔐</div>
      <h3 style="margin-bottom:4px">Welcome Back</h3>
      <p style="font-size:13px;color:var(--txt2)">Login to your Aetbar account</p>
    </div>
    <div class="form-group"><label class="flabel">Phone Number</label><input class="finput" id="login-phone" placeholder="0300-XXXXXXX" type="tel"></div>
    <div class="form-group"><label class="flabel">Password</label><input class="finput" id="login-pass" placeholder="Your password" type="password"></div>
    <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px;margin-top:8px" onclick="doLogin()">Login to Aetbar →</button>
    <p style="text-align:center;margin-top:16px;font-size:13px;color:var(--txt2)">No account? <a style="color:var(--g);cursor:pointer;font-weight:700" onclick="closeModal('login-modal');showModal('register-modal')">Register here</a></p>
  </div>
</div>

<div class="overlay" id="register-modal">
  <div class="modal">
    <button class="modal-close" onclick="closeModal('register-modal')">✕</button>
    <div style="text-align:center;margin-bottom:24px">
      <div style="font-size:40px;margin-bottom:8px">🏠</div>
      <h3 style="margin-bottom:4px">Create Account</h3>
      <p style="font-size:13px;color:var(--txt2)">Join 1,284+ families on Aetbar</p>
    </div>
    <div class="form-group"><label class="flabel">Full Name</label><input class="finput" id="reg-name" placeholder="Muhammad Ahmed"></div>
    <div class="form-group"><label class="flabel">Phone Number</label><input class="finput" id="reg-phone" placeholder="0300-XXXXXXX" type="tel"></div>
    <div class="form-group"><label class="flabel">Email (optional)</label><input class="finput" id="reg-email" placeholder="email@example.com" type="email"></div>
    <div class="form-group"><label class="flabel">Password</label><input class="finput" id="reg-pass" placeholder="Minimum 4 characters" type="password"></div>
    <div class="form-group"><label class="flabel">City</label>
      <select class="finput" id="reg-city"><option>Islamabad</option><option>Rawalpindi</option><option>Lahore</option><option>Karachi</option></select>
    </div>
    <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px;margin-top:8px" onclick="doRegister()">Create My Account →</button>
    <p style="text-align:center;margin-top:16px;font-size:13px;color:var(--txt2)">Already have account? <a style="color:var(--g);cursor:pointer;font-weight:700" onclick="closeModal('register-modal');showModal('login-modal')">Login</a></p>
  </div>
</div>

<div class="overlay" id="worker-register-modal">
  <div class="modal">
    <button class="modal-close" onclick="closeModal('worker-register-modal')">✕</button>
    <div style="text-align:center;margin-bottom:24px">
      <div style="font-size:40px;margin-bottom:8px">👷</div>
      <h3 style="margin-bottom:4px">Register as Worker</h3>
      <p style="font-size:13px;color:var(--txt2)">Start earning on Aetbar today</p>
    </div>
    <div class="notice notice-g"><span>💰</span><div>Average workers earn <strong>Rs 18,000–35,000/month</strong> on Aetbar.</div></div>
    <div class="form-group"><label class="flabel">Full Name (as on CNIC)</label><input class="finput" id="wr-name" placeholder="Full name"></div>
    <div class="form-group"><label class="flabel">CNIC Number</label><input class="finput" id="wr-cnic" placeholder="XXXXX-XXXXXXX-X"></div>
    <div class="form-group"><label class="flabel">Phone</label><input class="finput" id="wr-phone" placeholder="0300-XXXXXXX" type="tel"></div>
    <div class="form-group"><label class="flabel">Service Category</label>
      <select class="finput" id="wr-cat">
        <option value="maid">🧹 Maid / House Cleaning</option>
        <option value="cook">👨‍🍳 Cook / Chef</option>
        <option value="clothes_wash">👔 Clothes Washing</option>
        <option value="dishwasher">🍽️ Dishwashing</option>
        <option value="security">🔒 Security Guard</option>
        <option value="electrician">⚡ Electrician</option>
        <option value="plumber">🔧 Plumber</option>
        <option value="gardener">🌿 Gardener</option>
        <option value="labourer">⛏️ Labourer (Daily Wages)</option>
        <option value="babysitter">👶 Baby Sitter / Child Care</option>
        <option value="carpenter">🪚 Carpenter</option>
        <option value="painter">🎨 Painter</option>
      </select>
    </div>
    <div class="form-group"><label class="flabel">Expected Daily Rate (Rs)</label><input class="finput" id="wr-rate" placeholder="e.g. 800" type="number"></div>
    <div class="form-group"><label class="flabel">City & Area</label><input class="finput" id="wr-city" placeholder="G-10, Islamabad"></div>
    <div class="notice notice-a"><span>🆔</span><div><strong>Verification Required:</strong> CNIC photos, selfie & police clearance letter. Approval takes 24–48 hours.</div></div>
    <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px" onclick="doWorkerRegister()">Submit Application →</button>
  </div>
</div>

<div class="overlay" id="book-modal">
  <div class="modal">
    <button class="modal-close" onclick="closeModal('book-modal')">✕</button>
    <h3>Book Worker</h3>
    <div id="book-modal-worker-info" style="margin-bottom:18px"></div>
    <div class="form-group"><label class="flabel">Package</label>
      <select class="finput" id="bm-package"><option value="daily">Daily</option><option value="weekly">Weekly (save 30%)</option><option value="monthly">Monthly (save 42%)</option></select>
    </div>
    <div class="form-group"><label class="flabel">Start Date</label><input class="finput" id="bm-date" type="date"></div>
    <div class="form-group"><label class="flabel">Working Hours</label>
      <select class="finput" id="bm-hours"><option>Morning (8am–12pm)</option><option>Afternoon (12pm–4pm)</option><option>Full Day (8am–4pm)</option></select>
    </div>
    <div class="form-group"><label class="flabel">Your Address</label><input class="finput" id="bm-address" placeholder="House #, Street, Area, City"></div>
    <div class="form-group"><label class="flabel">Special Instructions</label><textarea class="finput" id="bm-notes" rows="2" placeholder="e.g. focus on kitchen and bathrooms..."></textarea></div>
    <div class="notice notice-g"><span>💳</span><div><strong>Secure Escrow</strong> — Pay via Easypaisa or JazzCash. Released only after you confirm job is done.</div></div>
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;padding:14px;background:var(--gll);border-radius:12px">
      <span style="font-weight:700;font-size:15px">Total Amount:</span>
      <span id="bm-total" style="font-size:22px;font-weight:800;color:var(--g)">Rs 800</span>
    </div>
    <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px" onclick="confirmBooking()">✓ Confirm Booking</button>
  </div>
</div>

<div class="overlay" id="topup-modal">
  <div class="modal">
    <button class="modal-close" onclick="closeModal('topup-modal')">✕</button>
    <h3>💰 Add Money to Wallet</h3>
    <div class="form-group"><label class="flabel">Amount (Rs)</label><input class="finput" id="topup-amount" placeholder="Enter amount (min Rs 100)" type="number" min="100"></div>
    <div class="form-group"><label class="flabel">Payment Method</label>
      <select class="finput" id="topup-method"><option>📱 Easypaisa</option><option>💚 JazzCash</option><option>🏦 Bank Transfer</option></select>
    </div>
    <div class="notice notice-a"><span>📱</span><div>Send to Aetbar Easypaisa: <strong>0300-AETBAR1</strong> — then enter the amount above to confirm.</div></div>
    <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px" onclick="doTopup()">Add Money →</button>
  </div>
</div>

<script>
// ════════════════════════════════════════
// DATABASE
// ════════════════════════════════════════
const DB={
  get:k=>{try{return JSON.parse(localStorage.getItem('aetbar_'+k))||null}catch{return null}},
  set:(k,v)=>localStorage.setItem('aetbar_'+k,JSON.stringify(v)),
  init(){
    if(!this.get('workers'))this.set('workers',SEED.workers);
    if(!this.get('users'))this.set('users',SEED.users);
    if(!this.get('bookings'))this.set('bookings',SEED.bookings);
    if(!this.get('messages'))this.set('messages',SEED.messages);
    if(!this.get('notifications'))this.set('notifications',SEED.notifications);
    if(!this.get('transactions'))this.set('transactions',SEED.transactions);
  },
  getWorkers(){return this.get('workers')||[]},
  getUsers(){return this.get('users')||[]},
  getBookings(uid){const a=this.get('bookings')||[];return uid?a.filter(b=>b.employer_id===uid):a},
  addBooking(b){const a=this.get('bookings')||[];a.unshift(b);this.set('bookings',a)},
  addUser(u){const a=this.get('users')||[];a.push(u);this.set('users',a)},
  addWorker(w){const a=this.get('workers')||[];a.push(w);this.set('workers',a)},
  updateBookingStatus(id,s){const a=this.get('bookings')||[];const i=a.findIndex(b=>b.id===id);if(i>-1){a[i].status=s;this.set('bookings',a)}},
  addTransaction(t){const a=this.get('transactions')||[];a.unshift(t);this.set('transactions',a)},
  updateUserBalance(uid,amt){
    const u=this.get('users')||[];const i=u.findIndex(x=>x.id===uid);
    if(i>-1){u[i].wallet_balance=(u[i].wallet_balance||0)+amt;this.set('users',u);
      if(appState.user&&appState.user.id===uid){appState.user.wallet_balance=u[i].wallet_balance;localStorage.setItem('aetbar_session',JSON.stringify(appState.user))}}
  }
};
const SEED={
  workers:[
    {id:'w1',name:'Fatima Khan',initials:'FK',color:'#E1F5EE',fgColor:'#0F6E56',grad:'linear-gradient(135deg,#1D9E75,#0F6E56)',role:'Maid',category:'maid',emoji:'🧹',rating:4.9,reviews:87,daily_rate:800,rate_label:'/day',verified:true,online:true,city:'G-10, Islamabad',exp:3,skills:['Deep Cleaning','Laundry','Ironing','Dishwashing','Child Care'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Experienced maid specialising in deep cleaning, laundry and ironing. Non-smoker, reliable and discreet.',jobs:87},
    {id:'w2',name:'Muhammad Ali',initials:'MA',color:'#FAEEDA',fgColor:'#633806',grad:'linear-gradient(135deg,#EF9F27,#C47D0E)',role:'Cook',category:'cook',emoji:'👨‍🍳',rating:4.8,reviews:63,daily_rate:1200,rate_label:'/day',verified:true,online:false,city:'G-11, Islamabad',exp:5,skills:['Pakistani Cuisine','BBQ','Baking','Continental','Desserts'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Professional cook with 5 years experience in Pakistani and continental cuisine.',jobs:63},
    {id:'w3',name:'Zahid Butt',initials:'ZB',color:'#E6F1FB',fgColor:'#0C447C',grad:'linear-gradient(135deg,#378ADD,#1B5FA8)',role:'Electrician',category:'electrician',emoji:'⚡',rating:4.7,reviews:44,daily_rate:2000,rate_label:'/job',verified:true,online:true,city:'F-7, Islamabad',exp:8,skills:['Wiring','Fan Install','AC Repair','Generator','MCB/DB'],days:['Mon','Tue','Wed','Thu','Fri'],bio:'Certified electrician with 8 years experience. Residential and emergency repairs.',jobs:44},
    {id:'w4',name:'Rukhsana Naz',initials:'RN',color:'#FBEAF0',fgColor:'#72243E',grad:'linear-gradient(135deg,#EC4899,#9D1558)',role:'Clothes Washer',category:'clothes_wash',emoji:'👔',rating:5.0,reviews:29,daily_rate:600,rate_label:'/day',verified:true,online:false,city:'G-9, Islamabad',exp:4,skills:['Hand Wash','Machine Wash','Ironing','Delicate Fabrics'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Clothes washing specialist. Handles all fabric types with utmost care.',jobs:29},
    {id:'w5',name:'Imran Haider',initials:'IH',color:'#E0F2FE',fgColor:'#0369A1',grad:'linear-gradient(135deg,#0EA5E9,#0369A1)',role:'Security Guard',category:'security',emoji:'🔒',rating:4.6,reviews:18,daily_rate:1500,rate_label:'/day',verified:true,online:true,city:'I-8, Islamabad',exp:6,skills:['Night Guard','CCTV Monitor','Gate Duty','First Aid'],days:['Mon','Tue','Wed','Thu','Fri','Sat','Sun'],bio:'Ex-army security professional. Day and night duty available. Valid security license.',jobs:18},
    {id:'w6',name:'Saba Begum',initials:'SB',color:'#FBEAF0',fgColor:'#72243E',grad:'linear-gradient(135deg,#F97316,#C2410C)',role:'Maid',category:'maid',emoji:'🧹',rating:4.8,reviews:120,daily_rate:900,rate_label:'/day',verified:true,online:false,city:'G-8, Islamabad',exp:5,skills:['Cooking','Child Care','Deep Cleaning','Laundry'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Experienced maid, also handles light cooking and child care. Trusted by 50+ families.',jobs:120},
    {id:'w7',name:'Asif Khan',initials:'AK',color:'#EDE9FE',fgColor:'#5B21B6',grad:'linear-gradient(135deg,#7C3AED,#5B21B6)',role:'Plumber',category:'plumber',emoji:'🔧',rating:4.5,reviews:32,daily_rate:1800,rate_label:'/job',verified:true,online:true,city:'F-8, Islamabad',exp:7,skills:['Pipe Repair','Fitting','Drainage','Geyser','CPVC'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Licensed plumber with 7 years experience. Emergency repairs available 24/7.',jobs:32},
    {id:'w8',name:'Nadia Iqbal',initials:'NI',color:'#E1F5EE',fgColor:'#085041',grad:'linear-gradient(135deg,#1D9E75,#0F6E56)',role:'Maid',category:'maid',emoji:'🧹',rating:0,reviews:0,daily_rate:700,rate_label:'/day',verified:false,online:false,city:'I-8, Islamabad',exp:1,skills:['Cleaning','Dishes'],days:['Mon','Tue','Wed','Thu','Fri'],bio:'New to the platform. Hardworking and eager to provide great service.',jobs:0},
    {id:'w9',name:'Tariq Mehmood',initials:'TM',color:'#FEF3C7',fgColor:'#92400E',grad:'linear-gradient(135deg,#D97706,#92400E)',role:'Labourer',category:'labourer',emoji:'⛏️',rating:4.4,reviews:21,daily_rate:700,rate_label:'/day',verified:true,online:true,city:'G-7, Islamabad',exp:6,skills:['Loading & Unloading','Heavy Lifting','Construction','Digging','Demolition'],days:['Mon','Tue','Wed','Thu','Fri','Sat','Sun'],bio:'Experienced daily wage labourer available for construction sites, house moves and general heavy work. Available 7 days a week.',jobs:21},
    {id:'w10',name:'Amna Bibi',initials:'AB',color:'#FCE7F3',fgColor:'#9D174D',grad:'linear-gradient(135deg,#EC4899,#9D174D)',role:'Baby Sitter',category:'babysitter',emoji:'👶',rating:4.8,reviews:15,daily_rate:900,rate_label:'/day',verified:true,online:false,city:'F-6, Islamabad',exp:4,skills:['Infant Care','Toddler Activities','Feeding','Nap Routines','First Aid'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Caring and experienced child minder specialising in infants and toddlers. First aid certified. Non-smoker.',jobs:15},
    {id:'w11',name:'Khalid Rehman',initials:'KR',color:'#ECFDF5',fgColor:'#065F46',grad:'linear-gradient(135deg,#10B981,#065F46)',role:'Carpenter',category:'carpenter',emoji:'🪚',rating:4.6,reviews:38,daily_rate:1600,rate_label:'/day',verified:true,online:true,city:'I-10, Islamabad',exp:10,skills:['Furniture Making','Doors & Windows','Wood Polish','Custom Woodwork','Repairs'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Skilled carpenter with 10 years experience. Custom furniture, doors, cabinets and all woodwork.',jobs:38},
    {id:'w12',name:'Shakeel Ahmed',initials:'SA',color:'#EFF6FF',fgColor:'#1E40AF',grad:'linear-gradient(135deg,#3B82F6,#1E40AF)',role:'Painter',category:'painter',emoji:'🎨',rating:4.5,reviews:27,daily_rate:1400,rate_label:'/day',verified:true,online:false,city:'G-13, Islamabad',exp:8,skills:['Interior Painting','Exterior Painting','Wall Polish','Texture Work','POP Design'],days:['Mon','Tue','Wed','Thu','Fri','Sat'],bio:'Professional painter specialising in interior and exterior work. Clean finish guaranteed.',jobs:27},
  ],
  users:[
    {id:'u1',name:'Ahmed Raza',initials:'AR',phone:'0300-1234567',email:'ahmed@example.com',password:'1234',role:'employer',city:'Islamabad',area:'G-10',wallet_balance:5200,rating:4.8},
    {id:'u2',name:'Admin',initials:'AD',phone:'admin',email:'admin@aetbar.pk',password:'admin123',role:'admin',city:'Islamabad',area:'F-7',wallet_balance:0,rating:5.0},
  ],
  bookings:[
    {id:'b1',employer_id:'u1',worker_id:'w1',service:'Maid – Full Clean',schedule:'Mon, Wed, Fri',package:'monthly',amount:3200,status:'active',date:'Jan 2025',next:'Monday, 8:00 AM',address:'G-10/3, Street 12'},
    {id:'b2',employer_id:'u1',worker_id:'w2',service:'Cook – Lunch & Dinner',schedule:'Mon–Sat',package:'monthly',amount:28000,status:'active',date:'Dec 2024',next:'Working now',address:'G-10/3, Street 12'},
    {id:'b3',employer_id:'u1',worker_id:'w3',service:'Electrician – Fan Install',schedule:'One-time',package:'daily',amount:2000,status:'completed',date:'Dec 28, 2024',next:'',address:'G-10/3, Street 12'},
    {id:'b4',employer_id:'u1',worker_id:'w5',service:'Security Guard – Night',schedule:'Night shift',package:'daily',amount:1500,status:'pending',date:'Jan 10, 2025',next:'Jan 10, 2025',address:'G-10/3, Street 12'},
  ],
  messages:{
    w1:[{from:'worker',text:'Assalam o Alaikum! Available Monday morning inshallah.',time:'9:12 AM'},{from:'user',text:'Walaikum Assalam! Please come at 8am. Focus on kitchen and bathrooms.',time:'9:25 AM'},{from:'worker',text:'Ji zaroor! Will bring all supplies. See you Monday!',time:'9:28 AM'},{from:'user',text:'Payment in escrow, will release after job done.',time:'9:30 AM'},{from:'worker',text:'Shukriya! 🙏',time:'9:31 AM'}],
    w2:[{from:'user',text:'Ali bhai, kya aaj biryani ban sakti hai?',time:'Yesterday'},{from:'worker',text:'Ji zaroor sir! Chicken ya mutton?',time:'Yesterday'},{from:'user',text:'Chicken please.',time:'Yesterday'},{from:'worker',text:'Ji 1 baje ready ho jaye gi.',time:'Yesterday'}],
    w3:[{from:'worker',text:'Fan installation complete. Please release payment.',time:'Dec 28'},{from:'user',text:'Working great! Payment released. Shukriya!',time:'Dec 28'}],
  },
  notifications:[
    {id:'n1',icon:'✅',title:'Booking Confirmed',body:'Fatima Khan accepted your Monday booking.',time:'Just now',read:false,color:'var(--g)'},
    {id:'n2',icon:'⭐',title:'Rate Zahid Butt',body:'How was the electrician service on Dec 28?',time:'2 hours ago',read:false,color:'var(--amb)'},
    {id:'n3',icon:'💰',title:'Payment Released',body:'Rs 2,000 sent to Zahid Butt via Easypaisa.',time:'Yesterday',read:true,color:'var(--g)'},
    {id:'n4',icon:'🛡️',title:'New Worker Nearby',body:'A new verified cook joined near G-10 Islamabad.',time:'2 days ago',read:true,color:'var(--blu)'},
  ],
  transactions:[
    {id:'t1',type:'payment',desc:'Fatima Khan – Maid',amount:-800,date:'Jan 1, 2025'},
    {id:'t2',type:'payment',desc:'Zahid Butt – Electrician',amount:-2000,date:'Dec 28, 2024'},
    {id:'t3',type:'topup',desc:'Wallet Top-up via Easypaisa',amount:10000,date:'Dec 25, 2024'},
  ]
};

// ════════════════════════════════════════
// STATE & INIT
// ════════════════════════════════════════
let appState={user:null,currentWorker:null,bookingWorker:null,activeChatWorker:null,bookingFilter:'all',searchFilter:'all'};
DB.init();
// Force refresh workers so new seed data always loads
DB.set('workers', SEED.workers);
const session=localStorage.getItem('aetbar_session');
if(session){try{appState.user=JSON.parse(session);if(appState.user.role==='admin'){showView('admin');renderAdmin()}else{showView('app');initApp()}}catch{showView('landing');renderLanding()}}
else{showView('landing');renderLanding()}

// ════════════════════════════════════════
// VIEW + MODAL + TOAST
// ════════════════════════════════════════
function showView(n){document.querySelectorAll('.view').forEach(v=>v.classList.remove('active'));document.getElementById('v-'+n).classList.add('active');window.scrollTo(0,0)}
function showModal(id){document.getElementById(id).classList.add('open')}
function closeModal(id){document.getElementById(id).classList.remove('open')}
function toast(msg,type='success'){const t=document.getElementById('toast');t.textContent=msg;t.className='toast show '+type;setTimeout(()=>t.classList.remove('show'),3500)}
function showPage(name){const map={about:'page-about',contact:'page-contact',careers:'page-careers',blog:'page-blog',privacy:'page-privacy',terms:'page-terms',report:'page-report'};if(map[name])showModal(map[name])}
function scrollToId(id){const el=document.getElementById(id);if(el)el.scrollIntoView({behavior:'smooth',block:'start'})}
function scrollToTop(){window.scrollTo({top:0,behavior:'smooth'})}

// ════════════════════════════════════════
// AUTH
// ════════════════════════════════════════
function doLogin(){
  const phone=document.getElementById('login-phone').value.trim();
  const pass=document.getElementById('login-pass').value.trim();
  if(!phone||!pass){toast('Please fill all fields','error');return}
  const user=DB.getUsers().find(u=>u.phone===phone&&u.password===pass);
  if(!user){toast('Invalid phone or password','error');return}
  appState.user=user;localStorage.setItem('aetbar_session',JSON.stringify(user));
  closeModal('login-modal');toast('Welcome back, '+user.name.split(' ')[0]+'! 👋');
  if(user.role==='admin'){showView('admin');renderAdmin()}else{showView('app');initApp()}
}
function doRegister(){
  const name=document.getElementById('reg-name').value.trim();
  const phone=document.getElementById('reg-phone').value.trim();
  const email=document.getElementById('reg-email').value.trim();
  const pass=document.getElementById('reg-pass').value.trim();
  const city=document.getElementById('reg-city').value;
  if(!name||!phone||!pass){toast('Please fill all required fields','error');return}
  if(pass.length<4){toast('Password too short','error');return}
  if(DB.getUsers().find(u=>u.phone===phone)){toast('Phone already registered','error');return}
  const user={id:'u'+Date.now(),name,initials:name.split(' ').map(w=>w[0]).join('').toUpperCase().slice(0,2),phone,email,password:pass,role:'employer',city,area:'',wallet_balance:0,rating:5.0};
  DB.addUser(user);appState.user=user;localStorage.setItem('aetbar_session',JSON.stringify(user));
  closeModal('register-modal');toast('Welcome to Aetbar, '+name.split(' ')[0]+'! 🎉');showView('app');initApp()
}
function doWorkerRegister(){
  const name=document.getElementById('wr-name').value.trim();
  const cnic=document.getElementById('wr-cnic').value.trim();
  const phone=document.getElementById('wr-phone').value.trim();
  const cat=document.getElementById('wr-cat').value;
  const rate=document.getElementById('wr-rate').value;
  const city=document.getElementById('wr-city').value.trim();
  if(!name||!cnic||!phone||!rate){toast('Please fill all required fields','error');return}
  const catMap={maid:'Maid',cook:'Cook',clothes_wash:'Clothes Washer',dishwasher:'Dishwasher',security:'Security Guard',electrician:'Electrician',plumber:'Plumber',gardener:'Gardener'};
  const emojiMap={maid:'🧹',cook:'👨‍🍳',clothes_wash:'👔',dishwasher:'🍽️',security:'🔒',electrician:'⚡',plumber:'🔧',gardener:'🌿'};
  const gradMap={maid:'linear-gradient(135deg,#1D9E75,#0F6E56)',cook:'linear-gradient(135deg,#EF9F27,#C47D0E)',electrician:'linear-gradient(135deg,#378ADD,#1B5FA8)',plumber:'linear-gradient(135deg,#7C3AED,#5B21B6)',security:'linear-gradient(135deg,#0EA5E9,#0369A1)',clothes_wash:'linear-gradient(135deg,#EC4899,#9D1558)',dishwasher:'linear-gradient(135deg,#22C55E,#15803D)',gardener:'linear-gradient(135deg,#84CC16,#4D7C0F)',labourer:'linear-gradient(135deg,#D97706,#92400E)',babysitter:'linear-gradient(135deg,#EC4899,#9D174D)',carpenter:'linear-gradient(135deg,#10B981,#065F46)',painter:'linear-gradient(135deg,#3B82F6,#1E40AF)'};
  const w={id:'w'+Date.now(),name,initials:name.split(' ').map(x=>x[0]).join('').toUpperCase().slice(0,2),color:'#E1F5EE',fgColor:'#0F6E56',grad:gradMap[cat]||'linear-gradient(135deg,#1D9E75,#0F6E56)',role:catMap[cat],category:cat,emoji:emojiMap[cat],rating:0,reviews:0,daily_rate:parseInt(rate),rate_label:'/day',verified:false,online:false,city,exp:0,skills:[],days:['Mon','Tue','Wed','Thu','Fri'],bio:'New worker profile. Pending verification.',jobs:0};
  DB.addWorker(w);
  const pending=DB.get('pending_workers')||[];pending.push({...w,cnic,phone,applied:new Date().toLocaleDateString()});DB.set('pending_workers',pending);
  closeModal('worker-register-modal');toast('Application submitted! Verification takes 24–48 hours. ✅')
}
function logout(){localStorage.removeItem('aetbar_session');appState.user=null;showView('landing');renderLanding();toast('Logged out successfully','info')}

// ════════════════════════════════════════
// LANDING
// ════════════════════════════════════════
function renderLanding(){
  const workers=DB.getWorkers().filter(w=>w.verified).slice(0,3);
  document.getElementById('landing-workers').innerHTML=workers.map(w=>`
    <div class="worker-card" onclick="goToApp('detail','${w.id}')">
      <div class="wc-top" style="background:${w.grad}">
        <div class="wc-av">${w.initials}</div>
        <div class="wc-info"><h4>${w.name}</h4><p>${w.emoji} ${w.role} · ${w.exp} yrs exp</p>${w.online?'<p style="color:#A8EDCB;font-size:11px;margin-top:3px">● Online now</p>':''}</div>
        ${w.verified?'<div class="wc-verified">✓ Verified</div>':''}
      </div>
      <div class="wc-body">
        <div class="wc-stats">
          <div class="wcs"><div class="n">Rs ${w.daily_rate}</div><div class="l">Per Day</div></div>
          <div class="wcs"><div class="n">${w.rating>0?w.rating:'New'}</div><div class="l">Rating</div></div>
          <div class="wcs"><div class="n">${w.jobs}</div><div class="l">Jobs</div></div>
        </div>
        <div class="skills-row">${w.skills.slice(0,3).map(s=>`<span class="badge bg">${s}</span>`).join('')}</div>
        <button class="btn btn-g" style="width:100%;margin-top:14px;padding:11px" onclick="event.stopPropagation();goToApp('detail','${w.id}')">View Profile →</button>
      </div>
    </div>`).join('')
}
function goToApp(tab,param){
  if(!appState.user){showModal('login-modal');return}
  showView('app');
  if(tab==='detail'){loadWorkerDetail(param);appTab('detail')}
  else if(tab==='search'){appState.searchFilter=param||'all';appTab('search')}
  else appTab(tab)
}

// ════════════════════════════════════════
// APP TABS
// ════════════════════════════════════════
function initApp(){
  const u=appState.user;
  document.getElementById('home-greeting').textContent=u.name+' 👋';
  document.getElementById('user-av-chip').textContent=u.initials;
  document.getElementById('user-name-chip').textContent=u.name.split(' ')[0];
  document.getElementById('profile-av').textContent=u.initials;
  document.getElementById('profile-name').textContent=u.name;
  document.getElementById('profile-email').textContent=u.email||u.phone;
  document.getElementById('wallet-bal').textContent='Rs '+(u.wallet_balance||0).toLocaleString();
  renderProfileStats();renderHomeWorkers();renderHomeBookings();renderSearch();renderChatList();renderNotifs();checkNotifDot();appTab('home')
}
function appTab(name){
  document.querySelectorAll('.atab').forEach(t=>t.classList.remove('on'));
  ['home','search','detail','bookings','messages','profile','notifications'].forEach(t=>{const el=document.getElementById('tab-'+t);if(el)el.style.display=t===name?'block':'none'});
  const tabMap={home:0,search:1,bookings:2,messages:3,profile:4};
  const els=document.querySelectorAll('.atab');
  if(tabMap[name]!==undefined&&els[tabMap[name]])els[tabMap[name]].classList.add('on');
  if(name==='bookings')renderBookings();
  if(name==='search')renderSearch();
  if(name==='notifications'){renderNotifs();markNotifsRead()}
}
function appTabFilter(tab,cat){appState.searchFilter=cat;appTab(tab)}

// ════════════════════════════════════════
// HOME
// ════════════════════════════════════════
function renderHomeWorkers(){
  const workers=DB.getWorkers().filter(w=>w.verified).slice(0,6);
  document.getElementById('home-workers-scroll').innerHTML=workers.map(w=>`
    <div style="background:#fff;border-radius:18px;border:1.5px solid var(--border);padding:18px;min-width:160px;flex-shrink:0;cursor:pointer;transition:all .2s;box-shadow:0 2px 10px rgba(0,0,0,.05)" onclick="loadWorkerDetail('${w.id}');appTab('detail')" onmouseover="this.style.borderColor='var(--g)';this.style.transform='translateY(-3px)'" onmouseout="this.style.borderColor='var(--border)';this.style.transform=''">
      <div style="width:48px;height:48px;border-radius:50%;background:${w.grad};display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:800;color:#fff;box-shadow:0 4px 12px rgba(0,0,0,.15)">${w.initials}</div>
      <div style="font-size:14px;font-weight:700;margin-top:10px">${w.name}</div>
      <div style="font-size:11px;color:var(--txt2);margin-top:2px">${w.emoji} ${w.role}</div>
      <div style="display:flex;align-items:center;gap:3px;margin-top:6px"><span style="color:var(--amb);font-size:12px">★</span><span style="font-size:11px;color:var(--txt3)">${w.rating>0?w.rating:'New'}</span></div>
      <div style="font-size:14px;font-weight:800;color:var(--g);margin-top:8px">Rs ${w.daily_rate}<span style="font-size:10px;color:var(--txt3);font-weight:500">${w.rate_label}</span></div>
    </div>`).join('')
}
function renderHomeBookings(){
  const bookings=DB.getBookings(appState.user.id).filter(b=>b.status==='active');
  const el=document.getElementById('home-bookings');
  if(!bookings.length){el.innerHTML='<div style="background:#fff;border-radius:16px;border:1.5px dashed var(--border);padding:28px;text-align:center;color:var(--txt3)"><div style="font-size:36px;margin-bottom:10px">📅</div><p style="font-size:14px;font-weight:500">No active bookings yet</p><p style="font-size:12px;margin-top:4px">Find a worker and make your first booking</p><button class="btn btn-g btn-sm" style="margin-top:14px" onclick="appTab(\'search\')">Find Workers →</button></div>';return}
  const workers=DB.getWorkers();
  el.innerHTML=bookings.map(b=>{const w=workers.find(x=>x.id===b.worker_id)||{};return`<div class="bcard" style="cursor:pointer" onclick="appTab('bookings')">
    <div style="display:flex;align-items:center;gap:12px">
      <div style="width:48px;height:48px;border-radius:50%;background:${w.grad||'var(--gl)'};display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:800;color:#fff;flex-shrink:0">${w.initials||'?'}</div>
      <div style="flex:1"><div style="font-size:14px;font-weight:700">${w.name||'Unknown'}</div><div style="font-size:12px;color:var(--txt2)">${w.emoji||''} ${b.service} · ${b.schedule}</div><div style="font-size:11px;color:var(--txt3);margin-top:2px">📅 Next: ${b.next}</div></div>
      <span class="badge bg">Active</span>
    </div></div>`}).join('')
}

// ════════════════════════════════════════
// SEARCH
// ════════════════════════════════════════
const CATS=['all','maid','cook','electrician','plumber','security','clothes_wash','dishwasher','gardener','labourer','babysitter','carpenter','painter'];
const CAT_LABELS={all:'🔍 All',maid:'🧹 Maid',cook:'👨‍🍳 Cook',electrician:'⚡ Electrician',plumber:'🔧 Plumber',security:'🔒 Security',clothes_wash:'👔 Clothes',dishwasher:'🍽️ Dishes',gardener:'🌿 Gardener',labourer:'⛏️ Labourer',babysitter:'👶 Baby Sitter',carpenter:'🪚 Carpenter',painter:'🎨 Painter'};
function renderSearch(){
  document.getElementById('cat-filters').innerHTML=CATS.map(c=>`<span class="fchip ${appState.searchFilter===c?'on':''}" onclick="appState.searchFilter='${c}';renderSearch()">${CAT_LABELS[c]}</span>`).join('');
  const q=(document.getElementById('search-input')?.value||'').toLowerCase();
  const sort=document.getElementById('sort-select')?.value||'rating';
  let workers=DB.getWorkers().filter(w=>{
    const mc=appState.searchFilter==='all'||w.category===appState.searchFilter;
    const mq=!q||w.name.toLowerCase().includes(q)||w.role.toLowerCase().includes(q)||w.city.toLowerCase().includes(q);
    return mc&&mq;
  });
  if(sort==='rating')workers.sort((a,b)=>b.rating-a.rating);
  else if(sort==='price_low')workers.sort((a,b)=>a.daily_rate-b.daily_rate);
  else workers.sort((a,b)=>b.daily_rate-a.daily_rate);
  document.getElementById('search-count').textContent=`${workers.length} worker${workers.length!==1?'s':''} found near Islamabad`;
  document.getElementById('search-results').innerHTML=workers.map(w=>`
    <div class="rcard" onclick="loadWorkerDetail('${w.id}');appTab('detail')">
      <div style="display:flex;gap:12px;margin-bottom:12px">
        <div class="rav" style="background:${w.grad};color:#fff;box-shadow:0 4px 12px rgba(0,0,0,.15)">${w.initials}</div>
        <div style="flex:1">
          <div style="display:flex;align-items:center;gap:6px;flex-wrap:wrap;margin-bottom:3px">
            <span style="font-size:15px;font-weight:800">${w.name}</span>
            ${w.verified?'<span class="badge bg" style="font-size:9px">✓ Verified</span>':'<span class="badge ba" style="font-size:9px">⏳ Pending</span>'}
            ${w.online?'<span class="badge" style="background:#E8F5E9;color:#166534;font-size:9px">● Online</span>':''}
          </div>
          <p style="font-size:12px;color:var(--txt2)">${w.emoji} ${w.role} · ${w.exp} yrs experience</p>
          <div style="display:flex;align-items:center;gap:5px;margin-top:4px">
            <span style="color:var(--amb);font-size:12px">${w.rating>0?'★'.repeat(Math.round(w.rating)):'☆☆☆☆☆'}</span>
            <span style="font-size:11px;color:var(--txt3)">${w.rating>0?w.rating:'New'} (${w.reviews} reviews)</span>
          </div>
        </div>
        <div style="text-align:right;flex-shrink:0">
          <div class="rcard-rate">Rs ${w.daily_rate}<small>${w.rate_label}</small></div>
          <div style="font-size:11px;color:var(--txt3);margin-top:3px">📍 ${w.city}</div>
        </div>
      </div>
      <div class="skills-row">${w.skills.slice(0,3).map(s=>`<span class="badge bg">${s}</span>`).join('')}</div>
    </div>`).join('')||'<div style="grid-column:1/-1;padding:40px;text-align:center;color:var(--txt3)"><div style="font-size:48px;margin-bottom:12px">🔍</div><p style="font-size:15px;font-weight:500">No workers found</p><p style="font-size:13px;margin-top:6px">Try a different search or category</p></div>'
}

// ════════════════════════════════════════
// WORKER DETAIL
// ════════════════════════════════════════
function loadWorkerDetail(wid){
  const w=DB.getWorkers().find(x=>x.id===wid);if(!w)return;appState.currentWorker=w;
  document.getElementById('detail-hero').style.background=w.grad;
  document.getElementById('detail-hero').innerHTML=`
    <div class="dh-av">${w.initials}</div>
    <div class="dh-info" style="flex:1">
      <div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-bottom:6px">
        <h2>${w.name}</h2>
        ${w.verified?'<span style="background:rgba(255,255,255,.2);color:#fff;font-size:10px;font-weight:700;padding:3px 10px;border-radius:12px;border:1px solid rgba(255,255,255,.35)">✓ CNIC Verified</span>':'<span style="background:rgba(255,200,0,.25);color:#ffe066;font-size:10px;font-weight:700;padding:3px 10px;border-radius:12px">⏳ Pending Verification</span>'}
      </div>
      <p>${w.emoji} ${w.role} · ${w.exp} years experience</p>
      <div style="display:flex;align-items:center;gap:8px;margin-top:6px">
        <span style="color:#FAC775;font-size:14px">${w.rating>0?'★'.repeat(Math.round(w.rating)):'☆☆☆☆☆'}</span>
        <span style="color:rgba(255,255,255,.8);font-size:13px">${w.rating>0?w.rating:'No ratings'} · ${w.reviews} reviews</span>
        ${w.online?'<div style="width:9px;height:9px;background:#22C55E;border-radius:50%;border:2px solid #fff"></div><span style="font-size:11px;color:#A8EDCB">Online</span>':''}
      </div>
      <div class="dh-stats">
        <div class="dhs"><div class="n">Rs ${w.daily_rate}</div><div class="l">Per Day</div></div>
        <div class="dhs"><div class="n">${w.jobs}</div><div class="l">Jobs Done</div></div>
        <div class="dhs"><div class="n">${w.online?'Available':'Offline'}</div><div class="l">Status</div></div>
      </div>
    </div>`;
  document.getElementById('dp-about').innerHTML=`
    <div class="detail-card">
      <div class="notice notice-g"><span>🛡️</span><div><strong>Fully Verified</strong> — CNIC, selfie match, police clearance & reference check completed.</div></div>
      <p class="sec-title">About ${w.name}</p>
      <p style="font-size:14px;color:var(--txt2);line-height:1.75">${w.bio}</p>
      <p class="sec-title" style="margin-top:18px">Skills & Expertise</p>
      <div class="skills-row" style="gap:7px">${w.skills.map(s=>`<span class="badge bg" style="padding:5px 12px;font-size:11px">${s}</span>`).join('')||'<span class="badge bw">No skills listed yet</span>'}</div>
      <p class="sec-title" style="margin-top:18px">Availability</p>
      <div style="display:flex;gap:6px;flex-wrap:wrap">${['Mon','Tue','Wed','Thu','Fri','Sat','Sun'].map(d=>`<span class="badge ${w.days.includes(d)?'bg':'bw'}" style="padding:5px 12px">${d}${w.days.includes(d)?' ✓':''}</span>`).join('')}</div>
      <p class="sec-title" style="margin-top:18px">Location & Travel</p>
      <p style="font-size:13px;color:var(--txt2)">📍 ${w.city} · Willing to travel up to 10 km</p>
    </div>`;
  const revs=w.reviews>0?[
    {n:'Ahmed R.',c:'#E6F1FB',fc:'#0C447C',s:5,t:'Very professional and thorough. My house was spotless!',d:'Dec 2024'},
    {n:'Sara K.',c:'#FBEAF0',fc:'#72243E',s:5,t:'Punctual, trustworthy and hardworking. 6 months!',d:'Nov 2024'},
    {n:'Omar M.',c:'#FAEEDA',fc:'#633806',s:4,t:'Good work. Sometimes a bit late but always calls ahead.',d:'Oct 2024'},
  ]:[];
  document.getElementById('dp-reviews').innerHTML=w.reviews>0?`
    <div class="detail-card">
      <div style="display:flex;align-items:center;gap:24px;margin-bottom:18px">
        <div style="text-align:center"><div style="font-size:44px;font-weight:800">${w.rating}</div><div style="color:var(--amb);font-size:18px">${'★'.repeat(Math.round(w.rating))}</div><div style="font-size:11px;color:var(--txt3);margin-top:3px">${w.reviews} reviews</div></div>
        <div style="flex:1">${[5,4,3,2,1].map(s=>`<div style="display:flex;align-items:center;gap:8px;margin-bottom:5px"><span style="font-size:11px;color:var(--txt3);width:22px">${s}★</span><div style="flex:1;height:6px;background:var(--border);border-radius:3px"><div style="width:${s===5?92:s===4?6:2}%;height:100%;background:var(--g);border-radius:3px"></div></div></div>`).join('')}</div>
      </div>
      <div style="height:1px;background:var(--border);margin-bottom:14px"></div>
      ${revs.map(r=>`<div style="padding:14px 0;border-bottom:1px solid var(--border)">
        <div style="display:flex;justify-content:space-between;margin-bottom:8px">
          <div style="display:flex;align-items:center;gap:8px"><div style="width:34px;height:34px;border-radius:50%;background:${r.c};color:${r.fc};display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:800">${r.n.split(' ').map(w=>w[0]).join('')}</div><span style="font-size:13px;font-weight:700">${r.n}</span></div>
          <span style="color:var(--amb);font-size:13px">${'★'.repeat(r.s)}</span>
        </div>
        <p style="font-size:13px;color:var(--txt2);line-height:1.6">"${r.t}"</p>
        <p style="font-size:11px;color:var(--txt3);margin-top:5px">${r.d}</p>
      </div>`).join('')}
    </div>`:`<div class="detail-card"><p style="color:var(--txt3);font-size:14px;text-align:center;padding:20px">No reviews yet. Be the first to hire and rate!</p></div>`;
  document.getElementById('book-box-container').innerHTML=`
    <div class="book-box">
      <h3>Book ${w.name}</h3>
      <div style="background:${w.grad};border-radius:12px;padding:14px;margin-bottom:18px;display:flex;align-items:center;gap:12px">
        <div style="width:44px;height:44px;border-radius:50%;background:rgba(255,255,255,.2);display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:800;color:#fff">${w.initials}</div>
        <div><div style="font-size:15px;font-weight:800;color:#fff">${w.name}</div><div style="font-size:12px;color:rgba(255,255,255,.8)">${w.emoji} ${w.role} · Rs ${w.daily_rate}${w.rate_label}</div></div>
      </div>
      <div class="form-group"><label class="flabel">Service Package</label>
        <select class="finput" id="bb-package" onchange="updateBookPrice(${w.daily_rate})">
          <option value="${w.daily_rate}">Daily – Rs ${w.daily_rate}${w.rate_label}</option>
          <option value="${Math.round(w.daily_rate*5*0.7)}">Weekly – Rs ${Math.round(w.daily_rate*5*0.7)}/week</option>
          <option value="${Math.round(w.daily_rate*22*0.58)}">Monthly – Rs ${Math.round(w.daily_rate*22*0.58)}/month</option>
        </select>
      </div>
      <div class="form-group"><label class="flabel">Start Date</label><input class="finput" type="date" id="bb-date" value="${new Date().toISOString().split('T')[0]}"></div>
      <div class="form-group"><label class="flabel">Your Address</label><input class="finput" id="bb-addr" placeholder="House #, Street, Area, City"></div>
      <div class="notice notice-g"><span>💳</span><div>Secure escrow payment. Released only after job completion.</div></div>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;padding:14px;background:var(--gll);border-radius:12px;border:1px solid #9FE1CB">
        <span style="font-weight:700;font-size:14px">Total:</span>
        <span id="bb-total" style="font-size:20px;font-weight:800;color:var(--g)">Rs ${w.daily_rate}</span>
      </div>
      <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px" onclick="openBookModal('${w.id}')">Book Now →</button>
      <button class="btn btn-o" style="width:100%;margin-top:10px;padding:11px" onclick="openChat('${w.id}')">💬 Message Worker</button>
    </div>`;
  detailTab('about')
}
function updateBookPrice(base){const sel=document.getElementById('bb-package');if(sel)document.getElementById('bb-total').textContent='Rs '+parseInt(sel.value).toLocaleString()}
function detailTab(t){
  document.getElementById('dp-about').style.display=t==='about'?'block':'none';
  document.getElementById('dp-reviews').style.display=t==='reviews'?'block':'none';
  document.getElementById('dt-about').classList.toggle('on',t==='about');
  document.getElementById('dt-reviews').classList.toggle('on',t==='reviews')
}

// ════════════════════════════════════════
// BOOKING
// ════════════════════════════════════════
function openBookModal(wid){
  const w=DB.getWorkers().find(x=>x.id===wid);if(!w)return;appState.bookingWorker=w;
  document.getElementById('book-modal-worker-info').innerHTML=`<div style="display:flex;align-items:center;gap:12px;background:${w.grad};border-radius:14px;padding:14px"><div style="width:46px;height:46px;border-radius:50%;background:rgba(255,255,255,.2);display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:800;color:#fff">${w.initials}</div><div><div style="font-size:15px;font-weight:800;color:#fff">${w.name}</div><div style="font-size:12px;color:rgba(255,255,255,.8)">${w.emoji} ${w.role} · Rs ${w.daily_rate}${w.rate_label}</div></div></div>`;
  document.getElementById('bm-total').textContent='Rs '+w.daily_rate;
  document.getElementById('bm-date').value=new Date().toISOString().split('T')[0];
  showModal('book-modal')
}
function confirmBooking(){
  const w=appState.bookingWorker;if(!w)return;
  const date=document.getElementById('bm-date').value;
  const addr=document.getElementById('bm-address').value.trim();
  const pkg=document.getElementById('bm-package').value;
  if(!date||!addr){toast('Please fill date and address','error');return}
  const pkgNames={daily:'Daily',weekly:'Weekly',monthly:'Monthly'};
  const amts={daily:w.daily_rate,weekly:Math.round(w.daily_rate*5*0.7),monthly:Math.round(w.daily_rate*22*0.58)};
  DB.addBooking({id:'b'+Date.now(),employer_id:appState.user.id,worker_id:w.id,service:w.role+' – '+w.name,schedule:pkgNames[pkg],package:pkg,amount:amts[pkg],status:'pending',date:new Date().toLocaleDateString('en-PK',{month:'short',day:'numeric',year:'numeric'}),next:date,address:addr});
  if((appState.user.wallet_balance||0)>=amts[pkg])DB.updateUserBalance(appState.user.id,-amts[pkg]);
  const ns=DB.get('notifications')||[];ns.unshift({id:'n'+Date.now(),icon:'📅',title:'Booking Submitted',body:`Your booking for ${w.name} has been submitted and is pending confirmation.`,time:'Just now',read:false,color:'var(--blu)'});DB.set('notifications',ns);
  closeModal('book-modal');toast('Booking confirmed! Worker will respond within 24 hours. ✅');
  document.getElementById('wallet-bal').textContent='Rs '+(appState.user.wallet_balance||0).toLocaleString();
  appTab('bookings')
}

// ════════════════════════════════════════
// BOOKINGS PAGE
// ════════════════════════════════════════
function filterBookings(f){
  appState.bookingFilter=f;
  ['all','active','completed','pending'].forEach(x=>{const el=document.getElementById('bf-'+x);if(el)el.classList.toggle('on',x===f)});
  renderBookings()
}
function renderBookings(){
  const all=DB.getBookings(appState.user.id);
  const filtered=appState.bookingFilter==='all'?all:all.filter(b=>b.status===appState.bookingFilter);
  const workers=DB.getWorkers();
  const el=document.getElementById('bookings-list');
  if(!filtered.length){el.innerHTML='<div style="text-align:center;padding:50px;color:var(--txt3)"><div style="font-size:52px;margin-bottom:14px">📅</div><p style="font-size:16px;font-weight:600">No bookings found</p><p style="font-size:13px;margin-top:6px">Try a different filter or make a new booking</p><button class="btn btn-g btn-sm" style="margin-top:16px" onclick="appTab(\'search\')">Find Workers →</button></div>';return}
  el.innerHTML=filtered.map(b=>{const w=workers.find(x=>x.id===b.worker_id)||{};const sClass={active:'',completed:'done',pending:'pending',cancelled:'cancelled'}[b.status]||'';const bClass={active:'bg',completed:'ba',pending:'bb',cancelled:'br'}[b.status]||'bw';
    return`<div class="bcard ${sClass}">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:12px">
        <div class="bav" style="background:${w.grad||'var(--gl)'};color:#fff;box-shadow:0 4px 12px rgba(0,0,0,.15)">${w.initials||'?'}</div>
        <div style="flex:1">
          <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:6px">
            <div><div style="font-size:15px;font-weight:800">${w.name||'Unknown'}</div><div style="font-size:12px;color:var(--txt2);margin-top:2px">${b.service} · ${b.schedule}</div>${b.next?`<div style="font-size:11px;color:var(--txt3);margin-top:2px">📅 ${b.next}</div>`:''}</div>
            <span class="badge ${bClass}" style="padding:4px 12px">${b.status.charAt(0).toUpperCase()+b.status.slice(1)}</span>
          </div>
        </div>
      </div>
      <div class="bcard-actions">
        <span style="font-size:14px;font-weight:800;color:var(--g)">Rs ${b.amount.toLocaleString()}</span>
        <div style="margin-left:auto;display:flex;gap:8px;flex-wrap:wrap">
          ${b.status==='active'?`<button class="btn btn-o btn-sm" onclick="openChat('${b.worker_id}')">💬 Chat</button><button class="btn btn-g btn-sm" onclick="completeBooking('${b.id}')">✓ Mark Done</button>`:''}
          ${b.status==='completed'?`<button class="btn btn-o btn-sm">⭐ Rate Worker</button><button class="btn btn-g btn-sm" onclick="loadWorkerDetail('${b.worker_id}');appTab('detail')">🔁 Rehire</button>`:''}
          ${b.status==='pending'?`<button class="btn btn-sm" style="background:var(--redl);color:var(--red);border:1px solid var(--red)" onclick="cancelBooking('${b.id}')">✕ Cancel</button><button class="btn btn-o btn-sm" onclick="openChat('${b.worker_id}')">💬 Message</button>`:''}
        </div>
      </div>
    </div>`}).join('')
}
function completeBooking(id){DB.updateBookingStatus(id,'completed');toast('Booking marked as completed! ✅');renderBookings();renderHomeBookings()}
function cancelBooking(id){DB.updateBookingStatus(id,'cancelled');toast('Booking cancelled.');renderBookings()}

// ════════════════════════════════════════
// CHAT
// ════════════════════════════════════════
function renderChatList(){
  const workers=DB.getWorkers().filter(w=>w.verified).slice(0,4);
  document.getElementById('chat-list').innerHTML=`<div style="padding:14px 18px;border-bottom:1px solid var(--border);background:#fafafa"><p style="font-size:11px;font-weight:700;color:var(--txt3);text-transform:uppercase;letter-spacing:.6px">Conversations</p></div>`+workers.map(w=>`
    <div class="chat-item ${appState.activeChatWorker===w.id?'active':''}" onclick="openChat('${w.id}')">
      <div style="display:flex;align-items:center;gap:10px">
        <div class="ci-av" style="background:${w.grad};color:#fff;box-shadow:0 2px 8px rgba(0,0,0,.12)">${w.initials}</div>
        <div class="ci-info" style="flex:1;min-width:0">
          <div style="display:flex;justify-content:space-between;align-items:center"><h4>${w.name}</h4>${w.online?'<div style="width:7px;height:7px;background:#22C55E;border-radius:50%"></div>':''}</div>
          <p>${w.emoji} ${w.role}</p>
        </div>
      </div>
    </div>`).join('')
}
function openChat(wid){
  appState.activeChatWorker=wid;
  const w=DB.getWorkers().find(x=>x.id===wid);if(!w)return;
  appTab('messages');renderChatList();
  const msgs=(DB.get('messages')||{})[wid]||[];
  document.getElementById('chat-main').innerHTML=`
    <div class="chat-header">
      <div style="width:40px;height:40px;border-radius:50%;background:${w.grad};display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:800;color:#fff;box-shadow:0 2px 8px rgba(0,0,0,.15)">${w.initials}</div>
      <div style="margin-left:10px;flex:1"><div style="font-size:14px;font-weight:800">${w.name}</div><div style="font-size:11px;color:${w.online?'var(--g)':'var(--txt3)'}">${w.online?'● Online now':'Offline'}</div></div>
      <button style="background:var(--gl);border:1px solid #9FE1CB;border-radius:9px;padding:7px 14px;font-size:12px;font-weight:600;color:var(--gd);cursor:pointer">📍 View Profile</button>
    </div>
    <div class="chat-messages" id="chat-msgs">
      <div style="text-align:center;margin-bottom:14px"><span class="badge bw">Today</span></div>
      ${msgs.map(m=>`<div class="msg ${m.from==='user'?'msg-out':'msg-in'}">${m.text}<div class="msg-time">${m.time}</div></div>`).join('')}
    </div>
    <div class="chat-input">
      <input id="chat-inp" placeholder="Type a message..." onkeydown="if(event.key==='Enter')sendMsg('${wid}')">
      <button class="send-btn" onclick="sendMsg('${wid}')"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2.5"><line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/></svg></button>
    </div>`;
  const el=document.getElementById('chat-msgs');if(el)el.scrollTop=el.scrollHeight
}
function sendMsg(wid){
  const inp=document.getElementById('chat-inp');const text=inp?.value.trim();if(!text)return;
  const msgs=DB.get('messages')||{};if(!msgs[wid])msgs[wid]=[];
  const now=new Date();const time=now.getHours()+':'+String(now.getMinutes()).padStart(2,'0');
  msgs[wid].push({from:'user',text,time});DB.set('messages',msgs);inp.value='';openChat(wid);
  setTimeout(()=>{const replies=['Shukriya! Ji zaroor.','Ji sir, theek hai.','Inshallah, hum kar denge.','Theek hai sir, aa jaayenge.','Ji bilkul, koi masla nahi!'];const r=replies[Math.floor(Math.random()*replies.length)];const m2=DB.get('messages')||{};if(!m2[wid])m2[wid]=[];m2[wid].push({from:'worker',text:r,time:new Date().getHours()+':'+String(new Date().getMinutes()).padStart(2,'0')});DB.set('messages',m2);if(appState.activeChatWorker===wid)openChat(wid)},1600)
}

// ════════════════════════════════════════
// NOTIFICATIONS
// ════════════════════════════════════════
function renderNotifs(){
  const ns=DB.get('notifications')||[];
  document.getElementById('notif-list').innerHTML=ns.map(n=>`
    <div style="background:#fff;border-radius:16px;border:1.5px solid ${!n.read?n.color||'var(--g)':'var(--border)'};padding:16px;margin-bottom:10px;box-shadow:0 2px 10px rgba(0,0,0,.05)">
      <div style="display:flex;gap:12px">
        <span style="font-size:26px">${n.icon}</span>
        <div><div style="font-size:14px;font-weight:700">${n.title}</div><div style="font-size:13px;color:var(--txt2);margin-top:3px;line-height:1.5">${n.body}</div><div style="font-size:11px;color:var(--txt3);margin-top:6px">${n.time}</div></div>
        ${!n.read?`<div style="width:8px;height:8px;background:${n.color||'var(--g)'};border-radius:50%;flex-shrink:0;margin-left:auto;margin-top:4px"></div>`:''}
      </div>
    </div>`).join('')||'<p style="color:var(--txt3);font-size:14px;text-align:center;padding:40px">No notifications yet</p>';
  checkNotifDot()
}
function checkNotifDot(){const ns=DB.get('notifications')||[];const dot=document.getElementById('notif-dot');if(dot)dot.style.display=ns.filter(n=>!n.read).length>0?'block':'none'}
function markNotifsRead(){const ns=(DB.get('notifications')||[]).map(n=>({...n,read:true}));DB.set('notifications',ns);checkNotifDot()}

// ════════════════════════════════════════
// PROFILE
// ════════════════════════════════════════
function renderProfileStats(){
  const bs=DB.getBookings(appState.user.id);
  document.getElementById('profile-stats').innerHTML=`
    <div style="background:#fff;border-radius:14px;border:1.5px solid var(--border);padding:14px;text-align:center;box-shadow:0 2px 8px rgba(0,0,0,.04)"><div style="font-size:22px;font-weight:800;color:var(--g)">${bs.length}</div><div style="font-size:10px;color:var(--txt2);margin-top:3px;font-weight:600;text-transform:uppercase;letter-spacing:.3px">Bookings</div></div>
    <div style="background:#fff;border-radius:14px;border:1.5px solid var(--border);padding:14px;text-align:center;box-shadow:0 2px 8px rgba(0,0,0,.04)"><div style="font-size:22px;font-weight:800;color:var(--blu)">${[...new Set(bs.map(b=>b.worker_id))].length}</div><div style="font-size:10px;color:var(--txt2);margin-top:3px;font-weight:600;text-transform:uppercase;letter-spacing:.3px">Workers</div></div>
    <div style="background:#fff;border-radius:14px;border:1.5px solid var(--border);padding:14px;text-align:center;box-shadow:0 2px 8px rgba(0,0,0,.04)"><div style="font-size:22px;font-weight:800;color:var(--amb)">${appState.user.rating||5.0}★</div><div style="font-size:10px;color:var(--txt2);margin-top:3px;font-weight:600;text-transform:uppercase;letter-spacing:.3px">Rating</div></div>`
}
function doTopup(){
  const amt=parseInt(document.getElementById('topup-amount').value);const method=document.getElementById('topup-method').value;
  if(!amt||amt<100){toast('Minimum top-up is Rs 100','error');return}
  DB.updateUserBalance(appState.user.id,amt);DB.addTransaction({id:'t'+Date.now(),type:'topup',desc:'Wallet Top-up via '+method,amount:amt,date:new Date().toLocaleDateString()});
  document.getElementById('wallet-bal').textContent='Rs '+(appState.user.wallet_balance||0).toLocaleString();
  closeModal('topup-modal');toast(`Rs ${amt.toLocaleString()} added to wallet! 💰`)
}

// ════════════════════════════════════════
// ADMIN
// ════════════════════════════════════════
function renderAdmin(){adminTab('dashboard');const p=(DB.get('pending_workers')||[]).length+DB.getWorkers().filter(w=>!w.verified).length;const pb=document.getElementById('pending-badge');if(pb)pb.textContent=p||''}
function adminTab(name){
  document.querySelectorAll('.admin-content').forEach(c=>c.classList.remove('on'));
  document.querySelectorAll('.as-item').forEach(i=>i.classList.remove('on'));
  const el=document.getElementById('ac-'+name);if(el)el.classList.add('on');
  const titles={dashboard:'Dashboard',analytics:'Analytics',employers:'Employers',workers:'Workers',verify:'Verification Queue','bookings-admin':'Bookings','payments-admin':'Payments',disputes:'Disputes',settings:'Settings'};
  document.getElementById('admin-page-title').textContent=titles[name]||name;
  document.querySelectorAll('.as-item').forEach(i=>{if(i.textContent.trim().startsWith((titles[name]||'').substring(0,5)))i.classList.add('on')});
  if(name==='dashboard')renderAdminDashboard();
  else if(name==='workers')renderAdminWorkers();
  else if(name==='employers')renderAdminEmployers();
  else if(name==='verify')renderAdminVerify();
  else if(name==='bookings-admin')renderAdminBookings();
  else if(name==='payments-admin')renderAdminPayments();
  else if(name==='analytics')renderAdminAnalytics();
  else if(name==='disputes')renderAdminDisputes();
  else if(name==='settings')renderAdminSettings()
}
function renderAdminDashboard(){
  const workers=DB.getWorkers(),users=DB.getUsers(),bookings=DB.getBookings();
  const emp=users.filter(u=>u.role==='employer').length,vw=workers.filter(w=>w.verified).length,ab=bookings.filter(b=>b.status==='active').length,rev=bookings.filter(b=>b.status==='completed').reduce((s,b)=>s+Math.round(b.amount*.1),0);
  document.getElementById('ac-dashboard').innerHTML=`
    <div class="ag">
      <div class="astat g"><div class="l">Total Employers</div><div class="n" style="color:var(--g)">${emp}</div><div class="ch">↑ +4 this week</div><div class="em">👥</div></div>
      <div class="astat a"><div class="l">Verified Workers</div><div class="n" style="color:var(--amb)">${vw}</div><div class="ch">↑ +2 this week</div><div class="em">👷</div></div>
      <div class="astat b"><div class="l">Active Bookings</div><div class="n" style="color:var(--blu)">${ab}</div><div class="ch">↑ +1 today</div><div class="em">📅</div></div>
      <div class="astat r"><div class="l">Platform Revenue</div><div class="n" style="color:var(--red)">Rs ${rev.toLocaleString()}</div><div class="ch">10% commission</div><div class="em">💰</div></div>
    </div>
    <div style="display:grid;grid-template-columns:1.5fr 1fr;gap:16px;margin-bottom:18px">
      <div class="atable"><div class="atable-head"><h3>Revenue Chart (6 months)</h3><span class="badge bg">2025</span></div><div style="padding:18px"><div style="display:flex;align-items:flex-end;gap:8px;height:130px;padding-bottom:20px;position:relative">${[['Aug',60,'var(--teal)'],['Sep',75,'var(--blu)'],['Oct',55,'var(--pur)'],['Nov',90,'var(--ora)'],['Dec',70,'var(--amb)'],['Jan',100,'var(--g)']].map(([l,h,c])=>`<div style="flex:1;position:relative"><div style="background:${c};border-radius:6px 6px 0 0;height:${h}%;opacity:.85;transition:opacity .2s;cursor:pointer" title="${l}" onmouseover="this.style.opacity=1" onmouseout="this.style.opacity=.85"></div><div style="position:absolute;bottom:-20px;left:0;right:0;text-align:center;font-size:10px;color:var(--txt3)">${l}</div></div>`).join('')}</div></div></div>
      <div class="atable"><div class="atable-head"><h3>Platform Health</h3></div><div style="padding:16px">${[['Pending Verifications','ba',workers.filter(w=>!w.verified).length+' workers'],['Open Disputes','br','2 cases'],['Avg Worker Rating','bg','4.8 ★'],['Completion Rate','bg','94%'],['Escrow Balance','bg','Rs 1,28,500']].map(([l,c,v])=>`<div style="display:flex;justify-content:space-between;align-items:center;padding:9px 0;border-bottom:1px solid var(--border)"><span style="font-size:12px;color:var(--txt2)">${l}</span><span class="badge ${c}">${v}</span></div>`).join('')}</div></div>
    </div>
    <div class="atable"><div class="atable-head"><h3>Recent Bookings</h3><button class="btn btn-o btn-sm" onclick="adminTab('bookings-admin')">View All</button></div>
      <table><thead><tr><th>ID</th><th>Employer</th><th>Worker</th><th>Service</th><th>Amount</th><th>Status</th><th>Date</th></tr></thead>
      <tbody>${bookings.slice(0,6).map(b=>{const w=workers.find(x=>x.id===b.worker_id)||{};const u=users.find(x=>x.id===b.employer_id)||{};const bc={active:'bg',completed:'ba',pending:'bb',cancelled:'br'}[b.status]||'bw';return`<tr><td><code style="font-size:10px;color:var(--txt3);background:#f5f5f5;padding:2px 6px;border-radius:4px">#${b.id.slice(-5).toUpperCase()}</code></td><td>${u.name||'—'}</td><td>${w.initials?`<span style="background:${w.grad};color:#fff;padding:2px 8px;border-radius:6px;font-size:10px;font-weight:700">${w.initials}</span> `:''}${w.name||'—'}</td><td>${b.service}</td><td style="font-weight:700">Rs ${b.amount.toLocaleString()}</td><td><span class="badge ${bc}">${b.status}</span></td><td>${b.date}</td></tr>`}).join('')}</tbody></table>
    </div>`
}
function renderAdminWorkers(){
  const workers=DB.getWorkers();
  document.getElementById('ac-workers').innerHTML=`
    <div class="filter-row2"><input class="finput2" placeholder="🔍 Search worker..." oninput="filterAW(this.value)"><select class="finput2"><option>All Categories</option><option>maid</option><option>cook</option><option>electrician</option><option>plumber</option></select><select class="finput2"><option>All Status</option><option>Verified</option><option>Pending</option></select><button class="btn btn-g btn-sm" style="margin-left:auto">Export CSV</button></div>
    <div class="atable"><div class="atable-head"><h3>All Workers <span style="color:var(--txt3);font-weight:400;font-size:13px">(${workers.length} total)</span></h3></div>
      <table id="wtable"><thead><tr><th>Worker</th><th>Category</th><th>City</th><th>Rate</th><th>Rating</th><th>Jobs</th><th>Status</th><th>Actions</th></tr></thead>
      <tbody>${workers.map(w=>`<tr><td><div style="display:flex;align-items:center;gap:8px"><div style="width:30px;height:30px;border-radius:50%;background:${w.grad};color:#fff;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:800;flex-shrink:0">${w.initials}</div><div><div style="font-weight:700;font-size:12px">${w.name}</div><div style="font-size:10px;color:var(--txt3)">${w.emoji} ${w.role}</div></div></div></td><td>${w.category}</td><td style="font-size:11px">${w.city}</td><td>Rs ${w.daily_rate}</td><td>${w.rating>0?`⭐ ${w.rating} (${w.reviews})`:'-'}</td><td>${w.jobs}</td><td><span class="badge ${w.verified?'bg':'ba'}">${w.verified?'Verified':'Pending'}</span></td><td><div style="display:flex;gap:4px">${!w.verified?`<button class="btn btn-g btn-xs" onclick="verifyWorker('${w.id}')">✓ Verify</button>`:''}<button class="btn btn-xs" style="background:var(--redl);color:var(--red);border:none;font-family:inherit;cursor:pointer" onclick="toast('Worker suspended')">Suspend</button></div></td></tr>`).join('')}</tbody></table>
    </div>`
}
function filterAW(q){document.querySelectorAll('#wtable tbody tr').forEach(r=>r.style.display=r.textContent.toLowerCase().includes(q.toLowerCase())?'':'none')}
function verifyWorker(id){const ws=DB.getWorkers();const i=ws.findIndex(w=>w.id===id);if(i>-1){ws[i].verified=true;DB.set('workers',ws)}toast('Worker verified! ✅');renderAdminWorkers();renderAdmin()}
function renderAdminEmployers(){
  const users=DB.getUsers().filter(u=>u.role==='employer');
  document.getElementById('ac-employers').innerHTML=`<div class="atable"><div class="atable-head"><h3>All Employers <span style="color:var(--txt3);font-weight:400;font-size:13px">(${users.length} total)</span></h3></div>
    <table><thead><tr><th>Name</th><th>Phone</th><th>City</th><th>Bookings</th><th>Wallet</th><th>Rating</th><th>Status</th></tr></thead>
    <tbody>${users.map(u=>`<tr><td><div style="font-weight:700">${u.name}</div><div style="font-size:10px;color:var(--txt3)">${u.id}</div></td><td>${u.phone}</td><td>${u.city||'—'}</td><td>${DB.getBookings(u.id).length}</td><td>Rs ${(u.wallet_balance||0).toLocaleString()}</td><td>⭐ ${u.rating||5.0}</td><td><span class="badge bg">Active</span></td></tr>`).join('')}</tbody></table></div>`
}
function renderAdminVerify(){
  const pending=[...DB.getWorkers().filter(w=>!w.verified),...(DB.get('pending_workers')||[]).filter(e=>!DB.getWorkers().find(p=>p.id===e.id))];
  document.getElementById('ac-verify').innerHTML=`
    <div style="display:flex;align-items:center;gap:12px;margin-bottom:20px;flex-wrap:wrap"><div><h3 style="font-size:16px;font-weight:800">Worker Verification Queue</h3><p style="font-size:13px;color:var(--txt2);margin-top:3px">Review CNIC, selfie and police clearance documents</p></div><span class="badge br" style="margin-left:auto;padding:6px 16px;font-size:12px">${pending.length} Pending</span></div>
    ${pending.length===0?'<div style="text-align:center;padding:60px;color:var(--txt3)"><div style="font-size:52px;margin-bottom:12px">🎉</div><p style="font-size:16px;font-weight:600">All clear!</p><p style="font-size:13px;margin-top:6px">No pending verifications right now</p></div>':pending.map(w=>`
    <div style="background:#fff;border-radius:18px;border:1.5px solid var(--border);padding:20px;margin-bottom:14px;box-shadow:0 2px 10px rgba(0,0,0,.05)">
      <div style="display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:12px;margin-bottom:16px">
        <div style="display:flex;align-items:center;gap:14px">
          <div style="width:52px;height:52px;background:${w.grad||'linear-gradient(135deg,var(--g),var(--gd))'};border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:800;color:#fff;font-size:18px;box-shadow:0 4px 12px rgba(0,0,0,.15)">${w.initials}</div>
          <div><div style="font-size:16px;font-weight:800">${w.name}</div><div style="font-size:12px;color:var(--txt2);margin-top:2px">${w.emoji} ${w.role} · ${w.city}</div><div style="font-size:11px;color:var(--txt3);margin-top:2px">Applied: ${w.applied||'Recently'}</div></div>
        </div>
        <div style="display:flex;gap:10px"><button class="btn btn-g" onclick="verifyWorker('${w.id}');renderAdminVerify()">✓ Approve</button><button class="btn" style="background:var(--redl);color:var(--red);border:1.5px solid var(--red)" onclick="toast('Worker rejected');this.closest('[style*=border-radius]').remove()">✗ Reject</button></div>
      </div>
      <div style="display:flex;gap:10px;flex-wrap:wrap">${['🪪 CNIC Front','🪪 CNIC Back','🤳 Selfie Photo','📄 Police Cert'].map(d=>`<div style="text-align:center"><div style="width:88px;height:66px;background:var(--bg);border-radius:10px;border:1.5px solid var(--border);display:flex;align-items:center;justify-content:center;font-size:24px;cursor:pointer;transition:all .15s" onmouseover="this.style.borderColor='var(--g)'" onmouseout="this.style.borderColor='var(--border)'">${d.split(' ')[0]}</div><div style="font-size:10px;color:var(--txt3);margin-top:5px">${d.substring(3)}</div></div>`).join('')}</div>
    </div>`).join('')}`
}
function renderAdminBookings(){
  const bs=DB.getBookings(),ws=DB.getWorkers(),us=DB.getUsers();
  const counts={active:0,completed:0,pending:0,cancelled:0};bs.forEach(b=>{if(counts[b.status]!==undefined)counts[b.status]++});
  document.getElementById('ac-bookings-admin').innerHTML=`
    <div style="display:grid;grid-template-columns:repeat(5,1fr);gap:12px;margin-bottom:18px">${[['Total',bs.length,''],['Active',counts.active,'var(--g)'],['Pending',counts.pending,'var(--blu)'],['Done',counts.completed,'var(--amb)'],['Cancelled',counts.cancelled,'var(--red)']].map(([l,n,c])=>`<div style="background:#fff;border-radius:14px;border:1.5px solid var(--border);padding:16px;text-align:center;box-shadow:0 2px 8px rgba(0,0,0,.04)"><div style="font-size:24px;font-weight:800;${c?'color:'+c:''}">${n}</div><div style="font-size:11px;color:var(--txt2);margin-top:3px;font-weight:600">${l}</div></div>`).join('')}</div>
    <div class="atable"><div class="atable-head"><h3>All Bookings</h3><button class="btn btn-g btn-sm">Export</button></div>
      <table><thead><tr><th>ID</th><th>Employer</th><th>Worker</th><th>Service</th><th>Amount</th><th>Fee</th><th>Status</th><th>Date</th></tr></thead>
      <tbody>${bs.map(b=>{const w=ws.find(x=>x.id===b.worker_id)||{};const u=us.find(x=>x.id===b.employer_id)||{};const bc={active:'bg',completed:'ba',pending:'bb',cancelled:'br'}[b.status]||'bw';return`<tr><td><code style="font-size:10px;color:var(--txt3);background:#f5f5f5;padding:2px 6px;border-radius:4px">#${b.id.slice(-5).toUpperCase()}</code></td><td>${u.name||'—'}</td><td>${w.name||'—'}</td><td>${b.service}</td><td style="font-weight:700">Rs ${b.amount.toLocaleString()}</td><td style="color:var(--g);font-weight:700">Rs ${Math.round(b.amount*.1).toLocaleString()}</td><td><span class="badge ${bc}">${b.status}</span></td><td>${b.date}</td></tr>`}).join('')}</tbody></table></div>`
}
function renderAdminPayments(){
  const ts=DB.get('transactions')||SEED.transactions;const rev=ts.filter(t=>t.type==='payment').reduce((s,t)=>s+Math.abs(t.amount)*.1,0);
  document.getElementById('ac-payments-admin').innerHTML=`
    <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-bottom:20px">
      <div style="background:linear-gradient(135deg,var(--gd),var(--g));border-radius:18px;padding:22px;color:#fff;box-shadow:0 8px 28px rgba(29,158,117,.25)"><div style="font-size:10px;opacity:.7;font-weight:700;letter-spacing:.8px;text-transform:uppercase">PLATFORM REVENUE</div><div style="font-size:30px;font-weight:800;margin:6px 0">Rs ${Math.round(rev).toLocaleString()}</div><div style="font-size:12px;opacity:.7">10% of all bookings</div></div>
      <div style="background:linear-gradient(135deg,var(--blu),var(--pur));border-radius:18px;padding:22px;color:#fff;box-shadow:0 8px 28px rgba(55,138,221,.25)"><div style="font-size:10px;opacity:.7;font-weight:700;letter-spacing:.8px;text-transform:uppercase">ESCROW HELD</div><div style="font-size:30px;font-weight:800;margin:6px 0">Rs 1,28,500</div><div style="font-size:12px;opacity:.7">Pending job completion</div></div>
      <div style="background:linear-gradient(135deg,var(--ora),var(--amb));border-radius:18px;padding:22px;color:#fff;box-shadow:0 8px 28px rgba(249,115,22,.25)"><div style="font-size:10px;opacity:.7;font-weight:700;letter-spacing:.8px;text-transform:uppercase">WORKER PAYOUTS</div><div style="font-size:30px;font-weight:800;margin:6px 0">Rs ${(Math.round(rev*9)).toLocaleString()}</div><div style="font-size:12px;opacity:.7">Paid out to workers</div></div>
    </div>
    <div class="atable"><div class="atable-head"><h3>Transaction Log</h3></div>
      <table><thead><tr><th>ID</th><th>Type</th><th>Description</th><th>Amount</th><th>Date</th></tr></thead>
      <tbody>${ts.map(t=>`<tr><td><code style="font-size:10px;color:var(--txt3);background:#f5f5f5;padding:2px 6px;border-radius:4px">${t.id.slice(-6).toUpperCase()}</code></td><td><span class="badge ${t.type==='topup'?'ba':t.type==='payment'?'bb':'bg'}">${t.type}</span></td><td>${t.desc}</td><td style="font-weight:800;color:${t.amount>0?'var(--g)':'var(--red)'}">${t.amount>0?'+':''}Rs ${Math.abs(t.amount).toLocaleString()}</td><td>${t.date}</td></tr>`).join('')}</tbody></table></div>`
}
function renderAdminAnalytics(){
  document.getElementById('ac-analytics').innerHTML=`
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
      <div class="atable"><div class="atable-head"><h3>Top Services by Bookings</h3></div><div style="padding:18px">${[['🧹 Maid',82,['var(--g)']],['👨‍🍳 Cook',58,'var(--amb)'],['⚡ Electrician',34,'var(--blu)'],['🔒 Security',21,'var(--pur)'],['🔧 Plumber',18,'var(--red)']].map(([s,p,c])=>`<div style="display:flex;align-items:center;gap:10px;margin-bottom:12px"><span style="font-size:13px;width:130px">${s}</span><div style="flex:1;height:8px;background:var(--border);border-radius:4px"><div style="width:${p}%;height:100%;background:${c};border-radius:4px;transition:width .5s"></div></div><span style="font-size:12px;font-weight:800;width:35px;text-align:right;color:${c}">${p}%</span></div>`).join('')}</div></div>
      <div class="atable"><div class="atable-head"><h3>Users by City</h3></div><div style="padding:18px">${[['🌆 Islamabad','1,284','var(--g)'],['🌇 Lahore','842','var(--amb)'],['🌃 Karachi','391','var(--blu)'],['🏙️ Rawalpindi','124','var(--pur)']].map(([c,u,col])=>`<div style="display:flex;justify-content:space-between;align-items:center;padding:12px 0;border-bottom:1px solid var(--border)"><span style="font-size:14px">${c}</span><span style="font-weight:800;color:${col};font-size:15px">${u} users</span></div>`).join('')}</div></div>
    </div>`
}
function renderAdminDisputes(){
  document.getElementById('ac-disputes').innerHTML=`
    <div class="atable"><div class="atable-head"><h3>Open Disputes</h3><span class="badge br" style="padding:5px 14px;font-size:12px">2 Open</span></div><div style="padding:18px">
      ${[{id:'D-041',booking:'#B1279',parties:'Omar Khan vs Saba Begum',reason:'"Worker did not show up and is not responding."',filed:'Jan 3, 2025',escrow:'Rs 1,800'},{id:'D-040',booking:'#B1271',parties:'Hina Javed vs Ali (Cook)',reason:'"Food quality was very poor, not as agreed."',filed:'Dec 30, 2024',escrow:'Rs 5,000'}].map(d=>`
        <div style="border:1.5px solid var(--border);border-radius:14px;padding:18px;margin-bottom:12px;background:#fafafa">
          <div style="display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px">
            <div><div style="font-size:15px;font-weight:800">Dispute #${d.id}</div><div style="font-size:12px;color:var(--txt2);margin-top:3px">Booking ${d.booking} · ${d.parties}</div><div style="font-size:12px;color:var(--txt2);margin-top:3px">Reason: ${d.reason}</div><div style="font-size:11px;color:var(--txt3);margin-top:6px">Filed: ${d.filed} · ${d.escrow} in escrow</div></div>
            <div style="display:flex;gap:8px;align-items:flex-start"><button class="btn btn-o btn-sm">View Chat</button><button class="btn btn-g btn-sm" onclick="toast('Dispute #${d.id} resolved!');this.closest('[style*=border-radius:14px]').remove()">✓ Resolve</button></div>
          </div>
        </div>`).join('')}
    </div></div>`
}
function renderAdminSettings(){
  document.getElementById('ac-settings').innerHTML=`
    <div style="background:#fff;border-radius:18px;border:1.5px solid var(--border);padding:28px;max-width:560px;box-shadow:0 4px 20px rgba(0,0,0,.06)">
      <h3 style="font-size:18px;font-weight:800;margin-bottom:22px">Platform Settings</h3>
      ${[['Platform Fee (%)','10','number'],['Min Booking Amount (Rs)','200','number'],['OTP Expiry (minutes)','10','number'],['Max Travel Radius (km)','15','number']].map(([l,v,t])=>`<div style="margin-bottom:16px"><label style="font-size:10px;font-weight:700;color:var(--txt2);text-transform:uppercase;letter-spacing:.5px;display:block;margin-bottom:6px">${l}</label><input class="finput2" value="${v}" type="${t}" style="width:100%;font-size:14px;padding:11px 14px"></div>`).join('')}
      <div style="margin-bottom:16px"><label style="font-size:10px;font-weight:700;color:var(--txt2);text-transform:uppercase;letter-spacing:.5px;display:block;margin-bottom:6px">Payment Methods</label><select class="finput2" style="width:100%;font-size:14px;padding:11px 14px"><option>Easypaisa + JazzCash</option><option>Easypaisa only</option><option>JazzCash only</option></select></div>
      <div style="display:flex;justify-content:space-between;align-items:center;background:var(--gl);border-radius:12px;padding:14px 18px;margin-bottom:20px;border:1px solid #9FE1CB">
        <div><div style="font-size:14px;font-weight:700">Maintenance Mode</div><div style="font-size:12px;color:var(--txt2);margin-top:2px">Disable public access to the platform</div></div>
        <input type="checkbox" style="width:20px;height:20px;cursor:pointer;accent-color:var(--g)">
      </div>
      <button class="btn btn-g" style="width:100%;padding:14px;font-size:15px" onclick="toast('Settings saved successfully! ✅')">Save Settings</button>
    </div>`
}
</script>
</body>
</html>
