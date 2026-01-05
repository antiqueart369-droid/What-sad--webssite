<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>what's.ad - Earn Money</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            background: linear-gradient(135deg, #292F36 0%, #1a1f25 100%);
            color: white;
            font-family: 'Arial', sans-serif;
            min-height: 100vh;
            padding: 20px;
            text-align: center;
        }
        .header {
            padding: 30px 0;
            border-bottom: 3px solid #FF6B6B;
        }
        .logo {
            font-size: 60px;
            margin-bottom: 10px;
        }
        h1 {
            font-size: 40px;
            background: linear-gradient(45deg, #FF6B6B, #FFE66D);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }
        .balance-card {
            background: rgba(255,255,255,0.1);
            padding: 25px;
            border-radius: 20px;
            margin: 30px auto;
            width: 90%;
            max-width: 300px;
            border: 2px solid #4ECDC4;
        }
        .balance-amount {
            font-size: 48px;
            color: #FFE66D;
            font-weight: bold;
        }
        .btn {
            background: linear-gradient(45deg, #FF6B6B, #FF8E8E);
            color: white;
            border: none;
            padding: 18px 35px;
            font-size: 18px;
            border-radius: 50px;
            margin: 15px;
            cursor: pointer;
            font-weight: bold;
            display: inline-block;
            min-width: 200px;
        }
        .btn:hover {
            transform: scale(1.05);
        }
        .btn-secondary {
            background: rgba(255,255,255,0.15);
            border: 2px solid #4ECDC4;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="logo">🤑</div>
            <h1>what's.ad</h1>
            <p>Watch Ads. Earn Instantly. Withdraw Daily.</p>
        </div>
        
        <div class="balance-card">
            <div>Your Balance</div>
            <div class="balance-amount">₹250</div>
            <div style="font-size:14px;margin-top:10px;">Minimum: ₹100 to withdraw</div>
        </div>
        
        <div>
            <button class="btn" onclick="earnMoney()">Watch Ad & Earn ₹10</button>
            <button class="btn btn-secondary" onclick="withdrawMoney()">Withdraw Money</button>
        </div>
        
        <div style="margin-top: 40px; padding: 20px; background: rgba(0,0,0,0.3); border-radius: 15px;">
            <h3>How it works:</h3>
            <p>1. Watch 30-second ads</p>
            <p>2. Earn ₹10 per ad</p>
            <p>3. Withdraw via UPI/Bank</p>
        </div>
        
        <div style="margin-top: 50px; font-size: 14px; opacity: 0.8;">
            <p>© 2024 what's.ad | Made with ❤️ for earners</p>
        </div>
    </div>
    
    <script>
        function earnMoney() {
            alert('🎉 You earned ₹10! Watch more ads to earn more.');
        }
        function withdrawMoney() {
            alert('Withdrawal feature coming soon! Minimum ₹100 required.');
        }
    </script>
</body>
</html>