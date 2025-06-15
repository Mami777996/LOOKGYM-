:root {
  --background: #fff;
  --foreground: #111;
  --accent: #000;
  --secondary: #888;
  --border-radius: 12px;
}

body {
  background: var(--background);
  color: var(--foreground);
  font-family: 'Montserrat', Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.header {
  background: var(--accent);
  color: var(--background);
  padding: 32px 0;
  text-align: center;
  letter-spacing: 3px;
  font-size: 2.5rem;
  font-weight: 700;
}

.container {
  max-width: 800px;
  margin: 40px auto;
  background: var(--background);
  border-radius: var(--border-radius);
  box-shadow: 0 2px 24px rgba(0,0,0,0.08);
  padding: 32px;
}

.section-title {
  color: var(--accent);
  border-bottom: 2px solid var(--accent);
  display: inline-block;
  margin-bottom: 18px;
  font-size: 1.4rem;
  font-weight: 600;
}

.button {
  padding: 12px 30px;
  border-radius: 8px;
  background: var(--accent);
  color: var(--background);
  border: none;
  font-weight: 600;
  letter-spacing: 2px;
  cursor: pointer;
  transition: background 0.2s;
}
.button:hover {
  background: var(--secondary);
  color: var(--accent);
}

input, textarea {
  background: #fafafa;
  border: 1px solid #222;
  border-radius: 6px;
  padding: 10px;
  color: var(--foreground);
  margin-bottom: 16px;
  width: 100%;
  font-size: 1rem;
}

::-webkit-scrollbar {
  width: 7px;
  background: #eee;
}
::-webkit-scrollbar-thumb {
  background: #222;
  border-radius: 5px;
}
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>lookgym Tema</title>
  <link rel="stylesheet" href="lookgym-theme.css">
</head>
<body>
  <div class="header">lookgym</div>
  <div class="container">
    <div class="section-title">Hoş Geldiniz</div>
    <p>Bu tema siyah-beyaz, sade ve şık bir arka plana sahiptir. Spor salonu veya fitness projeleri için uygundur.</p>
    <button class="button">Daha Fazla Bilgi</button>
  </div>
</body>
</html>
