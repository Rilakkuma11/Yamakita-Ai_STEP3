# Yamakita-Ai_STEP3

設問１

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>世界一甘いお店｜お問い合わせフォーム</title>
  <style>{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: sans-serif;
    }
    #wrapper {
      width: 900px;
      margin: 0 auto;
      background: #fff;
    }
    #header {
      width: 900px;
      height: 100px;
      background: #f48fb1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    #header h2 {
      color: #fff;
      font-size: 1.8em;
    }
    .nav-links {
      margin-top: 8px;
    }
    .nav-links a {
      margin: 0 10px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .nav-links a:hover {
      text-decoration: underline;
    }
    #container {
      display: flex;
    }
    #sidebar {
      width: 220px;
      height: 500px;
      background: #ffe082;
      padding: 16px;
    }
    #sidebar nav a {
      display: block;
      margin-bottom: 12px;
      color: #444;
      text-decoration: none;
      font-weight: bold;
    }
    #sidebar nav a:hover {
      text-decoration: underline;
    }
    #main {
      width: 680px;
      height: 500px;
      background: #e3f2fd;
      padding: 16px;
      overflow: auto;
    }
    .main-nav {
      display: flex;
      gap: 20px;
      margin-bottom: 16px;
    }
    .main-nav a {
      text-decoration: none;
      color: #0288d1;
      font-weight: bold;
    }
    .main-nav a:hover {
      text-decoration: underline;
    }
    table {
      margin: 0 auto;
      border-collapse: collapse;
      border: 4px solid #000;
    }
    th, td {
      border: 4px solid #000;
      padding: 8px;
      text-align: left;
    }
    .btn-area {
      text-align: left;
      margin-top: 12px;
    }
    .btn-area input[type="submit"] {
      padding: 6px 16px;
      background: #0288d1;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    #footer {
      width: 900px;
      height: 80px;
      background: #ce93d8;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      font-size: 1rem;
      margin-top: 8px;
    }
    section {
      margin-bottom: 24px;
    }
  </style>
</head>
<body>
  <div id="wrapper">
    <header id="header">
      <h2>世界一甘いお店</h2>
      <nav class="nav-links">
        <a href="#top">トップ</a>
        <a href="#news">新着情報</a>
        <a href="#sweets">おすすめスイーツ</a>
        <a href="#form">お問い合わせ</a>
      </nav>
    </header>
    <div id="container">
      <main id="main">
        <section id="form">
          <h3>お問い合わせ</h3>
          <form action="#" method="post">
            <table>
              <tr>
                <th>お名前</th>
                <td><input type="text" name="name" size="40"></td>
              </tr>
              <tr>
                <th>近くのお店</th>
                <td>
                  <select name="store">
                    <option value="">選択してください</option>
                    <option>北海道・東北</option>
                    <option>関東</option>
                    <option>中部</option>
                    <option>関西</option>
                    <option>中国</option>
                    <option>四国</option>
                    <option>九州・沖縄</option>
                  </select>
                </td>
              </tr>
              <tr>
                <th>電話</th>
                <td><input type="text" name="tel" size="40"></td>
              </tr>
              <tr>
                <th>電話番号</th>
                <td><input type="text" name="phone" size="40"></td>
              </tr>
              <tr>
                <th>メールアドレス</th>
                <td><input type="email" name="email" size="40"></td>
              </tr>
              <tr>
                <th>お問い合わせ種別</th>
                <td>
                  <label><input type="radio" name="inquiry_type" value="product"> 商品について</label>
                  <label><input type="radio" name="inquiry_type" value="staff"> 従業員について</label>
                </td>
              </tr>
              <tr>
                <th>お問い合わせ内容</th>
                <td>
                  <textarea name="message" cols="30" rows="5" placeholder="詳細を入力してください"></textarea>
                </td>
              </tr>
            </table>
            <div class="btn-area">
              <input type="submit" value="送信">
            </div>
          </form>
        </section>
      </main>
    </div>
    <footer id="footer">
      © 2025 世界一甘いお店
    </footer>
  </div>
</body>
</html>
