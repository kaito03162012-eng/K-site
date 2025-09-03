<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>ランダム画像ギャラリー</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main class="wrap">
    <h1>ランダム画像ギャラリー</h1>

    <div class="controls">
      <button id="randomBtn" class="btn">ランダム画像を表示</button>

      <!-- オプション: ローカル画像を使うなら ON に -->
      <label class="switch">
        <input type="checkbox" id="useLocal">
        <span>ローカル画像を使う</span>
      </label>
    </div>

    <section id="gallery" class="gallery" aria-live="polite">
      <div id="placeholder" class="placeholder">ここに画像が表示されます</div>
    </section>

    <p class="note">ヒント：ローカル画像を使う場合は `images/` フォルダに画像を入れてください（例: images/1.jpg, images/2.png ...）。</p>
  </main>

  <script src="script.js"></script>
</body>
</html>
