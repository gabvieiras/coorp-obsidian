---
{"dg-publish":true,"permalink":"/home/","tags":["home","workspace","sae","gardenEntry"],"dg-note-properties":{"tags":["home","workspace","sae","gardenEntry"],"aliases":["Home OS","SAE Executive Workspace","SAE Systemic Automation Engineering"],"created":"2026-08-30","modified":"2026-08-30"}}
---


<div class="sae-hero-wrapper">
  <canvas id="saeParticleCanvas" class="sae-canvas-bg"></canvas>
  <div class="sae-hero-content">
    <img src="sae-logo-white.png" alt="SAE Logo" />
    <div style="text-align: center; margin-bottom: 24px;">
      <h1 style="border-bottom: none; margin-bottom: 8px; font-size: 2.2rem; background: linear-gradient(135deg, #ffffff 0%, #a5b4fc 50%, #818cf8 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">SAE — Systemic Automation Engineering</h1>
      <p style="color: #94a3b8; font-size: 0.95rem; max-width: 680px; margin: 0 auto; line-height: 1.6;">
        Plataforma de Engenharia de Automação & Governança de Processos. Monitore frentes de trabalho, métricas de carga e integrações sistêmicas em tempo real.
      </p>
    </div>

    <!-- Live Animated Metric Dashboard -->
    <div class="sae-metrics-dashboard">
      <div class="sae-metric-box">
        <div class="sae-metric-val">104h</div>
        <div class="sae-metric-lbl">⏱️ Esforço Total</div>
      </div>
      <div class="sae-metric-box">
        <div class="sae-metric-val">10</div>
        <div class="sae-metric-lbl">📊 Data Boards</div>
      </div>
      <div class="sae-metric-box">
        <div class="sae-metric-val">35%</div>
        <div class="sae-metric-lbl">🎯 Progresso Q3</div>
      </div>
      <div class="sae-metric-box">
        <div class="sae-metric-val">&lt; 5s</div>
        <div class="sae-metric-lbl">🤖 SLA Bot WhatsApp</div>
      </div>
    </div>
  </div>
</div>

> [!NOTE] 🌐 **System Navigation**
> [[HOME\|🏠 Home]] • [[1. Projects/kreston/kreston.README\|🚗 SAE Overview]] • [[1. Projects/kreston/kreston-muriel\|🎨 Muriel Board]] • [[1. Projects/kreston/kreston-gabriel\|⚡ Gabriel Board]] • [[1. Projects/kreston/kreston-kanban\|📋 Monday Kanban]] • [[3. Resources/Zettelkasten/00_Zettelkasten_Hub\|🧠 Knowledge Engine]] • [[2. Areas/Work/kreston-gestao-operacional\|🏢 Gestão Operacional]]

---

## 📊 Explorer Interativo de Frentes de Trabalho

<div style="margin: 20px 0 10px 0;">
  <p style="color: #94a3b8; font-size: 0.88rem; text-align: center; margin-bottom: 14px;">Filtre e explore interativamente os pilares operacionais da SAE com efeito 3D ao passar o mouse:</p>
  
  <!-- Interactive Filter Tabs -->
  <div class="sae-tabs-nav">
    <button class="sae-tab-btn active" onclick="filterWorkstreams('all')">🌐 Todas as Frentes</button>
    <button class="sae-tab-btn" onclick="filterWorkstreams('muriel')">🎨 Muriel — Branding</button>
    <button class="sae-tab-btn" onclick="filterWorkstreams('gabriel')">⚡ Gabriel — Automação</button>
    <button class="sae-tab-btn" onclick="filterWorkstreams('kanban')">📋 Monday Kanban</button>
    <button class="sae-tab-btn" onclick="filterWorkstreams('ops')">🏢 Gestão Operacional</button>
    <button class="sae-tab-btn" onclick="filterWorkstreams('zk')">🧠 Knowledge Engine</button>
  </div>

  <!-- Interactive Grid Cards with 3D Tilt -->
  <div class="sae-workstream-grid">
    <!-- Card 1: Muriel -->
    <div class="sae-workcard muriel" data-category="muriel">
      <div>
        <div class="sae-workcard-header">
          <div class="sae-workcard-title">🎨 Muriel — Branding & Funil</div>
          <span class="sae-badge executing">Em Execução</span>
        </div>
        <div class="sae-workcard-desc">
          Posicionamento de marca, fotografia padronizada (12 ângulos), walkarounds em vídeo (60s), copywriting AIDA e tráfego pago Meta Ads.
        </div>
        <div class="sae-tags-container">
          <span class="sae-pill-tag">Instagram Grid</span>
          <span class="sae-pill-tag">Presets Fotos</span>
          <span class="sae-pill-tag">Copy AIDA</span>
          <span class="sae-pill-tag">Meta Ads</span>
        </div>
      </div>
      <div>
        <div class="sae-workcard-meta">
          <span>Esforço: ⏱️ 62 Horas</span>
          <span>7 Boards</span>
        </div>
        <div class="sae-progress-bar-container">
          <div class="sae-progress-fill" style="width: 35%; background: linear-gradient(90deg, #c084fc, #fb7185);"></div>
        </div>
        <a href="kreston-muriel" class="sae-btn-cta">Abrir Board Muriel →</a>
      </div>
    </div>

    <!-- Card 2: Gabriel -->
    <div class="sae-workcard gabriel" data-category="gabriel">
      <div>
        <div class="sae-workcard-header">
          <div class="sae-workcard-title">⚡ Gabriel — Automação & BI</div>
          <span class="sae-badge executing">Em Execução</span>
        </div>
        <div class="sae-workcard-desc">
          Engenharia de bots WhatsApp 24/7 (API 99Motors &lt; 5s), relatórios mensais de ROI no Looker Studio e agendamento sistêmico Cal.com.
        </div>
        <div class="sae-tags-container">
          <span class="sae-pill-tag">Bot WhatsApp</span>
          <span class="sae-pill-tag">API 99Motors</span>
          <span class="sae-pill-tag">Looker Studio</span>
          <span class="sae-pill-tag">Cal.com</span>
        </div>
      </div>
      <div>
        <div class="sae-workcard-meta">
          <span>Esforço: ⏱️ 42 Horas</span>
          <span>3 Boards</span>
        </div>
        <div class="sae-progress-bar-container">
          <div class="sae-progress-fill" style="width: 40%; background: linear-gradient(90deg, #60a5fa, #22d3ee);"></div>
        </div>
        <a href="kreston-gabriel" class="sae-btn-cta">Abrir Board Gabriel →</a>
      </div>
    </div>

    <!-- Card 3: Kanban -->
    <div class="sae-workcard kanban" data-category="kanban">
      <div>
        <div class="sae-workcard-header">
          <div class="sae-workcard-title">📋 Monday Kanban Live</div>
          <span class="sae-badge sync">🟢 Sincronizado</span>
        </div>
        <div class="sae-workcard-desc">
          Quadro interativo ao vivo em tempo real via Trello API. Gestão de fluxo contínuo (Backlog, ToDo, Doing, Done).
        </div>
        <div class="sae-tags-container">
          <span class="sae-pill-tag">Live Trello Sync</span>
          <span class="sae-pill-tag">Drag &amp; Drop</span>
          <span class="sae-pill-tag">WIP Limit 3</span>
        </div>
      </div>
      <div>
        <div class="sae-workcard-meta">
          <span>Modo: Tempo Real</span>
          <span>Live API</span>
        </div>
        <div class="sae-progress-bar-container">
          <div class="sae-progress-fill" style="width: 100%; background: linear-gradient(90deg, #34d399, #10b981);"></div>
        </div>
        <a href="kreston-kanban" class="sae-btn-cta">Abrir Kanban Live →</a>
      </div>
    </div>

    <!-- Card 4: Gestão Operacional -->
    <div class="sae-workcard ops" data-category="ops">
      <div>
        <div class="sae-workcard-header">
          <div class="sae-workcard-title">🏢 Gestão Operacional</div>
          <span class="sae-badge executing">Ativo</span>
        </div>
        <div class="sae-workcard-desc">
          Processos recorrentes diários e semanais, checkin de catálogo, rotina de atendimento e controle de KPIs operacionais.
        </div>
        <div class="sae-tags-container">
          <span class="sae-pill-tag">Rotinas Diárias</span>
          <span class="sae-pill-tag">KPI Tracker</span>
          <span class="sae-pill-tag">Catálogo</span>
        </div>
      </div>
      <div>
        <div class="sae-workcard-meta">
          <span>Frequência: Diária</span>
          <span>Operações</span>
        </div>
        <div class="sae-progress-bar-container">
          <div class="sae-progress-fill" style="width: 60%; background: linear-gradient(90deg, #fbbf24, #fb923c);"></div>
        </div>
        <a href="kreston-gestao-operacional" class="sae-btn-cta">Ver Operações →</a>
      </div>
    </div>

    <!-- Card 5: Knowledge Engine -->
    <div class="sae-workcard zk" data-category="zk">
      <div>
        <div class="sae-workcard-header">
          <div class="sae-workcard-title">🧠 Zettelkasten Knowledge</div>
          <span class="sae-badge sync">5 Camadas</span>
        </div>
        <div class="sae-workcard-desc">
          Base de conhecimento atômica da SAE (Fleeting → Literature → Permanent → Project → Structure). Conecta leituras a entregáveis.
        </div>
        <div class="sae-tags-container">
          <span class="sae-pill-tag">Literature Map</span>
          <span class="sae-pill-tag">Ontologia</span>
          <span class="sae-pill-tag">ARCO View</span>
          <span class="sae-pill-tag">Inspect Analytics</span>
        </div>
      </div>
      <div>
        <div class="sae-workcard-meta">
          <span>Notas: Atômicas</span>
          <span>Knowledge Engine</span>
        </div>
        <div class="sae-progress-bar-container">
          <div class="sae-progress-fill" style="width: 85%; background: linear-gradient(90deg, #818cf8, #c084fc);"></div>
        </div>
        <a href="00_Zettelkasten_Hub" class="sae-btn-cta">Abrir Knowledge Engine →</a>
      </div>
    </div>
  </div>
</div>

<script>
// 1. Interactive 3D Canvas Particle Background Engine
(function initParticleHero() {
  const canvas = document.getElementById('saeParticleCanvas');
  if (!canvas) return;
  const ctx = canvas.getContext('2d');

  function resize() {
    if (!canvas.parentElement) return;
    canvas.width = canvas.parentElement.clientWidth;
    canvas.height = canvas.parentElement.clientHeight;
  }
  resize();
  window.addEventListener('resize', resize);

  const particles = [];
  const numParticles = 40;
  let mouse = { x: null, y: null, radius: 130 };

  canvas.parentElement.addEventListener('mousemove', (e) => {
    const rect = canvas.getBoundingClientRect();
    mouse.x = e.clientX - rect.left;
    mouse.y = e.clientY - rect.top;
  });

  canvas.parentElement.addEventListener('mouseleave', () => {
    mouse.x = null;
    mouse.y = null;
  });

  for (let i = 0; i < numParticles; i++) {
    particles.push({
      x: Math.random() * (canvas.width || 800),
      y: Math.random() * (canvas.height || 300),
      vx: (Math.random() - 0.5) * 0.7,
      vy: (Math.random() - 0.5) * 0.7,
      radius: Math.random() * 2 + 1.2,
      color: Math.random() > 0.5 ? 'rgba(129, 140, 248, ' : 'rgba(96, 165, 250, '
    });
  }

  function animate() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);

    for (let i = 0; i < particles.length; i++) {
      let p = particles[i];
      p.x += p.vx;
      p.y += p.vy;

      if (p.x < 0 || p.x > canvas.width) p.vx *= -1;
      if (p.y < 0 || p.y > canvas.height) p.vy *= -1;

      // Mouse repulsion/glow interaction
      if (mouse.x !== null) {
        let dx = mouse.x - p.x;
        let dy = mouse.y - p.y;
        let dist = Math.sqrt(dx * dx + dy * dy);
        if (dist < mouse.radius && dist > 0) {
          p.x -= (dx / dist) * 1.5;
          p.y -= (dy / dist) * 1.5;
        }
      }

      ctx.beginPath();
      ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
      ctx.fillStyle = p.color + '0.6)';
      ctx.fill();

      // Connect near particles with laser lines
      for (let j = i + 1; j < particles.length; j++) {
        let p2 = particles[j];
        let dx = p.x - p2.x;
        let dy = p.y - p2.y;
        let dist = Math.sqrt(dx * dx + dy * dy);
        if (dist < 110) {
          ctx.beginPath();
          ctx.moveTo(p.x, p.y);
          ctx.lineTo(p2.x, p2.y);
          ctx.strokeStyle = 'rgba(129, 140, 248, ' + (0.22 * (1 - dist / 110)) + ')';
          ctx.lineWidth = 0.8;
          ctx.stroke();
        }
      }
    }
    requestAnimationFrame(animate);
  }
  animate();
})();

// 2. Interactive Workstream Filter Tabs
function filterWorkstreams(cat) {
  const cards = document.querySelectorAll('.sae-workcard');
  const btns = document.querySelectorAll('.sae-tab-btn');

  btns.forEach(btn => btn.classList.remove('active'));
  if (window.event && window.event.target) window.event.target.classList.add('active');

  cards.forEach(card => {
    if (cat === 'all' || card.getAttribute('data-category') === cat) {
      card.style.display = 'flex';
      card.style.opacity = '1';
    } else {
      card.style.display = 'none';
    }
  });
}

// 3. Interactive 3D Perspective Tilt on Hover
document.querySelectorAll('.sae-workcard').forEach(card => {
  card.addEventListener('mousemove', (e) => {
    const rect = card.getBoundingClientRect();
    const x = e.clientX - rect.left - rect.width / 2;
    const y = e.clientY - rect.top - rect.height / 2;
    const rotateX = (y / rect.height) * -12;
    const rotateY = (x / rect.width) * 12;
    card.style.transform = `perspective(1000px) rotateX(${rotateX}deg) rotateY(${rotateY}deg) translateY(-4px)`;
  });

  card.addEventListener('mouseleave', () => {
    card.style.transform = 'perspective(1000px) rotateX(0deg) rotateY(0deg) translateY(0)';
  });
});
</script>

---

## 📊 Tabela de Status Executivo — Visão Consolidada

| # | Frente de Trabalho | Responsável | Status | Grupos | Esforço Total | Quadro de Trabalho |
| :---: | :--- | :--- | :---: | :---: | :---: | :--- |
| 1 | **Branding, Mídia & Funil** | 🎨 Muriel | 🔵 Em Execução | 7 | `⏱️ 62h` | [[1. Projects/kreston/kreston-muriel\|Abrir Board →]] |
| 2 | **Automações, Bot & BI** | ⚡ Gabriel | 🔵 Em Execução | 3 | `⏱️ 42h` | [[1. Projects/kreston/kreston-gabriel\|Abrir Board →]] |
| 3 | **Kanban Trello Live** | 👥 Equipe | 🟢 Sincronizado | Live | `⏱️ Contínuo` | [[1. Projects/kreston/kreston-kanban\|Abrir Kanban →]] |
| 4 | **Gestão Operacional** | 🏢 Equipe | 🟢 Ativo | Ops | `⏱️ Diário` | [[2. Areas/Work/kreston-gestao-operacional\|Ver Ops →]] |

---

## 🧠 Knowledge Engine — Zettelkasten System

> [!WARNING] 🧠 **Base de Engenharia do Conhecimento**
> Sistema de 5 camadas atômicas (Fleeting → Literature → Permanent → Project → Structure). Conecta pesquisas de arquitetura de automação a insights aplicados nos clientes e projetos SAE.

| # | Módulo | Tipo | Função | Acesso |
| :---: | :--- | :---: | :--- | :--- |
| 1 | **Zettelkasten Hub** | 🧠 MOC | Central de conexões e índice geral | [[3. Resources/Zettelkasten/00_Zettelkasten_Hub\|Abrir →]] |
| 2 | **Literature Map** | 🗺️ Map | Pipeline de destilação: Fonte → Nota | [[3. Resources/Zettelkasten/Literature Map/Literature Map\|Abrir →]] |
| 3 | **Ontologia** | 🏗️ Rules | Regras formais das 5 camadas | [[3. Resources/Zettelkasten/Zettelkasten Ontology/Zettelkasten Ontology\|Abrir →]] |
| 4 | **ARCO View** | 🧭 Framework | Atlas • Reference • Calendar • Organizer | [[3. Resources/Zettelkasten/Views/ARCO View\|Abrir →]] |
| 5 | **Inspect View** | 📊 Analytics | Vault health, distribuição e métricas | [[3. Resources/Zettelkasten/Views/Inspect View\|Abrir →]] |

---

## 📚 Publicações & Cases de Engenharia SAE

> [!EXAMPLE] 🚀 **Artigo Express — Case SAE**
> **[[5. Express/blogs/Como Estruturar um Funil de Vendas Automatizado para Loja de Veiculos\|Funil de Vendas Automatizado para Loja de Veículos]]**
> 
> Case executivo de engenharia sistêmica combinando branding de marca (Muriel) + automação de mensagens e inteligência (Gabriel).

### 🧠 Notas Permanentes & Leituras

| Nota / Fonte | Tipo | Aplicação | Link |
| :--- | :---: | :--- | :--- |
| **How to Take Smart Notes** | 📖 Livro | Resumo de metodologia Zettelkasten | [[3. Resources/Zettelkasten/Literature/Livro - How to Take Smart Notes (Soenke Ahrens)\|Ver →]] |
| **Guia Automação 99Motors** | 🛠️ Tool | Lead scoring e atendimento de veículos | [[3. Resources/Zettelkasten/Literature/Guia - Automacao de Vendas e Lead Scoring para Veiculos\|Ver →]] |
| **Atomicidade de Notas** | Permanent | Arquitetura do Zettelkasten SAE | [[3. Resources/Zettelkasten/Permanent/Atomicidade de Notas no Zettelkasten\|Ver →]] |
| **Funil WhatsApp** | Permanent | Engenharia do Bot WhatsApp SAE | [[3. Resources/Zettelkasten/Permanent/Funil de Conversao Automatica via WhatsApp para Concessionarias\|Ver →]] |
| **Padronização Visual** | Permanent | Identidade e Confiança de Marca | [[3. Resources/Zettelkasten/Permanent/Padronizacao Visual como Fator de Confianca na Venda de Veiculos\|Ver →]] |

---
