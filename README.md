<svg xmlns="http://www.w3.org/2000/svg" width="1500" height="500" viewBox="0 0 1500 500" fill="none" role="img" aria-label="Java Backend Developer — Spring Boot, Microservices, Cloud-Native">
  <defs>
    <!-- ── Background gradient ───────────────────────────── -->
    <linearGradient id="bg" x1="0" y1="0" x2="1500" y2="500" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#0d1117"/>
      <stop offset="1" stop-color="#1a1f36"/>
    </linearGradient>

    <!-- ── Avatar glow ───────────────────────────────────── -->
    <radialGradient id="glow" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                    gradientTransform="translate(170 250) scale(150)">
      <stop offset="0"    stop-color="#58a6ff" stop-opacity="0.45"/>
      <stop offset="0.55" stop-color="#58a6ff" stop-opacity="0.12"/>
      <stop offset="1"    stop-color="#58a6ff" stop-opacity="0"/>
    </radialGradient>

    <!-- ── Avatar ring gradient ──────────────────────────── -->
    <linearGradient id="ring" x1="86" y1="164" x2="254" y2="336" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#58a6ff"/>
      <stop offset="1" stop-color="#1f6feb"/>
    </linearGradient>

    <!-- ── Underline accent ──────────────────────────────── -->
    <linearGradient id="accent" x1="312" y1="0" x2="404" y2="0" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#58a6ff"/>
      <stop offset="1" stop-color="#1f6feb" stop-opacity="0"/>
    </linearGradient>

    <!-- ── Circuit board pattern (10% opacity) ───────────── -->
    <pattern id="circuit" width="140" height="140" patternUnits="userSpaceOnUse">
      <g stroke="#58a6ff" stroke-width="1" fill="none" opacity="0.10">
        <path d="M12 12h58v58h58"/>
        <path d="M12 128h34V82"/>
        <path d="M128 12v40"/>
        <path d="M70 70v22"/>
        <circle cx="70"  cy="12"  r="3.5" fill="#58a6ff" stroke="none"/>
        <circle cx="12"  cy="128" r="3.5" fill="#58a6ff" stroke="none"/>
        <circle cx="128" cy="52"  r="3.5" fill="#58a6ff" stroke="none"/>
        <circle cx="70"  cy="92"  r="3.5" fill="#58a6ff" stroke="none"/>
      </g>
    </pattern>

    <!-- ── Avatar clip ───────────────────────────────────── -->
    <clipPath id="avatarClip">
      <circle cx="170" cy="250" r="82"/>
    </clipPath>
  </defs>

  <!-- ══════════ BACKGROUND ══════════ -->
  <rect width="1500" height="500" fill="url(#bg)"/>
  <rect width="1500" height="500" fill="url(#circuit)"/>

  <!-- ══════════ LEFT — AVATAR ══════════ -->
  <circle cx="170" cy="250" r="150" fill="url(#glow)"/>
  <circle cx="170" cy="250" r="94" fill="none" stroke="#58a6ff" stroke-opacity="0.22" stroke-width="1"/>
  <circle cx="170" cy="250" r="86" fill="#161b22"/>

  <g clip-path="url(#avatarClip)">
    <!-- ░░ PLACEHOLDER — swap for your photo (see notes below) ░░ -->
    <circle cx="170" cy="224" r="30" fill="#30363d"/>
    <path d="M110 342a60 60 0 0 1 120 0z" fill="#30363d"/>
  </g>

  <circle cx="170" cy="250" r="84" fill="none" stroke="url(#ring)" stroke-width="3"/>

  <!-- ══════════ CENTER — TEXT ══════════ -->
  <g font-family="Inter, 'Segoe UI', -apple-system, 'Helvetica Neue', Arial, sans-serif"
     text-rendering="geometricPrecision">
    <text x="312" y="242" font-size="54" font-weight="700" fill="#ffffff" letter-spacing="-0.6">
      Java Backend Developer
    </text>
    <text x="314" y="292" font-size="24" font-weight="400" fill="#8b949e" letter-spacing="1.4">
      Spring Boot | Microservices | Cloud-Native
    </text>
    <rect x="314" y="310" width="90" height="4" rx="2" fill="url(#accent)"/>
  </g>

  <!-- ══════════ RIGHT — TECH ICONS ══════════ -->

  <!-- 1. Java ─────────────────────────────── -->
  <g transform="translate(1008,228)">
    <rect x="-6" y="-6" width="56" height="56" rx="14" fill="#ffffff" fill-opacity="0.03"
          stroke="#58a6ff" stroke-opacity="0.10"/>
    <path d="M15 6c3 3 3 5 0 8s-3 5 0 8"   stroke="#f89820" stroke-width="2.4" stroke-linecap="round" fill="none"/>
    <path d="M26 6c3 3 3 5 0 8s-3 5 0 8"   stroke="#f89820" stroke-width="2.4" stroke-linecap="round" fill="none"/>
    <path d="M7 20H34L31.4 35.4A4 4 0 0 1 27.5 39H16.5A4 4 0 0 1 12.6 35.4Z" fill="#f89820"/>
    <path d="M33.5 23.5c4.2 0 6.4 2.6 5.2 6.2-1.1 3.3-4 4.6-6.6 3.9"
          stroke="#f89820" stroke-width="2.6" stroke-linecap="round" fill="none"/>
  </g>

  <!-- 2. Spring Boot ──────────────────────── -->
  <g transform="translate(1080,228)">
    <rect x="-6" y="-6" width="56" height="56" rx="14" fill="#ffffff" fill-opacity="0.03"
          stroke="#58a6ff" stroke-opacity="0.10"/>
    <g fill="#6DB33F">
      <circle cx="22" cy="13" r="9.5"/>
      <circle cx="13" cy="26" r="9.5"/>
      <circle cx="31" cy="26" r="9.5"/>
      <rect x="20.5" y="30" width="3" height="12" rx="1.5"/>
    </g>
  </g>

  <!-- 3. Docker ───────────────────────────── -->
  <g transform="translate(1152,228)">
    <rect x="-6" y="-6" width="56" height="56" rx="14" fill="#ffffff" fill-opacity="0.03"
          stroke="#58a6ff" stroke-opacity="0.10"/>
    <g fill="#2496ED">
      <rect x="12" y="9"  width="6" height="6" rx="1"/>
      <rect x="19" y="9"  width="6" height="6" rx="1"/>
      <rect x="26" y="9"  width="6" height="6" rx="1"/>
      <rect x="12" y="16" width="6" height="6" rx="1"/>
      <rect x="19" y="16" width="6" height="6" rx="1"/>
      <rect x="26" y="16" width="6" height="6" rx="1"/>
      <rect x="33" y="16" width="6" height="6" rx="1"/>
      <path d="M6 24h34v5.5A8.5 8.5 0 0 1 31.5 38h-17A8.5 8.5 0 0 1 6 29.5Z"/>
      <path d="M6 27l-5-3.5v9z"/>
    </g>
  </g>

  <!-- 4. Kubernetes ───────────────────────── -->
  <g transform="translate(1224,228)">
    <rect x="-6" y="-6" width="56" height="56" rx="14" fill="#ffffff" fill-opacity="0.03"
          stroke="#58a6ff" stroke-opacity="0.10"/>
    <circle cx="22" cy="22" r="15" fill="none" stroke="#326CE5" stroke-width="2.4"/>
    <circle cx="22" cy="22" r="4.5" fill="#326CE5"/>
    <g stroke="#326CE5" stroke-width="2.2" stroke-linecap="round" fill="none">
      <path d="M22 12v-5"/>
      <path d="M30.7 17l4.3-2.5"/>
      <path d="M30.7 27l4.3 2.5"/>
      <path d="M22 32v5"/>
      <path d="M13.3 27L9 29.5"/>
      <path d="M13.3 17L9 14.5"/>
    </g>
  </g>

  <!-- 5. PostgreSQL ───────────────────────── -->
  <g transform="translate(1296,228)">
    <rect x="-6" y="-6" width="56" height="56" rx="14" fill="#ffffff" fill-opacity="0.03"
          stroke="#58a6ff" stroke-opacity="0.10"/>
    <circle cx="13" cy="20" r="8.5" fill="#336791"/>
    <circle cx="31" cy="20" r="8.5" fill="#336791"/>
    <ellipse cx="22" cy="21" rx="11.5" ry="13" fill="#3d7ab8"/>
    <path d="M19.5 28h5v9a2.5 2.5 0 0 1-5 0z" fill="#3d7ab8"/>
    <circle cx="16.5" cy="18" r="2" fill="#0d1117"/>
    <circle cx="27.5" cy="18" r="2" fill="#0d1117"/>
  </g>

  <!-- 6. Redis ────────────────────────────── -->
  <g transform="translate(1368,228)">
    <rect x="-6" y="-6" width="56" height="56" rx="14" fill="#ffffff" fill-opacity="0.03"
          stroke="#58a6ff" stroke-opacity="0.10"/>
    <path d="M26 3L9 26h10L15 43l20-24H25z" fill="#DC382D"/>
  </g>
</svg>
