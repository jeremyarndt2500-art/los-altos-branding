# LOS ALTOS V2 – Branding

Permanentes Hosting der FiveM-Server-Banner via `raw.githubusercontent.com`.
Das Repo muss **public** sein, sonst sind die Raw-Links nicht ohne Token erreichbar.

| Datei | Verwendung | FiveM-Empfehlung |
|---|---|---|
| `banner_connecting.png` | `sets banner_connecting` – Verbinden-Bildschirm | 1920 x 1080 |
| `banner_detail.png` | `sets banner_detail` – Serverliste, Detailansicht | 1920 x 384 |

## Banner austauschen

Datei ersetzen, dann:

    git add -A && git commit -m "banner update" && git push

Die URL in der `server.cfg` bleibt gleich. `raw.githubusercontent.com` cached
rund 5 Minuten, danach sehen die Spieler das neue Bild.
