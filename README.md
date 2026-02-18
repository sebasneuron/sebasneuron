<p align="center">
<svg width="800" height="140" viewBox="0 0 800 140" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Blue beam -->
  <line x1="0" y1="70" x2="0" y2="70"
        stroke="#00eaff"
        stroke-width="8"
        filter="url(#glow)">
    <animate attributeName="x2"
             from="0" to="400"
             dur="1s"
             repeatCount="indefinite"/>
  </line>

  <!-- Red beam -->
  <line x1="800" y1="70" x2="800" y2="70"
        stroke="#ff004c"
        stroke-width="8"
        filter="url(#glow)">
    <animate attributeName="x2"
             from="800" to="400"
             dur="1s"
             repeatCount="indefinite"/>
  </line>

</svg>
</p>
