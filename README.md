<p align="center">
  <svg width="400" height="380" viewBox="0 0 400 380" xmlns="http://www.w3.org/2000/svg" style="background-color: #0d1117; border-radius: 12px; border: 1px solid #30363d;">
    <style>
      .grid { stroke: #30363d; stroke-width: 1; fill: none; }
      .axis { stroke: #484f58; stroke-width: 1; }
      .label { fill: #c9d1d9; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; font-size: 13px; font-weight: 600; text-anchor: middle; }
      .title { fill: #58a6ff; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: bold; text-anchor: middle; }
      .web-poly { fill: rgba(56, 139, 253, 0.35); stroke: #58a6ff; stroke-width: 2.5; }
      .point { fill: #58a6ff; stroke: #0d1117; stroke-width: 2; }
    </style>

    <!-- Título -->
    <text x="200" y="32" class="title">Teia de Habilidades</text>

    <!-- Teia de Fundo (Graus de nível) -->
    <polygon points="200,80 304,140 304,260 200,320 96,260 96,140" class="grid" />
    <polygon points="200,110 278,155 278,245 200,290 122,245 122,155" class="grid" />
    <polygon points="200,140 252,170 252,230 200,260 148,230 148,170" class="grid" />
    <polygon points="200,170 226,185 226,215 200,230 174,215 174,185" class="grid" />

    <!-- Eixos -->
    <line x1="200" y1="200" x2="200" y2="80" class="axis" />
    <line x1="200" y1="200" x2="304" y2="140" class="axis" />
    <line x1="200" y1="200" x2="304" y2="260" class="axis" />
    <line x1="200" y1="200" x2="200" y2="320" class="axis" />
    <line x1="200" y1="200" x2="96" y2="260" class="axis" />
    <line x1="200" y1="200" x2="96" y2="140" class="axis" />

    <!-- Polígono das Habilidades (JavaScript, HTML, CSS, Node.js, Python, Git) -->
    <!-- Níveis ajustados: JS 85%, HTML 85%, CSS 80%, Node 80%, Python 60%, Git 75% -->
    <polygon points="200,98 288,149 283,248 200,296 138,236 122,155" class="web-poly" />

    <!-- Pontos nos Vértices -->
    <circle cx="200" cy="98" r="4.5" class="point" />
    <circle cx="288" cy="149" r="4.5" class="point" />
    <circle cx="283" cy="248" r="4.5" class="point" />
    <circle cx="200" cy="296" r="4.5" class="point" />
    <circle cx="138" cy="236" r="4.5" class="point" />
    <circle cx="122" cy="155" r="4.5" class="point" />

    <!-- Rótulos das Linguagens -->
    <text x="200" y="65" class="label">JavaScript</text>
    <text x="325" y="135" class="label">HTML5</text>
    <text x="325" y="275" class="label">CSS3</text>
    <text x="200" y="342" class="label">Node.js</text>
    <text x="75" y="275" class="label">Python</text>
    <text x="75" y="135" class="label">Git & GitHub</text>
  </svg>
</p>
