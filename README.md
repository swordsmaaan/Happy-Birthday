<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday Haniya</title>

<style>
    body {
        margin: 0;
        padding: 0;
        height: 100vh;
        overflow: hidden;
        background: linear-gradient(135deg, #ff9a9e, #fad0c4, #fbc2eb, #a6c1ee);
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Segoe UI', sans-serif;
    }

    /* ===== BALLOONS ===== */
    .balloon {
        position: absolute;
        bottom: -180px;
        width: 70px;
        height: 90px;
        border-radius: 50%;
        animation-name: floatUp;
        animation-timing-function: linear;
        animation-iteration-count: infinite;
        opacity: 0.85;
    }

    .balloon::after {
        content: "";
        position: absolute;
        top: 100%;
        left: 50%;
        width: 2px;
        height: 55px;
        background: rgba(0,0,0,0.25);
    }

    @keyframes floatUp {
        0% {
            transform: translateY(0) translateX(0);
        }
        100% {
            transform: translateY(-130vh) translateX(60px);
        }
    }

    /* Colors */
    .pink { background: #ff6f91; }
    .yellow { background: #ffc75f; }
    .purple { background: #845ec2; }
    .blue { background: #4d96ff; }
    .green { background: #43e97b; }
    .peach { background: #ff9671; }
    .teal { background: #4fffe0; }

    /* ===== CARD ===== */
    .card {
        background: rgba(255, 255, 255, 0.92);
        border-radius: 25px;
        padding: 50px 40px;
        max-width: 750px;
        text-align: center;
        border: 5px solid transparent;
        background-clip: padding-box;
        box-shadow: 0 25px 60px rgba(0, 0, 0, 0.25);
        position: relative;
        z-index: 10;
    }

    .card::before {
        content: "";
        position: absolute;
        inset: -5px;
        border-radius: 30px;
        background: linear-gradient(45deg, #ff6ec4, #7873f5, #4facfe, #43e97b);
        z-index: -1;
    }

    h1 {
        font-size: 3.2em;
        font-weight: 800;
        margin-bottom: 25px;
        background: linear-gradient(90deg, #ff5f6d, #ffc371);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        letter-spacing: 2px;
    }

    p {
        font-size: 1.2em;
        line-height: 1.8;
        color: #444;
        margin-bottom: 20px;
    }

    .highlight {
        color: #ff5f6d;
        font-weight: bold;
    }

    .heart {
        font-size: 3em;
        animation: pulse 1.5s infinite;
        margin-top: 10px;
    }

    @keyframes pulse {
        0% { transform: scale(1); }
        50% { transform: scale(1.25); }
        100% { transform: scale(1); }
    }

    .footer {
        margin-top: 30px;
        font-size: 0.95em;
        color: #777;
        border-top: 1px dashed #ccc;
        padding-top: 15px;
    }
</style>
</head>

<body>

<!-- LOTS OF BALLOONS -->
<div class="balloon pink" style="left:2%; animation-duration:14s;"></div>
<div class="balloon yellow" style="left:8%; animation-duration:12s;"></div>
<div class="balloon purple" style="left:14%; animation-duration:16s;"></div>
<div class="balloon blue" style="left:20%; animation-duration:13s;"></div>
<div class="balloon green" style="left:26%; animation-duration:15s;"></div>
<div class="balloon peach" style="left:32%; animation-duration:14s;"></div>
<div class="balloon teal" style="left:38%; animation-duration:12s;"></div>

<div class="balloon pink" style="left:44%; animation-duration:16s;"></div>
<div class="balloon yellow" style="left:50%; animation-duration:13s;"></div>
<div class="balloon purple" style="left:56%; animation-duration:15s;"></div>
<div class="balloon blue" style="left:62%; animation-duration:14s;"></div>
<div class="balloon green" style="left:68%; animation-duration:12s;"></div>
<div class="balloon peach" style="left:74%; animation-duration:16s;"></div>
<div class="balloon teal" style="left:80%; animation-duration:13s;"></div>
<div class="balloon pink" style="left:86%; animation-duration:15s;"></div>
<div class="balloon yellow" style="left:92%; animation-duration:14s;"></div>

<!-- CARD -->
<div class="card">
    <h1>Happy Birthday, Haniya</h1>

    <p>
        I love you and I am pleased to have you as my
        <span class="highlight">best friend</span>.
    </p>

    <p>
        I hope we remain best friends forever even when we are miles apart,<br>
        even when we are busy, even when we get married, even when we are old,<br>
        even after death in heaven.
    </p>

    <p class="highlight">
        Best friends for forever!
    </p>

    <div class="heart">💖</div>

    <div class="footer">
        Made by your best friend, Anosha  🌸
    </div>
</div>

</body>
</html>
