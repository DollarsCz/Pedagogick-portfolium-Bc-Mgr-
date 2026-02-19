# Metodický komentář – Simulace semaforu (Micro:bit)

## Vzdělávací cíle
- Žák ovládá více digitálních výstupů Micro:bitu.
- Žák vytváří sekvenci a pracuje s časováním (pauza).
- Žák chápe základní princip řízení LED a bezpečného zapojení (rezistor, polarita).

## Doporučený ročník a čas
2. stupeň ZŠ (cca 8. - 9. ročník), 45 minut.

## Organizace
Doporučeno ve dvojicích (jeden zapojuje, druhý tvoří program), poté prohození rolí.

## Pomůcky
Micro:bit + edge konektor, nepájivé pole, 3× LED, 3× rezistor 220 Ω, vodiče, PC/tablet s MakeCode.

## Postup hodiny
1) Úvod (5 min): bezpečné zapojení LED, polarita, role rezistoru.  
2) Zapojení obvodu (10 min): žáci zapojí dle schématu.  
3) Programování (20 min): nastavení pinů při startu, poté cyklus zelená–žlutá–červená s pauzami.  
4) Test a ladění (5–10 min): ověření pořadí, času, pouze jedna LED současně.

## Kritéria splnění
- Správné pořadí a časy (3 s, 1 s, 3 s).
- Vždy svítí jen jedna LED.
- Bezpečné zapojení (rezistor u každé LED, správná polarita).

## Diferenciace
- Lehčí varianta: učitel předpřipraví část programu, žáci doplní časy a pořadí.
- Těžší varianta: tlačítko spustí přechod (default červená), nebo přidat bzučák při zelené.

## Nejčastější problémy (prevence)
- Záměna anody/katody: ukázat na začátku, kontrola před spuštěním.
- Nesystematické zapojení: doporučit „každá LED vlastní řádek/sloupec“.
- Zapomenuté zhasnutí LED: připomenout „před další barvou vždy vypnout předchozí“.
