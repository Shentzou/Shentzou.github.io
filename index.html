<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
<meta name="mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="default" />
<meta name="apple-mobile-web-app-title" content="Cashier POS" />
<meta name="theme-color" content="#378ADD" />
<title>Cashier POS</title>
<link rel="manifest" href="manifest.json" />
<link rel="apple-touch-icon" href="icon.svg" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@3.19.0/dist/tabler-icons.min.css" />
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --bg: #ffffff; --bg2: #f4f4f2; --bg3: #ebebea;
    --text: #1a1a19; --text2: #5f5e5a; --text3: #888780;
    --border: rgba(0,0,0,0.12); --border2: rgba(0,0,0,0.22);
    --info-bg: #e6f1fb; --info-text: #185fa5; --info-border: rgba(24,95,165,0.3);
    --success-bg: #eaf3de; --success-text: #3b6d11; --success-border: rgba(59,109,17,0.3);
    --danger-bg: #fcebeb; --danger-text: #a32d2d; --danger-border: rgba(163,45,45,0.3);
    --warn-bg: #faeeda; --warn-text: #854f0b;
    --radius: 8px; --radius-lg: 12px;
    --accent: #378ADD;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #1e1e1c; --bg2: #272725; --bg3: #2e2e2b;
      --text: #f0efea; --text2: #b4b2a9; --text3: #888780;
      --border: rgba(255,255,255,0.12); --border2: rgba(255,255,255,0.22);
      --info-bg: #0c447c; --info-text: #b5d4f4; --info-border: rgba(181,212,244,0.3);
      --success-bg: #27500a; --success-text: #c0dd97; --success-border: rgba(192,221,151,0.3);
      --danger-bg: #791f1f; --danger-text: #f7c1c1; --danger-border: rgba(247,193,193,0.3);
      --warn-bg: #633806; --warn-text: #fac775;
      --accent: #5ea8e8;
    }
  }
  body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: var(--bg3); color: var(--text); min-height: 100vh; }
  h1 { font-size: 20px; font-weight: 500; }
  header { background: var(--bg); border-bottom: 0.5px solid var(--border); padding: 14px 20px; display: flex; align-items: center; gap: 12px; }
  header .sub { font-size: 13px; color: var(--text3); margin-left: auto; }
  .pos { display: grid; grid-template-columns: 1fr 340px; height: calc(100vh - 57px); }
  .left { overflow-y: auto; padding: 1.25rem; }
  .right { background: var(--bg2); border-left: 0.5px solid var(--border); padding: 1.25rem; display: flex; flex-direction: column; gap: 1rem; overflow-y: auto; }
  .tabs { display: flex; gap: 6px; margin-bottom: 1.25rem; }
  .tab { padding: 7px 16px; font-size: 13px; border-radius: var(--radius); border: 0.5px solid var(--border2); background: none; cursor: pointer; color: var(--text2); font-family: inherit; }
  .tab.active { background: var(--info-bg); color: var(--info-text); border-color: var(--info-border); font-weight: 500; }
  .panel { display: none; }
  .panel.active { display: block; }
  .section-label { font-size: 11px; font-weight: 500; color: var(--text3); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 10px; }
  .add-form { background: var(--bg2); border-radius: var(--radius); padding: 1rem; margin-bottom: 1.25rem; display: grid; grid-template-columns: 1fr 130px auto; gap: 8px; align-items: end; }
  .form-group label { display: block; font-size: 12px; color: var(--text2); margin-bottom: 4px; }
  input[type="text"], input[type="number"] { width: 100%; padding: 7px 10px; border-radius: var(--radius); border: 0.5px solid var(--border2); background: var(--bg); color: var(--text); font-size: 13px; font-family: inherit; outline: none; }
  input:focus { border-color: var(--accent); box-shadow: 0 0 0 3px rgba(55,138,221,0.15); }
  .btn { padding: 7px 14px; border-radius: var(--radius); border: 0.5px solid var(--border2); background: var(--bg); font-size: 13px; cursor: pointer; color: var(--text); font-family: inherit; white-space: nowrap; display: inline-flex; align-items: center; gap: 5px; }
  .btn:hover { background: var(--bg2); }
  .btn-primary { background: var(--info-bg); color: var(--info-text); border-color: var(--info-border); font-weight: 500; }
  .btn-primary:hover { opacity: 0.85; }
  .btn-danger { background: var(--danger-bg); color: var(--danger-text); border-color: var(--danger-border); }
  .btn-danger:hover { opacity: 0.85; }
  .btn-success { background: var(--success-bg); color: var(--success-text); border-color: var(--success-border); font-weight: 500; }
  .btn-success:hover { opacity: 0.85; }
  .items-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(130px, 1fr)); gap: 8px; margin-bottom: 1rem; }
  .item-card { background: var(--bg); border: 0.5px solid var(--border); border-radius: var(--radius); padding: 12px; cursor: pointer; text-align: center; transition: border-color 0.15s; }
  .item-card:hover { border-color: var(--accent); }
  .item-card .iname { font-size: 13px; font-weight: 500; margin-bottom: 4px; }
  .item-card .iprice { font-size: 12px; color: var(--text2); }
  .cart-items { flex: 1; overflow-y: auto; }
  .cart-row { display: flex; align-items: center; gap: 8px; padding: 9px 0; border-bottom: 0.5px solid var(--border); }
  .cart-row:last-child { border-bottom: none; }
  .cart-name { flex: 1; font-size: 13px; }
  .qty-ctrl { display: flex; align-items: center; gap: 4px; }
  .qty-btn { width: 24px; height: 24px; border-radius: 6px; border: 0.5px solid var(--border2); background: var(--bg); cursor: pointer; font-size: 15px; display: flex; align-items: center; justify-content: center; color: var(--text2); font-family: inherit; }
  .qty-btn:hover { background: var(--bg3); }
  .qty-num { width: 24px; text-align: center; font-size: 13px; font-weight: 500; }
  .cart-price { font-size: 13px; font-weight: 500; min-width: 80px; text-align: right; }
  .cart-rm { color: var(--danger-text); cursor: pointer; font-size: 17px; padding: 2px; }
  hr { border: none; border-top: 0.5px solid var(--border); margin: 10px 0; }
  .sum-row { display: flex; justify-content: space-between; font-size: 13px; color: var(--text2); margin-bottom: 4px; }
  .sum-total { display: flex; justify-content: space-between; font-size: 17px; font-weight: 500; margin-top: 6px; }
  .empty { text-align: center; padding: 2.5rem 0; color: var(--text3); font-size: 13px; }
  .empty i { font-size: 32px; display: block; margin-bottom: 8px; }
  .metric-row { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-bottom: 1.25rem; }
  .metric { background: var(--bg2); border-radius: var(--radius); padding: 10px 12px; }
  .metric-label { font-size: 11px; color: var(--text3); margin-bottom: 2px; }
  .metric-val { font-size: 20px; font-weight: 500; }
  .box { border: 0.5px solid var(--border); border-radius: var(--radius); overflow: hidden; margin-bottom: 1.25rem; }
  .box-head { display: grid; gap: 8px; padding: 8px 12px; background: var(--bg2); font-size: 11px; font-weight: 500; color: var(--text3); text-transform: uppercase; letter-spacing: 0.05em; }
  .box-row { display: grid; gap: 8px; padding: 9px 12px; border-top: 0.5px solid var(--border); align-items: center; font-size: 13px; }
  .chart-row { display: flex; align-items: center; gap: 8px; margin-bottom: 7px; }
  .chart-label { font-size: 12px; color: var(--text2); width: 100px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
  .chart-track { flex: 1; background: var(--bg2); border-radius: 3px; height: 14px; overflow: hidden; }
  .chart-fill { height: 100%; border-radius: 3px; background: var(--accent); }
  .chart-val { font-size: 12px; color: var(--text2); width: 80px; text-align: right; }
  .badge { font-size: 10px; padding: 2px 8px; border-radius: 999px; font-weight: 500; background: var(--success-bg); color: var(--success-text); }
  .toast { position: fixed; bottom: 24px; right: 24px; background: var(--bg); border: 0.5px solid var(--border2); border-radius: var(--radius); padding: 10px 18px; font-size: 13px; z-index: 9999; opacity: 0; transition: opacity 0.25s; pointer-events: none; color: var(--text); }
  .prod-row { display: grid; grid-template-columns: 1fr 120px auto; gap: 8px; padding: 9px 12px; border-top: 0.5px solid var(--border); align-items: center; }
  @media (max-width: 700px) {
    .pos { grid-template-columns: 1fr; height: auto; }
    .right { border-left: none; border-top: 0.5px solid var(--border); min-height: 320px; }
    .add-form { grid-template-columns: 1fr; }
  }
  @supports (padding-bottom: env(safe-area-inset-bottom)) {
    body { padding-bottom: env(safe-area-inset-bottom); }
    header { padding-top: max(14px, env(safe-area-inset-top)); }
  }
</style>
</head>
<body>
<header>
  <i class="ti ti-cash-register" style="font-size:22px;"></i>
  <h1>Cashier POS</h1>
  <span class="sub" id="clock"></span>
</header>

<div class="pos">
  <div class="left">
    <div class="tabs">
      <button class="tab active" onclick="switchTab('register')"><i class="ti ti-layout-grid"></i> Register</button>
      <button class="tab" onclick="switchTab('products')"><i class="ti ti-package"></i> Products</button>
      <button class="tab" onclick="switchTab('sales')"><i class="ti ti-chart-bar"></i> Today's Sales</button>
    </div>

    <!-- REGISTER -->
    <div class="panel active" id="panel-register">
      <div style="position:relative;margin-bottom:1rem;">
        <i class="ti ti-search" style="position:absolute;left:10px;top:50%;transform:translateY(-50%);font-size:16px;color:var(--text3);pointer-events:none;"></i>
        <input type="text" id="search-input" placeholder="Search items..." oninput="renderMenu()" style="padding-left:34px;width:100%;" />
      </div>
      <div class="section-label" id="menu-label">Tap item to add</div>
      <div class="items-grid" id="menu-grid"></div>
    </div>

    <!-- PRODUCTS -->
    <div class="panel" id="panel-products">
      <div class="section-label">Add new product</div>
      <div class="add-form">
        <div class="form-group">
          <label>Name</label>
          <input type="text" id="new-name" placeholder="e.g. Coffee" />
        </div>
        <div class="form-group">
          <label>Price (Rp)</label>
          <input type="number" id="new-price" placeholder="15000" min="0" />
        </div>
        <button class="btn btn-primary" onclick="addProduct()" style="align-self:flex-end"><i class="ti ti-plus"></i> Add</button>
      </div>
      <div class="section-label">All products</div>
      <div id="product-list"></div>
    </div>

    <!-- SALES -->
    <div class="panel" id="panel-sales">
      <div class="metric-row" id="summary-metrics"></div>
      <div class="section-label">Items sold today</div>
      <div id="items-sold-list"></div>
      <div class="section-label" id="chart-label" style="display:none;">Revenue by item</div>
      <div id="income-chart" style="margin-bottom:1.25rem;"></div>
      <div class="section-label">Transactions</div>
      <div id="txn-list"></div>
    </div>
  </div>

  <div class="right">
    <div style="font-size:15px;font-weight:500;display:flex;align-items:center;gap:8px;">
      <i class="ti ti-receipt"></i> Current order
    </div>
    <div class="cart-items" id="cart-display"></div>
    <div>
      <hr>
      <div class="sum-total"><span>Total</span><span id="total-amt">Rp 0</span></div>
      <hr>
      <button class="btn btn-success" style="width:100%;margin-top:8px;padding:10px;justify-content:center;" onclick="checkout()">
        <i class="ti ti-check"></i> Charge & Complete
      </button>
      <button class="btn btn-danger" style="width:100%;margin-top:6px;justify-content:center;" onclick="clearCart()">
        <i class="ti ti-trash"></i> Clear order
      </button>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
const KEY = 'pos_standalone_v1';
let state = load();

function load() {
  try { const r = localStorage.getItem(KEY); if (r) return JSON.parse(r); } catch(e) {}
  return {
    products: [
      {id:1,name:'Coffee',price:15000},
      {id:2,name:'Tea',price:10000},
      {id:3,name:'Sandwich',price:25000},
      {id:4,name:'Cake',price:20000},
      {id:5,name:'Juice',price:18000},
      {id:6,name:'Water',price:5000},
    ],
    cart: [],
    transactions: [],
    nextId: 7
  };
}

function save() { try { localStorage.setItem(KEY, JSON.stringify(state)); } catch(e) {} }

function fmt(n) { return 'Rp ' + Math.round(n).toLocaleString('id-ID'); }
function esc(s) { return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }

function sub() { return state.cart.reduce((s,i)=>s+i.price*i.qty,0); }
function total() { return sub(); }

function addToCart(id) {
  const p = state.products.find(p=>p.id===id);
  if (!p) return;
  const ex = state.cart.find(i=>i.id===id);
  if (ex) ex.qty++; else state.cart.push({id:p.id,name:p.name,price:p.price,qty:1});
  save(); renderCart(); toast('Added '+p.name);
}

function changeQty(id, delta) {
  const item = state.cart.find(i=>i.id===id);
  if (!item) return;
  item.qty += delta;
  if (item.qty <= 0) state.cart = state.cart.filter(i=>i.id!==id);
  save(); renderCart();
}

function removeFromCart(id) {
  state.cart = state.cart.filter(i=>i.id!==id);
  save(); renderCart();
}

function clearCart() {
  if (!state.cart.length) return;
  state.cart = []; save(); renderCart();
}

function checkout() {
  if (!state.cart.length) { toast('Order is empty'); return; }
  state.transactions.push({
    time: new Date().toISOString(),
    items: state.cart.map(i=>({...i})),
    subtotal: sub(), total: total()
  });
  const t = total();
  state.cart = []; save(); renderCart();
  toast('✓ Payment recorded — ' + fmt(t));
  if (document.getElementById('panel-sales').classList.contains('active')) renderSales();
}

function renderCart() {
  const el = document.getElementById('cart-display');
  if (!state.cart.length) {
    el.innerHTML = '<div class="empty"><i class="ti ti-shopping-cart-off"></i>No items yet<br><span style="font-size:12px;color:var(--text3)">Tap a product to add</span></div>';
  } else {
    el.innerHTML = state.cart.map(i=>`
      <div class="cart-row">
        <span class="cart-name">${esc(i.name)}</span>
        <div class="qty-ctrl">
          <button class="qty-btn" onclick="changeQty(${i.id},-1)">−</button>
          <span class="qty-num">${i.qty}</span>
          <button class="qty-btn" onclick="changeQty(${i.id},1)">+</button>
        </div>
        <span class="cart-price">${fmt(i.price*i.qty)}</span>
        <span class="cart-rm" onclick="removeFromCart(${i.id})"><i class="ti ti-x"></i></span>
      </div>`).join('');
  }
  document.getElementById('total-amt').textContent = fmt(total());
}

function renderMenu() {
  const el = document.getElementById('menu-grid');
  const q = (document.getElementById('search-input')?.value||'').toLowerCase().trim();
  const filtered = state.products.filter(p=>p.name.toLowerCase().includes(q));
  const label = document.getElementById('menu-label');
  if (!state.products.length) {
    el.innerHTML = '<div style="color:var(--text3);font-size:13px;grid-column:1/-1;padding:1rem 0;">No products. Add some in the Products tab.</div>';
    if(label) label.textContent = 'Tap item to add';
    return;
  }
  if (!filtered.length) {
    el.innerHTML = '<div style="color:var(--text3);font-size:13px;grid-column:1/-1;padding:1rem 0;">No items match your search.</div>';
    if(label) label.textContent = '0 results';
    return;
  }
  if(label) label.textContent = q ? filtered.length+' result'+(filtered.length>1?'s':'')+' for "'+q+'"' : 'Tap item to add';
  el.innerHTML = filtered.map(p=>`
    <div class="item-card" onclick="addToCart(${p.id})">
      <div class="iname">${esc(p.name)}</div>
      <div class="iprice">${fmt(p.price)}</div>
    </div>`).join('');
}

function renderProducts() {
  const el = document.getElementById('product-list');
  if (!state.products.length) { el.innerHTML = '<div style="color:var(--text3);font-size:13px;padding:1rem 0;">No products yet.</div>'; return; }
  el.innerHTML = `<div class="box">${state.products.map(p=>`
    <div class="prod-row">
      <span style="font-size:13px;">${esc(p.name)}</span>
      <div style="display:flex;align-items:center;gap:4px;">
        <input type="number" value="${p.price}" min="0" style="width:100%;font-size:13px;" onchange="updatePrice(${p.id},this.value)" aria-label="Price for ${esc(p.name)}" />
        <span style="font-size:12px;color:var(--text3);">Rp</span>
      </div>
      <button class="btn btn-danger" style="padding:5px 9px;font-size:12px;" onclick="deleteProduct(${p.id})"><i class="ti ti-trash"></i></button>
    </div>`).join('')}</div>`;
}

function addProduct() {
  const name = document.getElementById('new-name').value.trim();
  const price = parseFloat(document.getElementById('new-price').value);
  if (!name || isNaN(price) || price < 0) { toast('Enter a valid name and price'); return; }
  state.products.push({id:state.nextId++, name, price});
  document.getElementById('new-name').value = '';
  document.getElementById('new-price').value = '';
  save(); renderProducts(); renderMenu(); toast('Added '+name);
}

function updatePrice(id, val) {
  const p = state.products.find(p=>p.id===id);
  if (p) { p.price = parseFloat(val)||0; save(); renderMenu(); }
}

function deleteProduct(id) {
  state.products = state.products.filter(p=>p.id!==id);
  state.cart = state.cart.filter(i=>i.id!==id);
  save(); renderProducts(); renderMenu(); renderCart();
}

function todayTxns() {
  const today = new Date().toDateString();
  return state.transactions.filter(t=>new Date(t.time).toDateString()===today);
}

function adjustSalesItem(name, delta) {
  const today = new Date().toDateString();
  const todayIdxs = state.transactions
    .map((t,i)=>({t,i}))
    .filter(({t})=>new Date(t.time).toDateString()===today);
  if (!todayIdxs.length) return;
  const price = (() => {
    for (const {t} of todayIdxs) {
      const found = t.items.find(i=>i.name===name);
      if (found) return found.price;
    }
    const p = state.products.find(p=>p.name===name);
    return p ? p.price : 0;
  })();
  if (delta > 0) {
    const last = todayIdxs[todayIdxs.length-1];
    const ex = last.t.items.find(i=>i.name===name);
    if (ex) { ex.qty++; } else { last.t.items.push({id:Date.now(),name,price,qty:1}); }
    last.t.total += price;
  } else {
    for (let k = todayIdxs.length-1; k >= 0; k--) {
      const t = todayIdxs[k].t;
      const item = t.items.find(i=>i.name===name);
      if (item && item.qty > 0) {
        item.qty--;
        t.total = Math.max(0, t.total - price);
        if (item.qty === 0) t.items = t.items.filter(i=>i.name!==name);
        break;
      }
    }
  }
  state.transactions = state.transactions.filter(t=>t.items.length>0);
  save(); renderSales();
  toast((delta>0?'+1 ':'-1 ')+name);
}

function renderSales() {
  const txns = todayTxns();
  const totalIncome = txns.reduce((s,t)=>s+t.total,0);
  const itemMap = {};
  txns.forEach(t=>t.items.forEach(i=>{
    if (!itemMap[i.name]) itemMap[i.name]={qty:0,rev:0,price:i.price};
    itemMap[i.name].qty+=i.qty;
    itemMap[i.name].rev+=i.price*i.qty;
  }));
  const items = Object.entries(itemMap).sort((a,b)=>b[1].rev-a[1].rev);
  const totalQty = items.reduce((s,[,v])=>s+v.qty,0);

  document.getElementById('summary-metrics').innerHTML = `
    <div class="metric"><div class="metric-label">Total income</div><div class="metric-val">${fmt(totalIncome)}</div></div>
    <div class="metric"><div class="metric-label">Orders today</div><div class="metric-val">${txns.length}</div></div>
    <div class="metric"><div class="metric-label">Items sold</div><div class="metric-val">${totalQty}</div></div>
    <div class="metric"><div class="metric-label">Avg. order</div><div class="metric-val">${txns.length?fmt(totalIncome/txns.length):'Rp 0'}</div></div>
  `;

  if (!items.length) {
    document.getElementById('items-sold-list').innerHTML = '<div style="color:var(--text3);font-size:13px;padding:1rem 0 0;">No sales recorded today.</div>';
    document.getElementById('income-chart').innerHTML = '';
    document.getElementById('chart-label').style.display = 'none';
  } else {
    document.getElementById('items-sold-list').innerHTML = `<div class="box" style="margin-bottom:1.25rem;">
      <div class="box-head" style="grid-template-columns:1fr auto auto auto;"><span>Item</span><span>Adjust</span><span style="text-align:center;">Qty</span><span style="text-align:right;">Revenue</span></div>
      ${items.map(([name,{qty,rev}])=>`
        <div class="box-row" style="grid-template-columns:1fr auto auto auto;align-items:center;">
          <span>${esc(name)}</span>
          <span style="display:flex;gap:4px;">
            <button class="qty-btn" onclick="adjustSalesItem('${esc(name)}',-1)" title="Remove one">−</button>
            <button class="qty-btn" onclick="adjustSalesItem('${esc(name)}',1)" title="Add one">+</button>
          </span>
          <span style="text-align:center;color:var(--text2);min-width:28px;">${qty}</span>
          <span style="text-align:right;font-weight:500;">${fmt(rev)}</span>
        </div>`).join('')}
    </div>`;

    const maxRev = Math.max(...items.map(([,v])=>v.rev));
    document.getElementById('chart-label').style.display = '';
    document.getElementById('income-chart').innerHTML = items.map(([name,{rev}])=>`
      <div class="chart-row">
        <span class="chart-label">${esc(name)}</span>
        <div class="chart-track"><div class="chart-fill" style="width:${Math.round(rev/maxRev*100)}%"></div></div>
        <span class="chart-val">${fmt(rev)}</span>
      </div>`).join('');
  }

  if (!txns.length) {
    document.getElementById('txn-list').innerHTML = '<div style="color:var(--text3);font-size:13px;padding:0.5rem 0;">No transactions yet.</div>';
  } else {
    document.getElementById('txn-list').innerHTML = `<div class="box">
      ${[...txns].reverse().map(t=>`
        <div style="display:flex;justify-content:space-between;align-items:center;padding:9px 12px;border-top:0.5px solid var(--border);font-size:12px;">
          <span style="color:var(--text3);">${new Date(t.time).toLocaleTimeString('id-ID',{hour:'2-digit',minute:'2-digit'})} — ${t.items.map(i=>i.name+(i.qty>1?' x'+i.qty:'')).join(', ')}</span>
          <span style="display:flex;align-items:center;gap:8px;"><span class="badge">Paid</span><span style="font-weight:500;">${fmt(t.total)}</span></span>
        </div>`).join('')}
    </div>`;
  }
}

function switchTab(tab) {
  document.querySelectorAll('.tab').forEach((t,i)=>t.classList.toggle('active',['register','products','sales'][i]===tab));
  document.querySelectorAll('.panel').forEach(p=>p.classList.remove('active'));
  document.getElementById('panel-'+tab).classList.add('active');
  if (tab==='products') renderProducts();
  if (tab==='sales') renderSales();
}

let toastTimer;
function toast(msg) {
  const el = document.getElementById('toast');
  el.textContent = msg; el.style.opacity = '1';
  clearTimeout(toastTimer);
  toastTimer = setTimeout(()=>el.style.opacity='0', 2200);
}

function updateClock() {
  document.getElementById('clock').textContent = new Date().toLocaleString('id-ID',{weekday:'short',day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'});
}

renderMenu(); renderCart(); updateClock(); setInterval(updateClock, 10000);
</script>
<script>
if ('serviceWorker' in navigator) {
  window.addEventListener('load', () => {
    navigator.serviceWorker.register('./sw.js').catch(()=>{});
  });
}
</script>
</body>
</html>
