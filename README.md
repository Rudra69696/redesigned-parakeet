<!DOCTYPE html>
<html>
<head>
<title>Your Key</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    body { background: #0e0e0e; color: white; font-family: Arial; text-align: center; }
    #box { margin: auto; margin-top: 100px; width: 90%; max-width: 500px;
           background: #161616; padding: 30px; border-radius: 10px; }
    button { background: #007bff; border: none; padding: 15px 30px;
             color: white; font-size: 18px; border-radius: 8px; cursor: pointer; margin-top: 20px; }
    button:hover { background: #0063cc; }
    #key { margin-top: 20px; font-size: 22px; letter-spacing: 3px; }
</style>
</head>

<body>

<div id="box">
    <h1>Your Key</h1>
    <p>Copy the key below and paste it in Roblox:</p>

    <!-- This is where the key appears -->
    <div id="key">LOADING...</div>

    <button onclick="copyKey()">Copy Key</button>
</div>

<script>
    /* ⭐⭐ HERE IS THE LINE YOU LOOKING FOR ⭐⭐ */
    var KEY = "CO8SIYBU9KOHUA2S5ZCWBOG3C8HDW4IT";  // <=== your key goes here

    document.getElementById("key").innerText = KEY;

    function copyKey() {
        navigator.clipboard.writeText(KEY);
        alert("Key copied!");
    }
</script>

</body>
</html>
