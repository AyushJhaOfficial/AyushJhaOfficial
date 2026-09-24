<svg xmlns="http://www.w3.org/2000/svg" width="1500" height="500" viewBox="0 0 1500 500" fill="none">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1500" y2="500" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#0d1117"/>
      <stop offset="1" stop-color="#1a1f36"/>
    </linearGradient>

    <radialGradient id="light" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(300 150) scale(800)">
      <stop offset="0" stop-color="#2a3446" stop-opacity="0.4"/>
      <stop offset="1" stop-color="#2a3446" stop-opacity="0"/>
    </radialGradient>

    <filter id="neu-out" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="6" dy="6" stdDeviation="6" flood-color="#0a0d13" flood-opacity="0.8"/>
      <feDropShadow dx="-6" dy="-6" stdDeviation="6" flood-color="#2b3346" flood-opacity="0.6"/>
    </filter>

    <filter id="neu-out-sm" x="-30%" y="-30%" width="160%" height="160%">
      <feDropShadow dx="3" dy="3" stdDeviation="3" flood-color="#0a0d13" flood-opacity="0.8"/>
      <feDropShadow dx="-3" dy="-3" stdDeviation="3" flood-color="#2b3346" flood-opacity="0.6"/>
    </filter>

    <filter id="text-shadow" x="-10%" y="-10%" width="120%" height="120%">
      <feDropShadow dx="1" dy="1" stdDeviation="1" flood-color="#000000" flood-opacity="0.6"/>
    </filter>

    <clipPath id="avatarClip">
      <circle cx="170" cy="250" r="90"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="1500" height="500" fill="url(#bg)"/>
  <rect width="1500" height="500" fill="url(#light)"/>

  <!-- Avatar -->
  <circle cx="170" cy="250" r="110" fill="#1e2430" filter="url(#neu-out)"/>
  <circle cx="170" cy="250" r="92" fill="#151a22"/>
  <g clip-path="url(#avatarClip)">
    <circle cx="170" cy="220" r="32" fill="#30363d"/>
    <path d="M110 340a60 60 0 0 1 120 0z" fill="#30363d"/>
  </g>
  <circle cx="170" cy="250" r="90" fill="none" stroke="#58a6ff" stroke-width="2" opacity="0.6"/>

  <!-- Center Panel -->
  <rect x="310" y="170" width="650" height="160" rx="30" fill="#1e2430" filter="url(#neu-out)"/>
  <text x="635" y="235" text-anchor="middle" font-family="Inter, 'Segoe UI', sans-serif" font-size="48" font-weight="700" fill="#e6edf3" filter="url(#text-shadow)">Java Backend Developer</text>
  <text x="635" y="285" text-anchor="middle" font-family="Inter, 'Segoe UI', sans-serif" font-size="22" font-weight="400" fill="#8b949e" letter-spacing="1.2">Spring Boot | Microservices | Cloud-Native</text>

  <!-- Java -->
  <g transform="translate(1030,250)">
    <rect x="-30" y="-30" width="60" height="60" rx="16" fill="#1e2430" filter="url(#neu-out-sm)"/>
    <g transform="translate(-18,-18)">
      <path d="M15 6c3 3 3 5 0 8s-3 5 0 8" stroke="#f89820" stroke-width="2.4" stroke-linecap="round" fill="none"/>
      <path d="M26 6c3 3 3 5 0 8s-3 5 0 8" stroke="#f89820" stroke-width="2.4" stroke-linecap="round" fill="none"/>
      <path d="M7 20H34L31.4 35.4A4 4 0 0 1 27.5 39H16.5A4 4 0 0 1 12.6 35.4Z" fill="#f89820"/>
      <path d="M33.5 23.5c4.2 0 6.4 2.6 5.2 6.2-1.1 3.3-4 4.6-6.6 3.9" stroke="#f89820" stroke-width="2.6" stroke-linecap="round" fill="none"/>
    </g>
  </g>

  <!-- Spring Boot -->
  <g transform="translate(1105,250)">
    <rect x="-30" y="-30" width="60" height="60" rx="16" fill="#1e2430" filter="url(#neu-out-sm)"/>
    <g transform="translate(-22,-22)" fill="#6DB33F">
      <circle cx="22" cy="13" r="9.5"/>
      <circle cx="13" cy="26" r="9.5"/>
      <circle cx="31" cy="26" r="9.5"/>
      <rect x="20.5" y="30" width="3" height="12" rx="1.5"/>
    </g>
  </g>

  <!-- Docker -->
  <g transform="translate(1180,250)">
    <rect x="-30" y="-30" width="60" height="60" rx="16" fill="#1e2430" filter="url(#neu-out-sm)"/>
    <g transform="translate(-22,-22)" fill="#2496ED">
      <rect x="12" y="9" width="6" height="6" rx="1"/>
      <rect x="19" y="9" width="6" height="6" rx="1"/>
      <rect x="26" y="9" width="6" height="6" rx="1"/>
      <rect x="12" y="16" width="6" height="6" rx="1"/>
      <rect x="19" y="16" width="6" height="6" rx="1"/>
      <rect x="26" y="16" width="6" height="6" rx="1"/>
      <rect x="33" y="16" width="6" height="6" rx="1"/>
      <path d="M6 24h34v5.5A8.5 8.5 0 0 1 31.5 38h-17A8.5 8.5 0 0 1 6 29.5Z"/>
      <path d="M6 27l-5-3.5v9z"/>
    </g>
  </g>

  <!-- Kubernetes -->
  <g transform="translate(1255,250)">
    <rect x="-30" y="-30" width="60" height="60" rx="16" fill="#1e2430" filter="url(#neu-out-sm)"/>
    <g transform="translate(-22,-22)">
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
  </g>

  <!-- PostgreSQL -->
  <g transform="translate(1330,250)">
    <rect x="-30" y="-30" width="60" height="60" rx="16" fill="#1e2430" filter="url(#neu-out-sm)"/>
    <g transform="translate(-22,-22)">
      <circle cx="13" cy="20" r="8.5" fill="#336791"/>
      <circle cx="31" cy="20" r="8.5" fill="#336791"/>
      <ellipse cx="22" cy="21" rx="11.5" ry="13" fill="#3d7ab8"/>
      <path d="M19.5 28h5v9a2.5 2.5 0 0 1-5 0z" fill="#3d7ab8"/>
      <circle cx="16.5" cy="18" r="2" fill="#0d1117"/>
      <circle cx="27.5" cy="18" r="2" fill="#0d1117"/>
    </g>
  </g>

  <!-- Redis -->
  <g transform="translate(1405,250)">
    <rect x="-30" y="-30" width="60" height="60" rx="16" fill="#1e2430" filter="url(#neu-out-sm)"/>
    <g transform="translate(-22,-22)">
      <path d="M26 3L9 26h10L15 43l20-24H25z" fill="#DC382D"/>
    </g>
  </g>
</svg>
