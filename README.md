# Ports

Forks van ports die we op Android draaien, met eigen aanpassingen: Xbox 360-recompilaties (ReXGlue) en Switch-spellen
die natief draaien via nx2android. Dit is de index; elke port heeft zijn eigen repo. Alle repo's met het topic
[xbox360-port](https://github.com/topics/xbox360-port?q=user%3Aflip-o0o-flow) of [switch-port](https://github.com/topics/switch-port?q=user%3Aflip-o0o-flow) horen hierbij.

| Spel | Upstream | Onze fork | Wat wij toevoegden |
|---|---|---|---|
| Forza Horizon 2 | [Gabrick75/fh2-recompiled](https://github.com/Gabrick75/fh2-recompiled) | [fh2-recompiled](https://github.com/flip-o0o-flow/fh2-recompiled) (branch `cheats`, apk onder Releases) | Cheats › Credits in de launcher, touch-knop terug naar de launcher, spel in eigen proces, AES-dumphook voor savevelden |
| Need for Speed: Carbon | [](https://github.com/) | [NFS-CARBON-360-ANDROID-RECOMP](https://github.com/flip-o0o-flow/NFS-CARBON-360-ANDROID-RECOMP) (branch `taalkeuze`) | launcher-only build op de upstream-apk, taalkeuze, knoppen per controller toewijsbaar |
| Batman: Arkham Knight (Switch) | [shirai91/nx2android](https://github.com/shirai91/nx2android) | [nx2android](https://github.com/flip-o0o-flow/nx2android) (branch `arkham-knight`, geen apk: die bevat spelcode) | profiel voor Arkham Knight 1.0.5 (Unreal Engine 3), fixes voor zwart 3D-beeld en startcrashes op Adreno 730/740, diagnose per draw met image-statistieken |

## Wat er nooit in de repo's staat

De spelbestanden, de gegenereerde recompilatiecode en shaderbibliotheken die uit een eigen ISO gebouwd zijn. Die maak
je zelf met de tools van de upstream-projecten; de .gitignore's sluiten ze uit.

## Licentie

Elke fork volgt de licentie van zijn upstream (GPL; nx2android MIT). De apk's onder Releases zijn builds van die broncode.
