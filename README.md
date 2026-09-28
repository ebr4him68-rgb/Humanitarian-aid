# Humanitarian-aid


<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>کمک به یک خانواده بی‌خانمان</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Tahoma, Arial, sans-serif;
  background: linear-gradient(180deg, #fffdf5, #f5f7ff);
  color: #222;
  text-align: center;
}

.container {
  max-width: 650px;
  margin: 40px auto;
  padding: 20px;
}

.card {
  background: white;
  border-radius: 25px;
  padding: 30px 22px;
  box-shadow: 0 8px 30px rgba(0,0,0,.10);
}

.angel {
  font-size: 70px;
  margin-bottom: 10px;
}

h1 {
  color: #333;
  font-size: 27px;
  margin: 10px 0 20px;
}

.text {
  font-size: 19px;
  line-height: 2.2;
  color: #444;
  margin-bottom: 25px;
}

.donation-button {
  border: none;
  background: #16a34a;
  color: white;
  font-size: 20px;
  font-weight: bold;
  padding: 15px 35px;
  border-radius: 14px;
  cursor: pointer;
  box-shadow: 0 5px 15px rgba(22,163,74,.25);
}

.donation-button:hover {
  background: #12813b;
}

.wallet-box {
  display: none;
  margin-top: 25px;
  padding: 20px;
  background: #f7f7f7;
  border-radius: 18px;
  border: 1px solid #ddd;
}

.wallet-title {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 12px;
}

.wallet-address {
  direction: ltr;
  word-break: break-all;
  background: white;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 13px;
  font-family: monospace;
  font-size: 15px;
  margin-bottom: 12px;
}

.copy-button {
  border: none;
  background: #2563eb;
  color: white;
  padding: 11px 25px;
  border-radius: 10px;
  font-size: 16px;
  cursor: pointer;
}

.copy-button:hover {
  background: #1d4ed8;
}

.note {
  margin-top: 18px;
  color: #777;
  font-size: 13px;
  line-height: 1.8;
}

.footer {
  margin-top: 25px;
  color: #888;
  font-size: 13px;
}
</style>
</head>

<body>

<div class="container">

  <div class="card">

    <div class="angel">👼🏻</div>

    <h1>کمک به یک خانواده بی‌خانمان</h1>

    <div class="text">
      یک خانواده ۵ نفره شامل یک مرد معلول،
      یک خانم مسن و دو دختر و یک پسر
      بی‌خانمان هستند و برای کمک به شما نیازمندند.
      <br><br>
      اگر تمایل دارید در تهیه سرپناه برای این خانواده
      کمک کنید، می‌توانید از طریق بیت‌کوین یاری برسانید.
    </div>

    <button class="donation-button" onclick="showWallet()">
      ❤️ کمک می‌کنم
    </button>

    <div class="wallet-box" id="walletBox">

      <div class="wallet-title">
        🕊️ صندوق صدقات بیت‌کوین
      </div>

      <div class="wallet-address" id="walletAddress">
        1Q99GpYnEU9yELNLjiJUWopNT1HatRYQrV
      </div>

      <button class="copy-button" onclick="copyAddress()">
        📋 کپی آدرس بیت‌کوین
      </button>

      <div class="note">
        لطفاً قبل از ارسال، آدرس کیف پول را با دقت بررسی کنید.
        <br>
        این آدرس برای دریافت BTC روی شبکه Bitcoin است.
      </div>

    </div>

  </div>

  <div class="footer">
    🙏 از حمایت و مهربانی شما سپاسگزاریم
  </div>

</div>

<script>

function showWallet() {
  document.getElementById("walletBox").style.display = "block";
}

function copyAddress() {

  const address =
    document.getElementById("walletAddress").innerText.trim();

  navigator.clipboard.writeText(address).then(function() {

    const button = document.querySelector(".copy-button");

    button.innerText = "✅ آدرس کپی شد";

    setTimeout(function() {
      button.innerText = "📋 کپی آدرس بیت‌کوین";
    }, 2000);

  }).catch(function() {

    alert("کپی خودکار انجام نشد. آدرس را دستی کپی کنید.");

  });
}

</script>
بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيمِبه نام خداوند رحمتگر مهربان إِنَّا أَعْطَيْنَاكَ الْكَوْثَرَ ﴿۱﴾ما تو را [چشمه] كوثر داديم (۱) فَصَلِّ لِرَبِّكَ وَانْحَرْ ﴿۲﴾پس براى پروردگارت نماز گزار و قربانى كن (۲) إِنَّ شَانِئَكَ هُوَ الْأَبْتَرُ
</body>
</html>
```
