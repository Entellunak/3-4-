<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>クラス時間割（曜日別）</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 1em;
      background-color: #f4f4f4;
    }

    h1 {
      text-align: center;
      color: #333;
    }

    .day {
      background-color: white;
      margin-bottom: 1.5em;
      padding: 1em;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .day h2 {
      margin-top: 0;
      border-bottom: 1px solid #ccc;
      padding-bottom: 0.5em;
    }

    .period {
      display: flex;
      justify-content: space-between;
      padding: 0.5em 0;
      border-bottom: 1px solid #eee;
    }

    .period:last-child {
      border-bottom: none;
    }

    .time {
      font-weight: bold;
      color: #333;
    }

    .subject {
      color: #555;
    }
  </style>
</head>
<body>
  <h1>3年4組 時間割</h1>

  <div class="day">
    <h2>月曜日</h2>
    <div class="period"><div class="time">1限</div><div class="subject">道徳</div></div>
    <div class="period"><div class="time">2限</div><div class="subject">体育</div></div>
    <div class="period"><div class="time">3限</div><div class="subject">理科</div></div>
    <div class="period"><div class="time">4限</div><div class="subject">数学</div></div>
    <div class="period"><div class="time">5限</div><div class="subject">英語</div></div>
    <div class="period"><div class="time">6限</div><div class="subject">社会</div></div>
  </div>

  <div class="day">
    <h2>火曜日</h2>
    <div class="period"><div class="time">1限</div><div class="subject">音楽</div></div>
    <div class="period"><div class="time">2限</div><div class="subject">社会</div></div>
    <div class="period"><div class="time">3限</div><div class="subject">理科</div></div>
    <div class="period"><div class="time">4限</div><div class="subject">数学</div></div>
    <div class="period"><div class="time">5限</div><div class="subject">英語</div></div>
    <div class="period"><div class="time">6限</div><div class="subject">総合</div></div>
  </div>

  <div class="day">
    <h2>水曜日</h2>
    <div class="period"><div class="time">1限</div><div class="subject">社会</div></div>
    <div class="period"><div class="time">2限</div><div class="subject">理科</div></div>
    <div class="period"><div class="time">3限</div><div class="subject">体育</div></div>
    <div class="period"><div class="time">4限</div><div class="subject">数学</div></div>
    <div class="period"><div class="time">5限</div><div class="subject">英語</div></div>
    <div class="period"><div class="time">6限</div><div class="subject">国語</div></div>
  </div>

  <div class="day">
    <h2>木曜日</h2>
    <div class="period"><div class="time">1限</div><div class="subject">国語</div></div>
    <div class="period"><div class="time">2限</div><div class="subject">数学</div></div>
    <div class="period"><div class="time">3限</div><div class="subject">社会</div></div>
    <div class="period"><div class="time">4限</div><div class="subject">体育</div></div>
    <div class="period"><div class="time">5限</div><div class="subject">学活</div></div>
    <div class="period"><div class="time">6限</div><div class="subject">なし</div></div>
  </div>

  <div class="day">
    <h2>金曜日</h2>
    <div class="period"><div class="time">1限</div><div class="subject">技家</div></div>
    <div class="period"><div class="time">2限</div><div class="subject">国語</div></div>
    <div class="period"><div class="time">3限</div><div class="subject">英語</div></div>
    <div class="period"><div class="time">4限</div><div class="subject">美術</div></div>
    <div class="period"><div class="time">5限</div><div class="subject">理科</div></div>
    <div class="period"><div class="time">6限</div><div class="subject">総合</div></div>
  </div>

</body>
</html>
