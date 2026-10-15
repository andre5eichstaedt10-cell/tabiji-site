# tabiji-site

Öffentliche Seiten von Tabiji, ausgeliefert über GitHub Pages. Dieses Repo ist
absichtlich öffentlich und enthält **nur** veröffentlichte Seiten – keinen
Code, keine Daten, keine Schlüssel. Der App-Code liegt im privaten Repo
`TravelCostCalculator`.

| Datei | Quelle | Adresse |
|---|---|---|
| `privacy-policy.html` | `TravelCostCalculator/docs/privacy-policy.html` | `https://andre5eichstaedt10-cell.github.io/tabiji-site/privacy-policy.html` |
| `data-deletion.html` | hier gepflegt, Inhalt folgt der Datenschutzerklärung (§§ 3, 5, 6, 7, 10) | `https://andre5eichstaedt10-cell.github.io/tabiji-site/data-deletion.html` |

`data-deletion.html` ist die Lösch-URL im Formular „Datensicherheit“ der Play
Console. Ändert sich die Datenschutzerklärung (Speicherfristen, Dienste), diese
Seite mit anpassen.

## Aktualisieren

Die Datenschutzseite wird im App-Repo erzeugt, nie hier von Hand bearbeitet:

1. Im App-Repo: `flutter test --update-goldens test/unit/services/legal_html_test.dart`
2. `docs/privacy-policy.html` hierher kopieren, committen, pushen.

Die Adresse muss gleich bleiben – sie steht in der Play Console (Store-Eintrag
und Datensicherheit).
