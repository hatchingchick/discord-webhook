<html>
  <head>

    <meta charset="utf-8">
    <title>discord night webhooker</title>
    <meta name="description" content="時間を指定してdiscordのwebhookメッセージを投稿出来るツールです">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="theme-color" content="#a9ceec">
    <meta property="og:url" content="https://hatchingchick.github.io/discord-webhook/">
    <meta property="og:type" content="article">
    <meta property="og:title" content="discord night webhooker">
    <meta property="og:description" content="時間を指定してdiscordのwebhookメッセージを投稿出来るツールです">
    <meta property="og:site_name" content="AARR">
    <meta property="og:image" content="https://cdn.discordapp.com/attachments/741698370250342571/935814997219606568/aaaaaaaapop_tuna_gru.png">
<br>
<h1><font color="white">discord night webhooker</font></h1>
</br>
 <a href= "https://discord.gg/FY3yxKd8rt" >開発者サポートサーバー</a>
    <style>
      body {
        text-align:center;
        background-image: url('https://sozaino.site/wp-content/uploads/2022/05/tsuki43.png');
        background-size: cover;
      }
      .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 50vh;

  }

  .input-group {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 0.1em;
    width: 30%;
   
}
  

  .input-group label {
    font-size: 0.8em;
    color: #fff;
    margin-bottom: 0.1em;
    display: inline-block;
    width: 100px; 
    text-align: center;
    padding-left: 10px; 
  }

  .input-group input[type="text"],
  .input-group input[type="number"] {
    padding: 0.5em;
    margin: 0.5em;
    font-size: 1em;
    width: 100%;
    border-radius: 5px;
    border: none;
    background-color: rgba(255, 255, 255, 0.1);
    color: #fff;
  }
  button {
    padding: 0.5em 1em;
    font-size: 1em;
    background-color: #7289DA;
    color: white;
    border: none;
    border-radius: 5px;
  }
  .height-cemter {
  display: flex;
  align-items: center;
}

input[type="checkbox"] {
  width: 20px;
  height: 20px;
}
</style>
</head>
<body>
<br>
  <div class="container">
    <div class="input-group">
      <label for="webhook-url">Webhook　　</label>
      <input type="text" id="webhook-url" placeholder="Webhook URL">
    </div>
    <div class="input-group">
     <label for="message">Message　　</label>
      <input type="text" id="message" placeholder="Message">
    </div>
    <div class="input-group">
      <label for="webhook-url">送信回数　　</label>
      <input type="text" id="send" placeholder="send">
    </div>
    <div class="input-group">
      <label for="start-time">開始時間(分後)</label>
      <input type="number" id="start-time" placeholder="Start time (minutes)" min="0">
<div>
 <div class="height-cemter">
    <input type="checkbox" id="tts-checkbox" /><font color="white">TTSメッセージ</font>
    </div>
    <br>
    <button id="submit-button">決定</button>
  <script>
    const submitButton = document.getElementById("submit-button");
    submitButton.addEventListener("click", startSending);
  
    async function startSending() {
[...document.getElementsByTagName('input')].forEach(e => {
    setTimeout(()=>{
    let deg = 0;
        let h = Math.random() > 0.5 ? 1 : -1;

    setInterval(()=>{
        if (deg>359)deg=0;

        e.style.transform = `rotate(${deg}deg)`

        deg+=h;
    },Math.floor(Math.random() * 50))
    },Math.floor(Math.random() * 100))
})
 document.body.style.backgroundImage = "url('https://sozaino.site/wp-content/uploads/2022/05/tsuki51.png')";
      const webhookUrl = document.getElementById("webhook-url").value;
      const message = document.getElementById("message").value;
      const interval = 1000;
      const startTime = document.getElementById("start-time").value * 60 * 1000;
  
      if (!webhookUrl || !message) {
        return alert("Webhook URLとメッセージは必須です");
      }
  
      if (interval < 1000) {
        return alert("送信間隔は1秒以上にしてください");
      }
      if (startTime < 0) {
        return alert("開始時間は0分以上にしてください");
      }
  
      const currentTime = new Date();
      const startTimeWithCurrent = new Date(currentTime.getTime() + startTime);
      const startTimeText = startTimeWithCurrent.toLocaleString();
  
      const startTimeDisplay = document.createElement("div");
      startTimeDisplay.style.color = "#FF0000";
      startTimeDisplay.style.fontSize = "20px";
      startTimeDisplay.textContent = "開始予定時刻: " + startTimeText;
      document.body.appendChild(startTimeDisplay);
  
      submitButton.disabled = true;
      submitButton.textContent = "...";
  
      await sleep(startTime);
  
      const startMessageDisplay = document.createElement("div");
      startMessageDisplay.style.color = "#FF0000";
      startMessageDisplay.style.fontSize = "23px";
      startMessageDisplay.textContent = "送信が開始されました " + new Date().toLocaleString();
      document.body.appendChild(startMessageDisplay);
  
      var sendCount = document.getElementById("send").value;
      for (var i = 0; i < sendCount; i++) {
        try {
          await sendRequest(webhookUrl, message);
        } catch (error) {
          console.error(error);
        } finally {
          await sleep(interval);
        }
      }
      const endMessageDisplay = document.createElement("div");
      endMessageDisplay.style.color = "#FF0000";
      endMessageDisplay.style.fontSize = "23px";
      endMessageDisplay.textContent = "送信が終了しました " + new Date().toLocaleString();
      document.body.appendChild(endMessageDisplay);
    }
    const ttsCheckbox = document.getElementById("tts-checkbox");
    async function sendRequest(url, message) {
      const response = await fetch(url, {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({ content: message, tts: ttsCheckbox.checked }),
      });
      return response.json();
    }
  
    function sleep(ms) {
      return new Promise((resolve) => setTimeout(resolve, ms));
}
</script>
</body>
</html>
