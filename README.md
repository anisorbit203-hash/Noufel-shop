<!DOCTYPE html>
<html lang="en" dir="ltr" class="lock">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
<title>My Store | Online Shopping in Algeria</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
/* ============ الألوان: غيّرها من هنا ============ */
:root{
  --ink:#10222b; --teal:#0f4c5c; --gold:#e0a526; --sand:#faf6ee; --card:#fff;
  --muted:#6b7a82; --red:#d64045; --green:#25d366; --line:#e8e2d4;
  --radius:14px; --shadow:0 8px 24px rgba(16,34,43,.08);
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Poppins',Arial,sans-serif;background:var(--sand);color:var(--ink);line-height:1.6}
img{max-width:100%;display:block}
button,input,select,textarea{font:inherit;color:inherit}
button{cursor:pointer;border:0}
a{color:inherit;text-decoration:none}
:focus-visible{outline:3px solid var(--gold);outline-offset:2px}
.wrap{max-width:1180px;margin:auto;padding:0 18px}

/* الشريط العلوي */
.topbar{background:var(--ink);color:#fff;text-align:center;font-size:14px;padding:8px 12px}

/* الهيدر */
header{background:#fff;position:sticky;top:0;z-index:50;border-bottom:1px solid var(--line)}
.head{display:flex;align-items:center;justify-content:space-between;gap:14px;height:68px}
.logo{display:flex;align-items:center;gap:10px;font-weight:800;font-size:22px;color:var(--teal)}
.logo i{width:38px;height:38px;border-radius:10px;background:var(--teal);color:var(--gold);display:grid;place-items:center;font-style:normal;font-size:20px}
nav{display:flex;gap:6px}
nav a{padding:8px 14px;border-radius:999px;font-weight:500;transition:.2s}
nav a:hover{background:var(--sand);color:var(--teal)}
