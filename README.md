<svg width="1200" height="380" viewBox="0 0 1200 380" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0F172A"/>
      <stop offset="100%" stop-color="#111827"/>
    </linearGradient>

    <!-- Blue glow gradients -->
    <radialGradient id="glowBlue1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#3B82F6" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#3B82F6" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowBlue2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#6366F1" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#6366F1" stop-opacity="0"/>
    </radialGradient>

    <!-- Monogram gradient -->
    <linearGradient id="monoGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#60A5FA"/>
      <stop offset="100%" stop-color="#6366F1"/>
    </linearGradient>

    <!-- Glass panel gradient -->
    <linearGradient id="glassGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0.02"/>
    </linearGradient>

    <!-- Chip gradient -->
    <linearGradient id="chipGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1E293B"/>
      <stop offset="100%" stop-color="#1A2333"/>
    </linearGradient>

    <filter id="blurFilter" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="40"/>
    </filter>

    <clipPath id="roundedClip">
      <rect x="0" y="0" width="1200" height="380" rx="24"/>
    </clipPath>
  </defs>

  <g clip-path="url(#roundedClip)">
    <!-- Background -->
    <rect width="1200" height="380" fill="url(#bgGrad)"/>

    <!-- Glow accents -->
    <circle cx="1020" cy="60" r="220" fill="url(#glowBlue1)" filter="url(#blurFilter)"/>
    <circle cx="120" cy="360" r="200" fill="url(#glowBlue2)" filter="url(#blurFilter)"/>

    <!-- Faint code snippet background -->
    <g font-family="'JetBrains Mono','Fira Code',monospace" font-size="13" fill="#3B82F6" opacity="0.09">
      <text x="640" y="40">const engineer = {</text>
      <text x="660" y="62">name: "Harsh Vekariya",</text>
      <text x="660" y="84">role: "Software Engineer",</text>
      <text x="660" y="106">stack: ["React", "Node.js", "TypeScript"],</text>
      <text x="660" y="128">focus: "scalable systems",</text>
      <text x="640" y="150">};</text>
      <text x="640" y="190">function build(idea) {</text>
      <text x="660" y="212">return ship(idea).withCare();</text>
      <text x="640" y="234">}</text>
      <text x="640" y="270">export default engineer;</text>
      <text x="640" y="300">// clean code. reliable systems.</text>
    </g>

    <!-- Subtle grid lines -->
    <g stroke="#1E293B" stroke-width="1" opacity="0.4">
      <line x1="0" y1="379" x2="1200" y2="379"/>
      <line x1="0" y1="1" x2="1200" y2="1"/>
    </g>

    <!-- Glass panel -->
    <rect x="48" y="48" width="620" height="284" rx="20" fill="url(#glassGrad)" stroke="#FFFFFF" stroke-opacity="0.08" stroke-width="1"/>

    <!-- HV Monogram -->
    <circle cx="112" cy="120" r="34" fill="none" stroke="url(#monoGrad)" stroke-width="1.5" opacity="0.6"/>
    <circle cx="112" cy="120" r="28" fill="#0B1220" stroke="url(#monoGrad)" stroke-width="1.5"/>
    <text x="112" y="129" font-family="'Inter','Segoe UI',sans-serif" font-size="20" font-weight="700" fill="url(#monoGrad)" text-anchor="middle">HV</text>

    <!-- Name -->
    <text x="164" y="112" font-family="'Inter','Segoe UI',sans-serif" font-size="34" font-weight="700" fill="#F8FAFC">Harsh Vekariya</text>

    <!-- Subtitle -->
    <text x="164" y="140" font-family="'Inter','Segoe UI',sans-serif" font-size="16" font-weight="500" fill="#94A3B8">Software Engineer &#183; Full Stack &#183; Data Science</text>

    <!-- Divider -->
    <line x1="80" y1="176" x2="636" y2="176" stroke="#1E293B" stroke-width="1"/>

    <!-- Description -->
    <text x="80" y="206" font-family="'Inter','Segoe UI',sans-serif" font-size="14" fill="#CBD5E1">Building scalable products and clean, maintainable</text>
    <text x="80" y="228" font-family="'Inter','Segoe UI',sans-serif" font-size="14" fill="#CBD5E1">systems with modern web technologies.</text>

    <!-- Tech chips -->
    <g font-family="'JetBrains Mono','Fira Code',monospace" font-size="12.5" font-weight="500">
      <!-- React -->
      <rect x="80" y="256" width="70" height="30" rx="15" fill="url(#chipGrad)" stroke="#334155" stroke-width="1"/>
      <text x="115" y="275" text-anchor="middle" fill="#61DAFB">React</text>

      <!-- Next.js -->
      <rect x="160" y="256" width="82" height="30" rx="15" fill="url(#chipGrad)" stroke="#334155" stroke-width="1"/>
      <text x="201" y="275" text-anchor="middle" fill="#F8FAFC">Next.js</text>

      <!-- Node.js -->
      <rect x="252" y="256" width="86" height="30" rx="15" fill="url(#chipGrad)" stroke="#334155" stroke-width="1"/>
      <text x="295" y="275" text-anchor="middle" fill="#8CC84B">Node.js</text>

      <!-- Firebase -->
      <rect x="348" y="256" width="90" height="30" rx="15" fill="url(#chipGrad)" stroke="#334155" stroke-width="1"/>
      <text x="393" y="275" text-anchor="middle" fill="#FFA000">Firebase</text>

      <!-- TypeScript -->
      <rect x="448" y="256" width="106" height="30" rx="15" fill="url(#chipGrad)" stroke="#334155" stroke-width="1"/>
      <text x="501" y="275" text-anchor="middle" fill="#3178C6">TypeScript</text>
    </g>
  </g>

  <!-- Outer border -->
  <rect x="0.5" y="0.5" width="1199" height="379" rx="24" fill="none" stroke="#1E293B" stroke-width="1"/>
</svg>
