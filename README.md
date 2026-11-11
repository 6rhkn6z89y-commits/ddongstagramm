[index 2.html](https://github.com/user-attachments/files/34689144/index.2.html)
<!DOCTYPE html>
<html lang="ko"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>똥스타그램</title>
<link href="https://fonts.googleapis.com/css2?family=Grand+Hotel&display=swap" rel="stylesheet">
<style>
:root{--bg:#fafafa;--card:#fff;--tx:#262626;--mu:#8e8e8e;--bd:#dbdbdb;--bl:#0095f6;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#000;--card:#121212;--tx:#f5f5f5;--mu:#a8a8a8;--bd:#2b2b2b}}
:root[data-theme="dark"]{--bg:#000;--card:#121212;--tx:#f5f5f5;--mu:#a8a8a8;--bd:#2b2b2b}
html{height:100%;scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font:14px/1.45 -apple-system,"Noto Sans KR",system-ui,sans-serif}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--card);z-index:10}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:5;background:var(--card);border-bottom:1px solid var(--bd);text-align:center;padding:8px}
.logo{font-family:"Grand Hotel","Noto Sans KR",cursive;font-weight:800;font-size:26px;background:linear-gradient(45deg,#f09433,#dc2743,#bc1888);-webkit-background-clip:text;background-clip:text;color:transparent}
.big{font-size:38px;margin-bottom:4px}
#main{max-width:470px;margin:0 auto;padding-bottom:70px}
nav{position:fixed;bottom:0;left:0;right:0;background:var(--card);border-top:1px solid var(--bd);display:flex;justify-content:space-around;padding:6px 0 calc(6px + env(safe-area-inset-bottom,0px));z-index:5}
nav.hide{display:none}
nav button{background:none;border:0;font-size:26px;cursor:pointer;padding:2px 16px}
.auth{display:flex;flex-direction:column;gap:10px;padding:48px 28px;text-align:center}
input,textarea{font-family:inherit;width:100%;padding:11px;border:1px solid var(--bd);border-radius:6px;background:var(--bg);color:var(--tx);font-size:15px}
.pri{background:var(--bl);color:#fff;border:0;border-radius:8px;padding:11px;font-weight:600;font-size:15px;cursor:pointer}
.pri:disabled{opacity:.5}
a{color:var(--bl);cursor:pointer}.err{color:#ed4956;margin:0;min-height:1em}.mu{color:var(--mu)}.empty{text-align:center;color:var(--mu);padding:40px 20px}
.sm{font-size:13px;padding:6px 12px;border:1px solid var(--bd);border-radius:8px;background:none;color:var(--tx);cursor:pointer;font-weight:600}.pri.sm{border:0;background:var(--bl);color:#fff}
.av{border-radius:50%;color:#fff;display:flex;align-items:center;justify-content:center;font-weight:700;flex:none}
.sb{display:flex;gap:12px;overflow-x:auto;padding:12px;background:var(--card);border-bottom:1px solid var(--bd)}
.st{text-align:center;width:64px;flex:none;position:relative;cursor:pointer}
.st small{display:block;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;font-size:11px}
.ring{padding:3px;border-radius:50%;background:linear-gradient(45deg,#f09433,#dc2743,#bc1888);display:inline-flex}
.ring.no{background:var(--bd)}.ring .av{border:2px solid var(--card)}
.plus{position:absolute;right:2px;top:38px;background:var(--bl);color:#fff;border-radius:50%;width:20px;height:20px;line-height:20px;border:2px solid var(--card)}
.card{background:var(--card);border-bottom:1px solid var(--bd);margin-bottom:8px}
.ph{display:flex;align-items:center;gap:8px;padding:8px 12px}.ph b{cursor:pointer;flex:1}.del{color:#ed4956;cursor:pointer;font-size:12px}
.card>img{width:100%;display:block;background:var(--bd)}
.act button{background:none;border:0;font-size:24px;padding:8px 12px;cursor:pointer}
.pad{padding:0 12px 6px}.pad p{margin:2px 0}.cw{display:flex;border-top:1px solid var(--bd);padding:4px 8px}
.cw input{border:0;background:none}.lk{background:none;border:0;color:var(--bl);font-weight:600;cursor:pointer}
.pf{display:flex;gap:20px;align-items:center;padding:20px 16px;background:var(--card)}
.pf h2{margin:0 0 4px;font-size:20px}.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:2px;margin-top:2px}
.grid img{width:100%;aspect-ratio:1;object-fit:cover;cursor:pointer;display:block}
#ov{position:fixed;inset:0;background:rgba(0,0,0,.85);z-index:20;display:flex;align-items:center;justify-content:center;overflow:auto}
.sh{max-height:85vh;overflow:auto;background:var(--card);border-radius:12px;padding:16px;width:min(92vw,400px);display:flex;flex-direction:column;gap:10px;margin:auto}
.sh h3{margin:0;text-align:center}.sh button:not(.pri){background:none;border:0;color:var(--mu);cursor:pointer;padding:6px}
.pv{display:none;width:100%;max-height:50vh;object-fit:contain}
.sv{position:relative;width:min(100vw,480px);height:100%;background:#000;display:flex;align-items:center}
.sv>img{width:100%;max-height:100%;object-fit:contain}
.bars{position:absolute;top:calc(8px + env(safe-area-inset-top,0px));left:8px;right:8px;display:flex;gap:3px}
.bars i{flex:1;height:3px;background:rgba(255,255,255,.35);border-radius:2px}.bars i.on{background:#fff}
.sh2{position:absolute;top:calc(20px + env(safe-area-inset-top,0px));left:10px;right:10px;display:flex;align-items:center;gap:8px;color:#fff}
.sh2 .x{margin-left:auto;cursor:pointer;padding:4px 8px}.sh2 span:not(.x){opacity:.7}.sh2 .x+.x{margin-left:0}
.sb2{position:absolute;left:10px;right:10px;bottom:calc(14px + env(safe-area-inset-bottom,0px));display:flex;gap:8px;align-items:center;color:#fff}
.sb2 input{background:rgba(0,0,0,.5);color:#fff;border:1px solid #fff;border-radius:22px}.sb2 button{background:none;border:0;font-size:28px;cursor:pointer;color:#fff}
.msgs{display:flex;flex-direction:column;gap:6px;padding:10px;min-height:55vh}.m{max-width:75%;padding:8px 12px;border-radius:18px;background:var(--bd);align-self:flex-start;word-break:break-word}
.m.me{align-self:flex-end;background:var(--bl);color:#fff}.m small{display:block;opacity:.7;font-size:11px}
.cr{display:flex;gap:6px;align-items:flex-start;margin:3px 0}.cr.sub{margin-left:28px}.sm2{font-size:11px;color:var(--mu)}
.ch{background:none;border:0;cursor:pointer;font-size:12px;padding:0 4px;color:var(--mu)}
.row{display:flex;gap:18px}.cnt{text-align:center;cursor:pointer}.cnt b{display:block;font-size:16px}.cnt small{color:var(--mu)}
.bio{padding:0 16px 8px;background:var(--card);white-space:pre-wrap}.bt{display:flex;gap:8px;padding:0 16px 12px;background:var(--card)}.bt .sm{flex:1}
.sh .ph .sm{border:1px solid var(--bd);color:var(--tx);padding:6px 12px}.sh .ph .pri.sm{border:0;color:#fff}
</style></head>
<body>
<header><span class="logo">💩 똥스타그램</span></header>
<div id="main"><p class="empty">불러오는 중...</p></div>
<nav class="hide" id="nav"><button onclick="go('feed')">🏠</button><button onclick="go('people')">🔍</button><button onclick="go('inbox')">✉️</button><button onclick="sheet('post')">➕</button><button onclick="go('profile',me)">👤</button></nav>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2.45.4/dist/umd/supabase.min.js"></script>
<script>
// ===== 여기에 Supabase 값을 붙여넣으세요 =====
const SUPABASE_URL="https://jpqstpjskydzsmkoioig.supabase.co";
const SUPABASE_KEY="sb_publishable_cb-RlBlyPSvUrcnik2SnCw_gcib0fpj";
// ============================================
function makeDb(url,key){
  const sb=supabase.createClient(url,key),T=()=>sb.from('docs'),rid=()=>Math.random().toString(36).slice(2)+Date.now().toString(36);
  const docRef=(path)=>{const[col,id]=path.split('/');return{
    async get(){const{data,error}=await T().select('data').eq('col',col).eq('id',id).maybeSingle();if(error)throw error;return{exists:!!data,id,data:()=>data&&data.data}},
    async set(d){const{error}=await T().upsert({col,id,data:d});if(error)throw error},
    async update(d){const s=await this.get();const{error}=await T().upsert({col,id,data:{...(s.data()||{}),...d}});if(error)throw error},
    async delete(){const{error}=await T().delete().eq('col',col).eq('id',id);if(error)throw error}}};
  const colRef=(col,f={w:[],o:null,l:null})=>({
    orderBy(k,dir='asc'){return colRef(col,{...f,o:[k,dir]})},
    limit(n){return colRef(col,{...f,l:n})},
    where(k,op,v){return colRef(col,{...f,w:[...f.w,[k,op,v]]})},
    async get(){const{data,error}=await T().select('id,data').eq('col',col);if(error)throw error;let rows=data;
      for(const[k,op,v]of f.w)rows=rows.filter(r=>op==='>'?r.data[k]>v:op==='<'?r.data[k]<v:r.data[k]===v);
      if(f.o){const[k,d]=f.o;rows.sort((a,b)=>(a.data[k]>b.data[k]?1:-1)*(d==='desc'?-1:1))}
      if(f.l)rows=rows.slice(0,f.l);
      return{docs:rows.map(r=>({id:r.id,data:()=>r.data}))}},
    onSnapshot(cb,eb){const run=()=>this.get().then(cb).catch(eb||console.error);run();
      const ch=sb.channel('c-'+col+'-'+rid()).on('postgres_changes',{event:'*',schema:'public',table:'docs'},p=>{const c=(p.new&&p.new.col)||(p.old&&p.old.col);if(c===col)run()}).subscribe();
      return()=>sb.removeChannel(ch)},
    async add(d){const id=rid();await docRef(col+'/'+id).set(d);return docRef(col+'/'+id)}});
  return{doc:docRef,collection:n=>colRef(n)}
}
const $=s=>document.querySelector(s);
function h(t,a,...c){const e=document.createElement(t);for(const k in a||{}){if(k==='class')e.className=a[k];else if(k.startsWith('on'))e.addEventListener(k.slice(2),a[k]);else e.setAttribute(k,a[k])}for(const x of c.flat())if(x!=null)e.append(x.nodeType?x:document.createTextNode(x));return e}
const store={get(k){try{return localStorage.getItem(k)}catch(e){return null}},set(k,v){try{v==null?localStorage.removeItem(k):localStorage.setItem(k,v)}catch(e){}}};
let db,me=null,P=[],L=[],C=[],S=[],A=[],AC={},R=[],CL=[],SL=[],D=[],q='',view={t:'feed'},rt,stt;
const fr=()=>new Set(R.filter(r=>r.from===me).map(r=>r.to).concat(me));
const err=e=>console.error(e);
async function hash(id,pin){const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode('dung:'+id+':'+pin));return[...new Uint8Array(b)].map(x=>x.toString(16).padStart(2,'0')).join('')}
const col=['#f09433','#e6683c','#dc2743','#cc2366','#bc1888','#405de6','#0095f6','#2ecc71'];
function av(u,sz=32){const p=AC[u]&&AC[u].pic,st='width:'+sz+'px;height:'+sz+'px';
  if(p)return h('img',{class:'av',src:p,style:st+';object-fit:cover'});
  const c=col[[...u].reduce((a,x)=>a+x.charCodeAt(0),0)%col.length];
  return h('div',{class:'av',style:st+';background:'+c+';font-size:'+sz*.45+'px'},u[0].toUpperCase())}
function ago(t){const m=Math.floor((Date.now()-t)/6e4);return m<1?'방금':m<60?m+'분 전':m<1440?Math.floor(m/60)+'시간 전':Math.floor(m/1440)+'일 전'}
function shrink(f,M=720,LIM=200000){return new Promise((ok,no)=>{const i=new Image,u=URL.createObjectURL(f);i.onload=()=>{let m=M,q=.72,d;const cv=document.createElement('canvas');do{const r=Math.min(1,m/Math.max(i.width,i.height));cv.width=i.width*r;cv.height=i.height*r;cv.getContext('2d').drawImage(i,0,0,cv.width,cv.height);d=cv.toDataURL('image/jpeg',q);m*=.85;q*=.92}while(d.length>LIM&&m>100);URL.revokeObjectURL(u);ok(d)};i.onerror=no;i.src=u})}

async function auth(mode,id,pin){
  if(!/^[a-z0-9_.-]{2,20}$/.test(id))return'아이디는 영문 소문자/숫자 2~20자로 해주세요';
  if([...pin].length!==4)return'핀번호는 4자로 해주세요';
  try{
    const r=db.doc('accounts/'+id),s=await r.get(),hp=await hash(id,pin);
    if(mode==='signup'){if(s.exists)return'이미 있는 아이디예요';await r.set({pin:hp,ts:Date.now()})}
    else if(!s.exists||s.data().pin!==hp)return'아이디 또는 핀번호가 틀렸어요';
    store.set('dung_me',id+'|'+hp);start(id)
  }catch(e){err(e);return'오류가 났어요. 다시 시도해줘요'}
}
function authScreen(){
  let mode='login';
  const id=h('input',{placeholder:'아이디 (영문 소문자/숫자)',autocapitalize:'none',maxlength:20}),pin=h('input',{type:'password',placeholder:'핀번호 4자',maxlength:4}),msg=h('p',{class:'err'}),b=h('button',{class:'pri'},'로그인'),sw=h('a',{},'계정이 없나요? 가입하기');
  const run=async()=>{b.disabled=true;const r=await auth(mode,id.value.trim().toLowerCase(),pin.value);if(r){msg.textContent=r;b.disabled=false}};
  b.onclick=run;pin.addEventListener('keydown',e=>{if(e.key==='Enter')run()});
  sw.onclick=()=>{mode=mode==='login'?'signup':'login';b.textContent=mode==='login'?'로그인':'가입하기';sw.textContent=mode==='login'?'계정이 없나요? 가입하기':'이미 계정이 있나요? 로그인'};
  return h('div',{class:'auth'},h('div',{class:'logo big'},'💩 똥스타그램'),h('p',{class:'mu'},'친구들과 사진을 공유해요'),id,pin,msg,b,sw)
}
function start(id){
  me=id;$('#nav').classList.remove('hide');
  db.collection('posts').orderBy('ts','desc').limit(60).onSnapshot(s=>{P=s.docs.map(d=>({id:d.id,...d.data()}));render()},err);
  db.collection('likes').onSnapshot(s=>{L=s.docs.map(d=>d.data());render()},err);
  db.collection('comments').orderBy('ts','asc').onSnapshot(s=>{C=s.docs.map(d=>({id:d.id,...d.data()}));render()},err);
  db.collection('stories').where('ts','>',Date.now()-864e5).onSnapshot(s=>{S=s.docs.map(d=>({id:d.id,...d.data()}));render()},err);
  db.collection('accounts').onSnapshot(s=>{A=s.docs.map(d=>d.id);AC={};s.docs.forEach(d=>AC[d.id]=d.data());render()},err);
  db.collection('follows').onSnapshot(s=>{R=s.docs.map(d=>({id:d.id,...d.data()}));render()},err);
  db.collection('clikes').onSnapshot(s=>{CL=s.docs.map(d=>d.data());render()},err);
  db.collection('slikes').onSnapshot(s=>{SL=s.docs.map(d=>d.data());render()},err);
  db.collection('dms').orderBy('ts','asc').onSnapshot(s=>{D=s.docs.map(d=>d.data());render()},err);
  render()
}
function go(t,u){view={t,u};close();render();scrollTo(0,0)}
function render(){
  if(!me)return;
  const a=document.activeElement;
  if(a&&a.classList&&a.classList.contains('cin')&&a.value){clearTimeout(rt);rt=setTimeout(render,1500);return}
  $('#main').replaceChildren(view.t==='feed'?feed():view.t==='people'?people():view.t==='inbox'?inbox():view.t==='dm'?chat(view.u):profile(view.u))
}
function feed(){const F=fr(),ps=P.filter(p=>F.has(p.u));return h('div',{},storyBar(),...(ps.length?ps.map(card):[h('p',{class:'empty'},'팔로우한 사람의 게시물이 보여요. 아래 🔍에서 친구를 찾아 팔로우해봐요 💩')]))}
function storyBar(){
  const F=fr(),sn=seen(),by={};
  [...S].filter(s=>F.has(s.u)).forEach(s=>(by[s.u]=by[s.u]||[]).push(s));
  const un=u=>by[u].some(s=>!sn[s.id]),last=u=>Math.max(...by[u].map(s=>s.ts));
  const users=Object.keys(by).filter(u=>u!==me).sort((a,b)=>un(b)-un(a)||last(b)-last(a));
  const mine=!!by[me];
  return h('div',{class:'sb'},
    h('div',{class:'st',onclick:()=>mine?openStory(me):sheet('story')},h('div',{class:'ring'+(mine&&un(me)?'':' no')},av(me,56)),h('small',{},'내 스토리'),h('b',{class:'plus',onclick:e=>{e.stopPropagation();sheet('story')}},'+')),
    ...users.map(u=>h('div',{class:'st',onclick:()=>openStory(u)},h('div',{class:'ring'+(un(u)?'':' no')},av(u,56)),h('small',{},u))))
}
function like(p,mine){const r=db.doc('likes/'+p.id+'_'+me);(mine?r.delete():r.set({p:p.id,u:me})).catch(err)}
function card(p){
  const lk=L.filter(l=>l.p===p.id),mine=lk.some(l=>l.u===me),cm=C.filter(c=>c.p===p.id);
  let rp=null;
  const inp=h('input',{class:'cin',placeholder:'댓글 달기...',maxlength:200});
  const send=()=>{const t=inp.value.trim();if(!t)return;inp.value='';const d={p:p.id,u:me,t:(rp?'@'+rp.u+' ':'')+t,ts:Date.now()};if(rp)d.pc=rp.pc||rp.id;rp=null;inp.placeholder='댓글 달기...';db.collection('comments').add(d).catch(err)};
  inp.addEventListener('keydown',e=>{if(e.key==='Enter')send()});
  const clike=c=>{const m=CL.some(l=>l.c===c.id&&l.u===me),n=CL.filter(l=>l.c===c.id).length;return h('button',{class:'ch',onclick:()=>{const r=db.doc('clikes/'+c.id+'_'+me);(m?r.delete():r.set({c:c.id,u:me})).catch(err)}},(m?'❤️':'🤍')+(n?' '+n:''))};
  const row=(c,sub)=>h('div',{class:'cr'+(sub?' sub':'')},h('div',{style:'flex:1'},h('b',{},c.u+' '),c.t,h('div',{class:'sm2'},ago(c.ts)+'  ',h('a',{onclick:()=>{rp=c;inp.placeholder='@'+c.u+'님에게 답글...';inp.focus()}},'답글 달기'))),clike(c));
  return h('article',{class:'card'},
    h('div',{class:'ph'},av(p.u),h('b',{onclick:()=>go('profile',p.u)},p.u),h('span',{class:'mu'},ago(p.ts)),p.u===me?h('span',{class:'del',onclick:()=>{if(confirm('삭제할까요?'))db.doc('posts/'+p.id).delete().catch(err)}},'삭제'):null),
    h('img',{src:p.img,ondblclick:()=>like(p,mine)}),
    h('div',{class:'act'},h('button',{onclick:()=>like(p,mine)},mine?'❤️':'🤍')),
    h('div',{class:'pad'},h('b',{},'좋아요 '+lk.length+'개'),p.cap?h('p',{},h('b',{},p.u+' '),p.cap):null,...cm.filter(c=>!c.pc).map(c=>h('div',{},row(c,0),...cm.filter(x=>x.pc===c.id).map(x=>row(x,1))))),
    h('div',{class:'cw'},inp,h('button',{class:'lk',onclick:send},'게시')))
}
function profile(u){
  const mine=P.filter(p=>p.u===u),a=AC[u]||{},fl=R.filter(r=>r.to===u).map(r=>r.from),fg=R.filter(r=>r.from===u).map(r=>r.to);
  const cnt=(n,lab,list)=>h('div',{class:'cnt',onclick:()=>list&&userList(lab,list)},h('b',{},n),h('small',{},lab));
  return h('div',{},h('div',{class:'pf'},av(u,80),h('div',{style:'flex:1'},h('h2',{},u),h('div',{class:'row'},cnt(mine.length,'게시물'),cnt(fl.length,'팔로워',fl),cnt(fg.length,'팔로잉',fg)))),
    h('div',{class:'bio'},a.bio||''),
    h('div',{class:'bt'},...(u===me?[h('button',{class:'sm',onclick:editProfile},'프로필 편집'),h('button',{class:'sm',onclick:()=>{store.set('dung_me',null);location.reload()}},'로그아웃')]:[fbtn(u),h('button',{class:'sm',onclick:()=>go('dm',u)},'메시지')])),
    h('div',{class:'grid'},...mine.map(p=>h('img',{src:p.img,onclick:()=>overlay(h('div',{style:'width:min(96vw,470px);margin:auto'},card(p)))}))),
    mine.length?null:h('p',{class:'empty'},'아직 게시물이 없어요'))
}
function fbtn(u){
  const r=R.find(r=>r.from===me&&r.to===u),back=R.some(r=>r.from===u&&r.to===me);
  if(r)return h('button',{class:'sm',onclick:()=>{if(confirm(u+'님 팔로우를 취소할까요?'))db.doc('follows/'+me+'__'+u).delete().catch(err)}},'팔로잉');
  return h('button',{class:'pri sm',onclick:()=>db.doc('follows/'+me+'__'+u).set({from:me,to:u,ts:Date.now()}).catch(err)},back?'맞팔로우':'팔로우')
}
function people(){
  const inp=h('input',{placeholder:'아이디 검색...',value:q,class:'cin'}),list=h('div');
  const draw=()=>list.replaceChildren(...A.filter(u=>u!==me&&u.includes(q.toLowerCase())).map(u=>h('div',{class:'ph'},av(u,40),h('b',{onclick:()=>go('profile',u)},u),fbtn(u))));
  inp.addEventListener('input',()=>{q=inp.value.trim();draw()});draw();
  return h('div',{},h('div',{style:'padding:10px'},inp),list)
}
const seen=()=>{try{return JSON.parse(localStorage.getItem('seen_'+me)||'{}')}catch(e){return{}}};
const mark=id=>{const x=seen();if(x[id])return;x[id]=1;store.set('seen_'+me,JSON.stringify(x))};
function sendDm(to,t,re){if(to===me)return;db.collection('dms').add({from:me,to,t,ts:Date.now(),re:re||null}).catch(err)}
function inbox(){
  const by={};D.filter(m=>m.from===me||m.to===me).forEach(m=>{const o=m.from===me?m.to:m.from;(by[o]=by[o]||[]).push(m)});
  const us=Object.keys(by).sort((a,b)=>by[b][by[b].length-1].ts-by[a][by[a].length-1].ts);
  return h('div',{},h('h3',{style:'padding:10px 14px;margin:0'},'메시지'),
    ...(us.length?us.map(u=>{const l=by[u][by[u].length-1];return h('div',{class:'ph',style:'cursor:pointer',onclick:()=>go('dm',u)},av(u,44),h('div',{style:'flex:1'},h('b',{},u),h('div',{class:'mu'},(l.from===me?'나: ':'')+l.t)),h('span',{class:'mu'},ago(l.ts)))}):[h('p',{class:'empty'},'아직 메시지가 없어요. 프로필에서 메시지를 보내봐요')]))
}
function chat(u){
  const ms=D.filter(m=>(m.from===me&&m.to===u)||(m.from===u&&m.to===me));
  const inp=h('input',{class:'cin',placeholder:'메시지 보내기...',maxlength:500});
  const send=()=>{const t=inp.value.trim();if(!t)return;inp.value='';sendDm(u,t)};
  inp.addEventListener('keydown',e=>{if(e.key==='Enter')send()});
  setTimeout(()=>scrollTo(0,document.body.scrollHeight),0);
  return h('div',{},h('div',{class:'ph'},h('a',{onclick:()=>go('inbox')},'‹ 뒤로'),av(u,32),h('b',{onclick:()=>go('profile',u)},u)),
    h('div',{class:'msgs'},...ms.map(m=>h('div',{class:'m'+(m.from===me?' me':'')},m.re?h('small',{},m.re):null,m.t))),
    h('div',{class:'cw'},inp,h('button',{class:'lk',onclick:send},'보내기')))
}
function userList(title,list){
  overlay(h('div',{class:'sh'},h('h3',{},title),...(list.length?list.map(u=>h('div',{class:'ph'},av(u,40),h('b',{onclick:()=>go('profile',u)},u),u===me?null:fbtn(u))):[h('p',{class:'empty'},'아직 없어요')]),h('button',{onclick:close},'닫기')))
}
function editProfile(){
  let pic=null;const a=AC[me]||{},box=h('div',{style:'display:flex;justify-content:center'},av(me,90));
  const bio=h('textarea',{maxlength:100,rows:3,placeholder:'상태메시지 (100자)'},a.bio||''),f=h('input',{type:'file',accept:'image/*'});
  f.onchange=async()=>{if(f.files[0]){try{pic=await shrink(f.files[0],240,40000);box.replaceChildren(h('img',{class:'av',src:pic,style:'width:90px;height:90px;object-fit:cover'}))}catch(e){err(e)}}};
  const btn=h('button',{class:'pri'},'저장');
  btn.onclick=async()=>{btn.disabled=true;const d={bio:bio.value.trim()};if(pic)d.pic=pic;try{await db.doc('accounts/'+me).update(d);close()}catch(e){err(e);btn.disabled=false}};
  overlay(h('div',{class:'sh'},h('h3',{},'프로필 편집'),box,f,bio,btn,h('button',{onclick:close},'취소')))
}
function overlay(c){close();const o=h('div',{id:'ov',onclick:e=>{if(e.target===o)close()}},c);document.body.append(o)}
function close(){clearTimeout(stt);const o=$('#ov');if(o)o.remove()}
function sheet(kind){
  let data=null;
  const pv=h('img',{class:'pv'}),cap=h('input',{placeholder:'문구 입력...',maxlength:150});
  const btn=h('button',{class:'pri',disabled:''},'공유');
  btn.onclick=async()=>{btn.disabled=true;btn.textContent='올리는 중...';try{await db.collection(kind==='post'?'posts':'stories').add(kind==='post'?{u:me,img:data,cap:cap.value.trim(),ts:Date.now()}:{u:me,img:data,ts:Date.now()});close()}catch(e){err(e);btn.textContent='실패 - 다시 시도';btn.disabled=false}};
  const f=h('input',{type:'file',accept:'image/*'});
  f.onchange=async()=>{if(!f.files[0])return;try{data=await shrink(f.files[0]);pv.src=data;pv.style.display='block';btn.disabled=false}catch(e){err(e)}};
  overlay(h('div',{class:'sh'},h('h3',{},kind==='post'?'새 게시물':'새 스토리'),f,pv,kind==='post'?cap:null,btn,h('button',{onclick:close},'취소')))
}
function openStory(u,i){
  const l=S.filter(s=>s.u===u).sort((a,b)=>a.ts-b.ts),sn=seen();
  if(i===undefined){i=l.findIndex(s=>!sn[s.id]);if(i<0)i=0}
  if(i>=l.length)return close();
  const s=l[i];mark(s.id);
  const sl=SL.filter(x=>x.s===s.id);let liked=sl.some(x=>x.u===me);
  const inp=h('input',{class:'cin',placeholder:u+'님에게 답장 보내기...',maxlength:300});
  const send=()=>{const t=inp.value.trim();if(!t)return;inp.value='';sendDm(u,t,'스토리 답장');inp.placeholder='보냈어요 ✓'};
  inp.addEventListener('keydown',e=>{if(e.key==='Enter')send()});
  inp.addEventListener('focus',()=>clearTimeout(stt));
  const heart=h('button',{},liked?'❤️':'🤍');
  heart.onclick=()=>{const r=db.doc('slikes/'+s.id+'_'+me);if(liked)r.delete().catch(err);else{r.set({s:s.id,u:me}).catch(err);sendDm(u,'❤️','스토리 좋아요')}liked=!liked;heart.textContent=liked?'❤️':'🤍'};
  const bar=u===me?h('span',{},'❤️ '+sl.length+(sl.length?' ('+sl.map(x=>x.u).join(', ')+')':'')):[inp,heart];
  overlay(h('div',{class:'sv',onclick:e=>{if(e.target.closest('.x'))return;const r=e.currentTarget.getBoundingClientRect();e.clientX-r.left<r.width/3?openStory(u,Math.max(0,i-1)):openStory(u,i+1)}},
    h('div',{class:'bars'},...l.map((_,k)=>h('i',{class:k<=i?'on':''}))),
    h('div',{class:'sh2'},av(u,30),h('b',{},u),h('span',{},ago(s.ts)),u===me?h('span',{class:'x',onclick:()=>{db.doc('stories/'+s.id).delete().catch(err);close()}},'삭제'):null,h('span',{class:'x',onclick:close},'✕')),
    h('img',{src:s.img}),h('div',{class:'x sb2'},bar)));
  stt=setTimeout(()=>openStory(u,i+1),4500)
}
(async()=>{
  if(SUPABASE_URL.startsWith('여기에')){$('#main').replaceChildren(h('p',{class:'empty'},'파일 위쪽의 SUPABASE 값을 채워주세요'));return}
  db=makeDb(SUPABASE_URL,SUPABASE_KEY);
  const sv=(store.get('dung_me')||'').split('|');
  if(sv[0]){try{const s=await db.doc('accounts/'+sv[0]).get();if(s.exists&&s.data().pin===sv[1])return start(sv[0])}catch(e){err(e)}}
  $('#main').replaceChildren(authScreen())
})();
</script></body></html>
