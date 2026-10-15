# tabiji-site

Öffentliche Seiten von Tabiji, ausgeliefert über GitHub Pages. Dieses Repo ist
absichtlich öffentlich und enthält **nur** veröffentlichte Seiten – keinen
Code, keine Daten, keine Schlüssel. Der App-Code liegt im privaten Repo
`TravelCostCalculator`.

| Datei | Quelle | Adresse |
|---|---|---|
| `privacy-policy.html` | `TravelCostCalculator/docs/privacy-policy.html` | `https://<konto>.github.io/tabiji-site/privacy-policy.html` |

## Aktualisieren

Die Datenschutzseite wird im App-Repo erzeugt, nie hier von Hand bearbeitet:

1. Im App-Repo: `flutter test --update-goldens test/unit/services/legal_html_test.dart`
2. `docs/privacy-policy.html` hierher kopieren, committen, pushen.

Die Adresse muss gleich bleiben – sie steht in der Play Console (Store-Eintrag
und Datensicherheit).
