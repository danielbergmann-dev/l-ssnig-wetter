# Wetterseite für Leipzig-Lößnig

Eine kindgerechte, moderne Ein-Seiten-Webseite für den Unterricht:

- zeigt das **aktuelle Wetter** in Leipzig-Lößnig,
- visualisiert die Temperatur mit einem **Thermometer**,
- gibt eine **Oberteil-Empfehlung** (z. B. Jacke, Hoodie, T-Shirt),
- zeigt eine **übersichtliche 3-Tage-Vorhersage**.

## Starten

```bash
python3 -m http.server 8000
```

Dann im Browser öffnen: <http://localhost:8000>

## Datenquelle

Die Wetterdaten kommen von [Open-Meteo](https://open-meteo.com/) (ohne API-Key).
