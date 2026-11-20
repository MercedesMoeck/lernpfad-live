# Audio

* `klang/` — Klänge der Oberfläche (CC0), erzeugt von `scripts/build-klang.mjs`.
* `hoeren/` — 150 Hörbeispiele aus Tatoeba (CC BY / CC0 / CC BY-NC mit Nennung von Sprecher und Quelle; CC BY-NC nur, solange die App kostenlos und ohne Werbung bleibt), erzeugt von `scripts/import-hoerbeispiele.ts`.
* `hoeren-es/` — 200 spanische Hörbeispiele aus Tatoeba (18.10.2026, mit Zustimmung des Nutzers; Sprecher marcelostockle **CC BY-NC 4.0** und arh **CC BY-NC-ND 3.0**, nur solange die App kostenlos und ohne Werbung ist; ND-Dateien bleiben unverändert und werden vollständig abgespielt), erzeugt von `scripts/import-hoerbeispiele-es.ts`. Aufnahmen ohne Lizenzangabe bleiben draußen.
* `musik/` — Hintergrundmusik, **frei lizenziert** (13.10.2026, mit Zustimmung des Nutzers): zwei Stücke von Yoiyami (OpenGameArt.org, **CC0 1.0**), als MP3 mit 96 kbit/s umgewandelt und kurz ein-/ausgeblendet. Nachweis in `CREDITS.md` und auf der Lizenzseite (`src/data/lizenzen.ts`). Abgespielt von `src/lib/music.ts`.

Die frühere nicht frei lizenzierte Datei `poke-and-chill.ogg` wurde am 07.10.2026 gelöscht. Das Build-Plugin `lernpfad-ohne-musik` (`vite.config.ts`) entfernt weiterhin **lose Dateien** direkt in `audio/` aus dem Build — die Unterordner `klang`, `hoeren` und `musik` bleiben.
