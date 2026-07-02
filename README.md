[index.html](https://github.com/user-attachments/files/29586010/index.html)
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HCD Holdings · Hệ sinh thái trí tuệ nhân tạo cho ngành nội thất cao cấp</title>
<meta name="description" content="Bảy hệ thống AI hợp nhất cho HCD Holdings — từ thiết kế nội thất gỗ óc chó, lệnh cắt CNC, quản trị ERP đến sàn thương mại & lễ tân AI. Một hệ sinh thái, một nguồn dữ liệu.">

<!-- Favicon: viên ngọc brass thương hiệu -->
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0' stop-color='%23E4C687'/><stop offset='1' stop-color='%238A6D3A'/></linearGradient></defs><circle cx='16' cy='16' r='11' fill='none' stroke='url(%23g)' stroke-width='2'/><text x='16' y='21' font-size='13' font-family='Georgia,serif' font-weight='700' fill='%23E4C687' text-anchor='middle'>H</text></svg>">
<meta name="theme-color" content="#0E0B08">
<link rel="canonical" href="https://songleholdings.com/">

<!-- Open Graph -->
<meta property="og:type" content="website">
<meta property="og:locale" content="vi_VN">
<meta property="og:site_name" content="HCD Holdings">
<meta property="og:url" content="https://songleholdings.com/">
<meta property="og:title" content="HCD Holdings · Hệ sinh thái trí tuệ nhân tạo cho ngành nội thất cao cấp">
<meta property="og:description" content="Bảy hệ thống AI hợp nhất — từ thiết kế nội thất gỗ óc chó, lệnh cắt CNC đến ERP & sàn thương mại. Đỉnh cao trí tuệ trong thiết kế & sản xuất nội thất.">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="HCD Holdings · Hệ sinh thái AI cho nội thất cao cấp">
<meta name="twitter:description" content="Bảy hệ thống trí tuệ nhân tạo hợp nhất cho tập đoàn nội thất gỗ óc chó hàng đầu.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,500;0,9..144,600;1,9..144,400&family=Be+Vietnam+Pro:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0E0B08; --bg2:#14100B; --panel:#1A140D; --panel2:#211A11;
  --line:#2B2318; --line2:#3A2F1F;
  --gold:#C9A15E; --gold-bright:#E4C687; --gold-deep:#8A6D3A;
  --sage:#9DB39B; --mist:#A79C88; --ivory:#F2ECDF; --white:#FBF8F1;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  background:var(--bg); color:var(--ivory); font-family:'Be Vietnam Pro',sans-serif;
  line-height:1.7; font-size:17px; -webkit-font-smoothing:antialiased; overflow-x:hidden;
}
.wrap{max-width:1180px;margin:0 auto;padding:0 32px}
.serif{font-family:'Fraunces',serif}
.mono{font-family:'JetBrains Mono',monospace}
a{color:inherit;text-decoration:none}
.eyebrow{font-family:'JetBrains Mono',monospace;font-size:11px;letter-spacing:.32em;text-transform:uppercase;color:var(--gold)}

/* texture + glow */
.grain{position:fixed;inset:0;z-index:1;pointer-events:none;opacity:.04;mix-blend-mode:overlay;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");}
.glow{position:fixed;inset:0;z-index:0;pointer-events:none;
  background:radial-gradient(ellipse 55% 40% at 80% -2%,rgba(201,161,94,.13),transparent 70%),
             radial-gradient(ellipse 45% 45% at 3% 22%,rgba(157,179,155,.05),transparent 70%),
             radial-gradient(ellipse 42% 38% at 96% 72%,rgba(201,161,94,.06),transparent 70%);}

.ornament{display:flex;align-items:center;gap:16px;margin:0 0 22px}
.ornament .ln{flex:0 0 42px;height:1px;background:linear-gradient(90deg,var(--gold),transparent)}
.ornament .dm{color:var(--gold);font-size:10px}

/* HEADER / NAV */
header{position:sticky;top:0;z-index:60;backdrop-filter:blur(14px);background:rgba(14,11,8,.72);border-bottom:1px solid var(--line)}
.nav{display:flex;justify-content:space-between;align-items:center;padding:16px 0}
.brand{display:flex;align-items:center;gap:14px}
.brand .seal{width:42px;height:42px;border-radius:50%;border:1px solid var(--gold);display:grid;place-items:center;
  font-family:'Fraunces',serif;font-weight:600;font-size:16px;color:var(--gold);
  background:radial-gradient(circle,rgba(201,161,94,.16),transparent);position:relative}
.brand .seal::after{content:"";position:absolute;inset:-5px;border:1px solid rgba(201,161,94,.25);border-radius:50%}
.brand .bt{font-family:'Be Vietnam Pro',sans-serif;font-weight:700;font-size:19px;letter-spacing:.01em;color:var(--white)}
.brand .bt small{display:block;font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:.26em;color:var(--mist);margin-top:2px;font-weight:400}
.nav-links{display:flex;gap:26px;font-size:14px;color:var(--mist)}
.nav-links a:hover{color:var(--gold-bright)}
.nav-cta{display:inline-flex;align-items:center;gap:8px;background:var(--gold);color:var(--bg);font-weight:600;font-size:13px;padding:10px 20px;border-radius:9px;letter-spacing:.02em;transition:.22s}
.nav-cta:hover{background:var(--gold-bright);transform:translateY(-1px)}
@media(max-width:940px){.nav-links{display:none}}

/* HERO */
.hero{position:relative;z-index:2;padding:96px 0 46px;text-align:center}
.hero .eyebrow{display:block;margin-bottom:28px}
.hero h1{font-family:'Fraunces',serif;font-weight:500;font-size:clamp(42px,7vw,88px);line-height:1.06;
  letter-spacing:-.015em;color:var(--white);max-width:960px;margin:0 auto}
.hero h1 .g{color:var(--gold-bright);font-style:italic}
.hero .subline{font-family:'Fraunces',serif;font-style:italic;font-size:clamp(18px,2vw,23px);color:var(--mist);
  margin:28px auto 0;max-width:660px;font-weight:400;line-height:1.6}
.hero-cta{display:flex;gap:14px;flex-wrap:wrap;justify-content:center;margin-top:38px}
.btn{display:inline-flex;align-items:center;gap:9px;font-weight:600;font-size:14.5px;padding:15px 30px;border-radius:11px;transition:.24s;cursor:pointer;border:1px solid transparent;letter-spacing:.02em}
.btn-gold{background:var(--gold);color:var(--bg)}
.btn-gold:hover{background:var(--gold-bright);transform:translateY(-2px)}
.btn-ghost{background:transparent;color:var(--ivory);border-color:var(--line2)}
.btn-ghost:hover{border-color:var(--gold);color:var(--gold-bright)}
.hero-orn{display:flex;justify-content:center;align-items:center;gap:18px;margin-top:46px}
.hero-orn .ln{width:72px;height:1px;background:linear-gradient(90deg,transparent,var(--gold))}
.hero-orn .ln.r{background:linear-gradient(90deg,var(--gold),transparent)}
.hero-orn .dm{color:var(--gold);font-size:13px}
.trust{display:flex;flex-wrap:wrap;justify-content:center;gap:10px;margin-top:44px}
.trust .tc{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--mist);border:1px solid var(--line);border-radius:22px;padding:8px 15px;background:var(--panel);letter-spacing:.02em}
.trust .tc b{color:var(--gold-bright);font-weight:500}

/* PULL QUOTE */
.pullquote{position:relative;z-index:2;padding:56px 0 30px}
.pq-box{max-width:840px;margin:0 auto;text-align:center;padding:0 20px}
.pq-box .qmark{font-family:'Fraunces',serif;font-size:64px;color:var(--gold-deep);line-height:.5;display:block;margin-bottom:10px}
.pq-box p{font-family:'Fraunces',serif;font-style:italic;font-size:clamp(19px,2.3vw,27px);color:var(--ivory);line-height:1.55;font-weight:400}
.pq-box p b{color:var(--gold-bright);font-style:normal;font-weight:600}

/* SECTION */
section{position:relative;z-index:2}
.sec-head{margin:118px 0 52px;max-width:740px}
.sec-head h2{font-family:'Fraunces',serif;font-weight:500;font-size:clamp(32px,4.6vw,54px);letter-spacing:-.01em;color:var(--white);margin-top:16px;line-height:1.1}
.sec-head h2 .g{color:var(--gold-bright);font-style:italic}
.sec-head p{color:var(--mist);margin-top:18px;font-size:17px;font-weight:300;line-height:1.75;max-width:660px}

/* MODEL CARDS */
.models{display:flex;flex-direction:column}
.model{position:relative;padding:50px 0;border-top:1px solid var(--line);transition:.3s}
.model:last-child{border-bottom:1px solid var(--line)}
.model:hover{background:linear-gradient(90deg,rgba(201,161,94,.03),transparent 60%)}
.model-top{display:grid;grid-template-columns:92px 1fr 210px;gap:34px;align-items:start}
.model .rn{font-family:'Fraunces',serif;font-weight:500;font-size:14px;color:var(--gold-deep)}
.model .num{font-family:'Fraunces',serif;font-weight:600;font-size:54px;color:var(--gold-deep);line-height:1;margin-top:4px}
.model h3{font-family:'Fraunces',serif;font-weight:600;font-size:29px;color:var(--white);line-height:1.15}
.model .subtitle{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--sage);letter-spacing:.06em;margin:9px 0 18px}
.model .feat{font-size:15.5px;color:var(--mist);font-weight:300;line-height:1.72;margin-bottom:20px}
.model .feat b{color:var(--ivory);font-weight:500}
.model .tags{list-style:none;display:flex;flex-wrap:wrap;gap:8px}
.model .tags li{font-family:'JetBrains Mono',monospace;font-size:10.5px;color:var(--ivory);border:1px solid var(--line2);border-radius:20px;padding:5px 13px;background:var(--panel)}
.model .price-box{text-align:right;padding-top:4px}
.model .price-box .pl{font-family:'JetBrains Mono',monospace;font-size:9.5px;letter-spacing:.16em;color:var(--gold);text-transform:uppercase;margin-bottom:10px}
.model .price-box .pv{font-family:'Fraunces',serif;font-weight:600;font-size:24px;color:var(--white);line-height:1.25}
.model .price-box .pu{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--mist);margin-top:5px}
.model.crown .price-box .pv{color:var(--gold-bright)}

/* BEFORE / AFTER */
.impact-note{font-family:'JetBrains Mono',monospace;font-size:11.5px;color:var(--mist);letter-spacing:.02em;
  border:1px solid var(--line);border-radius:12px;padding:15px 20px;margin-bottom:30px;line-height:1.8}
.impact-grid{display:grid;grid-template-columns:1fr auto 1fr;gap:0;align-items:stretch}
.imp-col{background:var(--panel);border:1px solid var(--line);border-radius:18px;padding:36px 34px}
.imp-col.before{border-color:var(--line2)}
.imp-col.after{border-color:var(--gold-deep);background:linear-gradient(160deg,rgba(201,161,94,.07),var(--panel))}
.imp-col .ih{font-family:'JetBrains Mono',monospace;font-size:11px;letter-spacing:.18em;text-transform:uppercase;margin-bottom:6px}
.imp-col.before .ih{color:var(--mist)}
.imp-col.after .ih{color:var(--gold)}
.imp-col .isub{font-family:'Fraunces',serif;font-weight:600;font-size:23px;color:var(--white);margin-bottom:24px}
.imp-row{display:flex;justify-content:space-between;align-items:baseline;gap:16px;padding:13px 0;border-top:1px solid var(--line)}
.imp-row:first-of-type{border-top:none}
.imp-row .il{font-size:13.5px;color:var(--mist);font-weight:300;max-width:58%}
.imp-row .iv{font-family:'Fraunces',serif;font-weight:600;font-size:19px;color:var(--ivory);text-align:right}
.imp-col.after .iv{color:var(--gold-bright)}
.impact-arrow{display:flex;align-items:center;justify-content:center;padding:0 18px}
.impact-arrow .aw{width:46px;height:46px;border-radius:50%;border:1px solid var(--gold-deep);display:flex;align-items:center;justify-content:center;color:var(--gold);font-size:19px;background:var(--bg2)}

/* LEAD BAND */
.lead-band{display:grid;grid-template-columns:1fr 1fr 1fr;gap:1px;background:var(--line);border:1px solid var(--line);border-radius:18px;overflow:hidden}
.lead-item{background:var(--panel);padding:34px 30px}
.lead-item .li-n{font-family:'Fraunces',serif;font-weight:600;font-size:34px;color:var(--gold-bright)}
.lead-item .li-t{font-family:'Be Vietnam Pro';font-weight:600;font-size:16px;color:var(--white);margin:10px 0 8px}
.lead-item .li-d{font-size:13.5px;color:var(--mist);font-weight:300;line-height:1.6}

/* ARCHITECTURE */
.arch2{background:var(--panel);border:1px solid var(--line);border-radius:22px;padding:56px 50px;text-align:center;position:relative;overflow:hidden}
.arch2::before{content:"";position:absolute;top:-40%;left:50%;transform:translateX(-50%);width:600px;height:600px;border-radius:50%;background:radial-gradient(circle,rgba(201,161,94,.08),transparent 70%)}
.arch2 .ab{display:inline-block;font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--gold);border:1px solid var(--gold-deep);border-radius:30px;padding:9px 22px;letter-spacing:.12em;position:relative}
.arch2 h3{font-family:'Fraunces',serif;font-weight:500;font-size:clamp(26px,3.4vw,40px);color:var(--white);margin:24px auto 16px;max-width:680px;line-height:1.22;position:relative}
.arch2 h3 .g{color:var(--gold-bright);font-style:italic}
.arch2 p{color:var(--mist);max-width:600px;margin:0 auto;font-size:16px;font-weight:300;position:relative;line-height:1.75}

/* PRICING */
.market-table{border:1px solid var(--line);border-radius:16px;overflow:hidden;margin-bottom:24px}
.mt-row{display:grid;grid-template-columns:1fr 210px;padding:16px 26px;border-bottom:1px solid var(--line);align-items:center}
.mt-row:last-child{border-bottom:none}
.mt-row.head{background:var(--panel2)}
.mt-row .mn{font-size:14.5px;color:var(--ivory);font-weight:400}
.mt-row.head .mn{font-family:'JetBrains Mono',monospace;font-size:10.5px;letter-spacing:.14em;color:var(--mist);text-transform:uppercase}
.mt-row .mv{font-family:'JetBrains Mono',monospace;font-size:14px;color:var(--mist);text-align:right}
.mt-row.total{background:var(--panel2)}
.mt-row.total .mn{font-weight:600;color:var(--white)}
.mt-row.total .mv{color:var(--gold-bright);font-weight:500;font-size:16px}

.offer-band{background:linear-gradient(155deg,var(--panel2),var(--bg2));border:1px solid var(--gold-deep);border-radius:22px;padding:48px 44px;margin-top:24px;position:relative;overflow:hidden}
.offer-band::before{content:"";position:absolute;top:-30%;right:-10%;width:400px;height:400px;border-radius:50%;background:radial-gradient(circle,rgba(201,161,94,.13),transparent 70%)}
.offer-top{display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:24px;position:relative}
.offer-label{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--gold);letter-spacing:.16em;text-transform:uppercase}
.offer-title{font-family:'Fraunces',serif;font-weight:600;font-size:26px;color:var(--white);margin-top:12px;max-width:440px;line-height:1.28}
.offer-price{text-align:right}
.offer-price .op-strike{font-family:'JetBrains Mono',monospace;font-size:13px;color:var(--mist);text-decoration:line-through;opacity:.7}
.offer-price .op-val{font-family:'Fraunces',serif;font-weight:600;font-size:46px;color:var(--gold-bright);line-height:1.15;margin-top:6px}
.offer-price .op-unit{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--mist);margin-top:6px}
.offer-desc{font-size:15px;color:var(--mist);font-weight:300;max-width:660px;margin-top:22px;line-height:1.7;position:relative}
.offer-desc b{color:var(--ivory);font-weight:500}
.excl-box{margin-top:24px;border-top:1px dashed var(--line2);padding-top:20px;font-family:'JetBrains Mono',monospace;font-size:11.5px;color:var(--mist);line-height:2;position:relative}
.excl-box .ex-lbl{color:var(--gold)}

/* PAY + TERMS */
.pay{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin:34px 0 22px}
.pstep{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px 18px;text-align:center}
.pstep .pp{font-family:'Fraunces',serif;font-size:32px;font-weight:600;color:var(--gold-bright)}
.pstep .pl{font-size:12.5px;color:var(--mist);margin-top:6px;font-weight:300;line-height:1.5}
.terms{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:8px}
.term{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:24px 26px}
.term h4{margin:0 0 12px;font-size:16px;font-weight:600;color:var(--white);display:flex;align-items:center;gap:10px}
.term h4 .td{width:9px;height:9px;border-radius:3px;background:var(--gold)}
.term ul{list-style:none}
.term li{position:relative;padding-left:18px;font-size:13.5px;color:var(--mist);margin-bottom:9px;font-weight:300;line-height:1.6}
.term li::before{content:"—";position:absolute;left:0;color:var(--gold-deep)}
.term li b{color:var(--ivory);font-weight:500}

/* ROADMAP */
.road{border-top:1px solid var(--line)}
.ph{display:grid;grid-template-columns:200px 1fr;gap:32px;padding:32px 0;border-bottom:1px solid var(--line)}
.ph .when .pl{font-family:'JetBrains Mono',monospace;font-size:11px;letter-spacing:.14em;color:var(--gold)}
.ph .when .pdd{font-family:'Fraunces',serif;font-weight:600;font-size:25px;color:var(--white);margin-top:8px}
.ph .what h4{font-family:'Be Vietnam Pro';font-weight:600;color:var(--white);font-size:20px;margin-bottom:8px}
.ph .what p{font-size:14.5px;color:var(--mist);font-weight:300;line-height:1.6}

/* DEMO CALLOUT */
.demo-band{background:linear-gradient(150deg,var(--panel2),var(--bg2));border:1px solid var(--line2);border-radius:22px;padding:46px 44px;display:flex;justify-content:space-between;align-items:center;gap:32px;flex-wrap:wrap;position:relative;overflow:hidden}
.demo-band::before{content:"";position:absolute;top:-40%;left:-8%;width:380px;height:380px;border-radius:50%;background:radial-gradient(circle,rgba(157,179,155,.08),transparent 70%)}
.demo-band .dtxt{position:relative;max-width:560px}
.demo-band .dtxt .eyebrow{margin-bottom:12px;color:var(--sage)}
.demo-band .dtxt h3{font-family:'Fraunces',serif;font-weight:600;font-size:28px;color:var(--white);line-height:1.2;margin-bottom:12px}
.demo-band .dtxt p{color:var(--mist);font-size:15px;font-weight:300;line-height:1.7}

/* SCOPE BUILDER (dark luxury) */
.presets{display:flex;flex-wrap:wrap;align-items:center;gap:10px;margin-bottom:26px}
.presets-lb{font-size:13px;color:var(--mist);font-weight:400}
.preset{font:inherit;font-weight:500;font-size:13.5px;border:1px solid var(--line2);background:var(--panel);color:var(--ivory);border-radius:10px;padding:10px 16px;cursor:pointer;transition:.18s}
.preset:hover{transform:translateY(-1px);border-color:var(--gold)}
.preset[data-preset="all"]{background:var(--gold);color:var(--bg);border-color:transparent;font-weight:600}
.scope{display:grid;gap:16px;max-width:960px}
.grp{background:var(--panel);border:1px solid var(--line);border-top:2px solid var(--gc,var(--gold-deep));border-radius:16px;padding:8px}
.grp-head{display:flex;align-items:flex-start;gap:12px;padding:15px;border-radius:12px;cursor:pointer}
.grp-head.static{cursor:default}
.grp-head:hover:not(.static){background:var(--bg2)}
.grp-meta{flex:1}
.grp-meta b{display:block;font-size:16px;font-weight:600;color:var(--white);line-height:1.35}
.grp-meta span{display:block;font-size:13px;color:var(--mist);margin-top:3px;font-weight:300}
.grp-count{flex:0 0 auto;font-family:'JetBrains Mono',monospace;font-size:11px;font-weight:500;color:var(--gold);background:var(--bg2);border:1px solid var(--line);border-radius:20px;padding:4px 11px;margin-top:2px;white-space:nowrap}
.picks{display:grid;grid-template-columns:1fr 1fr;gap:8px;padding:0 8px 8px}
@media(max-width:680px){.picks{grid-template-columns:1fr}}
.pick{display:flex;gap:11px;align-items:flex-start;padding:13px 14px;border:1px solid var(--line);border-radius:11px;background:var(--bg2);cursor:pointer;transition:.16s}
.pick:hover{border-color:var(--gold-deep)}
.pick:has(input:checked){border-color:var(--gold);background:linear-gradient(160deg,rgba(201,161,94,.08),var(--bg2))}
.pick .meta b{display:block;font-size:14px;font-weight:500;color:var(--ivory);line-height:1.35}
.pick .meta span{display:block;font-size:12.5px;color:var(--mist);margin-top:2px;font-weight:300}
.master,.pick input,.grp-head input{position:absolute;opacity:0;width:0;height:0;pointer-events:none}
.box{position:relative;flex:0 0 21px;width:21px;height:21px;border-radius:6px;border:2px solid var(--line2);background:var(--bg);display:grid;place-items:center;margin-top:1px;transition:.16s}
.box svg{width:12px;height:12px;fill:none;stroke:var(--bg);stroke-width:3.2;stroke-linecap:round;stroke-linejoin:round;opacity:0;transition:.16s}
input:checked + .box{background:var(--gold);border-color:transparent}
input:checked + .box svg{opacity:1}
.master:indeterminate + .box{background:var(--gold-deep);border-color:transparent}
.master:indeterminate + .box::after{content:"";position:absolute;width:10px;height:3px;border-radius:2px;background:var(--bg)}
.pick.radio .box{border-radius:50%}
.fld{padding:6px 16px 16px}
.flbl{display:block;font-size:13.5px;font-weight:500;color:var(--ivory);margin:6px 0 7px}
.scope input[type=text],.scope input[type=email],.scope input[type=tel],.scope textarea,.scope select{width:100%;font:inherit;font-size:14.5px;color:var(--ivory);background:var(--bg);border:1px solid var(--line2);border-radius:10px;padding:12px 14px;transition:.16s}
.scope textarea{min-height:84px;resize:vertical;line-height:1.6}
.scope input:focus,.scope textarea:focus,.scope select:focus{outline:none;border-color:var(--gold)}
.scope select option{background:var(--panel2);color:var(--ivory)}
.frow{display:grid;grid-template-columns:1fr 1fr;gap:12px;padding:0 16px 16px}
@media(max-width:600px){.frow{grid-template-columns:1fr}}
.summary{max-width:960px;margin:18px 0 0;background:var(--panel2);border:1px solid var(--gold-deep);border-radius:18px;padding:24px 26px}
.summary .scnt{font-size:15px;color:var(--ivory);margin-bottom:10px}
.summary .scnt b{font-family:'Fraunces',serif;font-size:24px;color:var(--gold-bright)}
#sumList{list-style:none;margin:0 0 16px;padding:0;display:flex;flex-wrap:wrap;gap:6px;max-height:96px;overflow:auto}
#sumList li{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--ivory);background:var(--bg);border:1px solid var(--line2);border-radius:8px;padding:5px 10px}
#sumList li.empty{border:none;background:none;color:var(--mist);padding-left:0;font-family:'Be Vietnam Pro'}
.summary .actions{display:flex;flex-wrap:wrap;gap:10px}
.summary .btn{padding:13px 22px;font-size:14px}
.contact-chips{display:flex;flex-wrap:wrap;align-items:center;gap:10px;margin-top:16px;padding-top:16px;border-top:1px solid var(--line);font-size:13.5px}
.contact-chips a{display:inline-flex;align-items:center;gap:7px;color:var(--ivory);font-weight:500;border:1px solid var(--line2);border-radius:9px;padding:8px 13px;background:var(--bg)}
.contact-chips a:hover{border-color:var(--gold)}
.contact-chips .who{margin-left:auto;color:var(--mist);font-weight:300}
.sendmsg{display:none;margin-top:12px;font-size:13.5px;line-height:1.55;border-radius:10px;padding:12px 15px}
.sendmsg.ok{display:block;background:rgba(157,179,155,.12);color:var(--sage);border:1px solid rgba(157,179,155,.3)}
.sendmsg.info{display:block;background:rgba(201,161,94,.10);color:var(--gold-bright);border:1px solid rgba(201,161,94,.28)}
@media(max-width:600px){.contact-chips .who{margin-left:0;width:100%}}

/* CTA */
.cta{background:linear-gradient(160deg,var(--panel2),var(--bg2));border:1px solid var(--gold-deep);border-radius:26px;padding:70px 50px;text-align:center;margin:44px 0 90px;position:relative;overflow:hidden}
.cta::before{content:"";position:absolute;inset:0;background:radial-gradient(ellipse 50% 60% at 50% 0%,rgba(201,161,94,.12),transparent 70%);pointer-events:none}
.cta h2{font-family:'Fraunces',serif;font-weight:500;font-size:clamp(32px,5vw,54px);color:var(--white);letter-spacing:-.01em;margin-top:18px;position:relative;line-height:1.12}
.cta h2 .g{color:var(--gold-bright);font-style:italic}
.cta p{color:var(--mist);margin:20px auto 34px;max-width:560px;font-size:16px;font-weight:300;position:relative}
.cta .cta-actions{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;position:relative}

footer{border-top:1px solid var(--line);padding:40px 0;position:relative;z-index:2}
.foot{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:16px}
.foot-brand{display:flex;align-items:center;gap:12px}
.foot-brand .fseal{width:34px;height:34px;border-radius:50%;border:1px solid var(--gold-deep);display:grid;place-items:center;font-family:'Fraunces',serif;font-size:13px;color:var(--gold)}
.foot-brand b{color:var(--white);font-weight:600;font-size:15px}
.foot-brand small{display:block;color:var(--mist);font-size:12px;font-weight:300}
.foot-meta{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--mist);letter-spacing:.04em;text-align:right;line-height:1.9}
.foot-meta b{color:var(--gold)}

.reveal{opacity:0;transform:translateY(26px);transition:opacity .8s cubic-bezier(.2,.7,.2,1),transform .8s cubic-bezier(.2,.7,.2,1)}
.reveal.in{opacity:1;transform:none}

@media(max-width:920px){
  .model-top{grid-template-columns:1fr}
  .model .price-box{text-align:left;margin-top:6px}
  .impact-grid{grid-template-columns:1fr}
  .impact-arrow{padding:16px 0}
  .impact-arrow .aw{transform:rotate(90deg)}
  .lead-band{grid-template-columns:1fr}
  .mt-row{grid-template-columns:1fr}
  .mt-row .mv{text-align:left;margin-top:6px}
  .offer-top{flex-direction:column}
  .offer-price{text-align:left}
  .pay{grid-template-columns:1fr 1fr}
  .terms{grid-template-columns:1fr}
  .ph{grid-template-columns:1fr;gap:10px}
  .foot-meta{text-align:left}
}
@media(prefers-reduced-motion:reduce){.reveal{opacity:1;transform:none;transition:none}}
@media print{.glow,.grain{display:none}}
</style>
</head>
<body>
<div class="glow"></div>
<div class="grain"></div>

<header>
  <div class="wrap nav">
    <a class="brand" href="#top">
      <span class="seal">H</span>
      <span class="bt">HCD Holdings<small>ARCHITECTURAL · INTERIOR INTELLIGENCE</small></span>
    </a>
    <nav class="nav-links">
      <a href="#systems">Hệ thống</a>
      <a href="#impact">Hiệu quả</a>
      <a href="#ecosystem">Kiến trúc</a>
      <a href="#pricing">Đầu tư</a>
      <a href="#roadmap">Lộ trình</a>
      <a href="#contact">Chọn hạng mục</a>
    </nav>
    <a class="nav-cta" href="#contact">Trao đổi phương án</a>
  </div>
</header>

<!-- HERO -->
<section class="hero" id="top">
  <div class="wrap">
    <span class="eyebrow">Đỉnh cao trí tuệ trong thiết kế &amp; sản xuất nội thất</span>
    <h1>Từ bản vẽ đến<br>lệnh cắt xưởng, trên <span class="g">một hệ trí tuệ</span>.</h1>
    <p class="subline">Bảy hệ thống trí tuệ nhân tạo hợp nhất thành một hệ sinh thái duy nhất cho HCD Holdings — vận hành trọn chuỗi giá trị từ thiết kế nội thất gỗ óc chó, đến sản xuất CNC, quản trị doanh nghiệp và thương mại hóa toàn ngành.</p>
    <div class="hero-cta">
      <a class="btn btn-gold" href="#systems">Khám phá 7 hệ thống →</a>
      <a class="btn btn-ghost" href="/app">Trải nghiệm nền tảng demo</a>
    </div>
    <div class="hero-orn"><span class="ln"></span><span class="dm">✦</span><span class="ln r"></span></div>
    <div class="trust">
      <span class="tc"><b>10+ năm</b> dẫn đầu nội thất gỗ óc chó</span>
      <span class="tc">Xưởng sản xuất <b>3.000m²</b></span>
      <span class="tc">Thương hiệu <b>#1</b> biệt thự Vinhomes · Ecopark</span>
      <span class="tc">Phong cách <b>Modern · Tân cổ điển · Luxury</b></span>
    </div>
  </div>
</section>

<!-- PULL QUOTE -->
<section class="pullquote">
  <div class="wrap">
    <div class="pq-box reveal">
      <span class="qmark">"</span>
      <p>Khoản đầu tư này không mua một phần mềm — mà kết tinh <b>hàng chục năm kinh nghiệm</b> của người thợ óc chó, kiến trúc sư và nhà quản trị HCD vào một hệ sinh thái trí tuệ nhân tạo, để mỗi công trình đều mang chuẩn mực cao nhất.</p>
    </div>
  </div>
</section>

<!-- SYSTEMS -->
<section id="systems">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Bảy hệ thống cốt lõi</div>
      <h2>Mỗi hệ thống là một <span class="g">chuyên gia số</span>.<br>Cộng lại là một đế chế công nghệ.</h2>
      <p>Từ quy hoạch không gian đến lệnh cắt CNC trên sàn xưởng, từ quản trị nội bộ đến thương mại hóa toàn ngành — bảy hệ thống vận hành trên cùng một trí tuệ, cùng một nguồn dữ liệu của HCD.</p>
    </div>

    <div class="models reveal">

      <div class="model">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG I</div><div class="num">01</div></div>
          <div>
            <h3>Design Studio AI</h3>
            <div class="subtitle">Thiết kế kiến trúc &amp; không gian nội thất</div>
            <p class="feat">Từ mặt bằng thô đến phương án hoàn chỉnh. Đọc dữ liệu công trình, sinh hàng loạt phương án bố cục &amp; phong cách (modern, tân cổ điển, luxury), giả lập ánh sáng và tỷ lệ không gian <b>ở đẳng cấp tương đương kiến trúc sư nội thất 20 năm kinh nghiệm</b> — kiến trúc sư thật điều hành &amp; ký duyệt.</p>
            <ul class="tags"><li>Bố cục tự động</li><li>Đa phong cách</li><li>Giả lập ánh sáng</li><li>KTS ký duyệt</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">800tr – 1,2 tỷ</div>
            <div class="pu">VNĐ</div>
          </div>
        </div>
      </div>

      <div class="model">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG II</div><div class="num">02</div></div>
          <div>
            <h3>Architectural Builder</h3>
            <div class="subtitle">Kết cấu · Điện – Nước · Hồ sơ kỹ thuật</div>
            <p class="feat">Lõi dựng hình và xử lý xung đột vật lý. Tự động lên lưới kết cấu, đi luồng công năng tối ưu và hợp phong thủy. <b>Xử lý triệt để va chạm kỹ thuật Điện – Nước – Kết cấu</b> ngay trên môi trường BIM, cùng bộ shop drawing thi công chuẩn xác — trước khi ra công trường.</p>
            <ul class="tags"><li>Lưới kết cấu tự động</li><li>Clash Detection MEP</li><li>Shop drawing</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">1,0 – 1,6 tỷ</div>
            <div class="pu">VNĐ</div>
          </div>
        </div>
      </div>

      <div class="model crown">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG III</div><div class="num">03</div></div>
          <div>
            <h3>Interior &amp; CNC Detailer</h3>
            <div class="subtitle">Nội thất óc chó &amp; sản xuất thực chiến · phân hệ chủ lực</div>
            <p class="feat">Từ bản vẽ 3D thẩm mỹ thẳng đến lệnh cắt máy CNC tại xưởng 3.000m². Render nội thất gỗ óc chó độ thực cao, map vân gỗ thật 1:1, <b>tự động bóc tách BOQ chính xác tới 98%</b>, tối ưu xếp ván (nesting) và xuất lệnh cắt cho xưởng mộc — giảm tối đa hao hụt gỗ quý.</p>
            <ul class="tags"><li>Render vân óc chó 1:1</li><li>BOQ 98% chính xác</li><li>Nesting tối ưu</li><li>Lệnh cắt CNC</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">1,5 – 2,2 tỷ</div>
            <div class="pu">VNĐ · phân hệ lợi nhuận cao nhất</div>
          </div>
        </div>
      </div>

      <div class="model">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG IV</div><div class="num">04</div></div>
          <div>
            <h3>HCD Automation OS</h3>
            <div class="subtitle">Hệ điều hành &amp; cố vấn nghiệp vụ</div>
            <p class="feat">Kiến trúc "dùng đến đâu, bật đến đó" với <b>mạng lưới 16 chuyên gia AI</b> đóng vai cố vấn cấp cao: Agent Pháp chế soát rủi ro hợp đồng &amp; cập nhật luật xây dựng; Agent Nhân sự đánh giá năng lực &amp; đề xuất giữ chân nhân tài; Virtual CEO báo cáo sức khỏe doanh nghiệp real-time.</p>
            <ul class="tags"><li>16 Agent cố vấn</li><li>Virtual CEO</li><li>CRM · KPI · OKR</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">800tr – 1,2 tỷ</div>
            <div class="pu">VNĐ</div>
          </div>
        </div>
      </div>

      <div class="model">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG V</div><div class="num">05</div></div>
          <div>
            <h3>Full-Stack ERP</h3>
            <div class="subtitle">Quản trị nguồn lực &amp; trợ lý đa nhiệm</div>
            <p class="feat">Trục xương sống dữ liệu, kiểm soát biên lợi nhuận gộp từng công trình. Liên thông trực tiếp từ bản vẽ xuống kho vật tư để tự xuất lệnh mua hàng &amp; điều phối sản xuất. Tích hợp <b>ERP Copilot</b>: Ban lãnh đạo chỉ cần gõ một câu hỏi, hệ thống tự kéo dữ liệu và vẽ biểu đồ tức thì.</p>
            <ul class="tags"><li>Thiết kế → kho → xưởng</li><li>ERP Copilot</li><li>Kế toán chuẩn VAS</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">1,0 – 1,5 tỷ</div>
            <div class="pu">VNĐ</div>
          </div>
        </div>
      </div>

      <div class="model">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG VI</div><div class="num">06</div></div>
          <div>
            <h3>B2B SaaS &amp; Sàn thương mại</h3>
            <div class="subtitle">Cỗ máy tạo dòng tiền định kỳ</div>
            <p class="feat">Nền tảng thương mại hóa phần mềm và hệ sinh thái vật liệu nội thất. Thu phí thuê bao từ các đơn vị thiết kế khác; mở <b>Suppliers Hub</b> cho các thương hiệu gỗ &amp; vật liệu cao cấp tham gia; mạng lưới cộng tác viên &amp; hoa hồng khi vật liệu được chọn vào bản vẽ.</p>
            <ul class="tags"><li>Subscription B2B</li><li>Suppliers Hub</li><li>Affiliate hoa hồng</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">1,0 – 1,6 tỷ</div>
            <div class="pu">VNĐ</div>
          </div>
        </div>
      </div>

      <div class="model">
        <div class="model-top">
          <div><div class="rn">HỆ THỐNG VII</div><div class="num">07</div></div>
          <div>
            <h3>Luxury Landing &amp; AI Receptionist</h3>
            <div class="subtitle">Trải nghiệm điểm chạm đầu cuối</div>
            <p class="feat">Mặt tiền kỹ thuật số đẳng cấp, tối giản và sang trọng đúng tinh thần HCD. <b>Agent Lễ tân AI</b> được huấn luyện toàn bộ kiến thức hệ sinh thái, tiếp đón khách 24/7 bằng ngôn ngữ thương hiệu, phân loại nhu cầu và tự động đẩy lead vào CRM.</p>
            <ul class="tags"><li>Dark mode cao cấp</li><li>Lễ tân AI 24/7</li><li>Lead → CRM tự động</li></ul>
          </div>
          <div class="price-box">
            <div class="pl">Giá trị thị trường</div>
            <div class="pv">250 – 400tr</div>
            <div class="pu">VNĐ</div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- IMPACT -->
<section id="impact">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Đo lường thực tế · quy mô ~100 nhân sự</div>
      <h2>Cùng một đội ngũ. <span class="g">Sức mạnh khác biệt.</span></h2>
      <p>Ước tính hiệu năng khi áp dụng hệ sinh thái AI cho một tổ chức thiết kế – thi công – sản xuất nội thất quy mô ~100 nhân sự, dựa trên benchmark năng suất ngành và hiệu năng triển khai AI thực tế.</p>
    </div>

    <div class="impact-note reveal">// Số liệu là ước tính có căn cứ ngành, dùng để định hướng ROI — không phải cam kết hợp đồng.</div>

    <div class="impact-grid reveal">
      <div class="imp-col before">
        <div class="ih">Trước khi có hệ sinh thái</div>
        <div class="isub">Vận hành truyền thống</div>
        <div class="imp-row"><span class="il">Thời gian ra bộ hồ sơ + BOQ / dự án</span><span class="iv">10–15 ngày</span></div>
        <div class="imp-row"><span class="il">Số dự án xử lý đồng thời / quý</span><span class="iv">~8–10</span></div>
        <div class="imp-row"><span class="il">Hao hụt gỗ &amp; vật tư trung bình</span><span class="iv">8–12%</span></div>
        <div class="imp-row"><span class="il">Thời gian họp &amp; tổng hợp báo cáo</span><span class="iv">~20% quỹ giờ</span></div>
        <div class="imp-row"><span class="il">Chi phí quản trị công nghệ / năm</span><span class="iv">~1,28 tỷ</span></div>
        <div class="imp-row"><span class="il">Phát hiện xung đột kỹ thuật</span><span class="iv">Tại công trường</span></div>
      </div>
      <div class="impact-arrow"><div class="aw">→</div></div>
      <div class="imp-col after">
        <div class="ih">Sau khi có hệ sinh thái</div>
        <div class="isub">Vận hành trên nền tảng AI</div>
        <div class="imp-row"><span class="il">Thời gian ra bộ hồ sơ + BOQ / dự án</span><span class="iv">2–3 ngày</span></div>
        <div class="imp-row"><span class="il">Số dự án xử lý đồng thời / quý</span><span class="iv">~20–24</span></div>
        <div class="imp-row"><span class="il">Hao hụt gỗ &amp; vật tư trung bình</span><span class="iv">3–5%</span></div>
        <div class="imp-row"><span class="il">Thời gian họp &amp; tổng hợp báo cáo</span><span class="iv">~6% quỹ giờ</span></div>
        <div class="imp-row"><span class="il">Chi phí quản trị công nghệ / năm</span><span class="iv">~558tr</span></div>
        <div class="imp-row"><span class="il">Phát hiện xung đột kỹ thuật</span><span class="iv">Real-time trên BIM</span></div>
      </div>
    </div>
  </div>
</section>

<!-- MARKET OPPORTUNITY -->
<section id="opportunity">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Cơ hội thị trường</div>
      <h2>Đi đầu một xu thế, <span class="g">không đi sau ai cả</span>.</h2>
      <p>Ngành thiết kế – thi công nội thất cao cấp Việt Nam đang ở điểm khởi đầu của làn sóng AI. Hệ sinh thái này đặt HCD vào vị trí dẫn đầu cuộc chuyển đổi đó.</p>
    </div>
    <div class="lead-band reveal">
      <div class="lead-item">
        <div class="li-n">01</div>
        <div class="li-t">Người tiên phong ngành</div>
        <div class="li-d">Trong khi phần lớn đối thủ vẫn thiết kế &amp; bóc tách thủ công, HCD sở hữu hệ sinh thái AI toàn trình đầu tiên trong ngành nội thất gỗ óc chó cao cấp tại Việt Nam.</div>
      </div>
      <div class="lead-item">
        <div class="li-n">02</div>
        <div class="li-t">Tài sản số sinh lời</div>
        <div class="li-d">Không dừng ở công cụ nội bộ — Hệ thống VI biến nền tảng thành trung tâm sinh lời (Profit Center) qua thuê bao SaaS và hoa hồng chuỗi cung ứng vật liệu.</div>
      </div>
      <div class="lead-item">
        <div class="li-n">03</div>
        <div class="li-t">Doanh thu định kỳ</div>
        <div class="li-d">Khi hệ sinh thái vận hành đủ quy mô — thuê bao SaaS, hoa hồng vật liệu và dịch vụ thiết kế tự động hóa — tiềm năng dòng doanh thu định kỳ mở rộng liên tục theo thời gian.</div>
      </div>
    </div>
  </div>
</section>

<!-- ECOSYSTEM -->
<section id="ecosystem">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Kiến trúc hệ sinh thái</div>
      <h2>Một lõi trí tuệ. <span class="g">Bảy cánh tay chuyên môn.</span></h2>
      <p>Bảy hệ thống không vận hành rời rạc — chúng chia sẻ chung một nguồn dữ liệu và một lớp trí tuệ điều phối, để mọi thông tin chảy liền mạch từ thiết kế đến sản xuất, từ vận hành đến thương mại hóa.</p>
    </div>
    <div class="arch2 reveal">
      <span class="ab">// MỘT HỆ SINH THÁI · BẢY CHUYÊN GIA SỐ · MỘT NGUỒN DỮ LIỆU</span>
      <h3>Dữ liệu từ Hệ thống I chảy thẳng đến Hệ thống VII — <span class="g">không ốc đảo, không nhập liệu lặp</span>.</h3>
      <p>Từ phương án thiết kế đến lệnh cắt xưởng, từ báo cáo tài chính đến hoa hồng vật liệu — mọi cấu phần đứng trên cùng một nền tảng trí tuệ duy nhất, mang thương hiệu HCD và được thiết kế để mở rộng không giới hạn.</p>
    </div>
  </div>
</section>

<!-- PRICING -->
<section id="pricing">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Đầu tư · tham khảo thị trường VN 2026</div>
      <h2>Giá trị thị trường. <span class="g">Ưu đãi đối tác chiến lược.</span></h2>
      <p>Bảng dưới là giá trị tham khảo nếu triển khai riêng lẻ từng hệ thống theo mặt bằng thị trường. HCD Holdings được dành mức ưu đãi đặc biệt cho vai trò đối tác đồng hành giai đoạn đầu.</p>
    </div>

    <div class="market-table reveal">
      <div class="mt-row head"><div class="mn">Hệ thống</div><div class="mv">Giá trị thị trường</div></div>
      <div class="mt-row"><div class="mn">I · Design Studio AI</div><div class="mv">800tr – 1,2 tỷ</div></div>
      <div class="mt-row"><div class="mn">II · Architectural Builder</div><div class="mv">1,0 – 1,6 tỷ</div></div>
      <div class="mt-row"><div class="mn">III · Interior &amp; CNC Detailer</div><div class="mv">1,5 – 2,2 tỷ</div></div>
      <div class="mt-row"><div class="mn">IV · HCD Automation OS</div><div class="mv">800tr – 1,2 tỷ</div></div>
      <div class="mt-row"><div class="mn">V · Full-Stack ERP</div><div class="mv">1,0 – 1,5 tỷ</div></div>
      <div class="mt-row"><div class="mn">VI · B2B SaaS &amp; Sàn thương mại</div><div class="mv">1,0 – 1,6 tỷ</div></div>
      <div class="mt-row"><div class="mn">VII · Luxury Landing &amp; AI Receptionist</div><div class="mv">250 – 400tr</div></div>
      <div class="mt-row total"><div class="mn">Tổng giá trị bóc tách riêng lẻ</div><div class="mv">~6,35 – 9,7 tỷ</div></div>
    </div>

    <div class="offer-band reveal">
      <div class="offer-top">
        <div>
          <div class="offer-label">// Gói triển khai đồng bộ — đối tác đồng hành</div>
          <div class="offer-title">Toàn bộ 7 hệ thống, trên một lõi dữ liệu duy nhất.</div>
        </div>
        <div class="offer-price">
          <div class="op-strike">Giá trị thị trường 6,35 – 9,7 tỷ</div>
          <div class="op-val">2,6 – 3,4 tỷ</div>
          <div class="op-unit">VNĐ · TRỌN BỘ HỆ SINH THÁI</div>
        </div>
      </div>
      <p class="offer-desc">Việc xây dựng liền mạch trên cùng một lõi dữ liệu giúp tiết kiệm tối đa chi phí tích hợp hệ thống — phần tiết kiệm này được chuyển thành ưu đãi cho đối tác chiến lược đồng hành giai đoạn đầu. <b>Thanh toán chia theo mốc bàn giao từng giai đoạn.</b></p>
      <div class="excl-box">
        <span class="ex-lbl">// CHƯA BAO GỒM (tính theo thực dùng):</span><br>
        — Hosting &amp; cloud server vận hành · GPU render 3D<br>
        — Phí token API các mô hình AI nền tảng<br>
        — Phí vận hành &amp; bảo trì năm: theo thoả thuận (mục bên dưới)
      </div>
    </div>

    <h3 style="font-family:'Fraunces',serif;font-weight:500;font-size:22px;color:var(--white);text-align:center;margin:52px 0 4px">Thanh toán theo mốc bàn giao</h3>
    <div class="pay reveal">
      <div class="pstep"><div class="pp">30%</div><div class="pl">Ký hợp đồng · đặt cọc</div></div>
      <div class="pstep"><div class="pp">30%</div><div class="pl">Hoàn thành MVP</div></div>
      <div class="pstep"><div class="pp">30%</div><div class="pl">Bàn giao đầy đủ tính năng</div></div>
      <div class="pstep"><div class="pp">10%</div><div class="pl">Sau bàn giao 45 ngày (bảo hành)</div></div>
    </div>

    <div class="terms reveal">
      <div class="term">
        <h4><span class="td"></span>Vận hành sau bàn giao</h4>
        <ul>
          <li><b>Quản trị vận hành:</b> 15.000.000đ/tháng (ký theo năm).</li>
          <li><b>Bảo trì &amp; nâng cấp AI</b> thông minh hơn theo thời gian: 5–10% giá trị hợp đồng/năm, tuỳ nhu cầu thực tế.</li>
        </ul>
      </div>
      <div class="term">
        <h4><span class="td"></span>Bảo hành 6 tháng</h4>
        <ul>
          <li>Lỗi mã nguồn hoặc lỗi ngắt kết nối: <b>khắc phục miễn phí</b>.</li>
          <li>Lỗi do thao tác phía HCD gây hỏng: ngoài phạm vi bảo hành; nếu cần xây lại tính phí theo thực tế.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ROADMAP -->
<section id="roadmap">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Lộ trình triển khai</div>
      <h2>Bảy giai đoạn. <span class="g">Giá trị từ ngày đầu.</span></h2>
      <p>Mỗi giai đoạn bàn giao một hệ thống chạy thật, tạo giá trị ngay — không chờ đến khi hoàn thiện toàn bộ mới sử dụng được.</p>
    </div>
    <div class="road reveal">
      <div class="ph">
        <div class="when"><div class="pl">GIAI ĐOẠN I–II</div><div class="pdd">Thiết kế &amp; Kỹ thuật</div></div>
        <div class="what"><h4>Design Studio AI + Architectural Builder</h4><p>Nền tảng dựng hình và xử lý kỹ thuật — xương sống của toàn hệ sinh thái thiết kế.</p></div>
      </div>
      <div class="ph">
        <div class="when"><div class="pl">GIAI ĐOẠN III</div><div class="pdd">Nội thất &amp; Sản xuất</div></div>
        <div class="what"><h4>Interior &amp; CNC Detailer</h4><p>Cấu phần tạo giá trị sản xuất rõ rệt nhất — từ bản vẽ óc chó đến lệnh cắt xưởng.</p></div>
      </div>
      <div class="ph">
        <div class="when"><div class="pl">GIAI ĐOẠN IV–V</div><div class="pdd">Vận hành &amp; Quản trị</div></div>
        <div class="what"><h4>Automation OS + Full-Stack ERP</h4><p>Mạng lưới cố vấn AI và trục xương sống dữ liệu doanh nghiệp.</p></div>
      </div>
      <div class="ph">
        <div class="when"><div class="pl">GIAI ĐOẠN VI–VII</div><div class="pdd">Thương mại hóa</div></div>
        <div class="what"><h4>B2B SaaS + Điểm chạm số</h4><p>Mở dòng doanh thu định kỳ và hoàn thiện trải nghiệm khách hàng đầu cuối.</p></div>
      </div>
    </div>
  </div>
</section>

<!-- DEMO CALLOUT -->
<section id="demo">
  <div class="wrap">
    <div class="demo-band reveal">
      <div class="dtxt">
        <div class="eyebrow">Bản demo tương tác đã sẵn sàng</div>
        <h3>Trải nghiệm hệ sinh thái trước khi ký.</h3>
        <p>Chúng tôi đã dựng sẵn bản demo chạy thật để HCD thao tác trực tiếp trên giao diện các hệ thống, cảm nhận luồng dữ liệu liền mạch và góp ý tính năng — trước khi chốt phạm vi triển khai cuối cùng.</p>
      </div>
      <a class="btn btn-gold" href="/app">Mở nền tảng demo →</a>
    </div>
  </div>
</section>

<!-- SCOPE BUILDER / CONTACT -->
<section id="contact">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="ornament"><span class="ln"></span><span class="dm">✦</span></div>
      <div class="eyebrow">Trao đổi &amp; chọn hạng mục</div>
      <h2>Tích chọn hạng mục HCD muốn — <span class="g">chúng tôi lên phương án &amp; báo giá.</span></h2>
      <p>Không cần rành công nghệ. Hãy tích vào ô những phần tập đoàn muốn tự động hoá, ghi thêm mong muốn nếu có, rồi bấm gửi. Đội ngũ sẽ đọc lựa chọn của bạn, dựng lại phương án phù hợp và báo giá chi tiết.</p>
    </div>

    <div class="presets reveal">
      <span class="presets-lb">Chưa biết bắt đầu từ đâu?</span>
      <button type="button" class="preset" data-preset="all">✦ Trọn bộ 7 hệ thống</button>
      <button type="button" class="preset" data-preset="lean">Gói tinh gọn — bắt đầu nhanh</button>
      <button type="button" class="preset" data-preset="clear">Bỏ chọn tất cả</button>
    </div>

    <form id="scopeForm" class="scope" onsubmit="return false;">

      <div class="grp reveal" data-key="p1" style="--gc:var(--gold)">
        <label class="grp-head">
          <input type="checkbox" class="master">
          <span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span>
          <span class="grp-meta"><b>Hệ thống I–II · Thiết kế &amp; Kỹ thuật (Design Studio + Builder)</b><span>Tự động dựng hồ sơ thiết kế, kết cấu &amp; MEP; kiến trúc sư điều hành &amp; ký duyệt.</span></span>
          <span class="grp-count">0/6</span>
        </label>
        <div class="picks">
          <label class="pick"><input type="checkbox" data-label="Bố cục & phương án không gian nội thất AI"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Bố cục &amp; phương án không gian AI</b><span>Sinh nhiều phương án bố cục &amp; phong cách.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Thiết kế kiến trúc đa loại hình"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Thiết kế kiến trúc đa loại hình</b><span>Nhà phố, biệt thự, chung cư, thương mại.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Kết cấu + Điện nước (MEP)"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Kết cấu + Điện nước (MEP)</b><span>Bản vẽ kết cấu, điện, cấp thoát nước, điều hoà.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Clash detection & xử lý xung đột trên BIM"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Clash detection trên BIM</b><span>Phát hiện va chạm kỹ thuật trước thi công.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Shop drawing & hồ sơ thi công chi tiết"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Shop drawing thi công</b><span>Hồ sơ kỹ thuật chi tiết cho công trường.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Hồ sơ xin phép & dấu kiến trúc sư"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Hồ sơ xin phép &amp; dấu KTS</b><span>Hồ sơ pháp lý chuẩn, KTS ký &amp; chịu trách nhiệm.</span></span></label>
        </div>
      </div>

      <div class="grp reveal" data-key="p3" style="--gc:var(--gold-bright)">
        <label class="grp-head">
          <input type="checkbox" class="master">
          <span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span>
          <span class="grp-meta"><b>Hệ thống III · Interior &amp; CNC Detailer (phân hệ chủ lực)</b><span>Từ render nội thất óc chó đến lệnh cắt CNC cho xưởng.</span></span>
          <span class="grp-count">0/4</span>
        </label>
        <div class="picks">
          <label class="pick"><input type="checkbox" data-label="Render nội thất óc chó độ thực cao (vân gỗ 1:1)"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Render nội thất óc chó độ thực cao</b><span>Map vân gỗ, ánh sáng, vật liệu thật 1:1.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Bóc tách BOQ tự động (~98% chính xác)"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Bóc tách BOQ tự động ~98%</b><span>Bảng khối lượng &amp; dự toán chính xác cao.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Tối ưu xếp ván (nesting) giảm hao hụt gỗ"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Tối ưu xếp ván (nesting)</b><span>Giảm tối đa hao hụt gỗ quý.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Xuất lệnh cắt CNC cho xưởng mộc"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Xuất lệnh cắt CNC</b><span>Đưa thẳng bản vẽ xuống máy cắt tại xưởng.</span></span></label>
        </div>
      </div>

      <div class="grp reveal" data-key="p4" style="--gc:var(--sage)">
        <label class="grp-head">
          <input type="checkbox" class="master">
          <span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span>
          <span class="grp-meta"><b>Hệ thống IV–V · Vận hành, ERP &amp; Cố vấn AI</b><span>Quản trị toàn tập đoàn, 16 agent cố vấn, ERP Copilot.</span></span>
          <span class="grp-count">0/5</span>
        </label>
        <div class="picks">
          <label class="pick"><input type="checkbox" data-label="Mạng lưới 16 Agent cố vấn AI + Virtual CEO"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>16 Agent cố vấn AI + Virtual CEO</b><span>Cố vấn pháp chế, nhân sự, tài chính real-time.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Quản lý sản xuất nội thất tại xưởng"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Quản lý sản xuất tại xưởng</b><span>Điều hành xưởng 3.000m² theo đơn hàng.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Mua sắm · Kho · Chuỗi cung ứng"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Mua sắm · Kho · Chuỗi cung ứng</b><span>Vật tư, tồn kho, nhà cung cấp liên thông bản vẽ.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Giá thành & lợi nhuận theo từng dự án"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Giá thành &amp; lợi nhuận theo dự án</b><span>Biết lãi/lỗ chính xác từng công trình.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Kế toán tự động (chuẩn VAS) + ERP Copilot"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Kế toán tự động + ERP Copilot</b><span>Hỏi một câu, hệ thống tự vẽ báo cáo.</span></span></label>
        </div>
      </div>

      <div class="grp reveal" data-key="p6" style="--gc:var(--gold-deep)">
        <label class="grp-head">
          <input type="checkbox" class="master">
          <span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span>
          <span class="grp-meta"><b>Hệ thống VI–VII · Thương mại hóa &amp; Điểm chạm</b><span>Sàn SaaS, hoa hồng vật liệu, landing &amp; lễ tân AI.</span></span>
          <span class="grp-count">0/5</span>
        </label>
        <div class="picks">
          <label class="pick"><input type="checkbox" data-label="Sàn niêm yết & bán hàng online"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Sàn niêm yết &amp; bán hàng online</b><span>Đăng bán sản phẩm/dự án, hợp đồng số.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Suppliers Hub — vật liệu & gỗ cao cấp"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Suppliers Hub vật liệu</b><span>Thương hiệu gỗ &amp; vật liệu tham gia, thu phí.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Mạng lưới affiliate & hoa hồng minh bạch"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Affiliate &amp; hoa hồng</b><span>CTV bán hàng, hoa hồng minh bạch.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Luxury landing page thương hiệu HCD"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Luxury landing thương hiệu</b><span>Mặt tiền số cao cấp mang thương hiệu HCD.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Lễ tân AI 24/7 → tự đẩy lead vào CRM"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Lễ tân AI 24/7 → CRM</b><span>Tiếp khách 24/7, phân loại &amp; đẩy lead.</span></span></label>
        </div>
      </div>

      <div class="grp reveal" data-key="addons" style="--gc:var(--mist)">
        <label class="grp-head">
          <input type="checkbox" class="master">
          <span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span>
          <span class="grp-meta"><b>Tuỳ chọn nâng cao</b><span>Thêm vào nếu HCD muốn — không bắt buộc.</span></span>
          <span class="grp-count">0/6</span>
        </label>
        <div class="picks">
          <label class="pick"><input type="checkbox" data-label="Ứng dụng di động (iOS/Android)"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Ứng dụng di động (iOS/Android)</b><span>App cho nhân viên &amp; khách hàng.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Cổng cho khách theo dõi tiến độ công trình"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Cổng khách theo dõi tiến độ</b><span>Khách tự xem tiến độ công trình của mình.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Giám sát công trường bằng drone / camera AI"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Giám sát drone / camera AI</b><span>Tự động giám sát tiến độ &amp; chất lượng.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Đa ngôn ngữ (Việt / Anh)"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Đa ngôn ngữ (Việt / Anh)</b><span>Phục vụ khách &amp; đối tác quốc tế.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Hoá đơn điện tử & tích hợp ngân hàng"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Hoá đơn điện tử &amp; ngân hàng</b><span>Xuất hoá đơn, đối soát thu chi tự động.</span></span></label>
          <label class="pick"><input type="checkbox" data-label="Phân quyền nhiều cấp cho cả tập đoàn"><span class="box"><svg viewBox="0 0 24 24"><path d="M5 12l4 4L19 7"/></svg></span><span class="meta"><b>Phân quyền nhiều cấp</b><span>Mỗi phòng ban/chi nhánh có quyền riêng.</span></span></label>
        </div>
      </div>

      <div class="grp reveal" data-key="dir" style="--gc:var(--gold)">
        <div class="grp-head static">
          <span class="grp-meta"><b>Hướng triển khai mong muốn</b><span>Chọn 1 — hoặc để chúng tôi tư vấn thêm.</span></span>
        </div>
        <div class="picks">
          <label class="pick radio"><input type="radio" name="dir" data-label="Nhanh nhất — đấu nối nền tảng có sẵn (~45 ngày)"><span class="box"></span><span class="meta"><b>Nhanh nhất (~45 ngày)</b><span>Đấu nối module có sẵn, lên sóng nhanh.</span></span></label>
          <label class="pick radio"><input type="radio" name="dir" data-label="Xây riêng theo đặc thù (5–6 tháng)"><span class="box"></span><span class="meta"><b>Xây riêng (5–6 tháng)</b><span>Phát triển hệ thống riêng theo đặc thù HCD.</span></span></label>
          <label class="pick radio"><input type="radio" name="dir" data-label="Chưa rõ — cần tư vấn thêm" checked><span class="box"></span><span class="meta"><b>Cần tư vấn thêm</b><span>Chưa chắc — muốn nghe gợi ý phương án.</span></span></label>
        </div>
      </div>

      <div class="grp reveal" data-key="scale" style="--gc:var(--sage)">
        <div class="grp-head static">
          <span class="grp-meta"><b>Quy mô &amp; thời gian</b><span>Giúp chúng tôi ước lượng đúng nguồn lực (không bắt buộc).</span></span>
        </div>
        <div class="frow">
          <div><label class="flbl" for="scale1">Số dự án chạy song song dự kiến</label>
            <select id="scale1"><option value="">— Chưa xác định —</option><option>1–5 dự án</option><option>5–20 dự án</option><option>Trên 20 dự án</option></select></div>
          <div><label class="flbl" for="scale2">Mong muốn lên sóng trong</label>
            <select id="scale2"><option value="">— Chưa xác định —</option><option>1–2 tháng</option><option>3–6 tháng</option><option>Linh hoạt theo tư vấn</option></select></div>
        </div>
        <div class="fld">
          <label class="flbl" for="extra">Yêu cầu bổ sung khác (HCD muốn thêm gì cứ ghi vào đây)</label>
          <textarea id="extra" placeholder="Ví dụ: cần kết nối phần mềm kế toán đang dùng, cần đào tạo nhân sự, ưu tiên xưởng Thạch Thất trước…"></textarea>
        </div>
      </div>

      <div class="grp reveal" data-key="contact" style="--gc:var(--gold-deep)">
        <div class="grp-head static">
          <span class="grp-meta"><b>Thông tin để chúng tôi báo giá lại</b><span>Để liên hệ &amp; gửi phương án chi tiết cho đúng người.</span></span>
        </div>
        <div class="frow">
          <div><label class="flbl" for="cName">Họ tên người phụ trách</label><input type="text" id="cName" placeholder="VD: Nguyễn Văn A"></div>
          <div><label class="flbl" for="cCompany">Công ty</label><input type="text" id="cCompany" value="HCD Holdings"></div>
          <div><label class="flbl" for="cPhone">Điện thoại / Zalo</label><input type="tel" id="cPhone" placeholder="VD: 09xx xxx xxx"></div>
          <div><label class="flbl" for="cEmail">Email</label><input type="email" id="cEmail" placeholder="email@congty.com"></div>
        </div>
      </div>

    </form>

    <div class="summary reveal" id="summaryCard">
      <div class="scnt">Đã chọn <b id="cnt">0</b> hạng mục</div>
      <ul id="sumList"><li class="empty">Chưa chọn mục nào — tích vào các ô phía trên, hoặc bấm “Trọn bộ 7 hệ thống”.</li></ul>
      <div class="actions">
        <button type="button" id="sendBtn" class="btn btn-gold">Gửi yêu cầu báo giá →</button>
        <button type="button" id="copyBtn" class="btn btn-ghost">Sao chép nội dung</button>
        <button type="button" id="dlBtn" class="btn btn-ghost">Tải phiếu (.txt)</button>
      </div>
      <div class="contact-chips">
        <a href="tel:0913192586">📞 0913 192 586</a>
        <a href="mailto:ceo@zenidigital.com">✉️ ceo@zenidigital.com</a>
        <span class="who">Mr. Thiên Mộc Đức · Zeni Digital</span>
      </div>
      <div id="sendMsg" class="sendmsg"></div>
    </div>
  </div>
</section>

<!-- FINAL CTA -->
<section>
  <div class="wrap">
    <div class="cta reveal">
      <div class="eyebrow">Bước tiếp theo</div>
      <h2>Trở thành người dẫn đầu <span class="g">ngành nội thất số</span>.</h2>
      <p>Đề xuất này là khung giải pháp và biên độ ngân sách. Bước kế tiếp: chốt phạm vi triển khai theo từng hệ thống để đi tới hợp đồng và giá cuối cùng.</p>
      <div class="cta-actions">
        <a class="btn btn-gold" href="#contact">Đặt lịch trao đổi phương án</a>
        <a class="btn btn-ghost" href="/app">Xem nền tảng demo</a>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap foot">
    <div class="foot-brand">
      <span class="fseal">H</span>
      <div><b>HCD Holdings</b><small>Hệ sinh thái trí tuệ nhân tạo · Thiết kế — Sản xuất — Thương mại nội thất</small></div>
    </div>
    <div class="foot-meta">
      Đối tác công nghệ: <b>Zeni Digital</b> · Mr. Thiên Mộc Đức<br>
      0913 192 586 · ceo@zenidigital.com · © MMXXVI
    </div>
  </div>
</footer>

<script>
  var io=new IntersectionObserver(function(es){
    es.forEach(function(e){ if(e.isIntersecting){ e.target.classList.add('in'); io.unobserve(e.target); } });
  },{threshold:.12});
  document.querySelectorAll('.reveal').forEach(function(el){ io.observe(el); });
</script>

<!-- ============ PHIẾU CHỌN HẠNG MỤC ============
     Để khách bấm "Gửi yêu cầu" là email tự bay thẳng về hộp thư của Zeni (không cần khách có app mail):
     1) Vào https://web3forms.com  →  nhập email  ceo@zenidigital.com  →  bấm lấy Access Key (miễn phí).
     2) Dán key đó vào trong dấu ngoặc kép ở dòng  var W3F_KEY = ""  ngay bên dưới.
     Nếu để trống, nút "Gửi yêu cầu" sẽ tự mở ứng dụng email của khách (vẫn dùng được). -->
<script>
(function(){
  var W3F_KEY = ""; // ⬅️ dán Access Key web3forms vào đây (tuỳ chọn)

  function $(id){ return document.getElementById(id); }
  function val(id){ var el=$(id); return el ? el.value.trim() : ""; }
  function groups(){ return [].slice.call(document.querySelectorAll('.grp')); }
  function labelOf(i){ return i.getAttribute('data-label') || (i.closest('.pick') ? i.closest('.pick').querySelector('.meta b').textContent.trim() : ''); }

  function updateGroup(g){
    var subs=[].slice.call(g.querySelectorAll('.picks input[type=checkbox]'));
    var master=g.querySelector('.master');
    var cnt=g.querySelector('.grp-count');
    var n=subs.filter(function(s){return s.checked;}).length;
    if(master){ master.checked = (n===subs.length && subs.length>0); master.indeterminate = (n>0 && n<subs.length); }
    if(cnt) cnt.textContent = n + '/' + subs.length;
  }

  function refresh(){
    groups().forEach(updateGroup);
    var picked=[].slice.call(document.querySelectorAll('.picks input[type=checkbox]:checked'));
    $('cnt').textContent = picked.length;
    var ul=$('sumList'); ul.innerHTML='';
    if(!picked.length){
      var e=document.createElement('li'); e.className='empty';
      e.textContent='Chưa chọn mục nào — tích vào các ô phía trên, hoặc bấm “Trọn bộ 7 hệ thống”.';
      ul.appendChild(e);
    } else {
      picked.forEach(function(i){ var li=document.createElement('li'); li.textContent=labelOf(i); ul.appendChild(li); });
    }
  }

  document.addEventListener('change', function(e){
    var t=e.target;
    if(t.classList && t.classList.contains('master')){
      var g=t.closest('.grp');
      [].slice.call(g.querySelectorAll('.picks input[type=checkbox]')).forEach(function(s){ s.checked=t.checked; });
    }
    refresh();
  });

  [].slice.call(document.querySelectorAll('.preset')).forEach(function(b){
    b.addEventListener('click', function(){
      var p=b.getAttribute('data-preset');
      var all=[].slice.call(document.querySelectorAll('.picks input[type=checkbox]'));
      if(p==='clear') all.forEach(function(c){ c.checked=false; });
      if(p==='all')   all.forEach(function(c){ c.checked=true; });
      if(p==='lean'){
        all.forEach(function(c){ c.checked=false; });
        ['p1','p3'].forEach(function(k){
          [].slice.call(document.querySelectorAll('.grp[data-key="'+k+'"] .picks input[type=checkbox]')).forEach(function(c){ c.checked=true; });
        });
      }
      refresh();
      $('summaryCard').scrollIntoView({behavior:'smooth', block:'center'});
    });
  });

  function buildText(){
    var out='PHIẾU CHỌN HẠNG MỤC — HỆ SINH THÁI AI HCD HOLDINGS\n';
    out+='(Khách hàng tích chọn — gửi Zeni Digital lên phương án & báo giá)\n\n';
    groups().forEach(function(g){
      var tEl=g.querySelector('.grp-meta b'); if(!tEl) return;
      var items=[].slice.call(g.querySelectorAll('.picks input:checked')).map(labelOf);
      if(items.length){ out+='• '+tEl.textContent.trim()+':\n'; items.forEach(function(t){ out+='    - '+t+'\n'; }); out+='\n'; }
    });
    var s1=val('scale1'), s2=val('scale2');
    if(s1) out+='• Số dự án song song dự kiến: '+s1+'\n';
    if(s2) out+='• Mong muốn lên sóng trong: '+s2+'\n';
    var ex=val('extra'); if(ex) out+='\n• Yêu cầu bổ sung khác:\n'+ex+'\n';
    return out.replace(/\s+$/,'');
  }
  function contactBlock(){
    return '\n\n— THÔNG TIN LIÊN HỆ —\nNgười gửi: '+val('cName')+'\nCông ty: '+val('cCompany')+'\nĐiện thoại/Zalo: '+val('cPhone')+'\nEmail: '+val('cEmail');
  }
  function fullText(){ return buildText()+contactBlock(); }
  function anyPicked(){ return document.querySelectorAll('.picks input[type=checkbox]:checked').length>0; }
  function msg(type, html){ var m=$('sendMsg'); m.className='sendmsg '+type; m.innerHTML=html; }

  function openMail(){
    var url='mailto:ceo@zenidigital.com?subject='+encodeURIComponent('[HCD Holdings] Phiếu chọn hạng mục hệ sinh thái AI')+'&body='+encodeURIComponent(fullText());
    window.location.href=url;
    msg('info','Đang mở ứng dụng email để bạn bấm <b>Gửi</b>. Nếu máy chưa cài email, hãy bấm <b>“Sao chép nội dung”</b> rồi dán gửi qua Zalo <b>0913 192 586</b>.');
  }

  $('sendBtn').addEventListener('click', function(){
    if(!anyPicked()){ msg('info','Hãy tích chọn ít nhất 1 hạng mục bạn quan tâm trước khi gửi nhé.'); $('scopeForm').scrollIntoView({behavior:'smooth'}); return; }
    if(W3F_KEY && W3F_KEY.length>10){
      msg('info','Đang gửi yêu cầu tới Zeni…');
      fetch('https://api.web3forms.com/submit',{method:'POST',headers:{'Content-Type':'application/json','Accept':'application/json'},
        body:JSON.stringify({access_key:W3F_KEY,subject:'[HCD Holdings] Phiếu chọn hạng mục hệ sinh thái AI',from_name:(val('cName')||'HCD Holdings'),replyto:val('cEmail'),botcheck:'','Người gửi':val('cName'),'Công ty':val('cCompany'),'Điện thoại/Zalo':val('cPhone'),'Email':val('cEmail'),'Nội dung chọn':buildText()})
      }).then(function(r){ return r.json(); }).then(function(j){
        if(j && j.success){ msg('ok','✓ Đã gửi thành công! Zeni Digital sẽ xem lựa chọn của bạn và liên hệ lại sớm để chốt phương án &amp; báo giá. Cảm ơn HCD Holdings!'); }
        else { openMail(); }
      }).catch(function(){ openMail(); });
    } else { openMail(); }
  });

  function fallbackCopy(text){ var ta=document.createElement('textarea'); ta.value=text; ta.style.position='fixed'; ta.style.opacity='0'; document.body.appendChild(ta); ta.select(); try{ document.execCommand('copy'); }catch(e){} document.body.removeChild(ta); }
  $('copyBtn').addEventListener('click', function(){
    var text=fullText();
    function done(){ msg('ok','✓ Đã sao chép toàn bộ lựa chọn. Dán (Ctrl/Cmd+V) vào Zalo/Email gửi cho Zeni: 0913 192 586 · ceo@zenidigital.com.'); }
    if(navigator.clipboard && navigator.clipboard.writeText){ navigator.clipboard.writeText(text).then(done, function(){ fallbackCopy(text); done(); }); }
    else { fallbackCopy(text); done(); }
  });

  $('dlBtn').addEventListener('click', function(){
    var blob=new Blob([fullText()],{type:'text/plain;charset=utf-8'});
    var a=document.createElement('a'); a.href=URL.createObjectURL(blob); a.download='Phieu-chon-hang-muc-HCD.txt';
    document.body.appendChild(a); a.click(); document.body.removeChild(a);
    msg('ok','✓ Đã tải phiếu chọn (.txt). Bạn gửi file này qua Zalo/Email cho Zeni: 0913 192 586.');
  });

  refresh();
})();
</script>
</body>
</html>
