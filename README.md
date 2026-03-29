# Ghana-
<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Get Coins</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="app">

  <!-- Header -->
  <div class="header">
    <span>Get Coins</span>
    <span class="dots">•••</span>
  </div>

  <!-- Balance Card -->
  <div class="card">
    <div class="row">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/TikTok_logo.svg" class="logo">
      <div>
        <p class="title">Recharge</p>
        <p class="coins" id="balance">5,000 coins</p>
      </div>
    </div>
  </div>

  <!-- Info -->
  <p class="info">Save around 25% with a lower third-party service fee.</p>

  <!-- Coins Grid -->
  <div class="grid">
    <div class="box" onclick="selectAmount(30)">30<br><small>$0.31</small></div>
    <div class="box" onclick="selectAmount(350)">350<br><small>$3.65</small></div>
    <div class="box" onclick="selectAmount(700)">700<br><small>$7.25</small></div>
    <div class="box" onclick="selectAmount(1400)">1400<br><small>$14.49</small></div>
    <div class="box active" onclick="selectAmount(3500)">3500<br><small>$36.2</small></div>
    <div class="box" onclick="selectAmount(0)">Custom</div>
  </div>

  <!-- Invite -->
  <div class="invite">
    👋 Invite & Get Rewards
  </div>

  <!-- Transfer -->
  <div class="transfer">
    <h3>Send Coins</h3>
    <input id="username" placeholder="Username">
    <input id="amount" type="number" placeholder="Coins">
    <button onclick="sendCoins()">Send</button>
  </div>

  <!-- Buy Button -->
  <button class="buy" onclick="buyCoins()">Buy Now</button>

</div>

<script src="script.js"></script>

</body>
</html>
