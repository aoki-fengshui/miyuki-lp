<!DOCTYPE html><html lang="ja"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1.0"><title>風水師 青木美由紀</title>
<link href="https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@400;600&family=Noto+Sans+JP:wght@300;400&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{--cr:#FAF7F2;--iv:#F3EDE3;--sg:#8A9E89;--sgl:#C5D4C4;--sgp:#EBF0EA;--br:#7A6355;--gd:#C4A96B;--gdl:#E8D9B5;--td:#3A3330;--tm:#6B5F58;--tl:#9C9189;--wh:#FFFFFF}
html{scroll-behavior:smooth}
body{font-family:'Noto Sans JP',sans-serif;font-weight:300;color:var(--td);background:var(--cr);line-height:1.9;font-size:15px}
.sr{font-family:'Shippori Mincho',serif}
section{padding:72px 24px}
.inn{max-width:860px;margin:0 auto}
.inw{max-width:1100px;margin:0 auto}
.slb{font-family:'Shippori Mincho',serif;font-size:11px;letter-spacing:.25em;color:var(--sg);margin-bottom:10px}
.stl{font-family:'Shippori Mincho',serif;font-size:clamp(20px,4vw,28px);font-weight:600;line-height:1.6;margin-bottom:28px}
.div{width:48px;height:1px;background:var(--gd);margin:0 auto 36px}
.divl{width:48px;height:1px;background:var(--gd);margin:0 0 36px}
.ph{background:linear-gradient(135deg,var(--iv),var(--sgp));border:1px dashed var(--sgl);display:flex;flex-direction:column;align-items:center;justify-content:center;color:var(--tl);font-size:12px;gap:6px;height:100%}
/* header */
header{position:fixed;top:0;left:0;right:0;z-index:100;padding:16px 32px;display:flex;align-items:center;justify-content:space-between;background:rgba(250,247,242,.95);backdrop-filter:blur(8px);border-bottom:1px solid rgba(196,169,107,.2)}
.logo{font-family:'Shippori Mincho',serif;font-size:15px;color:var(--td);letter-spacing:.1em}
.logo span{color:var(--sg);font-size:10px;display:block;letter-spacing:.2em}
.hbtn{font-size:12px;letter-spacing:.12em;color:#fff;background:var(--sg);border:none;padding:10px 22px;border-radius:30px;cursor:pointer;text-decoration:none;transition:background .3s}
.hbtn:hover{background:var(--br)}
/* hero */
#hero{padding-top:110px;padding-bottom:0;min-height:100vh;display:flex;flex-direction:column;justify-content:center;position:relative;overflow:hidden}
.hbg{position:absolute;inset:0;background:radial-gradient(ellipse 60% 50% at 70% 40%,rgba(197,212,196,.25),transparent 70%),var(--cr);z-index:0}
.hinn{position:relative;z-index:1;max-width:1100px;margin:0 auto;padding:0 24px 72px;display:grid;grid-template-columns:1fr 400px;gap:56px;align-items:center}
.hph{width:100%;aspect-ratio:4/5;border-radius:200px 200px 0 0;overflow:hidden}
.hcs{font-family:'Shippori Mincho',serif;font-size:13px;color:var(--sg);letter-spacing:.2em;margin-bottom:18px;display:flex;align-items:center;gap:10px}
.hcs::before{content:'';display:block;width:28px;height:1px;background:var(--sg)}
.htg{font-family:'Shippori Mincho',serif;font-size:13px;color:var(--br);background:var(--gdl);display:inline-block;padding:5px 14px;border-radius:2px;letter-spacing:.12em;margin-bottom:20px}
.hc{font-family:'Shippori Mincho',serif;font-size:clamp(22px,4vw,36px);font-weight:600;line-height:1.65;margin-bottom:22px}
.hc em{font-style:normal;color:var(--sg)}
.hs{font-size:13px;color:var(--tm);line-height:2;margin-bottom:36px;border-left:2px solid var(--gd);padding-left:14px}
.cta{display:inline-flex;align-items:center;gap:10px;font-family:'Shippori Mincho',serif;font-size:15px;letter-spacing:.1em;color:#fff;background:linear-gradient(135deg,var(--sg),#6d8a6c);border:none;padding:16px 36px;border-radius:50px;cursor:pointer;text-decoration:none;box-shadow:0 8px 28px rgba(138,158,137,.3);transition:transform .2s,box-shadow .2s}
.cta:hover{transform:translateY(-2px);box-shadow:0 12px 36px rgba(138,158,137,.4)}
/* concern */
#concern{background:var(--iv)}
.cgr{display:grid;grid-template-columns:1fr 1fr;gap:44px;align-items:start}
.cph{width:100%;aspect-ratio:4/5;border-radius:8px;overflow:hidden}
.cl{list-style:none;margin-bottom:32px}
.cl li{display:flex;align-items:flex-start;gap:10px;padding:12px 0;border-bottom:1px solid rgba(196,169,107,.2);font-size:14px;color:var(--tm);line-height:1.8}
.cl li::before{content:'…';color:var(--gd);flex-shrink:0;font-size:16px}
.fb{background:var(--wh);border-radius:10px;padding:24px;border:1px solid var(--sgl)}
.ft{font-family:'Shippori Mincho',serif;font-size:14px;color:var(--sg);margin-bottom:16px;display:flex;align-items:center;gap:8px}
.ft::before{content:'✦';color:var(--gd)}
.fl{list-style:none}
.fl li{display:flex;gap:8px;font-size:13px;color:var(--td);line-height:1.8;margin-bottom:10px}
.fl li::before{content:'◎';color:var(--sg);flex-shrink:0;font-size:11px;margin-top:4px}
/* concept */
#concept{background:var(--cr)}
.coin{display:grid;grid-template-columns:360px 1fr;gap:56px;align-items:center}
.coph{width:100%;aspect-ratio:3/4;border-radius:8px;overflow:hidden}
.cld{font-family:'Shippori Mincho',serif;font-size:clamp(16px,2.5vw,20px);font-weight:600;line-height:1.8;margin-bottom:24px}
.cld span{border-bottom:2px solid var(--gd);padding-bottom:2px}
.cb{font-size:14px;color:var(--tm);line-height:2.1;margin-bottom:20px}
.cn{background:var(--sgp);border-left:3px solid var(--sg);padding:14px 18px;font-family:'Shippori Mincho',serif;font-size:14px;color:var(--br);line-height:1.9;border-radius:0 4px 4px 0}
/* voice */
#voice{background:var(--iv)}
.vgr{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:36px}
.vc{background:var(--wh);border-radius:10px;padding:24px;border:1px solid rgba(196,169,107,.2);position:relative}
.vc::before{content:'"';font-family:'Shippori Mincho',serif;font-size:54px;color:var(--gdl);position:absolute;top:10px;left:18px;line-height:1}
.ve{min-height:140px;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:6px;color:var(--tl);font-size:12px;letter-spacing:.08em}
.vm{margin-top:16px;padding-top:10px;border-top:1px solid var(--iv);font-size:11px;color:var(--tl)}
/* menu */
#menu{background:var(--cr)}
.mgr{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-bottom:28px}
.mc{background:var(--wh);border-radius:10px;padding:32px 24px;border:1px solid rgba(196,169,107,.2);text-align:center;transition:transform .3s,box-shadow .3s}
.mc:hover{transform:translateY(-4px);box-shadow:0 14px 40px rgba(138,158,137,.15)}
.mi{font-size:30px;margin-bottom:14px}
.mn{font-family:'Shippori Mincho',serif;font-size:16px;font-weight:600;margin-bottom:10px;line-height:1.6}
.mt{font-size:12px;color:var(--tl);line-height:1.9;margin-bottom:20px;text-align:left}
.mp{font-family:'Shippori Mincho',serif;font-size:22px;color:var(--sg);font-weight:600;padding:10px 0;border-top:1px solid var(--iv);border-bottom:1px solid var(--iv)}
.mp span{font-size:12px;color:var(--tl);font-family:'Noto Sans JP',sans-serif;font-weight:300}
.mno{text-align:center;font-size:12px;color:var(--tl);background:var(--sgp);padding:12px 18px;border-radius:8px;line-height:1.9}
/* profile */
#profile{background:var(--iv)}
.prin{display:grid;grid-template-columns:280px 1fr;gap:56px;align-items:start}
.prph{width:100%;aspect-ratio:3/4;border-radius:8px;overflow:hidden}
.prn{font-family:'Shippori Mincho',serif;font-size:24px;font-weight:600;margin-bottom:4px}
.prne{font-size:11px;color:var(--tl);letter-spacing:.2em;margin-bottom:6px}
.prr{font-size:13px;color:var(--sg);letter-spacing:.1em;margin-bottom:28px;padding-bottom:20px;border-bottom:1px solid var(--gdl)}
.prb{font-size:14px;color:var(--tm);line-height:2.1;margin-bottom:24px}
.prp{list-style:none;display:flex;flex-wrap:wrap;gap:8px}
.prp li{font-size:12px;color:var(--br);background:var(--gdl);padding:5px 12px;border-radius:30px}
/* flow */
#flow{background:var(--cr)}
.fs{display:grid;grid-template-columns:repeat(4,1fr);position:relative;margin-top:36px}
.fs::before{content:'';position:absolute;top:34px;left:10%;right:10%;height:1px;background:linear-gradient(to right,var(--sgl),var(--gdl),var(--sgl));z-index:0}
.fst{text-align:center;padding:0 14px;position:relative;z-index:1}
.fn{width:68px;height:68px;border-radius:50%;background:var(--wh);border:2px solid var(--sgl);margin:0 auto 18px;display:flex;flex-direction:column;align-items:center;justify-content:center}
.fnl{font-size:9px;color:var(--sg);letter-spacing:.08em}
.fnn{font-family:'Shippori Mincho',serif;font-size:20px;color:var(--td);font-weight:600;line-height:1}
.fti{font-family:'Shippori Mincho',serif;font-size:13px;color:var(--td);font-weight:600;margin-bottom:6px}
.fd{font-size:12px;color:var(--tl);line-height:1.8}
/* faq */
#faq{background:var(--iv)}
.fql{max-width:660px;margin:0 auto}
.fqi{border-bottom:1px solid rgba(196,169,107,.2);overflow:hidden}
.fqq{display:flex;align-items:flex-start;gap:14px;padding:20px 0;cursor:pointer;font-family:'Shippori Mincho',serif;font-size:15px;color:var(--td);font-weight:600;line-height:1.7;user-select:none}
.qm{flex-shrink:0;width:26px;height:26px;background:var(--sg);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;margin-top:2px}
.ch{margin-left:auto;flex-shrink:0;color:var(--tl);transition:transform .3s;font-style:normal;font-size:17px}
.fqi.open .ch{transform:rotate(180deg)}
.fqa{display:none;padding:0 0 20px 40px;font-size:14px;color:var(--tm);line-height:2}
.fqi.open .fqa{display:block}
/* cta */
#cta{background:linear-gradient(160deg,#E8EDEB,#F3EDE3 50%,#EDF0EB);text-align:center;padding:90px 24px;position:relative;overflow:hidden}
.ctl{font-family:'Shippori Mincho',serif;font-size:clamp(19px,3.5vw,28px);font-weight:600;line-height:1.7;margin-bottom:10px}
.cts{font-size:13px;color:var(--tm);margin-bottom:48px;line-height:2}
.fb2{max-width:540px;margin:0 auto;background:var(--wh);border-radius:14px;padding:44px 36px;box-shadow:0 14px 56px rgba(0,0,0,.06);text-align:left}
.fg{margin-bottom:22px}
.fl2{display:block;font-size:13px;color:var(--tm);margin-bottom:7px}
.fl2 .rq{font-size:10px;color:var(--sg);background:var(--sgp);padding:1px 6px;border-radius:3px;margin-left:5px}
.fi,.fse,.fta{width:100%;padding:11px 14px;border:1px solid rgba(196,169,107,.3);border-radius:6px;font-family:'Noto Sans JP',sans-serif;font-size:14px;font-weight:300;color:var(--td);background:var(--cr);outline:none;transition:border-color .2s;appearance:none}
.fi:focus,.fse:focus,.fta:focus{border-color:var(--sg);background:var(--wh)}
.fta{min-height:90px;resize:vertical}
.fsb{width:100%;font-family:'Shippori Mincho',serif;font-size:15px;letter-spacing:.15em;color:#fff;background:linear-gradient(135deg,var(--sg),#6d8a6c);border:none;padding:17px;border-radius:50px;cursor:pointer;box-shadow:0 8px 28px rgba(138,158,137,.3);transition:transform .2s,box-shadow .2s;margin-top:6px}
.fsb:hover{transform:translateY(-2px);box-shadow:0 12px 36px rgba(138,158,137,.4)}
/* footer */
footer{background:var(--td);color:rgba(255,255,255,.5);text-align:center;padding:36px 24px;font-size:12px;letter-spacing:.1em}
.fn2{font-family:'Shippori Mincho',serif;font-size:15px;color:rgba(255,255,255,.8);margin-bottom:8px;letter-spacing:.2em}
.sl{display:flex;justify-content:center;gap:18px;margin-bottom:16px}
.sl a{color:rgba(255,255,255,.5);text-decoration:none;font-size:12px;transition:color .2s}
.sl a:hover{color:var(--gdl)}
@media(max-width:768px){
.hinn,.cgr,.coin,.prin{grid-template-columns:1fr}
.hph{order:-1;max-width:260px;margin:0 auto}
.mgr,.vgr{grid-template-columns:1fr}
.fs{grid-template-columns:1fr 1fr;gap:28px}
.fs::before{display:none}
.fb2{padding:32px 20px}
header{padding:13px 18px}
}
</style></head><body>
<header>
<div class="logo sr">青木美由紀<span>FENG SHUI PRACTITIONER</span></div>
<a href="#cta" class="hbtn sr">鑑定を申し込む</a>
</header>
 
<section id="hero">
<div class="hbg"></div>
<div class="hinn">
<div>
<p class="hcs sr">住まいを整えると、人生が動き出す</p>
<p class="htg sr">20回の引っ越し経験を持つ風水師</p>
<h1 class="hc sr">なんとなく落ち着かないのは、<br><em>家のせい</em>かもしれません。</h1>
<p class="hs">引っ越し前のご相談から、今の暮らしの見直しまで。<br>あなたの住まいの力を、一緒に引き出しませんか。</p>
<a href="#cta" class="cta sr">風水鑑定を申し込む →</a>
</div>
<div class="hph"><div class="ph"><span style="font-size:26px">🏡</span><span>【写真①】</span><span style="font-size:11px;opacity:.7">光差し込む清潔なリビング</span></div></div>
</div>
</section>
 
<section id="concern">
<div class="inw">
<div class="cgr">
<div>
<p class="slb">for you</p>
<h2 class="stl sr">毎日の暮らしで、<br>こんな風に感じることはありませんか？</h2>
<div class="divl"></div>
<ul class="cl">
<li>今の家に不満はないのに、なぜか落ち着かない</li>
<li>仕事から帰ってきても、なぜかゆっくりできない</li>
<li>引っ越し先を内見しても、決め手がわからない</li>
<li>家のどこから整えたらいいのか、分からない</li>
<li>仕事も暮らしも、なんとなく流れが滞っている気がする</li>
<li>片付けても片付けても、なぜかまたすぐ乱れる</li>
<li>風水は気になるけれど、難しそうで踏み出せない</li>
</ul>
<div class="fb">
<p class="ft sr">風水鑑定を受けると、こう変わります</p>
<ul class="fl">
<li>家が「一番のパワースポット」になり、疲れが取れやすくなる</li>
<li>自分に合った物件選びの基準がわかり、安心して新生活を送れる</li>
<li>整える優先順位がわかり、片付けや掃除が楽しくなる</li>
<li>空間が整うことで、気持ちも仕事もスムーズに回り出す</li>
</ul>
</div>
</div>
<div class="cph"><div class="ph"><span style="font-size:26px">🪴</span><span>【写真③】</span><span style="font-size:11px;opacity:.7">植物・窓を開けるイメージ</span></div></div>
</div>
</div>
</section>
 
<section id="concept">
<div class="inw">
<div class="coin">
<div class="coph"><div class="ph"><span style="font-size:26px">🧭</span><span>【写真④】</span><span style="font-size:11px;opacity:.7">羅盤・図面を見る柔らかい表情</span></div></div>
<div>
<p class="slb">philosophy</p>
<h2 class="stl sr">「不安」をあおらず、<br>「安心」して整えられる風水を。</h2>
<div class="divl"></div>
<p class="cld sr">私が大切にしているのは、<br><span>今の暮らしに無理なく活かせる風水</span>です。</p>
<p class="cb">方位だけを見て家を責めたり、高価な開運グッズを押し付けたりはしません。「高価なものを買ってください」とは、一切お伝えしません。</p>
<p class="cb">本格的な技法（フライングスター風水）を使いつつ、私自身の20回に及ぶ引っ越し経験から得た「リアルな心地よさ」を大切にしています。あなたの住まいの良さを活かしながら、より心地よく過ごせる整え方を一緒に見つけていきます。</p>
<div class="cn sr">「何を変えたらいいか分からない」という方も、<br>どうぞ気軽にご相談ください。</div>
</div>
</div>
</div>
</section>
 
<section id="voice">
<div class="inw">
<p class="slb" style="text-align:center">voice</p>
<h2 class="stl sr" style="text-align:center">お客様の声</h2>
<div class="div"></div>
<div class="vgr">
<div class="vc"><div class="ve"><span style="font-size:22px;opacity:.4">💬</span><span>【お客様の声①】</span><span style="font-size:11px">引っ越し・物件選び系の声</span></div><div class="vm">― お名前（匿名可）｜メニュー名</div></div>
<div class="vc"><div class="ve"><span style="font-size:22px;opacity:.4">💬</span><span>【お客様の声②】</span><span style="font-size:11px">今の住まいを整えた系の声</span></div><div class="vm">― お名前（匿名可）｜メニュー名</div></div>
<div class="vc"><div class="ve"><span style="font-size:22px;opacity:.4">💬</span><span>【お客様の声③】</span><span style="font-size:11px">「最初は不安だったけど…」系の声</span></div><div class="vm">― お名前（匿名可）｜メニュー名</div></div>
</div>
</div>
</section>
 
<section id="menu">
<div class="inw">
<p class="slb" style="text-align:center">menu &amp; price</p>
<h2 class="stl sr" style="text-align:center">鑑定メニュー・料金</h2>
<div class="div"></div>
<div class="mgr">
<div class="mc"><div class="mi">🏠</div><div class="mn sr">住まいの<br>風水鑑定</div><p class="mt">今のお住まいをもっとパワースポットにしたい方、どこから整えるか知りたい方</p><div class="mp sr">◯◯,◯◯◯円<br><span>（税込）</span></div></div>
<div class="mc"><div class="mi">🔑</div><div class="mn sr">引っ越し前の<br>風水相談</div><p class="mt">物件選びで迷っている方、新生活を最高の流れでスタートさせたい方</p><div class="mp sr">◯◯,◯◯◯円<br><span>（税込）</span></div></div>
<div class="mc"><div class="mi">🪴</div><div class="mn sr">自宅兼仕事場・サロンの<br>風水鑑定</div><p class="mt">暮らしと仕事どちらも整えたい方、お客様を迎える空間を整えたい方</p><div class="mp sr">◯◯,◯◯◯円<br><span>（税込）</span></div></div>
</div>
<p class="mno">※ 鑑定内容や広さによって異なる場合があります。事前にお見積もりをお出ししますので、ご安心ください。</p>
</div>
</section>
 
<section id="profile">
<div class="inw">
<div class="prin">
<div class="prph"><div class="ph"><span style="font-size:26px">🌿</span><span>【写真⑤】</span><span style="font-size:11px;opacity:.7">プロフィールのメイン写真</span></div></div>
<div>
<p class="slb">profile</p>
<div class="divl"></div>
<h2 class="prn sr">青木美由紀</h2>
<p class="prne">AOKI MIYUKI</p>
<p class="prr">風水師 / カフェ店長</p>
<p class="prb">家や間取り、インテリアが大好きで、これまでに20回以上の引っ越しを経験。さまざまな住環境を体感してきました。<br><br>多くの職業・職種を経験ののち、2017年より本格的に風水師として活動を開始。九州・東京の2拠点で、会社経営者宅・著名人宅をはじめ、一般家庭のお宅やサロンなど幅広い鑑定を行っています。<br><br>風水を特別なものではなく、日々の暮らしに自然になじむ知恵としてお伝えしています。</p>
<ul class="prp">
<li>20回以上の引っ越し経験</li><li>フライングスター風水</li><li>2017年〜本格活動</li><li>九州・東京2拠点</li><li>経営者宅・著名人宅の鑑定実績</li><li>執筆活動中</li>
</ul>
</div>
</div>
</div>
</section>
 
<section id="flow">
<div class="inw">
<p class="slb" style="text-align:center">how to start</p>
<h2 class="stl sr" style="text-align:center">お申し込みの流れ</h2>
<div class="div"></div>
<div class="fs">
<div class="fst"><div class="fn"><span class="fnl">STEP</span><span class="fnn sr">1</span></div><p class="fti sr">お申し込み</p><p class="fd">下記フォームより必要事項をお送りください。</p></div>
<div class="fst"><div class="fn"><span class="fnl">STEP</span><span class="fnn sr">2</span></div><p class="fti sr">日程調整・ヒアリング</p><p class="fd">2日以内にご連絡し、鑑定日を決定します。</p></div>
<div class="fst"><div class="fn"><span class="fnl">STEP</span><span class="fnn sr">3</span></div><p class="fti sr">資料のご提出</p><p class="fd">間取り図やお部屋の写真をお送りください。スマホ撮影でOKです。</p></div>
<div class="fst"><div class="fn"><span class="fnl">STEP</span><span class="fnn sr">4</span></div><p class="fti sr">鑑定・結果のご案内</p><p class="fd">オンラインまたは対面にて、わかりやすくお伝えします。</p></div>
</div>
</div>
</section>
 
<section id="faq">
<div class="inn">
<p class="slb" style="text-align:center">faq</p>
<h2 class="stl sr" style="text-align:center">よくある質問</h2>
<div class="div"></div>
<div class="fql">
<div class="fqi"><div class="fqq sr" onclick="t(this)"><span class="qm">Q</span>風水に詳しくなくても大丈夫ですか？<em class="ch">∨</em></div><div class="fqa">はい、もちろんです。専門用語を使わず、どなたでも分かる言葉でお伝えします。</div></div>
<div class="fqi"><div class="fqq sr" onclick="t(this)"><span class="qm">Q</span>賃貸でも見てもらえますか？<em class="ch">∨</em></div><div class="fqa">はい。家具の配置やカーテンの色など、賃貸でもできることはたくさんあります。</div></div>
<div class="fqi"><div class="fqq sr" onclick="t(this)"><span class="qm">Q</span>家具を全部買い替えないといけませんか？<em class="ch">∨</em></div><div class="fqa">その必要はありません。今あるものを大切にしながら、より良い配置をご提案します。</div></div>
<div class="fqi"><div class="fqq sr" onclick="t(this)"><span class="qm">Q</span>無理な勧誘やグッズ販売はありますか？<em class="ch">∨</em></div><div class="fqa">一切ございませんので、ご安心ください。</div></div>
<div class="fqi"><div class="fqq sr" onclick="t(this)"><span class="qm">Q</span>一度相談だけでもできますか？<em class="ch">∨</em></div><div class="fqa">もちろんです。「まず話を聞いてみたい」という段階でも、どうぞお気軽にお申し込みください。</div></div>
</div>
</div>
</section>
 
<section id="cta">
<div class="inn">
<p class="slb" style="text-align:center">contact</p>
<h2 class="ctl sr">住まいを整えることは、<br>毎日の自分を慈しむこと。</h2>
<p class="cts">あなたの新しい一歩を、精一杯サポートさせていただきます。</p>
<div class="fb2">
<div class="fg"><label class="fl2">お名前<span class="rq">必須</span></label><input type="text" class="fi" placeholder="青木 美由紀"></div>
<div class="fg"><label class="fl2">メールアドレス<span class="rq">必須</span></label><input type="email" class="fi" placeholder="example@email.com"></div>
<div class="fg"><label class="fl2">ご希望のメニュー<span class="rq">必須</span></label>
<select class="fse"><option value="">選択してください</option><option>住まいの風水鑑定</option><option>引っ越し前の風水相談</option><option>自宅兼仕事場・サロンの風水鑑定</option><option>まずは相談だけしたい</option></select></div>
<div class="fg"><label class="fl2">ご相談内容（任意）</label><textarea class="fta" placeholder="お気軽にお書きください。"></textarea></div>
<button class="fsb sr" type="button">この内容で申し込む →</button>
</div>
</div>
</section>
 
<footer>
<p class="fn2 sr">青木美由紀｜風水師</p>
<div class="sl"><a href="#" target="_blank">Instagram</a><a href="#" target="_blank">note</a><a href="#" target="_blank">Ameblo</a></div>
<p>© 青木美由紀 All Rights Reserved.</p>
</footer>
<script>function t(e){e.parentElement.classList.toggle('open')}</script>
</body></html>
