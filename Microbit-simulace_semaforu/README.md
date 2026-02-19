# Simulace semaforu pomocí Micro:bitu (odborná část)

## Popis
Micro:bit řídí tři externí LED diody (zelená, žlutá, červená) připojené na piny P0, P1, P2. Program běží v nekonečném cyklu, ve kterém se střídá zelená (3 s), žlutá (1 s) a červená (3 s).

## Použité piny
- P0 – zelená LED
- P1 – žlutá LED
- P2 – červená LED

## Princip programu
- Při startu: P0, P1, P2 = 0 (vše vypnuto)
- Opakuj stále:
  - P0 = 1 → čekej 3000 ms → P0 = 0
  - P1 = 1 → čekej 1000 ms → P1 = 0
  - P2 = 1 → čekej 3000 ms → P2 = 0

## Hardware
Zapojení je realizováno přes nepájivé pole. Každá LED je chráněna rezistorem 220 Ω.

## Soubory
- schema-zapojeni.png
- bloky-programu.png
- seznam-soucastek.md
