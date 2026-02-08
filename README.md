<!-- 这个更简单，直接粘贴 -->
<div align="center">
  <div id="galaxy"></div>
</div>

<script>
  const emojis = ['✨','🌙','🪐','⭐','☄️','🌍','🚀','👾'];
  const galaxy = document.getElementById('galaxy');
  
  for(let i=0; i<24; i++) {
    const span = document.createElement('span');
    span.textContent = emojis[Math.floor(Math.random()*emojis.length)];
    span.style = `
      position: absolute;
      left: ${50 + 40*Math.cos(i*0.26)}%;
      top: ${50 + 40*Math.sin(i*0.26)}%;
      font-size: ${20+Math.random()*15}px;
      animation: spin ${3+Math.random()*4}s linear infinite;
    `;
    galaxy.appendChild(span);
  }
  
  const style = document.createElement('style');
  style.textContent = `
    @keyframes spin {
      to { transform: rotate(360deg); }
    }
    #galaxy {
      position: relative;
      height: 200px;
    }
  `;
  document.head.appendChild(style);
</script>