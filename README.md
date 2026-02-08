# 欢迎来到我的空间！ 👋

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJueGZ3bmZ6Z3R3eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHh4JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1z/3o72EX5QZ9N9d51dqo/giphy.gif" width="200" alt="Pixel Cat">
  <p><i>ㄟ(≧◇≦)ㄏ</i></p>
</div>

## 📊 我的 GitHub 统计

![XOR-Y's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=XOR-Y&theme=github-compact)

### 🛠️ 技术栈
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

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