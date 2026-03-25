<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PunchScan — Construction Management</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jsQR/1.4.0/jsQR.min.js"></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=IBM+Plex+Mono:wght@400;500;600&family=IBM+Plex+Sans:wght@300;400;500;600&display=swap');

:root {
  --bg: #0f0f0d;
  --surface: #1a1a17;
  --surface2: #242420;
  --surface3: #2e2e29;
  --accent: #f5a623;
  --accent2: #e8391a;
  --text: #e8e6df;
  --text-dim: #8a8878;
  --text-muted: #55554a;
  --border: #333330;
  --success: #4caf72;
  --warning: #f5a623;
  --danger: #e8391a;
  --scan-green: #00ff88;
}

* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: 'IBM Plex Sans', sans-serif;
  min-height: 100vh;
  overflow-x: hidden;
}

/* ─── HEADER ─── */
header {
  background: var(--surface);
  border-bottom: 2px solid var(--accent);
  padding: 0 24px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: sticky;
  top: 0;
  z-index: 200;
}
.logo {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 28px;
  letter-spacing: 3px;
  color: var(--accent);
  cursor: pointer;
}
.logo span { color: var(--text-muted); font-size: 13px; font-family: 'IBM Plex Mono', monospace; margin-left: 10px; letter-spacing: 1px; }

.nav-tabs {
  display: flex;
  height: 100%;
  gap: 2px;
  align-items: center;
}
.nav-tab {
  height: 100%;
  background: none;
  border: none;
  color: var(--text-dim);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 2px;
  text-transform: uppercase;
  padding: 0 20px;
  cursor: pointer;
  border-bottom: 3px solid transparent;
  transition: all .2s;
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: 3px;
}
.nav-tab:hover { color: var(--text); }
.nav-tab.active { color: var(--accent); border-bottom-color: var(--accent); }
.nav-tab .nav-icon { font-size: 14px; }

.header-right {
  display: flex; gap: 12px; align-items: center;
}
.stat-pill {
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 4px;
  padding: 4px 12px;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  color: var(--text-dim);
  display: flex; align-items: center; gap: 6px;
}
.stat-pill .dot { width: 7px; height: 7px; border-radius: 50%; }
.dot-red { background: var(--danger); }
.dot-amber { background: var(--warning); }
.dot-green { background: var(--success); }

/* ─── PAGE SYSTEM ─── */
.page { display: none; }
.page.active { display: flex; flex-direction: column; }

/* ══════════════════════════════════════════
   HOME / DASHBOARD PAGE
══════════════════════════════════════════ */
#page-home {
  min-height: calc(100vh - 56px);
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  padding: 60px 32px 40px;
  background: radial-gradient(ellipse at 50% 0%, #1f1e19 0%, #0f0f0d 60%);
}

.home-hero {
  text-align: center;
  margin-bottom: 64px;
}
.home-hero h1 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 80px;
  letter-spacing: 8px;
  color: var(--accent);
  line-height: 1;
  margin-bottom: 12px;
}
.home-hero p {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 13px;
  color: var(--text-dim);
  letter-spacing: 2px;
  text-transform: uppercase;
}

.home-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  width: 100%;
  max-width: 900px;
  margin-bottom: 48px;
}

.home-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 28px 28px 24px;
  cursor: pointer;
  transition: all .25s;
  position: relative;
  overflow: hidden;
}
.home-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
  background: var(--accent);
  transform: scaleX(0);
  transform-origin: left;
  transition: transform .3s;
}
.home-card:hover { border-color: var(--accent); background: var(--surface2); transform: translateY(-2px); }
.home-card:hover::before { transform: scaleX(1); }

.home-card-icon {
  font-size: 36px;
  margin-bottom: 16px;
  display: block;
}
.home-card h2 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 28px;
  letter-spacing: 2px;
  color: var(--text);
  margin-bottom: 8px;
}
.home-card p {
  font-size: 13px;
  color: var(--text-dim);
  line-height: 1.6;
  margin-bottom: 20px;
}
.home-card-arrow {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 2px;
  color: var(--accent);
  text-transform: uppercase;
}

.home-stats {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 14px;
  width: 100%;
  max-width: 900px;
}
.home-stat {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 20px;
  text-align: center;
}
.home-stat-num {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 42px;
  color: var(--accent);
  line-height: 1;
  margin-bottom: 4px;
}
.home-stat-label {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--text-muted);
}

/* ══════════════════════════════════════════
   PROJECTS PAGE
══════════════════════════════════════════ */
#page-projects {
  height: calc(100vh - 56px);
  flex-direction: row;
}

.proj-layout {
  display: flex;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.proj-main {
  flex: 1;
  overflow-y: auto;
  padding: 28px 32px;
}
.proj-main::-webkit-scrollbar { width: 4px; }
.proj-main::-webkit-scrollbar-track { background: transparent; }
.proj-main::-webkit-scrollbar-thumb { background: var(--border); }

.proj-topbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 20px;
  gap: 12px;
  flex-wrap: wrap;
}
.proj-topbar h2 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 26px;
  letter-spacing: 3px;
  color: var(--text);
}
.proj-filters {
  display: flex; gap: 8px; flex-wrap: wrap; align-items: center;
}

input[type="text"], input[type="number"], input[type="date"], select, textarea {
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 5px;
  padding: 8px 12px;
  color: var(--text);
  font-family: 'IBM Plex Sans', sans-serif;
  font-size: 13px;
  transition: border-color .2s;
}
input:focus, select:focus, textarea:focus { outline: none; border-color: var(--accent); }
input::placeholder, textarea::placeholder { color: var(--text-muted); }
select option { background: var(--surface2); }

.btn {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 1px;
  padding: 8px 18px;
  border-radius: 5px;
  border: 1px solid var(--border);
  cursor: pointer;
  transition: all .2s;
  display: inline-flex; align-items: center; gap: 6px;
}
.btn-ghost { background: none; color: var(--text-dim); }
.btn-ghost:hover { border-color: var(--text-dim); color: var(--text); }
.btn-primary { background: var(--accent); color: var(--bg); border-color: var(--accent); font-weight: 600; }
.btn-primary:hover { background: #f7b840; }
.btn-danger { background: none; color: var(--danger); border-color: rgba(232,57,26,.4); }
.btn-danger:hover { background: rgba(232,57,26,.1); }
.btn-success { background: var(--success); color: var(--bg); border-color: var(--success); font-weight: 600; }
.btn-scan { background: var(--scan-green); color: var(--bg); border-color: var(--scan-green); font-weight: 700; font-size: 12px; padding: 10px 24px; }
.btn-scan:hover { background: #00e07a; }

/* Projects Table */
.proj-table-wrap {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 8px;
  overflow: hidden;
}

.proj-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 13px;
}
.proj-table th {
  background: var(--surface2);
  padding: 10px 14px;
  text-align: left;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: var(--text-muted);
  border-bottom: 1px solid var(--border);
  cursor: pointer;
  white-space: nowrap;
  user-select: none;
}
.proj-table th:hover { color: var(--text-dim); }
.proj-table td {
  padding: 12px 14px;
  border-bottom: 1px solid var(--border);
  vertical-align: middle;
}
.proj-table tr:last-child td { border-bottom: none; }
.proj-table tr:hover td { background: var(--surface2); }
.proj-table tr { cursor: pointer; transition: background .15s; }

.proj-name-cell .name { font-weight: 500; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; max-width: 220px; display: block; }
.proj-name-cell .loc { font-size: 11px; color: var(--text-muted); margin-top: 2px; }

.badge {
  display: inline-flex;
  align-items: center;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 9px;
  letter-spacing: 1px;
  text-transform: uppercase;
  padding: 3px 8px;
  border-radius: 3px;
  font-weight: 600;
  white-space: nowrap;
}
.badge-open    { background: rgba(232,57,26,.12); color: #e8391a; border: 1px solid rgba(232,57,26,.25); }
.badge-active  { background: rgba(245,166,35,.12); color: #f5a623; border: 1px solid rgba(245,166,35,.25); }
.badge-complete{ background: rgba(76,175,114,.12); color: #4caf72; border: 1px solid rgba(76,175,114,.25); }
.badge-on-hold { background: rgba(138,136,120,.12); color: #8a8878; border: 1px solid rgba(138,136,120,.25); }
.badge-critical{ background: rgba(232,57,26,.15); color: #e8391a; border: 1px solid rgba(232,57,26,.3); }
.badge-high    { background: rgba(245,166,35,.15); color: #f5a623; border: 1px solid rgba(245,166,35,.3); }
.badge-normal  { background: rgba(76,175,114,.12); color: #4caf72; border: 1px solid rgba(76,175,114,.25); }
.badge-low     { background: rgba(138,136,120,.12); color: #8a8878; border: 1px solid rgba(138,136,120,.25); }

.count-bar {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  color: var(--text-muted);
  margin-top: 10px;
}

/* Edit Panel */
.edit-panel {
  width: 0;
  min-width: 0;
  background: var(--surface);
  border-left: 1px solid var(--border);
  overflow: hidden;
  transition: width .3s ease, min-width .3s ease;
  display: flex;
  flex-direction: column;
}
.edit-panel.open {
  width: 360px;
  min-width: 360px;
}

.edit-panel-inner {
  width: 360px;
  padding: 24px 24px;
  overflow-y: auto;
  flex: 1;
}
.edit-panel-inner::-webkit-scrollbar { width: 4px; }
.edit-panel-inner::-webkit-scrollbar-thumb { background: var(--border); }

.edit-panel-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 24px;
  padding-bottom: 16px;
  border-bottom: 1px solid var(--border);
}
.edit-panel-header h3 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 22px;
  letter-spacing: 2px;
  color: var(--accent);
}
.close-panel-btn {
  background: none;
  border: none;
  color: var(--text-muted);
  font-size: 20px;
  cursor: pointer;
  padding: 2px 6px;
  border-radius: 4px;
  transition: color .2s;
}
.close-panel-btn:hover { color: var(--text); }

.field-group { margin-bottom: 16px; }
.field-group label {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: var(--text-muted);
  display: block;
  margin-bottom: 6px;
}
.field-group input,
.field-group select,
.field-group textarea { width: 100%; }
.field-row { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
.edit-panel-footer {
  padding: 16px 24px;
  border-top: 1px solid var(--border);
  display: flex;
  justify-content: space-between;
  gap: 8px;
}

/* ══════════════════════════════════════════
   QR SCANNER PAGE
══════════════════════════════════════════ */
#page-scanner {
  height: calc(100vh - 56px);
  flex-direction: row;
}

.scanner-layout { display: flex; width: 100%; height: 100%; }

.scanner-sidebar {
  width: 300px;
  min-width: 300px;
  background: var(--surface);
  border-right: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  overflow: hidden;
}
.scanner-sidebar-header {
  padding: 14px 18px;
  border-bottom: 1px solid var(--border);
  display: flex; align-items: center; justify-content: space-between;
}
.scanner-sidebar-header h3 {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--text-dim);
}

.filter-tabs { display: flex; border-bottom: 1px solid var(--border); }
.filter-tab {
  flex: 1;
  background: none;
  border: none;
  color: var(--text-muted);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 9px;
  letter-spacing: 1px;
  text-transform: uppercase;
  padding: 9px 4px;
  cursor: pointer;
  border-bottom: 2px solid transparent;
  transition: all .2s;
}
.filter-tab:hover { color: var(--text-dim); }
.filter-tab.active { color: var(--accent); border-bottom-color: var(--accent); }

.items-list {
  flex: 1;
  overflow-y: auto;
  padding: 8px;
}
.items-list::-webkit-scrollbar { width: 4px; }
.items-list::-webkit-scrollbar-thumb { background: var(--border); }

.punch-item {
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 6px;
  padding: 10px 12px;
  margin-bottom: 6px;
  cursor: pointer;
  transition: all .2s;
  position: relative;
}
.punch-item:hover { border-color: var(--accent); background: var(--surface3); }
.punch-item.active { border-color: var(--accent); background: var(--surface3); }
.punch-item.active::before {
  content: '';
  position: absolute;
  left: 0; top: 0; bottom: 0;
  width: 3px;
  background: var(--accent);
  border-radius: 6px 0 0 6px;
}
.item-qr-id {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  color: var(--accent);
  letter-spacing: 1px;
  margin-bottom: 4px;
}
.item-title {
  font-size: 12px;
  font-weight: 500;
  margin-bottom: 4px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.item-meta { display: flex; align-items: center; gap: 6px; flex-wrap: wrap; }
.status-badge {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 9px;
  letter-spacing: 1px;
  text-transform: uppercase;
  padding: 2px 6px;
  border-radius: 3px;
  font-weight: 600;
}
.status-open       { background: rgba(232,57,26,.15); color: var(--danger); border: 1px solid rgba(232,57,26,.3); }
.status-in-progress{ background: rgba(245,166,35,.15); color: var(--warning); border: 1px solid rgba(245,166,35,.3); }
.status-complete   { background: rgba(76,175,114,.15); color: var(--success); border: 1px solid rgba(76,175,114,.3); }

/* Scanner main */
.scanner-main {
  flex: 1;
  display: flex;
  flex-direction: column;
  overflow: hidden;
}

.scanner-view {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 28px;
  padding: 40px;
  background: radial-gradient(ellipse at center, #1a1a17 0%, #0f0f0d 70%);
}
.scanner-view.hidden { display: none; }

.scanner-box {
  position: relative;
  width: 320px;
  height: 320px;
  border-radius: 8px;
  overflow: hidden;
  background: #000;
  box-shadow: 0 0 0 1px var(--border);
}
.scanner-box video { width: 100%; height: 100%; object-fit: cover; display: block; }
.scanner-overlay { position: absolute; inset: 0; pointer-events: none; }
.scanner-corner {
  position: absolute;
  width: 26px; height: 26px;
  border-color: var(--scan-green);
  border-style: solid;
  border-width: 0;
}
.scanner-corner.tl { top: 18px; left: 18px; border-top-width: 3px; border-left-width: 3px; }
.scanner-corner.tr { top: 18px; right: 18px; border-top-width: 3px; border-right-width: 3px; }
.scanner-corner.bl { bottom: 18px; left: 18px; border-bottom-width: 3px; border-left-width: 3px; }
.scanner-corner.br { bottom: 18px; right: 18px; border-bottom-width: 3px; border-right-width: 3px; }
.scanner-line {
  position: absolute;
  left: 18px; right: 18px;
  height: 2px;
  background: linear-gradient(90deg, transparent, var(--scan-green), transparent);
  animation: scan-sweep 2s ease-in-out infinite;
}
@keyframes scan-sweep {
  0%   { top: 18px; opacity: 0; }
  10%  { opacity: 1; }
  90%  { opacity: 1; }
  100% { top: calc(100% - 18px); opacity: 0; }
}
.scanner-status {
  position: absolute;
  bottom: 12px; left: 0; right: 0;
  text-align: center;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 2px;
  color: var(--scan-green);
}
.scanner-canvas { display: none; }

.scanner-label {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 32px;
  letter-spacing: 4px;
  color: var(--text-dim);
}
.scanner-sublabel {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  color: var(--text-muted);
  letter-spacing: 1px;
  text-align: center;
  max-width: 260px;
}
.manual-btn {
  background: var(--surface2);
  border: 1px solid var(--border);
  color: var(--text-dim);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 1px;
  padding: 9px 20px;
  border-radius: 5px;
  cursor: pointer;
  transition: all .2s;
}
.manual-btn:hover { border-color: var(--accent); color: var(--accent); }

/* Detail view */
.detail-view { flex: 1; overflow-y: auto; display: none; }
.detail-view::-webkit-scrollbar { width: 4px; }
.detail-view::-webkit-scrollbar-thumb { background: var(--border); }
.detail-view.visible { display: block; }

.detail-topbar {
  background: var(--surface);
  border-bottom: 1px solid var(--border);
  padding: 12px 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: sticky;
  top: 0;
  z-index: 10;
}
.detail-qr { font-family: 'IBM Plex Mono', monospace; font-size: 12px; color: var(--accent); }
.detail-topbar-actions { display: flex; gap: 8px; }

.detail-body { padding: 24px 28px; max-width: 800px; }

.detail-title-row {
  display: flex; align-items: flex-start; gap: 12px; margin-bottom: 20px;
}
.detail-title-input {
  flex: 1;
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 6px;
  padding: 12px 16px;
  color: var(--text);
  font-size: 18px;
  font-weight: 500;
  transition: border-color .2s;
}
.detail-title-input:focus { outline: none; border-color: var(--accent); }
.detail-title-input::placeholder { color: var(--text-muted); }

.status-select {
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 6px;
  padding: 12px 14px;
  color: var(--text);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  cursor: pointer;
  min-width: 130px;
}
.status-select:focus { outline: none; border-color: var(--accent); }

.section-label {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--text-muted);
  margin-bottom: 10px;
  display: flex; align-items: center; gap: 10px;
}
.section-label::after { content: ''; flex: 1; height: 1px; background: var(--border); }

.notes-area {
  width: 100%;
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 6px;
  padding: 12px 16px;
  color: var(--text);
  font-size: 13px;
  line-height: 1.7;
  resize: vertical;
  min-height: 100px;
  transition: border-color .2s;
  margin-bottom: 20px;
}
.notes-area:focus { outline: none; border-color: var(--accent); }

.meta-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
  margin-bottom: 24px;
}
.meta-field label {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  color: var(--text-muted);
  letter-spacing: 1px;
  text-transform: uppercase;
  display: block;
  margin-bottom: 5px;
}
.meta-field input, .meta-field select {
  width: 100%;
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 5px;
  padding: 9px 11px;
  color: var(--text);
  font-size: 13px;
  transition: border-color .2s;
}
.meta-field input:focus, .meta-field select:focus { outline: none; border-color: var(--accent); }

/* Media */
.media-upload-row { display: flex; gap: 10px; margin-bottom: 12px; }
.upload-btn {
  flex: 1;
  background: var(--surface2);
  border: 1px dashed var(--border);
  border-radius: 6px;
  padding: 14px;
  text-align: center;
  cursor: pointer;
  transition: all .2s;
  color: var(--text-dim);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 1px;
  display: flex; flex-direction: column; align-items: center; gap: 6px;
}
.upload-btn:hover { border-color: var(--accent); color: var(--accent); background: var(--surface3); }
.upload-btn .icon { font-size: 18px; }
input[type="file"] { display: none; }

.media-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
  gap: 8px;
}
.media-thumb {
  aspect-ratio: 1;
  border-radius: 5px;
  overflow: hidden;
  position: relative;
  background: var(--surface3);
  border: 1px solid var(--border);
  cursor: pointer;
  transition: all .2s;
}
.media-thumb:hover { transform: scale(1.03); border-color: var(--accent); }
.media-thumb img, .media-thumb video { width: 100%; height: 100%; object-fit: cover; }
.media-thumb .thumb-overlay {
  position: absolute; inset: 0;
  background: rgba(0,0,0,.5);
  opacity: 0;
  transition: opacity .2s;
  display: flex; align-items: center; justify-content: center;
  font-size: 18px;
}
.media-thumb:hover .thumb-overlay { opacity: 1; }
.media-type-badge {
  position: absolute; bottom: 5px; right: 5px;
  background: rgba(0,0,0,.7);
  border-radius: 3px;
  padding: 2px 5px;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 9px;
  color: var(--text);
  text-transform: uppercase;
}
.media-delete {
  position: absolute; top: 4px; right: 4px;
  width: 20px; height: 20px;
  background: var(--danger);
  border: none; border-radius: 3px;
  color: #fff; font-size: 11px;
  cursor: pointer;
  display: none; align-items: center; justify-content: center;
}
.media-thumb:hover .media-delete { display: flex; }

/* Log */
.log-entry {
  display: flex; align-items: flex-start; gap: 10px;
  padding: 8px 0;
  border-bottom: 1px solid var(--border);
  font-size: 12px;
}
.log-dot { width: 7px; height: 7px; border-radius: 50%; background: var(--accent); margin-top: 3px; flex-shrink: 0; }
.log-text { flex: 1; color: var(--text-dim); }
.log-time { font-family: 'IBM Plex Mono', monospace; font-size: 10px; color: var(--text-muted); white-space: nowrap; }

/* ─── TOAST ─── */
.toast {
  position: fixed;
  bottom: 24px; right: 24px;
  background: var(--surface3);
  border: 1px solid var(--border);
  border-left: 3px solid var(--success);
  border-radius: 6px;
  padding: 12px 18px;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 12px;
  color: var(--text);
  z-index: 1000;
  transform: translateX(120%);
  transition: transform .3s ease;
  max-width: 300px;
}
.toast.show { transform: translateX(0); }
.toast.error { border-left-color: var(--danger); }

/* ─── MODALS ─── */
.modal-backdrop {
  position: fixed; inset: 0;
  background: rgba(0,0,0,.85);
  z-index: 500;
  display: none;
  align-items: center; justify-content: center;
}
.modal-backdrop.open { display: flex; }
.modal {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 28px;
  width: 440px;
  max-width: 92vw;
  max-height: 90vh;
  overflow-y: auto;
}
.modal h3 {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 22px;
  letter-spacing: 2px;
  color: var(--accent);
  margin-bottom: 20px;
}
.modal-sub { font-size: 12px; color: var(--text-dim); margin-bottom: 16px; font-family: 'IBM Plex Mono', monospace; }
.modal-input {
  width: 100%;
  background: var(--surface2);
  border: 1px solid var(--border);
  border-radius: 5px;
  padding: 10px 14px;
  color: var(--text);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 13px;
  margin-bottom: 14px;
}
.modal-input:focus { outline: none; border-color: var(--accent); }
.modal-actions { display: flex; gap: 8px; justify-content: flex-end; margin-top: 8px; }

/* ─── LIGHTBOX ─── */
.lightbox {
  position: fixed; inset: 0;
  background: rgba(0,0,0,.95);
  z-index: 600;
  display: none;
  align-items: center; justify-content: center;
}
.lightbox.open { display: flex; }
.lightbox img, .lightbox video {
  max-width: 90vw; max-height: 85vh;
  border-radius: 6px; object-fit: contain;
}
.lightbox-close {
  position: absolute; top: 18px; right: 22px;
  background: none; border: none; color: var(--text-dim);
  font-size: 26px; cursor: pointer;
}
.lightbox-close:hover { color: var(--text); }

.empty-state {
  text-align: center; padding: 50px 20px; color: var(--text-muted);
}
.empty-state .icon { font-size: 30px; margin-bottom: 10px; }
.empty-state p { font-size: 12px; font-family: 'IBM Plex Mono', monospace; }

@media (max-width: 768px) {
  .scanner-sidebar, .edit-panel { display: none; }
  .home-stats { grid-template-columns: 1fr 1fr; }
  .home-hero h1 { font-size: 56px; }
  .nav-tab span.nav-label { display: none; }
}
</style>
</head>
<body>

<!-- ══ HEADER ══ -->
<header>
  <div class="logo" onclick="navigate('home')">PunchScan <span>v3.0</span></div>
  <nav class="nav-tabs">
    <button class="nav-tab active" data-page="home" onclick="navigate('home')">
      <span class="nav-icon">⌂</span><span class="nav-label">Dashboard</span>
    </button>
    <button class="nav-tab" data-page="projects" onclick="navigate('projects')">
      <span class="nav-icon">▤</span><span class="nav-label">Projects</span>
    </button>
    <button class="nav-tab" data-page="scanner" onclick="navigate('scanner')">
      <span class="nav-icon">▣</span><span class="nav-label">QR Scanner</span>
    </button>
  </nav>
  <div class="header-right">
    <div class="stat-pill"><span class="dot dot-red"></span><span id="hdr-open">0 open</span></div>
    <div class="stat-pill"><span class="dot dot-green"></span><span id="hdr-done">0 done</span></div>
  </div>
</header>

<!-- ══════════════════════════════════════
     PAGE: HOME / DASHBOARD
══════════════════════════════════════ -->
<div id="page-home" class="page active">
  <div class="home-hero">
    <h1>PUNCHSCAN</h1>
    <p>Construction Punch List Management System</p>
  </div>

  <div class="home-cards">
    <div class="home-card" onclick="navigate('projects')">
      <span class="home-card-icon">▤</span>
      <h2>Projects</h2>
      <p>View and manage all construction projects. Filter by status, trade, or priority. Edit details and track progress in one place.</p>
      <div class="home-card-arrow">Open projects →</div>
    </div>
    <div class="home-card" onclick="navigate('scanner')">
      <span class="home-card-icon">▣</span>
      <h2>QR Scanner</h2>
      <p>Scan QR codes on site to instantly create or open punch list items. Attach photos, video, and field notes directly from the field.</p>
      <div class="home-card-arrow">Open scanner →</div>
    </div>
  </div>

  <div class="home-stats">
    <div class="home-stat">
      <div class="home-stat-num" id="stat-total">0</div>
      <div class="home-stat-label">Total Projects</div>
    </div>
    <div class="home-stat">
      <div class="home-stat-num" id="stat-open" style="color:var(--danger)">0</div>
      <div class="home-stat-label">Open</div>
    </div>
    <div class="home-stat">
      <div class="home-stat-num" id="stat-active" style="color:var(--warning)">0</div>
      <div class="home-stat-label">Active</div>
    </div>
    <div class="home-stat">
      <div class="home-stat-num" id="stat-complete" style="color:var(--success)">0</div>
      <div class="home-stat-label">Complete</div>
    </div>
  </div>
</div>

<!-- ══════════════════════════════════════
     PAGE: PROJECTS
══════════════════════════════════════ -->
<div id="page-projects" class="page">
  <div class="proj-layout">
    <div class="proj-main">
      <div class="proj-topbar">
        <h2>Projects</h2>
        <div class="proj-filters">
          <input type="text" id="proj-search" placeholder="Search…" style="width:180px" oninput="renderProjects()">
          <select id="proj-filter-status" onchange="renderProjects()" style="width:130px">
            <option value="">All statuses</option>
            <option value="open">Open</option>
            <option value="active">Active</option>
            <option value="complete">Complete</option>
            <option value="on-hold">On hold</option>
          </select>
          <select id="proj-filter-trade" onchange="renderProjects()" style="width:130px">
            <option value="">All trades</option>
            <option>Electrical</option><option>Plumbing</option><option>HVAC</option>
            <option>Framing</option><option>Drywall</option><option>General</option>
          </select>
          <button class="btn btn-primary" onclick="openNewProject()">+ New Project</button>
        </div>
      </div>

      <div class="proj-table-wrap">
        <table class="proj-table" id="proj-table">
          <thead>
            <tr>
              <th onclick="sortProjects('name')">Project ↕</th>
              <th onclick="sortProjects('status')">Status ↕</th>
              <th onclick="sortProjects('priority')">Priority ↕</th>
              <th onclick="sortProjects('trade')">Trade ↕</th>
              <th onclick="sortProjects('assigned')">Assigned ↕</th>
              <th onclick="sortProjects('due')">Due ↕</th>
              <th onclick="sortProjects('items')" style="text-align:right">Items ↕</th>
              <th></th>
            </tr>
          </thead>
          <tbody id="proj-tbody"></tbody>
        </table>
        <div id="proj-empty" style="display:none" class="empty-state">
          <div class="icon">📋</div>
          <p>No projects match your filters.</p>
        </div>
      </div>
      <div class="count-bar" id="proj-count-bar"></div>
    </div>

    <!-- Edit Panel -->
    <div class="edit-panel" id="edit-panel">
      <div class="edit-panel-inner">
        <div class="edit-panel-header">
          <h3 id="ep-title">Edit Project</h3>
          <button class="close-panel-btn" onclick="closeEditPanel()">✕</button>
        </div>

        <div class="field-group">
          <label>Project Name</label>
          <input type="text" id="ep-name" placeholder="Project name">
        </div>
        <div class="field-row">
          <div class="field-group">
            <label>Status</label>
            <select id="ep-status">
              <option value="open">Open</option>
              <option value="active">Active</option>
              <option value="complete">Complete</option>
              <option value="on-hold">On hold</option>
            </select>
          </div>
          <div class="field-group">
            <label>Priority</label>
            <select id="ep-priority">
              <option value="normal">Normal</option>
              <option value="high">High</option>
              <option value="critical">Critical</option>
              <option value="low">Low</option>
            </select>
          </div>
        </div>
        <div class="field-row">
          <div class="field-group">
            <label>Trade</label>
            <select id="ep-trade">
              <option value="">— None —</option>
              <option>Electrical</option><option>Plumbing</option><option>HVAC</option>
              <option>Framing</option><option>Drywall</option><option>General</option>
            </select>
          </div>
          <div class="field-group">
            <label>Punch Items</label>
            <input type="number" id="ep-items" min="0" placeholder="0">
          </div>
        </div>
        <div class="field-group">
          <label>Assigned To</label>
          <input type="text" id="ep-assigned" placeholder="Contractor / crew">
        </div>
        <div class="field-group">
          <label>Location / Zone</label>
          <input type="text" id="ep-location" placeholder="Building / floor / zone">
        </div>
        <div class="field-row">
          <div class="field-group">
            <label>Due Date</label>
            <input type="date" id="ep-due">
          </div>
          <div class="field-group">
            <label>Cost Estimate ($)</label>
            <input type="number" id="ep-cost" placeholder="0.00">
          </div>
        </div>
        <div class="field-group">
          <label>Notes</label>
          <textarea id="ep-notes" rows="4" style="width:100%;resize:vertical" placeholder="Project notes…"></textarea>
        </div>
      </div>
      <div class="edit-panel-footer">
        <button class="btn btn-danger" id="ep-delete-btn" onclick="deleteProject()">🗑 Delete</button>
        <div style="display:flex;gap:8px">
          <button class="btn btn-ghost" onclick="closeEditPanel()">Cancel</button>
          <button class="btn btn-primary" onclick="saveProject()">Save</button>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ══════════════════════════════════════
     PAGE: QR SCANNER
══════════════════════════════════════ -->
<div id="page-scanner" class="page">
  <div class="scanner-layout">

    <!-- Punch Items Sidebar -->
    <aside class="scanner-sidebar">
      <div class="scanner-sidebar-header">
        <h3>Punch Items</h3>
        <span style="background:var(--accent);color:var(--bg);font-family:'IBM Plex Mono',monospace;font-size:10px;font-weight:600;border-radius:3px;padding:2px 7px" id="sidebar-count">0</span>
      </div>
      <div class="filter-tabs">
        <button class="filter-tab active" data-filter="all" onclick="setFilter(this,'all')">All</button>
        <button class="filter-tab" data-filter="open" onclick="setFilter(this,'open')">Open</button>
        <button class="filter-tab" data-filter="in-progress" onclick="setFilter(this,'in-progress')">Active</button>
        <button class="filter-tab" data-filter="complete" onclick="setFilter(this,'complete')">Done</button>
      </div>
      <div class="items-list" id="items-list"></div>
    </aside>

    <!-- Scanner + Detail -->
    <div class="scanner-main">

      <!-- Scanner view -->
      <div class="scanner-view" id="scanner-view">
        <div class="scanner-label">QR SCANNER</div>
        <div class="scanner-box">
          <video id="scanner-video" autoplay muted playsinline></video>
          <canvas class="scanner-canvas" id="scanner-canvas"></canvas>
          <div class="scanner-overlay">
            <div class="scanner-corner tl"></div>
            <div class="scanner-corner tr"></div>
            <div class="scanner-corner bl"></div>
            <div class="scanner-corner br"></div>
            <div class="scanner-line"></div>
            <div class="scanner-status" id="scanner-status">READY TO SCAN</div>
          </div>
        </div>
        <div class="scanner-sublabel">Point camera at a punch list QR code to create or open an item</div>
        <div style="display:flex;gap:10px;flex-wrap:wrap;justify-content:center">
          <button class="btn btn-scan" id="start-scan-btn" onclick="startScanner()">⬤ START CAMERA</button>
          <button class="manual-btn" onclick="openManualModal()">+ Manual Entry</button>
        </div>
      </div>

      <!-- Detail view -->
      <div class="detail-view" id="detail-view">
        <div class="detail-topbar">
          <div>
            <div class="detail-qr" id="detail-qr-id">—</div>
            <div style="font-size:11px;color:var(--text-muted);font-family:'IBM Plex Mono',monospace" id="detail-timestamp">—</div>
          </div>
          <div class="detail-topbar-actions">
            <button class="btn btn-ghost" onclick="backToScan()">← Back</button>
            <button class="btn btn-success" onclick="saveCurrentItem()">✓ Save Item</button>
          </div>
        </div>

        <div class="detail-body">
          <div class="detail-title-row">
            <input class="detail-title-input" id="item-title" type="text" placeholder="Describe the punch list item…">
            <select class="status-select" id="item-status" onchange="statusAutoLog()">
              <option value="open">Open</option>
              <option value="in-progress">In Progress</option>
              <option value="complete">Complete</option>
            </select>
          </div>

          <div class="section-label">Item Details</div>
          <div class="meta-grid">
            <div class="meta-field"><label>Location / Zone</label><input type="text" id="meta-location" placeholder="e.g. Level 3 — Room 312"></div>
            <div class="meta-field"><label>Assigned To</label><input type="text" id="meta-assigned" placeholder="Contractor / crew"></div>
            <div class="meta-field">
              <label>Trade</label>
              <select id="meta-trade">
                <option value="">— Select trade —</option>
                <option>Electrical</option><option>Plumbing</option><option>HVAC</option>
                <option>Framing</option><option>Drywall</option><option>Painting</option>
                <option>Flooring</option><option>Roofing</option><option>General</option>
              </select>
            </div>
            <div class="meta-field">
              <label>Priority</label>
              <select id="meta-priority">
                <option value="normal">Normal</option>
                <option value="high">High</option>
                <option value="critical">Critical</option>
                <option value="low">Low</option>
              </select>
            </div>
            <div class="meta-field"><label>Due Date</label><input type="date" id="meta-due"></div>
            <div class="meta-field"><label>Cost Estimate ($)</label><input type="number" id="meta-cost" placeholder="0.00"></div>
          </div>

          <div class="section-label">Field Notes</div>
          <textarea class="notes-area" id="item-notes" placeholder="Enter detailed notes, observations, corrective actions…"></textarea>

          <div class="section-label">Photos & Video</div>
          <div class="media-upload-row">
            <label class="upload-btn" for="photo-input">
              <span class="icon">📷</span><span>Photo</span>
              <input type="file" id="photo-input" accept="image/*" capture="environment" multiple>
            </label>
            <label class="upload-btn" for="video-input">
              <span class="icon">🎥</span><span>Video</span>
              <input type="file" id="video-input" accept="video/*" capture="environment">
            </label>
            <label class="upload-btn" for="file-input">
              <span class="icon">📎</span><span>File</span>
              <input type="file" id="file-input" accept="image/*,video/*,.pdf" multiple>
            </label>
          </div>
          <div class="media-grid" id="media-grid"></div>

          <div class="section-label" style="margin-top:24px">Activity Log</div>
          <div id="activity-log" style="margin-bottom:24px"></div>

          <div style="display:flex;justify-content:flex-end">
            <button class="btn btn-danger" onclick="deleteCurrentItem()">🗑 Delete Item</button>
          </div>
        </div>
      </div>

    </div>
  </div>
</div>

<!-- Manual Entry Modal -->
<div class="modal-backdrop" id="manual-modal">
  <div class="modal">
    <h3>Manual Entry</h3>
    <p class="modal-sub">Enter a QR code ID or leave blank to auto-generate.</p>
    <input class="modal-input" id="manual-qr-input" type="text" placeholder="QR code / item ID (e.g. SITE-A-042)">
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeManualModal()">Cancel</button>
      <button class="btn btn-primary" onclick="confirmManualEntry()">Create Item</button>
    </div>
  </div>
</div>

<!-- Lightbox -->
<div class="lightbox" id="lightbox" onclick="if(event.target===this)this.classList.remove('open')">
  <button class="lightbox-close" onclick="document.getElementById('lightbox').classList.remove('open')">✕</button>
  <div id="lightbox-content"></div>
</div>

<!-- Toast -->
<div class="toast" id="toast"></div>

<script>
// ═══════════════════════════════════════════════════
//  SHARED STATE & UTILS
// ═══════════════════════════════════════════════════
function uid() { return 'ITEM-' + Date.now().toString(36).toUpperCase() + '-' + Math.random().toString(36).slice(2,5).toUpperCase(); }
function now() { return new Date().toLocaleString(); }
function fmtDate(d) { if(!d) return '—'; const[y,m,day]=d.split('-'); return `${m}/${day}/${y}`; }

function showToast(msg, err=false) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.className = 'toast' + (err?' error':'');
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 3200);
}

// ═══════════════════════════════════════════════════
//  NAVIGATION
// ═══════════════════════════════════════════════════
function navigate(page) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-tab').forEach(t => t.classList.remove('active'));
  document.getElementById('page-' + page).classList.add('active');
  document.querySelector(`.nav-tab[data-page="${page}"]`).classList.add('active');

  if (page !== 'scanner') stopScanner();
  if (page === 'home') updateHomeDash();
  if (page === 'projects') renderProjects();
  if (page === 'scanner') renderList();
}

// ═══════════════════════════════════════════════════
//  PROJECTS DATA
// ═══════════════════════════════════════════════════
let projects = JSON.parse(localStorage.getItem('ps_projects') || 'null') || [
  {id:1, name:'Tower A — Level 3 Fit-out',    status:'active',   priority:'high',     trade:'Electrical', assigned:'Martinez Electric',  location:'Tower A',    due:'2026-04-15', items:14, cost:'', notes:''},
  {id:2, name:'Lobby Plumbing Rough-in',        status:'open',    priority:'critical', trade:'Plumbing',   assigned:'Blue River Plumbing', location:'Main Lobby', due:'2026-03-30', items:8,  cost:'', notes:''},
  {id:3, name:'HVAC Ductwork — Floors 4-6',     status:'active',  priority:'normal',   trade:'HVAC',       assigned:'AirFlow Co.',        location:'Floors 4–6', due:'2026-05-01', items:5,  cost:'', notes:''},
  {id:4, name:'Parking Garage Framing',          status:'complete',priority:'low',      trade:'Framing',    assigned:'Steele Frames Ltd.', location:'Garage B',   due:'2026-03-10', items:22, cost:'', notes:''},
  {id:5, name:'Drywall — East Wing',             status:'on-hold', priority:'normal',   trade:'Drywall',    assigned:'Smooth Finish Inc.', location:'East Wing',  due:'2026-06-20', items:3,  cost:'', notes:'Awaiting structural sign-off.'},
  {id:6, name:'Roof Membrane Repair',            status:'open',    priority:'high',     trade:'General',    assigned:'TBD',                location:'Roof Level', due:'2026-04-05', items:2,  cost:'', notes:''},
];
let projNextId = Math.max(...projects.map(p=>p.id)) + 1;
let projSortCol = null, projSortDir = 1;
let editingProjId = null;

function persistProjects() { localStorage.setItem('ps_projects', JSON.stringify(projects)); }

function openNewProject() {
  editingProjId = null;
  document.getElementById('ep-title').textContent = 'New Project';
  document.getElementById('ep-delete-btn').style.display = 'none';
  ['ep-name','ep-assigned','ep-location','ep-notes','ep-cost'].forEach(id => document.getElementById(id).value = '');
  document.getElementById('ep-status').value = 'open';
  document.getElementById('ep-priority').value = 'normal';
  document.getElementById('ep-trade').value = '';
  document.getElementById('ep-items').value = 0;
  document.getElementById('ep-due').value = '';
  document.getElementById('edit-panel').classList.add('open');
}

function openEditProject(id) {
  editingProjId = id;
  const p = projects.find(x => x.id === id);
  document.getElementById('ep-title').textContent = 'Edit Project';
  document.getElementById('ep-delete-btn').style.display = '';
  document.getElementById('ep-name').value = p.name;
  document.getElementById('ep-status').value = p.status;
  document.getElementById('ep-priority').value = p.priority;
  document.getElementById('ep-trade').value = p.trade || '';
  document.getElementById('ep-items').value = p.items;
  document.getElementById('ep-assigned').value = p.assigned || '';
  document.getElementById('ep-location').value = p.location || '';
  document.getElementById('ep-due').value = p.due || '';
  document.getElementById('ep-cost').value = p.cost || '';
  document.getElementById('ep-notes').value = p.notes || '';
  document.getElementById('edit-panel').classList.add('open');
}

function closeEditPanel() {
  document.getElementById('edit-panel').classList.remove('open');
}

function saveProject() {
  const name = document.getElementById('ep-name').value.trim();
  if (!name) { document.getElementById('ep-name').focus(); return; }
  const data = {
    name, status: document.getElementById('ep-status').value,
    priority: document.getElementById('ep-priority').value,
    trade: document.getElementById('ep-trade').value,
    items: parseInt(document.getElementById('ep-items').value) || 0,
    assigned: document.getElementById('ep-assigned').value.trim(),
    location: document.getElementById('ep-location').value.trim(),
    due: document.getElementById('ep-due').value,
    cost: document.getElementById('ep-cost').value,
    notes: document.getElementById('ep-notes').value.trim()
  };
  if (editingProjId) {
    const idx = projects.findIndex(p => p.id === editingProjId);
    projects[idx] = { ...projects[idx], ...data };
    showToast('✓ Project updated');
  } else {
    projects.unshift({ id: projNextId++, ...data });
    showToast('✓ Project created');
  }
  persistProjects();
  closeEditPanel();
  renderProjects();
  updateHomeDash();
  updateHeaderStats();
}

function deleteProject() {
  if (!confirm('Delete this project?')) return;
  projects = projects.filter(p => p.id !== editingProjId);
  persistProjects();
  closeEditPanel();
  renderProjects();
  updateHomeDash();
  updateHeaderStats();
  showToast('Project deleted');
}

function sortProjects(col) {
  if (projSortCol === col) projSortDir *= -1;
  else { projSortCol = col; projSortDir = 1; }
  renderProjects();
}

function renderProjects() {
  const q  = document.getElementById('proj-search').value.toLowerCase();
  const fs = document.getElementById('proj-filter-status').value;
  const ft = document.getElementById('proj-filter-trade').value;

  let list = projects.filter(p => {
    if (q && !p.name.toLowerCase().includes(q) && !(p.assigned||'').toLowerCase().includes(q) && !(p.location||'').toLowerCase().includes(q)) return false;
    if (fs && p.status !== fs) return false;
    if (ft && p.trade !== ft) return false;
    return true;
  });

  if (projSortCol) {
    list.sort((a,b) => {
      let av = a[projSortCol] ?? '', bv = b[projSortCol] ?? '';
      if (projSortCol === 'items') return (av - bv) * projSortDir;
      return String(av).localeCompare(String(bv)) * projSortDir;
    });
  }

  const tbody = document.getElementById('proj-tbody');
  const empty = document.getElementById('proj-empty');

  if (!list.length) {
    tbody.innerHTML = '';
    empty.style.display = 'block';
  } else {
    empty.style.display = 'none';
    tbody.innerHTML = list.map(p => `
      <tr onclick="openEditProject(${p.id})">
        <td>
          <div class="proj-name-cell">
            <span class="name">${p.name}</span>
            ${p.location ? `<span class="loc">${p.location}</span>` : ''}
          </div>
        </td>
        <td><span class="badge badge-${p.status}">${p.status==='on-hold'?'On hold':p.status.charAt(0).toUpperCase()+p.status.slice(1)}</span></td>
        <td><span class="badge badge-${p.priority}">${p.priority.charAt(0).toUpperCase()+p.priority.slice(1)}</span></td>
        <td style="font-size:12px;color:var(--text-dim)">${p.trade||'—'}</td>
        <td style="font-size:12px">${p.assigned||'—'}</td>
        <td style="font-size:12px;color:var(--text-dim)">${fmtDate(p.due)}</td>
        <td style="text-align:right;font-weight:500">${p.items}</td>
        <td><button class="btn btn-ghost" style="font-size:10px;padding:5px 12px" onclick="event.stopPropagation();openEditProject(${p.id})">Edit</button></td>
      </tr>
    `).join('');
  }

  document.getElementById('proj-count-bar').textContent = `${list.length} of ${projects.length} project${projects.length!==1?'s':''}`;
}

// ═══════════════════════════════════════════════════
//  PUNCH ITEMS DATA
// ═══════════════════════════════════════════════════
let items = JSON.parse(localStorage.getItem('punchItems') || '[]');
let currentItemId = null;
let currentFilter = 'all';
let scanning = false;
let stream = null;

function persistItems() { localStorage.setItem('punchItems', JSON.stringify(items)); }
function getItem(id) { return items.find(i => i.id === id); }

function createItem(qrCode) {
  const item = {
    id: qrCode || uid(),
    title: '', status: 'open', location: '', assigned: '', trade: '',
    priority: 'normal', due: '', cost: '',
    notes: '', media: [],
    log: [{ text: 'Item created via QR scan', time: now() }],
    created: now()
  };
  items.unshift(item);
  persistItems();
  return item;
}

function openItem(id) {
  const item = getItem(id);
  if (!item) return;
  currentItemId = id;

  document.getElementById('detail-qr-id').textContent = id;
  document.getElementById('detail-timestamp').textContent = 'Created: ' + item.created;
  document.getElementById('item-title').value = item.title;
  document.getElementById('item-status').value = item.status;
  document.getElementById('meta-location').value = item.location;
  document.getElementById('meta-assigned').value = item.assigned;
  document.getElementById('meta-trade').value = item.trade;
  document.getElementById('meta-priority').value = item.priority;
  document.getElementById('meta-due').value = item.due;
  document.getElementById('meta-cost').value = item.cost;
  document.getElementById('item-notes').value = item.notes;

  renderMedia(item);
  renderLog(item);

  document.getElementById('scanner-view').classList.add('hidden');
  document.getElementById('detail-view').classList.add('visible');
  stopScanner();
  renderList();
}

function saveCurrentItem() {
  const item = getItem(currentItemId);
  if (!item) return;
  item.title    = document.getElementById('item-title').value;
  item.status   = document.getElementById('item-status').value;
  item.location = document.getElementById('meta-location').value;
  item.assigned = document.getElementById('meta-assigned').value;
  item.trade    = document.getElementById('meta-trade').value;
  item.priority = document.getElementById('meta-priority').value;
  item.due      = document.getElementById('meta-due').value;
  item.cost     = document.getElementById('meta-cost').value;
  item.notes    = document.getElementById('item-notes').value;
  item.log.push({ text: 'Item saved', time: now() });
  renderLog(item);
  persistItems();
  renderList();
  updateHeaderStats();
  showToast('✓ Punch item saved');
}

function deleteCurrentItem() {
  if (!confirm('Delete this punch item? This cannot be undone.')) return;
  items = items.filter(i => i.id !== currentItemId);
  persistItems();
  backToScan();
  showToast('Item deleted');
}

function backToScan() {
  document.getElementById('scanner-view').classList.remove('hidden');
  document.getElementById('detail-view').classList.remove('visible');
  currentItemId = null;
  renderList();
}

function statusAutoLog() {
  const item = getItem(currentItemId);
  const val = document.getElementById('item-status').value;
  if (item) { item.log.push({ text: `Status changed to "${val}"`, time: now() }); renderLog(item); persistItems(); }
}

// Media
function renderMedia(item) {
  const grid = document.getElementById('media-grid');
  grid.innerHTML = '';
  item.media.forEach((m, i) => {
    const div = document.createElement('div');
    div.className = 'media-thumb';
    div.innerHTML = m.type === 'video'
      ? `<video src="${m.src}" muted></video><div class="thumb-overlay">▶</div><div class="media-type-badge">VIDEO</div>`
      : `<img src="${m.src}" loading="lazy"><div class="thumb-overlay">🔍</div><div class="media-type-badge">PHOTO</div>`;
    const del = document.createElement('button');
    del.className = 'media-delete';
    del.textContent = '✕';
    del.onclick = (e) => { e.stopPropagation(); item.media.splice(i,1); item.log.push({text:'Media removed',time:now()}); renderMedia(item); renderLog(item); persistItems(); };
    div.appendChild(del);
    div.onclick = () => openLightbox(m);
    grid.appendChild(div);
  });
}

function addMedia(item, files) {
  const promises = Array.from(files).map(f => new Promise(res => {
    const reader = new FileReader();
    reader.onload = e => res({ src: e.target.result, type: f.type.startsWith('video') ? 'video' : 'photo', name: f.name });
    reader.readAsDataURL(f);
  }));
  Promise.all(promises).then(results => {
    item.media.push(...results);
    item.log.push({ text: `Added ${results.length} media file(s)`, time: now() });
    renderMedia(item);
    renderLog(item);
    persistItems();
    showToast('📎 Media attached');
  });
}

function openLightbox(m) {
  document.getElementById('lightbox-content').innerHTML = m.type === 'video'
    ? `<video src="${m.src}" controls autoplay style="max-width:90vw;max-height:85vh;border-radius:6px"></video>`
    : `<img src="${m.src}" style="max-width:90vw;max-height:85vh;border-radius:6px">`;
  document.getElementById('lightbox').classList.add('open');
}

function renderLog(item) {
  document.getElementById('activity-log').innerHTML = [...item.log].reverse().map(e =>
    `<div class="log-entry"><div class="log-dot"></div><div class="log-text">${e.text}</div><div class="log-time">${e.time}</div></div>`
  ).join('');
}

function setFilter(btn, filter) {
  document.querySelectorAll('.filter-tab').forEach(t => t.classList.remove('active'));
  btn.classList.add('active');
  currentFilter = filter;
  renderList();
}

function renderList() {
  const list = document.getElementById('items-list');
  let filtered = currentFilter === 'all' ? items : items.filter(i => i.status === currentFilter);
  document.getElementById('sidebar-count').textContent = filtered.length;
  if (!filtered.length) {
    list.innerHTML = `<div class="empty-state"><div class="icon">📋</div><p>No items yet.<br>Scan a QR code to begin.</p></div>`;
    return;
  }
  list.innerHTML = filtered.map(item => `
    <div class="punch-item ${currentItemId === item.id ? 'active' : ''}" onclick="openItem('${item.id}')">
      <div class="item-qr-id">${item.id}</div>
      <div class="item-title">${item.title || '— Untitled item —'}</div>
      <div class="item-meta">
        <span class="status-badge status-${item.status}">${item.status.replace('-',' ')}</span>
        ${item.trade ? `<span style="font-size:10px;color:var(--text-muted)">${item.trade}</span>` : ''}
        ${item.media.length ? `<span style="font-size:10px;color:var(--text-muted)">📎 ${item.media.length}</span>` : ''}
      </div>
    </div>
  `).join('');
}

// QR Scanner
async function startScanner() {
  const video  = document.getElementById('scanner-video');
  const status = document.getElementById('scanner-status');
  const btn    = document.getElementById('start-scan-btn');

  if (scanning) { stopScanner(); return; }

  try {
    stream = await navigator.mediaDevices.getUserMedia({ video: { facingMode: 'environment' }, audio: false });
    video.srcObject = stream;
    scanning = true;
    btn.textContent = '⬛ STOP CAMERA';
    status.textContent = 'SCANNING…';
    scanFrame();
  } catch(err) {
    showToast('Camera access denied or unavailable', true);
    status.textContent = 'CAMERA ERROR';
  }
}

function stopScanner() {
  if (stream) { stream.getTracks().forEach(t => t.stop()); stream = null; }
  scanning = false;
  const btn = document.getElementById('start-scan-btn');
  if (btn) btn.textContent = '⬤ START CAMERA';
  const status = document.getElementById('scanner-status');
  if (status) status.textContent = 'READY TO SCAN';
}

function scanFrame() {
  if (!scanning) return;
  const video  = document.getElementById('scanner-video');
  const canvas = document.getElementById('scanner-canvas');
  if (video.readyState === video.HAVE_ENOUGH_DATA) {
    canvas.width = video.videoWidth; canvas.height = video.videoHeight;
    const ctx = canvas.getContext('2d');
    ctx.drawImage(video, 0, 0);
    const imageData = ctx.getImageData(0, 0, canvas.width, canvas.height);
    const code = jsQR(imageData.data, imageData.width, imageData.height, { inversionAttempts: 'dontInvert' });
    if (code) { handleQRCode(code.data); return; }
  }
  requestAnimationFrame(scanFrame);
}

function handleQRCode(data) {
  stopScanner();
  document.getElementById('scanner-status').textContent = '✓ CODE FOUND';
  showToast('QR Scanned: ' + data);
  let item = getItem(data);
  if (!item) item = createItem(data);
  setTimeout(() => openItem(item.id), 400);
}

function openManualModal() {
  document.getElementById('manual-modal').classList.add('open');
  document.getElementById('manual-qr-input').value = '';
  setTimeout(() => document.getElementById('manual-qr-input').focus(), 100);
}
function closeManualModal() { document.getElementById('manual-modal').classList.remove('open'); }
function confirmManualEntry() {
  const val = document.getElementById('manual-qr-input').value.trim() || uid();
  closeManualModal();
  let item = getItem(val);
  if (!item) item = createItem(val);
  openItem(item.id);
}

// File inputs
['photo-input','video-input','file-input'].forEach(id => {
  document.getElementById(id).onchange = function() {
    const item = getItem(currentItemId);
    if (item && this.files.length) addMedia(item, this.files);
    this.value = '';
  };
});

// ═══════════════════════════════════════════════════
//  HEADER STATS & HOME DASHBOARD
// ═══════════════════════════════════════════════════
function updateHeaderStats() {
  document.getElementById('hdr-open').textContent = projects.filter(p=>p.status==='open').length + ' open';
  document.getElementById('hdr-done').textContent = projects.filter(p=>p.status==='complete').length + ' done';
}

function updateHomeDash() {
  document.getElementById('stat-total').textContent   = projects.length;
  document.getElementById('stat-open').textContent    = projects.filter(p=>p.status==='open').length;
  document.getElementById('stat-active').textContent  = projects.filter(p=>p.status==='active').length;
  document.getElementById('stat-complete').textContent= projects.filter(p=>p.status==='complete').length;
}

// ═══════════════════════════════════════════════════
//  INIT
// ═══════════════════════════════════════════════════
updateHeaderStats();
updateHomeDash();
renderProjects();
renderList();
</script>
</body>
</html>
