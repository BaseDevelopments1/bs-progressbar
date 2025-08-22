local success = exports['bs-progressbar']:wystartujprogress(
    "Zbieranie Kasy z kasetki...", -- tekst 
    5000,                          -- czas 
    true,                          -- Czy mozna anulowac przyciskiem X domyslnie ustawione na true 
    { dict = 'oddjobs@shop_robbery@rob_till', name = 'loop', flags = 1 } 
)


if success then
    print("Progressbar zakończony!") 
else
    print("Progressbar został anulowany!") 
end
