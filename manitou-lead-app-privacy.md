---
title: Datenschutzerklärung – Manitou Lead App
permalink: /manitou-lead-app/
---

# Datenschutzerklärung – Manitou Lead App

Stand: 27.10.2026

## 1. Anbieter und Verantwortlichkeit

Die Manitou Lead App wird bereitgestellt von:

Springboard GmbH
Dornbachstraße 51
61440 Oberursel
Deutschland
E-Mail: [support@spring-board.dev](mailto:support@spring-board.dev)
Impressum: [https://spring-board.dev/impressum](https://spring-board.dev/impressum)

Verantwortlich für die Verarbeitung der über die App erfassten Lead- und Kontaktdaten ist der jeweilige Kunde bzw. Veranstalter, für den die App eingesetzt wird (nachfolgend „Kunde“). Der Anbieter verarbeitet diese Daten im Auftrag des Kunden und speichert sie in der vom Kunden genutzten Backend-Datenbank.

Die Datenschutzerklärung des Kunden ist in der App verlinkt. Für die Manitou Lead App verweist diese auf:
[https://www.manitou.com/de-DE/datenschutz](https://www.manitou.com/de-DE/datenschutz)

## 2. Zweck der App

Die Manitou Lead App unterstützt Vertriebsmitarbeiter auf Messen und Veranstaltungen dabei, Besucherkontakte als Leads zu erfassen, zu verwalten und mit dem Backend zu synchronisieren. Die App ist offline-first: Daten werden zunächst lokal auf dem Gerät gespeichert und erst bei bestehender Verbindung an das Backend übertragen.

## 3. Welche Daten verarbeitet werden

Bei der Nutzung der App können folgende Daten verarbeitet werden:

- **Lead- und Kontaktdaten:** Anrede, Vor- und Nachname, Unternehmen, Position, Website, Telefon, Mobiltelefon, E-Mail-Adresse, Straße, Postleitzahl, Ort und Land.
- **Messe- und Interessensdaten:** ausgewählte Veranstaltung, Marke, Branche, Besuchsgrund, Modell, Produktinteressen und freie Kommentare.
- **Fotos:** optional aufgenommene Fotos, insbesondere die Aufnahme einer Visitenkarte sowie weitere vom Nutzer hinzugefügte Bilder.
- **Technische Metadaten:** Zeitstempel der Erfassung und letzten Änderung, Bearbeiterkennung, eine zufällig erzeugte Geräte-ID, App-Version und Synchronisierungsstatus.
- **Administrationsdaten:** Name, E-Mail-Adresse, Rolle und Aktivstatus von App-Benutzern sowie Metadaten zu ausgestellten API-Schlüsseln (Bezeichnung, Erstellungs- und letzter Verwendungszeitpunkt).

Die App erhebt keine Standortdaten, greift nicht auf das Adressbuch des Geräts zu und verwendet keine Werbe-IDs, kein Tracking und keine Analyse- oder Crash-Reporting-Dienste. Es werden keine Cookies oder vergleichbaren Tracking-Technologien eingesetzt.

## 4. Verarbeitung auf dem Gerät

- Leads werden lokal in einer SQLite-Datenbank gespeichert.
- Fotos werden im app-eigenen Speicher des Geräts abgelegt.
- Der API-Schlüssel sowie Anmelde-Token für den Administrationsbereich werden im sicheren Speicher des Betriebssystems abgelegt (iOS Keychain bzw. Android Keystore).
- Die Texterkennung von Visitenkarten erfolgt ausschließlich lokal auf dem Gerät: unter Android mit Google ML Kit, unter iOS mit Apple Vision. Die Bilder und erkannten Texte werden dabei nicht an Google oder Apple übertragen.

## 5. Übermittlung an das Backend und Speicherung

Wenn eine Netzwerkverbindung verfügbar ist, werden die erfassten Daten verschlüsselt per HTTPS an das Backend übertragen und dort in einer MongoDB-Datenbank gespeichert. Die Speicherung erfolgt auf Servern in Frankfurt am Main, Deutschland (AWS eu-central-1, bereitgestellt über MongoDB Atlas).

Die Daten werden nicht an Dritte verkauft oder zu Werbezwecken weitergegeben. Eine Weitergabe erfolgt nur, soweit dies zur Erbringung des Dienstes erforderlich ist (z. B. an Hosting- und Datenbankdienstleister als Auftragsverarbeiter), gesetzlich vorgeschrieben ist oder der Kunde hierzu berechtigt ist.

## 6. Rechtsgrundlage

Die Rechtsgrundlage für die Verarbeitung der Lead- und Kontaktdaten legt der jeweilige Kunde als Verantwortlicher fest. Bei der Erfassung eines Leads wird in der App ein Hinweis mit Verlinkung auf die Datenschutzerklärung des Kunden angezeigt, den der Nutzer bestätigt. Weitere Informationen finden sich in der Datenschutzerklärung des Kunden (siehe Abschnitt 1).

## 7. Speicherdauer

Lokale Daten bleiben auf dem Gerät gespeichert, bis sie in der App gelöscht, die App deinstalliert oder die App-Daten gelöscht werden. Serverdaten werden für die Dauer der Nutzung durch den Kunden gespeichert und anschließend gelöscht, sofern keine gesetzlichen Aufbewahrungspflichten entgegenstehen. Der Kunde kann Leads und Benutzer im Administrationsbereich löschen.

## 8. Export von Daten

Berechtigte Nutzer können Daten im Administrationsbereich als CSV-Datei exportieren, per E-Mail versenden oder lokal speichern. Ab dem Zeitpunkt des Exports liegt die Verantwortung für den weiteren Umgang mit den exportierten Daten beim Kunden. Der Anbieter hat auf exportierte Dateien keinen Zugriff und keine Kontrolle. Es gelten die Datenschutzbestimmungen des Kunden.

## 9. Datensicherheit

Die Übertragung zwischen App und Backend erfolgt verschlüsselt per HTTPS. Der Zugriff auf das Backend ist über einen persönlichen API-Schlüssel geschützt; der Administrationsbereich verwendet eine separate Anmeldung. API-Schlüssel und Token werden auf dem Gerät im sicheren Speicher abgelegt. Der Anbieter trifft angemessene technische und organisatorische Maßnahmen, um die Daten gegen Verlust, Missbrauch und unbefugten Zugriff zu schützen.

## 10. Rechte der Betroffenen

Betroffene Personen haben nach der DSGVO das Recht auf:

- Auskunft über die verarbeiteten personenbezogenen Daten (Art. 15 DSGVO),
- Berichtigung unrichtiger Daten (Art. 16 DSGVO),
- Löschung (Art. 17 DSGVO),
- Einschränkung der Verarbeitung (Art. 18 DSGVO),
- Datenübertragbarkeit (Art. 20 DSGVO),
- Widerspruch gegen die Verarbeitung (Art. 21 DSGVO) sowie
- Widerruf einer erteilten Einwilligung mit Wirkung für die Zukunft (Art. 7 Abs. 3 DSGVO).

Zur Ausübung dieser Rechte wenden sich Betroffene an den Kunden bzw. den oben genannten Anbieter. Außerdem besteht das Recht, sich bei einer Datenschutz-Aufsichtsbehörde zu beschweren.

## 11. Kinder

Die App richtet sich an berufliche Nutzer im Vertrieb und nicht an Kinder. Es werden wissentlich keine Daten von Kindern erhoben.

## 12. Änderungen dieser Datenschutzerklärung

Der Anbieter kann diese Datenschutzerklärung anpassen, wenn sich die App, die Datenverarbeitung oder rechtliche Anforderungen ändern. Die jeweils aktuelle Fassung wird auf dieser Seite veröffentlicht.

## 13. Kontakt

Bei Fragen zum Datenschutz wenden Sie sich bitte an:

Springboard GmbH
E-Mail: [support@spring-board.dev](mailto:support@spring-board.dev)