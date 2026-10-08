# Embedded Linux Remote Update and Recovery

| Hét | Fő cél | Várható eredmény |
|---|---|---|
| 1. (09.28)| Követelmények, szakirodalom, szabványok | Követelménylista és első architektúra |
| 2. | RAUC, SWUpdate, Mender, OSTree és hawkBit vizsgálata | Összehasonlító mátrix és technológiaválasztás |
| 3. | Buildroot + QEMU környezet | Bootoló minimális embedded Linux |
| 4. | U-Boot + A/B kialakítása, RAUC integráció | Signed bundle és inaktív slot frissítése |
| 5. | State machine, health check és commit/rollback | Automatikus mark-good vagy rollback |
| 6. | Watchdog | Rendszerfagyások és boot hibák kezelése |
| 7. | Megszakított távoli frissítések tesztelése | Network/power-loss recovery |
| 8. | Btrfs snapshot | Perzisztens adatok snapshot/restore tesztje |
| 9. | Hibatesztek | Mérési és teszteredmények |
| 10. | Megoldások kiértékelése | A/B, snapshot és alternatívák összehasonlítása |
| 11. (12.07.)| Dokumentáció és demó | Végleges prototípus és szakdolgozati eredmények |
