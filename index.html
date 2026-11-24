<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>4-Bit Arithmetic Circuit – Interactive Project</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;600&family=IBM+Plex+Mono:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#eef2f4;--card:#fff;--ink:#14202b;--mute:#566673;--line:#cdd7de;--trace:#0e7c7b;--led:#e5322d;--ledoff:#d9e0e5;--ok:#1b8a4b;--sw:#14202b;--swt:#fff;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e161c;--card:#16212a;--ink:#e6edf2;--mute:#93a4b0;--line:#2a3a46;--trace:#3fc4c1;--led:#ff5a52;--ledoff:#2a3a46;--ok:#46d47f;--sw:#e6edf2;--swt:#0e161c;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0e161c;--card:#16212a;--ink:#e6edf2;--mute:#93a4b0;--line:#2a3a46;--trace:#3fc4c1;--led:#ff5a52;--ledoff:#2a3a46;--ok:#46d47f;--sw:#e6edf2;--swt:#0e161c;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 16px/1.55 "IBM Plex Sans",system-ui,-apple-system,"Segoe UI",sans-serif}
main{max-width:760px;margin:0 auto;padding:20px 16px 48px}
h1{font-size:1.7rem;line-height:1.2;margin:8px 0 6px;font-weight:600}
h2{font-size:1.15rem;margin:0 0 10px;font-weight:600}
p.lead{color:var(--mute);margin:0 0 18px;max-width:62ch}
section{background:var(--card);border:1px solid var(--line);border-radius:10px;padding:16px;margin:14px 0}
code,.mono{font-family:"IBM Plex Mono",ui-monospace,Menlo,Consolas,monospace}
.row{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.lbl{width:2.2rem;font-weight:600}
.bits{display:flex;gap:6px}
.bit{width:50px;height:50px;border-radius:8px;border:2px solid var(--sw);background:var(--card);color:var(--ink);font:600 1.2rem "IBM Plex Mono",monospace;cursor:pointer}
.bit[aria-pressed="true"]{background:var(--sw);color:var(--swt)}
.bit:focus-visible,.op:focus-visible,button:focus-visible{outline:3px solid var(--trace);outline-offset:2px}
.dec{font-family:"IBM Plex Mono",monospace;color:var(--mute);margin-left:4px}
.ops{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-top:6px}
.op{padding:10px 4px;border-radius:8px;border:2px solid var(--line);background:var(--card);color:var(--ink);font:600 .95rem "IBM Plex Sans",sans-serif;cursor:pointer}
.op small{display:block;font:400 .72rem "IBM Plex Mono",monospace;color:var(--mute)}
.op[aria-pressed="true"]{border-color:var(--trace);box-shadow:inset 0 0 0 1px var(--trace)}
.leds{display:flex;gap:10px;align-items:center;margin:6px 0}
.led{width:34px;height:34px;border-radius:50%;background:var(--ledoff);border:2px solid var(--line);display:grid;place-items:center;font:600 .7rem "IBM Plex Mono",monospace;color:var(--mute)}
.led.on{background:var(--led);border-color:var(--led);color:#fff;box-shadow:0 0 12px var(--led)}
.sep{width:1px;height:30px;background:var(--line);margin:0 4px}
.eq{font-family:"IBM Plex Mono",monospace;background:var(--bg);border-left:4px solid var(--trace);padding:10px 12px;border-radius:4px;margin-top:10px;overflow-x:auto;white-space:pre}
.scroll{overflow-x:auto}
table{border-collapse:collapse;width:100%;font-size:.9rem}
th,td{padding:6px 8px;border-bottom:1px solid var(--line);text-align:center;white-space:nowrap}
th{font-weight:600;color:var(--mute)}
td.mono{font-family:"IBM Plex Mono",monospace}
.pass{color:var(--ok);font-weight:600}
button.run{background:var(--trace);color:#fff;border:0;border-radius:8px;padding:10px 16px;font:600 1rem "IBM Plex Sans",sans-serif;cursor:pointer}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) button.run{color:#0e161c}}
#result{margin-left:10px;font-weight:600}
pre{background:var(--bg);padding:12px;border-radius:8px;overflow-x:auto;font-size:.8rem;line-height:1.45;margin:8px 0 0}
.note{color:var(--mute);font-size:.9rem}
@media (max-width:420px){.bit{width:44px;height:44px}.led{width:30px;height:30px}}
</style>
</head>
<body>
<main>
<h1>4-Bit Arithmetic Circuit</h1>
<p class="lead">Addition, subtraction, increment and decrement from a single 4-bit adder, a bank of 4-to-1 multiplexers and two control lines. Flip the switches and watch every signal.</p>

<section aria-label="Simulator">
<h2>Simulator</h2>
<div class="row"><span class="lbl">A</span><div class="bits" id="aBits"></div><span class="dec" id="aDec"></span></div>
<div class="row" style="margin-top:8px"><span class="lbl">B</span><div class="bits" id="bBits"></div><span class="dec" id="bDec"></span></div>
<p class="note" style="margin:10px 0 4px">Select the operation (control lines S1 S0)</p>
<div class="ops" id="ops"></div>
<div class="eq" id="eq"></div>
<p class="note" style="margin:14px 0 2px">Output</p>
<div class="leds"><div class="led" id="cout" title="Cout">C</div><div class="sep"></div><div id="fLeds" class="leds" style="margin:0"></div><span class="dec" id="fDec"></span></div>
<p class="note" id="flag" style="margin:2px 0 0"></p>
</section>

<section aria-label="Bit by bit">
<h2>Signals, bit by bit</h2>
<p class="note" style="margin-top:0">Carry ripples from bit 0 to bit 3. Y is the multiplexer output that feeds the adder.</p>
<div class="scroll"><table id="slice"></table></div>
</section>

<section aria-label="Design">
<h2>How it works</h2>
<p style="margin-top:0">The adder always computes <code>F = A + Y + Cin</code>. The multiplexers choose Y, and one XOR gate sets Cin.</p>
<div class="scroll"><table>
<tr><th>S1 S0</th><th>Operation</th><th>Y</th><th>Cin</th><th>F</th></tr>
<tr><td class="mono">00</td><td>Add</td><td class="mono">B</td><td class="mono">0</td><td class="mono">A + B</td></tr>
<tr><td class="mono">01</td><td>Subtract</td><td class="mono">B′</td><td class="mono">1</td><td class="mono">A − B</td></tr>
<tr><td class="mono">10</td><td>Increment</td><td class="mono">0000</td><td class="mono">1</td><td class="mono">A + 1</td></tr>
<tr><td class="mono">11</td><td>Decrement</td><td class="mono">1111</td><td class="mono">0</td><td class="mono">A − 1</td></tr>
</table></div>
<pre>Yi  = S1′·(Bi ⊕ S0) + S1·S0
Cin = S1 ⊕ S0

 B3..B0 ─▶ [4 × MUX 4:1] ─ Y3..Y0 ─┐
 (I0=B, I1=B′, I2=0, I3=1)         ▼
 S1,S0 ──┬──────────────────▶ [4-bit adder 7483] ─▶ F3..F0, Cout
         └─▶ [XOR] ── Cin ─────────▲
 A3..A0 ─────────────────────────────┘</pre>
<p class="note">ICs: 74LS83 adder, 2 × 74LS153 dual 4:1 mux, 74LS04 inverter, 74LS86 XOR.</p>
</section>

<section aria-label="Verification">
<h2>Verification</h2>
<div class="row"><button class="run" id="runAll">Run all 1024 tests</button><span id="result" role="status"></span></div>
<p class="note">Every operation is checked against all 16 × 16 combinations of A and B.</p>
<div class="scroll"><table id="vt"></table></div>
</section>
</main>

<script>
(function(){
var A=5,B=3,op=0;
var NAMES=["Add","Subtract","Increment","Decrement"],SYM=["A + B","A − B","A + 1","A − 1"];
function bits(n){return [(n>>3)&1,(n>>2)&1,(n>>1)&1,n&1];}
function b4(n){return (n&15).toString(2).padStart(4,"0");}
function fa(a,b,c){return {s:a^b^c,c:(a&b)|(c&(a^b))};}
function mux(i0,i1,i2,i3,s1,s0){return ((1-s1)&(1-s0)&i0)|((1-s1)&s0&i1)|(s1&(1-s0)&i2)|(s1&s0&i3);}
function circuit(a,b,o){
  var s1=o>>1,s0=o&1,cin=s1^s0,c=cin,F=0,rows=[];
  for(var i=0;i<4;i++){
    var ai=(a>>i)&1,bi=(b>>i)&1,y=mux(bi,1-bi,0,1,s1,s0),r=fa(ai,y,c);
    rows.push({i:i,a:ai,b:bi,y:y,cin:c,s:r.s,cout:r.c});
    F|=r.s<<i;c=r.c;
  }
  return {F:F,cout:c,cin:cin,rows:rows,s1:s1,s0:s0};
}
function ref(a,b,o){return ([a+b,a-b,a+1,a-1][o])&15;}
function mkBits(id,get,set){
  var el=document.getElementById(id);el.innerHTML="";
  for(var k=3;k>=0;k--)(function(k){
    var btn=document.createElement("button");btn.className="bit";btn.type="button";
    btn.setAttribute("aria-label",id[0].toUpperCase()+k);
    btn.onclick=function(){set(get()^(1<<k));render();};
    btn.dataset.k=k;el.appendChild(btn);
  })(k);
}
function paintBits(id,v){
  document.querySelectorAll("#"+id+" .bit").forEach(function(b){
    var on=(v>>b.dataset.k)&1;b.textContent=on;b.setAttribute("aria-pressed",on?"true":"false");
  });
}
function setup(){
  mkBits("aBits",function(){return A;},function(v){A=v;});
  mkBits("bBits",function(){return B;},function(v){B=v;});
  var ops=document.getElementById("ops");
  NAMES.forEach(function(n,i){
    var b=document.createElement("button");b.type="button";b.className="op";
    b.innerHTML=n+"<small>"+(i>>1)+(i&1)+"</small>";
    b.onclick=function(){op=i;render();};ops.appendChild(b);
  });
  var f=document.getElementById("fLeds");
  for(var k=3;k>=0;k--){var d=document.createElement("div");d.className="led";d.id="f"+k;d.textContent="F"+k;f.appendChild(d);}
}
function render(){
  paintBits("aBits",A);paintBits("bBits",B);
  document.getElementById("aDec").textContent="= "+A;
  document.getElementById("bDec").textContent="= "+B+(op>1?" (not used)":"");
  document.querySelectorAll(".op").forEach(function(b,i){b.setAttribute("aria-pressed",i===op?"true":"false");});
  var r=circuit(A,B,op),Y=0;
  r.rows.forEach(function(x){Y|=x.y<<x.i;});
  var raw=[A+B,A-B,A+1,A-1][op];
  document.getElementById("eq").textContent=
    "S1 S0 = "+r.s1+r.s0+"  →  "+NAMES[op]+" ("+SYM[op]+")\n"+
    "A   = "+b4(A)+"\nY   = "+b4(Y)+"\nCin = "+r.cin+"\n"+
    "F   = "+b4(A)+" + "+b4(Y)+" + "+r.cin+" = "+(r.cout?"1 ":"0 ")+b4(r.F);
  for(var k=0;k<4;k++)document.getElementById("f"+k).classList.toggle("on",!!((r.F>>k)&1));
  document.getElementById("cout").classList.toggle("on",!!r.cout);
  document.getElementById("fDec").textContent="= "+r.F;
  var msg="";
  if(op===0)msg=r.cout?"Cout = 1: the sum is more than 15 (overflow).":"Cout = 0: the sum fits in 4 bits.";
  if(op===1)msg=r.cout?"Cout = 1: no borrow, because A ≥ B.":"Cout = 0: borrow, because A < B. F is "+(r.F-16)+" in 2’s complement.";
  if(op===2)msg=r.cout?"Cout = 1: A was 1111 and wrapped to 0000.":"Cout = 0: normal increment.";
  if(op===3)msg=r.cout?"Cout = 1: normal decrement.":"Cout = 0: A was 0000, so the result underflows to 1111 (−1).";
  document.getElementById("flag").textContent=msg;
  var t="<tr><th>Bit</th><th>A</th><th>B</th><th>Y</th><th>Cin</th><th>Sum</th><th>Cout</th></tr>";
  for(var i=3;i>=0;i--){var x=r.rows[i];t+="<tr><td class='mono'>"+i+"</td><td class='mono'>"+x.a+"</td><td class='mono'>"+x.b+"</td><td class='mono'>"+x.y+"</td><td class='mono'>"+x.cin+"</td><td class='mono'>"+x.s+"</td><td class='mono'>"+x.cout+"</td></tr>";}
  document.getElementById("slice").innerHTML=t;
}
function table(){
  var T=[[0,5,3],[0,9,7],[0,6,7],[1,9,4],[1,15,5],[1,3,5],[1,6,6],[2,7,0],[2,10,0],[2,15,0],[3,4,0],[3,8,0],[3,1,0],[3,0,0]];
  var h="<tr><th>Op</th><th>A</th><th>B</th><th>F</th><th>Cout</th><th>Expected</th><th>Result</th></tr>";
  T.forEach(function(x){
    var r=circuit(x[1],x[2],x[0]),e=ref(x[1],x[2],x[0]),ok=r.F===e;
    h+="<tr><td>"+NAMES[x[0]]+"</td><td class='mono'>"+b4(x[1])+"</td><td class='mono'>"+(x[0]>1?"–":b4(x[2]))+"</td><td class='mono'>"+b4(r.F)+"</td><td class='mono'>"+r.cout+"</td><td class='mono'>"+b4(e)+"</td><td class='"+(ok?"pass":"")+"'>"+(ok?"Pass":"Fail")+"</td></tr>";
  });
  document.getElementById("vt").innerHTML=h;
}
document.getElementById("runAll").onclick=function(){
  var tot=0,ok=0,per=[0,0,0,0];
  for(var o=0;o<4;o++)for(var a=0;a<16;a++)for(var b=0;b<16;b++){tot++;if(circuit(a,b,o).F===ref(a,b,o)){ok++;per[o]++;}}
  var el=document.getElementById("result");
  el.className=ok===tot?"pass":"";
  el.textContent=ok+" / "+tot+" passed (Add "+per[0]+", Sub "+per[1]+", Inc "+per[2]+", Dec "+per[3]+" of 256 each)";
};
setup();render();table();
})();
</script>
</body>
</html>
