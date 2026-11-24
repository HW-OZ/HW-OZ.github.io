# HW-OZ.github.io
[code_artifact (1).html](https://github.com/user-attachments/files/35323373/code_artifact.1.html)
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />
  <title>JY Happy Birthday ♥</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DungGeunMo&display=swap" rel="stylesheet">
  <style>
    :root {
      --ink: #141013;
      --pink-main: #e63986;
      --pink-light: #ff85bc;
      --pink-pale: #ffeaf4;
      --sky-bg: #b6d2f2;
      --cta-bar-h: 56px;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      user-select: none;
      -webkit-user-select: none;
      -webkit-tap-highlight-color: transparent;
      font-family: 'DungGeunMo', monospace;
    }

    html, body {
      width: 100%;
      height: 100%;
      background-color: var(--sky-bg);
      background-image:
        radial-gradient(#97bce8 1.5px, transparent 1.5px),
        radial-gradient(#dfeeff 1.5px, #b6d2f2 1.5px);
      background-size: 20px 20px;
      background-position: 0 0, 10px 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }

    /* 엄격한 1:1 정사각형 고정 비율 컨테이너 */
    .game-shell {
      position: relative;
      aspect-ratio: 1 / 1;
      width: min(94vw, 94dvh, 460px);
      height: min(94vw, 94dvh, 460px);
      background: #7ca6df;
      border: 4px solid var(--ink);
      box-shadow: 0 12px 32px rgba(20, 16, 19, 0.28);
      display: flex;
      flex-direction: column;
      overflow: hidden;
    }

    /* 상단 핫핑크 뾰족 레이스 보더 */
    .lace-top {
      height: 15px;
      width: 100%;
      flex-shrink: 0;
      background-color: var(--pink-main);
      background-image:
        radial-gradient(circle at 8px 4px, #ff99c8 2px, transparent 2.5px),
        linear-gradient(135deg, transparent 50%, #7ca6df 50%),
        linear-gradient(225deg, transparent 50%, #7ca6df 50%);
      background-position: top left, bottom left, bottom left;
      background-size: 16px 15px, 16px 7px, 16px 7px;
      background-repeat: repeat-x;
      border-bottom: 2px solid var(--ink);
      z-index: 5;
      transition: background-image 0.2s;
    }

    .game-shell.indoor .lace-top {
      background-image:
        radial-gradient(circle at 8px 4px, #ff99c8 2px, transparent 2.5px),
        linear-gradient(135deg, transparent 50%, #ffe6f0 50%),
        linear-gradient(225deg, transparent 50%, #ffe6f0 50%);
    }

    .game-shell.finale .lace-top {
      background-image:
        radial-gradient(circle at 8px 4px, #ff99c8 2px, transparent 2.5px),
        linear-gradient(135deg, transparent 50%, #ffeaf4 50%),
        linear-gradient(225deg, transparent 50%, #ffeaf4 50%);
    }

    /* 메인 픽셀 캔버스 스테이지 (하단 CTA 바를 제외한 상단 독립 영역) */
    .stage-wrap {
      position: relative;
      flex: 1;
      width: 100%;
      overflow: hidden;
      cursor: pointer;
    }

    canvas {
      display: block;
      width: 100%;
      height: 100%;
      image-rendering: -moz-crisp-edges;
      image-rendering: -webkit-crisp-edges;
      image-rendering: pixelated;
      image-rendering: crisp-edges;
    }

    /* 은은한 CRT 가로 스캔라인 오버레이 */
    .crt-scanlines {
      pointer-events: none;
      position: absolute;
      inset: 0;
      background: repeating-linear-gradient(
        to bottom,
        rgba(255, 255, 255, 0) 0px,
        rgba(255, 255, 255, 0) 2px,
        rgba(20, 16, 19, 0.09) 3px,
        rgba(20, 16, 19, 0.09) 4px
      );
      z-index: 4;
    }

    /* 우측 상단 미니 사운드 토글 버튼 */
    .btn-mute {
      position: absolute;
      top: 8px;
      right: 8px;
      z-index: 8;
      width: 28px;
      height: 28px;
      background: #ffffff;
      color: var(--ink);
      border: 2px solid var(--ink);
      box-shadow: 2px 2px 0 var(--pink-main);
      font-size: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
    }

    .btn-mute:active {
      transform: translate(1px, 1px);
    }

    /* 케이크 선택 오버레이 (상단 스테이지 내부 중앙 배치, 하단 CTA 바와 완전 분리) */
    .cake-selector {
      position: absolute;
      inset: 0;
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 12px;
      background: rgba(20, 16, 19, 0.24);
      z-index: 6;
    }

    .cake-selector.active {
      display: flex;
    }

    .selector-title {
      background: #ffffff;
      color: var(--ink);
      border: 3px solid var(--ink);
      padding: 6px 14px;
      font-size: 14px;
      margin-bottom: 12px;
      box-shadow: 0 3px 0 var(--ink);
    }

    .cake-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 8px;
      width: 100%;
      max-width: 344px;
    }

    .cake-card {
      background: #ffffff;
      border: 3px solid var(--ink);
      padding: 8px 4px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 6px;
      cursor: pointer;
      box-shadow: 0 3px 0 var(--ink);
      transition: transform 0.08s;
    }

    .cake-card:active {
      transform: translateY(2px);
      box-shadow: 0 1px 0 var(--ink);
    }

    .cake-card.selected {
      background: #fff0f7;
      border-color: var(--pink-main);
      animation: cardBlink 0.24s steps(2) infinite;
    }

    .cake-card.dimmed {
      opacity: 0.45;
      pointer-events: none;
    }

    @keyframes cardBlink {
      0%, 100% { background: #ffffff; }
      50% { background: #ffd1e6; }
    }

    .cake-card canvas {
      width: 38px;
      height: 38px;
      image-rendering: pixelated;
    }

    .cake-name {
      font-size: 12px;
      color: var(--ink);
      text-align: center;
      word-break: keep-all;
    }

    /* 하단 핫핑크 레이스 구분선 */
    .lace-divider {
      height: 12px;
      width: 100%;
      flex-shrink: 0;
      background-color: var(--pink-main);
      background-image:
        radial-gradient(circle at 6px 6px, #ffffff 2.2px, transparent 2.6px),
        radial-gradient(circle at 12px 2px, #ff99c8 1.5px, transparent 2px);
      background-size: 12px 12px;
      border-top: 3px solid var(--ink);
      border-bottom: 3px solid var(--ink);
      z-index: 10;
    }

    /* 모든 장면 공용 하단 고정 CTA 독 (겹침 원천 차단) */
    .cta-dock {
      height: var(--cta-bar-h);
      width: 100%;
      flex-shrink: 0;
      background: #ffffff;
      padding: 7px 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      z-index: 10;
    }

    /* 통일된 단일 CTA 버튼 규격 */
    .cta-btn {
      width: 100%;
      height: 100%;
      background: var(--pink-main);
      color: #ffffff;
      border: 3px solid var(--ink);
      box-shadow:
        inset 2px 2px 0 #ff85bc,
        inset -2px -2px 0 #9e1955,
        0 3px 0 var(--ink);
      text-shadow: 1.5px 1.5px 0 var(--ink);
      font-size: 16px;
      letter-spacing: 0.5px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      cursor: pointer;
    }

    .cta-btn:active:not(:disabled) {
      transform: translateY(2px);
      box-shadow: 0 1px 0 var(--ink);
    }

    .cta-btn.secondary {
      background: var(--pink-pale);
      color: var(--ink);
      text-shadow: none;
      box-shadow:
        inset 2px 2px 0 #ffffff,
        inset -2px -2px 0 #f2b8d4,
        0 3px 0 var(--ink);
    }

    .cta-btn:disabled {
      background: #e5e8ed;
      color: #6c757d;
      text-shadow: none;
      cursor: default;
      box-shadow: 0 2px 0 var(--ink);
      transform: none;
    }
  </style>
</head>
<body>

<div class="game-shell" id="gameShell">
  <div class="lace-top"></div>

  <div class="stage-wrap" id="stageWrap">
    <!-- 고밀도 240x192 논리 픽셀 캔버스 (1:1 도트 비율 유지) -->
    <canvas id="gameCanvas" width="240" height="192"></canvas>
    <div class="crt-scanlines" aria-hidden="true"></div>
    <button type="button" id="btnMute" class="btn-mute" aria-label="효과음 토글">♪</button>

    <!-- Scene 3: 케이크 선택 오버레이 (중앙 스테이지 내부) -->
    <div class="cake-selector" id="cakeSelector">
      <div class="selector-title">원하는 케이크 종류를 선택하세요</div>
      <div class="cake-grid">
        <button type="button" class="cake-card" data-cake="strawberry">
          <canvas id="iconStrawberry" width="36" height="36"></canvas>
          <span class="cake-name">딸기 생크림</span>
        </button>
        <button type="button" class="cake-card" data-cake="choco">
          <canvas id="iconChoco" width="36" height="36"></canvas>
          <span class="cake-name">초코 가나슈</span>
        </button>
        <button type="button" class="cake-card" data-cake="sweetpotato">
          <canvas id="iconSweetpotato" width="36" height="36"></canvas>
          <span class="cake-name">달콤 고구마</span>
        </button>
      </div>
    </div>
  </div>

  <div class="lace-divider"></div>

  <!-- 모든 장면에서 동일한 위치·크기·디자인으로 고정되는 하단 CTA 독 -->
  <div class="cta-dock" id="ctaDock">
    <button type="button" class="cta-btn" id="mainCtaBtn">따라가기</button>
  </div>
</div>

<script>
  /* =====================================================================
     1. 8비트 Web Audio 효과음
  ===================================================================== */
  let isMuted = false;
  let audioCtx = null;

  function initAudio() {
    if (!audioCtx) {
      const AC = window.AudioContext || window.webkitAudioContext;
      if (AC) audioCtx = new AC();
    }
    if (audioCtx && audioCtx.state === 'suspended') {
      audioCtx.resume();
    }
  }

  document.getElementById('btnMute').addEventListener('click', (e) => {
    e.stopPropagation();
    isMuted = !isMuted;
    const btn = document.getElementById('btnMute');
    btn.textContent = isMuted ? '✕' : '♪';
    btn.style.opacity = isMuted ? '0.55' : '1';
  });

  function beep(freq, duration = 0.1, type = 'square', delay = 0, vol = 0.06) {
    if (isMuted) return;
    try {
      initAudio();
      if (!audioCtx) return;
      const osc = audioCtx.createOscillator();
      const gain = audioCtx.createGain();
      osc.type = type;
      osc.frequency.setValueAtTime(freq, audioCtx.currentTime + delay);
      gain.gain.setValueAtTime(vol, audioCtx.currentTime + delay);
      gain.gain.exponentialRampToValueAtTime(0.001, audioCtx.currentTime + delay + duration);
      osc.connect(gain);
      gain.connect(audioCtx.destination);
      osc.start(audioCtx.currentTime + delay);
      osc.stop(audioCtx.currentTime + delay + duration);
    } catch (err) {}
  }

  function playHopSfx() {
    beep(392.0, 0.07, 'square', 0, 0.06);
    beep(587.3, 0.10, 'square', 0.05, 0.06);
  }

  function playSelectSfx() {
    beep(523.25, 0.07, 'square', 0, 0.06);
    beep(783.99, 0.11, 'square', 0.06, 0.06);
  }

  function playOvenDoneSfx() {
    beep(659.25, 0.08, 'square', 0, 0.06);
    beep(880.00, 0.08, 'square', 0.08, 0.06);
    beep(1046.5, 0.22, 'square', 0.16, 0.07);
  }

  function playBirthdayJingle() {
    const notes = [
      [392.00, 0.13, 0.00], [392.00, 0.13, 0.15], [440.00, 0.26, 0.30],
      [392.00, 0.26, 0.60], [523.25, 0.26, 0.90], [493.88, 0.44, 1.20]
    ];
    notes.forEach(([f, d, t]) => beep(f, d, 'triangle', t, 0.09));
  }

  /* =====================================================================
     2. 고밀도 240x192 캔버스 및 상태 변수 설정
  ===================================================================== */
  const W = 240;
  const H = 192;

  const gameShell = document.getElementById('gameShell');
  const canvas = document.getElementById('gameCanvas');
  const ctx = canvas.getContext('2d');
  const stageWrap = document.getElementById('stageWrap');
  const cakeSelector = document.getElementById('cakeSelector');
  const mainCtaBtn = document.getElementById('mainCtaBtn');
  ctx.imageSmoothingEnabled = false;

  // scene: 'intro' | 'walk' | 'select' | 'oven_ready' | 'oven_baking' | 'oven_done' | 'finale'
  let scene = 'intro';
  let walkStep = 0; // 0 -> 1 -> 2 -> 3 (도착)
  let isJumping = false;
  let isSelectingDelay = false;
  let jumpProgress = 0;
  let selectedCake = 'strawberry';
  let bakeProgress = 0;
  let candlesLit = [true, true, true];
  let frame = 0;

  let footprints = [];
  let confetti = [];
  let smokeParticles = [];

  // 배경 파티클 (뭉게구름, 반짝이는 음표, 눈송이)
  const clouds = [
    { x: 14, y: 18, w: 54, speed: 0.05 },
    { x: 118, y: 14, w: 66, speed: 0.04 },
    { x: 186, y: 34, w: 46, speed: 0.06 }
  ];

  const notes = [
    { x: 42, y: 46, color: '#ff7eb9', hi: '#ffc2de', phase: 0 },
    { x: 116, y: 34, color: '#ffd166', hi: '#fff1b8', phase: 2.1 },
    { x: 190, y: 48, color: '#ff7eb9', hi: '#ffc2de', phase: 4.2 }
  ];

  const snows = Array.from({ length: 34 }, (_, i) => ({
    x: (i * 37) % W,
    y: (i * 23) % H,
    s: (i % 2) + 1,
    vy: 0.28 + (i % 3) * 0.13,
    drift: i * 0.65
  }));

  // 토끼 3단계 점프 경로 (240x192 좌표)
  const walkPositions = [
    { x: 42, y: 156 },
    { x: 78, y: 150 },
    { x: 116, y: 144 },
    { x: 154, y: 138 }
  ];
  let rabbitX = walkPositions[0].x;
  let rabbitY = walkPositions[0].y;
  let startX = rabbitX;
  let startY = rabbitY;
  let targetX = rabbitX;
  let targetY = rabbitY;

  /* =====================================================================
     3. 통일된 하단 CTA 바 상태 동기화
  ===================================================================== */
  function updateCTA() {
    mainCtaBtn.classList.remove('secondary');
    mainCtaBtn.disabled = false;
    cakeSelector.classList.remove('active');

    gameShell.classList.toggle('indoor', scene === 'select' || scene.startsWith('oven_'));
    gameShell.classList.toggle('finale', scene === 'finale');

    if (scene === 'intro') {
      mainCtaBtn.textContent = '따라가기';
    } else if (scene === 'walk') {
      if (walkStep < 3) {
        mainCtaBtn.textContent = `깡충깡충 (${walkStep}/3)`;
        mainCtaBtn.disabled = isJumping;
      } else {
        mainCtaBtn.textContent = '오두막 도착!';
        mainCtaBtn.disabled = true;
      }
    } else if (scene === 'select') {
      cakeSelector.classList.add('active');
      mainCtaBtn.textContent = '위에서 케이크를 골라주세요';
      mainCtaBtn.disabled = true;
    } else if (scene === 'oven_ready') {
      mainCtaBtn.textContent = '굽기';
    } else if (scene === 'oven_baking') {
      mainCtaBtn.textContent = '노릇노릇 굽는 중...';
      mainCtaBtn.disabled = true;
    } else if (scene === 'oven_done') {
      mainCtaBtn.textContent = '꺼내기';
    } else if (scene === 'finale') {
      mainCtaBtn.textContent = '다시하기';
      mainCtaBtn.classList.add('secondary');
    }
  }

  /* =====================================================================
     4. 사용자 인터랙션 핸들러
  ===================================================================== */
  mainCtaBtn.addEventListener('click', () => {
    initAudio();
    if (scene === 'intro') {
      scene = 'walk';
      triggerJump();
      updateCTA();
    } else if (scene === 'walk' && !isJumping && walkStep < 3) {
      triggerJump();
      updateCTA();
    } else if (scene === 'oven_ready') {
      playSelectSfx();
      scene = 'oven_baking';
      bakeProgress = 0;
      updateCTA();
    } else if (scene === 'oven_done') {
      playBirthdayJingle();
      scene = 'finale';
      candlesLit = [true, true, true];
      addConfetti(120, 96, 56);
      updateCTA();
    } else if (scene === 'finale') {
      playSelectSfx();
      resetAll();
    }
  });

  // 스테이지 터치 지원 (걷기 점프 & 피날레 촛불 끄기)
  stageWrap.addEventListener('click', () => {
    initAudio();
    if (scene === 'walk' && !isJumping && walkStep < 3) {
      triggerJump();
      updateCTA();
    } else if (scene === 'finale') {
      const idx = candlesLit.findIndex(v => v);
      if (idx !== -1) {
        candlesLit[idx] = false;
        const candleXs = [103, 120, 137];
        addCandleSmoke(candleXs[idx], 64);
        beep(660 - idx * 80, 0.09, 'triangle', 0, 0.06);
        if (!candlesLit.some(v => v)) {
          playBirthdayJingle();
          addConfetti(120, 86, 68);
        }
      }
    }
  });

  // 케이크 카드 선택 핸들러
  document.querySelectorAll('.cake-card').forEach(card => {
    card.addEventListener('click', (e) => {
      e.stopPropagation();
      if (scene !== 'select' || isSelectingDelay) return;
      initAudio();
      isSelectingDelay = true;
      playSelectSfx();

      document.querySelectorAll('.cake-card').forEach(c => {
        if (c === card) {
          c.classList.add('selected');
          c.classList.remove('dimmed');
        } else {
          c.classList.remove('selected');
          c.classList.add('dimmed');
        }
      });

      selectedCake = card.dataset.cake;

      // 한 템포(0.95초) 깜빡임 대기 후 오븐으로 전환
      setTimeout(() => {
        document.querySelectorAll('.cake-card').forEach(c => c.classList.remove('selected', 'dimmed'));
        isSelectingDelay = false;
        scene = 'oven_ready';
        updateCTA();
      }, 950);
    });
  });

  function triggerJump() {
    if (walkStep >= 3) return;
    isJumping = true;
    jumpProgress = 0;
    playHopSfx();
    startX = walkPositions[walkStep].x;
    startY = walkPositions[walkStep].y;
    footprints.push({ x: startX, y: startY });
    walkStep++;
    targetX = walkPositions[walkStep].x;
    targetY = walkPositions[walkStep].y;
  }

  function resetAll() {
    scene = 'intro';
    walkStep = 0;
    isJumping = false;
    isSelectingDelay = false;
    jumpProgress = 0;
    rabbitX = walkPositions[0].x;
    rabbitY = walkPositions[0].y;
    bakeProgress = 0;
    candlesLit = [true, true, true];
    footprints = [];
    confetti = [];
    smokeParticles = [];
    updateCTA();
  }

  /* =====================================================================
     5. 고밀도 픽셀 드로잉 유틸 & 섬세한 셰이딩 스프라이트
  ===================================================================== */
  function px(x, y, w, h, color) {
    ctx.fillStyle = color;
    ctx.fillRect(Math.round(x), Math.round(y), Math.round(w), Math.round(h));
  }

  // 디더링 패턴 보조 (체커보드 픽셀 음영)
  function dither(x, y, w, h, c1, c2) {
    for (let py = Math.round(y); py < Math.round(y + h); py++) {
      for (let px0 = Math.round(x); px0 < Math.round(x + w); px0++) {
        ctx.fillStyle = ((px0 + py) & 1) === 0 ? c1 : c2;
        ctx.fillRect(px0, py, 1, 1);
      }
    }
  }

  // 섬세한 3단계 셀 셰이딩 + 레이스 달린 빨간 앞치마 토끼
  function drawRabbit(x, y, jumping) {
    const ox = Math.round(x - 16);
    const oy = Math.round(y - 36);
    const earOffset = jumping ? -3 : 0;

    // 설원 바닥 그림자
    px(ox + 7, Math.round(y) - 1, 18, 4, '#b8d3f0');
    px(ox + 9, Math.round(y), 14, 2, '#9ec0e6');

    // 꼬리 (왼쪽 뒤)
    px(ox + 1, oy + 24 + (jumping ? -1 : 0), 5, 5, '#141013');
    px(ox + 2, oy + 25 + (jumping ? -1 : 0), 3, 3, '#ffffff');
    px(ox + 2, oy + 26 + (jumping ? -1 : 0), 2, 2, '#dce8f5');

    // 왼쪽 귀 (다단계 음영 + 핑크 내이)
    px(ox + 8, oy + earOffset, 5, 13, '#141013');
    px(ox + 9, oy + 1 + earOffset, 3, 11, '#ffffff');
    px(ox + 9, oy + 1 + earOffset, 1, 10, '#f3f8ff');
    px(ox + 10, oy + 3 + earOffset, 1, 7, '#ff85bc');
    px(ox + 10, oy + 4 + earOffset, 1, 4, '#ff4d94');

    // 오른쪽 귀
    px(ox + 19, oy + earOffset, 5, 13, '#141013');
    px(ox + 20, oy + 1 + earOffset, 3, 11, '#ffffff');
    px(ox + 22, oy + 1 + earOffset, 1, 10, '#dce8f5');
    px(ox + 21, oy + 3 + earOffset, 1, 7, '#ff85bc');
    px(ox + 21, oy + 4 + earOffset, 1, 4, '#ff4d94');

    // 머리 외곽선 & 입체 하이라이트/음영
    px(ox + 5, oy + 11, 22, 13, '#141013');
    px(ox + 6, oy + 12, 20, 11, '#ffffff');
    px(ox + 7, oy + 12, 12, 2, '#f5f9ff'); // 정수리 광택
    dither(ox + 6, oy + 20, 20, 3, '#ffffff', '#dce8f5'); // 턱 밑 디더링 음영

    // 반짝이는 눈망울 & 볼터치 & 코
    px(ox + 10, oy + 15, 3, 4, '#141013');
    px(ox + 10, oy + 15, 1, 2, '#ffffff'); // 상단 광택
    px(ox + 12, oy + 17, 1, 1, '#90e0ef'); // 하단 반사광

    px(ox + 19, oy + 15, 3, 4, '#141013');
    px(ox + 19, oy + 15, 1, 2, '#ffffff');
    px(ox + 21, oy + 17, 1, 1, '#90e0ef');

    // 볼터치 그라데이션
    px(ox + 7, oy + 18, 3, 2, '#ff7eb9');
    px(ox + 7, oy + 18, 2, 1, '#ffb3d9');
    px(ox + 22, oy + 18, 3, 2, '#ff7eb9');
    px(ox + 23, oy + 18, 2, 1, '#ffb3d9');

    // 코 & 미소
    px(ox + 15, oy + 18, 2, 1, '#e63986');
    px(ox + 14, oy + 20, 1, 1, '#141013');
    px(ox + 17, oy + 20, 1, 1, '#141013');
    px(ox + 15, oy + 21, 2, 1, '#141013');

    // 몸통 & 레이스 트리밍 빨간 앞치마
    px(ox + 7, oy + 24, 18, 9, '#141013');
    px(ox + 8, oy + 25, 16, 7, '#d62839');
    px(ox + 9, oy + 25, 11, 3, '#ff4d5a'); // 앞치마 하이라이트
    px(ox + 10, oy + 25, 5, 1, '#ff858f');
    px(ox + 18, oy + 25, 6, 7, '#9e1924'); // 우측 그림자
    // 흰색 레이스 프릴
    px(ox + 9, oy + 30, 14, 2, '#ffffff');
    px(ox + 10, oy + 32, 2, 1, '#ffffff');
    px(ox + 15, oy + 32, 2, 1, '#ffffff');
    px(ox + 20, oy + 32, 2, 1, '#ffffff');

    // 두 발
    const footShift = jumping ? -2 : 0;
    px(ox + 8, oy + 33 + footShift, 6, 3, '#141013');
    px(ox + 9, oy + 34 + footShift, 4, 1, '#ffffff');
    px(ox + 18, oy + 33 - footShift, 6, 3, '#141013');
    px(ox + 19, oy + 34 - footShift, 4, 1, '#ffffff');
  }

  // 36x36 고밀도 케이크 카드 아이콘
  function initCardIcons() {
    const drawMini = (id, type) => {
      const c = document.getElementById(id);
      const g = c.getContext('2d');
      g.imageSmoothingEnabled = false;
      g.clearRect(0, 0, 36, 36);
      const r = (x, y, w, h, col) => { g.fillStyle = col; g.fillRect(x, y, w, h); };

      if (type === 'strawberry') {
        r(4, 28, 28, 3, '#141013');
        r(6, 29, 24, 1, '#d8e8fa');
        r(7, 15, 22, 13, '#141013');
        r(8, 16, 20, 11, '#fff5f8');
        r(8, 21, 20, 3, '#ff85b8');
        r(22, 16, 6, 11, '#f3dce6');
        // 딸기 & 크림
        r(14, 8, 8, 8, '#141013');
        r(15, 9, 6, 6, '#e63956');
        r(16, 9, 2, 2, '#ffffff');
        r(16, 12, 1, 1, '#ffd166');
        r(19, 11, 1, 1, '#ffd166');
      } else if (type === 'choco') {
        r(4, 28, 28, 3, '#141013');
        r(7, 14, 22, 14, '#141013');
        r(8, 15, 20, 12, '#7f4f3e');
        r(8, 15, 20, 5, '#3b1e14');
        r(9, 16, 8, 1, '#8c5846');
        r(11, 20, 3, 4, '#3b1e14');
        r(16, 20, 2, 2, '#3b1e14');
        r(21, 20, 3, 5, '#3b1e14');
        r(15, 11, 6, 4, '#141013');
        r(16, 12, 4, 2, '#ff85bc');
      } else {
        r(5, 28, 26, 3, '#141013');
        r(6, 18, 24, 10, '#141013');
        r(8, 14, 20, 14, '#141013');
        r(7, 19, 22, 8, '#9d4edd');
        r(9, 15, 18, 12, '#b565f2');
        r(10, 16, 6, 2, '#e0aaff');
        // 황금 고구마 단면 포인트
        r(15, 17, 11, 8, '#141013');
        r(16, 18, 9, 6, '#ffd166');
        r(17, 19, 6, 3, '#fff3b0');
      }
    };

    drawMini('iconStrawberry', 'strawberry');
    drawMini('iconChoco', 'choco');
    drawMini('iconSweetpotato', 'sweetpotato');
  }

  /* =====================================================================
     6. Scene 1 & 2: 파스텔 하늘 + 디더링 구름 + 광택 음표 + 설원 오두막
  ===================================================================== */
  function drawSkyAndField() {
    // 하늘 그라데이션 밴드 + 디더링 전환
    px(0, 0, W, 62, '#7ca6df');
    dither(0, 58, W, 8, '#7ca6df', '#9ec3f0');
    px(0, 66, W, 60, '#9ec3f0');

    // 다단계 셰이딩 뭉게구름
    clouds.forEach(c => {
      c.x += c.speed;
      if (c.x > W + 8) c.x = -c.w - 8;
      const cx = Math.round(c.x);
      const cy = Math.round(c.y);
      const cw = c.w;

      // 외곽선 & 하단 디더링 그림자
      px(cx + 2, cy + 5, cw - 4, 11, '#141013');
      px(cx + 8, cy, cw - 16, 6, '#141013');
      px(cx + 9, cy + 1, cw - 18, 5, '#ffffff');
      px(cx + 3, cy + 6, cw - 6, 9, '#ffffff');
      px(cx + 10, cy + 2, Math.floor((cw - 20) * 0.5), 2, '#f7fbff'); // 상단 하이라이트
      dither(cx + 3, cy + 12, cw - 6, 3, '#ffffff', '#b8d4f5');
    });

    // 반짝이는 2000s 광택 픽셀 음표
    notes.forEach(n => {
      const ny = Math.round(n.y + Math.sin(frame * 0.06 + n.phase) * 3);
      const nx = Math.round(n.x);
      // 검은 외곽선
      px(nx, ny, 7, 6, '#141013');
      px(nx + 5, ny - 9, 3, 10, '#141013');
      px(nx + 5, ny - 9, 7, 4, '#141013');
      // 컬러 채움 & 광택 하이라이트
      px(nx + 1, ny + 1, 5, 4, n.color);
      px(nx + 2, ny + 1, 2, 2, n.hi);
      px(nx + 6, ny - 8, 1, 8, n.color);
      px(nx + 6, ny - 8, 5, 2, n.hi);
      px(nx + 1, ny + 4, 4, 1, '#c94b86');
    });

    // 설원 언덕 & 미묘한 음영
    px(0, 122, W, 70, '#dcebfa');
    px(0, 126, W, 66, '#eef6ff');
    px(0, 130, W, 62, '#ffffff');
    dither(0, 124, W, 4, '#9ec3f0', '#dcebfa');

    // 전나무 2그루 (눈 쌓인 가지 & 다단계 초록 셰이딩)
    [22, 212].forEach(tx => {
      px(tx - 3, 118, 6, 9, '#141013');
      px(tx - 2, 119, 4, 7, '#6b4423');
      px(tx + 1, 119, 1, 7, '#462a14');

      // 3단 나뭇잎
      const tiers = [
        { y: 106, w: 24, h: 12 },
        { y: 95,  w: 18, h: 12 },
        { y: 85,  w: 12, h: 11 }
      ];
      tiers.forEach(t => {
        const half = Math.floor(t.w / 2);
        px(tx - half, t.y, t.w, t.h, '#141013');
        px(tx - half + 1, t.y + 1, t.w - 2, t.h - 2, '#2d7a53');
        px(tx - half + 1, t.y + 1, Math.floor((t.w - 2) * 0.55), t.h - 3, '#44ab77');
        // 눈 덮인 상단
        px(tx - half + 2, t.y + 1, t.w - 4, 2, '#ffffff');
      });
    });

    // 눈 덮인 통나무 오두막 (우측 중경)
    const hx = 152, hy = 82;
    // 굴뚝 & 피어오르는 연기
    px(hx + 34, hy - 5, 8, 13, '#141013');
    px(hx + 35, hy - 4, 6, 11, '#a64b3a');
    px(hx + 39, hy - 4, 2, 11, '#753023');
    const sm1 = hy - 11 - ((frame >> 2) % 6);
    const sm2 = hy - 18 - ((frame >> 3) % 6);
    px(hx + 36, sm1, 4, 4, '#ffffff');
    px(hx + 38, sm2, 5, 4, '#eef6ff');

    // 경사진 지붕 & 두툼한 눈 이불
    px(hx - 3, hy + 8, 52, 16, '#141013');
    px(hx - 1, hy + 9, 48, 13, '#8c4a27');
    px(hx + 22, hy + 9, 25, 13, '#633218');
    // 지붕 위 눈
    px(hx - 2, hy + 4, 50, 7, '#141013');
    px(hx - 1, hy + 5, 48, 5, '#ffffff');
    px(hx - 1, hy + 9, 48, 1, '#c8dff7');

    // 통나무 벽체 & 가로 결 디테일
    px(hx + 3, hy + 24, 42, 24, '#141013');
    px(hx + 4, hy + 25, 40, 22, '#c97a4b');
    for (let ly = hy + 29; ly < hy + 46; ly += 4) {
      px(hx + 4, ly, 40, 1, '#9e5830');
    }

    // 나무 문 & 따뜻한 노란 창문 2개
    px(hx + 9, hy + 31, 10, 16, '#141013');
    px(hx + 10, hy + 32, 8, 15, '#6b4423');
    px(hx + 16, hy + 39, 2, 2, '#ffd166'); // 문고리

    [24, 35].forEach(wx => {
      px(hx + wx, hy + 31, 8, 9, '#141013');
      px(hx + wx + 1, hy + 32, 6, 7, '#ffe66d');
      px(hx + wx + 1, hy + 32, 2, 2, '#fff9c4'); // 창문 하이라이트
      px(hx + wx + 3, hy + 32, 1, 7, '#8c4a27'); // 창살 세로
      px(hx + wx + 1, hy + 35, 6, 1, '#8c4a27'); // 창살 가로
    });

    // 발자국
    footprints.forEach(fp => {
      px(fp.x - 4, fp.y - 1, 2, 2, '#9ec3f0');
      px(fp.x + 2, fp.y + 1, 2, 2, '#9ec3f0');
    });
  }

  /* =====================================================================
     7. Scene 3 & 4: 아늑한 주방 & 레트로 미니 오븐
  ===================================================================== */
  function drawKitchenScene() {
    // 체크무늬 주방 벽지
    px(0, 0, W, H, '#ffe6f0');
    for (let y = 0; y < 138; y += 16) {
      for (let x = 0; x < W; x += 16) {
        if (((x + y) / 16) % 2 === 0) px(x, y, 16, 16, '#ffd1e3');
      }
    }

    // 상단 선반 & 작은 컵/병 디테일
    px(54, 24, 62, 4, '#141013');
    px(55, 25, 60, 2, '#c97a4b');
    px(62, 17, 6, 8, '#141013');
    px(63, 18, 4, 6, '#ffe66d');
    px(74, 19, 7, 6, '#141013');
    px(75, 20, 5, 4, '#ff85bc');

    // 핑크 레트로 냉장고 (좌측)
    px(12, 34, 42, 98, '#141013');
    px(14, 36, 38, 38, '#ff85bc');
    px(15, 37, 8, 35, '#ffb3d9'); // 냉장고 좌측 광택
    px(46, 48, 3, 14, '#141013');
    px(46, 49, 2, 12, '#ffffff');

    px(14, 76, 38, 54, '#ff6ba8');
    px(15, 77, 8, 51, '#ff9ec7');
    px(46, 90, 3, 16, '#141013');
    px(46, 91, 2, 14, '#ffffff');

    // 조리대
    px(0, 132, W, 60, '#141013');
    px(0, 135, W, 57, '#f5d0a9');
    px(0, 135, W, 3, '#ffe8cc');

    // 레트로 미니 오븐 (중앙)
    const ox = 74, oy = 60;
    px(ox, oy, 92, 72, '#141013');
    px(ox + 2, oy + 2, 88, 68, '#ffffff');
    px(ox + 22, oy + 68, 44, 2, '#d8e8fa');

    // 상단 제어 패널 & 다이얼 3개
    px(ox + 4, oy + 4, 84, 14, '#ff85bc');
    px(ox + 5, oy + 5, 82, 2, '#ffb3d9');
    [20, 46, 72].forEach(dx => {
      px(ox + dx - 3, oy + 8, 6, 6, '#141013');
      px(ox + dx - 2, oy + 9, 4, 4, '#ffffff');
      px(ox + dx, oy + 9, 1, 2, '#e63986');
    });

    // 오븐 유리창 & 열선
    const glassColor =
      scene === 'oven_baking' ? (frame % 10 < 5 ? '#ff7b39' : '#ffab40') :
      scene === 'oven_done' ? '#ffe082' : '#4a4e69';
    px(ox + 10, oy + 22, 72, 36, '#141013');
    px(ox + 12, oy + 24, 68, 32, glassColor);
    if (scene === 'oven_baking' || scene === 'oven_done') {
      px(ox + 14, oy + 26, 64, 2, '#fff3b0'); // 내부 따뜻한 빛
    }

    // 오븐 내부 반죽/케이크
    if (scene === 'oven_ready' || scene === 'oven_baking' || scene === 'oven_done') {
      const cakeColor = selectedCake === 'choco' ? '#6f3e22' : selectedCake === 'sweetpotato' ? '#f4c430' : '#ffb3c6';
      const h = scene === 'oven_done' ? 16 : 10;
      px(ox + 30, oy + 54 - h, 32, h, '#141013');
      px(ox + 31, oy + 55 - h, 30, h - 2, cakeColor);
    }

    // 굽기 게이지
    if (scene === 'oven_baking') {
      px(ox + 12, oy + 61, 68, 5, '#141013');
      px(ox + 13, oy + 62, Math.round(66 * (bakeProgress / 100)), 3, '#e63986');
    }

    // 우측 응원 토끼
    drawRabbit(204, 134, scene === 'oven_done' && (frame % 20 < 10));
  }

  /* =====================================================================
     8. Scene 5: JY Happy Birthday ♥ 2단 케이크 피날레
  ===================================================================== */
  function drawFinaleScene() {
    px(0, 0, W, H, '#ffeaf4');

    // 파스텔 반짝이 별빛
    for (let i = 0; i < 24; i++) {
      const sx = (i * 43 + ((frame >> 2) % 8)) % W;
      const sy = (i * 29) % 148;
      const col = i % 3 === 0 ? '#ff7eb9' : i % 3 === 1 ? '#ffd166' : '#ffffff';
      px(sx, sy, 2, 2, col);
      if (i % 6 === 0) {
        px(sx - 1, sy, 4, 1, col);
        px(sx, sy - 1, 1, 3, col);
      }
    }

    // 상단 토퍼 배너 (하단 CTA 바와 완전히 분리된 상단 y=12~42 영역 고정)
    px(22, 12, 196, 30, '#141013');
    px(24, 14, 192, 26, '#ffffff');
    px(26, 16, 188, 22, '#fff5fa');
    ctx.fillStyle = '#e63986';
    ctx.font = 'bold 15px DungGeunMo, monospace';
    ctx.textAlign = 'center';
    ctx.textBaseline = 'middle';
    ctx.fillText('JY Happy Birthday ♥', W / 2, 28);

    // 테이블
    px(0, 152, W, 40, '#141013');
    px(0, 155, W, 37, '#ffffff');
    px(0, 155, W, 3, '#f3f8ff');

    // 케이크 접시
    px(58, 146, 124, 8, '#141013');
    px(60, 147, 120, 6, '#e3f0ff');
    px(62, 148, 116, 2, '#ffffff');

    // 맛별 색상 팔레트
    const palette = {
      strawberry: { base: '#fff5f8', shade: '#f5dce6', cream: '#ff85bc', drip: '#e63986' },
      choco:      { base: '#7f4f3e', shade: '#593427', cream: '#4a281c', drip: '#2b150d' },
      sweetpotato:{ base: '#ffe885', shade: '#ebd065', cream: '#f4c430', drip: '#b565a7' }
    }[selectedCake];

    // 1단 (하단)
    px(68, 114, 104, 32, '#141013');
    px(70, 116, 100, 28, palette.base);
    px(142, 116, 28, 28, palette.shade);
    // 크림 물결
    px(70, 116, 100, 7, palette.cream);
    for (let dx = 74; dx < 164; dx += 12) {
      px(dx, 123, 6, 4, palette.drip);
      px(dx + 1, 127, 4, 2, palette.drip);
    }

    // 2단 (상단)
    px(84, 88, 72, 26, '#141013');
    px(86, 90, 68, 22, palette.base);
    px(134, 90, 20, 22, palette.shade);
    px(86, 90, 68, 6, palette.cream);
    for (let dx = 90; dx < 148; dx += 12) {
      px(dx, 96, 6, 3, palette.drip);
    }

    // 딸기 장식 3알
    [94, 117, 140].forEach(sx => {
      px(sx, 83, 7, 7, '#141013');
      px(sx + 1, 84, 5, 5, '#ff2a55');
      px(sx + 2, 85, 2, 2, '#ff9eb5');
      px(sx + 2, 82, 3, 2, '#2d7a53');
    });

    // 촛불 3개 (터치하여 하나씩 끄기 가능)
    [101, 119, 137].forEach((cx, idx) => {
      px(cx, 71, 4, 12, '#141013');
      px(cx + 1, 72, 2, 10, '#ffffff');
      px(cx + 1, 75, 2, 2, '#ff85bc');
      if (candlesLit[idx]) {
        const flicker = (frame + idx * 3) % 6 < 3 ? 0 : 1;
        px(cx, 63 + flicker, 4, 7, '#141013');
        px(cx + 1, 64 + flicker, 2, 5, '#ff9f1c');
        px(cx + 1, 65 + flicker, 1, 3, '#fff3b0');
      }
    });

    // 좌측 하단 축하 토끼
    drawRabbit(36, 156, frame % 24 < 12);
  }

  /* =====================================================================
     9. 파티클 (컨페티, 촛불 연기) & 메인 루프
  ===================================================================== */
  function addConfetti(cx, cy, count = 48) {
    const colors = ['#e63986', '#ffd166', '#4cc9f0', '#ff85bc', '#ffffff', '#52b788'];
    for (let i = 0; i < count; i++) {
      const ang = Math.random() * Math.PI * 2;
      const spd = 0.8 + Math.random() * 2.2;
      confetti.push({
        x: cx,
        y: cy,
        vx: Math.cos(ang) * spd,
        vy: Math.sin(ang) * spd - 1.4,
        col: colors[i % colors.length],
        sz: Math.random() > 0.45 ? 3 : 2,
        life: 70 + Math.random() * 35
      });
    }
  }

  function addCandleSmoke(cx, cy) {
    for (let i = 0; i < 8; i++) {
      smokeParticles.push({
        x: cx + (Math.random() - 0.5) * 3,
        y: cy,
        vx: (Math.random() - 0.5) * 0.3,
        vy: -0.4 - Math.random() * 0.25,
        life: 36 + Math.random() * 14
      });
    }
  }

  function updateAndDrawEffects() {
    for (let i = confetti.length - 1; i >= 0; i--) {
      const c = confetti[i];
      c.x += c.vx;
      c.y += c.vy;
      c.vy += 0.06;
      c.life--;
      if (c.life <= 0) confetti.splice(i, 1);
      else px(c.x, c.y, c.sz, c.sz, c.col);
    }

    for (let i = smokeParticles.length - 1; i >= 0; i--) {
      const s = smokeParticles[i];
      s.x += s.vx;
      s.y += s.vy;
      s.life--;
      if (s.life <= 0) smokeParticles.splice(i, 1);
      else px(s.x, s.y, 2, 2, '#ffffff');
    }
  }

  function loop() {
    frame++;
    ctx.clearRect(0, 0, W, H);

    if (scene === 'intro' || scene === 'walk') {
      drawSkyAndField();

      if (isJumping) {
        jumpProgress += 0.045;
        if (jumpProgress >= 1) {
          jumpProgress = 1;
          isJumping = false;
          rabbitX = targetX;
          rabbitY = targetY;

          // 3번째 점프 완료 후 오두막 앞 1.4초 여유 대기
          if (walkStep === 3) {
            updateCTA();
            setTimeout(() => {
              if (scene === 'walk' && walkStep === 3) {
                scene = 'select';
                updateCTA();
              }
            }, 1400);
          } else {
            updateCTA();
          }
        } else {
          const arc = Math.sin(jumpProgress * Math.PI) * 20;
          rabbitX = startX + (targetX - startX) * jumpProgress;
          rabbitY = startY + (targetY - startY) * jumpProgress - arc;
        }
      }

      drawRabbit(rabbitX, rabbitY, isJumping);

      // 눈 내림
      snows.forEach(s => {
        s.y += s.vy;
        s.x += Math.sin(frame * 0.03 + s.drift) * 0.18;
        if (s.y > H) s.y = 0;
        if (s.x < 0) s.x = W;
        if (s.x > W) s.x = 0;
        px(s.x, s.y, s.s, s.s, '#ffffff');
      });

    } else if (scene === 'select' || scene === 'oven_ready' || scene === 'oven_baking' || scene === 'oven_done') {
      if (scene === 'oven_baking') {
        bakeProgress += 0.85;
        if (bakeProgress >= 100) {
          bakeProgress = 100;
          scene = 'oven_done';
          playOvenDoneSfx();
          updateCTA();
        }
      }
      drawKitchenScene();

    } else if (scene === 'finale') {
      drawFinaleScene();
    }

    updateAndDrawEffects();
    requestAnimationFrame(loop);
  }

  window.onload = function () {
    initCardIcons();
    updateCTA();
    loop();
  };
</script>
</body>
</html>
