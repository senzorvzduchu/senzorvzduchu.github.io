# Senzorvzduchu firmware update server

Aktualizační server (GitHub Pages, prosté HTTP) pro firmware stavebnice LaskaKit Senzorvzduchu SEN55.
Stanice s firmwarem FWL-2026-10-B1 a novějším si odsud stahují aktualizace tlačítkem „Aktualizovat firmware“
nebo automaticky (volba „Automatická aktualizace firmwaru“).

Soubory ve `firmware/update/`:
- `latest_cz.bin`, `latest_cz.bin.md5` – česká verze
- `latest_en.bin`, `latest_en.bin.md5` – anglická verze
- `loader-002.bin`, `loader-002.bin.md5` – druhostupňový zavaděč (airrohr-update-loader)

Zdrojové kódy a changelog: https://github.com/senzorvzduchu/sensors-software-Leusden/tree/sen55-gas-fix

Pozor: v nastavení Pages musí zůstat vypnuté „Enforce HTTPS“, ESP8266 stahuje přes HTTP.
