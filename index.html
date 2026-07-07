<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
<title>نوفا دروب · سحب USDT</title>
<script src="https://telegram.org/js/telegram-web-app.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@500;600;700;800&family=Tajawal:wght@400;500;700&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">
<style>
  :root{
    /* ---- Nova Drop token system ---- */
    --void:#05060e;
    --deep:#0b0e1e;
    --purple-deep:#180f36;
    --purple-mid:#2c1b63;
    --ton-cyan:#0088CC;
    --cyan-glow:#28c8ff;
    --usdt-green:#26A17B;
    --green-glow:#33e6a8;
    --warn:#ffc65c;
    --danger:#ff5c73;
    --glass:rgba(255,255,255,0.055);
    --glass-strong:rgba(255,255,255,0.09);
    --glass-border:rgba(255,255,255,0.14);
    --text-1:#f3f5ff;
    --text-2:#a6adc9;
    --text-3:#6b7290;
    --radius-lg:22px;
    --radius-md:16px;
    --radius-sm:11px;
    --font-display:'Cairo', sans-serif;
    --font-body:'Tajawal', sans-serif;
    --font-mono:'JetBrains Mono', monospace;

    /* Telegram theme fallbacks */
    --tg-bg: var(--tg-theme-bg-color, var(--void));
    --tg-safe-top: env(safe-area-inset-top, 0px);
    --tg-safe-bottom: env(safe-area-inset-bottom, 0px);
  }

  *{ box-sizing:border-box; -webkit-tap-highlight-color:transparent; }
  html,body{
    margin:0; padding:0; width:100%; min-height:100%;
    background:var(--void);
    color:var(--text-1);
    font-family:var(--font-body);
    overflow-x:hidden;
  }
  body{
    padding-top:calc(var(--tg-safe-top) + 10px);
    padding-bottom:calc(var(--tg-safe-bottom) + 18px);
  }

  /* ---------- ambient background ---------- */
  .bg-layer{ position:fixed; inset:0; z-index:0; overflow:hidden; pointer-events:none; }
  .bg-layer .blob{
    position:absolute; border-radius:50%; filter:blur(70px); opacity:.55;
    animation:drift 18s ease-in-out infinite;
  }
  .blob.b1{ width:340px; height:340px; left:-120px; top:-80px;
    background:radial-gradient(circle, var(--purple-mid), transparent 70%); }
  .blob.b2{ width:300px; height:300px; right:-110px; top:220px;
    background:radial-gradient(circle, rgba(0,136,204,.55), transparent 70%); animation-delay:-6s; }
  .blob.b3{ width:280px; height:280px; left:10%; bottom:-140px;
    background:radial-gradient(circle, rgba(38,161,123,.45), transparent 70%); animation-delay:-11s; }
  @keyframes drift{
    0%,100%{ transform:translate(0,0) scale(1); }
    50%{ transform:translate(18px,-24px) scale(1.08); }
  }
  .stars{ position:absolute; inset:0; }
  .star{ position:absolute; width:2px; height:2px; background:#fff; border-radius:50%; opacity:.5;
    animation:twinkle 3.5s ease-in-out infinite; }
  @keyframes twinkle{ 0%,100%{ opacity:.15; } 50%{ opacity:.9; } }

  .app{ position:relative; z-index:1; max-width:480px; margin:0 auto; padding:0 18px; }

  /* ---------- status pill ---------- */
  .status-row{ display:flex; justify-content:center; margin-bottom:6px; }
  .status-pill{
    display:inline-flex; align-items:center; gap:7px;
    background:var(--glass); border:1px solid var(--glass-border);
    padding:6px 14px; border-radius:999px; backdrop-filter:blur(14px);
    font-size:12px; letter-spacing:.04em; color:var(--text-2);
  }
  .dot-live{ width:7px; height:7px; border-radius:50%; background:var(--green-glow);
    box-shadow:0 0 8px var(--green-glow); animation:pulse-dot 1.6s ease-in-out infinite; }
  @keyframes pulse-dot{ 0%,100%{ opacity:1; transform:scale(1);} 50%{ opacity:.4; transform:scale(.75);} }

  /* ---------- hero / prize orb ---------- */
  .hero{ display:flex; flex-direction:column; align-items:center; text-align:center; padding:18px 0 6px; }
  .orb-wrap{ position:relative; width:148px; height:148px; margin-bottom:14px; }
  .orb-ring{
    position:absolute; inset:0; border-radius:50%;
    background:conic-gradient(from 0deg, var(--ton-cyan), var(--usdt-green), var(--purple-mid), var(--ton-cyan));
    filter:blur(1px);
    animation:spin 7s linear infinite;
    -webkit-mask:radial-gradient(farthest-side, transparent calc(100% - 6px), #000 calc(100% - 5px));
            mask:radial-gradient(farthest-side, transparent calc(100% - 6px), #000 calc(100% - 5px));
  }
  @keyframes spin{ to{ transform:rotate(360deg); } }
  .orb-core{
    position:absolute; inset:12px; border-radius:50%;
    background:radial-gradient(circle at 32% 28%, rgba(255,255,255,.18), transparent 45%),
               linear-gradient(155deg, #101a33, #0a0d1c 60%);
    border:1px solid var(--glass-border);
    display:flex; align-items:center; justify-content:center;
    box-shadow:0 0 34px rgba(0,194,255,.28), inset 0 0 24px rgba(0,0,0,.5);
    animation:orb-pulse 3s ease-in-out infinite;
  }
  @keyframes orb-pulse{ 0%,100%{ box-shadow:0 0 34px rgba(0,194,255,.28), inset 0 0 24px rgba(0,0,0,.5);} 50%{ box-shadow:0 0 46px rgba(51,230,168,.38), inset 0 0 24px rgba(0,0,0,.5);} }
  .orb-core svg{ width:56px; height:56px; animation:coin-flip 4.2s ease-in-out infinite; }
  @keyframes coin-flip{ 0%,40%{ transform:rotateY(0deg);} 50%{ transform:rotateY(180deg);} 90%,100%{ transform:rotateY(360deg);} }
  .orb-particles span{
    position:absolute; width:5px; height:5px; border-radius:50%;
    background:var(--cyan-glow); box-shadow:0 0 8px var(--cyan-glow);
    top:50%; left:50%; transform-origin:0 0;
    animation:orbit 5s linear infinite;
  }
  .orb-particles span:nth-child(2){ background:var(--green-glow); box-shadow:0 0 8px var(--green-glow); animation-duration:6.5s; animation-direction:reverse; }
  .orb-particles span:nth-child(3){ background:#fff; opacity:.7; animation-duration:8s; }
  @keyframes orbit{
    from{ transform:rotate(0deg) translateX(88px) rotate(0deg); }
    to{ transform:rotate(360deg) translateX(88px) rotate(-360deg); }
  }

  .eyebrow{ font-family:var(--font-mono); font-size:11px; letter-spacing:.16em; color:var(--green-glow); text-transform:uppercase; margin:0 0 6px; }
  h1.title{ font-family:var(--font-display); font-weight:700; font-size:30px; line-height:1.08; margin:0 0 8px;
    background:linear-gradient(100deg,#fff 20%, var(--cyan-glow) 55%, var(--green-glow) 85%);
    -webkit-background-clip:text; background-clip:text; color:transparent; letter-spacing:-0.01em; }
  .subtitle{ color:var(--text-2); font-size:14px; line-height:1.5; margin:0 0 4px; max-width:340px; }
  .pool{ font-family:var(--font-mono); font-size:13px; color:var(--text-3); margin-top:2px; }
  .pool b{ color:var(--text-1); font-weight:700; }


  /* ---------- divider ---------- */
  .divider{ display:flex; align-items:center; gap:10px; margin:22px 0 14px; color:var(--text-3); font-size:11px; letter-spacing:.08em; text-transform:uppercase; }
  .divider::before,.divider::after{ content:""; flex:1; height:1px; background:linear-gradient(90deg, transparent, var(--glass-border), transparent); }

  /* ---------- already-registered banner ---------- */
  .already-note{
    display:none; align-items:flex-start; gap:9px; margin-bottom:14px;
    background:rgba(255,198,92,.08); border:1px solid rgba(255,198,92,.3); border-radius:var(--radius-md);
    padding:12px 13px; font-size:12.5px; line-height:1.6; color:var(--warn);
  }
  .already-note.show{ display:flex; }
  .already-note svg{ flex:none; margin-top:1px; }
  .already-note b{ color:#fff; }

  .field.locked input{ opacity:.55; cursor:not-allowed; background:rgba(255,255,255,.02); }
  .field.locked .hint{ color:var(--text-3); }

  /* ---------- toast ---------- */
  .toast{
    position:fixed; left:50%; bottom:24px; transform:translateX(-50%) translateY(20px);
    background:rgba(20,24,44,.95); border:1px solid var(--glass-border); color:var(--text-1);
    padding:12px 20px; border-radius:999px; font-size:13px; font-weight:600;
    box-shadow:0 8px 26px rgba(0,0,0,.4); opacity:0; pointer-events:none; z-index:60;
    transition:opacity .3s ease, transform .3s ease; white-space:nowrap;
  }
  .toast.show{ opacity:1; transform:translateX(-50%) translateY(0); }

  /* ---------- glass card / form ---------- */
  .card{
    background:linear-gradient(180deg, var(--glass-strong), var(--glass));
    border:1px solid var(--glass-border); border-radius:var(--radius-lg);
    padding:20px 18px 18px; backdrop-filter:blur(18px);
    box-shadow:0 8px 30px rgba(0,0,0,.35), inset 0 1px 0 rgba(255,255,255,.06);
    position:relative; overflow:hidden;
  }
  .card::before{ content:""; position:absolute; top:-40%; left:-20%; width:60%; height:180%;
    background:linear-gradient(120deg, rgba(255,255,255,.06), transparent 60%); pointer-events:none; }

  .field{ position:relative; margin-bottom:16px; }
  .field label{
    position:absolute; inset-inline-start:14px; top:15px; font-size:14.5px; color:var(--text-3);
    pointer-events:none; transition:.18s ease; background:transparent; padding:0 4px;
  }
  .field input{
    width:100%; padding:17px 14px 9px 14px; border-radius:var(--radius-sm);
    background:rgba(255,255,255,.04); border:1px solid var(--glass-border);
    color:var(--text-1); font-size:15px; font-family:var(--font-mono);
    outline:none; transition:.18s ease;
  }
  .field input::placeholder{ color:transparent; }
  .field input:focus{ border-color:var(--ton-cyan); background:rgba(0,136,204,.07);
    box-shadow:0 0 0 3px rgba(0,136,204,.16), 0 0 18px rgba(0,136,204,.25); }
  .field input:focus + label,
  .field input:not(:placeholder-shown) + label{
    top:5px; font-size:10.5px; letter-spacing:.03em; color:var(--cyan-glow); text-transform:uppercase;
  }
  .field .hint{ display:block; font-size:11px; color:var(--text-3); margin-top:6px; padding-left:2px; transition:.2s; }
  .field.valid input{ border-color:var(--usdt-green); box-shadow:0 0 0 3px rgba(38,161,123,.15); }
  .field.valid .hint{ color:var(--green-glow); }
  .field.invalid input{ border-color:var(--danger); box-shadow:0 0 0 3px rgba(255,92,115,.15); animation:shake .32s; }
  .field.invalid .hint{ color:var(--danger); }
  .field .check-icon{ position:absolute; inset-inline-end:12px; top:15px; opacity:0; transform:scale(.6); transition:.2s; color:var(--green-glow); }
  .field.valid .check-icon{ opacity:1; transform:scale(1); }
  @keyframes shake{ 20%,60%{ transform:translateX(-5px);} 40%,80%{ transform:translateX(5px);} }

  .join-btn{
    width:100%; border:none; cursor:pointer; padding:16px; border-radius:var(--radius-md);
    font-family:var(--font-display); font-weight:700; font-size:16px; letter-spacing:.01em; color:#04140f;
    background:linear-gradient(95deg, var(--cyan-glow), var(--green-glow));
    box-shadow:0 6px 24px rgba(51,230,168,.35), 0 0 0 1px rgba(255,255,255,.15) inset;
    position:relative; overflow:hidden; transition:transform .12s ease, box-shadow .25s ease;
  }
  .join-btn:active{ transform:scale(.97); }
  .join-btn.pulsing{ animation:btn-pulse 2.1s ease-in-out infinite; }
  @keyframes btn-pulse{
    0%,100%{ box-shadow:0 6px 24px rgba(51,230,168,.35), 0 0 0 1px rgba(255,255,255,.15) inset; }
    50%{ box-shadow:0 6px 34px rgba(0,194,255,.55), 0 0 0 1px rgba(255,255,255,.2) inset; }
  }
  .join-btn:disabled{ opacity:.6; cursor:not-allowed; }
  .join-btn .btn-label{ display:flex; align-items:center; justify-content:center; gap:9px; }
  .spinner{ width:16px; height:16px; border-radius:50%; border:2.5px solid rgba(4,20,15,.3); border-top-color:#04140f;
    animation:spin .7s linear infinite; display:none; }
  .join-btn.loading .spinner{ display:inline-block; }
  .join-btn.loading .btn-text{ opacity:0; width:0; }

  .fine-print{ text-align:center; font-size:11px; color:var(--text-3); margin-top:12px; line-height:1.5; }

  /* ---------- success card ---------- */
  .success-card{ display:none; text-align:center; padding:28px 18px 22px; }
  .success-card.show{ display:block; animation:pop-in .5s cubic-bezier(.2,.9,.3,1.3); }
  @keyframes pop-in{ from{ opacity:0; transform:scale(.85) translateY(10px);} to{ opacity:1; transform:scale(1) translateY(0);} }
  .check-circle{
    width:74px; height:74px; margin:0 auto 16px; border-radius:50%;
    background:radial-gradient(circle at 35% 30%, rgba(255,255,255,.15), transparent 60%), linear-gradient(145deg, var(--usdt-green), #14735a);
    display:flex; align-items:center; justify-content:center;
    box-shadow:0 0 0 6px rgba(38,161,123,.15), 0 0 30px rgba(51,230,168,.5);
  }
  .check-circle svg{ width:34px; height:34px; }
  .check-circle path{ stroke-dasharray:48; stroke-dashoffset:48; animation:draw-check .5s .15s ease forwards; }
  @keyframes draw-check{ to{ stroke-dashoffset:0; } }
  .success-card h2{ font-family:var(--font-display); font-size:21px; margin:0 0 6px; }
  .success-card p.msg{ color:var(--text-2); font-size:13.5px; margin:0 0 18px; }
  .ref-box{
    display:flex; align-items:center; gap:8px; background:rgba(255,255,255,.05);
    border:1px solid var(--glass-border); border-radius:var(--radius-sm); padding:11px 12px; margin-bottom:14px;
  }
  .ref-box input{ flex:1; background:transparent; border:none; outline:none; color:var(--cyan-glow); font-family:var(--font-mono); font-size:12.5px; min-width:0; }
  .copy-btn{ background:rgba(0,136,204,.18); border:1px solid rgba(0,136,204,.4); color:#fff; border-radius:8px;
    padding:7px 11px; font-size:12px; font-family:var(--font-body); font-weight:600; cursor:pointer; white-space:nowrap; transition:.15s; }
  .copy-btn:active{ transform:scale(.94); }
  .copy-btn.copied{ background:rgba(38,161,123,.3); border-color:var(--usdt-green); }
  .share-btn{
    width:100%; padding:13px; border-radius:var(--radius-md); border:1px solid var(--glass-border);
    background:linear-gradient(180deg, rgba(0,136,204,.18), rgba(0,136,204,.06)); color:#fff;
    font-family:var(--font-display); font-weight:600; font-size:14.5px; cursor:pointer;
    display:flex; align-items:center; justify-content:center; gap:8px;
  }
  .entry-number{ font-family:var(--font-mono); font-size:11px; color:var(--text-3); margin-top:14px; }
  .entry-number b{ color:var(--green-glow); }

  #confetti-canvas{ position:fixed; inset:0; pointer-events:none; z-index:50; }

  footer.appfoot{ text-align:center; margin-top:22px; color:var(--text-3); font-size:10.5px; line-height:1.6; }
  footer.appfoot a{ color:var(--cyan-glow); text-decoration:none; }

  @media (prefers-reduced-motion: reduce){
    *{ animation-duration:.001ms !important; animation-iteration-count:1 !important; transition-duration:.001ms !important; }
  }
</style>
</head>
<body>

<div class="bg-layer">
  <div class="blob b1"></div>
  <div class="blob b2"></div>
  <div class="blob b3"></div>
  <div class="stars" id="stars"></div>
</div>

<div class="app">

  <div class="status-row">
    <div class="status-pill"><span class="dot-live"></span> السحب مفتوح الآن</div>
  </div>

  <div class="hero">
    <div class="orb-wrap">
      <div class="orb-ring"></div>
      <div class="orb-particles"><span></span><span></span><span></span></div>
      <div class="orb-core">
        <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="16" cy="16" r="15" fill="#26A17B" stroke="#0b3c2f" stroke-width="1"/>
          <path d="M17.9 13.2v-2h4.7V8.4H9.4v2.8h4.7v2c-3.8.2-6.7 1-6.7 1.9s2.9 1.7 6.7 1.9v6.8h3.8v-6.8c3.8-.2 6.7-1 6.7-1.9s-2.9-1.7-6.7-1.9zm0 3.2v-.01c-.1 0-.6.03-1.9.03-1 0-1.7-.02-1.9-.03v.01c-3.9-.17-6.8-.86-6.8-1.68s2.9-1.5 6.8-1.68v2.68c.2.01.9.05 1.9.05 1.24 0 1.8-.05 1.9-.05v-2.68c3.9.17 6.8.86 6.8 1.68s-2.9 1.51-6.8 1.68z" fill="#fff"/>
        </svg>
      </div>
    </div>
    <p class="eyebrow">نوفا دروب</p>
    <h1 class="title">شارك وعزز فرصك<br>بجوائز تصل إلى 10 USDT</h1>
    <p class="subtitle">أدخل بياناتك وشارك رابطك — كل مشاركة تمنحك إدخالات إضافية وترفع فرصتك في السحب العشوائي.</p>
    <p class="pool">السحب: <b>عشوائي بين المشاركين</b> · الجائزة: <b dir="ltr">حتى 10 USDT</b> · الشبكة: <b>TON</b></p>
  </div>

  <div class="divider">أدخل بياناتك للمشاركة</div>

  <div class="already-note" id="already-note">
    <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M12 8v5M12 16h.01M12 22a10 10 0 100-20 10 10 0 000 20z" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg>
    <span>أنت مسجَّل بالفعل في السحب باسم <b id="already-name">—</b>. لا يمكن المشاركة مرتين بنفس الحساب، لكن يمكنك تعديل عنوان محفظتك أدناه إذا كان غير صحيح.</span>
  </div>

  <div class="card" id="form-card">
    <form id="join-form" novalidate>
      <div class="field" id="field-name">
        <input id="tg-name" type="text" placeholder=" " autocomplete="off" dir="auto" />
        <label for="tg-name">اسمك على تيليجرام</label>
        <span class="check-icon">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M5 13l4 4L19 7" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </span>
        <span class="hint" id="hint-name">مثال: ‎@yourname‎ — من 5 إلى 32 حرفًا</span>
      </div>

      <div class="field" id="field-wallet">
        <input id="ton-wallet" type="text" placeholder=" " autocomplete="off" dir="ltr" style="text-align:right" />
        <label for="ton-wallet">عنوان محفظة USDT (شبكة TON)</label>
        <span class="check-icon">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M5 13l4 4L19 7" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </span>
        <span class="hint" id="hint-wallet">عنوان USDT على شبكة TON — يبدأ بـ EQ أو UQ، ويتكون من 48 حرفًا</span>
      </div>

      <button type="submit" class="join-btn pulsing" id="join-btn">
        <span class="btn-label">
          <span class="spinner"></span>
          <span class="btn-text" id="btn-text">انضم إلى السحب ←</span>
        </span>
      </button>
      <p class="fine-print" id="fine-print">لا يتطلب أي عملية شراء. إدخال واحد لكل حساب تيليجرام.<br>شارك رابطك بعد التسجيل لزيادة فرصك في الفوز.</p>
    </form>

    <div class="success-card" id="success-card">
      <div class="check-circle">
        <svg viewBox="0 0 24 24" fill="none"><path d="M5 13l4 4L19 7" stroke="#fff" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </div>
      <h2>أنت الآن ضمن السحب!</h2>
      <p class="msg">حظًا موفقًا — الفوز يتم عبر سحب عشوائي بين المشاركين. شارك رابطك لزيادة عدد إدخالاتك ورفع فرصتك.</p>
      <div class="ref-box">
        <input id="ref-link" type="text" readonly dir="ltr" style="text-align:left" />
        <button class="copy-btn" id="copy-btn">نسخ</button>
      </div>
      <button class="share-btn" id="share-btn">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M22 2L11 13M22 2l-7 20-4-9-9-4 20-7z" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg>
        مشاركة على تيليجرام
      </button>
      <p class="entry-number">الإدخال رقم <b id="entry-num" dir="ltr">—</b> · مكافأة الإحالة: <b>+2 إدخال</b> لكل صديق</p>
    </div>
  </div>

  <footer class="appfoot">
    نوفا دروب فعالية مجتمعية مستقلة تُسوَّى على بلوكتشين TON.<br>
    مدعوم بواسطة <a href="#">Telegram Mini Apps</a> · السحب قابل للتحقق على البلوكتشين.
  </footer>
</div>

<canvas id="confetti-canvas"></canvas>
<div class="toast" id="toast"></div>

<script>
(function(){
  "use strict";

  /* ---------------- Telegram WebApp bootstrap ---------------- */
  var tg = window.Telegram && window.Telegram.WebApp ? window.Telegram.WebApp : null;
  if (tg) {
    try {
      tg.ready();
      tg.expand();
      tg.setHeaderColor && tg.setHeaderColor('#05060e');
      tg.setBackgroundColor && tg.setBackgroundColor('#05060e');
      tg.MainButton && tg.MainButton.hide();
    } catch(e) {}
  }
  function haptic(type){
    if (tg && tg.HapticFeedback) {
      try {
        if (type === 'success') tg.HapticFeedback.notificationOccurred('success');
        else if (type === 'error') tg.HapticFeedback.notificationOccurred('error');
        else tg.HapticFeedback.impactOccurred(type || 'light');
      } catch(e) {}
    }
  }

  /* ---------------- Supabase client ----------------
     املأ القيمتين التاليتين من: Supabase Dashboard → Project Settings → API
     - Project URL         → SUPABASE_URL
     - anon public key     → SUPABASE_ANON_KEY
     (المفتاح anon مخصص للاستخدام في المتصفح ولا يعطي وصولاً مباشرًا للجدول،
      لأن الجدول محمي ولا يُستخدَم إلا عبر الدالتين get_entry / upsert_entry). */
  var SUPABASE_URL = 'https://bksoohuzmwntforypkxc.supabase.co';
  var SUPABASE_ANON_KEY = 'sb_publishable_tpYDGyFN_dzdPQPWVKRqlg_ezEtE8IS';
  var supabase = null;
  var supabaseReady = SUPABASE_URL.indexOf('YOUR-PROJECT') === -1 && SUPABASE_ANON_KEY.indexOf('YOUR_ANON') === -1;
  if (supabaseReady && window.supabase) {
    supabase = window.supabase.createClient(SUPABASE_URL, SUPABASE_ANON_KEY);
  } else {
    console.warn('Supabase غير مُهيّأ بعد — يرجى وضع SUPABASE_URL و SUPABASE_ANON_KEY الحقيقيين.');
  }

  /* ---------------- unique user id ----------------
     الأساس الوحيد الموثوق لمنع التكرار هو user.id القادم من تيليجرام،
     وليس الاسم المكتوب يدويًا (قابل للتكرار) ولا اليوزرنيم (قابل للتغيير/قد يكون فارغًا). */
  function getCurrentUserId(){
    if (tg && tg.initDataUnsafe && tg.initDataUnsafe.user && tg.initDataUnsafe.user.id) {
      return String(tg.initDataUnsafe.user.id);
    }
    // احتياطي للمعاينة خارج تيليجرام فقط (متصفح عادي) — لا يُستخدم في الإنتاج الفعلي.
    var demoId = localStorage.getItem('nova_demo_uid');
    if (!demoId) {
      demoId = 'demo_' + Math.random().toString(36).slice(2, 10);
      localStorage.setItem('nova_demo_uid', demoId);
    }
    return demoId;
  }
  var currentUserId = getCurrentUserId();

  /* ---------------- entries store ----------------
     يعمل عبر Supabase (get_entry / upsert_entry) عند تهيئته.
     إن لم تُملأ المفاتيح بعد، يتراجع مؤقتًا إلى localStorage للمعاينة فقط —
     هذا التراجع للاختبار المحلي حصرًا ولا يمنع التكرار الحقيقي بين الأجهزة. */
  var ENTRY_PREFIX = 'nova_entry_';
  var api = {
    getEntry: function(userId){
      if (supabase) {
        return supabase.rpc('get_entry', { p_telegram_id: userId }).then(function(res){
          if (res.error) { console.error('get_entry error:', res.error); return null; }
          var row = res.data && res.data[0];
          return row ? { id: row.telegram_id, name: row.name, wallet: row.wallet } : null;
        });
      }
      var raw = localStorage.getItem(ENTRY_PREFIX + userId);
      return Promise.resolve(raw ? JSON.parse(raw) : null);
    },
    saveEntry: function(entry){
      if (supabase) {
        return supabase.rpc('upsert_entry', {
          p_telegram_id: entry.id,
          p_name: entry.name,
          p_wallet: entry.wallet
        }).then(function(res){
          if (res.error) { console.error('upsert_entry error:', res.error); throw res.error; }
          var row = res.data && res.data[0];
          return row ? { id: row.telegram_id, name: row.name, wallet: row.wallet } : entry;
        });
      }
      localStorage.setItem(ENTRY_PREFIX + entry.id, JSON.stringify(entry));
      return Promise.resolve(entry);
    }
  };

  /* ---------------- toast ---------------- */
  var toastEl = document.getElementById('toast');
  var toastTimer = null;
  function showToast(msg){
    toastEl.textContent = msg;
    toastEl.classList.add('show');
    clearTimeout(toastTimer);
    toastTimer = setTimeout(function(){ toastEl.classList.remove('show'); }, 2600);
  }

  /* ---------------- background starfield ---------------- */
  var starsEl = document.getElementById('stars');
  var starHtml = '';
  for (var i = 0; i < 44; i++) {
    var top = Math.random() * 100, left = Math.random() * 100, delay = (Math.random() * 3.5).toFixed(2);
    starHtml += '<span class="star" style="top:' + top + '%; left:' + left + '%; animation-delay:' + delay + 's;"></span>';
  }
  starsEl.innerHTML = starHtml;

  /* ---------------- form validation ---------------- */
  var nameInput = document.getElementById('tg-name');
  var walletInput = document.getElementById('ton-wallet');
  var fieldName = document.getElementById('field-name');
  var fieldWallet = document.getElementById('field-wallet');
  var hintName = document.getElementById('hint-name');
  var hintWallet = document.getElementById('hint-wallet');
  var joinBtn = document.getElementById('join-btn');
  var btnText = document.getElementById('btn-text');
  var form = document.getElementById('join-form');
  var alreadyNote = document.getElementById('already-note');
  var alreadyNameEl = document.getElementById('already-name');
  var finePrintEl = document.getElementById('fine-print');
  var isEditMode = false;

  var NAME_RE = /^@?[a-zA-Z0-9_]{5,32}$/;
  var WALLET_RE = /^(EQ|UQ)[A-Za-z0-9_-]{46}$/;

  function validateName(showState){
    var v = nameInput.value.trim();
    var valid = NAME_RE.test(v);
    if (showState && v.length > 0) {
      fieldName.classList.toggle('valid', valid);
      fieldName.classList.toggle('invalid', !valid);
      hintName.textContent = valid ? 'يبدو جيدًا' : 'مثال: @yourname — من 5 إلى 32 حرفًا/رقمًا أو شرطة سفلية _';
    } else if (v.length === 0) {
      fieldName.classList.remove('valid', 'invalid');
      hintName.textContent = 'مثال: @yourname — من 5 إلى 32 حرفًا';
    }
    return valid;
  }

  function validateWallet(showState){
    var v = walletInput.value.trim();
    var valid = WALLET_RE.test(v);
    if (showState && v.length > 0) {
      fieldWallet.classList.toggle('valid', valid);
      fieldWallet.classList.toggle('invalid', !valid);
      hintWallet.textContent = valid ? 'عنوان محفظة صالح' : 'يجب أن يبدأ بـ EQ أو UQ ويتكون من 48 حرفًا';
    } else if (v.length === 0) {
      fieldWallet.classList.remove('valid', 'invalid');
      hintWallet.textContent = 'يبدأ بـ EQ أو UQ، ويتكون من 48 حرفًا';
    }
    return valid;
  }

  nameInput.addEventListener('input', function(){ validateName(true); });
  walletInput.addEventListener('blur', function(){ validateWallet(true); });
  nameInput.addEventListener('blur', function(){ validateName(true); });
  walletInput.addEventListener('input', function(){ validateWallet(true); });

  /* ---------------- duplicate check / edit mode ---------------- */
  function enterEditMode(entry){
    isEditMode = true;

    alreadyNameEl.textContent = entry.name;
    alreadyNote.classList.add('show');

    nameInput.value = entry.name;
    fieldName.classList.add('locked', 'valid');
    nameInput.disabled = true;

    walletInput.value = entry.wallet;
    validateWallet(true);
    walletInput.focus();

    joinBtn.classList.remove('pulsing');
    btnText.textContent = 'تحديث عنوان المحفظة';
    finePrintEl.innerHTML = 'اسمك وحسابك ثابتان ولا يمكن تغييرهما. يمكنك فقط تصحيح عنوان محفظتك إن كان خاطئًا.';
  }

  api.getEntry(currentUserId).then(function(existing){
    if (existing) enterEditMode(existing);
  }).catch(function(err){
    console.error('getEntry error:', err);
  });

  /* ---------------- confetti ---------------- */
  var canvas = document.getElementById('confetti-canvas');
  var ctx = canvas.getContext('2d');
  function resizeCanvas(){ canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
  resizeCanvas();
  window.addEventListener('resize', resizeCanvas);

  function burstConfetti(){
    var colors = ['#0088CC','#26A17B','#33e6a8','#28c8ff','#ffc65c','#ffffff'];
    var particles = [];
    var count = 90;
    for (var i = 0; i < count; i++) {
      particles.push({
        x: canvas.width / 2,
        y: canvas.height * 0.32,
        vx: (Math.random() - 0.5) * 11,
        vy: Math.random() * -9 - 3,
        size: Math.random() * 6 + 4,
        color: colors[Math.floor(Math.random() * colors.length)],
        rot: Math.random() * 360,
        vr: (Math.random() - 0.5) * 12,
        life: 0,
        maxLife: 90 + Math.random() * 40
      });
    }
    var gravity = 0.32;
    function frame(){
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      var alive = false;
      for (var i = 0; i < particles.length; i++) {
        var p = particles[i];
        if (p.life > p.maxLife) continue;
        alive = true;
        p.vy += gravity;
        p.x += p.vx;
        p.y += p.vy;
        p.rot += p.vr;
        p.life++;
        var alpha = 1 - p.life / p.maxLife;
        ctx.save();
        ctx.globalAlpha = Math.max(alpha, 0);
        ctx.translate(p.x, p.y);
        ctx.rotate(p.rot * Math.PI / 180);
        ctx.fillStyle = p.color;
        ctx.fillRect(-p.size / 2, -p.size / 2, p.size, p.size * 0.6);
        ctx.restore();
      }
      if (alive) requestAnimationFrame(frame);
      else ctx.clearRect(0, 0, canvas.width, canvas.height);
    }
    requestAnimationFrame(frame);
  }

  /* ---------------- submit flow ---------------- */
  var formCard = document.getElementById('form-card');
  var successCard = document.getElementById('success-card');
  var refLinkInput = document.getElementById('ref-link');
  var copyBtn = document.getElementById('copy-btn');
  var shareBtn = document.getElementById('share-btn');
  var entryNumEl = document.getElementById('entry-num');

  function makeReferralCode(name){
    var clean = name.replace(/[^a-zA-Z0-9]/g, '').toLowerCase() || 'nova';
    // Arabic-only handles fall back to the "nova" slug above since referral codes stay Latin for URL-safety.
    var hash = 0;
    for (var i = 0; i < clean.length; i++) hash = (hash * 31 + clean.charCodeAt(i)) >>> 0;
    return clean.slice(0, 10) + (hash % 9999);
  }

  form.addEventListener('submit', function(e){
    e.preventDefault();
    var nameValid = isEditMode ? true : validateName(true);
    var walletValid = validateWallet(true);

    if (!nameValid || !walletValid) {
      haptic('error');
      if (!nameValid) { nameInput.focus(); }
      else { walletInput.focus(); }
      return;
    }

    haptic('light');
    joinBtn.classList.add('loading');
    joinBtn.disabled = true;

    var entry = {
      id: currentUserId,
      name: nameInput.value.trim(),
      wallet: walletInput.value.trim(),
      updatedAt: Date.now()
    };
    if (!isEditMode) entry.joinedAt = Date.now();

    api.saveEntry(entry).then(function(){
      joinBtn.classList.remove('loading');
      joinBtn.disabled = false;

      if (isEditMode) {
        showToast('تم تحديث عنوان محفظتك بنجاح ✓');
        haptic('success');
        return;
      }

      isEditMode = true;
      form.style.display = 'none';
      successCard.classList.add('show');

      var code = makeReferralCode(entry.name);
      refLinkInput.value = 't.me/NovaDropBot?start=' + code;
      entryNumEl.textContent = (12000 + Math.floor(Math.random() * 900)).toLocaleString();

      burstConfetti();
      haptic('success');

      if (tg && tg.MainButton) {
        try {
          tg.MainButton.setText('شارك رابطك');
          tg.MainButton.show();
          tg.MainButton.onClick(function(){ shareBtn.click(); });
        } catch(err) {}
      }
    }).catch(function(){
      joinBtn.classList.remove('loading');
      joinBtn.disabled = false;
      haptic('error');
      showToast('تعذّر الحفظ، يرجى المحاولة مرة أخرى');
    });
  });

  copyBtn.addEventListener('click', function(){
    refLinkInput.select();
    refLinkInput.setSelectionRange(0, 999);
    var done = function(){
      copyBtn.textContent = 'تم النسخ ✓';
      copyBtn.classList.add('copied');
      haptic('light');
      setTimeout(function(){ copyBtn.textContent = 'نسخ'; copyBtn.classList.remove('copied'); }, 1800);
    };
    if (navigator.clipboard && navigator.clipboard.writeText) {
      navigator.clipboard.writeText(refLinkInput.value).then(done).catch(function(){
        document.execCommand('copy'); done();
      });
    } else {
      document.execCommand('copy'); done();
    }
  });

  shareBtn.addEventListener('click', function(){
    var url = 'https://' + refLinkInput.value;
    var text = encodeURIComponent('انضممت للتو إلى نوفا دروب — جوائز تصل إلى 10 USDT عبر شبكة TON. انضم عبر رابطي:');
    var shareUrl = 'https://t.me/share/url?url=' + encodeURIComponent(url) + '&text=' + text;
    if (tg && tg.openTelegramLink) {
      try { tg.openTelegramLink(shareUrl); return; } catch(e) {}
    }
    window.open(shareUrl, '_blank');
  });

})();
</script>
</body>
</html>
