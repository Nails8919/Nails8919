
<!-- File: assets/banner-animated.svg -->
<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Lisa Mapp — Network Tech | IoT | Docker">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0F2027"/>
      <stop offset="50%" stop-color="#203A43"/>
      <stop offset="100%" stop-color="#2C5364"/>
    </linearGradient>

    <linearGradient id="wave" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00C9A7"/>
      <stop offset="100%" stop-color="#1E90FF"/>
    </linearGradient>

    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="300" fill="url(#bg)"/>

  <!-- Animated wave at bottom -->
  <path id="wavePath" fill="url(#wave)" opacity="0.85">
    <!-- Initial d (path shape) -->
    <animate attributeName="d" dur="6s" repeatCount="indefinite"
      values="
        M0,240 C300,220 450,270 600,250 C750,230 900,280 1200,260 L1200,300 L0,300 Z;
        M0,245 C300,265 450,225 600,245 C750,265 900,225 1200,245 L1200,300 L0,300 Z;
        M0,240 C300,220 450,270 600,250 C750,230 900,280 1200,260 L1200,300 L0,300 Z
      "
    />
  </path>

  <!-- Title -->
  <text x="50%" y="45%" text-anchor="middle" fill="#E6F7FF" font-size="64" font-family="Inter, Segoe UI, Roboto, Helvetica, Arial, sans-serif" filter="url(#glow)">
    Lisa Mapp
  </text>

  <!-- Subtitle -->
  <text x="50%" y="65%" text-anchor="middle" fill="#CDE8FF" font-size="24" font-family="Inter, Segoe UI, Roboto, Helvetica, Arial, sans-serif" letter-spacing="0.5">
    Network Tech • IoT • Docker
  </text>
</svg>
