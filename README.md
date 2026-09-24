<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#0A0A0A">
<meta property="og:title" content="Huy Trần – Only The Best">
<meta property="og:description" content="Xây dựng Tư duy, Tài chính và Bản lĩnh phái mạnh.">
<title>Huy Trần – Only The Best</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#0A0A0A;--bg2:#121212;--tx:#F5F5F5;--mu:#9a9a9a;--ac:#D4AF37;--ln:rgba(212,175,55,.35);
box-sizing:border-box;color-scheme:dark;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-behavior:smooth;scroll-padding-top:env(safe-area-inset-top,0px)}
*,*::before,*::after{box-sizing:inherit;margin:0}
body{background:var(--bg);color:var(--tx);font:400 16px/1.65 Montserrat,system-ui,sans-serif;-webkit-font-smoothing:antialiased}
h1,h2,h3{font-weight:800;line-height:1.15}
a{color:inherit;text-decoration:none}
section{padding:72px 20px}
.w{max-width:1080px;margin:0 auto}
.kick{color:var(--ac);font-size:12px;font-weight:700;letter-spacing:.28em;text-transform:uppercase;margin-bottom:12px}
h2{font-size:clamp(26px,6vw,40px);margin-bottom:32px}
.btn{display:inline-block;text-align:center;padding:15px 28px;font:700 14px Montserrat,system-ui,sans-serif;letter-spacing:.08em;text-transform:uppercase;border:1px solid var(--ac);cursor:pointer;transition:.25s}
.b1{background:var(--ac);color:#0A0A0A}.b1:hover{background:#e6c34d}
.b2{background:transparent;color:var(--ac)}.b2:hover{background:rgba(212,175,55,.12)}

/* Placeholder CSS */
.ph{display:grid;place-items:center;text-align:center;background:repeating-linear-gradient(45deg,#151515 0 12px,#1a1a1a 12px 24px);border:1px dashed var(--ln);color:var(--mu);font-size:12px;letter-spacing:.06em;padding:8px}
.ph::after{content:attr(data-l)}

/* 1. HERO */
.hero{position:relative;min-height:88svh;display:flex;align-items:center;overflow:hidden}
.hero>.ph{position:absolute;top:0;right:0;bottom:0;width:100%;height:100%;opacity:.35;border:0;-webkit-mask-image:linear-gradient(to left,#000 30%,transparent);mask-image:linear-gradient(to left,#000 30%,transparent)}
.hero .w{position:relative;z-index:1;width:100%}
.hero h1{font-size:clamp(44px,13vw,92px);text-transform:uppercase;color:var(--ac)}
.hero h1 small{display:block;font-size:clamp(20px,5vw,30px);text-transform:none;color:var(--tx);margin-top:18px;line-height:1.3;max-width:600px}
.hero p{max-width:520px;color:#cfcfcf;margin:22px 0 32px}
.cta{display:flex;flex-direction:column;gap:12px;max-width:340px}

/* 2. TRIẾT LÝ */
.about{text-align:center}
.box{max-width:760px;margin:0 auto;border:1px solid var(--ac);padding:44px 24px}
.box .ph{width:100px;height:100px;margin:0 auto 24px;border-radius:50%}
.box p{font-size:clamp(17px,4vw,22px);color:#dcdcdc}
.box b{color:var(--ac)}

/* 3. CHƯƠNG TRÌNH */
.grid{display:grid;gap:26px}
.card{background:var(--bg2);border:1px solid #262626;padding:32px 26px;position:relative;display:flex;flex-direction:column}
.card h3{font-size:24px;margin-bottom:4px}
.card .sub{color:var(--mu);font-size:14px;margin-bottom:18px}
.card ul{list-style:none;padding:0;margin:0 0 28px;flex:1}
.card li{padding:10px 0 10px 28px;position:relative;border-bottom:1px solid #222;font-size:15px}
.card li::before{content:"✦";position:absolute;left:0;color:var(--ac)}
.hot{border-color:var(--ac);background:linear-gradient(180deg,#1a1608,#121212);box-shadow:0 0 40px rgba(212,175,55,.12)}
.badge{position:absolute;top:-13px;left:26px;background:var(--ac);color:#0A0A0A;font-size:11px;font-weight:800;letter-spacing:.18em;padding:5px 12px;text-transform:uppercase}

/* 4. TESTIMONIALS */
.sl{overflow:hidden;max-width:620px;margin:0 auto}
.tr{display:flex;transition:transform .6s ease}
.sd{flex:0 0 100%;padding:0 6px;display:flex;justify-content:center}
.shot{aspect-ratio:9/16;width:min(100%,270px);max-height:480px;border-radius:22px;}
.dots{display:flex;justify-content:center;gap:8px;margin-top:22px}
.dots button{width:9px;height:9px;border-radius:5px;border:0;background:#444;padding:0;cursor:pointer;transition:.3s}
.dots .on{background:var(--ac);width:24px}

/* 5. BLOG */
.tabs{display:flex;overflow-x:auto;margin-bottom:28px;border-bottom:1px solid #262626}
.tabs button{flex:1 0 auto;background:none;border:0;border-bottom:2px solid transparent;color:var(--mu);font:700 14px Montserrat,system-ui,sans-serif;letter-spacing:.06em;text-transform:uppercase;padding:14px 16px;cursor:pointer;margin-bottom:-1px}
.tabs .on{color:var(--ac);border-color:var(--ac)}
.posts{display:grid;gap:22px}
.post{background:var(--bg2);border:1px solid #232323;overflow:hidden}
.thumb{overflow:hidden;aspect-ratio:16/9}
.thumb .ph{width:100%;height:100%;transition:transform .5s;border:none}
.post:hover .thumb .ph{transform:scale(1.07)}
.post .in{padding:20px}
.post h3{font-size:20px;margin:6px 0 16px}
.more{color:var(--ac);font-size:12px;font-weight:700;letter-spacing:.12em;text-transform:uppercase;border-bottom:1px solid var(--ac);padding-bottom:2px}

/* 6. FOOTER */
footer{background:#050505;border-top:1px solid var(--ln);padding:64px 20px 40px;text-align:center}
.logo{font-size:clamp(26px,8vw,44px);font-weight:800;letter-spacing:.3em;text-transform:uppercase;color:var(--ac)}
.logo small{display:block;font-size:11px;letter-spacing:.5em;color:var(--mu);margin-top:6px;font-weight:500}
.soc{display:flex;justify-content:center;align-items:center;gap:26px;margin:34px 0}
.soc a{color:var(--tx);transition:.25s;display:grid;place-items:center}
.soc a:hover{color:var(--ac);transform:translateY(-3px)}
.soc svg{width:34px;height:34px;fill:none;stroke:currentColor;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
.soc .tt{width:88px;height:88px;border:1px solid var(--ac);border-radius:50%;color:var(--ac)}
.soc .tt svg{width:52px;height:52px;stroke-width:2.2}
.nl{max-width:460px;margin:0 auto}
.nl p{color:var(--mu);font-size:14px;margin-bottom:14px}
.nl form{display:flex;flex-direction:column;gap:10px}
.nl input{padding:15px 16px;background:#111;border:1px solid #333;color:var(--tx);font:inherit;border-radius:0}
.nl input:focus{outline:1px solid var(--ac)}
.fine{margin-top:44px;font-size:12px;color:#6b6b6b}

@media(min-width:800px){
section{padding:110px 32px}
.hero>.ph{width:55%;min-width:600px;opacity:1}
.cta{flex-direction:row;max-width:none}
.grid{grid-template-columns:1fr 1fr}.hot{transform:scale(1.03)}
.posts{grid-template-columns:repeat(3,1fr)}
.nl form{flex-direction:row}.nl input{flex:1}
}
.hero .kick{color:var(--ac);margin:0 0 16px;max-width:none}
.box .kick{font-size:12px;color:var(--ac)}
.chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:16px}
.chips span{border:1px solid var(--ln);color:var(--ac);font-size:12px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;padding:7px 12px}
.story{max-width:760px;margin:64px auto 0}
.story p{margin-bottom:18px;color:#d6d6d6}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:0 0 32px}
.stats div{border:1px solid #262626;background:var(--bg2);padding:16px 6px;text-align:center}
.stats b{display:block;font-size:clamp(22px,6vw,34px);color:var(--ac);line-height:1.1}
.stats small{display:block;font-size:11px;color:var(--mu);line-height:1.3;margin-top:4px}
.warn{border-left:3px solid var(--ac);background:var(--bg2);padding:18px 20px;margin-bottom:36px;font-size:15px;color:#d6d6d6}
.warn b{display:block;color:var(--ac);margin-bottom:6px}
.price{font-size:26px;font-weight:800;color:var(--ac);margin:4px 0 2px}
.meta{color:var(--mu);font-size:13px;margin-bottom:18px}
.card details{margin:-12px 0 24px;font-size:14px;color:#cfcfcf}
.card summary{cursor:pointer;color:var(--ac);font-weight:700;padding:8px 0}
.card details p{margin:6px 0}
.tip{color:var(--mu);font-size:13px;margin:-8px 0 22px}
.tag{background:var(--ac);color:#0A0A0A;font-size:10px;font-weight:800;letter-spacing:.1em;padding:2px 7px;margin-right:8px;vertical-align:middle}
.list{grid-column:1/-1}
.list a{display:flex;justify-content:space-between;gap:12px;padding:14px 4px;border-bottom:1px solid #222;font-size:15px}
.list a:hover{color:var(--ac)}
.soc{gap:22px}
</style>
</head>
<body>

<header class="hero" style="padding:64px 20px">
  <div class="ph" data-l="Ảnh chân dung (1920x1080)"></div>
  <div class="w">
    <p class="kick">Huy Trần · OnlyTheBest — Chỉ lựa chọn cái tốt nhất</p>
    <h1>Only The Best<small>Xây dựng Tư duy, Tài chính và Bản lĩnh phái mạnh.</small></h1>
    <p>Trang bị những góc nhìn sắc bén nhất về cuộc sống, tiền bạc và các mối quan hệ để bạn trở thành phiên bản ưu tú nhất.</p>
    <div class="cta">
      <a class="btn b1" href="#coaching">Đăng ký Coaching 1:1</a>
      <a class="btn b2" href="#kien-thuc">Đọc Bài Viết Mới</a>
    </div>
  </div>
</header>

<section class="about">
  <div class="box">
    <div class="ph" data-l="Logo"></div>
    <p class="kick">Triết lý cốt lõi</p>
    <p><b>OnlyTheBest</b> nghĩa là chỉ lựa chọn cái tốt nhất. Trong bất kì hoàn cảnh nào, tui sẽ tìm ra lựa chọn tốt nhất, quyết định tốt nhất. Và cho dù cái "tốt nhất" đã được chọn, nó sẽ liên tục được review và sẽ bị thay thế nếu phát hiện ra có cái tốt hơn.</p>
    <p style="margin-top:18px;font-size:16px">Tốt nhất có nghĩa là:</p>
    <div class="chips"><span>Mạnh mẽ nhất</span><span>Thông minh nhất</span><span>Linh hoạt nhất</span><span>Chính xác nhất</span><span>Tối ưu nhất</span><span>Uy tín nhất</span><span>Nhanh nhất</span></div>
  </div>
  <div class="story" style="text-align:left">
    <p class="kick">Câu chuyện</p>
    <h2>Vì sao tui lập kênh chia sẻ</h2>
    <div class="stats">
      <div><b>2010</b><small>Bắt đầu học hỏi liên tục</small></div>
      <div><b>12 năm</b><small>Đầu tư cổ phiếu liên tục</small></div>
      <div><b>Cả ngàn</b><small>Em gái đã tiếp xúc</small></div>
    </div>
    <p>Một trong những lý do tui lập kênh chia sẻ là vì lúc nhỏ tui không có 1 người anh có hiểu biết để hướng dẫn cho mình về cách học hỏi hay định hướng cho cuộc sống. Tuổi mới lớn tui cũng không có 1 người anh biết cách tán tỉnh hay thu hút con gái đẹp. Giờ đây khi tạm có 1 chút thành công nhờ học hỏi liên tục từ 2010, đầu tư cổ phiếu liên tục 12 năm, tiếp xúc cả ngàn em gái, từng nhiều lần mất tiền, bị từ chối, tui xuất hiện và chia sẻ những kinh nghiệm của mình để giúp bạn rút ngắn nhiều tháng, nhiều năm cuộc đời trong việc mò mẫm, cố gắng học hỏi để đạt được các mục tiêu về tài chính, quan hệ.</p>
  </div>
</section>

<section id="coaching" style="background:var(--bg2)">
  <div class="w">
    <p class="kick">Chương trình đào tạo</p>
    <h2>Chọn cấp độ dành cho bạn</h2>
    <div class="warn"><b>ĐỪNG ĐĂNG KÝ HỌC NẾU BẠN CHƯA BÀO HẾT CLIP MIỄN PHÍ CỦA TUI!</b>Tui có đào tạo! Nhưng trước khi tham gia hay quay lại bào mấy clip miễn phí đến khi nào bạn thấy giá trị đã vượt phí đào tạo.</div>
    <div class="grid">
      <article class="card" style="background:var(--bg)">
        <h3>Khóa Khởi Đầu</h3>
        <p class="sub">Định hướng &amp; Mục tiêu</p>
        <p class="price">5.000.000 VNĐ</p>
        <p class="meta">Call cá nhân hóa ~2 tiếng · Được hỏi lại khi va chạm thực tế, tối đa 1 năm</p>
        <ul>
          <li>Chỉnh lại cách ăn nói, cách đặt câu hỏi để người giỏi chịu giúp đỡ bạn</li>
          <li>Thiết kế mục tiêu hiệu quả để sống có mục đích, không vô định</li>
          <li>Dùng thời gian tối ưu và fix các tư duy nghèo cản trở phát triển</li>
        </ul>
        <a class="btn b2" href="https://docs.google.com/forms/d/e/1FAIpQLSdF47USbaz5NNSbvsKuKYLBNGsACRBWNtV8R398xOmuR2HujQ/viewform" target="_blank" rel="noopener">Đăng ký ngay</a>
      </article>
      <article class="card hot">
        <span class="badge">Premium</span>
        <h3>Khóa Tự Học Nhanh + Đầu Tư</h3>
        <p class="sub">Tư duy xác suất · Tâm lý ứng dụng · Đầu tư</p>
        <p class="price">100.000.000 VNĐ</p>
        <p class="meta">Combo 2 khóa · Kèm cặp đến khi xong chương trình · Hỗ trợ tối đa 1 năm</p>
        <ul>
          <li>Tư duy giàu – nghèo: hệ thống niềm tin quyết định bạn có giàu hay không</li>
          <li>Tư duy xác suất chuyên sâu, tâm lý học ứng dụng, phương pháp tự học hiệu quả</li>
          <li>Đầu tư: định giá doanh nghiệp, chọn cổ phiếu và xây danh mục, quản trị rủi ro</li>
          <li>Được đặc quyền làm phiền; có thể gặp mặt trực tiếp (bonus)</li>
        </ul>
        <a class="btn b1" href="https://docs.google.com/forms/d/e/1FAIpQLSdF47USbaz5NNSbvsKuKYLBNGsACRBWNtV8R398xOmuR2HujQ/viewform" target="_blank" rel="noopener">Đăng ký ngay</a>
      </article>
    </div>
  </div>
</section>

<section>
  <div class="w">
    <p class="kick">Bằng chứng</p>
    <h2>Feedback từ các bạn</h2>
    <div class="sl"><div class="tr">
      <div class="sd"><div class="ph shot" data-l="Ảnh Feedback 1"></div></div>
      <div class="sd"><div class="ph shot" data-l="Ảnh Feedback 2"></div></div>
      <div class="sd"><div class="ph shot" data-l="Ảnh Feedback 3"></div></div>
    </div></div>
    <div class="dots"></div>
  </div>
</section>

<section id="kien-thuc" style="background:var(--bg2)">
  <div class="w">
    <p class="kick">Kiến thức</p>
    <h2>Bài viết của Huy Trần</h2>
    <div class="tabs" role="tablist">
      <button class="on" data-k="mindset">Tư duy</button>
      <button data-k="finance">Tài chính</button>
      <button data-k="social">Mối quan hệ</button>
    </div>
    <div class="posts" id="posts"></div>
  </div>
</section>

<footer>
  <div class="logo">Only The Best<small>Huy Trần</small></div>
  <div class="soc">
    <a class="tt" href="https://www.tiktok.com/@huytran.onlythebest" target="_blank" rel="noopener" aria-label="TikTok"><svg viewBox="0 0 24 24"><path d="M14 4v10.5a3.5 3.5 0 1 1-3.5-3.5M14 4c.4 2.6 2.1 4.4 5 4.7"/></svg></a>
    <a href="https://www.youtube.com/@Huytran.OnlyTheBestNo1" target="_blank" rel="noopener" aria-label="YouTube"><svg viewBox="0 0 24 24"><rect x="2.5" y="5.5" width="19" height="13" rx="4"/><path d="M10.5 9.5v5l4-2.5z"/></svg></a>
    <a href="https://www.instagram.com/huytran.onlythebest/" target="_blank" rel="noopener" aria-label="Instagram"><svg viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><path d="M17.4 6.6h.01"/></svg></a>
  </div>
  <div class="nl">
    <p>Đăng ký nhận Newsletter — Cập nhật bài viết sâu nhất hàng tuần</p>
    <form><input type="email" placeholder="Email của bạn" required aria-label="Email"><button class="btn b1" type="submit">Đăng ký</button></form>
  </div>
</footer>

<script>
const tr=document.querySelector('.tr'),dots=document.querySelector('.dots'),sl=document.querySelector('.sl'),n=tr.children.length;
let i=0,t,x0;
for(let k=0;k<n;k++){const b=document.createElement('button');b.setAttribute('aria-label','Slide '+(k+1));b.onclick=()=>go(k,1);dots.append(b)}
function go(k,reset){i=(k+n)%n;tr.style.transform='translateX(-'+i*100+'%)';[...dots.children].forEach((d,j)=>d.classList.toggle('on',j==i));if(reset)play()}
function play(){clearInterval(t);t=setInterval(()=>go(i+1),4500)}
sl.addEventListener('touchstart',e=>x0=e.touches[0].clientX,{passive:true});
sl.addEventListener('touchend',e=>{const d=e.changedTouches[0].clientX-x0;if(Math.abs(d)>40)go(i+(d<0?1:-1),1)});
sl.onmouseenter=()=>clearInterval(t);sl.onmouseleave=play;
go(0);play();

const P={
 mindset:['+Uy tín là sức mạnh phần 1','Làm sao để người giỏi dạy mình','Cái tôi lớn làm trì trệ con người bạn!','1 chút về tư duy xác suất','Ăn nói'],
 finance:['Có nên cho bạn bè người thân vay tiền?','Cắt lỗ','Tài sản vs tiêu sản','Lãi kép','Đốt tiền'],
 social:['+Mẫu bạn gái tồi tệ','+Dành riêng cho mấy thằng đực mới lớn','Sự an toàn của thằng đàn ông','Nam nữ bình đẳng?','Tình trạng hẹn hò hiện nay']
};
const box=document.getElementById('posts');
const url= 'https://www.tiktok.com/@huytran.onlythebest';
function show(k){
 const a=P[k].map(s=>{const w=s[0]=='+',t=w?s.slice(1):s;return{t:t,w:w,u:url}});
 const g=w=>w?'<span class="tag">MỚI</span>':'';
 box.innerHTML=a.slice(0,3).map(p=>'<article class="post"><div class="thumb"><div class="ph" data-l="Ảnh Blog"></div></div><div class="in"><h3>'+g(p.w)+p.t+'</h3><a class="more" href="'+p.u+'" target="_blank">Đọc tiếp →</a></div></article>').join('')
  +'<div class="list">'+a.slice(3).map(p=>'<a href="'+p.u+'" target="_blank"><span>'+g(p.w)+p.t+'</span><span>→</span></a>').join('')+'</div>';
}
document.querySelectorAll('.tabs button').forEach(b=>b.onclick=()=>{document.querySelector('.tabs .on').classList.remove('on');b.classList.add('on');show(b.dataset.k)});
show('mindset');

document.querySelector('.nl form').onsubmit=e=>{e.preventDefault();e.target.innerHTML='<p style="color:var(--ac); font-weight:bold;">Đã gửi thành công! Cảm ơn bạn.</p>'};
</script>
</body>
</html>
