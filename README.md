```html
<!-- Typing Terminal Animation -->
<svg width="100%" height="260" viewBox="0 0 800 260" xmlns="http://www.w3.org/2000/svg">
  <style>
    .bg { fill: #0d1117; }
    .text { fill: #39ff14; font-family: monospace; font-size: 16px; }
    .cursor {
      animation: blink 1s steps(1) infinite;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>

  <rect class="bg" width="800" height="260" rx="12"/>

  <text class="text" x="20" y="40">
    <tspan>┌──(</tspan><tspan fill="#ff5555">whitedeathkl23</tspan><tspan>)─[~/root]</tspan>
  </text>

  <text class="text" x="20" y="70">
    <tspan>$ whoami</tspan>
  </text>

  <text class="text" x="20" y="100">
    <tspan>
      <animate attributeName="opacity" from="0" to="1" dur="1s" begin="0.5s" fill="freeze"/>
      Ethical Hacker | Red Team ⚔️
    </tspan>
  </text>

  <text class="text" x="20" y="130">
    <tspan>
      <animate attributeName="opacity" from="0" to="1" dur="1s" begin="1.5s" fill="freeze"/>
      Bug Bounty Hunter 🐞
    </tspan>
  </text>

  <text class="text" x="20" y="160">
    <tspan>
      <animate attributeName="opacity" from="0" to="1" dur="1s" begin="2.5s" fill="freeze"/>
      Kali Linux | Pentesting | VAPT 🛡️
    </tspan>
  </text>

  <text class="text" x="20" y="190">
    <tspan>
      <animate attributeName="opacity" from="0" to="1" dur="1s" begin="3.5s" fill="freeze"/>
      HackerOne • Bugcrowd 🎯
    </tspan>
  </text>

  <text class="text cursor" x="20" y="220">█</text>
</svg>
```
