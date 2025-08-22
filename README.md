exports("wystartujprogress", wystartujprogress)

exports['bs-progressbar']:wystartujprogress(
    "Nalewanie paliwa...", -- tekst
    5000,                  -- czas w ms
    true,                  -- czy można anulować
    { dict = "amb@world_human_hammering@male@base", name = "base", flags = 49 } -- animacja (opcjonalne)
)
