<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Programa de Tutoria — IMECC</title>

<style>
  :root{
    /* Paleta IMECC */
    --ink-900:#0B0B0D; --ink-700:#2B2B2F; --ink-600:#3F3F46;
    --paper:#FFFFFF; --paper-alt:#F7F7FB; --line:#E6E6EA;
    --brand:#E30613; --brand-600:#B10510; --brand-200:#F7A3A8;
    --glow:#c5d1ff;
    --radius:16px;
    --elev-1:0 6px 18px rgba(0,0,0,.08);
    --elev-2:0 10px 24px rgba(0,0,0,.14);
  }

  /* Base */
  *,*::before,*::after{ box-sizing:border-box; }
  body{
    margin:0;
    font: 16px/1.55 Inter, system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
    color:var(--ink-900);
    background:linear-gradient(#fff, #fafbff);
  }
  img{ max-width:100%; display:block; }
  .container{ width:min(1100px, 92vw); margin:0 auto; }

  /* Hero (sem navbar) */
  .hero{
    padding:28px 0 6px;
  }
  .hero .card{
    position:relative; overflow:hidden;
    display:grid; gap:8px; padding:24px;
    border-radius:var(--radius);
    background:linear-gradient(180deg,var(--paper),var(--paper-alt));
    border:1px solid var(--line);
    box-shadow:var(--elev-1);
  }
  .hero .card::before{
    content:""; position:absolute; inset:-40% -20% auto auto;
    background:radial-gradient(50% 40% at 80% 0%, color-mix(in oklab, var(--glow) 55%, transparent), transparent 60%);
  }
  .kicker{ font-weight:900; color:var(--brand-600); letter-spacing:.6px; text-transform:uppercase; font-size:12px;}
  .title{ font-weight:900; font-size:clamp(22px, 2.4vw + 14px, 36px); letter-spacing:.2px;}
  .subtitle{ color:var(--ink-600); max-width:75ch; }

  /* Seções */
  section{ padding:26px 0; }
  .section-title{
    display:flex; align-items:center; gap:10px; margin-bottom:14px;
    font-weight:900; letter-spacing:.2px;
  }
  .section-title .bar{
    width:6px; height:22px; border-radius:4px;
    background:linear-gradient(180deg,var(--brand), var(--brand-600));
    box-shadow:0 0 0 3px color-mix(in oklab, var(--brand) 18%, transparent);
  }
  .card-text{
    background:var(--paper); border:1px solid var(--line); border-radius:14px; padding:18px;
    box-shadow:var(--elev-1); color:var(--ink-700);
  }
  .list{
    display:grid; gap:10px;
    background:var(--paper);
    border:1px solid var(--line); border-radius:14px; padding:18px; box-shadow:var(--elev-1);
  }
  .list ul{ margin:0; padding-left:20px; }
  .list li{ margin:6px 0; }

  /* Docentes em destaque */
  .featured-row{
    display:flex; gap:18px; justify-content:center; flex-wrap:wrap;
  }
  .person.featured{
    width:min(320px, 90vw);
    background:linear-gradient(180deg,var(--paper), var(--paper-alt));
    border:1px solid var(--line); border-radius:var(--radius);
    box-shadow:var(--elev-2);
    overflow:hidden; isolation:isolate;
  }
  .person .accent{ height:6px; background:linear-gradient(90deg, var(--brand), var(--brand-600)); }
  .person .content{ padding:16px; display:grid; gap:6px; }
  .avatar{ width:100%; aspect-ratio: 16 / 10; object-fit:cover; background:#eee; }
  .name{ font-weight:900; font-size:18px; }
  .role{ font-weight:700; color:var(--brand-600); }
  .meta{ color:var(--ink-600); font-size:14px; }

  /* Equipe (tutores) */
  .team-grid{
    display:grid; gap:16px;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  }
  .person.card{
    background:var(--paper); border:1px solid var(--line); border-radius:14px; overflow:hidden;
    transition: transform .18s ease, box-shadow .18s ease, border-color .18s ease;
    box-shadow:var(--elev-1);
  }
  .person.card:hover{
    transform: translateY(-4px);
    border-color: color-mix(in oklab, var(--line) 60%, var(--brand) 40%);
    box-shadow:var(--elev-2);
  }

  /* Disciplinas */
  .badges{ display:flex; gap:8px; flex-wrap:wrap; }
  .badge{
    background:color-mix(in oklab, var(--brand-200) 22%, #fff 78%);
    color:var(--ink-700);
    border:1px solid color-mix(in oklab, var(--brand-200) 60%, var(--line));
    padding:6px 10px; border-radius:999px; font-weight:800; letter-spacing:.2px;
  }

  /* Rodapé */
  footer{
    margin:28px 0 16px; padding:16px 0; border-top:1px solid var(--line);
    color:var(--ink-600); font-size:14px; background:linear-gradient(180deg,var(--paper),var(--paper-alt));
  }

  @media (prefers-reduced-motion: reduce){
    .person.card:hover{ transform:none; }
  }
</style>
</head>
<body>

<main>
  <!-- HERO -->
  <div class="container hero">
    <div class="card">
      <div class="kicker">IMECC • Unicamp</div>
      <div class="title">Programa de Tutoria — Área de Matemática</div>
      <div class="subtitle">
        Apoio aos(as) ingressantes, materiais abertos, ações de permanência e integração
        com a escola básica. Encontros conduzidos por docentes e tutores(as).
      </div>
    </div>
  </div>

  <!-- SOBRE -->
  <section id="sobre">
    <div class="container">
      <div class="section-title"><span class="bar"></span><span>Sobre o Programa de Tutoria</span></div>
      <div class="card-text">
        O Programa de Tutoria visa apoiar a formação inicial de estudantes ingressantes, promover
        a permanência com qualidade e aproximar universidade e escola básica por meio de atividades
        didáticas, materiais abertos e ações articuladas de ensino, pesquisa e extensão.
      </div>
    </div>
  </section>

  <!-- OBJETIVOS -->
  <section>
    <div class="container">
      <div class="section-title"><span class="bar"></span><span>Objetivos</span></div>
      <div class="list">
        <ul>
          <li>Apoiar a formação inicial de ingressantes em cursos de graduação;</li>
          <li>Contribuir para uma permanência estudantil de qualidade e reduzir os índices de evasão;</li>
          <li>Estruturar material e atividades didáticas adequadas, abertas e gratuitas;</li>
          <li>Fortalecer a formação profissional de estudantes de licenciatura;</li>
          <li>Estreitar a colaboração entre a Universidade e docentes do Ensino Básico;</li>
          <li>Identificar e analisar problemas e necessidades relacionados à evasão universitária.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- RESULTADOS ESPERADOS -->
  <section>
    <div class="container">
      <div class="section-title"><span class="bar"></span><span>Resultados esperados do programa</span></div>
      <div class="list">
        <ul>
          <li>Diminuição dos índices de evasão;</li>
          <li>Melhoria no rendimento acadêmico e na formação profissional nos cursos de graduação;</li>
          <li>Criação/fortalecimento de linhas de estudo e pesquisa educacional a partir da implementação do programa;</li>
          <li>Aproximação entre universidade e escola como fonte de temas de pesquisa e ações de extensão.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- DOCENTES -->
  <section id="docentes">
    <div class="container">
      <div class="section-title"><span class="bar"></span><span>Coordenação (docentes responsáveis)</span></div>
      <div class="featured-row">
        <article class="person featured">
          <div class="accent"></div>
          <img class="avatar" src="https://lh3.googleusercontent.com/d/1VPk8oJ-0WVXcLPDGt4uW_tCxhCNx2GAE=w1000" alt="Prof. Pietro Speziali">
          <div class="content">
            <div class="name">Prof. Pietro Speziali</div>
            <div class="role">Coordenação do Programa de Tutoria</div>
            <div class="meta">Área de Matemática Pura — IMECC</div>
          </div>
        </article>

        <article class="person featured">
          <div class="accent"></div>
          <img class="avatar" src="https://lh3.googleusercontent.com/d/16VNjepY0y2QsjQb-thRAVR0nFs-4GRVW=w1000" alt="Prof. Ricardo Miranda Martins">
          <div class="content">
            <div class="name">Prof. Ricardo Miranda Martins</div>
            <div class="role">Coordenação do Programa de Tutoria</div>
            <div class="meta">Área de Matemática Pura — IMECC</div>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- EQUIPE (TUTORES) -->
  <section id="equipe">
    <div class="container">
      <div class="section-title"><span class="bar"></span><span>Equipe responsável — Tutores(as)</span></div>

      <div class="team-grid">
        <!-- Tutores atuais -->
        <article class="person card">
          <img class="avatar" src="https://i.pravatar.cc/600?img=32" alt="Bruno Yuji Kobaiashi Marques">
          <div class="content">
            <div class="name">Bruno Yuji Kobaiashi Marques</div>
            <div class="meta">Tutor 2025-2</div>
          </div>
        </article>

        <article class="person card">
          <img class="avatar" src="https://lh3.googleusercontent.com/d/1VWsZBcWQto9rvWMpPjSA7evLULy5DAkH=w1000" alt="Breno William Migliorini">
          <div class="content">
            <div class="name">Breno William Migliorini</div>
            <div class="meta">Tutor 2025-2</div>
          </div>
        </article>

        <!-- Tutores 2025-1 -->
        <article class="person card">
          <img class="avatar" src="https://i.pravatar.cc/600?img=28" alt="Laura Santos Afonso Ferreira">
          <div class="content">
            <div class="name">Laura Santos Afonso Ferreira</div>
            <div class="meta">Tutora 2025-1</div>
          </div>
        </article>

        <article class="person card">
          <img class="avatar" src="https://i.pravatar.cc/600?img=17" alt="Felipe Jardim Pinhati">
          <div class="content">
            <div class="name">Felipe Jardim Pinhati</div>
            <div class="meta">Tutor 2025-1</div>
          </div>
        </article>

        <article class="person card">
          <img class="avatar" src="https://i.pravatar.cc/600?img=41" alt="Felipe Pinto Murad">
          <div class="content">
            <div class="name">Felipe Pinto Murad</div>
            <div class="meta">Tutor 2025-1</div>
          </div>
        </article>

        <article class="person card">
          <img class="avatar" src="https://i.pravatar.cc/600?img=7" alt="Rodrigo Macedo Monti Silva">
          <div class="content">
            <div class="name">Rodrigo Macedo Monti Silva</div>
            <div class="meta">Tutor 2025-1</div>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- PÚBLICO-ALVO / DISCIPLINAS -->
  <section>
    <div class="container">
      <div class="section-title"><span class="bar"></span><span>Público-alvo e disciplinas cobertas</span></div>
      <div class="card-text" style="margin-bottom:10px">
        O público-alvo são estudantes de graduação da Unicamp no primeiro ano cursando:
      </div>
      <div class="badges">
        <div class="badge">MA141 — Geometria Analítica e Vetores</div>
        <div class="badge">MA111 — Cálculo 1</div>
        <div class="badge">MA105 — Matemática Elementar</div>
        <div class="badge">MS380 — Matemática Aplicada para Biologia</div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="container">© IMECC • Programa de Tutoria — Área de Matemática. Conteúdos e horários sujeitos a atualização.</div>
</footer>
</body>
</html>
