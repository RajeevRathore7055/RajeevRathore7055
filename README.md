<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#050308"/>
      <stop offset="50%" stop-color="#0b0713"/>
      <stop offset="100%" stop-color="#0a0510"/>
    </linearGradient>
    <radialGradient id="glowPurple" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#9d4edd" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#9d4edd" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowOrange" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff8c42" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#ff8c42" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowRed" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff3864" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#ff3864" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c77dff"/>
      <stop offset="45%" stop-color="#ff8c42"/>
      <stop offset="100%" stop-color="#ff3864"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#9d4edd" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#ff3864" stop-opacity="0.15"/>
    </linearGradient>
    <filter id="softBlur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6"/>
    </filter>
  </defs>

  <rect width="1200" height="320" fill="url(#bg)"/>
  <circle cx="140" cy="80" r="180" fill="url(#glowPurple)"/>
  <circle cx="1060" cy="260" r="200" fill="url(#glowOrange)"/>
  <circle cx="900" cy="60" r="150" fill="url(#glowRed)"/>

  <!-- neural network mesh -->
  <g stroke="url(#lineGrad)" stroke-width="1" opacity="0.55">
    <line x1="60" y1="60" x2="230" y2="120"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite"/></line>
    <line x1="60" y1="150" x2="230" y2="120"><animate attributeName="opacity" values="0.7;0.15;0.7" dur="3.2s" repeatCount="indefinite"/></line>
    <line x1="60" y1="240" x2="230" y2="180"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="5s" repeatCount="indefinite"/></line>
    <line x1="230" y1="120" x2="400" y2="70"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="3.6s" repeatCount="indefinite"/></line>
    <line x1="230" y1="120" x2="400" y2="160"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="4.4s" repeatCount="indefinite"/></line>
    <line x1="230" y1="180" x2="400" y2="160"><animate attributeName="opacity" values="0.6;0.15;0.6" dur="2.8s" repeatCount="indefinite"/></line>
    <line x1="230" y1="180" x2="400" y2="230"><animate attributeName="opacity" values="0.25;0.85;0.25" dur="3.9s" repeatCount="indefinite"/></line>
    <line x1="400" y1="70" x2="560" y2="120"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="4.1s" repeatCount="indefinite"/></line>
    <line x1="400" y1="160" x2="560" y2="120"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3.3s" repeatCount="indefinite"/></line>
    <line x1="400" y1="230" x2="560" y2="180"><animate attributeName="opacity" values="0.8;0.25;0.8" dur="4.7s" repeatCount="indefinite"/></line>
  </g>

  <g fill="#c77dff">
    <circle cx="60" cy="60" r="3.5"/>
    <circle cx="60" cy="150" r="3.5"/>
    <circle cx="60" cy="240" r="3.5"/>
    <circle cx="230" cy="120" r="4.5"/>
    <circle cx="230" cy="180" r="4.5"/>
  </g>
  <g fill="#ff8c42">
    <circle cx="400" cy="70" r="4"/>
    <circle cx="400" cy="160" r="4"/>
    <circle cx="400" cy="230" r="4"/>
  </g>
  <g fill="#ff3864">
    <circle cx="560" cy="120" r="4.5"/>
    <circle cx="560" cy="180" r="4.5"/>
  </g>

  <!-- right side floating math / code glyphs -->
  <g font-family="Menlo, Consolas, monospace" fill="#9d4edd" opacity="0.35" font-size="15">
    <text x="720" y="55">∑ P(θ|X)</text>
    <text x="850" y="95">f(x) = Wx + b</text>
    <text x="980" y="45">def forward():</text>
    <text x="760" y="140">∇L</text>
    <text x="900" y="180">async fastapi</text>
    <text x="1020" y="130">λ e⁻ˣ</text>
    <text x="740" y="230">agent.invoke()</text>
    <text x="880" y="265">O(n log n)</text>
    <text x="1010" y="230">AWS · Docker</text>
  </g>

  <!-- headline -->
  <text x="60" y="185" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="46" font-weight="700" fill="url(#textGrad)">
    RAJEEV RATHORE
  </text>
  <text x="61" y="185" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="46" font-weight="700" fill="url(#textGrad)" opacity="0.3" filter="url(#softBlur)">
    RAJEEV RATHORE
  </text>
  <text x="60" y="220" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="16.5" letter-spacing="2.5" fill="#e6d9ff" opacity="0.9">
    AI RESEARCH ENGINEER  ·  MACHINE LEARNING  ·  MATHEMATICS  ·  AGENTIC SYSTEMS
  </text>

  <rect x="60" y="240" width="440" height="1.4" fill="url(#textGrad)" opacity="0.7"/>
</svg>
