# Zacharijus Kurnosov – 9th Grandmaster in Lithuania ♟️
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root {
    --primary:#0f172a;
    --accent:#2563eb;
    --bg:#f8fafc;
    --text:#1e293b;
    --muted:#64748b;
}

* { box-sizing:border-box; margin:0; padding:0; }

body {
    font-family: Inter, system-ui, sans-serif;
    background:var(--bg);
    color:var(--text);
    line-height:1.7;
}

.container {
    max-width:1100px;
    margin:auto;
    padding:60px 24px;
}

header {
    display:flex;
    justify-content:space-between;
    align-items:flex-start;
    margin-bottom:80px;
}

h1 {
    font-size:3rem;
    font-weight:800;
    color:var(--primary);
}

.subtitle {
    font-size:1.2rem;
    color:var(--muted);
    max-width:720px;
    margin-top:16px;
}

.lang-switch {
    border:none;
    background:var(--accent);
    color:white;
    padding:10px 16px;
    border-radius:10px;
    cursor:pointer;
    font-weight:600;
    transition:transform .2s, box-shadow .2s;
}
.lang-switch:hover {
    transform:translateY(-2px);
    box-shadow:0 10px 20px rgba(0,0,0,.15);
}

section {
    margin-bottom:80px;
    opacity:0;
    transform:translateY(30px);
    animation:fadeUp 0.8s ease forwards;
}

section:nth-child(2){animation-delay:.1s}
section:nth-child(3){animation-delay:.2s}
section:nth-child(4){animation-delay:.3s}
section:nth-child(5){animation-delay:.4s}

@keyframes fadeUp {
    to { opacity:1; transform:none; }
}

.card {
    background:white;
    border-radius:20px;
    padding:40px;
    box-shadow:0 20px 40px rgba(0,0,0,.06);
}

h2 {
    font-size:2rem;
    margin-bottom:20px;
    color:var(--primary);
}

p {
    max-width:820px;
    margin-bottom:16px;
    font-size:1.05rem;
}

.stats {
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:30px;
    margin-top:40px;
}

.stat {
    background:white;
    padding:30px;
    border-radius:18px;
    text-align:center;
    transition:transform .3s;
    box-shadow:0 10px 25px rgba(0,0,0,.05);
}
.stat:hover {
    transform:translateY(-6px);
}

.stat strong {
    font-size:2.2rem;
    color:var(--accent);
    display:block;
}

footer {
    border-top:1px solid #e5e7eb;
    padding-top:40px;
    color:var(--muted);
    font-size:.9rem;
}
</style>
</head>

<body>
<div class="container">
<p class="subtitle lang en">
<header>
<div>
<h1>Zacharijus Kurnosov</h1>
Zacharijus Kurnosov has officially become the <strong>9th Grandmaster in Lithuania</strong>,
marking a historic milestone for Lithuanian chess on the international stage.
</p>
<p class="subtitle lang lt" style="display:none">
Zacharijus Kurnosov oficialiai tapo <strong>9-uoju didmeistriu Lietuvoje</strong>,
pažymėdamas istorinį pasiekimą Lietuvos šachmatų istorijoje.
</p>
</div>

<button class="lang-switch" onclick="toggleLang()">EN / LT</button>
</header>

<section class="card">
<h2 class="lang en">A Historic Achievement in Lithuania</h2>
<h2 class="lang lt" style="display:none">Istorinis pasiekimas Lietuvoje</h2>

<p class="lang en">
In 2025, in Lithuania, Zacharijus Kurnosov earned the prestigious Grandmaster title.
This achievement represents year of dedication, elite competition, and strategic excellence.
</p>

<p class="lang lt" style="display:none">
2025 metais Lietuvoje Zacharijus Kurnosov pasiekė prestižinį didmeistrio titulą.
Šis pasiekimas – metų darbas, strategijos ir meistriškumo rezultatas.
</p>
</section>

<section>
<h2 class="lang en">The Lithuanian Journey</h2>
<h2 class="lang lt" style="display:none">Kelias Lietuvoje</h2>

<p class="lang en">
Life in the dormitory of "Vilnius Lietuvių Namai" Gymnasium became an important part of his chess journey — it was there that he regularly took part in tournaments. Despite not being a Lithuanian citizen since birth, he competed in tournaments of the Russian Chess Federation while traveling to his homeland during summer holidays, yet his title was officially recognized in Lithuania, “the country of his heart.”
</p>
<p class="lang lt" style="display:none">
Gyvenimas Vilniaus lietuvių namų gimnazijos bendrabutyje tapo svarbia jo šachmatų kelio dalimi – būtent čia jis nuolat dalyvavo turnyruose, nepaisant to, kad nuo gimimo nėra Lietuvos pilietis, važiuodamas į vasaros atostogas į savo gimtinę, jis žaidė Šachmatų Rusijos Federacijos turnyruose, bet jo titulas buvo pripažintas Lietuvoje, "jo širdies šalyje."
</p>
</section>

<section>
<h2 class="lang en">What This Means for Lithuania</h2>
<h2 class="lang lt" style="display:none">Ką tai reiškia Lietuvai</h2>

<p class="lang en">
Zacharijus still cannot fully grasp the significance of his achievement, but becoming the 9th Grandmaster in Lithuania strengthens the country’s position on the global chess map and inspires the younger generation of Lithuanian chess players.
</p>

<p class="lang lt" style="display:none">
Zacharijus vis dar negali iki galo suvokti savo pasiekto titulo, bet tapimas 9-uoju didmeistriu Lietuvoje stiprina šalies pozicijas pasaulio šachmatų
žemėlapyje ir įkvepia jaunąją Lietuvos šachmatininkų kartą.
</p>

<div class="stats">
<div class="stat"><strong>9th</strong>in Lithuania</div>
<div class="stat"><strong>2025</strong>Achievement</div>
<div class="stat"><strong>LT</strong>Chess History</div>
</div>
</section>

<section>
<h2 class="lang en">Looking Ahead</h2>
<h2 class="lang lt" style="display:none">Žvilgsnis į ateitį</h2>

<p class="lang en">
Representing Lithuania, Zacharijus Kurnosov now focuses on elite international
tournaments and the development of future chess talents in the country.
</p>

<p class="lang lt" style="display:none">
Atstovaudamas Lietuvai, Zacharijus Kurnosov siekia aukščiausio lygio turnyrų ir
prisideda prie būsimų šalies šachmatų talentų ugdymo.
</p>
</section>

<footer>
<p>© 2025 Lithuanian Chess Project</p>
</footer>

</div>

<script>
let currentLang = "en";
function toggleLang() {
    currentLang = currentLang === "en" ? "lt" : "en";
    document.querySelectorAll(".lang").forEach(el => {
        el.style.display = el.classList.contains(currentLang) ? "block" : "none";
    });
}
</script>

</body>
</html>
