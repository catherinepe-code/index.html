# index.html
Ms. P's Daily Hub
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Class Hub</title>
  <meta name="description" content="Daily agenda, Check & Connect, and announcements" />
  <style>
    :root {
      --text: #eaf2ff;
      --muted: #a7b0c1;
      --brand: #6ac3ff;
      --accent: #92ffb6;
      --radius: 12px;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --font: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas;
      --size: clamp(15px, 1.8vw, 18px);
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    body {
      margin: 0;
      font-family: var(--font);
      font-size: var(--size);
      line-height: 1.6;
      backgrou
