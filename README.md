[Cổng thông tin Đoàn trường.html](https://github.com/user-attachments/files/34757801/C.ng.thong.tin.Doan.tr.ng.html)
# a123<!doctype html><html><head><meta charset=utf8><meta name=viewport content="width=device-width,initial-scale=1,viewport-fit=cover"><style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#fff;color:#000}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style></head><body>
<title>Cổng thông tin Đoàn trường</title>
<meta name="claude:viewport-fit-sides" content="cover">
<style>
/* Layout: thanh đầu trang cố định, nội dung 1 cột rộng 1080px, admin = thanh bên + vùng làm việc. Màu xanh Đoàn làm điểm nhấn duy nhất. */
:root{
  --bg:#F4F7FB;--surface:#FFFFFF;--fg:#14213D;--muted:#566680;--line:#DCE4EF;
  --accent:#0066CC;--accent-ink:#FFFFFF;--accent-soft:#E5F0FB;
  --warn:#B45309;--warn-soft:#FEF3C7;--danger:#DC2626;--danger-soft:#FEE2E2;--ok:#15803D;--ok-soft:#DCFCE7;--gray-soft:#EEF1F6;
  --font:"Be Vietnam Pro",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  --r:8px;--rc:12px;
}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){
  --bg:#0D1524;--surface:#152038;--fg:#E8EEF9;--muted:#9DABC4;--line:#263550;
  --accent:#4C9AFF;--accent-ink:#06142B;--accent-soft:#132E57;
  --warn:#FBBF24;--warn-soft:#3A2D0B;--danger:#F87171;--danger-soft:#3D1618;--ok:#4ADE80;--ok-soft:#0F2E1A;--gray-soft:#1C2A45;color-scheme:dark}}
:root[data-theme="dark"]{
  --bg:#0D1524;--surface:#152038;--fg:#E8EEF9;--muted:#9DABC4;--line:#263550;
  --accent:#4C9AFF;--accent-ink:#06142B;--accent-soft:#132E57;
  --warn:#FBBF24;--warn-soft:#3A2D0B;--danger:#F87171;--danger-soft:#3D1618;--ok:#4ADE80;--ok-soft:#0F2E1A;--gray-soft:#1C2A45;color-scheme:dark}
:root[data-brand="red"]{--accent:#C8102E;--accent-soft:#FBE7EA}
@media (prefers-color-scheme:dark){:root[data-brand="red"]:not([data-theme="light"]){--accent:#FF6B7F;--accent-soft:#3F1620;--accent-ink:#2A0710}}
:root[data-theme="dark"][data-brand="red"]{--accent:#FF6B7F;--accent-soft:#3F1620;--accent-ink:#2A0710}

*{box-sizing:border-box}
body{background:var(--bg);color:var(--fg);font-family:var(--font);font-size:16px;line-height:1.6;margin:0}
a{color:var(--accent)}
h1,h2,h3{line-height:1.25;text-wrap:balance;margin:0}
h1{font-size:clamp(1.6rem,4vw,2.3rem);font-weight:700}
h2{font-size:1.3rem;font-weight:700}
h3{font-size:1.05rem;font-weight:600}
p{margin:0}
button,input,select,textarea{font:inherit;color:inherit}
:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.wrap{max-width:1080px;margin:0 auto;padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
.muted{color:var(--muted)}
.small{font-size:.875rem}
.num{font-variant-numeric:tabular-nums}

/* header */
.top{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--surface);border-bottom:1px solid var(--line)}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:30;background:var(--surface)}
.top .wrap{display:flex;align-items:center;gap:20px;min-height:60px;flex-wrap:wrap;padding-block:6px}
.brand{display:flex;align-items:center;gap:10px;text-decoration:none;color:var(--fg);font-weight:700;min-width:0}
.brand svg{flex:none}
.brand small{display:block;font-weight:400;color:var(--muted);font-size:.75rem;line-height:1.2}
.nav{display:flex;gap:2px;overflow-x:auto;flex:1;min-width:0;scrollbar-width:none}
.nav a{white-space:nowrap;padding:8px 12px;border-radius:var(--r);text-decoration:none;color:var(--fg);font-size:.95rem}
.nav a:hover{background:var(--gray-soft)}
.nav a[aria-current="page"]{background:var(--accent-soft);color:var(--accent);font-weight:600}
.sform{display:flex;gap:6px}
.sform input{width:150px}

/* controls */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:6px;min-height:44px;padding:8px 18px;border-radius:var(--r);border:1px solid var(--accent);background:var(--accent);color:var(--accent-ink);font-weight:600;cursor:pointer;text-decoration:none}
.btn:hover{filter:brightness(1.08)}
.btn.ghost{background:transparent;color:var(--accent)}
.btn.plain{background:var(--surface);color:var(--fg);border-color:var(--line)}
.btn.danger{background:var(--danger);border-color:var(--danger);color:#fff}
.btn.sm{min-height:34px;padding:4px 12px;font-size:.875rem}
.btn[disabled]{opacity:.5;cursor:not-allowed}
input,select,textarea{width:100%;min-height:44px;padding:8px 12px;border:1px solid var(--line);border-radius:var(--r);background:var(--surface)}
textarea{min-height:110px;resize:vertical}
input[type=checkbox],input[type=radio]{width:auto;min-height:0;accent-color:var(--accent)}
label.f{display:grid;gap:6px;font-weight:500;font-size:.95rem}
label.f .hint{font-weight:400;color:var(--muted);font-size:.85rem}
.grid2{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px}
.grid3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:14px}
.stack{display:grid;gap:14px}
.row{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
.sp{flex:1}

/* surfaces */
main{padding-block:28px 64px;min-height:70vh}
.card{background:var(--surface);border:1px solid var(--line);border-radius:var(--rc);padding:20px;min-width:0}
.sec{margin-top:36px;display:grid;gap:14px}
.sec>.head{display:flex;align-items:baseline;gap:12px;flex-wrap:wrap}
.sec>.head a{margin-left:auto;font-size:.9rem}
.pill{display:inline-flex;align-items:center;gap:6px;padding:2px 10px;border-radius:99px;font-size:.8rem;font-weight:600;background:var(--gray-soft);color:var(--muted);white-space:nowrap}
.pill.pending{background:var(--warn-soft);color:var(--warn)}
.pill.processing{background:var(--accent-soft);color:var(--accent)}
.pill.done{background:var(--ok-soft);color:var(--ok)}
.pill.rejected{background:var(--danger-soft);color:var(--danger)}
.notice{padding:12px 16px;border-radius:var(--r);background:var(--warn-soft);color:var(--fg);border:1px solid var(--warn)}
.empty{padding:28px;text-align:center;color:var(--muted);border:1px dashed var(--line);border-radius:var(--rc)}
.tablewrap{overflow-x:auto;border:1px solid var(--line);border-radius:var(--rc);background:var(--surface)}
table{border-collapse:collapse;width:100%}
th,td{padding:10px 14px;text-align:left;border-bottom:1px solid var(--line);vertical-align:middle}
th{font-size:.8rem;text-transform:uppercase;letter-spacing:.04em;color:var(--muted);font-weight:600;background:var(--gray-soft)}
tr:last-child td{border-bottom:0}
td.r,th.r{text-align:right}

/* hero */
.hero{display:grid;grid-template-columns:minmax(0,1.4fr) minmax(0,1fr);gap:28px;align-items:center;padding:36px;border-radius:var(--rc);background:var(--accent);color:var(--accent-ink)}
.hero p{opacity:.92;max-width:52ch;margin-top:10px}
.hero .lookup{background:var(--surface);color:var(--fg);border-radius:var(--rc);padding:18px;display:grid;gap:10px}
.hero .lookup b{font-size:.95rem}
.short{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:14px}
.short a{display:grid;gap:4px;padding:18px;border-radius:var(--rc);background:var(--surface);border:1px solid var(--line);text-decoration:none;color:var(--fg)}
.short a:hover{border-color:var(--accent)}
.short b{color:var(--accent);font-size:1.05rem}
.stat{display:grid;gap:2px}
.stat b{font-size:2rem;line-height:1.1;font-variant-numeric:tabular-nums}
.list{display:grid;gap:0}
.list>a,.list>div.it{display:grid;gap:2px;padding:12px 0;border-bottom:1px solid var(--line);text-decoration:none;color:var(--fg);cursor:pointer}
.list>a:last-child,.list>div.it:last-child{border-bottom:0}
.list .t{font-weight:600}
.list>a:hover .t{color:var(--accent)}

/* deduction */
.chips{display:flex;gap:8px;flex-wrap:wrap}
.chip{padding:6px 14px;border-radius:99px;border:1px solid var(--line);background:var(--surface);cursor:pointer;font-size:.9rem}
.chip:hover,.chip.on{border-color:var(--accent);color:var(--accent);background:var(--accent-soft)}
.ded{width:100%}
.ded td{padding:14px 16px;font-size:1.02rem}
.ded td.p{text-align:right;white-space:nowrap;font-weight:700;font-variant-numeric:tabular-nums;width:1%}
.sev-l{color:var(--muted)}.sev-m{color:var(--warn)}.sev-h{color:var(--danger)}
.dot{display:inline-block;width:10px;height:10px;border-radius:50%;background:var(--danger);margin-right:6px}
mark{background:var(--warn-soft);color:inherit;border-radius:3px;padding:0 2px}
.secttl{display:flex;align-items:baseline;gap:10px;margin-bottom:8px;scroll-margin-top:90px}

/* detail */
.doc{display:grid;grid-template-columns:230px minmax(0,1fr);gap:28px;align-items:start}
.toc{position:sticky;top:80px;display:grid;gap:4px;font-size:.9rem}
.toc button{text-align:left;background:none;border:0;padding:6px 10px;border-left:2px solid var(--line);cursor:pointer;color:var(--muted)}
.toc button:hover{color:var(--accent);border-color:var(--accent)}
.prose{display:grid;gap:12px;max-width:68ch}
.prose h2{margin-top:14px;scroll-margin-top:90px}
.prose ul{margin:0;padding-left:1.3em;display:grid;gap:4px}

/* form */
.opt{display:flex;gap:10px;align-items:flex-start;padding:12px 14px;border:1px solid var(--line);border-radius:var(--r);cursor:pointer;background:var(--surface)}
.opt:has(input:checked){border-color:var(--accent);background:var(--accent-soft)}
.opt span{display:grid;gap:0}
.codebox{font-size:1.7rem;font-weight:700;letter-spacing:.06em;font-variant-numeric:tabular-nums;padding:14px 18px;border-radius:var(--r);background:var(--accent-soft);color:var(--accent);word-break:break-all}
.thumbs{display:flex;gap:8px;flex-wrap:wrap}
.thumbs div{position:relative}
.thumbs img{width:84px;height:84px;object-fit:cover;border-radius:var(--r);border:1px solid var(--line)}
.thumbs button{position:absolute;top:-6px;right:-6px;width:24px;height:24px;border-radius:50%;border:0;background:var(--danger);color:#fff;cursor:pointer}

/* admin */
.adm{display:grid;grid-template-columns:210px minmax(0,1fr);gap:24px;align-items:start}
.side{position:sticky;top:80px;display:grid;gap:2px}
.side a{padding:9px 12px;border-radius:var(--r);text-decoration:none;color:var(--fg);font-size:.95rem}
.side a:hover{background:var(--gray-soft)}
.side a[aria-current="page"]{background:var(--accent-soft);color:var(--accent);font-weight:600}
.side .grp{font-size:.75rem;text-transform:uppercase;letter-spacing:.06em;color:var(--muted);padding:12px 12px 4px}
.kpis{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:12px}
.kpi{padding:14px 16px;border-radius:var(--rc);background:var(--surface);border:1px solid var(--line)}
.kpi b{display:block;font-size:1.7rem;font-variant-numeric:tabular-nums;line-height:1.2}
.kpi.warn b{color:var(--danger)}
.bar{display:grid;grid-template-columns:130px minmax(0,1fr) 34px;gap:10px;align-items:center;font-size:.9rem}
.bar i{display:block;height:12px;border-radius:6px;background:var(--accent);min-width:2px}
.days{display:flex;align-items:flex-end;gap:5px;height:100px}
.days div{flex:1;background:var(--accent);border-radius:3px 3px 0 0;min-height:2px;position:relative}
.inl{min-height:34px;padding:4px 8px}
.permgrp{border:1px solid var(--line);border-radius:var(--r);padding:10px 14px;display:grid;gap:6px}
.permgrp label{display:flex;gap:8px;align-items:flex-start;font-size:.92rem}
.permgrp label.dis{opacity:.45}
.permgrp code{font-size:.8rem;color:var(--muted)}

/* modal */
#modal:not(:empty){position:fixed;inset:0;z-index:50;background:rgba(8,14,28,.55);display:grid;place-items:start center;overflow-y:auto;padding:max(16px,env(safe-area-inset-top,0px)) max(16px,env(safe-area-inset-right,0px)) 16px max(16px,env(safe-area-inset-left,0px))}
.dlg{background:var(--surface);border-radius:var(--rc);width:min(680px,100%);padding:22px;margin-block:24px;display:grid;gap:14px;border:1px solid var(--line)}
.dlg.wide{width:min(860px,100%)}
.dlg>.hd{display:flex;align-items:center;gap:10px}
.toast{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(20px + env(safe-area-inset-bottom,0px));background:var(--fg);color:var(--bg);padding:10px 18px;border-radius:99px;z-index:60;font-size:.9rem}
footer{border-top:1px solid var(--line);background:var(--surface);padding-block:28px calc(28px + env(safe-area-inset-bottom,0px))}
footer .wrap{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}

@media (max-width:860px){
  .hero,.doc,.adm{grid-template-columns:minmax(0,1fr)}
  .hero{padding:24px}
  .toc,.side{position:static}
  .side{grid-auto-flow:column;overflow-x:auto;grid-auto-columns:max-content}
  .side .grp{display:none}
  .short,.grid3{grid-template-columns:minmax(0,1fr)}
  .sform{display:none}
}
@media (max-width:560px){.grid2{grid-template-columns:minmax(0,1fr)}.bar{grid-template-columns:90px minmax(0,1fr) 30px}.card{padding:16px}}
@media (prefers-reduced-motion:no-preference){.btn,.chip,.short a{transition:background .15s,border-color .15s,filter .15s}}
</style>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;700&display=swap">

<header class="top"><div class="wrap">
  <a class="brand" href="#" id="brand"></a>
  <nav class="nav" id="nav" aria-label="Menu chính"></nav>
  <form class="sform" data-form="hsearch"><input id="hq" type="search" placeholder="Tìm kiếm..." aria-label="Tìm kiếm"><button class="btn sm" type="submit">Tìm</button></form>
</div></header>
<div id="banner"></div>
<main class="wrap" id="main"></main>
<footer><div class="wrap" id="foot"></div></footer>
<div id="modal" role="dialog" aria-modal="true"></div>
<div id="toast"></div>

<script>
(async function(){
"use strict";
/* ============ tiện ích ============ */
const $=(s,r=document)=>r.querySelector(s);
const esc=s=>String(s??"").replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
const norm=s=>String(s||"").normalize("NFD").replace(/[̀-ͯ]/g,"").replace(/đ/g,"d").toLowerCase();
const slug=s=>norm(s).replace(/[^a-z0-9]+/g,"-").replace(/^-|-$/g,"")||("m"+Date.now().toString(36));
const fdate=t=>t?new Date(t).toLocaleDateString("vi-VN"):"";
const fdt=t=>t?new Date(t).toLocaleString("vi-VN",{dateStyle:"short",timeStyle:"short"}):"";
const hl=(txt,q)=>{const t=esc(txt);if(!q)return t;const i=norm(txt).indexOf(norm(q));if(i<0)return t;
  const a=esc(String(txt).slice(0,i)),b=esc(String(txt).slice(i,i+q.length)),c=esc(String(txt).slice(i+q.length));return a+"<mark>"+b+"</mark>"+c};
function toast(m){const t=$("#toast");t.innerHTML='<div class="toast">'+esc(m)+'</div>';clearTimeout(toast.t);toast.t=setTimeout(()=>t.innerHTML="",2600)}
function md(src){const out=[],toc=[];let ul=false;const cl=()=>{if(ul){out.push("</ul>");ul=false}};
  String(src||"").split("\n").forEach(l=>{l=l.trimEnd();
    if(l.startsWith("### ")){cl();out.push("<h3>"+esc(l.slice(4))+"</h3>")}
    else if(l.startsWith("## ")){cl();const id="h"+toc.length;toc.push({id,t:l.slice(3)});out.push('<h2 id="'+id+'">'+esc(l.slice(3))+"</h2>")}
    else if(l.startsWith("- ")){if(!ul){out.push("<ul>");ul=true}out.push("<li>"+esc(l.slice(2))+"</li>")}
    else if(!l.trim())cl();else{cl();out.push("<p>"+esc(l)+"</p>")}});
  cl();return{html:out.join(""),toc}}

/* ============ dữ liệu ============ */
const TYPES={suggestion:["Góp ý xây dựng","Đề xuất cải thiện nhà trường, hoạt động Đoàn."],self:["Phản ánh bản thân","Tự trình bày hoàn cảnh hoặc vi phạm của mình, xin hỗ trợ."],report:["Báo cáo vi phạm","Tố giác hành vi vi phạm của người khác."]};
const STAT={pending:"Chờ xử lý",processing:"Đang xử lý",done:"Đã xử lý",rejected:"Từ chối"};
const ANON={full:"Ẩn danh hoàn toàn",doan:"Ẩn danh với Đoàn",named:"Nói danh"};
const CATS=["Học tập","Nề nếp","Đạo đức","Cơ sở vật chất","Khác"];
const S={sections:[],items:[],regcats:[],regs:[],cases:[],posts:[],roles:[],accounts:[],fbraw:[],fbmeta:[],audit:[],status:[],contacts:[],settings:{},loaded:{}};
const UI={acct:null,sess:null,fails:[],lastAct:Date.now(),isAdmin:false,isOwner:false,uid:null,asRole:null,reg:null,regCat:"",post:null,postCat:"",q:"",kl:"",lookup:null,sent:null,files:[],fb:{status:"",type:"",q:""},modal:null,dbOk:true};
let db=null,dl=null;
try{UI.sess=sessionStorage.getItem("doan_sess")}catch(e){}
const settings=()=>Object.assign({name:"Đoàn trường",slogan:"Quy định minh bạch, góp ý ẩn danh, đồng hành cùng học sinh.",heroTitle:"Biết rõ quy định, nói được điều mình nghĩ.",heroText:"Tra cứu nội quy, điểm trừ rèn luyện và các vụ việc đã xử lý. Gửi góp ý hoặc phản ánh mà không cần nêu tên.",year:"2025–2026",address:"",email:"",phone:"",hours:"",deadline:7,maxImages:5,maxMB:5,hide:[],maintenance:false,brand:"blue",enabled:{suggestion:true,self:true,report:true}},S.settings);

/* ============ phân quyền ============ */
const PERMS=[
["Trang","pages",[["pages.view","Xem danh sách"],["pages.create","Tạo nháp","pages.view"],["pages.edit","Sửa","pages.view"],["pages.delete","Xóa mềm","pages.edit",1],["pages.publish","Công khai","pages.edit"]]],
["Blog","posts",[["posts.view","Xem"],["posts.create","Tạo nháp","posts.view"],["posts.edit.own","Sửa bài mình","posts.view"],["posts.edit.all","Sửa mọi bài","posts.view"],["posts.delete","Xóa","posts.edit.own",1],["posts.publish","Công khai","posts.edit.own"],["taxonomy.manage","Chuyên mục & tag"],["comments.moderate","Duyệt bình luận"],["comments.reply","Trả lời bình luận"]]],
["Cấu trúc & giao diện","ui",[["menus.edit","Sửa menu"],["widgets.edit","Sửa widget"],["theme.manage","Đổi theme"],["templates.manage","Chọn template"],["media.upload","Upload file"],["media.delete","Xóa file",null,1]]],
["Đơn góp ý","fb",[["feedback.view","Xem đơn"],["feedback.process","Xử lý (đổi trạng thái)","feedback.view"],["feedback.assign","Phân công","feedback.view"],["feedback.export","Xuất Excel/PDF","feedback.view"],["feedback.delete","Xóa mềm","feedback.process",1]]],
["Kỷ luật & quy định","reg",[["discipline.manage","Quản lý vụ việc"],["regulations.manage","Quản lý văn bản"],["deduction.manage","Quản lý trừ điểm"]]],
["Hệ thống","sys",[["users.manage","Quản lý người dùng",null,1],["roles.manage","Quản lý vai trò",null,1],["settings.manage","Cài đặt",null,1],["audit.view","Xem nhật ký"]]]];
const ALLP=PERMS.flatMap(g=>g[2].map(p=>({code:p[0],label:p[1],dep:p[2],danger:p[3],grp:g[1]})));
const PRESET={"Quản lý nội dung":null};
const roleById=id=>S.roles.find(r=>r.id===id);
const isSuper=()=>!!(UI.acct&&UI.acct.roleId==="super"&&!UI.asRole);
const myRole=()=>{if(!UI.acct)return null;if(UI.acct.roleId==="super")return UI.asRole?roleById(UI.asRole):null;return roleById(UI.acct.roleId)||{name:"?",level:0,permissions:[]}};
const myPerms=()=>{if(!UI.isAdmin||!UI.acct)return new Set();if(isSuper())return new Set(["*"]);const r=myRole();return new Set(r?r.permissions||[]:[])};
const can=p=>{const s=myPerms();return s.has("*")||s.has(p)};
const myLevel=()=>{if(isSuper())return 100;const r=myRole();return r?r.level:0};
const levelOf=a=>a.roleId==="super"?100:(roleById(a.roleId)||{level:0}).level;

async function audit(action,entity,detail){try{await db.collection("audit").add({at:Date.now(),action,entity,detail:String(detail||"").slice(0,200),actor:UI.acct?UI.acct.id:"?",role:UI.acct?(UI.acct.roleId==="super"?"Super Admin":(roleById(UI.acct.roleId)||{}).name||"?"):"?"})}catch(e){}}
async function w(fn,okMsg){try{await fn();if(okMsg)toast(okMsg);return true}catch(e){toast("Không lưu được: "+(e&&e.code==="invalid_argument"?"bạn chưa có quyền ghi dữ liệu.":(e&&e.message)||"lỗi không rõ"));return false}}
const col=n=>db.collection(n);

/* ============ nạp dữ liệu ============ */
function listen(key,coll,adminOnly){
  if(!db||(adminOnly&&!UI.isAdmin)){S.loaded[key]=true;return}
  try{col(coll).onSnapshot(s=>{S[key]=s.docs.map(d=>({id:d.id,...d.data()}));S.loaded[key]=true;refresh()},e=>{S.loaded[key]=true;refresh()})}catch(e){S.loaded[key]=true}}
let pend=false,rt=0;
function refresh(){clearTimeout(rt);rt=setTimeout(()=>{
  const r0=route();if((r0==="gop-y"&&!UI.sent)||r0==="lien-he"||r0==="admin-settings"){chrome();return}
  const a=document.activeElement;
  if(a&&$("#main").contains(a)&&/INPUT|TEXTAREA|SELECT/.test(a.tagName)&&route()!=="tra-cuu"){pend=true;return}
  pend=false;render(true)},60)}
document.addEventListener("focusout",()=>{if(pend)setTimeout(()=>{if(pend&&!(document.activeElement&&/INPUT|TEXTAREA|SELECT/.test(document.activeElement.tagName)))refresh()},200)});

/* ============ đường dẫn ============ */
const route=()=>location.hash.replace("#","")||"home";
const go=r=>{if(location.hash.replace("#","")===r){render()}else location.hash=r};
const PUB=[["home","Trang chủ"],["quy-dinh","Quy định"],["diem-ren-luyen","Trừ điểm"],["ky-luat","Kỷ luật"],["gop-y","Góp ý"],["tra-cuu","Tra cứu"],["blog","Blog"],["lien-he","Liên hệ"]];
const ADM=[
["admin","Tổng quan",null,""],
["admin-feedback","Đơn góp ý","feedback.view","Nội dung"],
["admin-deduction","Trừ điểm rèn luyện","deduction.manage",""],
["admin-regs","Quy định","regulations.manage",""],
["admin-cases","Kỷ luật","discipline.manage",""],
["admin-posts","Blog","posts.view",""],
["admin-roles","Vai trò & quyền","roles.manage","Hệ thống"],
["admin-users","Người dùng","users.manage",""],
["admin-settings","Cài đặt","settings.manage",""],
["admin-audit","Nhật ký","audit.view",""]];

/* ============ khung trang ============ */
function chrome(){
  const s=settings();
  document.documentElement.dataset.brand=s.brand==="red"?"red":"blue";
  document.title=s.name+" – Cổng thông tin";
  $("#brand").innerHTML='<svg width="36" height="36" viewBox="0 0 24 24" aria-hidden="true"><circle cx="12" cy="12" r="11.5" fill="var(--accent)"/><polygon points="12,4 14,9.6 19.9,9.9 15.3,13.6 16.9,19.3 12,16 7.1,19.3 8.7,13.6 4.1,9.9 10,9.6" fill="var(--accent-ink)"/></svg><span>'+esc(s.name)+'<small>Cổng thông tin &amp; quản trị</small></span>';
  const r=route();
  $("#nav").innerHTML=PUB.map(([k,l])=>'<a href="#'+(k==="home"?"":k)+'"'+((r===k||(k==="quy-dinh"&&r==="quy-dinh"))?' aria-current="page"':"")+">"+l+"</a>").join("")+'<a href="#admin"'+(r.startsWith("admin")?' aria-current="page"':"")+'>Quản trị</a>';
  $("#foot").innerHTML='<div><b>'+esc(s.name)+'</b><p class="muted small">'+esc(s.slogan)+'</p></div><div class="small"><b>Liên hệ</b><p class="muted">'+(esc(s.address)||"Chưa cập nhật địa chỉ")+'</p><p class="muted">'+esc(s.email)+" "+esc(s.phone)+'</p></div><div class="small"><b>Cam kết</b><p class="muted">Đơn ẩn danh hoàn toàn không lưu tên, email, số điện thoại. Ảnh đính kèm được xử lý lại để xóa vị trí và thông tin thiết bị.</p></div>';
  let b="";
  if(!db)b='<div class="wrap" style="padding-top:12px"><div class="notice">Chưa kết nối được kho dữ liệu. Hãy đăng nhập tài khoản để xem và gửi dữ liệu.</div></div>';
  else if(!Object.values(S.loaded).every(Boolean)&&S._slow)b='<div class="wrap" style="padding-top:12px"><div class="notice">Đang tải dữ liệu chậm. Nội dung có thể chưa mới nhất.</div></div>';
  $("#banner").innerHTML=b}

function doLogout(){UI.acct=null;UI.sess=null;UI.asRole=null;try{sessionStorage.removeItem("doan_sess")}catch(e){}}
function syncAcct(){if(!UI.isAdmin||!S.loaded.accounts)return;
  if(!UI.acct&&UI.sess){const a=S.accounts.find(x=>x.id===UI.sess&&x.active!==false);if(a)UI.acct=a;else UI.sess=null}
  else if(UI.acct){const a=S.accounts.find(x=>x.id===UI.acct.id);if(!a||a.active===false)doLogout();else UI.acct=a}}
const b64=a=>btoa(String.fromCharCode(...new Uint8Array(a)));
const unb64=t=>Uint8Array.from(atob(t),c=>c.charCodeAt(0));
const newSalt=()=>b64(crypto.getRandomValues(new Uint8Array(16)));
async function pwHash(pw,salt){const k=await crypto.subtle.importKey("raw",new TextEncoder().encode(pw),"PBKDF2",false,["deriveBits"]);return b64(await crypto.subtle.deriveBits({name:"PBKDF2",hash:"SHA-256",salt:unb64(salt),iterations:150000},k,256))}
function loginHtml(){
  if(!S.loaded.accounts)return '<div class="empty">Đang tải...</div>';
  if(!S.accounts.length)return '<form class="card stack" data-form="setup" style="max-width:460px;margin:30px auto"><h1>Thiết lập Super Admin</h1><p class="muted small">Chưa có tài khoản nào. Tạo tài khoản Super Admin đầu tiên. Tài khoản này cấp được tài khoản cho người khác.</p><label class="f">Họ tên<input name="name" required></label><label class="f">Tên đăng nhập<input name="username" required autocomplete="username"></label><label class="f">Mật khẩu <span class="hint">Tối thiểu 8 ký tự</span><input name="password" type="password" required autocomplete="new-password"></label><label class="f">Nhập lại mật khẩu<input name="password2" type="password" required autocomplete="new-password"></label><button class="btn" type="submit">Tạo Super Admin</button><p class="small" id="lerr" style="color:var(--danger)"></p></form>';
  return '<form class="card stack" data-form="login" style="max-width:420px;margin:30px auto"><h1>Đăng nhập quản trị</h1><p class="muted small">Dành cho thành viên BCH Đoàn có tài khoản.</p><label class="f">Tên đăng nhập<input name="username" required autocomplete="username"></label><label class="f">Mật khẩu<input name="password" type="password" required autocomplete="current-password"></label><button class="btn" type="submit">Đăng nhập</button><p class="small" id="lerr" style="color:var(--danger)"></p><p class="small muted">Quên mật khẩu? Liên hệ Super Admin để đặt lại.</p></form>'}
let lastRoute=null;
function render(keep){
  syncAcct();const r=route();chrome();
  const s=settings();
  let pg;
  if(s.maintenance&&!UI.isAdmin&&!r.startsWith("admin"))pg=P.maint;
  else pg=P[r]||P.nf;
  $("#main").innerHTML=pg.html();
  if(pg.bind)pg.bind();
  if(lastRoute!==r){window.scrollTo(0,0);lastRoute=r}
}
addEventListener("hashchange",()=>{if(UI.keep)UI.keep=false;else{UI.reg=null;UI.post=null}render()});
document.addEventListener("click",e=>{const a=e.target.closest(".nav a,.brand");if(a){const h=(a.getAttribute("href")||"").replace("#","")||"home";if(h===route()){UI.reg=null;UI.post=null;render()}}});

/* ============ lắp ghép ============ */
const sectionsPub=()=>S.sections.filter(x=>x.visible!==false).sort((a,b)=>(a.order||0)-(b.order||0));
const itemsOf=id=>S.items.filter(i=>i.section===id&&i.status!=="draft").sort((a,b)=>a.points-b.points||(a.order||0)-(b.order||0));
const sev=p=>p>=16?"h":p>=6?"m":"l";
const sevTxt=p=>p>=16?'<span class="dot"></span>':"";
const loadingOrEmpty=(k,msg)=>S.loaded[k]?'<div class="empty">'+msg+"</div>":'<div class="empty">Đang tải...</div>';
const pub=(a,d="published")=>a.filter(x=>x.status===d);
const regsPub=()=>S.regs.filter(x=>x.status==="published").sort((a,b)=>(b.pinned?1:0)-(a.pinned?1:0)||(b.updatedAt||0)-(a.updatedAt||0));
const postsPub=()=>S.posts.filter(x=>x.status==="published"&&(x.publishAt||0)<=Date.now()).sort((a,b)=>(b.pinned?1:0)-(a.pinned?1:0)||(b.publishAt||0)-(a.publishAt||0));
const casesPub=()=>S.cases.filter(x=>x.visible!==false).sort((a,b)=>(b.decidedAt||"").localeCompare(a.decidedAt||""));
const dedRow=(i,q)=>'<tr><td>'+hl(i.title,q)+(i.note?'<div class="small muted">'+esc(i.note)+"</div>":"")+'</td><td class="p sev-'+sev(i.points)+'">'+sevTxt(i.points)+"Trừ "+i.points+" điểm</td></tr>";

/* ============ TRANG CÔNG KHAI ============ */
const P={};
P.maint={html:()=>'<div class="card" style="max-width:560px;margin:40px auto;text-align:center"><h1>Đang bảo trì</h1><p class="muted" style="margin-top:10px">Cổng thông tin tạm đóng để cập nhật. Vui lòng quay lại sau.</p></div>'};
P.nf={html:()=>'<div class="card" style="max-width:560px;margin:40px auto"><h1>Không tìm thấy trang</h1><p class="muted" style="margin:10px 0 16px">Địa chỉ này không tồn tại. Thử các lối tắt bên dưới.</p><div class="row"><a class="btn" href="#quy-dinh">Xem quy định</a><a class="btn plain" href="#gop-y">Gửi góp ý</a></div></div>'};

P.home={html(){
  const s=settings(),hide=s.hide||[],show=k=>!hide.includes(k);
  const regs=regsPub().slice(0,5),posts=postsPub(),notices=posts.filter(p=>p.pinned).slice(0,4),latest=posts.slice(0,3);
  const done=S.status.filter(x=>x.status==="done").length,cases=casesPub().length;
  const pick=[];sectionsPub().forEach(sc=>itemsOf(sc.id).slice(0,2).forEach(i=>pick.push({...i,sc:sc.name})));
  let h='<section class="hero"><div><h1>'+esc(s.heroTitle)+"</h1><p>"+esc(s.heroText)+'</p><div class="row" style="margin-top:20px"><a class="btn plain" href="#gop-y">Gửi góp ý ẩn danh</a><a class="btn ghost" style="color:var(--accent-ink);border-color:var(--accent-ink)" href="#quy-dinh">Xem quy định</a></div></div>'
   +'<form class="lookup" data-form="homelookup"><b>Tra cứu hồ sơ đã gửi</b><input id="hcode" placeholder="Ví dụ: PA-2026-A1B2C3" aria-label="Mã hồ sơ" autocomplete="off"><button class="btn" type="submit">Tra cứu trạng thái</button></form></section>';
  if(show("shortcuts"))h+='<div class="short sec"><a href="#gop-y"><b>Gửi góp ý ẩn danh</b><span class="muted small">Góp ý, phản ánh, báo cáo vi phạm kèm ảnh.</span></a><a href="#tra-cuu"><b>Tra cứu đơn</b><span class="muted small">Nhập mã hồ sơ để xem trạng thái.</span></a><a href="#diem-ren-luyen"><b>Điểm trừ rèn luyện</b><span class="muted small">Bảng điểm trừ theo từng mục.</span></a></div>';
  if(show("notices")&&notices.length)h+='<section class="sec"><div class="head"><h2>Thông báo nổi bật</h2><a href="#blog">Xem tất cả</a></div><div class="card list">'+notices.map(p=>'<a href="#blog" data-act="post" data-id="'+p.id+'"><span class="t">'+esc(p.title)+'</span><span class="small muted">'+fdate(p.publishAt)+"</span></a>").join("")+"</div></section>";
  if(show("regs"))h+='<section class="sec"><div class="head"><h2>Quy định mới cập nhật</h2><a href="#quy-dinh">Tất cả quy định</a></div><div class="card list">'+(regs.length?regs.map(r=>'<a href="#quy-dinh" data-act="reg" data-id="'+r.id+'"><span class="t">'+esc(r.title)+'</span><span class="small muted">'+esc(r.summary)+"</span></a>").join(""):loadingOrEmpty("regs","Chưa có quy định nào được công khai."))+"</div></section>";
  if(show("deduction"))h+='<section class="sec"><div class="head"><h2>Điểm trừ rèn luyện thường gặp</h2><a href="#diem-ren-luyen">Xem bảng đầy đủ</a></div>'+(pick.length?'<div class="tablewrap"><table class="ded"><tbody>'+pick.slice(0,6).map(i=>dedRow(i)).join("")+"</tbody></table></div>":loadingOrEmpty("items","Chưa có quy định trừ điểm."))+"</section>";
  if(show("stats"))h+='<section class="sec"><div class="head"><h2>Số liệu công khai</h2></div><div class="grid3"><div class="card stat"><b>'+S.status.length+'</b><span class="muted">đơn đã tiếp nhận</span></div><div class="card stat"><b>'+done+'</b><span class="muted">đơn đã xử lý xong</span></div><div class="card stat"><b>'+cases+'</b><span class="muted">vụ việc kỷ luật công khai</span></div></div></section>';
  if(show("blog")&&latest.length)h+='<section class="sec"><div class="head"><h2>Hoạt động Đoàn</h2><a href="#blog">Xem blog</a></div><div class="grid3">'+latest.map(p=>'<a class="card" style="text-decoration:none;color:inherit" href="#blog" data-act="post" data-id="'+p.id+'"><span class="pill">'+esc(p.category||"Tin tức")+'</span><h3 style="margin:8px 0 4px">'+esc(p.title)+'</h3><p class="muted small">'+esc(p.excerpt||"")+"</p></a>").join("")+"</div></section>";
  if(show("contact"))h+='<section class="sec"><div class="head"><h2>Liên hệ BCH Đoàn</h2><a href="#lien-he">Gửi tin nhắn</a></div><div class="card grid3 small"><div><b>Địa chỉ</b><p class="muted">'+(esc(s.address)||"Chưa cập nhật")+'</p></div><div><b>Email / điện thoại</b><p class="muted">'+(esc(s.email+" "+s.phone).trim()||"Chưa cập nhật")+'</p></div><div><b>Giờ tiếp</b><p class="muted">'+(esc(s.hours)||"Chưa cập nhật")+"</p></div></div></section>";
  return h}};

P["quy-dinh"]={html(){
  if(UI.reg){const r=S.regs.find(x=>x.id===UI.reg);if(r){const m=md(r.body);const cat=S.regcats.find(c=>c.id===r.cat);
    return '<p><button class="btn plain sm" data-act="regback">← Danh sách quy định</button></p><div class="doc" style="margin-top:16px"><nav class="toc" aria-label="Mục lục">'+(m.toc.length?'<b class="small muted">MỤC LỤC</b>'+m.toc.map(t=>'<button data-act="scrollto" data-id="'+t.id+'">'+esc(t.t)+"</button>").join(""):"")+'</nav><article class="stack"><div><span class="pill">'+esc(cat?cat.name:"Quy định")+'</span><h1 style="margin-top:8px">'+esc(r.title)+'</h1><p class="small muted" style="margin-top:6px">Cập nhật '+fdate(r.updatedAt)+(r.effective?" · Hiệu lực từ "+fdate(r.effective):"")+'</p></div><div class="card" style="background:var(--accent-soft);border-color:var(--accent)"><b>Tóm tắt</b><p>'+esc(r.summary)+'</p></div><div class="prose">'+m.html+"</div>"
      +((r.penalties||[]).length?'<div class="stack"><h2>Lỗi thường gặp &amp; mức xử lý</h2><div class="tablewrap"><table><thead><tr><th>Lỗi</th><th>Mức xử lý</th></tr></thead><tbody>'+r.penalties.map(p=>"<tr><td>"+esc(p[0])+"</td><td>"+esc(p[1])+"</td></tr>").join("")+"</tbody></table></div></div>":"")+"</article></div>"}}
  const q=norm(UI.q);let regs=regsPub();if(UI.regCat)regs=regs.filter(r=>r.cat===UI.regCat);
  const cats=S.regcats.filter(c=>c.visible!==false).sort((a,b)=>(a.order||0)-(b.order||0));
  return '<h1>Quy định nhà trường</h1><p class="muted" style="margin:6px 0 18px">Mỗi văn bản có phần tóm tắt ngắn trước nội dung chi tiết.</p><div class="stack"><input id="rq" type="search" placeholder="Tìm: đồng phục, nghỉ học, điện thoại, thi lại..." aria-label="Tìm quy định" value="'+esc(UI.q)+'"><div class="chips"><button class="chip'+(UI.regCat?"":" on")+'" data-act="regcat" data-id="">Tất cả</button>'+cats.map(c=>'<button class="chip'+(UI.regCat===c.id?" on":"")+'" data-act="regcat" data-id="'+c.id+'">'+esc(c.name)+"</button>").join("")+'</div><div id="rlist"></div></div>'},
  bind(){if(UI.reg)return;const f=()=>{UI.q=$("#rq").value;const q=norm(UI.q);let regs=regsPub();if(UI.regCat)regs=regs.filter(r=>r.cat===UI.regCat);
    if(q)regs=regs.filter(r=>norm(r.title+" "+r.summary).includes(q));
    $("#rlist").innerHTML=regs.length?'<div class="card list">'+regs.map(r=>'<div class="it" data-act="reg" data-id="'+r.id+'"><span class="t">'+hl(r.title,UI.q)+'</span><span class="small muted">'+hl(r.summary,UI.q)+'</span><span class="small muted">Cập nhật '+fdate(r.updatedAt)+"</span></div>").join("")+"</div>":loadingOrEmpty("regs","Không có quy định phù hợp.")};
    $("#rq").addEventListener("input",f);f()}};

P["diem-ren-luyen"]={html(){
  const s=settings(),secs=sectionsPub().filter(sc=>itemsOf(sc.id).length);
  return '<h1>Quy định trừ điểm rèn luyện</h1><p class="muted" style="margin:6px 0 18px">Năm học '+esc(s.year)+'. Điểm trừ xếp từ nhẹ đến nặng trong từng mục.</p><div class="stack"><input id="dq" type="search" placeholder="Tìm vi phạm: đi muộn, điện thoại..." aria-label="Tìm vi phạm" value="'+esc(UI.q)+'"><div class="chips" aria-label="Mục lục">'+secs.map(sc=>'<button class="chip" data-act="scrollto" data-id="s-'+sc.id+'">'+esc(sc.name)+" "+itemsOf(sc.id).length+"</button>").join("")+'</div><div id="dlist" class="stack"></div><p class="small muted">Chấm 100 điểm mỗi học kỳ. Điểm trừ cộng dồn theo số lần vi phạm.</p></div>'},
  bind(){const f=()=>{UI.q=$("#dq").value;const q=norm(UI.q);let out="";
    sectionsPub().forEach(sc=>{let its=itemsOf(sc.id);if(q)its=its.filter(i=>norm(i.title).includes(q));if(!its.length)return;
      out+='<section><div class="secttl" id="s-'+sc.id+'"><h2>'+esc(sc.name)+'</h2><span class="muted small">'+its.length+' vi phạm</span></div>'+(sc.description?'<p class="muted small" style="margin-bottom:8px">'+esc(sc.description)+"</p>":"")+'<div class="tablewrap"><table class="ded"><tbody>'+its.map(i=>dedRow(i,UI.q)).join("")+"</tbody></table></div></section>"});
    $("#dlist").innerHTML=out||loadingOrEmpty("items",q?"Không tìm thấy vi phạm phù hợp.":"Chưa có quy định trừ điểm nào.")};
    $("#dq").addEventListener("input",f);f()}};

P["ky-luat"]={html(){
  const all=casesPub(),types=[...new Set(all.map(c=>c.type).filter(Boolean))];
  const list=all.filter(c=>!UI.kl||c.type===UI.kl);
  const byM={};all.forEach(c=>{const m=(c.decidedAt||"").slice(0,7);if(m)byM[m]=(byM[m]||0)+1});const ms=Object.keys(byM).sort().slice(-8),mx=Math.max(1,...ms.map(m=>byM[m]));
  return '<h1>Vụ việc kỷ luật đã xử lý</h1><p class="muted" style="margin:6px 0 18px">Mô tả đã được ẩn danh, không nêu tên học sinh.</p><div class="stack"><div class="row"><select id="klf" aria-label="Lọc loại vi phạm" style="max-width:280px"><option value="">Mọi loại vi phạm</option>'+types.map(t=>'<option'+(UI.kl===t?" selected":"")+">"+esc(t)+"</option>").join("")+"</select></div>"
   +(ms.length?'<div class="card"><b class="small">Số vụ theo tháng</b><div class="days" style="margin-top:12px">'+ms.map(m=>'<div style="height:'+Math.round(byM[m]/mx*100)+'%" title="'+m+": "+byM[m]+'"></div>').join("")+'</div><div class="row small muted" style="gap:5px;margin-top:4px">'+ms.map(m=>'<span style="flex:1;text-align:center">'+m.slice(5)+"/"+m.slice(2,4)+" · "+byM[m]+"</span>").join("")+"</div></div>":"")
   +(list.length?'<div class="grid2">'+list.map(c=>'<article class="card stack" style="gap:8px"><div class="row"><b>'+esc(c.code)+'</b><span class="pill">'+esc(c.type)+'</span><span class="sp"></span><span class="small muted">'+fdate(c.decidedAt)+'</span></div><p>'+esc(c.description)+'</p><p class="small"><b>Hình thức xử lý:</b> '+esc(c.penalty)+"</p></article>").join("")+"</div>":loadingOrEmpty("cases","Chưa có vụ việc nào được công khai."))+"</div>"},
  bind(){$("#klf").addEventListener("change",e=>{UI.kl=e.target.value;render()})}};

P["gop-y"]={html(){
  const s=settings();
  if(UI.sent)return '<div class="card stack" style="max-width:620px;margin:20px auto"><h1>Đã nhận đơn của bạn</h1><p class="muted">Hãy lưu lại mã hồ sơ. Đây là cách duy nhất để tra cứu kết quả, kể cả khi bạn gửi ẩn danh.</p><div class="codebox" id="codev">'+esc(UI.sent)+'</div><div class="row"><button class="btn" data-act="copy" data-v="'+esc(UI.sent)+'">Sao chép mã</button><a class="btn plain" href="#tra-cuu">Đến trang tra cứu</a><button class="btn ghost" data-act="newfb">Gửi đơn khác</button></div><p class="small muted">Thời hạn xử lý dự kiến: '+s.deadline+" ngày làm việc.</p></div>";
  const en=s.enabled||{};
  return '<h1>Góp ý, phản ánh, báo cáo</h1><p class="muted" style="margin:6px 0 18px">Bạn có thể gửi hoàn toàn ẩn danh. Hệ thống không ghi tên, email hay số điện thoại nếu bạn chọn ẩn danh hoàn toàn.</p>'
  +'<form class="card stack" data-form="feedback" style="max-width:760px" novalidate><fieldset style="border:0;padding:0;margin:0;display:grid;gap:8px"><legend style="font-weight:600;margin-bottom:6px">Loại đơn *</legend>'
  +Object.entries(TYPES).filter(([k])=>en[k]!==false).map(([k,v],i)=>'<label class="opt"><input type="radio" name="type" value="'+k+'"'+(i?"":" checked")+"><span><b>"+v[0]+'</b><span class="muted small">'+v[1]+"</span></span></label>").join("")+"</fieldset>"
  +'<div class="grid2"><label class="f">Chủ đề *<select name="category">'+CATS.map(c=>"<option>"+c+"</option>").join("")+'</select></label><label class="f">Tiêu đề * <span class="hint" id="tc">0/120</span><input name="title" maxlength="120" required></label></div>'
  +'<label class="f">Nội dung * <span class="hint" id="cc">0 ký tự (tối thiểu 50)</span><textarea name="content" rows="6" required></textarea></label>'
  +'<fieldset style="border:0;padding:0;margin:0;display:grid;gap:8px"><legend style="font-weight:600;margin-bottom:6px">Chế độ danh tính *</legend>'
  +Object.entries(ANON).map(([k,v],i)=>'<label class="opt"><input type="radio" name="anonymity" value="'+k+'"'+(i?"":" checked")+"><span><b>"+v+'</b><span class="muted small">'+({full:"Không lưu bất kỳ thông tin nhận diện nào.",doan:"Chỉ BCH Đoàn được xem thông tin liên hệ của bạn.",named:"Bạn đồng ý để BCH Đoàn liên hệ trực tiếp."})[k]+"</span></span></label>").join("")+"</fieldset>"
  +'<div id="ident" class="grid2" hidden><label class="f">Họ tên<input name="sname"></label><label class="f">Lớp / Chi đoàn<input name="sclass"></label><label class="f">Email<input name="semail" type="email"></label><label class="f">Số điện thoại<input name="sphone" type="tel"></label></div>'
  +'<div class="stack" style="gap:8px"><b>Ảnh đính kèm <span class="muted small" style="font-weight:400">(tối đa '+s.maxImages+' ảnh, mỗi ảnh ≤ '+s.maxMB+'MB; JPG, PNG, WebP)</span></b><input type="file" id="fi" accept="image/jpeg,image/png,image/webp" multiple><div class="thumbs" id="thumbs"></div><p class="small muted">Ảnh được vẽ lại và nén trước khi gửi nên vị trí GPS và thông tin thiết bị bị xóa.</p></div>'
  +'<label class="row" style="align-items:flex-start"><input type="checkbox" name="oath" required style="margin-top:6px"><span>Tôi cam kết nội dung trung thực và chịu trách nhiệm về thông tin đã gửi.</span></label><div class="row"><button class="btn" type="submit" id="fbsub">Gửi đơn</button><span class="small muted" id="fberr" style="color:var(--danger)"></span></div></form>'},
  bind(){if(UI.sent)return;const f=$("form[data-form=feedback]");if(!f)return;
    f.elements.title.addEventListener("input",e=>$("#tc").textContent=e.target.value.length+"/120");
    f.elements.content.addEventListener("input",e=>$("#cc").textContent=e.target.value.length+" ký tự (tối thiểu 50)");
    f.addEventListener("change",e=>{if(e.target.name==="anonymity")$("#ident").hidden=e.target.value==="full"});
    $("#fi").addEventListener("change",async e=>{const s=settings();
      for(const file of e.target.files){if(UI.files.length>=s.maxImages){toast("Tối đa "+s.maxImages+" ảnh.");break}
        if(file.size>s.maxMB*1048576){toast(file.name+" lớn hơn "+s.maxMB+"MB.");continue}
        try{UI.files.push(await shrink(file))}catch(err){toast("Không đọc được "+file.name+". Hãy dùng ảnh JPG, PNG hoặc WebP.")}}
      e.target.value="";thumbs()});thumbs()}};
function thumbs(){const t=$("#thumbs");if(t)t.innerHTML=UI.files.map((d,i)=>'<div><img alt="Ảnh đính kèm '+(i+1)+'" src="'+d+'"><button type="button" data-act="rmfile" data-i="'+i+'" aria-label="Xóa ảnh">×</button></div>').join("")}
async function shrink(file){const bmp=await createImageBitmap(file);let max=1000,q=.62,out;
  for(let k=0;k<4;k++){const sc=Math.min(1,max/Math.max(bmp.width,bmp.height));const c=document.createElement("canvas");c.width=Math.round(bmp.width*sc);c.height=Math.round(bmp.height*sc);
    const x=c.getContext("2d");x.fillStyle="#fff";x.fillRect(0,0,c.width,c.height);x.drawImage(bmp,0,0,c.width,c.height);out=c.toDataURL("image/jpeg",q);if(out.length<230000)return out;max*=.75;q-=.08}
  throw new Error("big")}
function newCode(){const a="ABCDEFGHJKLMNPQRSTUVWXYZ23456789",r=crypto.getRandomValues(new Uint8Array(6));return"PA-"+new Date().getFullYear()+"-"+[...r].map(n=>a[n%a.length]).join("")}

FORMS_INIT();
P["tra-cuu"]={html(){
  const r=UI.lookup;let res="";
  if(r){if(r.none)res='<div class="empty">Không tìm thấy hồ sơ với mã này. Kiểm tra lại mã và thử lại.</div>';
    else res='<div class="card stack"><div class="row"><b>'+esc(r.code)+'</b><span class="pill '+r.status+'">'+STAT[r.status]+'</span></div><p class="small muted">Cập nhật lần cuối: '+fdt(r.updatedAt)+"</p>"+(r.publicNote?'<div class="card" style="background:var(--accent-soft)"><b class="small">Ghi chú từ BCH Đoàn</b><p>'+esc(r.publicNote)+"</p></div>":'<p class="muted">Chưa có ghi chú công khai.</p>')+'<p class="small muted">Vì lý do riêng tư, nội dung đơn gốc và danh tính người gửi không hiển thị tại đây.</p></div>'}
  return '<h1>Tra cứu hồ sơ</h1><p class="muted" style="margin:6px 0 18px">Nhập mã hồ sơ bạn nhận được sau khi gửi đơn.</p><div class="stack" style="max-width:620px"><form class="row" data-form="lookup"><input id="lcode" placeholder="PA-2026-A1B2C3" aria-label="Mã hồ sơ" autocomplete="off" style="flex:1;min-width:200px" value="'+esc(r?r.code:"")+'"><button class="btn" type="submit">Tra cứu</button></form>'+res+"</div>"}};
async function doLookup(code){code=String(code||"").trim().toUpperCase();if(!code)return;
  try{const d=await col("status").doc(code).get();UI.lookup=d.exists?{code,...d.data()}:{code,none:true}}catch(e){UI.lookup={code,none:true}}
  go("tra-cuu");render()}

P.blog={html(){
  if(UI.post){const p=S.posts.find(x=>x.id===UI.post);if(p){const m=md(p.body);
    return '<p><button class="btn plain sm" data-act="postback">← Blog</button></p><article class="stack prose" style="margin-top:16px;max-width:720px"><span class="pill" style="width:max-content">'+esc(p.category||"Tin tức")+"</span><h1>"+esc(p.title)+'</h1><p class="small muted">'+esc(p.author||"BCH Đoàn")+" · "+fdate(p.publishAt)+"</p>"+m.html+"</article>"}}
  const posts=postsPub(),cats=[...new Set(posts.map(p=>p.category).filter(Boolean))],list=posts.filter(p=>!UI.postCat||p.category===UI.postCat);
  return '<h1>Blog hoạt động Đoàn</h1><div class="chips" style="margin:16px 0"><button class="chip'+(UI.postCat?"":" on")+'" data-act="postcat" data-id="">Tất cả</button>'+cats.map(c=>'<button class="chip'+(UI.postCat===c?" on":"")+'" data-act="postcat" data-id="'+esc(c)+'">'+esc(c)+"</button>").join("")+"</div>"
   +(list.length?'<div class="grid2">'+list.map(p=>'<article class="card" style="cursor:pointer" data-act="post" data-id="'+p.id+'"><div class="row"><span class="pill">'+esc(p.category||"Tin tức")+"</span>"+(p.pinned?'<span class="pill pending">Ghim</span>':"")+'</div><h3 style="margin:8px 0 4px">'+esc(p.title)+'</h3><p class="muted small">'+esc(p.excerpt||"")+'</p><p class="small muted" style="margin-top:8px">'+esc(p.author||"BCH Đoàn")+" · "+fdate(p.publishAt)+"</p></article>").join("")+"</div>":loadingOrEmpty("posts","Chưa có bài viết nào."))}};

P["lien-he"]={html(){const s=settings();
  return '<h1>Liên hệ</h1><div class="grid2" style="margin-top:18px"><div class="card stack"><h3>BCH Đoàn trường</h3><p><b>Địa chỉ:</b> '+(esc(s.address)||"Chưa cập nhật")+"</p><p><b>Email:</b> "+(esc(s.email)||"Chưa cập nhật")+"</p><p><b>Điện thoại:</b> "+(esc(s.phone)||"Chưa cập nhật")+"</p><p><b>Giờ tiếp:</b> "+(esc(s.hours)||"Chưa cập nhật")+'</p></div><form class="card stack" data-form="contact"><h3>Gửi tin nhắn</h3><label class="f">Họ tên<input name="name" required></label><label class="f">Email hoặc số điện thoại<input name="contact" required></label><label class="f">Nội dung<textarea name="msg" required></textarea></label><button class="btn" type="submit">Gửi</button></form></div>'}};

P["tim-kiem"]={html(){
  const q=norm(UI.q);let out="";
  const grp=(t,arr)=>arr.length?'<section class="stack"><h2>'+t+'</h2><div class="card list">'+arr.join("")+"</div></section>":"";
  if(q){
   out+=grp("Quy định",regsPub().filter(r=>norm(r.title+" "+r.summary).includes(q)).map(r=>'<a href="#quy-dinh" data-act="reg" data-id="'+r.id+'"><span class="t">'+hl(r.title,UI.q)+'</span><span class="small muted">'+esc(r.summary)+"</span></a>"));
   const di=[];sectionsPub().forEach(sc=>itemsOf(sc.id).filter(i=>norm(i.title).includes(q)).forEach(i=>di.push('<a href="#diem-ren-luyen"><span class="t">'+hl(i.title,UI.q)+'</span><span class="small muted">'+esc(sc.name)+" · Trừ "+i.points+" điểm</span></a>")));out+=grp("Trừ điểm rèn luyện",di);
   out+=grp("Bài viết",postsPub().filter(p=>norm(p.title+" "+p.excerpt).includes(q)).map(p=>'<a href="#blog" data-act="post" data-id="'+p.id+'"><span class="t">'+hl(p.title,UI.q)+"</span></a>"));
   out+=grp("Kỷ luật",casesPub().filter(c=>norm(c.type+" "+c.description).includes(q)).map(c=>'<a href="#ky-luat"><span class="t">'+esc(c.code)+" · "+esc(c.type)+'</span><span class="small muted">'+esc(c.description)+"</span></a>"));
   if(!out)out='<div class="empty">Không có kết quả cho “'+esc(UI.q)+"”.</div>"}
  return '<h1>Tìm kiếm</h1><form class="row" data-form="hsearch2" style="margin:16px 0"><input id="sq" type="search" value="'+esc(UI.q)+'" style="flex:1;min-width:200px" aria-label="Từ khóa"><button class="btn" type="submit">Tìm</button></form><div class="stack">'+out+"</div>"}};

/* ============ ADMIN ============ */
function adminShell(inner,r){
  if(!UI.isAdmin)return '<div class="card stack" style="max-width:600px;margin:30px auto"><h1>Khu vực quản trị</h1><p class="muted">Trang này dành cho BCH Đoàn. Hãy đăng nhập bằng tài khoản được cấp quyền chỉnh sửa trang web này.</p><a class="btn plain" href="#" style="width:max-content">Về trang chủ</a></div>';
  if(!UI.acct)return loginHtml();
  const items=ADM.filter(a=>!a[2]||can(a[2]));
  let side="",last="";items.forEach(a=>{if(a[3]&&a[3]!==last){side+='<div class="grp">'+a[3]+"</div>";last=a[3]}side+='<a href="#'+a[0]+'"'+(a[0]===r?' aria-current="page"':"")+">"+a[1]+"</a>"});
  const cur=ADM.find(a=>a[0]===r);
  if(cur&&cur[2]&&!can(cur[2]))inner='<div class="empty">Vai trò hiện tại không có quyền “'+cur[2]+'”.</div>';
  const roleSel=UI.acct.roleId==="super"?'<label class="row small muted">Xem giao diện với vai trò <select id="asr" style="width:auto;min-height:34px;padding:2px 8px"><option value="">Super Admin (đầy đủ)</option>'+S.roles.filter(x=>!x.system).map(x=>'<option value="'+x.id+'"'+(UI.asRole===x.id?" selected":"")+">"+esc(x.name)+" (cấp "+x.level+")</option>").join("")+"</select></label>":"";
  return '<div class="adm"><nav class="side" aria-label="Menu quản trị">'+side+'</nav><div class="stack" style="min-width:0"><div class="row small card" style="padding:10px 14px"><b>'+esc(UI.acct.name)+'</b><span class="pill">'+(UI.acct.roleId==="super"?"Super Admin":esc((roleById(UI.acct.roleId)||{}).name||"?"))+'</span><span class="sp"></span>'+roleSel+'<button class="btn plain sm" data-act="chpw">Đổi mật khẩu</button><button class="btn plain sm" data-act="logout">Đăng xuất</button></div>'+inner+"</div></div>"}
const adm=(r,fn,bind)=>{P[r]={html:()=>adminShell(fn(),r),bind(){const s=$("#asr");if(s)s.addEventListener("change",e=>{UI.asRole=e.target.value||null;render()});bind&&bind()}}};
const age=d=>(Date.now()-d)/864e5;
const fbAll=()=>{const m={};S.fbmeta.forEach(x=>m[x.id]=x);return S.fbraw.map(x=>({...x,...(m[x.id]||{}),id:x.id}))};
const live=()=>fbAll().filter(f=>!f.deleted);
async function setMeta(code,patch){const old=S.fbmeta.find(x=>x.id===code)||{};const {id,...rest}=old;return col("fbmeta").doc(code).set({...rest,...patch})}

adm("admin",()=>{
  const f=live(),now=Date.now(),dl_=settings().deadline,day=new Date().setHours(0,0,0,0);
  const cnt=(ms)=>f.filter(x=>now-x.createdAt<ms).length;
  const pending=f.filter(x=>x.status==="pending"),over=f.filter(x=>(x.status==="pending"||x.status==="processing")&&age(x.createdAt)>dl_*7/5);
  const byS=Object.keys(STAT).map(k=>[STAT[k],f.filter(x=>x.status===k).length]),byT=Object.keys(TYPES).map(k=>[TYPES[k][0],f.filter(x=>x.type===k).length]);
  const mx=Math.max(1,...byS.map(x=>x[1]),...byT.map(x=>x[1]));
  const days=[...Array(14)].map((_,i)=>{const d0=day-(13-i)*864e5;return f.filter(x=>x.createdAt>=d0&&x.createdAt<d0+864e5).length}),dm=Math.max(1,...days);
  const bars=a=>a.map(x=>'<div class="bar"><span>'+x[0]+'</span><i style="width:'+Math.round(x[1]/mx*100)+'%"></i><b class="num">'+x[1]+"</b></div>").join("");
  return '<h1>Tổng quan</h1><div class="kpis"><div class="kpi">Hôm nay<b>'+f.filter(x=>x.createdAt>=day).length+'</b></div><div class="kpi">7 ngày<b>'+cnt(7*864e5)+'</b></div><div class="kpi">30 ngày<b>'+cnt(30*864e5)+'</b></div><div class="kpi">Đơn chờ<b>'+pending.length+'</b></div><div class="kpi'+(over.length?" warn":"")+'">Quá hạn<b>'+over.length+'</b></div><div class="kpi">Bài viết<b>'+S.posts.length+"</b></div></div>"
  +'<div class="grid2"><div class="card stack"><h3>Đơn theo trạng thái</h3>'+bars(byS)+'</div><div class="card stack"><h3>Đơn theo loại</h3>'+bars(byT)+"</div></div>"
  +'<div class="card stack"><h3>Đơn mới trong 14 ngày</h3><div class="days">'+days.map((n,i)=>'<div style="height:'+Math.round(n/dm*100)+'%" title="'+n+' đơn"></div>').join("")+'</div></div>'
  +'<div class="card stack"><div class="row"><h3>Đơn mới nhất</h3><span class="sp"></span>'+(can("feedback.view")?'<a href="#admin-feedback">Xem tất cả</a>':"")+"</div>"+(f.length?'<div class="list">'+[...f].sort((a,b)=>b.createdAt-a.createdAt).slice(0,5).map(x=>'<div class="it" data-act="fbopen" data-id="'+x.id+'"><span class="t">'+esc(x.title)+'</span><span class="small muted">'+x.code+" · "+fdt(x.createdAt)+' · <span class="pill '+x.status+'">'+STAT[x.status]+"</span></span></div>").join("")+"</div>":'<p class="muted">Chưa có đơn nào.</p>')+"</div>"
  +(over.length?'<div class="notice">Có '+over.length+" đơn quá hạn xử lý "+dl_+" ngày làm việc.</div>":"")
  +'<div class="row">'+(can("deduction.manage")?'<a class="btn plain" href="#admin-deduction">Thêm quy định trừ điểm</a>':"")+(can("posts.create")?'<a class="btn plain" href="#admin-posts">Viết blog</a>':"")+(can("regulations.manage")?'<a class="btn plain" href="#admin-regs">Thêm văn bản quy định</a>':"")+"</div>"});

/* --- đơn góp ý --- */
function fbFiltered(){const F=UI.fb,q=norm(F.q);return live().filter(x=>(!F.status||x.status===F.status)&&(!F.type||x.type===F.type)&&(!q||norm(x.code+" "+x.title+" "+x.content).includes(q))).sort((a,b)=>b.createdAt-a.createdAt)}
adm("admin-feedback",()=>{const F=UI.fb;
  return '<div class="row"><h1>Đơn góp ý</h1><span class="sp"></span>'+(can("feedback.export")?'<button class="btn plain sm" data-act="fbexport">Xuất CSV (Excel)</button>':"")+'</div><div class="row"><input id="fq" type="search" placeholder="Mã hoặc từ khóa..." value="'+esc(F.q)+'" style="flex:1;min-width:180px" aria-label="Tìm đơn"><select id="fs" style="width:auto" aria-label="Trạng thái"><option value="">Mọi trạng thái</option>'+Object.entries(STAT).map(([k,v])=>'<option value="'+k+'"'+(F.status===k?" selected":"")+">"+v+"</option>").join("")+'</select><select id="ft" style="width:auto" aria-label="Loại đơn"><option value="">Mọi loại</option>'+Object.entries(TYPES).map(([k,v])=>'<option value="'+k+'"'+(F.type===k?" selected":"")+">"+v[0]+"</option>").join("")+'</select></div><div id="fbl"></div>'},
 ()=>{const fill=()=>{const l=fbFiltered();$("#fbl").innerHTML=l.length?'<div class="tablewrap"><table><thead><tr><th>Mã</th><th>Loại</th><th>Tiêu đề</th><th>Danh tính</th><th>Trạng thái</th><th>Ngày gửi</th></tr></thead><tbody>'+l.map(x=>'<tr style="cursor:pointer" data-act="fbopen" data-id="'+x.id+'"><td class="num">'+x.code+"</td><td>"+TYPES[x.type][0]+"</td><td>"+esc(x.title)+"</td><td>"+ANON[x.anonymity]+'</td><td><span class="pill '+x.status+'">'+STAT[x.status]+'</span></td><td class="num">'+fdate(x.createdAt)+"</td></tr>").join("")+"</tbody></table></div>":loadingOrEmpty("feedback","Chưa có đơn nào khớp bộ lọc.")};
  $("#fq").addEventListener("input",e=>{UI.fb.q=e.target.value;fill()});$("#fs").addEventListener("change",e=>{UI.fb.status=e.target.value;fill()});$("#ft").addEventListener("change",e=>{UI.fb.type=e.target.value;fill()});fill()});

async function openFb(id){
  const f=fbAll().find(x=>x.id===id);if(!f)return;
  let imgs=[];if(f.attachments){try{const q=await col("feedback").doc(f.uid).collection("files").where("code","==",f.code).get();imgs=q.docs.map(d=>d.data().data)}catch(e){}}
  const st=S.status.find(x=>x.id===f.code)||{};
  const who=f.anonymity==="full"?"Ẩn danh":(f.sname||"(không ghi tên)")+(f.sclass?" · "+f.sclass:"")+(f.semail?" · "+f.semail:"")+(f.sphone?" · "+f.sphone:"");
  const cp=can("feedback.process"),ca=can("feedback.assign");
  modal('<div class="dlg wide"><div class="hd"><h2>'+f.code+'</h2><span class="pill '+f.status+'">'+STAT[f.status]+'</span><span class="sp"></span><button class="btn plain sm" data-act="close">Đóng</button></div>'
  +'<p class="small muted">'+TYPES[f.type][0]+" · "+esc(f.category)+" · "+ANON[f.anonymity]+" · "+fdt(f.createdAt)+'</p><h3>'+esc(f.title)+'</h3><div class="card" style="white-space:pre-wrap">'+esc(f.content)+"</div>"
  +(imgs.length?'<div class="thumbs">'+imgs.map(s=>'<img style="width:120px;height:120px" alt="Ảnh đính kèm" src="'+esc(s)+'">').join("")+"</div>":"")
  +'<p><b>Người gửi:</b> '+esc(who)+'</p><form class="stack" data-form="fbsave" data-id="'+f.id+'"><div class="grid2"><label class="f">Trạng thái<select name="status"'+(cp?"":" disabled")+">"+Object.entries(STAT).map(([k,v])=>'<option value="'+k+'"'+(f.status===k?" selected":"")+">"+v+"</option>").join("")+'</select></label><label class="f">Người phụ trách<select name="assigned"'+(ca?"":" disabled")+'><option value="">Chưa phân công</option>'+S.accounts.map(u=>'<option value="'+u.id+'"'+(f.assigned===u.id?" selected":"")+">"+esc(u.name)+"</option>").join("")+'</select></label></div><label class="f">Ghi chú công khai <span class="hint">Người gửi thấy khi tra cứu</span><textarea name="pub" rows="2"'+(cp?"":" disabled")+">"+esc(st.publicNote||"")+'</textarea></label><label class="f">Ghi chú nội bộ <span class="hint">Chỉ BCH thấy</span><textarea name="note" rows="2"'+(cp?"":" disabled")+">"+esc(f.adminNote||"")+'</textarea></label><div class="row">'+(cp||ca?'<button class="btn" type="submit">Lưu</button>':"")+'<span class="sp"></span>'+(can("feedback.delete")?'<button class="btn danger sm" type="button" data-act="fbdel" data-id="'+f.id+'">Xóa mềm</button>':"")+"</div></form></div>")}
function fbCSV(){const rows=[["Mã","Loại","Chủ đề","Tiêu đề","Nội dung","Danh tính","Họ tên","Lớp","Email","SĐT","Trạng thái","Ngày gửi"]];
  fbFiltered().forEach(x=>rows.push([x.code,TYPES[x.type][0],x.category,x.title,x.content,ANON[x.anonymity],x.sname||"",x.sclass||"",x.semail||"",x.sphone||"",STAT[x.status],fdt(x.createdAt)]));
  return"﻿"+rows.map(r=>r.map(c=>'"'+String(c).replace(/"/g,'""')+'"').join(",")).join("\r\n")}
async function saveFile(name,data){if(!dl){toast("Trình xem này chưa cho phép tải tệp.");return}try{await dl.save({filename:name,data});toast("Đã tạo tệp "+name)}catch(e){if(!e||e.code!=="declined")toast("Không tải được tệp.")}}

/* --- trừ điểm --- */
adm("admin-deduction",()=>{
  const secs=[...S.sections].sort((a,b)=>(a.order||0)-(b.order||0));
  return '<div class="row"><h1>Trừ điểm rèn luyện</h1><span class="sp"></span><button class="btn plain sm" data-act="dimport">Nhập từ Excel</button><button class="btn plain sm" data-act="dsec">+ Tạo mục</button><button class="btn sm" data-act="dadd" data-sec="">+ Thêm quy định</button></div><p class="small muted">Sửa trực tiếp ô tiêu đề hoặc điểm trừ rồi nhấn Enter. Dùng mũi tên để đổi thứ tự.</p>'
  +(secs.length?secs.map(sc=>{const its=S.items.filter(i=>i.section===sc.id).sort((a,b)=>(a.order||0)-(b.order||0));
    return '<section class="card stack" style="gap:8px"><div class="row"><h3>'+esc(sc.name)+'</h3><span class="muted small">'+its.length+' mục'+(sc.visible===false?" · đang ẩn":"")+'</span><span class="sp"></span><button class="btn plain sm" data-act="dsec" data-id="'+sc.id+'">Sửa mục</button><button class="btn sm" data-act="dadd" data-sec="'+sc.id+'">+ Thêm</button></div>'
    +(its.length?'<div class="tablewrap"><table><tbody>'+its.map((i,ix)=>'<tr><td><input class="inl" data-chg="dtitle" data-id="'+i.id+'" value="'+esc(i.title)+'" aria-label="Tiêu đề"></td><td style="width:110px"><input class="inl num" type="number" min="1" data-chg="dpts" data-id="'+i.id+'" value="'+i.points+'" aria-label="Điểm trừ"></td><td style="width:70px">'+(i.status==="draft"?'<span class="pill">Nháp</span>':"")+'</td><td class="r" style="white-space:nowrap"><button class="btn plain sm" data-act="dmove" data-id="'+i.id+'" data-d="-1"'+(ix?"":" disabled")+' aria-label="Lên">↑</button> <button class="btn plain sm" data-act="dmove" data-id="'+i.id+'" data-d="1"'+(ix<its.length-1?"":" disabled")+' aria-label="Xuống">↓</button> <button class="btn plain sm" data-act="dedit" data-id="'+i.id+'">Sửa</button> <button class="btn plain sm" data-act="ddel" data-id="'+i.id+'">Xóa</button></td></tr>').join("")+"</tbody></table></div>":'<p class="muted small">Mục này chưa có quy định.</p>')+"</section>"}).join(""):loadingOrEmpty("sections","Chưa có mục nào. Tạo mục đầu tiên để bắt đầu."))});

/* --- quy định --- */
adm("admin-regs",()=>{
  const cats=S.regcats;
  return '<div class="row"><h1>Văn bản quy định</h1><span class="sp"></span><button class="btn plain sm" data-act="rcat">+ Nhóm</button><button class="btn sm" data-act="redit">+ Văn bản</button></div><div class="chips">'+cats.map(c=>'<button class="chip" data-act="rcat" data-id="'+c.id+'">'+esc(c.name)+"</button>").join("")+"</div>"
  +(S.regs.length?'<div class="tablewrap"><table><thead><tr><th>Tiêu đề</th><th>Nhóm</th><th>Trạng thái</th><th>Cập nhật</th><th></th></tr></thead><tbody>'+[...S.regs].sort((a,b)=>(b.updatedAt||0)-(a.updatedAt||0)).map(r=>"<tr><td>"+esc(r.title)+"</td><td>"+esc((cats.find(c=>c.id===r.cat)||{}).name||"")+'</td><td><span class="pill '+(r.status==="published"?"done":"")+'">'+(r.status==="published"?"Công khai":"Nháp")+'</span></td><td class="num">'+fdate(r.updatedAt)+'</td><td class="r"><button class="btn plain sm" data-act="redit" data-id="'+r.id+'">Sửa</button> <button class="btn plain sm" data-act="rdel" data-id="'+r.id+'">Xóa</button></td></tr>').join("")+"</tbody></table></div>":loadingOrEmpty("regs","Chưa có văn bản nào."))});

adm("admin-cases",()=>'<div class="row"><h1>Vụ việc kỷ luật</h1><span class="sp"></span><button class="btn sm" data-act="cedit">+ Thêm vụ việc</button></div>'
  +(S.cases.length?'<div class="tablewrap"><table><thead><tr><th>Mã</th><th>Loại</th><th>Hình thức</th><th>Ngày</th><th>Hiển thị</th><th></th></tr></thead><tbody>'+[...S.cases].sort((a,b)=>(b.decidedAt||"").localeCompare(a.decidedAt||"")).map(c=>"<tr><td>"+esc(c.code)+"</td><td>"+esc(c.type)+"</td><td>"+esc(c.penalty)+'</td><td class="num">'+fdate(c.decidedAt)+"</td><td>"+(c.visible===false?"Ẩn":"Công khai")+'</td><td class="r"><button class="btn plain sm" data-act="cedit" data-id="'+c.id+'">Sửa</button> <button class="btn plain sm" data-act="cdel" data-id="'+c.id+'">Xóa</button></td></tr>').join("")+"</tbody></table></div>":loadingOrEmpty("cases","Chưa có vụ việc nào.")));

adm("admin-posts",()=>'<div class="row"><h1>Blog</h1><span class="sp"></span>'+(can("posts.create")?'<button class="btn sm" data-act="pedit">+ Viết bài</button>':"")+"</div>"
  +(S.posts.length?'<div class="tablewrap"><table><thead><tr><th>Tiêu đề</th><th>Chuyên mục</th><th>Trạng thái</th><th>Ngày đăng</th><th></th></tr></thead><tbody>'+[...S.posts].sort((a,b)=>(b.publishAt||0)-(a.publishAt||0)).map(p=>"<tr><td>"+esc(p.title)+"</td><td>"+esc(p.category||"")+'</td><td><span class="pill '+(p.status==="published"?"done":"")+'">'+(p.status==="published"?((p.publishAt||0)>Date.now()?"Đã lên lịch":"Công khai"):"Nháp")+'</span></td><td class="num">'+fdate(p.publishAt)+'</td><td class="r">'+((can("posts.edit.all")||can("posts.edit.own"))?'<button class="btn plain sm" data-act="pedit" data-id="'+p.id+'">Sửa</button> ':"")+(can("posts.delete")?'<button class="btn plain sm" data-act="pdel" data-id="'+p.id+'">Xóa</button>':"")+"</td></tr>").join("")+"</tbody></table></div>":loadingOrEmpty("posts","Chưa có bài viết nào.")));

/* --- vai trò --- */
adm("admin-roles",()=>'<div class="row"><h1>Vai trò &amp; quyền</h1><span class="sp"></span><button class="btn sm" data-act="redrole">+ Tạo vai trò</button></div><p class="small muted">Cấp bậc quyết định ai được quản lý ai. Quyền quyết định được làm gì. Bạn chỉ cấp được quyền mình có và cấp bậc thấp hơn mình.</p>'
 +'<div class="tablewrap"><table><thead><tr><th>Vai trò</th><th class="r">Cấp</th><th class="r">Quyền</th><th class="r">Người dùng</th><th></th></tr></thead><tbody>'
 +'<tr><td><b>Super Admin</b><div class="small muted">Toàn quyền (*), không thể sửa hoặc xóa</div></td><td class="r">100</td><td class="r">Tất cả</td><td class="r">—</td><td></td></tr>'
 +[...S.roles].sort((a,b)=>b.level-a.level).map(r=>"<tr><td><b>"+esc(r.name)+'</b><div class="small muted">'+esc(r.description||"")+'</div></td><td class="r num">'+r.level+'</td><td class="r num">'+(r.permissions||[]).length+'/32</td><td class="r num">'+S.accounts.filter(u=>u.roleId===r.id).length+'</td><td class="r"><button class="btn plain sm" data-act="redrole" data-id="'+r.id+'">Sửa</button> <button class="btn plain sm" data-act="dupr" data-id="'+r.id+'">Nhân bản</button> <button class="btn plain sm" data-act="delr" data-id="'+r.id+'">Xóa</button></td></tr>').join("")+"</tbody></table></div>");

adm("admin-users",()=>'<div class="row"><h1>Tài khoản BCH</h1><span class="sp"></span><button class="btn sm" data-act="uedit">+ Cấp tài khoản</button></div><p class="small muted">Chỉ cấp được vai trò thấp hơn cấp của bạn. Người được cấp tài khoản cũng cần được mời làm Editor trong menu Share của trang này thì mới xem được dữ liệu quản trị.</p>'
 +(S.accounts.length?'<div class="tablewrap"><table><thead><tr><th>Họ tên</th><th>Đăng nhập</th><th>Vai trò</th><th class="r">Cấp</th><th>Trạng thái</th><th></th></tr></thead><tbody>'+S.accounts.map(u=>{const r=u.roleId==="super"?{name:"Super Admin"}:(roleById(u.roleId)||{});const me=UI.acct&&u.id===UI.acct.id;const ok=isSuper()||levelOf(u)<myLevel();return"<tr><td>"+esc(u.name)+(me?' <span class="pill">Bạn</span>':"")+"</td><td>"+esc(u.id)+"</td><td>"+esc(r.name||"—")+'</td><td class="r num">'+levelOf(u)+"</td><td>"+(u.active===false?"Đã khóa":"Hoạt động")+'</td><td class="r">'+(ok?'<button class="btn plain sm" data-act="uedit" data-id="'+u.id+'">Sửa / đặt lại mật khẩu</button>'+(me?"":' <button class="btn plain sm" data-act="udel" data-id="'+u.id+'">Xóa</button>'):'<span class="small muted">Không đủ cấp</span>')+"</td></tr>"}).join("")+"</tbody></table></div>":loadingOrEmpty("accounts","Chưa có tài khoản nào.")));

adm("admin-settings",()=>{const s=settings(),hide=s.hide||[];
  const blocks=[["notices","Thông báo nổi bật"],["shortcuts","Lối tắt nhanh"],["regs","Quy định mới"],["deduction","Trừ điểm rèn luyện"],["stats","Thống kê công khai"],["blog","Blog mới nhất"],["contact","Liên hệ nhanh"]];
  return '<h1>Cài đặt</h1><form class="card stack" data-form="settings"><h3>Thông tin trang</h3><div class="grid2"><label class="f">Tên<input name="name" value="'+esc(s.name)+'"></label><label class="f">Năm học<input name="year" value="'+esc(s.year)+'"></label></div><label class="f">Khẩu hiệu<input name="slogan" value="'+esc(s.slogan)+'"></label><label class="f">Tiêu đề trang chủ<input name="heroTitle" value="'+esc(s.heroTitle)+'"></label><label class="f">Mô tả trang chủ<textarea name="heroText" rows="2">'+esc(s.heroText)+'</textarea></label><label class="f">Màu chủ đạo<select name="brand"><option value="blue"'+(s.brand!=="red"?" selected":"")+'>Xanh Đoàn</option><option value="red"'+(s.brand==="red"?" selected":"")+">Đỏ truyền thống</option></select></label>"
  +'<h3>Liên hệ</h3><div class="grid2"><label class="f">Địa chỉ<input name="address" value="'+esc(s.address)+'"></label><label class="f">Giờ tiếp<input name="hours" value="'+esc(s.hours)+'"></label><label class="f">Email<input name="email" value="'+esc(s.email)+'"></label><label class="f">Điện thoại<input name="phone" value="'+esc(s.phone)+"\"></label></div><h3>Form góp ý</h3><div class=\"grid3\"><label class=\"f\">Hạn xử lý (ngày làm việc)<input name=\"deadline\" type=\"number\" min=\"1\" value=\""+s.deadline+'"></label><label class="f">Số ảnh tối đa<input name="maxImages" type="number" min="0" max="5" value="'+s.maxImages+'"></label><label class="f">Dung lượng ảnh (MB)<input name="maxMB" type="number" min="1" max="10" value="'+s.maxMB+'"></label></div><div class="row">'+Object.entries(TYPES).map(([k,v])=>'<label class="row"><input type="checkbox" name="en_'+k+'"'+((s.enabled||{})[k]!==false?" checked":"")+"> Nhận “"+v[0]+"”</label>").join("")+"</div>"
  +'<h3>Khối hiển thị ở trang chủ</h3><div class="row">'+blocks.map(([k,l])=>'<label class="row"><input type="checkbox" name="b_'+k+'"'+(hide.includes(k)?"":" checked")+"> "+l+"</label>").join("")+'</div><h3>Bảo trì</h3><label class="row"><input type="checkbox" name="maintenance"'+(s.maintenance?" checked":"")+"> Bật chế độ bảo trì (quản trị viên vẫn vào được)</label><div class=\"row\"><button class=\"btn\" type=\"submit\">Lưu cài đặt</button></div></form>"
  +'<div class="card stack"><h3>Sao lưu</h3><p class="muted small">Tải toàn bộ dữ liệu nội dung (không gồm ảnh đính kèm) thành tệp JSON.</p><div><button class="btn plain" data-act="backup">Tải bản sao lưu</button></div></div>'});

adm("admin-audit",()=>'<h1>Nhật ký thao tác</h1>'+(S.audit.length?'<div class="tablewrap"><table><thead><tr><th>Thời gian</th><th>Vai trò</th><th>Thao tác</th><th>Đối tượng</th><th>Chi tiết</th></tr></thead><tbody>'+[...S.audit].sort((a,b)=>b.at-a.at).slice(0,200).map(a=>'<tr><td class="num">'+fdt(a.at)+"</td><td>"+esc(a.role)+"</td><td>"+esc(a.action)+"</td><td>"+esc(a.entity)+"</td><td>"+esc(a.detail)+"</td></tr>").join("")+"</tbody></table></div>":loadingOrEmpty("audit","Chưa có thao tác nào được ghi.")));

/* ============ hộp thoại ============ */
function modal(html){$("#modal").innerHTML=html;const d=$("#modal .dlg");if(d)d.scrollTop=0}
function closeModal(){$("#modal").innerHTML="";UI.rd=null}
function formModal(o){UI.fm=o;
  const d=o.data||{};
  modal('<div class="dlg"><div class="hd"><h2>'+esc(o.title)+'</h2><span class="sp"></span><button class="btn plain sm" data-act="close">Đóng</button></div><form class="stack" data-form="gen">'
  +o.fields.map(f=>{const v=d[f.k]??f.def??"";let inp;
    if(f.t==="textarea")inp='<textarea name="'+f.k+'" rows="'+(f.rows||4)+'"'+(f.req?" required":"")+">"+esc(v)+"</textarea>";
    else if(f.t==="select")inp='<select name="'+f.k+'">'+f.opts.map(op=>'<option value="'+esc(op[0])+'"'+(String(v)===String(op[0])?" selected":"")+">"+esc(op[1])+"</option>").join("")+"</select>";
    else if(f.t==="check")return'<label class="row"><input type="checkbox" name="'+f.k+'"'+((d[f.k]??f.def)?" checked":"")+"> "+esc(f.l)+"</label>";
    else inp='<input name="'+f.k+'" type="'+(f.t||"text")+'" value="'+esc(v)+'"'+(f.req?" required":"")+(f.min!=null?' min="'+f.min+'"':"")+">";
    return'<label class="f">'+esc(f.l)+(f.req?" *":"")+(f.hint?'<span class="hint">'+esc(f.hint)+"</span>":"")+inp+"</label>"}).join("")
  +(o.extra||"")+'<div class="row"><button class="btn" type="submit">Lưu</button>'+(o.more?'<button class="btn plain" type="submit" data-more="1">Lưu &amp; thêm tiếp</button>':"")+'<button class="btn ghost" type="button" data-act="close">Hủy</button></div></form></div>')}
function confirmBox(msg,fn){UI.cf=fn;modal('<div class="dlg"><h2>Xác nhận</h2><p>'+esc(msg)+'</p><div class="row"><button class="btn danger" data-act="cfok">Xóa</button><button class="btn ghost" data-act="close">Hủy</button></div></div>')}

/* --- bộ soạn vai trò --- */
function roleModal(r){
  const d=UI.rd||(UI.rd={id:r?r.id:null,name:r?r.name:"",description:r?r.description||"":"",level:r?r.level:20,perms:new Set(r?r.permissions:[]),danger:null});
  const rn=$("#rn");if(rn){d.name=rn.value;d.description=$("#rd").value;d.level=+$("#rl").value}
  const mine=myPerms(),isP=p=>mine.has("*")||mine.has(p),L=myLevel();
  const lv=[80,60,40,20,10].filter(x=>x<L||(L===100&&x<=80));
  const name={80:"Admin",60:"Quản lý",40:"Biên tập viên",20:"Cộng tác viên",10:"Chuyên trách"};
  const ok=(p)=>{const a=ALLP.find(x=>x.code===p);return isP(p)};
  modal('<div class="dlg wide"><div class="hd"><h2>'+(d.id?"Sửa vai trò":"Tạo vai trò mới")+'</h2><span class="sp"></span><button class="btn plain sm" data-act="close">Đóng</button></div><div class="grid2"><label class="f">Tên *<input id="rn" value="'+esc(d.name)+'"></label><label class="f">Cấp bậc<select id="rl">'+lv.map(x=>'<option value="'+x+'"'+(d.level===x?" selected":"")+">"+x+" – "+name[x]+"</option>").join("")+'</select></label></div><label class="f">Mô tả<input id="rd" value="'+esc(d.description)+'"></label><p class="small muted">Chỉ chọn được cấp thấp hơn cấp của bạn (hiện là '+L+"). Quyền bạn không có sẽ bị khóa.</p>"
  +'<div class="row"><span class="small muted">Mẫu nhanh:</span>'+Object.keys(PRESETS).map(k=>'<button class="btn plain sm" data-act="rpreset" data-k="'+esc(k)+'">'+esc(k)+"</button>").join("")+'<button class="btn plain sm" data-act="rpreset" data-k="">Trống</button></div>'
  +(d.danger?'<div class="notice"><b>Quyền nhạy cảm:</b> “'+esc(ALLP.find(x=>x.code===d.danger).label)+'” cho phép thay đổi hoặc xóa dữ liệu. Chắc chắn cấp?<div class="row" style="margin-top:8px"><button class="btn sm danger" data-act="rdyes">Cấp quyền</button><button class="btn sm plain" data-act="rdno">Hủy</button></div></div>':"")
  +PERMS.map(g=>{const all=g[2].every(p=>d.perms.has(p[0]));return'<div class="permgrp"><label><input type="checkbox" data-act="rgrp" data-g="'+g[1]+'"'+(all?" checked":"")+"> <b>"+g[0]+"</b></label>"+g[2].map(p=>{const dis=!isP(p[0]);return'<label class="'+(dis?"dis":"")+'" title="'+(dis?"Bạn không có quyền này":p[2]?"Cần có "+p[2]:"")+'"><input type="checkbox" data-act="rperm" data-p="'+p[0]+'"'+(d.perms.has(p[0])?" checked":"")+(dis?" disabled":"")+"> <span>"+p[1]+(p[3]?' <span style="color:var(--danger)" title="Nhạy cảm">⚠</span>':"")+" <code>"+p[0]+"</code>"+(dis?" (khóa)":"")+"</span></label>"}).join("")+"</div>"}).join("")
  +(d.perms.has("posts.edit.own")&&d.perms.has("posts.edit.all")?'<p class="small" style="color:var(--warn)">Gợi ý: đã có “Sửa mọi bài”, có thể bỏ “Sửa bài mình”.</p>':"")
  +'<div class="row"><span class="small muted">Đã chọn: '+d.perms.size+'/32 quyền</span><span class="sp"></span><button class="btn ghost" data-act="close">Hủy</button><button class="btn" data-act="rsave">'+(d.id?"Lưu vai trò":"Tạo vai trò")+"</button></div></div>")}
const PRESETS={
 "Quản lý nội dung":["pages.view","pages.create","pages.edit","pages.delete","pages.publish","posts.view","posts.create","posts.edit.own","posts.edit.all","posts.delete","posts.publish","taxonomy.manage","comments.moderate","comments.reply","media.upload","media.delete","menus.edit","widgets.edit","templates.manage"],
 "Quản lý Đoàn vụ":["feedback.view","feedback.process","feedback.assign","feedback.export","feedback.delete","discipline.manage","regulations.manage","deduction.manage"],
 "Biên tập viên":["pages.view","pages.edit","posts.view","posts.create","posts.edit.own","posts.edit.all","posts.publish","media.upload","comments.moderate","comments.reply"],
 "Cộng tác viên":["posts.view","posts.create","posts.edit.own","media.upload"],
 "Người duyệt đơn":["feedback.view","feedback.process","feedback.export"],
 "Nhập liệu quy định":["regulations.manage","deduction.manage"],
 "Chỉ xem":["pages.view","posts.view","feedback.view"]};
function setPerm(d,p,on){const info=ALLP.find(x=>x.code===p);
  if(on){d.perms.add(p);if(info.dep)setPerm(d,info.dep,true)}
  else{d.perms.delete(p);ALLP.filter(x=>x.dep===p).forEach(x=>setPerm(d,x.code,false))}}

/* ============ sự kiện ============ */
const ACT={
 close:()=>closeModal(),
 post:(d)=>{UI.post=d.id;UI.keep=route()!=="blog";go("blog")},postback:()=>{UI.post=null;render()},postcat:d=>{UI.postCat=d.id;render()},
 reg:d=>{UI.reg=d.id;UI.keep=route()!=="quy-dinh";go("quy-dinh")},regback:()=>{UI.reg=null;render()},regcat:d=>{UI.regCat=d.id;render()},
 scrollto:d=>{const e=document.getElementById(d.id);if(e)e.scrollIntoView({behavior:"smooth",block:"start"})},
 copy:async(d)=>{try{await navigator.clipboard.writeText(d.v);toast("Đã sao chép mã")}catch(e){const r=document.createRange();r.selectNodeContents($("#codev"));const s=getSelection();s.removeAllRanges();s.addRange(r);toast("Hãy chép mã đang được chọn")}},
 newfb:()=>{UI.sent=null;UI.files=[];render()},
 rmfile:d=>{UI.files.splice(+d.i,1);thumbs()},
 fbopen:d=>openFb(d.id),
 fbexport:()=>saveFile("don-gop-y.csv",fbCSV()),
 fbdel:d=>confirmBox("Xóa mềm đơn này? Đơn sẽ ẩn khỏi danh sách.",async()=>{if(await w(()=>setMeta(d.id,{deleted:true}),"Đã xóa"))audit("Xóa mềm","Đơn góp ý",d.id);closeModal()}),
 cfok:async()=>{const f=UI.cf;UI.cf=null;closeModal();f&&await f()},
 /* trừ điểm */
 dsec:d=>{const x=S.sections.find(s=>s.id===d.id)||{};formModal({title:d.id?"Sửa mục":"Tạo mục",data:x,fields:[{k:"name",l:"Tên mục",req:1},{k:"description",l:"Mô tả",t:"textarea",rows:2},{k:"visible",l:"Hiển thị công khai",t:"check",def:true}],
   onSave:async v=>{const doc={name:v.name,description:v.description,visible:v.visible,slug:x.slug||slug(v.name),order:x.order??S.sections.length};
     if(await w(()=>col("sections").doc(d.id||undefined).set(doc),"Đã lưu mục"))audit(d.id?"Sửa":"Tạo","Mục trừ điểm",v.name)}})},
 dadd:d=>dedForm(null,d.sec),
 dedit:d=>dedForm(S.items.find(i=>i.id===d.id)),
 ddel:d=>{const i=S.items.find(x=>x.id===d.id);confirmBox("Xóa quy định “"+i.title+"”?",async()=>{if(await w(()=>col("items").doc(d.id).delete(),"Đã xóa"))audit("Xóa","Điểm trừ",i.title)})},
 dmove:async d=>{const i=S.items.find(x=>x.id===d.id),its=S.items.filter(x=>x.section===i.section).sort((a,b)=>(a.order||0)-(b.order||0));const ix=its.findIndex(x=>x.id===i.id),j=ix+(+d.d);if(j<0||j>=its.length)return;
   const arr=its.map(x=>x.id);arr.splice(ix,1);arr.splice(j,0,i.id);for(let k=0;k<arr.length;k++){const it=S.items.find(x=>x.id===arr[k]);if((it.order||0)!==k)await w(()=>col("items").doc(arr[k]).update({order:k}))}},
 dimport:()=>formModal({title:"Nhập từ Excel",data:{},fields:[{k:"text",l:"Dán dữ liệu (3 cột: Mục, Tiêu đề, Điểm)",t:"textarea",rows:8,req:1,hint:"Sao chép các dòng từ Excel rồi dán vào đây. Mục chưa có sẽ được tạo tự động."}],onSave:importDed}),
 /* quy định */
 rcat:d=>{const x=S.regcats.find(c=>c.id===d.id)||{};formModal({title:d.id?"Sửa nhóm":"Tạo nhóm",data:x,fields:[{k:"name",l:"Tên nhóm",req:1},{k:"visible",l:"Hiển thị",t:"check",def:true}],onSave:async v=>{if(await w(()=>col("regcats").doc(d.id||undefined).set({name:v.name,visible:v.visible,order:x.order??S.regcats.length}),"Đã lưu nhóm"))audit("Lưu","Nhóm quy định",v.name)}})},
 redit:d=>{const x=S.regs.find(r=>r.id===d.id)||{};const dd={...x,pen:(x.penalties||[]).map(p=>p.join(" | ")).join("\n"),effective:x.effective||""};
   formModal({title:d.id?"Sửa văn bản":"Thêm văn bản",data:dd,fields:[{k:"title",l:"Tiêu đề",req:1},{k:"cat",l:"Nhóm",t:"select",opts:[["","— Chọn nhóm —"],...S.regcats.map(c=>[c.id,c.name])]},{k:"summary",l:"Tóm tắt",t:"textarea",rows:2,req:1,hint:"Học sinh đọc phần này đầu tiên."},{k:"body",l:"Nội dung chi tiết",t:"textarea",rows:9,hint:"Dùng ## cho tiêu đề mục, - cho danh sách."},{k:"pen",l:"Lỗi thường gặp & mức xử lý",t:"textarea",rows:4,hint:"Mỗi dòng: Lỗi | Mức xử lý"},{k:"effective",l:"Ngày hiệu lực",t:"date"},{k:"status",l:"Trạng thái",t:"select",opts:[["draft","Nháp"],["published","Công khai"]]},{k:"pinned",l:"Ghim",t:"check"}],
     onSave:async v=>{const doc={title:v.title,slug:x.slug||slug(v.title),cat:v.cat,summary:v.summary,body:v.body,penalties:String(v.pen||"").split("\n").map(l=>l.split("|").map(s=>s.trim())).filter(a=>a[0]&&a[1]),effective:v.effective,status:v.status,pinned:v.pinned,updatedAt:Date.now()};
       if(await w(()=>col("regs").doc(d.id||undefined).set(doc),"Đã lưu văn bản"))audit(d.id?"Sửa":"Tạo","Quy định",v.title)}})},
 rdel:d=>{const r=S.regs.find(x=>x.id===d.id);confirmBox("Xóa văn bản “"+r.title+"”?",async()=>{if(await w(()=>col("regs").doc(d.id).delete(),"Đã xóa"))audit("Xóa","Quy định",r.title)})},
 /* kỷ luật */
 cedit:d=>{const x=S.cases.find(c=>c.id===d.id)||{};formModal({title:d.id?"Sửa vụ việc":"Thêm vụ việc",data:x,fields:[{k:"code",l:"Mã vụ việc",req:1,def:"KL-"+new Date().getFullYear()+"-"+String(S.cases.length+1).padStart(3,"0")},{k:"type",l:"Loại vi phạm",req:1},{k:"penalty",l:"Hình thức xử lý",req:1},{k:"decidedAt",l:"Ngày quyết định",t:"date"},{k:"description",l:"Mô tả (đã ẩn danh)",t:"textarea",req:1,hint:"Không ghi tên, lớp hay chi tiết nhận diện."},{k:"visible",l:"Công khai",t:"check",def:true},{k:"pinned",l:"Ghim",t:"check"}],
   onSave:async v=>{if(await w(()=>col("cases").doc(d.id||undefined).set(v),"Đã lưu vụ việc"))audit(d.id?"Sửa":"Tạo","Kỷ luật",v.code)}})},
 cdel:d=>{const c=S.cases.find(x=>x.id===d.id);confirmBox("Xóa vụ việc "+c.code+"?",async()=>{if(await w(()=>col("cases").doc(d.id).delete(),"Đã xóa"))audit("Xóa","Kỷ luật",c.code)})},
 /* blog */
 pedit:d=>{const x=S.posts.find(p=>p.id===d.id)||{};const dd={...x,publishDate:x.publishAt?new Date(x.publishAt).toISOString().slice(0,10):new Date().toISOString().slice(0,10)};
   formModal({title:d.id?"Sửa bài viết":"Viết bài",data:dd,fields:[{k:"title",l:"Tiêu đề",req:1},{k:"category",l:"Chuyên mục",def:"Tin tức"},{k:"excerpt",l:"Mô tả ngắn",t:"textarea",rows:2},{k:"body",l:"Nội dung",t:"textarea",rows:9,hint:"## tiêu đề mục, - danh sách."},{k:"author",l:"Tác giả",def:"BCH Đoàn"},{k:"publishDate",l:"Ngày đăng (chọn ngày sau hôm nay để lên lịch)",t:"date"},{k:"status",l:"Trạng thái",t:"select",opts:[["draft","Nháp"],["published","Công khai"]]},{k:"pinned",l:"Ghim thành thông báo",t:"check"}],
     onSave:async v=>{if(v.status==="published"&&!can("posts.publish")){toast("Vai trò này chưa có quyền công khai bài.");return}
       const doc={title:v.title,slug:x.slug||slug(v.title),category:v.category,excerpt:v.excerpt,body:v.body,author:v.author,publishAt:new Date(v.publishDate||Date.now()).getTime(),status:v.status,pinned:v.pinned};
       if(await w(()=>col("posts").doc(d.id||undefined).set(doc),"Đã lưu bài"))audit(d.id?"Sửa":"Tạo","Bài viết",v.title)}})},
 pdel:d=>{const p=S.posts.find(x=>x.id===d.id);confirmBox("Xóa bài “"+p.title+"”?",async()=>{if(await w(()=>col("posts").doc(d.id).delete(),"Đã xóa"))audit("Xóa","Bài viết",p.title)})},
 /* vai trò */
 redrole:d=>{UI.rd=null;roleModal(d.id?roleById(d.id):null)},
 rperm:(d,t)=>{if(t.checked&&ALLP.find(x=>x.code===d.p).danger){t.checked=false;UI.rd.danger=d.p;roleModal();return}setPerm(UI.rd,d.p,t.checked);roleModal()},
 rgrp:(d,t)=>{const g=PERMS.find(x=>x[1]===d.g);g[2].forEach(p=>{if(!(myPerms().has("*")||myPerms().has(p[0])))return;if(t.checked&&p[3])return;setPerm(UI.rd,p[0],t.checked)});roleModal()},
 rdyes:()=>{const p=UI.rd.danger;UI.rd.danger=null;setPerm(UI.rd,p,true);roleModal()},rdno:()=>{UI.rd.danger=null;roleModal()},
 rpreset:d=>{const m=myPerms();UI.rd.perms=new Set((PRESETS[d.k]||[]).filter(p=>m.has("*")||m.has(p)));roleModal()},
 rsave:async()=>{const d=UI.rd;d.name=$("#rn").value.trim();d.description=$("#rd").value;d.level=+$("#rl").value;
   if(!d.name){toast("Hãy nhập tên vai trò.");return}
   if(d.level>=myLevel()){toast("Cấp bậc phải thấp hơn cấp của bạn.");return}
   const m=myPerms();if(![...d.perms].every(p=>m.has("*")||m.has(p))){toast("Bạn không thể cấp quyền mình không có.");return}
   const doc={name:d.name,description:d.description,level:d.level,permissions:[...d.perms],system:false};
   if(await w(()=>col("roles").doc(d.id||undefined).set(doc),"Đã lưu vai trò")){audit(d.id?"Sửa":"Tạo","Vai trò",d.name);closeModal()}},
 dupr:async d=>{const r=roleById(d.id);if(await w(()=>col("roles").add({...r,id:undefined,name:r.name+" (bản sao)"}),"Đã nhân bản"))audit("Nhân bản","Vai trò",r.name)},
 delr:d=>{const r=roleById(d.id);if(S.accounts.some(u=>u.roleId===d.id)){toast("Không thể xóa vai trò đang có người dùng.");return}confirmBox("Xóa vai trò “"+r.name+"”?",async()=>{if(await w(()=>col("roles").doc(d.id).delete(),"Đã xóa"))audit("Xóa","Vai trò",r.name)})},
 /* người dùng */
 uedit:d=>{const x=S.accounts.find(u=>u.id===d.id)||{};const opts=[...(isSuper()?[["super","Super Admin (toàn quyền)"]]:[]),...S.roles.filter(r=>r.level<myLevel()).map(r=>[r.id,r.name+" (cấp "+r.level+")"])];
   const fields=[...(d.id?[]:[{k:"username",l:"Tên đăng nhập",req:1,hint:"Chữ thường, số, . _ -"}]),{k:"name",l:"Họ tên",req:1},{k:"password",l:d.id?"Mật khẩu mới":"Mật khẩu",t:"password",req:!d.id,hint:d.id?"Để trống nếu không đổi. Tối thiểu 8 ký tự.":"Tối thiểu 8 ký tự."},{k:"roleId",l:"Vai trò",t:"select",opts},{k:"active",l:"Cho phép đăng nhập",t:"check",def:true}];
   formModal({title:d.id?"Sửa tài khoản":"Cấp tài khoản",data:x,fields,onSave:async v=>{
     const id=d.id||String(v.username||"").trim().toLowerCase(),pw=String(v.password||"");
     if(!d.id){if(!/^[a-z0-9._-]{3,30}$/.test(id)){toast("Tên đăng nhập 3–30 ký tự: chữ thường, số, . _ -");return false}if(S.accounts.some(a=>a.id===id)){toast("Tên đăng nhập đã tồn tại.");return false}}
     if((!d.id||pw)&&pw.length<8){toast("Mật khẩu tối thiểu 8 ký tự.");return false}
     if(!v.roleId){toast("Hãy chọn vai trò.");return false}
     const me=UI.acct&&id===UI.acct.id;
     const doc={name:v.name,roleId:me?UI.acct.roleId:v.roleId,active:me?true:v.active};
     if(pw){doc.salt=newSalt();doc.hash=await pwHash(pw,doc.salt)}
     const ok=await w(()=>d.id?col("accounts").doc(id).update(doc):col("accounts").doc(id).set({...doc,createdAt:Date.now()}),"Đã lưu tài khoản");
     if(ok)audit(d.id?(pw?"Sửa / đặt lại mật khẩu":"Sửa"):"Cấp tài khoản","Tài khoản",id);return ok}})},
 udel:d=>{const u=S.accounts.find(x=>x.id===d.id);confirmBox("Xóa tài khoản “"+u.id+"”?",async()=>{if(await w(()=>col("accounts").doc(d.id).delete(),"Đã xóa"))audit("Xóa","Tài khoản",u.id)})},
 logout:()=>{audit("Đăng xuất","Tài khoản",UI.acct?UI.acct.id:"");doLogout();render()},
 chpw:()=>formModal({title:"Đổi mật khẩu",data:{},fields:[{k:"cur",l:"Mật khẩu hiện tại",t:"password",req:1},{k:"nw",l:"Mật khẩu mới",t:"password",req:1,hint:"Tối thiểu 8 ký tự"}],onSave:async v=>{
   if((await pwHash(v.cur,UI.acct.salt))!==UI.acct.hash){toast("Mật khẩu hiện tại chưa đúng.");return false}
   if(v.nw.length<8){toast("Mật khẩu mới tối thiểu 8 ký tự.");return false}
   const salt=newSalt(),hash=await pwHash(v.nw,salt);const ok=await w(()=>col("accounts").doc(UI.acct.id).update({salt,hash}),"Đã đổi mật khẩu");if(ok)audit("Đổi mật khẩu","Tài khoản",UI.acct.id);return ok}}),
 backup:()=>{const o={exportedAt:new Date().toISOString()};["sections","items","regcats","regs","cases","posts","roles","staff","settings"].forEach(k=>o[k]=S[k]);saveFile("sao-luu-doan-truong.json",JSON.stringify(o,null,1))}
};
function dedForm(x,secId){x=x||{};
  const sid=x.section||secId||"";
  formModal({title:x.id?"Sửa quy định trừ điểm":"Thêm quy định trừ điểm",more:!x.id,data:{...x,section:sid},
   fields:[{k:"section",l:"Mục",t:"select",req:1,opts:[["","— Chọn mục —"],...S.sections.map(s=>[s.id,s.name])]},{k:"title",l:"Tiêu đề",req:1},{k:"points",l:"Điểm trừ (số dương)",t:"number",min:1,req:1},{k:"note",l:"Ghi chú",hint:"Ví dụ: trừ mỗi lần vi phạm"},{k:"status",l:"Trạng thái",t:"select",opts:[["published","Công khai"],["draft","Nháp"]]}],
   extra:(x.rev&&x.rev.length?'<details class="small"><summary>Lịch sử chỉnh sửa ('+x.rev.length+')</summary>'+x.rev.map(r=>"<div>"+fdt(r.at)+": "+esc(r.title)+" · "+r.points+" điểm</div>").join("")+"</details>":""),
   onSave:async(v,more)=>{if(!v.section){toast("Hãy chọn mục.");return false}const pts=Math.round(+v.points);if(!(pts>0)){toast("Điểm trừ phải lớn hơn 0.");return false}
     const dup=S.items.find(i=>i.section===v.section&&norm(i.title)===norm(v.title)&&i.id!==x.id);if(dup&&!UI.dupOk){UI.dupOk=true;toast("Đã có quy định trùng tiêu đề trong mục này. Nhấn Lưu lần nữa nếu vẫn muốn thêm.");return false}UI.dupOk=false;
     const rev=x.id?[...(x.rev||[]),{at:Date.now(),title:x.title,points:x.points}].slice(-10):[];
     const doc={section:v.section,title:v.title,points:pts,note:v.note,status:v.status,order:x.order??S.items.filter(i=>i.section===v.section).length,rev};
     const ok=await w(()=>col("items").doc(x.id||undefined).set(doc),"Đã lưu");if(ok){audit(x.id?"Sửa":"Tạo","Điểm trừ",v.title+" ("+pts+")");
       if(more){dedForm(null,v.section);return"stay"}}return ok}})}
async function importDed(v){
  const lines=String(v.text||"").split("\n").map(l=>l.split(/\t|;/).map(s=>s.trim())).filter(a=>a.length>=3&&+a[2]>0);
  if(!lines.length){toast("Không có dòng hợp lệ (cần 3 cột, điểm > 0).");return false}
  const secs={};S.sections.forEach(s=>secs[norm(s.name)]=s.id);let n=0;
  for(const [m,t,p] of lines){let id=secs[norm(m)];
    if(!id){const ref=col("sections").doc();await w(()=>ref.set({name:m,slug:slug(m),order:Object.keys(secs).length,visible:true}));id=ref.id;secs[norm(m)]=id}
    if(await w(()=>col("items").add({section:id,title:t,points:Math.round(+p),status:"published",order:900+n,rev:[]})))n++}
  toast("Đã nhập "+n+" dòng");audit("Nhập Excel","Điểm trừ",n+" dòng");return true}

document.addEventListener("click",e=>{
  const t=e.target.closest("[data-act]");if(!t)return;
  if(t.tagName==="INPUT")return;
  const fn=ACT[t.dataset.act];if(fn){if(t.tagName==="A")e.preventDefault();fn(t.dataset,t,e)}});
document.addEventListener("change",e=>{const t=e.target;
  if(t.matches("input[data-act]")){const fn=ACT[t.dataset.act];fn&&fn(t.dataset,t,e);return}
  if(t.dataset.chg==="dtitle"&&t.value.trim())w(()=>col("items").doc(t.dataset.id).update({title:t.value.trim()}),"Đã lưu");
  if(t.dataset.chg==="dpts"){const n=Math.round(+t.value);if(n>0)w(()=>col("items").doc(t.dataset.id).update({points:n}),"Đã lưu");else{toast("Điểm trừ phải lớn hơn 0.");render()}}});
document.addEventListener("keydown",e=>{if(e.key==="Enter"&&e.target.dataset&&e.target.dataset.chg)e.target.blur();if(e.key==="Escape"&&$("#modal").innerHTML)closeModal()});

const FORMS={};
FORMS.login=async f=>{const fd=new FormData(f),err=$("#lerr");err.textContent="";
  UI.fails=UI.fails.filter(t=>Date.now()-t<60000);if(UI.fails.length>=5)return err.textContent="Sai quá 5 lần. Thử lại sau 1 phút.";
  const id=String(fd.get("username")).trim().toLowerCase(),a=S.accounts.find(x=>x.id===id);
  const ok=a&&a.active!==false&&(await pwHash(String(fd.get("password")),a.salt))===a.hash;
  if(!ok){UI.fails.push(Date.now());err.textContent="Sai tên đăng nhập hoặc mật khẩu.";return}
  UI.acct=a;UI.sess=id;UI.lastAct=Date.now();try{sessionStorage.setItem("doan_sess",id)}catch(e){}
  audit("Đăng nhập","Tài khoản",id);render()};
FORMS.setup=async f=>{const fd=new FormData(f),err=$("#lerr");err.textContent="";
  const id=String(fd.get("username")).trim().toLowerCase(),pw=String(fd.get("password"));
  if(!/^[a-z0-9._-]{3,30}$/.test(id))return err.textContent="Tên đăng nhập 3–30 ký tự: chữ thường, số, . _ -";
  if(pw.length<8)return err.textContent="Mật khẩu tối thiểu 8 ký tự.";
  if(pw!==fd.get("password2"))return err.textContent="Hai mật khẩu chưa khớp.";
  if(S.accounts.length)return err.textContent="Đã có tài khoản.";
  const salt=newSalt(),hash=await pwHash(pw,salt),doc={name:String(fd.get("name")).trim()||id,roleId:"super",active:true,salt,hash,createdAt:Date.now()};
  if(await w(()=>col("accounts").doc(id).set(doc),"Đã tạo Super Admin")){UI.acct={id,...doc};UI.sess=id;try{sessionStorage.setItem("doan_sess",id)}catch(e){}audit("Thiết lập","Super Admin",id);render()}};
function FORMS_INIT(){}
FORMS.hsearch=f=>{UI.q=$("#hq").value;go("tim-kiem");render()};
FORMS.hsearch2=f=>{UI.q=$("#sq").value;render()};
FORMS.homelookup=f=>doLookup($("#hcode").value);
FORMS.lookup=f=>doLookup($("#lcode").value);
FORMS.gen=async(f,ev)=>{const o=UI.fm;const fd=new FormData(f),v={};
  o.fields.forEach(x=>{v[x.k]=x.t==="check"?fd.has(x.k):x.t==="number"?(+fd.get(x.k)):fd.get(x.k)});
  const more=ev&&ev.submitter&&ev.submitter.dataset.more==="1";
  const r=await o.onSave(v,more);if(r===false)return;if(r!=="stay")closeModal()};
FORMS.settings=async f=>{const fd=new FormData(f),g=k=>fd.get(k);
  const hide=["notices","shortcuts","regs","deduction","stats","blog","contact"].filter(k=>!fd.has("b_"+k));
  const doc={name:g("name"),year:g("year"),slogan:g("slogan"),heroTitle:g("heroTitle"),heroText:g("heroText"),brand:g("brand"),address:g("address"),hours:g("hours"),email:g("email"),phone:g("phone"),deadline:+g("deadline")||7,maxImages:Math.min(5,Math.max(0,+g("maxImages")||0)),maxMB:+g("maxMB")||5,hide,maintenance:fd.has("maintenance"),enabled:{suggestion:fd.has("en_suggestion"),self:fd.has("en_self"),report:fd.has("en_report")}};
  if(await w(()=>db.doc("settings/site").set(doc),"Đã lưu cài đặt"))audit("Lưu","Cài đặt","")};
FORMS.fbsave=async f=>{const id=f.dataset.id,fb=fbAll().find(x=>x.id===id),fd=new FormData(f);
  const upd={status:fd.get("status")||fb.status,assigned:fd.get("assigned")??fb.assigned??"",adminNote:fd.get("note")??fb.adminNote??""};
  const ok=await w(async()=>{await setMeta(fb.code,upd);await col("status").doc(fb.code).set({status:upd.status,publicNote:fd.get("pub")??(S.status.find(x=>x.id===fb.code)||{}).publicNote??"",updatedAt:Date.now()})},"Đã cập nhật đơn");
  if(ok){audit("Cập nhật","Đơn "+fb.code,STAT[upd.status]);closeModal()}};
FORMS.contact=async f=>{const fd=new FormData(f);if(!UI.uid){toast("Hãy đăng nhập để gửi tin nhắn.");return}if(await w(()=>col("contacts").doc(UI.uid).collection("msgs").add({name:fd.get("name"),contact:fd.get("contact"),msg:fd.get("msg"),at:Date.now()}),"Đã gửi tin nhắn"))f.reset()};
FORMS.feedback=async f=>{
  const fd=new FormData(f),err=$("#fberr"),s=settings();err.textContent="";
  const title=String(fd.get("title")).trim(),content=String(fd.get("content")).trim(),an=fd.get("anonymity");
  if(!title)return err.textContent="Hãy nhập tiêu đề.";
  if(content.length<50)return err.textContent="Nội dung cần ít nhất 50 ký tự (hiện "+content.length+").";
  if(!fd.has("oath"))return err.textContent="Hãy tick cam kết trung thực.";
  try{const ts=JSON.parse(localStorage.getItem("fbts")||"[]").filter(t=>Date.now()-t<36e5);if(ts.length>=3)return err.textContent="Bạn đã gửi 3 đơn trong 1 giờ. Vui lòng thử lại sau.";}catch(e){}
  if(!db||!UI.uid)return err.textContent="Chưa kết nối được kho dữ liệu. Hãy đăng nhập rồi gửi lại.";
  $("#fbsub").disabled=true;
  const code=newCode();
  const doc={code,type:fd.get("type"),category:fd.get("category"),title,content,anonymity:an,status:"pending",createdAt:Date.now(),attachments:UI.files.length,assigned:"",adminNote:""};
  if(an!=="full"){doc.sname=fd.get("sname")||"";doc.sclass=fd.get("sclass")||"";doc.semail=fd.get("semail")||"";doc.sphone=fd.get("sphone")||""}
  const ok=await w(async()=>{const ref=col("feedback").doc(UI.uid);const sn=await ref.get();if(sn.exists)await ref.update({items:{[code]:doc}});else await ref.set({items:{[code]:doc}});await col("status").doc(code).set({status:"pending",publicNote:"",updatedAt:Date.now()});
    for(let i=0;i<UI.files.length;i++)await ref.collection("files").doc(code+"-"+i).set({code,data:UI.files[i]})});
  $("#fbsub")&&($("#fbsub").disabled=false);
  if(ok){try{const ts=JSON.parse(localStorage.getItem("fbts")||"[]").filter(t=>Date.now()-t<36e5);ts.push(Date.now());localStorage.setItem("fbts",JSON.stringify(ts))}catch(e){}
    UI.sent=code;UI.files=[];render()}};
document.addEventListener("submit",e=>{e.preventDefault();const fn=FORMS[e.target.dataset.form];if(fn)fn(e.target,e)});

/* ============ khởi động ============ */
["click","keydown"].forEach(ev=>document.addEventListener(ev,()=>{UI.lastAct=Date.now()},true));
setInterval(()=>{if(UI.acct&&Date.now()-UI.lastAct>30*60000){doLogout();toast("Đã đăng xuất do không hoạt động 30 phút.");render()}},30000);
render();
setTimeout(()=>{S._slow=true;if(!Object.values(S.loaded).every(Boolean))render()},10000);
try{
  const user=await claude.use("user");
  if(user){UI.isAdmin=!!(await user.canEdit());UI.isOwner=!!(await user.isOwner());try{UI.uid=await user.id()}catch(e){}}
  db=await claude.use("db");try{dl=await claude.use("downloads")}catch(e){}
}catch(e){}
if(db){
  listen("sections","sections");listen("items","items");listen("regcats","regcats");listen("regs","regs");listen("cases","cases");listen("posts","posts");listen("status","status");
  listen("roles","roles",true);listen("accounts","accounts",true);listen("fbmeta","fbmeta",true);if(UI.isAdmin){try{col("feedback").onSnapshot(q=>{const a=[];q.docs.forEach(d=>{const it=d.data().items||{};Object.keys(it).forEach(c=>a.push({...it[c],id:c,uid:d.id}))});S.fbraw=a;S.loaded.feedback=true;refresh()},()=>{S.loaded.feedback=true})}catch(e){S.loaded.feedback=true}}else S.loaded.feedback=true;listen("audit","audit",true);
  try{db.doc("settings/site").onSnapshot(d=>{S.settings=d.exists?d.data():{};S.loaded.settings=true;refresh()},()=>{S.loaded.settings=true})}catch(e){}
}
render();
})();
</script>

</body></html>
