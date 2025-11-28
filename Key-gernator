<!DOCTYPE html>
<html>
<head>
<title>Key Generator</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    body { background: #0e0e0e; color: white; font-family: Arial; text-align: center; }
    #box { margin: auto; margin-top: 100px; width: 90%; max-width: 500px; 
           background: #161616; padding: 30px; border-radius: 10px; }
    button { background: #3a8fff; border: none; padding: 15px 30px; 
             color: white; font-size: 18px; border-radius: 8px; cursor: pointer; margin-top: 20px; }
    button:hover { background: #1e70e6; }
    #key { margin-top: 20px; font-size: 22px; letter-spacing: 2px; }
</style>
</head>
<body>

<div id="box">
    <h1>Your Key</h1>
    <p>Click the button to generate a secure key.</p>

    <div id="key">—</div>

    <button onclick="genKey()">Generate Key</button>
</div>

<script>
function genKey() {
    let chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";
    let key = "";
    for (let i = 0; i < 32; i++) {
        key += chars[Math.floor(Math.random() * chars.length)];
    }
    document.getElementById("key").innerText = key;
}
</script>

</body>
</html>
