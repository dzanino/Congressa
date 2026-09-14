# Congressa – web

Statická stránka pre GitHub Pages (repo `dzanino/Congressa`): `index.html` (SK/EN prepínač), `privacy.html`
(povinné pre App Store), `support.html`, `assets/`. Nahrať obsah tohto priečinka do koreňa repozitára
(alebo do `docs/` a v Settings → Pages zvoliť `/docs`). Po schválení v App Store doplniť odkaz na appku v `index.html` (#stiahnut).

Obrázky v `assets/` sa generujú z ikon aplikácie:
`cp Congressa/Resources/Assets.xcassets/AppIcon.appiconset/mac-256@1x.png web/assets/icon-256.png`
(a `mac-512@1x.png` → `icon-512.png`), prehľad ikon `docs/icons_preview.png` → `assets/icons.png`.
Stav k 7. 9. 2026: appka je zadarmo s nepovinnými príspevkami, kontakt `congressa_main@icloud.com`.

`organizator.html` — návod pre organizátora (SK/EN). Sťahovateľné: `assets/Congressa_server_pre_druhy_Mac.zip` (obnoviť po každej zmene servera: `bash tools/zabal_server_pre_druhy_mac.sh && cp Congressa_server_pre_druhy_Mac.zip web/assets/`), `assets/Congressa-ako-pripravit-konferenciu.pdf`, `assets/Congressa-sprava-na-dialku.pdf` (kópie z `docs/navody/`; zdroje `docs/navody/zdroj/*.html`, PDF cez headless Chromium/Brave `--print-to-pdf`).
