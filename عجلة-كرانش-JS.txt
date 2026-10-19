(function(){
if(window.__crWheel)return;window.__crWheel=1;
var WA='966547495503',LINK='https://crunsh5.com/p591608085',KEY='crunshWheel1';
var P=[
{t:'خصم 5%',s:'خصم 5%',w:26,c:'SHEIKH5'},
{t:'كود سناب يوم',s:'سناب يوم',w:18,c:'WIN-SNAP1',g:1},
{t:'250 متابع',s:'250 متابع',w:12,c:'WIN-F250',g:1},
{t:'رصيد 20 ريال',s:'رصيد 20 ر.س',w:4,c:'WIN-W20',g:1},
{t:'خصم 10%',s:'خصم 10%',w:16,c:'SHEIKH10'},
{t:'كود سناب أسبوع',s:'سناب أسبوع',w:12,c:'WIN-SNAP7',g:1},
{t:'10 آلاف مشاهدة',s:'10 آلاف مشاهدة',w:10,c:'WIN-V10K',g:1},
{t:'اشتراك جيميناي',s:'جيميناي',w:2,c:'WIN-GEM',g:1}];
var COL=['#F88818','#1a1f20','#1B9AA0','#26292b','#d96b00','#14383a','#e07a10','#202426'];
var css='.crw-fab{position:fixed;left:16px;bottom:255px;z-index:11;width:52px;height:52px;border-radius:50%;border:0;padding:0;background:linear-gradient(160deg,#F88818,#d96b00);box-shadow:0 8px 22px rgba(248,136,24,.5);cursor:pointer;display:flex;align-items:center;justify-content:center;transition:bottom .2s}'+
'.crw-fab svg{width:30px;height:30px;animation:crwspin 6s linear infinite}@keyframes crwspin{to{transform:rotate(360deg)}}'+
'.crw-fab::after{content:"لف واربح";position:absolute;bottom:58px;left:50%;transform:translateX(-50%);white-space:nowrap;background:#131313;color:#F88818;border:1px solid rgba(248,136,24,.5);font:700 11px/1 inherit;font-family:inherit;padding:5px 8px;border-radius:8px}'+
'.crw-fab::before{content:"";position:absolute;top:2px;right:2px;width:10px;height:10px;border-radius:50%;background:#1B9AA0;box-shadow:0 0 0 0 rgba(27,154,160,.7);animation:crwp 1.6s infinite}@keyframes crwp{to{box-shadow:0 0 0 10px rgba(27,154,160,0)}}'+
'.crw-ov{position:fixed;inset:0;z-index:2147483000;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,.72);padding:16px;direction:rtl;font-family:inherit}.crw-ov.on{display:flex}'+
'.crw-box{position:relative;width:min(380px,100%);max-height:calc(100vh - 32px);overflow-y:auto;background:radial-gradient(circle at 80% 0%,rgba(248,136,24,.22),transparent 55%),radial-gradient(circle at 0% 100%,rgba(27,154,160,.22),transparent 55%),#0d1112;border:1px solid rgba(248,136,24,.35);border-radius:24px;padding:22px 18px 20px;text-align:center;color:#fff;box-shadow:0 20px 60px rgba(0,0,0,.6)}'+
'.crw-x{position:absolute;top:10px;left:12px;width:32px;height:32px;border-radius:50%;border:1px solid rgba(255,255,255,.15);background:transparent;color:#fff;font-size:18px;cursor:pointer;line-height:1}'+
'.crw-h{font-weight:900;font-size:24px;line-height:1.3;margin:4px 0 4px}.crw-h em{font-style:normal;color:#F88818}'+
'.crw-s{font-size:13px;color:rgba(255,255,255,.78);margin:0 0 14px;line-height:1.7}'+
'.crw-wrap{position:relative;width:min(300px,76vw);aspect-ratio:1;margin:0 auto}'+
'.crw-wheel{width:100%;height:100%;border-radius:50%;transition:transform 4.6s cubic-bezier(.12,.75,.12,1);box-shadow:0 0 0 6px #1a1f20,0 0 0 8px #F88818,0 0 30px rgba(248,136,24,.45)}'+
'.crw-ptr{position:absolute;top:-10px;left:50%;transform:translateX(-50%);width:0;height:0;border-left:14px solid transparent;border-right:14px solid transparent;border-top:26px solid #fff;z-index:2}'+
'.crw-hub{position:absolute;inset:0;margin:auto;width:58px;height:58px;border-radius:50%;background:#131313;border:3px solid #F88818;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:13px;color:#F88818}'+
'.crw-btn{margin-top:18px;width:100%;height:50px;border:0;border-radius:14px;background:#F88818;color:#131313;font-family:inherit;font-weight:800;font-size:17px;cursor:pointer}.crw-btn:disabled{opacity:.55;cursor:default}'+
'.crw-res{display:none;margin-top:16px;padding:14px;border-radius:16px;background:rgba(27,154,160,.12);border:1px dashed #1B9AA0}.crw-res.on{display:block}'+
'.crw-res b{display:block;font-size:19px;margin-bottom:6px}'+
'.crw-code{display:inline-block;margin:6px 0;padding:8px 16px;border-radius:10px;background:#131313;border:1px solid rgba(248,136,24,.5);font-family:monospace;font-size:18px;color:#F88818;letter-spacing:1px;cursor:pointer;direction:ltr}'+
'.crw-how{font-size:12.5px;color:rgba(255,255,255,.8);line-height:1.7;margin:6px 0 10px}'+
'.crw-go,.crw-wa{display:block;border-radius:12px;text-decoration:none;font-weight:800}.crw-go{height:44px;line-height:44px;background:#1B9AA0;color:#fff!important}'+
'.crw-wa{display:none;margin-top:8px;height:42px;line-height:42px;border:1.5px solid #25D366;color:#25D366!important;font-size:14px}.crw-wa.on{display:block}'+
'.crw-fine{font-size:10.5px;color:rgba(255,255,255,.5);margin-top:10px;line-height:1.6}';
var st=document.createElement('style');st.textContent=css;document.head.appendChild(st);
var fab=document.createElement('button');fab.type='button';fab.className='crw-fab';fab.setAttribute('aria-label','لف واربح');
fab.innerHTML='<svg viewBox="0 0 24 24" fill="none" stroke="#131313" stroke-width="2"><circle cx="12" cy="12" r="9"/><path d="M12 3v18M3 12h18M5.6 5.6l12.8 12.8M18.4 5.6 5.6 18.4"/></svg>';
var ov=document.createElement('div');ov.className='crw-ov';ov.setAttribute('role','dialog');
ov.innerHTML='<div class="crw-box"><button class="crw-x" type="button" aria-label="إغلاق">×</button><div class="crw-h">هدية مع <em>باقة الشيوخ</em> 🎁</div><p class="crw-s">لف العجلة واختار هديتك… كل لفة فيها جائزة<br>وتستلمها مع طلبك لباقة الشيوخ</p><div class="crw-wrap"><div class="crw-ptr"></div><canvas class="crw-wheel" width="600" height="600"></canvas><div class="crw-hub">كرانش</div></div><button class="crw-btn" type="button">لف الحين</button><div class="crw-res"><b></b><div class="crw-code"></div><div class="crw-how"></div><a class="crw-go" href="'+LINK+'">اطلب باقة الشيوخ واستلم هديتك</a><a class="crw-wa" target="_blank" rel="noopener" href="#">💬 تواصل مع الدعم لاستلام هديتك</a><div class="crw-fine">الهدية تُصرف مع طلب باقة الشيوخ فقط · لفة وحدة لكل زائر · بدون أي رسوم إضافية</div></div></div>';
document.body.appendChild(fab);document.body.appendChild(ov);
var cv=ov.querySelector('canvas'),x=cv.getContext('2d'),n=P.length,a=2*Math.PI/n,ff=getComputedStyle(document.body).fontFamily;
function draw(){x.clearRect(0,0,600,600);for(var i=0;i<n;i++){x.beginPath();x.moveTo(300,300);x.arc(300,300,296,-Math.PI/2+i*a,-Math.PI/2+(i+1)*a);x.closePath();x.fillStyle=COL[i];x.fill();x.strokeStyle='rgba(255,255,255,.12)';x.lineWidth=2;x.stroke();x.save();x.translate(300,300);var g=-Math.PI/2+i*a+a/2;x.rotate(g);x.direction='rtl';x.textAlign='center';x.fillStyle=(i%2==0&&i!=2)?'#131313':'#fff';x.font='700 26px '+ff;if(Math.cos(g)<-0.01){x.rotate(Math.PI);x.fillText(P[i].s,-178,9)}else{x.fillText(P[i].s,178,9)}x.restore()}}
draw();if(document.fonts&&document.fonts.ready)document.fonts.ready.then(draw);
var btn=ov.querySelector('.crw-btn'),res=ov.querySelector('.crw-res'),wa=ov.querySelector('.crw-wa'),rot=0,cur=0;
function saved(){try{return JSON.parse(localStorage.getItem(KEY))}catch(e){return null}}
function show(i){var p=P[i];cur=i;res.querySelector('b').textContent='مبروك! فزت بـ '+p.t+' 🎉';res.querySelector('.crw-code').textContent=p.c;res.querySelector('.crw-how').textContent=p.g?'اطلب باقة الشيوخ، وبعدها تواصل مع الدعم على الواتساب وأرسل الكود ورقم طلبك، وتستلم هديتك.':'اكتب الكود في السلة وقت طلب باقة الشيوخ.';if(p.g){wa.href='https://wa.me/'+WA+'?text='+encodeURIComponent('هلا، فزت بـ '+p.t+' من عجلة كرانش 🎁\nكود الهدية: '+p.c+'\nرقم طلب باقة الشيوخ: ');wa.classList.add('on')}else wa.classList.remove('on');res.classList.add('on');btn.disabled=true;btn.textContent='لفّيت وفزت ✓';try{res.scrollIntoView({block:'end',behavior:'smooth'})}catch(e){}}
fab.onclick=function(){ov.classList.add('on');var s=saved();if(s){rot=s.r;cv.style.transition='none';cv.style.transform='rotate('+rot+'deg)';show(s.i)}};
ov.querySelector('.crw-x').onclick=function(){ov.classList.remove('on')};
ov.onclick=function(e){if(e.target===ov)ov.classList.remove('on')};
res.querySelector('.crw-code').onclick=function(){var t=this;try{navigator.clipboard.writeText(P[cur].c)}catch(e){}t.textContent='تم النسخ ✓';setTimeout(function(){t.textContent=P[cur].c},1200)};
btn.onclick=function(){if(btn.disabled)return;btn.disabled=true;var tot=0,i,r;for(i=0;i<n;i++)tot+=P[i].w;r=Math.random()*tot;for(i=0;i<n;i++){r-=P[i].w;if(r<0)break}var mid=i*360/n+180/n,j=(Math.random()-.5)*(360/n)*.6;rot=rot+2160+((360-mid-j)-(rot%360)+360)%360;cv.style.transition='';cv.style.transform='rotate('+rot+'deg)';setTimeout(function(){show(i);try{localStorage.setItem(KEY,JSON.stringify({i:i,r:rot}))}catch(e){}},4700)};
function place(){var w=document.getElementById('wa-angel');if(w){var r=w.getBoundingClientRect();if(r.height){fab.style.left=Math.round(r.left+(r.width-52)/2)+'px';fab.style.bottom=Math.round(innerHeight-r.top+50)+'px';return}}fab.style.left='16px';fab.style.bottom='255px'}
place();addEventListener('resize',place);addEventListener('scroll',place,{passive:true});setInterval(place,1000);
})();
