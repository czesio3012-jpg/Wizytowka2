<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Szymon Kiełtyka - Agent Ubezpieczeniowy PZU</title>
    <style>
        :root {
            --bg-color: #0d1b2a;
            --card-bg: #1b263b;
            --accent-blue: #0056b3;
            --text-main: #f8f9fa;
            --text-muted: #e0e1dd;
            --gold: #d4af37;
            --whatsapp-color: #25d366;
            --highlight-bg: rgba(0, 86, 179, 0.25);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
        }

        .card {
            background-color: var(--card-bg);
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            max-width: 420px;
            width: 100%;
            padding: 30px 24px;
            text-align: center;
            border: 1px solid rgba(212, 175, 55, 0.2);
        }

        .badge {
            display: inline-block;
            background-color: rgba(212, 175, 55, 0.15);
            color: var(--gold);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
            margin-bottom: 15px;
            letter-spacing: 0.5px;
        }

        h1 {
            margin: 0 0 6px 0;
            font-size: 1.75rem;
            color: #ffffff;
        }

        p.subtitle {
            margin: 0 0 20px 0;
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .remote-banner {
            background: var(--highlight-bg);
            border: 1px solid rgba(212, 175, 55, 0.4);
            border-radius: 12px;
            padding: 14px 16px;
            margin-bottom: 20px;
            text-align: left;
        }

        .remote-banner .title {
            color: var(--gold);
            font-weight: 700;
            font-size: 0.95rem;
            display: flex;
            align-items: center;
            gap: 8px;
            margin-bottom: 4px;
        }

        .remote-banner .desc {
            color: var(--text-muted);
            font-size: 0.85rem;
            line-height: 1.4;
            margin: 0;
        }

        .section-title {
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--gold);
            margin: 20px 0 10px 0;
            text-align: left;
            border-bottom: 1px solid rgba(224, 225, 221, 0.1);
            padding-bottom: 5px;
        }

        .services-list {
            text-align: left;
            margin: 0 0 20px 0;
            padding-left: 0;
            list-style: none;
        }

        .services-list li {
            padding: 6px 0;
            font-size: 0.9rem;
            color: var(--text-muted);
            display: flex;
            align-items: center;
        }

        .services-list li::before {
            content: "✓";
            color: var(--gold);
            font-weight: bold;
            margin-right: 10px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 14px;
            margin-bottom: 12px;
            border: none;
            border-radius: 10px;
            font-size: 1rem;
            font-weight: 600;
            text-decoration: none;
            cursor: pointer;
            transition: transform 0.2s, opacity 0.2s;
            box-sizing: border-box;
        }

        .btn:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }

        .btn-phone {
            background-color: var(--accent-blue);
            color: white;
        }

        .btn-whatsapp {
            background-color: var(--whatsapp-color);
            color: white;
        }

        .btn-email {
            background-color: #415a77;
            color: white;
        }

        .btn-vcard {
            background-color: transparent;
            border: 1px solid var(--gold);
            color: var(--gold);
            margin-top: 10px;
        }
    </style>
</head>
<body>

<div class="card">
    <span class="badge">PZU Agent Ubezpieczeniowy</span>
    <h1>Szymon Kiełtyka</h1>
    <p class="subtitle">Specjalista ds. Ubezpieczeń Majątkowych</p>

    <!-- Chwytliwy baner o obsłudze zdalnej -->
    <div class="remote-banner">
        <div class="title">🏠 Wygodnie i bez wychodzenia z domu!</div>
        <p class="desc">
            Kompleksowa obsługa <strong>100% zdalnie</strong>. Wszystkie formalności i wycenę załatwisz szybko przez telefon, WhatsApp lub e-mail.
        </p>
    </div>

    <div class="section-title">Zakres ubezpieczeń majątkowych</div>
    <ul class="services-list">
        <li>Ubezpieczenia domów i mieszkań</li>
        <li>Majątek i finanse przedsiębiorstw / firm</li>
        <li>Ubezpieczenia komunikacyjne (AC, OC, NNW, Assistance)</li>
        <li>Odpowiedzialność cywilna (OC prywatne i zawodowe)</li>
        <li>Ubezpieczenia gospodarstw rolnych</li>
    </ul>

    <a href="tel:+48577317523" class="btn btn-phone">
        📞 Zadzwoń: +48 577 317 523
    </a>

    <a href="https://wa.me/48577317523" class="btn btn-whatsapp" target="_blank">
        💬 Napisz na WhatsApp
    </a>

    <a href="mailto:szkieltyka@agentpzu.pl" class="btn btn-email">
        ✉️ szkieltyka@agentpzu.pl
    </a>

    <a href="data:text/vcard;charset=utf-8,BEGIN%3AVCARD%0AVERSION%3A3.0%0AN%3AKie%C5%82tyka%3BSzymon%0AFN%3ASzymon%20Kie%C5%82tyka%0AORG%3APZU%0ATITLE%3AAgent%20Ubezpieczeniowy%0ATEL%3BTYPE%3DCELL%2CVOICE%2CWHATSAPP%3A%2B48577317523%0AEMAIL%3Aszkieltyka%40agentpzu.pl%0ANOTE%3AUbezpieczenia%20maj%C4%85tkowe.%20Pe%C5%82na%20obs%C5%82uga%20zdalna%20bez%20wychodzenia%20z%20domu.%0AEND%3AVCARD" download="szymon_kieltyka.vcf" class="btn btn-vcard">
        📇 Zapisz kontakt w telefonie (vCard)
    </a>
</div>

</body>
</html>
