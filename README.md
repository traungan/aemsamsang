# aemsamsang
applemeomeo
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Englishie ♡</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;700;800;900&display=swap');

* { box-sizing: border-box; }

body {
  margin: 0;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
  font-family: 'Nunito', sans-serif;
  color: #715469;
  background: linear-gradient(135deg, #ffe7f0, #f0e7ff, #e6fff5);
  overflow-x: hidden;
}

body::before {
  content: "♡ ୨୧ ♡";
  position: fixed;
  top: 20px;
  left: 15px;
  color: #efa5c6;
  font-size: 28px;
  opacity: .65;
}

body::after {
  content: "✿ ♡ ✿";
  position: fixed;
  bottom: 20px;
  right: 15px;
  color: #b39bdf;
  font-size: 28px;
  opacity: .65;
}

.card {
  width: 100%;
  max-width: 560px;
  padding: 32px 24px;
  border-radius: 30px;
  background: rgba(255,255,255,.88);
  border: 2px solid white;
  box-shadow: 0 15px 45px #c9a6cc45;
  position: relative;
}

.page { text-align: center; }
.hidden { display: none !important; }

.tag {
  font-size: 11px;
  letter-spacing: 3px;
  font-weight: 900;
  color: #c57fa7;
}

.bunny {
  font-size: 65px;
  margin: 20px 0 10px;
  animation: float 2s infinite ease-in-out;
}

@keyframes float {
  50% { transform: translateY(-7px) rotate(3deg); }
}

h1 {
  font-size: clamp(43px, 10vw, 64px);
  line-height: 1;
  margin: 15px 0;
  color: #ee8fb5;
  letter-spacing: -2px;
}

h1 span { color: #ac94e5; }

.subtitle {
  line-height: 1.8;
  font-size: 15px;
  margin: 18px 0;
}

.pill {
  display: inline-block;
  background: #f2eaff;
  color: #987ac7;
  padding: 8px 15px;
  border-radius: 30px;
  font-size: 12px;
  font-weight: 900;
}

button {
  font-family: inherit;
  cursor: pointer;
  transition: .2s;
}

button:hover { transform: translateY(-2px); }

.main-btn {
  border: none;
  background: linear-gradient(135deg, #ff9fbe, #e9a0ec);
  color: white;
  padding: 15px 28px;
  border-radius: 18px;
  font-size: 17px;
  font-weight: 900;
  box-shadow: 0 6px 0 #d98ab9;
  margin-top: 25px;
}

.main-btn:active {
  transform: translateY(3px);
  box-shadow: 0 3px 0 #d98ab9;
}

.note {
  font-size: 11px;
  color: #b29aad;
  margin-top: 25px;
}

.top {
  display: flex;
  justify-content: space-between;
  gap: 10px;
  font-size: 12px;
  font-weight: 900;
  color: #a486ce;
  margin-bottom: 12px;
}

.progress {
  height: 10px;
  background: #f5e8f3;
  border-radius: 20px;
  overflow: hidden;
  margin-bottom: 25px;
}

.bar {
  height: 100%;
  width: 0%;
  background: linear-gradient(90deg, #ff9fbe, #b9a1f2);
  transition: width .3s;
}

.question {
  text-align: left;
  font-size: 24px;
  line-height: 1.5;
  margin: 12px 0 22px;
  overflow-wrap: anywhere;
}

.answers {
  display: grid;
  gap: 12px;
}

.answer {
  width: 100%;
  display: flex;
  align-items: center;
  gap: 13px;
  padding: 13px;
  text-align: left;
