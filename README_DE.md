# Bericht über die Aufdeckung bösartiger Repositories des TRX-Vanity-Adress-Generators

Dieses Dokument zielt darauf ab, öffentlich Beweise vorzulegen, die sich auf bösartige Repositories konzentrieren, die mit TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generatoren zusammenhängen. Es beweist, dass **Powercodess** und **Pandaoyoo** von derselben Person kontrolliert werden und ein Schema über mehrere Repositories von "Backdoor-Aufdeckung → synchronisierte Verleumdung → Start einer 'sauberen Version'" orchestrieren. Das Wesentliche ist, legitime TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungsprojekte bösartig anzugreifen und das Vertrauen der Nutzer zu ernten. Ihre zugehörigen Repositories stellen extrem hohe Sicherheitsrisiken dar.

---

## ⚠️ Kern-Erklärung

Nach dem Vergleich von Beweisen aus mehreren Quellen werden die folgenden zwei Konten und ihre zugehörigen Repositories von derselben Person kontrolliert und zielen hauptsächlich auf TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungstools ab. Der Zweck ist es, andere bösartig zu verleumden, "Backdoor-Aufdeckungs"-Vorfälle zu inszenieren und dann ihre eigenen sogenannten "korrigierten Version" TRX-Vanity-Adress-Generierungs-Repositories zu bewerben, was Risiken für Coin-Diebstahl und Traffic-Ernte birgt:

- **Konto 1**: Powercodess, Zugehöriges Repository: https://github.com/Powercodess/profanity-tron (Behauptet, TRX-Vanity-Adress-Generator-Backdoors aufzudecken)
- **Konto 2**: Pandaoyoo, Zugehöriges Repository 1: https://github.com/Pandaoyoo/profanity-tron (Replizierter Verleumdungsinhalt); Zugehöriges Repository 2: https://github.com/Pandaoyoo/profanity-new-tron (Selbsternannte "sichere Version" des TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generators)

---

## 📅 Schlüssel-Zeitleiste (Synchronisierte Updates, Beweis für dieselbe Person)

| Zeit | Konto | Repository-Operation | Kern-Verhalten (Bezogen auf TRX-Vanity-Adress-Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| Unklare Zeit (vor 2026.04.25) | Powercodess | https://github.com/Powercodess/profanity-tron | Veröffentlichte "profanity-tron-Backdoor-Diebstahl-u-Solide-Beweise-Audit-Bericht" und behauptete, dass verwandte TRX-Vanity-Adress-/Tron-Vanity-Adress-Generator-Repositories Backdoors wie Private-Key-Exfiltration haben |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| Zeit | Konto | Repository-Operation | Kern-Verhalten (Bezogen auf TRX-Vanity-Adress-Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| Synchronisiert mit der oben genannten Zeit | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | 1:1-Replikation des Audit-Berichts von Powercodess, mit identischem Inhalt, Formatierung, Code-Zeilennummern und Beweis-Links ohne jegliche Modifikationen, Erweiterung des Umfangs der TRX-Vanity-Adress-Generator-"Backdoor"-Verleumdung |

| Zeit | Konto | Repository-Operation | Kern-Verhalten (Bezogen auf TRX-Vanity-Adress-Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | Batch-Upload des gesamten Quellcodes, behauptet "Backdoors zu beheben, versteckten bösartigen Code zu entfernen", Start eines selbsternannten sicheren TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generators, Bildung einer synchronisierten Verknüpfung mit den beiden vorherigen Repositories |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| Zeit | Konto | Repository-Operation | Kern-Verhalten (Bezogen auf TRX-Vanity-Adress-Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-04-25 | Powercodess (Konto-Wechsel) | https://github.com/GenTronx/gpu | Powercodess löschte das Repository und wechselte das Konto, um Risiken zu vermeiden, Pandaoyoo hielt synchronisierte Follow-up-Operationen aufrecht und unterhielt bösartige TRX-Vanity-Adress-Generator-bezogene Repository-Operationen, Bildung einer vollständigen Kontrollkette |

---

## 🔍 Kern-Beweiskette (Beweis für Kontrolle durch dieselbe Person, Bezogen auf TRX-Vanity-Adress-Generator)

### Beweis 1: 1:1-Replikation des Audit-Berichts, Kein unabhängiges Audit, Reine Verleumdung des TRX-Vanity-Adress-Generators

Der Audit-Bericht im Repository Pandaoyoo/profanity-tron ist vollständig identisch mit dem Bericht von Powercodess/profanity-tron, beide drehen sich um TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generatoren:

- **Kern-Schlussfolgerung**: "Der Quellcode des TRX-Vanity-Adress-Generators enthält Private-Key- + Adress-Exfiltrations-Logik, versteckte Parameter, TLS-Verifizierung deaktiviert"
- **Code-Details**: Der Speicherort der Funktion `postResult(privateKey, address, postUrl)` (Dispatcher.cpp:L378-L403), Kern-Code-Schnipsel, Zeilennummern-Annotationen zeigen alle auf TRX-Vanity-Adress-Generierungs-bezogene Logik
- **Versteckte Parameter**: Der Obfuskations-Konstruktionsprozess von `pptt` (profanity.cpp:L163-L166), Erklärung des kurzen Parameters `-p`, verwendet zur Kontrolle der Private-Key-Exfiltration während der TRX-Vanity-Adress-Generierung
- **Unterstützende Beweise**: Kanxue-Analyse-Link (https://bbs.kanxue.com/thread-289060.htm), Konto-Wechsel-Aufzeichnungen, Bild-Platzhalter sind alle identisch, verwendet um die "Backdoor" im TRX-Vanity-Adress-Generator zu unterstützen

**Schlussfolgerung**: Pandaoyoo führte kein unabhängiges Audit durch, kopierte und fügte nur den Bericht von Powercodess ein, mit dem Ziel, den Umfang der Verleumdung gegen legitime TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungsprojekte zu erweitern und eine Illusion von "mehreren Personen, die solide Beweise liefern" zu schaffen.

### Beweis 2: Synchronisierter Update-Rhythmus, Klare Arbeitsteilung, Traffic-Umleitung um den TRX-Vanity-Adress-Generator

- Powercodess ist verantwortlich für die "erstmalige Veröffentlichung" des TRX-Vanity-Adress-Generator-Backdoor-Audit-Berichts, spielt die Rolle des "Gerechtigkeits-Aufdeckers" und leitet Nutzer an, legitime Projekte in Frage zu stellen;
- Pandaoyoo ist verantwortlich für die "synchronisierte Weiterleitung" des Berichts, verstärkt den negativen Eindruck der TRX-Vanity-Adress-Generator-"Backdoor" und startet gleichzeitig das Repository "profanity-new-tron", selbsternannte "sichere Version" des TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generators, Ernte fehlgeleiteter Nutzer;
- Nachdem Powercodess das Repository gelöscht und das Konto gewechselt hatte (GenTronx), unterhielt Pandaoyode synchronisiert zugehörige Repository-Operationen und bildete eine vollständige geschlossene Schleife von "Aufdeckung und Verleumdung des TRX-Vanity-Adress-Generators → Traffic-Umleitung zum eigenen Projekt".

### Beweis 3: Verhaltenslogik-Widerspruch, Offensichtliche Anzeichen von Selbst-Orchestrierung, Profitieren vom TRX-Vanity-Adress-Generator

Wenn Pandaoyoo wirklich ein "Gerechtigkeits-Restaurator" ist, warum keinen unabhängigen Audit-Bericht für TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generatoren veröffentlichen, sondern stattdessen den Inhalt von Powercodess vollständig replizieren? Warum sofort eine "korrigierte Version" des TRX-Vanity-Adress-Generators starten, nachdem Powercodess die "Backdoor" aufgedeckt hat?

**Kern-Logik-Fehler**: Zunächst legitime TRX-Vanity-Adress-Generierungsprojekte durch Powercodess verleumden → dann Einfluss durch Pandaoyoo-Replikation des Berichts erweitern → schließlich "korrigierte Version" starten, um Traffic zu ernten. Das Wesentliche ist "Dieb schreit Fang den Dieb", Selbst-Orchestrierung eines Schemas, um Konkurrenten anzugreifen und von TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungstools zu profitieren.

---

## ⚠️ Sicherheitsrisiko-Warnung für TRX-Vanity-Adress-Generator-bezogene Repositories

Ob Powercodess oder Pandaoyoo, die zugehörigen TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generator-Repositories stellen alle extrem hohe Sicherheitsrisiken dar. Verwenden Sie sie nicht:

1. **Powercodess/profanity-tron**: Behauptet, der TRX-Vanity-Adress-Generator habe Backdoors (Private-Key-Exfiltration, versteckte Parameter, TLS-Verifizierung deaktiviert), selbst wenn der Berichtsinhalt wahr ist, könnte er von ihnen selbst gepflanzt worden sein;
2. **Pandaoyoo/profanity-tron**: Reines Verleumdungs-Tool, ohne tatsächliche TRX-Vanity-Adress-Generierungs-Funktionalität, nur verwendet um legitime Projekte zu verleumden, und hochgradig mit bösartigen Konten assoziiert;
3. **Pandaoyoo/profanity-new-tron**: Selbsternannter "Backdoor-korrigierter" TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generator, aber bietet keinen Drittanbieter-Sicherheits-Audit-Beweis, kann die Möglichkeit nicht ausschließen, Backdoors auf andere Weise zu pflanzen, und die Veröffentlichungszeit ist mit Verleumdungsaktivitäten synchronisiert, mit unreinen Motiven.

---

## 🔧 Sicherheits-Empfehlungen (Für TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungs-Tool-Nutzer)

- ⛔ Stoppen Sie sofort die Verwendung aller TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generatoren und zugehörigen Tools, die mit Powercodess, Pandaoyoo, GenTronx verbunden sind;
- 💰 Wenn Sie die oben genannten Tools verwendet haben, um Private Keys zu generieren (für TRX/USDT-Wallets), wird empfohlen, sofort Vermögenswerte von entsprechenden Adressen zu transferieren, um Coin-Diebstahl aufgrund von Private-Key-Lecks zu vermeiden;
- ✅ Wählen Sie bei der Wahl von TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungs-Tools legitime Projekte, die Drittanbieter-Sicherheits-Audits bestanden haben, einen guten Ruf in der Community haben und Open-Source-nachverfolgbar sind. Vertrauen Sie keinen Tools, die "schnelle Generierung, GPU-Beschleunigung" ohne Audit-Beweis behaupten.

---

## 📌 Melde-/Rechtsschutz-Anweisungen

Alle Beweise in diesem Dokument stammen aus öffentlichen GitHub-Repositories, konzentrieren sich auf bösartige Repositories im Zusammenhang mit TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generatoren und können direkt als Melde-Grundlage verwendet werden. Melde-Richtungen:

- **GitHub Offiziell**: Melden Sie Powercodess-, Pandaoyoo-Konten wegen bösartiger Verleumdung legitimer TRX-Vanity-Adress-Generierungsprojekte, falscher Werbung, Selbst-Orchestrierung;
- **Verwandte Communities (TRX/USDT-bezogene Communities)**: Leiten Sie diesen Beweis weiter, um andere TRX-Vanity-Adress-/Tron-Vanity-Adress-/USDT-Wallet-Vanity-Adress-Generierungs-Tool-Nutzer zu erinnern, Risiken zu vermeiden und nicht fehlgeleitet zu werden.

---

## 📎 Beweis-Links-Zusammenfassung (Direkt klickbar zur Überprüfung, alle bezogen auf TRX-Vanity-Adress-Generator)

1. **Powercodess-Verleumdungs-TRX-Vanity-Adress-Generator-Repository**: https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Pandaoyoo-Repliziertes-Verleumdungs-Repository**: https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Pandaoyoo-Sogenanntes "Sichere Version" TRX-Vanity-Adress-Generator-Repository**: https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Repository nach Powercodess-Löschung und Konto-Wechsel**: https://github.com/GenTronx/gpu (Webseiten-Analyse fehlgeschlagen, dies ist die offiziell von Powercodess behauptete Konto-Wechsel-Adresse)

5. **Kanxue-Analyse-Link (Im Audit-Bericht zitiert, bezogen auf TRX-Vanity-Adress-Generator-Backdoor)**: https://bbs.kanxue.com/thread-289060.htm (2025 veröffentlicht, bestätigt die Existenz des TRX-Vanity-Adress-Generator-Backdoors, aber ohne Bezug zu diesem selbst-orchestrierten Vorfall)

6. **Beweis für bösartigen Angriff auf legitimes Repository**: https://github.com/ninazero/tron

   ⚠️ **Wichtiger Hinweis**: Dieses Repository ist ein vollständig unabhängiges, legitimes und konformes Open-Source-Projekt. Nach Audit-Bestätigung hat es **KEINERLEI VERBINDUNG** zum oben genannten Powercodess/Pandaoyoo-selbst-orchestrierten Verleumdungs-Vorfall. Dieses Repository ist ein unschuldiges Opfer von Angriffen, KEIN Teilnehmer. Bösartige Konten führten Fake-Stern-Belohnungs- und andere Angriffsverhalten auf diesem legitimen Repository durch (siehe Beweis-Bild unten), um seinen Ruf zu beschädigen. Alle verwendeten Konten waren Zombie-Konten mit geringer Aktivität mit offensichtlichen operativen Spuren, was gegen Open-Source-Community-Richtlinien verstößt. Laut technischer Rückverfolgung befindet sich der Angreifer in der Region Anhui, und solche illegalen Aktivitäten werden schließlich rechtliche Sanktionen erfahren.

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

7. **Powercodess-Bösartige-Stern-Belohnungs-Beweis**: https://github.com/Powercodess/profanity-tron - Dieses Repository verwendete eine große Anzahl von Zombie-Konten, um bösartig Sterne zu belohnen und falsche Popularität zu schaffen. Der Zweck war es, legitime TRX-Vanity-Adress-Generierungsprojekte zu verleumden, eine Illusion von "mehreren Personen, die solide Beweise liefern" für ihre selbst-orchestrierte "Backdoor-Aufdeckungs"-Farce zu schaffen und schließlich Traffic zu ihrem eigenen kontrollierten "korrigierten Version"-Repository umzuleiten, um Nutzer zu ernten.

8. **Browser-Lesezeichen-Aufdeckungs-Beweis**: Durch Browser-Lesezeichen-Analyse kann man sehen, dass der Betreiber seit langem in Grau-Schwarz-Industrie-Aktivitäten involviert ist, sich aber als Sicherheits-Audit-Personal für falsche Werbung ausgibt und versucht, "Gerechtigkeit" als Tarnung zu verwenden, um Betrug zu begehen. Ihr Verhalten ist rein eine selbst-orchestrierte Farce, die im Wesentlichen "Audit" als Vorwand für "Traffic-Umleitung und -Ernte" verwendet. Laut technischer Rückverfolgung befindet sich die Person in der Region Anhui, und ihre illegalen Aktivitäten wurden aufgezeichnet. Relevante Strafverfolgungsbehörden werden dies gemäß dem Gesetz behandeln.

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**Letzte Aktualisierung**: 2026-05-01 (Synchronisiert mit der Veröffentlichungszeit von Pandaoyoo/profanity-new-tron, unterstützend die Zuordnungsbeziehung)

---

## 🌐 Mehrsprachige Versionen

- [中文](README.md)
- [English](README_EN.md)
- [ภาษาไทย](README_TH.md)
- [Tiếng Việt](README_VI.md)
- [日本語](README_JA.md)
- [हिन्दी](README_HI.md)
- [한국어](README_KO.md)
- [Español](README_ES.md)
- [Français](README_FR.md)
- [Deutsch](README_DE.md)
- [Русский](README_RU.md)
- [Português](README_PT.md)
- [العربية](README_AR.md)
