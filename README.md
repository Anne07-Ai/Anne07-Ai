<svg width="860" height="1980" viewBox="0 0 860 1980" xmlns="http://www.w3.org/2000/svg">
<defs>
  <style>
    @keyframes fadeUp{0%{opacity:0;transform:translateY(16px)}100%{opacity:1;transform:translateY(0)}}
    @keyframes fadeIn{0%{opacity:0}100%{opacity:1}}
    @keyframes barGrow1{0%{width:0}100%{width:786px}}
    @keyframes barGrow2{0%{width:0}100%{width:786px}}
    @keyframes barGrow3{0%{width:0}100%{width:752px}}
    @keyframes barGrow4{0%{width:0}100%{width:718px}}
    @keyframes barGrow5{0%{width:0}100%{width:685px}}
    @keyframes pulse{0%,100%{r:36px}50%{r:40px}}
    @keyframes waveAnim{0%,100%{d:path("M0,30 C215,55 430,5 645,30 C752,42 806,20 860,28 L860,60 L0,60 Z")}50%{d:path("M0,38 C215,15 430,50 645,22 C752,10 806,40 860,18 L860,60 L0,60 Z")}}
    @keyframes badgeSlide{0%{opacity:0;transform:translateX(-12px)}100%{opacity:1;transform:translateX(0)}}
    .n{animation:fadeUp 0.7s ease 0.2s both}
    .s{animation:fadeUp 0.7s ease 0.45s both}
    .l{animation:fadeUp 0.6s ease 0.65s both}
    .b1{animation:badgeSlide 0.5s ease 0.85s both}
    .b2{animation:badgeSlide 0.5s ease 1.0s both}
    .b3{animation:badgeSlide 0.5s ease 1.15s both}
    .br1{animation:barGrow1 1.2s ease 0.3s both}
    .br2{animation:barGrow2 1.2s ease 0.5s both}
    .br3{animation:barGrow3 1.2s ease 0.7s both}
    .br4{animation:barGrow4 1.2s ease 0.9s both}
    .br5{animation:barGrow5 1.2s ease 1.1s both}
    .sec{animation:fadeIn 0.6s ease 0.2s both}
    .av{animation:pulse 3s ease-in-out infinite}
    .wv{animation:waveAnim 5s ease-in-out infinite}
    text{font-family:'Segoe UI',system-ui,sans-serif}
  </style>
  <linearGradient id="heroBg" x1="0" y1="0" x2="860" y2="200" gradientUnits="userSpaceOnUse">
    <stop offset="0%" stop-color="#0f0c29"/>
    <stop offset="55%" stop-color="#1a0a2e"/>
    <stop offset="100%" stop-color="#0d2b1e"/>
  </linearGradient>
  <linearGradient id="avGrad" x1="0" y1="0" x2="1" y2="1"><stop offset="0%" stop-color="#7c3aed"/><stop offset="100%" stop-color="#0891b2"/></linearGradient>
  <linearGradient id="bar1" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#e11d48"/><stop offset="100%" stop-color="#fb7185"/></linearGradient>
  <linearGradient id="bar2" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#7c3aed"/><stop offset="100%" stop-color="#a78bfa"/></linearGradient>
  <linearGradient id="bar3" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#d97706"/><stop offset="100%" stop-color="#fbbf24"/></linearGradient>
  <linearGradient id="bar4" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0891b2"/><stop offset="100%" stop-color="#38bdf8"/></linearGradient>
  <linearGradient id="bar5" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#059669"/><stop offset="100%" stop-color="#34d399"/></linearGradient>
  <radialGradient id="orb1"><stop offset="0%" stop-color="#7c3aed" stop-opacity="0.3"/><stop offset="100%" stop-color="#7c3aed" stop-opacity="0"/></radialGradient>
  <radialGradient id="orb2"><stop offset="0%" stop-color="#0891b2" stop-opacity="0.22"/><stop offset="100%" stop-color="#0891b2" stop-opacity="0"/></radialGradient>
  <radialGradient id="orb3"><stop offset="0%" stop-color="#059669" stop-opacity="0.18"/><stop offset="100%" stop-color="#059669" stop-opacity="0"/></radialGradient>
</defs>
 
<!-- ── BACKGROUND ── -->
<rect width="860" height="1980" fill="#0d1117" rx="16"/>
 
<!-- ══════════════════════════════════════
     HERO
══════════════════════════════════════ -->
<rect width="860" height="210" fill="url(#heroBg)" rx="16"/>
<rect y="194" width="860" height="16" fill="#0d1117"/>
<ellipse cx="80" cy="60" rx="160" ry="140" fill="url(#orb1)"/>
<ellipse cx="800" cy="180" rx="130" ry="130" fill="url(#orb2)"/>
<ellipse cx="750" cy="30" rx="90" ry="90" fill="url(#orb3)"/>
 
<!-- wave -->
<path class="wv" d="M0,30 C215,55 430,5 645,30 C752,42 806,20 860,28 L860,60 L0,60 Z" fill="#0d1117" transform="translate(0,150)"/>
 
<!-- avatar -->
<circle class="av" cx="78" cy="105" r="46" fill="url(#avGrad)"/>
<text x="78" y="113" text-anchor="middle" font-size="22" font-weight="700" fill="white">LA</text>
 
<!-- name -->
<text class="n" x="148" y="86" font-size="34" font-weight="700" fill="white">Lakshmi Anne</text>
<circle cx="368" cy="75" r="5" fill="#a78bfa"/>
 
<!-- role -->
<text class="s" x="148" y="113" font-size="14" fill="#94a3b8">Senior AI Engineer  ·  MLOps  ·  Computer Vision  ·  LLMs</text>
 
<!-- location -->
<text class="l" x="148" y="135" font-size="11.5" fill="#6b7280">Milton Keynes, UK  ·  lakshmianne07@gmail.com</text>
 
<!-- badge 1 -->
<g class="b1">
  <rect x="148" y="150" width="148" height="26" rx="13" fill="#7c3aed" fill-opacity="0.85"/>
  <rect x="148" y="150" width="148" height="26" rx="13" fill="none" stroke="#a78bfa" stroke-width="1"/>
  <text x="222" y="167" text-anchor="middle" font-size="10.5" font-weight="600" fill="white">7+ Years Experience</text>
</g>
<!-- badge 2 -->
<g class="b2">
  <rect x="306" y="150" width="162" height="26" rx="13" fill="#d97706" fill-opacity="0.85"/>
  <rect x="306" y="150" width="162" height="26" rx="13" fill="none" stroke="#fbbf24" stroke-width="1"/>
  <text x="387" y="167" text-anchor="middle" font-size="10.5" font-weight="600" fill="white">Open to Opportunities</text>
</g>
<!-- badge 3 -->
<g class="b3">
  <rect x="478" y="150" width="118" height="26" rx="13" fill="#059669" fill-opacity="0.85"/>
  <rect x="478" y="150" width="118" height="26" rx="13" fill="none" stroke="#34d399" stroke-width="1"/>
  <text x="537" y="167" text-anchor="middle" font-size="10.5" font-weight="600" fill="white">CI/CD Passing</text>
</g>
 
<!-- ══════════════════════════════════════
     ABOUT
══════════════════════════════════════ -->
<text class="sec" x="30" y="244" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">ABOUT</text>
<line x1="30" y1="250" x2="830" y2="250" stroke="#21262d" stroke-width="1"/>
<text x="30" y="274" font-size="13" fill="#94a3b8">Senior AI Engineer with 7+ years building production-grade machine learning systems. Specialising in MLOps</text>
<text x="30" y="292" font-size="13" fill="#94a3b8">pipelines, real-time computer vision, and large language model integrations. Currently at Brod Services</text>
<text x="30" y="310" font-size="13" fill="#94a3b8">delivering RFID and Computer Vision fusion for Sam's Club at scale.</text>
 
<!-- ══════════════════════════════════════
     EXPERTISE
══════════════════════════════════════ -->
<text class="sec" x="30" y="348" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">EXPERTISE</text>
<line x1="30" y1="354" x2="830" y2="354" stroke="#21262d" stroke-width="1"/>
 
<!-- bar rows -->
<!-- row 1 -->
<text x="30" y="382" font-size="12.5" fill="#e2e8f0">Python &amp; ML Frameworks</text>
<text x="830" y="382" text-anchor="end" font-size="11" fill="#6b7280">95%</text>
<rect x="30" y="387" width="800" height="5" rx="2.5" fill="#21262d"/>
<rect class="br1" x="30" y="387" width="786" height="5" rx="2.5" fill="url(#bar1)"/>
<!-- row 2 -->
<text x="30" y="412" font-size="12.5" fill="#e2e8f0">MLOps &amp; Cloud Engineering</text>
<text x="830" y="412" text-anchor="end" font-size="11" fill="#6b7280">95%</text>
<rect x="30" y="417" width="800" height="5" rx="2.5" fill="#21262d"/>
<rect class="br2" x="30" y="417" width="786" height="5" rx="2.5" fill="url(#bar2)"/>
<!-- row 3 -->
<text x="30" y="442" font-size="12.5" fill="#e2e8f0">Real-time Data Pipelines</text>
<text x="830" y="442" text-anchor="end" font-size="11" fill="#6b7280">92%</text>
<rect x="30" y="447" width="800" height="5" rx="2.5" fill="#21262d"/>
<rect class="br3" x="30" y="447" width="752" height="5" rx="2.5" fill="url(#bar3)"/>
<!-- row 4 -->
<text x="30" y="472" font-size="12.5" fill="#e2e8f0">Computer Vision &amp; Object Tracking</text>
<text x="830" y="472" text-anchor="end" font-size="11" fill="#6b7280">88%</text>
<rect x="30" y="477" width="800" height="5" rx="2.5" fill="#21262d"/>
<rect class="br4" x="30" y="477" width="718" height="5" rx="2.5" fill="url(#bar4)"/>
<!-- row 5 -->
<text x="30" y="502" font-size="12.5" fill="#e2e8f0">LLM Integration &amp; RAG Systems</text>
<text x="830" y="502" text-anchor="end" font-size="11" fill="#6b7280">85%</text>
<rect x="30" y="507" width="800" height="5" rx="2.5" fill="#21262d"/>
<rect class="br5" x="30" y="507" width="685" height="5" rx="2.5" fill="url(#bar5)"/>
 
<!-- ══════════════════════════════════════
     PROJECTS
══════════════════════════════════════ -->
<text class="sec" x="30" y="548" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">PROJECTS</text>
<line x1="30" y1="554" x2="830" y2="554" stroke="#21262d" stroke-width="1"/>
 
<!-- card helper: col1 x=30, col2 x=450, card w=400, h=120 -->
 
<!-- RAG card -->
<rect x="30" y="566" width="400" height="118" rx="10" fill="#16213e"/>
<rect x="30" y="566" width="400" height="3" rx="10" fill="#378add"/>
<text x="48" y="589" font-size="13" font-weight="600" fill="#60a5fa">rag-enterprise-search</text>
<text x="48" y="607" font-size="11" fill="rgba(255,255,255,0.7)">Production RAG pipeline — LangChain,</text>
<text x="48" y="621" font-size="11" fill="rgba(255,255,255,0.7)">FAISS, GPT-4, FastAPI serving layer.</text>
<rect x="48" y="634" width="54" height="18" rx="4" fill="#1c3c5e"/>
<text x="75" y="647" text-anchor="middle" font-size="9.5" fill="#60a5fa">LangChain</text>
<rect x="110" y="634" width="36" height="18" rx="4" fill="#065f65"/>
<text x="128" y="647" text-anchor="middle" font-size="9.5" fill="#34d399">FAISS</text>
<rect x="154" y="634" width="36" height="18" rx="4" fill="#1a3530"/>
<text x="172" y="647" text-anchor="middle" font-size="9.5" fill="#6ee7b7">GPT-4</text>
<rect x="198" y="634" width="40" height="18" rx="4" fill="#003d35"/>
<text x="218" y="647" text-anchor="middle" font-size="9.5" fill="#34d399">FastAPI</text>
 
<!-- LLM card -->
<rect x="450" y="566" width="400" height="118" rx="10" fill="#2d1b69"/>
<rect x="450" y="566" width="400" height="3" rx="10" fill="#7c3aed"/>
<text x="468" y="589" font-size="13" font-weight="600" fill="#a78bfa">llm-sql-to-python</text>
<text x="468" y="607" font-size="11" fill="rgba(255,255,255,0.7)">GPT-4 powered PL/SQL to Python</text>
<text x="468" y="621" font-size="11" fill="rgba(255,255,255,0.7)">converter with Streamlit UI.</text>
<rect x="468" y="634" width="36" height="18" rx="4" fill="#1a3530"/>
<text x="486" y="647" text-anchor="middle" font-size="9.5" fill="#6ee7b7">GPT-4</text>
<rect x="512" y="634" width="28" height="18" rx="4" fill="#3b0a6b"/>
<text x="526" y="647" text-anchor="middle" font-size="9.5" fill="#c4b5fd">LLM</text>
<rect x="548" y="634" width="46" height="18" rx="4" fill="#5a0000"/>
<text x="571" y="647" text-anchor="middle" font-size="9.5" fill="#fca5a5">Streamlit</text>
 
<!-- RFID card -->
<rect x="30" y="698" width="400" height="118" rx="10" fill="#064e3b"/>
<rect x="30" y="698" width="400" height="3" rx="10" fill="#059669"/>
<text x="48" y="721" font-size="13" font-weight="600" fill="#34d399">rfid-kafka-pipeline</text>
<text x="48" y="739" font-size="11" fill="rgba(255,255,255,0.7)">Real-time RFID event streaming</text>
<text x="48" y="753" font-size="11" fill="rgba(255,255,255,0.7)">with Kafka and Streamlit.</text>
<rect x="48" y="766" width="34" height="18" rx="4" fill="#1a1a1a"/>
<text x="65" y="779" text-anchor="middle" font-size="9.5" fill="#d1d5db">Kafka</text>
<rect x="90" y="766" width="34" height="18" rx="4" fill="#0a2e1e"/>
<text x="107" y="779" text-anchor="middle" font-size="9.5" fill="#6ee7b7">RFID</text>
<rect x="132" y="766" width="56" height="18" rx="4" fill="#5a0000"/>
<text x="160" y="779" text-anchor="middle" font-size="9.5" fill="#fca5a5">Streaming</text>
 
<!-- YOLO card -->
<rect x="450" y="698" width="400" height="118" rx="10" fill="#78350f"/>
<rect x="450" y="698" width="400" height="3" rx="10" fill="#d97706"/>
<text x="468" y="721" font-size="13" font-weight="600" fill="#fbbf24">yolov8-object-tracking</text>
<text x="468" y="739" font-size="11" fill="rgba(255,255,255,0.7)">YOLOv8 + IoU tracker served</text>
<text x="468" y="753" font-size="11" fill="rgba(255,255,255,0.7)">via FastAPI. Edge-optimised.</text>
<rect x="468" y="766" width="46" height="18" rx="4" fill="#5a2a00"/>
<text x="491" y="779" text-anchor="middle" font-size="9.5" fill="#fdba74">YOLOv8</text>
<rect x="522" y="766" width="22" height="18" rx="4" fill="#5a2a00"/>
<text x="533" y="779" text-anchor="middle" font-size="9.5" fill="#fdba74">CV</text>
<rect x="552" y="766" width="42" height="18" rx="4" fill="#003d35"/>
<text x="573" y="779" text-anchor="middle" font-size="9.5" fill="#34d399">FastAPI</text>
 
<!-- MLOps card -->
<rect x="30" y="830" width="400" height="118" rx="10" fill="#881337"/>
<rect x="30" y="830" width="400" height="3" rx="10" fill="#e11d48"/>
<text x="48" y="853" font-size="13" font-weight="600" fill="#fb7185">mlops-azure-template</text>
<text x="48" y="871" font-size="11" fill="rgba(255,255,255,0.7)">Azure ML · MLflow · drift detection</text>
<text x="48" y="885" font-size="11" fill="rgba(255,255,255,0.7)">GitHub Actions CI/CD — passing.</text>
<rect x="48" y="898" width="48" height="18" rx="4" fill="#003d6b"/>
<text x="72" y="911" text-anchor="middle" font-size="9.5" fill="#93c5fd">Azure ML</text>
<rect x="104" y="898" width="40" height="18" rx="4" fill="#003d6b"/>
<text x="124" y="911" text-anchor="middle" font-size="9.5" fill="#93c5fd">MLflow</text>
<rect x="152" y="898" width="34" height="18" rx="4" fill="#0a2e1e"/>
<text x="169" y="911" text-anchor="middle" font-size="9.5" fill="#6ee7b7">CI/CD</text>
 
<!-- Sentiment card -->
<rect x="450" y="830" width="400" height="118" rx="10" fill="#701a75"/>
<rect x="450" y="830" width="400" height="3" rx="10" fill="#db2777"/>
<text x="468" y="853" font-size="13" font-weight="600" fill="#f9a8d4">sentiment-kafka-pipeline</text>
<text x="468" y="871" font-size="11" fill="rgba(255,255,255,0.7)">Real-time DistilBERT sentiment</text>
<text x="468" y="885" font-size="11" fill="rgba(255,255,255,0.7)">analysis with Kafka + Streamlit.</text>
<rect x="468" y="898" width="54" height="18" rx="4" fill="#3b0a6b"/>
<text x="495" y="911" text-anchor="middle" font-size="9.5" fill="#c4b5fd">DistilBERT</text>
<rect x="530" y="898" width="28" height="18" rx="4" fill="#3b0464">
</rect>
<text x="544" y="911" text-anchor="middle" font-size="9.5" fill="#e9d5ff">NLP</text>
<rect x="566" y="898" width="34" height="18" rx="4" fill="#1a1a1a"/>
<text x="583" y="911" text-anchor="middle" font-size="9.5" fill="#d1d5db">Kafka</text>
 
<!-- Multi-cloud card (full width) -->
<rect x="30" y="962" width="400" height="118" rx="10" fill="#164e63"/>
<rect x="30" y="962" width="400" height="3" rx="10" fill="#0891b2"/>
<rect x="352" y="970" width="42" height="16" rx="4" fill="rgba(255,255,255,0.15)"/>
<text x="373" y="982" text-anchor="middle" font-size="9" font-weight="700" fill="rgba(255,255,255,0.85)">SOON</text>
<text x="48" y="985" font-size="13" font-weight="600" fill="#38bdf8">multi-cloud-ai-agent</text>
<text x="48" y="1003" font-size="11" fill="rgba(255,255,255,0.7)">LangGraph agent across AWS, Azure</text>
<text x="48" y="1017" font-size="11" fill="rgba(255,255,255,0.7)">and GCP — coming soon.</text>
<rect x="48" y="1030" width="56" height="18" rx="4" fill="#003d6b"/>
<text x="76" y="1043" text-anchor="middle" font-size="9.5" fill="#93c5fd">LangGraph</text>
<rect x="112" y="1030" width="30" height="18" rx="4" fill="#1a1a1a"/>
<text x="127" y="1043" text-anchor="middle" font-size="9.5" fill="#d1d5db">AWS</text>
<rect x="150" y="1030" width="36" height="18" rx="4" fill="#003d6b"/>
<text x="168" y="1043" text-anchor="middle" font-size="9.5" fill="#93c5fd">Azure</text>
<rect x="194" y="1030" width="28" height="18" rx="4" fill="#1c2f5e"/>
<text x="208" y="1043" text-anchor="middle" font-size="9.5" fill="#93c5fd">GCP</text>
 
<!-- ══════════════════════════════════════
     TECH STACK
══════════════════════════════════════ -->
<text class="sec" x="30" y="1128" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">TECH STACK</text>
<line x1="30" y1="1134" x2="830" y2="1134" stroke="#21262d" stroke-width="1"/>
 
<!-- pill row 1 -->
<rect x="30"  y="1148" width="60"  height="24" rx="12" fill="#5a1a0a"/><text x="60"  y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#fca5a5">PyTorch</text>
<rect x="100" y="1148" width="72"  height="24" rx="12" fill="#0a1e3c"/><text x="136" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#93c5fd">LangChain</text>
<rect x="182" y="1148" width="62"  height="24" rx="12" fill="#003d6b"/><text x="213" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#93c5fd">Azure ML</text>
<rect x="254" y="1148" width="42"  height="24" rx="12" fill="#1a1a1a"/><text x="275" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#d1d5db">Kafka</text>
<rect x="306" y="1148" width="50"  height="24" rx="12" fill="#003d35"/><text x="331" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#34d399">FastAPI</text>
<rect x="366" y="1148" width="54"  height="24" rx="12" fill="#5a2a00"/><text x="393" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#fdba74">YOLOv8</text>
<rect x="430" y="1148" width="50"  height="24" rx="12" fill="#003d6b"/><text x="455" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#93c5fd">MLflow</text>
<rect x="490" y="1148" width="40"  height="24" rx="12" fill="#1a3530"/><text x="510" y="1164" text-anchor="middle" font-size="10.5" font-weight="600" fill="#6ee7b7">GPT-4</text>
<!-- pill row 2 -->
<rect x="30"  y="1182" width="56"  height="24" rx="12" fill="#5a0000"/><text x="58"  y="1198" text-anchor="middle" font-size="10.5" font-weight="600" fill="#fca5a5">Streamlit</text>
<rect x="96"  y="1182" width="46"  height="24" rx="12" fill="#0d3d6b"/><text x="119" y="1198" text-anchor="middle" font-size="10.5" font-weight="600" fill="#93c5fd">Docker</text>
<rect x="152" y="1182" width="94"  height="24" rx="12" fill="#002080"/><text x="199" y="1198" text-anchor="middle" font-size="10.5" font-weight="600" fill="#93c5fd">GitHub Actions</text>
<rect x="256" y="1182" width="60"  height="24" rx="12" fill="#3b0a6b"/><text x="286" y="1198" text-anchor="middle" font-size="10.5" font-weight="600" fill="#c4b5fd">DistilBERT</text>
<rect x="326" y="1182" width="38"  height="24" rx="12" fill="#065f65"/><text x="345" y="1198" text-anchor="middle" font-size="10.5" font-weight="600" fill="#34d399">FAISS</text>
<rect x="374" y="1182" width="50"  height="24" rx="12" fill="#1e3a5f"/><text x="399" y="1198" text-anchor="middle" font-size="10.5" font-weight="600" fill="#93c5fd">Python</text>
 
<!-- ══════════════════════════════════════
     AT A GLANCE
══════════════════════════════════════ -->
<text class="sec" x="30" y="1234" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">AT A GLANCE</text>
<line x1="30" y1="1240" x2="830" y2="1240" stroke="#21262d" stroke-width="1"/>
 
<rect x="30"  y="1254" width="252" height="80" rx="10" fill="#2d1b69" stroke="#7c3aed" stroke-width="1" stroke-opacity="0.4"/>
<text x="156" y="1296" text-anchor="middle" font-size="28" font-weight="700" fill="#a78bfa">7+</text>
<text x="156" y="1318" text-anchor="middle" font-size="10.5" fill="rgba(255,255,255,0.55)">Years Exp</text>
 
<rect x="304" y="1254" width="252" height="80" rx="10" fill="#064e3b" stroke="#059669" stroke-width="1" stroke-opacity="0.4"/>
<text x="430" y="1296" text-anchor="middle" font-size="28" font-weight="700" fill="#34d399">CI</text>
<text x="430" y="1318" text-anchor="middle" font-size="10.5" fill="rgba(255,255,255,0.55)">Passing</text>
 
<rect x="578" y="1254" width="252" height="80" rx="10" fill="#78350f" stroke="#d97706" stroke-width="1" stroke-opacity="0.4"/>
<text x="704" y="1296" text-anchor="middle" font-size="28" font-weight="700" fill="#fbbf24">3</text>
<text x="704" y="1318" text-anchor="middle" font-size="10.5" fill="rgba(255,255,255,0.55)">Cloud Platforms</text>
 
<!-- ══════════════════════════════════════
     CURRENT ROLE
══════════════════════════════════════ -->
<text class="sec" x="30" y="1376" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">CURRENT ROLE</text>
<line x1="30" y1="1382" x2="830" y2="1382" stroke="#21262d" stroke-width="1"/>
 
<rect x="30" y="1396" width="800" height="100" rx="10" fill="#161b22" stroke="#30363d" stroke-width="1"/>
<text x="52" y="1422" font-size="14" font-weight="700" fill="white">Brod Services</text>
<text x="52" y="1440" font-size="11.5" fill="#a78bfa">Senior AI Engineer</text>
<text x="52" y="1460" font-size="11.5" fill="#6b7280">Building RFID + Computer Vision fusion pipeline for Sam's Club. Real-time object tracking,</text>
<text x="52" y="1476" font-size="11.5" fill="#6b7280">edge ML deployment, and high-throughput Kafka streaming at production scale.</text>
 
<!-- ══════════════════════════════════════
     CONNECT
══════════════════════════════════════ -->
<text class="sec" x="30" y="1536" font-size="10" font-weight="700" letter-spacing="2" fill="#6b7280">CONNECT</text>
<line x1="30" y1="1542" x2="830" y2="1542" stroke="#21262d" stroke-width="1"/>
 
<rect x="30"  y="1556" width="248" height="42" rx="10" fill="#0a66c2"/>
<text x="154" y="1582" text-anchor="middle" font-size="12" font-weight="600" fill="white">LinkedIn — Lakshmi Anne</text>
 
<rect x="306" y="1556" width="248" height="42" rx="10" fill="#c05621"/>
<text x="430" y="1582" text-anchor="middle" font-size="12" font-weight="600" fill="white">lakshmianne07@gmail.com</text>
 
<rect x="582" y="1556" width="248" height="42" rx="10" fill="#7c3aed"/>
<text x="706" y="1582" text-anchor="middle" font-size="12" font-weight="600" fill="white">github.com/Anne07-Ai</text>
 
<!-- ══════════════════════════════════════
     FOOTER WAVE
══════════════════════════════════════ -->
<path d="M0,1620 C215,1595 430,1640 645,1615 C752,1603 806,1625 860,1612 L860,1660 L0,1660 Z" fill="#7c3aed" fill-opacity="0.25"/>
<path d="M0,1632 C215,1655 430,1618 645,1638 C752,1648 806,1628 860,1642 L860,1660 L0,1660 Z" fill="#0891b2" fill-opacity="0.2"/>
 
<text x="430" y="1648" text-anchor="middle" font-size="10.5" fill="#6b7280">Anne07-Ai · Senior AI Engineer · 2025</text>
 
</svg>
 
