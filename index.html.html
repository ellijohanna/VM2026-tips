<!DOCTYPE html>
<html lang="sv">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>⚽ VM 2026 — Familjetips</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --grass: #1a6b2f;
    --grass-light: #2d8a47;
    --gold: #f5c518;
    --off-white: #f7f7f5;
    --card: #ffffff;
    --border: #e4e4e0;
    --text: #1a1a1a;
    --muted: #888;

    --frida:   #c0397a;
    --linnea:  #7c3aed;
    --jessica: #d97706;
    --stefan:  #0369a1;
    --timo:    #15803d;
  }

  body {
    font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
    background: var(--off-white);
    color: var(--text);
    min-height: 100vh;
  }

  /* HEADER */
  .header {
    background: var(--grass);
    color: white;
    padding: 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 12px rgba(0,0,0,0.25);
  }
  .header-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 20px 10px;
  }
  .header-title {
    font-size: 1.5rem;
    font-weight: 900;
    letter-spacing: -0.03em;
    line-height: 1;
  }
  .header-sub {
    font-size: 0.72rem;
    opacity: 0.65;
    margin-top: 3px;
    letter-spacing: 0.04em;
  }
  .header-badge {
    background: var(--gold);
    color: #1a1a1a;
    font-weight: 900;
    font-size: 1.4rem;
    width: 48px;
    height: 48px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    line-height: 1;
  }
  .header-badge span { font-size: 0.5rem; font-weight: 700; opacity: 0.7; }

  /* MEMBER TABS */
  .tabs {
    display: flex;
    gap: 4px;
    padding: 6px 12px 0;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    scrollbar-width: none;
  }
  .tabs::-webkit-scrollbar { display: none; }
  .tab-btn {
    padding: 7px 14px;
    border: none;
    border-radius: 8px 8px 0 0;
    font-weight: 700;
    font-size: 0.82rem;
    cursor: pointer;
    white-space: nowrap;
    background: rgba(255,255,255,0.15);
    color: rgba(255,255,255,0.7);
    transition: all 0.15s;
    letter-spacing: 0.01em;
  }
  .tab-btn:hover { background: rgba(255,255,255,0.25); color: white; }
  .tab-btn.active { color: var(--text); }
  .tab-btn[data-member="Frida"].active    { background: var(--frida);   color: white; }
  .tab-btn[data-member="Linnea"].active   { background: var(--linnea);  color: white; }
  .tab-btn[data-member="Jessica"].active  { background: var(--jessica); color: white; }
  .tab-btn[data-member="Stefan"].active   { background: var(--stefan);  color: white; }
  .tab-btn[data-member="Timo"].active     { background: var(--timo);    color: white; }
  .tab-btn[data-member="summary"].active  { background: #1a1a1a;        color: white; }

  /* MAIN */
  .main { max-width: 960px; margin: 0 auto; padding: 20px 16px 40px; }

  /* MEMBER BANNER */
  .member-banner {
    border-radius: 14px;
    color: white;
    padding: 16px 20px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .member-banner[data-member="Frida"]   { background: linear-gradient(135deg, #c0397a, #e05e9a); }
  .member-banner[data-member="Linnea"]  { background: linear-gradient(135deg, #7c3aed, #a05cf0); }
  .member-banner[data-member="Jessica"] { background: linear-gradient(135deg, #d97706, #f59e0b); }
  .member-banner[data-member="Stefan"]  { background: linear-gradient(135deg, #0369a1, #0ea5e9); }
  .member-banner[data-member="Timo"]    { background: linear-gradient(135deg, #15803d, #22c55e); }
  .banner-name { font-size: 1.4rem; font-weight: 900; letter-spacing: -0.02em; }
  .banner-sub  { font-size: 0.72rem; opacity: 0.75; margin-top: 2px; }
  .banner-progress { text-align: right; }
  .banner-count { font-size: 2rem; font-weight: 900; line-height: 1; }
  .banner-label { font-size: 0.65rem; opacity: 0.75; }

  /* SECTION LABEL */
  .section-label {
    font-size: 0.68rem;
    font-weight: 800;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 10px;
    margin-top: 24px;
  }

  /* GROUPS GRID */
  .groups-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 12px;
    margin-bottom: 8px;
  }

  .group-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  }
  .group-card-header {
    background: #1a1a1a;
    color: white;
    padding: 8px 12px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .group-letter {
    font-size: 1.2rem;
    font-weight: 900;
    line-height: 1;
  }
  .group-eyebrow {
    font-size: 0.6rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    opacity: 0.5;
    line-height: 1;
  }
  .group-teams-list {
    padding: 8px 12px;
    border-bottom: 1px solid var(--border);
  }
  .group-team-row {
    font-size: 0.78rem;
    color: #555;
    padding: 2px 0;
    display: flex;
    align-items: center;
    gap: 5px;
  }
  .group-picks { padding: 8px 12px; display: flex; flex-direction: column; gap: 5px; }
  .pick-row { display: flex; align-items: center; gap: 6px; }
  .pick-medal { font-size: 0.9rem; width: 20px; flex-shrink: 0; text-align: center; }
  .pick-select {
    flex: 1;
    font-size: 0.75rem;
    border: 1px solid var(--border);
    border-radius: 7px;
    padding: 5px 6px;
    background: var(--off-white);
    color: var(--text);
    outline: none;
    cursor: pointer;
    transition: border-color 0.15s;
  }
  .pick-select:focus { border-color: #aaa; background: white; }
  .pick-select.filled { background: white; font-weight: 600; }

  /* GROUP DONE INDICATOR */
  .group-done {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #d1d5db;
    margin-left: auto;
    transition: background 0.3s;
  }
  .group-done.complete { background: #22c55e; }

  /* FINALS CARD */
  .finals-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    overflow: hidden;
    box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  }
  .finals-row {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 11px 16px;
    border-bottom: 1px solid var(--border);
  }
  .finals-row:last-child { border-bottom: none; }
  .finals-emoji { font-size: 1.1rem; width: 24px; flex-shrink: 0; text-align: center; }
  .finals-label { font-size: 0.8rem; color: #555; width: 130px; flex-shrink: 0; }
  .finals-select {
    flex: 1;
    font-size: 0.82rem;
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 7px 10px;
    background: var(--off-white);
    color: var(--text);
    outline: none;
    cursor: pointer;
    transition: border-color 0.15s;
  }
  .finals-select:focus { border-color: #aaa; background: white; }
  .finals-select.filled { background: white; font-weight: 600; }
  .finals-input {
    flex: 1;
    font-size: 0.82rem;
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 7px 10px;
    background: var(--off-white);
    color: var(--text);
    outline: none;
    transition: border-color 0.15s;
  }
  .finals-input:focus { border-color: #aaa; background: white; }

  /* SAVE TOAST */
  .toast {
    position: fixed;
    bottom: 24px;
    left: 50%;
    transform: translateX(-50%) translateY(80px);
    background: #1a1a1a;
    color: white;
    padding: 10px 20px;
    border-radius: 50px;
    font-size: 0.82rem;
    font-weight: 600;
    transition: transform 0.3s ease;
    z-index: 999;
    pointer-events: none;
    white-space: nowrap;
  }
  .toast.show { transform: translateX(-50%) translateY(0); }

  /* SUMMARY */
  .summary-section { margin-bottom: 24px; }
  .summary-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 18px 20px;
    box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  }
  .summary-title { font-size: 1rem; font-weight: 800; margin-bottom: 14px; }
  .vote-bar-row { display: flex; align-items: center; gap: 10px; margin-bottom: 8px; }
  .vote-bar-label { font-size: 0.85rem; width: 140px; flex-shrink: 0; }
  .vote-bar-track { flex: 1; height: 10px; background: #f0f0ee; border-radius: 99px; overflow: hidden; }
  .vote-bar-fill { height: 100%; background: var(--gold); border-radius: 99px; transition: width 0.5s ease; }
  .vote-bar-count { font-size: 0.78rem; font-weight: 700; color: var(--muted); width: 24px; }

  .overview-table { width: 100%; border-collapse: collapse; font-size: 0.82rem; }
  .overview-table th { text-align: left; font-size: 0.65rem; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; color: var(--muted); padding: 6px 10px 8px; border-bottom: 1px solid var(--border); }
  .overview-table td { padding: 9px 10px; border-bottom: 1px solid #f5f5f3; vertical-align: top; }
  .overview-table tr:last-child td { border-bottom: none; }
  .name-chip {
    display: inline-block;
    padding: 2px 10px;
    border-radius: 99px;
    font-size: 0.75rem;
    font-weight: 700;
    color: white;
  }
  .chip-Frida   { background: var(--frida); }
  .chip-Linnea  { background: var(--linnea); }
  .chip-Jessica { background: var(--jessica); }
  .chip-Stefan  { background: var(--stefan); }
  .chip-Timo    { background: var(--timo); }

  .empty { color: #ccc; }
  .italic { font-style: italic; color: var(--muted); font-size: 0.78rem; }

  /* RESPONSIVE */
  @media (max-width: 520px) {
    .groups-grid { grid-template-columns: 1fr 1fr; }
    .finals-label { width: 100px; font-size: 0.75rem; }
    .header-title { font-size: 1.2rem; }
  }
  @media (max-width: 360px) {
    .groups-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<div class="header">
  <div class="header-top">
    <div>
      <div class="header-title">⚽ VM 2026</div>
      <div class="header-sub">USA · Kanada · Mexiko &nbsp;·&nbsp; 11 jun – 19 jul</div>
    </div>
    <div class="header-badge">
      <span id="filled-count">0</span>/<span id="total-count">5</span>
      <span>börjat</span>
    </div>
  </div>
  <div class="tabs" id="tabs"></div>
</div>

<div class="main" id="main"></div>

<div class="toast" id="toast">✓ Sparat!</div>

<script>
const MEMBERS = ["Frida", "Linnea", "Jessica", "Stefan", "Timo"];

const GROUPS = [
  { name: "A", teams: ["Mexiko", "Sydafrika", "Sydkorea", "Tjeckien"] },
  { name: "B", teams: ["Kanada", "Bosnien", "Qatar", "Schweiz"] },
  { name: "C", teams: ["Brasilien", "Marocko", "Haiti", "Skottland"] },
  { name: "D", teams: ["USA", "Paraguay", "Australien", "Turkiet"] },
  { name: "E", teams: ["Tyskland", "Curaçao", "Elfenbenskusten", "Ecuador"] },
  { name: "F", teams: ["Nederländerna", "Japan", "Sverige", "Tunisien"] },
  { name: "G", teams: ["Belgien", "Egypten", "Iran", "Nya Zeeland"] },
  { name: "H", teams: ["Spanien", "Kap Verde", "Saudiarabien", "Uruguay"] },
  { name: "I", teams: ["Frankrike", "Senegal", "Irak", "Norge"] },
  { name: "J", teams: ["Argentina", "Algeriet", "Österrike", "Jordanien"] },
  { name: "K", teams: ["Portugal", "DR Kongo", "Uzbekistan", "Colombia"] },
  { name: "L", teams: ["England", "Kroatien", "Ghana", "Panama"] },
];

const ALL_TEAMS = [...new Set(GROUPS.flatMap(g => g.teams))].sort();

const FLAGS = {
  "Mexiko":"🇲🇽","Sydafrika":"🇿🇦","Sydkorea":"🇰🇷","Tjeckien":"🇨🇿",
  "Kanada":"🇨🇦","Bosnien":"🇧🇦","Qatar":"🇶🇦","Schweiz":"🇨🇭",
  "Brasilien":"🇧🇷","Marocko":"🇲🇦","Haiti":"🇭🇹","Skottland":"🏴󠁧󠁢󠁳󠁣󠁴󠁿",
  "USA":"🇺🇸","Paraguay":"🇵🇾","Australien":"🇦🇺","Turkiet":"🇹🇷",
  "Tyskland":"🇩🇪","Curaçao":"🇨🇼","Elfenbenskusten":"🇨🇮","Ecuador":"🇪🇨",
  "Nederländerna":"🇳🇱","Japan":"🇯🇵","Sverige":"🇸🇪","Tunisien":"🇹🇳",
  "Belgien":"🇧🇪","Egypten":"🇪🇬","Iran":"🇮🇷","Nya Zeeland":"🇳🇿",
  "Spanien":"🇪🇸","Kap Verde":"🇨🇻","Saudiarabien":"🇸🇦","Uruguay":"🇺🇾",
  "Frankrike":"🇫🇷","Senegal":"🇸🇳","Irak":"🇮🇶","Norge":"🇳🇴",
  "Argentina":"🇦🇷","Algeriet":"🇩🇿","Österrike":"🇦🇹","Jordanien":"🇯🇴",
  "Portugal":"🇵🇹","DR Kongo":"🇨🇩","Uzbekistan":"🇺🇿","Colombia":"🇨🇴",
  "England":"🏴󠁧󠁢󠁥󠁮󠁧󠁿","Kroatien":"🇭🇷","Ghana":"🇬🇭","Panama":"🇵🇦",
};

const MEDALS = ["🥇","🥈","🥉","4:a"];
const MEDAL_LABELS = ["Etta","Tvåa","Trean","Fyran"];

// Load/save
function loadData() {
  try { return JSON.parse(localStorage.getItem("vm2026") || "{}"); } catch(e) { return {}; }
}
function saveData(data) {
  localStorage.setItem("vm2026", JSON.stringify(data));
  showToast();
}
let appData = loadData();

// Toast
let toastTimer;
function showToast() {
  const t = document.getElementById("toast");
  t.classList.add("show");
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => t.classList.remove("show"), 1800);
}

// Active tab
let activeTab = MEMBERS[0];

function setTab(name) {
  activeTab = name;
  document.querySelectorAll(".tab-btn").forEach(b => {
    b.classList.toggle("active", b.dataset.member === name);
  });
  renderMain();
}

// Count completed groups for a member
function countCompletedGroups(member) {
  const groups = appData[member]?.groups || {};
  return GROUPS.filter(g => {
    const p = groups[g.name] || [];
    const filled = p.filter(Boolean);
    return filled.length === 4 && new Set(filled).size === 4;
  }).length;
}

// Build team options for a group select
function teamOptions(groupTeams, selectedValues, currentRank) {
  let html = '<option value="">— välj —</option>';
  groupTeams.forEach(team => {
    const isSelected = selectedValues[currentRank] === team;
    const isUsed = selectedValues.includes(team) && !isSelected;
    html += `<option value="${team}" ${isUsed ? "disabled" : ""} ${isSelected ? "selected" : ""}>${FLAGS[team]||"🏳️"} ${team}</option>`;
  });
  return html;
}

// Build all-teams options
function allTeamOptions(selected) {
  let html = '<option value="">— välj lag —</option>';
  ALL_TEAMS.forEach(team => {
    html += `<option value="${team}" ${selected === team ? "selected" : ""}>${FLAGS[team]||"🏳️"} ${team}</option>`;
  });
  return html;
}

function renderTabs() {
  const tabs = document.getElementById("tabs");
  let html = "";
  MEMBERS.forEach(m => {
    html += `<button class="tab-btn${m===activeTab?" active":""}" data-member="${m}" onclick="setTab('${m}')">${m}</button>`;
  });
  html += `<button class="tab-btn${activeTab==="summary"?" active":""}" data-member="summary" onclick="setTab('summary')" style="margin-left:auto">📊 Sammanfattning</button>`;
  tabs.innerHTML = html;
}

function renderMain() {
  const main = document.getElementById("main");
  if (activeTab === "summary") {
    main.innerHTML = renderSummary();
  } else {
    main.innerHTML = renderMemberForm(activeTab);
  }
  updateHeaderCount();
}

function updateHeaderCount() {
  const started = MEMBERS.filter(m => {
    const g = appData[m]?.groups || {};
    return Object.keys(g).length > 0 || appData[m]?.finals?.winner;
  }).length;
  document.getElementById("filled-count").textContent = started;
}

function renderMemberForm(member) {
  const memberData = appData[member] || {};
  const groups = memberData.groups || {};
  const finals = memberData.finals || {};
  const completed = countCompletedGroups(member);

  let html = `
    <div class="member-banner" data-member="${member}">
      <div>
        <div class="banner-name">${member}</div>
        <div class="banner-sub">VM 2026 — Tips</div>
      </div>
      <div class="banner-progress">
        <div class="banner-count">${completed}/12</div>
        <div class="banner-label">grupper klara</div>
      </div>
    </div>

    <div class="section-label">Gruppspel — rangordna lagen i varje grupp</div>
    <div class="groups-grid">
  `;

  GROUPS.forEach(group => {
    const picks = groups[group.name] || ["","","",""];
    const filled = picks.filter(Boolean);
    const isDone = filled.length === 4 && new Set(filled).size === 4;

    html += `<div class="group-card">
      <div class="group-card-header">
        <div>
          <div class="group-eyebrow">Grupp</div>
          <div class="group-letter">${group.name}</div>
        </div>
        <div class="group-done${isDone?" complete":""}" id="done-${member}-${group.name}" title="${isDone?"Klar!":"Inte klar ännu"}"></div>
      </div>
      <div class="group-teams-list">`;

    group.teams.forEach(t => {
      html += `<div class="group-team-row"><span>${FLAGS[t]||"🏳️"}</span><span>${t}</span></div>`;
    });

    html += `</div><div class="group-picks">`;

    for (let i = 0; i < 4; i++) {
      html += `
        <div class="pick-row">
          <span class="pick-medal">${MEDALS[i]}</span>
          <select class="pick-select${picks[i]?" filled":""}"
            data-member="${member}" data-group="${group.name}" data-rank="${i}"
            onchange="handleGroupPick(this)">
            ${teamOptions(group.teams, picks, i)}
          </select>
        </div>`;
    }

    html += `</div></div>`;
  });

  html += `</div>

    <div class="section-label" style="margin-top:28px">Slutspel — dina favoriter</div>
    <div class="finals-card">
      <div class="finals-row">
        <span class="finals-emoji">🏆</span>
        <span class="finals-label">Världsmästare</span>
        <select class="finals-select${finals.winner?" filled":""}" data-member="${member}" data-key="winner" onchange="handleFinal(this)">
          ${allTeamOptions(finals.winner||"")}
        </select>
      </div>
      <div class="finals-row">
        <span class="finals-emoji">🥈</span>
        <span class="finals-label">Finalist</span>
        <select class="finals-select${finals.finalist?" filled":""}" data-member="${member}" data-key="finalist" onchange="handleFinal(this)">
          ${allTeamOptions(finals.finalist||"")}
        </select>
      </div>
      <div class="finals-row">
        <span class="finals-emoji">🥉</span>
        <span class="finals-label">Trean</span>
        <select class="finals-select${finals.third?" filled":""}" data-member="${member}" data-key="third" onchange="handleFinal(this)">
          ${allTeamOptions(finals.third||"")}
        </select>
      </div>
      <div class="finals-row">
        <span class="finals-emoji">❤️</span>
        <span class="finals-label">Mitt favoritlag</span>
        <select class="finals-select${finals.fav?" filled":""}" data-member="${member}" data-key="fav" onchange="handleFinal(this)">
          ${allTeamOptions(finals.fav||"")}
        </select>
      </div>
      <div class="finals-row">
        <span class="finals-emoji">💬</span>
        <span class="finals-label">Kommentar</span>
        <input type="text" class="finals-input" placeholder="Något att tillägga..."
          value="${(finals.comment||"").replace(/"/g,'&quot;')}"
          data-member="${member}" data-key="comment"
          oninput="handleFinal(this)">
      </div>
    </div>
  `;

  return html;
}

function handleGroupPick(el) {
  const { member, group, rank } = el.dataset;
  if (!appData[member]) appData[member] = {};
  if (!appData[member].groups) appData[member].groups = {};
  if (!appData[member].groups[group]) appData[member].groups[group] = ["","","",""];

  appData[member].groups[group][parseInt(rank)] = el.value;
  el.classList.toggle("filled", !!el.value);

  // Update done indicator without full re-render
  const picks = appData[member].groups[group];
  const filled = picks.filter(Boolean);
  const isDone = filled.length === 4 && new Set(filled).size === 4;
  const dot = document.getElementById(`done-${member}-${group}`);
  if (dot) dot.classList.toggle("complete", isDone);

  // Update banner count
  const banner = document.querySelector(".banner-count");
  if (banner) banner.textContent = countCompletedGroups(member) + "/12";

  saveData(appData);
  updateHeaderCount();
}

function handleFinal(el) {
  const { member, key } = el.dataset;
  if (!appData[member]) appData[member] = {};
  if (!appData[member].finals) appData[member].finals = {};
  appData[member].finals[key] = el.value || el.value; // works for both select and input
  if (el.tagName === "SELECT") el.classList.toggle("filled", !!el.value);
  saveData(appData);
  updateHeaderCount();
}

function renderSummary() {
  // Count VM winner votes
  const wmVotes = {};
  MEMBERS.forEach(m => {
    const w = appData[m]?.finals?.winner;
    if (w) wmVotes[w] = (wmVotes[w]||0) + 1;
  });
  const topWM = Object.entries(wmVotes).sort((a,b) => b[1]-a[1]);

  let html = `<div class="summary-section">
    <div class="summary-card">
      <div class="summary-title">🏆 Vem tror ni vinner VM?</div>`;

  if (topWM.length === 0) {
    html += `<p style="color:var(--muted);font-size:0.85rem">Ingen har fyllt i sin gissning än.</p>`;
  } else {
    topWM.forEach(([team, count]) => {
      const pct = (count / MEMBERS.length) * 100;
      html += `
        <div class="vote-bar-row">
          <div class="vote-bar-label">${FLAGS[team]||"🏳️"} ${team}</div>
          <div class="vote-bar-track"><div class="vote-bar-fill" style="width:${pct}%"></div></div>
          <div class="vote-bar-count">${count}</div>
        </div>`;
    });
  }

  html += `</div></div>

  <div class="summary-section">
    <div class="summary-card">
      <div class="summary-title">📋 Allas tips — översikt</div>
      <table class="overview-table">
        <thead><tr>
          <th>Namn</th><th>🏆 Mästare</th><th>🥈 Finalist</th><th>❤️ Favorit</th><th>💬 Kommentar</th>
        </tr></thead>
        <tbody>`;

  MEMBERS.forEach(m => {
    const f = appData[m]?.finals || {};
    html += `<tr>
      <td><span class="name-chip chip-${m}">${m}</span></td>
      <td>${f.winner ? `${FLAGS[f.winner]||""} ${f.winner}` : '<span class="empty">—</span>'}</td>
      <td>${f.finalist ? `${FLAGS[f.finalist]||""} ${f.finalist}` : '<span class="empty">—</span>'}</td>
      <td>${f.fav ? `${FLAGS[f.fav]||""} ${f.fav}` : '<span class="empty">—</span>'}</td>
      <td class="italic">${f.comment || '—'}</td>
    </tr>`;
  });

  html += `</tbody></table></div></div>

  <div class="summary-section">
    <div class="summary-card">
      <div class="summary-title">📊 Framsteg per person</div>`;

  MEMBERS.forEach(m => {
    const done = countCompletedGroups(m);
    const pct = (done/12)*100;
    html += `
      <div class="vote-bar-row">
        <div class="vote-bar-label"><span class="name-chip chip-${m}" style="margin-right:6px">${m}</span></div>
        <div class="vote-bar-track"><div class="vote-bar-fill" style="width:${pct}%;background:var(--grass-light)"></div></div>
        <div class="vote-bar-count" style="font-size:0.7rem">${done}/12</div>
      </div>`;
  });

  html += `</div></div>`;
  return html;
}

// Init
renderTabs();
renderMain();
</script>
</body>
</html>
