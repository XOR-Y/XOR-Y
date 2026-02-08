<div align="center">
  <pre id="face" onclick="changeFace()" style="
    font-size: 30px;
    cursor: pointer;
    display: inline-block;
    transition: transform 0.3s;
  ">(◕‿◕✿)</pre>
</div>

<script>
const faces = [
  '(◕‿◕✿)', '(¬‿¬)', '(≧∇≦)ﾉ', '(╯°□°）╯', '¯\_(ツ)_/¯',
  '( ͡° ͜ʖ ͡°)', 'ಠ_ಠ', 'ʕ•ᴥ•ʔ', '(ﾉ◕ヮ◕)ﾉ*:･ﾟ✧', '♪(┌・。・)┌'
];
let faceIndex = 0;
function changeFace() {
  const face = document.getElementById('face');
  face.style.transform = 'scale(1.2)';
  setTimeout(() => {
    faceIndex = (faceIndex + 1) % faces.length;
    face.textContent = faces[faceIndex];
    face.style.transform = 'scale(1)';
  }, 150);
}
</script>