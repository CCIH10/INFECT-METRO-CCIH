<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Infectômetro - SCIH</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600;700;800&family=Open+Sans:wght@400;600&display=swap');

:root{
  --vm:#E05A6A; --vmc:#F2909A; --rx:#6B2D8B; --az:#1A2C5B;
  --azm:#2E4A8F; --gc:#F5F5F5; --gb:#DDD; --tx:#2C2C2C;
}
*{box-sizing:border-box;margin:0;padding:0;}

body{font-family:'Open Sans',sans-serif;background:#fff;color:var(--tx);font-size:10px;}

/* === PAGE === */
.page{width:277mm;margin:0 auto;background:#fff;padding:4mm 7mm;}

/* === HEADER === */
.header{display:flex;align-items:center;justify-content:space-between;
  border-bottom:3px solid var(--vm);padding-bottom:5px;margin-bottom:6px;}
.logo-box{background:#fff;padding:3px;display:flex;align-items:center;justify-content:center;}
.logo-box img{height:44px;object-fit:contain;}
.header-title{text-align:center;flex:1;padding:0 8px;}
.header-title h1{font-family:'Montserrat',sans-serif;font-size:24px;font-weight:800;
  color:var(--rx);letter-spacing:3px;text-shadow:1px 1px 0 var(--vmc);line-height:1;}
.header-title .sub{font-size:8px;color:var(--az);font-weight:600;letter-spacing:2px;
  text-transform:uppercase;margin-top:2px;}
.header-meta{display:flex;flex-direction:column;gap:3px;min-width:160px;}
.mf{display:flex;align-items:center;gap:3px;background:var(--gc);border-radius:3px;
  padding:2px 5px;border-left:3px solid var(--rx);}
.mf label{font-weight:700;color:var(--rx);white-space:nowrap;font-size:8px;}
.mf input, .mf select{border:none;background:transparent;width:100%;font-family:'Open Sans',sans-serif;
  font-size:9px;color:var(--az);font-weight:600;outline:none;}

/* === SECTIONS === */
.sec{margin-bottom:5px;}
.sec-t{font-family:'Montserrat',sans-serif;font-size:9px;font-weight:700;color:#fff;
  padding:3px 8px;border-radius:3px 3px 0 0;letter-spacing:.8px;text-transform:uppercase;
  display:flex;align-items:center;justify-content:space-between;}
.sec-t.vm{background:var(--vm);}
.sec-t.rx{background:var(--rx);}
.sec-t.az{background:var(--az);}
.sec-b{border:1.5px solid var(--gb);border-top:none;border-radius:0 0 3px 3px;
  padding:4px 5px;background:#fff;}

/* === DYN ROWS === */
.drow{display:flex;gap:4px;align-items:center;margin-bottom:2px;padding:2px 5px;
  background:var(--gc);border-radius:3px;border-left:3px solid var(--vm);}
.drow.itr{border-left-color:var(--rx);}
.drow input[type=text]{flex:2;border:1px solid var(--gb);border-radius:2px;
  padding:1px 4px;font-family:'Open Sans',sans-serif;font-size:9px;outline:none;}
.drow input[type=number]{width:48px;border:1px solid var(--gb);border-radius:2px;
  padding:1px 4px;font-size:9px;outline:none;text-align:center;}
.brm{background:var(--vm);color:#fff;border:none;border-radius:2px;width:16px;height:16px;
  cursor:pointer;font-size:12px;display:flex;align-items:center;justify-content:center;
  font-weight:bold;flex-shrink:0;}
.brm.rx{background:var(--rx);}
.badd{background:var(--az);color:#fff;border:none;border-radius:2px;padding:2px 8px;
  cursor:pointer;font-family:'Montserrat',sans-serif;font-size:8px;font-weight:700;
  margin-top:2px;letter-spacing:.3px;}
.badge{display:inline-flex;align-items:center;gap:3px;background:var(--vm);color:#fff;
  border-radius:3px;padding:1px 6px;font-size:9px;font-weight:700;margin-bottom:3px;}
.badge.rx{background:var(--rx);}
.mbadge{background:var(--vm);color:#fff;border-radius:2px;padding:1px 5px;
  font-size:8px;font-weight:700;}

/* === MONTHLY TABLE === */
.mt{width:100%;border-collapse:collapse;font-size:8px;margin-top:3px;}
.mt th{background:var(--az);color:#fff;padding:2px 2px;text-align:center;
  font-family:'Montserrat',sans-serif;font-weight:700;font-size:7.5px;}
.mt td{border:1px solid var(--gb);padding:1px 2px;text-align:center;}
.mt td input{width:100%;border:none;outline:none;font-family:'Open Sans',sans-serif;
  font-size:8px;text-align:center;background:transparent;}
.mt tr:nth-child(even) td{background:var(--gc);}
.mt tr.tr td{background:#e8eaf6;font-weight:700;}

/* === CHARTS === */
.cc{width:100%;height:80px;margin-top:3px;position:relative;}

/* === PREVENTION === */
.pg{display:grid;grid-template-columns:1fr 1fr 1fr;gap:5px;}
.pb{border:1.5px solid var(--gb);border-radius:4px;overflow:hidden;}
.pbt{color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:8px;
  padding:3px 6px;text-align:center;text-transform:uppercase;letter-spacing:.3px;}
.pbt.ipcs{background:var(--vm);}
.pbt.itu{background:var(--rx);}
.pbt.pav{background:var(--az);}
.pf{padding:4px 5px;}
.pdr{display:flex;align-items:center;gap:3px;margin-bottom:2px;}
.pdr input{flex:1;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;
  font-size:8px;outline:none;font-family:'Open Sans',sans-serif;}
.bsm{background:var(--vm);color:#fff;border:none;border-radius:2px;width:14px;height:14px;
  cursor:pointer;font-size:10px;display:flex;align-items:center;justify-content:center;
  font-weight:bold;flex-shrink:0;}
.bsm.rx{background:var(--rx);}
.bsm.az{background:var(--az);}
.pbadd{background:var(--az);color:#fff;border:none;border-radius:2px;padding:2px 8px;
  cursor:pointer;font-family:'Montserrat',sans-serif;font-size:8px;font-weight:700;
  margin-top:2px;letter-spacing:.3px;}

/* === FOOTER === */
.footer{text-align:center;font-size:8px;color:var(--az);margin-top:10px;display:flex;justify-content:space-between;}

</style>
</head>
<body>

<div class="page">
<div class="header">
  <div class="logo-box"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Hospital_Martag%C3%A3o_Gesteira_logo.png/640px-Hospital_Martag%C3%A3o_Gesteira_logo.png"></div>
  <div class="header-title">
    <h1>INFECTÔMETRO</h1>
    <div class="sub">Serviço de Controle de Infecção Hospitalar</div>
  </div>
  <div class="header-meta">
    <div class="mf">
      <label for="sectorFilter">Setor:</label>
      <select id="sectorFilter">
        <option value="Centro cirúrgico">Centro cirúrgico</option>
        <option value="UTI Neo">UTI Neo</option>
        <option value="PED A">PED A</option>
        <option value="PED B">PED B</option>
        <option value="PED C">PED C</option>
      </select>
    </div>
    <div class="mf">
      <label>Último Acesso:</label>
      <input type="text" id="lastAccess" readonly style="color: #555;">
    </div>
    <div class="mf">
      <label>Última Atualiz.:</label>
      <input type="text" id="lastUpdate" readonly style="color: #555;">
    </div>
  </div>
</div>

<div class="sec">
  <div class="sec-t vm">IRAS — Infecções Relacionadas à Assistência à Saúde <span class="badge">Total: <span id="totIras">0</span></span></div>
  <div class="sec-b">
    <div id="irasC"></div>
    <button class="badd" onclick="addRow('irasC','in',false)">+ Adicionar IRAS</button>
    <div class="cc"><canvas id="cIras"></canvas></div>
  </div>
</div>

<div class="sec">
  <div class="sec-t rx">ITR — Infecção do Trato Respiratório <span class="badge rx">Total: <span id="totItr">0</span></span></div>
  <div class="sec-b">
    <div id="itrC"></div>
    <button class="badd" onclick="addRow('itrC','itn',true)">+ Adicionar ITR</button>
    <div class="cc"><canvas id="cIpcs"></canvas></div>
  </div>
</div>

<div class="sec">
  <div class="sec-t az">Higienização das Mãos</div>
  <div class="sec-b">
    <table class="mt">
      <thead>
        <tr>
          <th>Mês</th>
          <th>Realizadas</th>
          <th>Observadas</th>
          <th>Taxa HM (%)</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Jan</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Fev</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Mar</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Abr</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Mai</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Jun</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Jul</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Ago</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Set</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Out</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Nov</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
        <tr><td>Dez</td><td><input type="number" class="hmn" oninput="cHM()"></td><td><input type="number" class="hmd" oninput="cHM()"></td><td><input type="text" class="hmr" readonly style="font-weight:700;color:var(--rx);"></td></tr>
      </tbody>
    </table>
    <div class="cc"><canvas id="cHM"></canvas></div>
  </div>
</div>

<div class="pg">
  <div class="pb">
    <div class="pbt ipcs">IPCS</div>
    <div class="pf">
      <div id="ipcsC">
        <div class="pdr">
          <input type="text" placeholder="Campo..." style="min-width:80px;flex:0 0 80px;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:7.5px;outline:none;font-family:'Open Sans',sans-serif;" value="Densidade">
          <input type="text" placeholder="Valor..." style="flex:1;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:8px;outline:none;font-family:'Open Sans',sans-serif;" value="0">
          <button class="bsm" onclick="rmPR(this)">−</button>
        </div>
      </div>
      <button class="pbadd" onclick="addPR('ipcsC')">+ Adicionar</button>
    </div>
  </div>
  <div class="pb">
    <div class="pbt itu">ITU associada a SVD</div>
    <div class="pf">
      <div id="ituC">
        <div class="pdr">
          <input type="text" placeholder="Campo..." style="min-width:80px;flex:0 0 80px;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:7.5px;outline:none;font-family:'Open Sans',sans-serif;" value="Densidade">
          <input type="text" placeholder="Valor..." style="flex:1;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:8px;outline:none;font-family:'Open Sans',sans-serif;" value="0">
          <button class="bsm rx" onclick="rmPR(this)">−</button>
        </div>
      </div>
      <button class="pbadd" onclick="addPR('ituC')">+ Adicionar</button>
    </div>
  </div>
  <div class="pb">
    <div class="pbt pav">PAV</div>
    <div class="pf">
      <div id="pavC">
        <div class="pdr">
          <input type="text" placeholder="Campo..." style="min-width:80px;flex:0 0 80px;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:7.5px;outline:none;font-family:'Open Sans',sans-serif;" value="Densidade">
          <input type="text" placeholder="Valor..." style="flex:1;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:8px;outline:none;font-family:'Open Sans',sans-serif;" value="0">
          <button class="bsm az" onclick="rmPR(this)">−</button>
        </div>
      </div>
      <button class="pbadd" onclick="addPR('pavC')">+ Adicionar</button>
    </div>
  </div>
</div>

<div class="footer">
  <span>Infectômetro — SCIH | Hospital Martagão Gesteira</span>
  <span>Gerado em: <span id="dg"></span></span>
</div>
</div>

<script>
const MS=['Jan','Fev','Mar','Abr','Mai','Jun','Jul','Ago','Set','Out','Nov','Dez'];

// Registra o Último Acesso (Momento da abertura da página)
const agora = new Date();
document.getElementById('lastAccess').value = agora.toLocaleDateString('pt-BR') + ' ' + agora.toLocaleTimeString('pt-BR', {hour: '2-digit', minute:'2-digit'});
document.getElementById('dg').textContent = agora.toLocaleDateString('pt-BR');

// ── CHARTS ─────────────────────────────────────────────
function mkBar(id,label,color){
  return new Chart(document.getElementById(id),{
    type:'bar',
    data:{labels:MS,datasets:[{label,data:Array(12).fill(0),
      backgroundColor:color+'BB',borderColor:color,borderWidth:1.5,borderRadius:2}]},
    options:{responsive:true,maintainAspectRatio:false,
      plugins:{legend:{display:false}},
      scales:{y:{beginAtZero:true,ticks:{font:{size:7}},grid:{color:'#eee'}},
              x:{ticks:{font:{size:7}},grid:{display:false}}}}
  });
}

const cIras=mkBar('cIras','IRAS','#E05A6A');
const cIpcs=mkBar('cIpcs','Densidade IPCS','#6B2D8B');

const cHMch=new Chart(document.getElementById('cHM'),{
  type:'bar',
  data:{labels:MS,datasets:[
    {label:'Taxa HM (%)',data:Array(12).fill(0),backgroundColor:'#2E4A8FBB',
     borderColor:'#1A2C5B',borderWidth:1.5,borderRadius:2},
    {label:'Meta 80%',data:Array(12).fill(80),type:'line',
     borderColor:'#E05A6A',borderWidth:1.5,borderDash:[4,3],pointRadius:0,fill:false}
  ]},
  options:{responsive:true,maintainAspectRatio:false,
    plugins:{legend:{display:true,labels:{font:{size:7},boxWidth:10}}},
    scales:{y:{beginAtZero:true,max:110,ticks:{font:{size:7}},grid:{color:'#eee'}},
            x:{ticks:{font:{size:7}},grid:{display:false}}}}
});

function uIC(){cIras.data.datasets[0].data=[...document.querySelectorAll('.imo')].map(i=>+i.value||0);cIras.update();}
function cIP(){
  const n=[...document.querySelectorAll('.ipn')],d=[...document.querySelectorAll('.ipd')],r=[...document.querySelectorAll('.ipr')];
  const v=n.map((ni,i)=>{const val=+d[i].value>0?(+ni.value/+d[i].value*1000).toFixed(2):'';r[i].value=val;return parseFloat(val)||0;});
  cIpcs.data.datasets[0].data=v;cIpcs.update();
}
function cHM(){
  const n=[...document.querySelectorAll('.hmn')],d=[...document.querySelectorAll('.hmd')],r=[...document.querySelectorAll('.hmr')];
  const v=n.map((ni,i)=>{const val=+d[i].value>0?(+ni.value/+d[i].value*100).toFixed(1):'';r[i].value=val?val+'%':'';return parseFloat(val)||0;});
  cHMch.data.datasets[0].data=v;cHMch.update();
}

// ── DYNAMIC ROWS ───────────────────────────────────────
function addRow(cid,cls,itr, name = '', value = 0){
  const c=document.getElementById(cid);
  const d=document.createElement('div');
  d.className='drow'+(itr?' itr':'');
  d.innerHTML=`<input type="text" placeholder="${itr?'Tipo de ITR...':'Tipo de IRAS...'}" value="${name}">
    <input type="number" min="0" value="${value}" class="${cls}" oninput="uT()">
    <button class="brm${itr?' rx':''}" onclick="this.parentElement.remove();uT()">−</button>`;
  c.appendChild(d);
  uT();
}

function clearDynamicRows(cid) {
    const container = document.getElementById(cid);
    while (container.firstChild) {
        container.removeChild(container.firstChild);
    }
}

function uT(){
  let t=0;document.querySelectorAll('.in').forEach(i=>t+=parseInt(i.value)||0);
  document.getElementById('totIras').textContent=t;
  let t2=0;document.querySelectorAll('.itn').forEach(i=>t2+=parseInt(i.value)||0);
  document.getElementById('totItr').textContent=t2;
}

// ── PREVENTION ─────────────────────────────────────────
function addPR(cid){
  const c=document.getElementById(cid),d=document.createElement('div');
  d.className='pdr';
  d.innerHTML=`<input type="text" placeholder="Campo..." style="min-width:80px;flex:0 0 80px;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:7.5px;outline:none;font-family:'Open Sans',sans-serif;">
    <input type="text" placeholder="Valor..." style="flex:1;border:1px solid var(--gb);border-radius:2px;padding:1px 3px;font-size:8px;outline:none;font-family:'Open Sans',sans-serif;">
    <button class="bsm" onclick="rmPR(this)">−</button>`;
  c.appendChild(d);
}
function rmPR(b){b.parentElement.remove();}

// ── INTEGRAÇÃO GOOGLE SHEETS (LINKS CORRIGIDOS PARA /pub) ──
const urlHM = "https://docs.google.com/spreadsheets/d/e/2PACX-1vS3R0BWCOyq0lpWM9I-7_AWuPXAr9hvfQniT5egOEOQVi1WjIxFAVusDEF5-DQh6joWMyozfKsTzb0I/pub?gid=0&single=true&output=csv";
const urlIras = "https://docs.google.com/spreadsheets/d/e/2PACX-1vS3R0BWCOyq0lpWM9I-7_AWuPXAr9hvfQniT5egOEOQVi1WjIxFAVusDEF5-DQh6joWMyozfKsTzb0I/pub?gid=276280385&single=true&output=csv";

async function carregarDados() {
  const setorSelecionado = document.getElementById('sectorFilter').value;

  try {
    const timestamp = new Date().getTime();
    const [resHM, resIras] = await Promise.all([
      fetch(`${urlHM}&t=${timestamp}`, { cache: "no-store" }),
      fetch(`${urlIras}&t=${timestamp}`, { cache: "no-store" })
    ]);
    
    const csvHM = await resHM.text();
    const csvIras = await resIras.text();

    processarHM(csvHM, sectorSelecionado);
    processarBaseIras(csvIras, sectorSelecionado);

    // Atualiza o horário de Última Atualização com sucesso
    const attData = new Date();
    document.getElementById('lastUpdate').value = attData.toLocaleDateString('pt-BR') + ' ' + attData.toLocaleTimeString('pt-BR', {hour: '2-digit', minute:'2-digit'});

  } catch(e) {
    console.error("Erro ao carregar dados do Sheets:", e);
    alert("Não foi possível conectar com a planilha. Verifique a internet ou o link do Google Sheets.");
  }
}

function processarHM(csv, setorSelecionado) {
  const linhas = csv.split('\n');
  const meses = ['jan', 'fev', 'mar', 'abr', 'mai', 'jun', 'jul', 'ago', 'set', 'out', 'nov', 'dez'];

  const inputsHmn = document.querySelectorAll('.hmn'); 
  const inputsHmd = document.querySelectorAll('.hmd'); 

  inputsHmn.forEach(inp => inp.value = '');
  inputsHmd.forEach(inp => inp.value = '');

  let inCorrectSectorBlock = false;
  let inHMBlock = false;
  let lineCounter = 0;

  for (const linha of linhas) {
    const cols = linha.split(/,(?=(?:(?:[^"]*"){2})*[^"]*$)/).map(col => col.replace(/^"|"$/g, '').trim());

    if (cols[0] === 'Centro cirúrgico' || cols[0] === 'UTI Neo' || cols[0] === 'PED A' || cols[0] === 'PED B' || cols[0] === 'PED C') {
        inCorrectSectorBlock = (cols[0] === setorSelecionado);
        inHMBlock = false; 
        continue;
    }

    if (inCorrectSectorBlock) {
        if (cols[0] === 'Taxa de higienização das mãos por Mês') {
            inHMBlock = true;
            lineCounter = 0; 
            continue;
        }

        if (inHMBlock) {
            lineCounter++;
            if (lineCounter === 1) { 
                continue;
            }
            if (lineCounter > 1 && lineCounter <= 13) { 
                const mesCSV = cols[0] ? cols[0].toLowerCase() : '';
                const realizadas = parseInt(cols[1]) || 0;
                const observadas = parseInt(cols[2]) || 0;

                const idxMes = meses.findIndex(m => mesCSV.startsWith(m)); 
                if (idxMes !== -1) {
                    inputsHmn[idxMes].value = realizadas;
                    inputsHmd[idxMes].value = observadas;
                }
            } else if (lineCounter > 13) { 
                inHMBlock = false;
                break; 
            }
        }
    }
  }
  cHM(); 
}

function processarBaseIras(csv, setorSelecionado) {
  const linhas = csv.split('\n');

  clearDynamicRows('irasC');
  clearDynamicRows('itrC');

  let inCorrectSectorBlock = false;
  let inIrasTopografiaBlock = false;
  let inItrAgentesBlock = false;

  for (const linha of linhas) {
    const cols = linha.split(/,(?=(?:(?:[^"]*"){2})*[^"]*$)/).map(col => col.replace(/^"|"$/g, '').trim());

    let currentLineSector = '';
    if (cols[1] === '2026' && cols[2]) { 
        currentLineSector = cols[2];
    } else if (cols[0] === 'Centro cirúrgico' || cols[0] === 'UTI Neo' || cols[0] === 'PED A' || cols[0] === 'PED B' || cols[0] === 'PED C') { 
        currentLineSector = cols[0];
    }

    if (currentLineSector) {
        inCorrectSectorBlock = (currentLineSector === setorSelecionado);
        inIrasTopografiaBlock = false; 
        inItrAgentesBlock = false;
        continue; 
    }

    if (inCorrectSectorBlock) {
      if (cols[0] === 'IRAS por topografia') {
        inIrasTopografiaBlock = true;
        inItrAgentesBlock = false;
        continue;
      }
      if (cols[0] === 'ITR - agentes isolados') {
        inItrAgentesBlock = true;
        inIrasTopografiaBlock = false;
        continue;
      }

      if (cols[0] === 'Medidas de prevenção de IRAS' || (cols.length > 0 && cols[0] === '')) {
        inIrasTopografiaBlock = false;
        inItrAgentesBlock = false;
        continue;
      }

      if (inIrasTopografiaBlock) {
        if (cols[0] && cols[0] !== '(colocar variável, paraser possível trocar ou adicionar mais nomes de IRAS)') {
          const indicador = cols[0];
          const valor = parseInt(cols[1]) || 0;
          addRow('irasC', 'in', false, indicador, valor);
        }
      } else if (inItrAgentesBlock) {
        if (cols[0] && cols[0] !== '(colocar variável, paraser possível trocar ou adicionar mais nomes de IRAS)') {
          const indicador = cols[0];
          const valor = parseInt(cols[1]) || 0;
          addRow('itrC', 'itn', true, indicador, valor);
        }
      }
    }
  }
  uT(); 
}

document.getElementById('sectorFilter').addEventListener('change', carregarDados);
window.onload = () => { carregarDados(); };
</script>
</body>
</html>
