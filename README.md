<p align="center">
  <a href="https://rl-mobile.de"><img src="assets/rl-mobile-hero.svg?v=20261113-monochrome" alt="Philipp Reinholz · RL-Mobile. Handel denken. Systeme bauen. Die Software hinter RL-Mobile." width="100%" /></a>
</p>

<p align="center">
  <a href="https://rl-mobile.de"><strong>RL-Mobile ↗</strong></a>
  &nbsp; / &nbsp;
  <a href="#was-ich-baue">Projekte</a>
  &nbsp; / &nbsp;
  <a href="#womit-ich-arbeite">Technik</a>
  &nbsp; / &nbsp;
  <a href="https://github.com/PhilippV22?tab=repositories">Repositories</a>
</p>

## Moin, ich bin Philipp.

Ich bin **Philipp Reinholz**, Inhaber von **RL-Mobile**. Mein Geschäft sind gebrauchte iPhones. Dafür entwickle ich die Software, die Geräte, Abläufe und Verkauf miteinander verbindet: Warenwirtschaft, Shopware-Erweiterungen, Automationen und ein eigenes KI-Büro.

Mich interessiert, was im Alltag funktioniert. Ein Gerät durchläuft Ankauf, Lager, gegebenenfalls Reparatur, Verkauf und Versand. Meine Systeme bilden diese Schritte ab und verbinden die Werkzeuge dahinter.

## Was ich baue

<table>
<tr>
<td width="50%" valign="top">

### 01 / RL-ERP

**Die Warenwirtschaft.** Geräteverwaltung, Ankauf, Lager, Reparatur, Verkauf und Versand. Dazu eBay- und Shopware-Abgleich, Dokumente und die gemeinsamen RL-Accounts.

</td>
<td width="50%" valign="top">

### 02 / RL-Base

**Die gemeinsame Plattform.** Installation und Verwaltung der RL-Plugins über eine Oberfläche. Datenbank, verschlüsselte Backups, n8n und HTTPS als zentrale Basisdienste.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 / RL-Office

**Das KI-Büro.** Eine gemeinsame Oberfläche für Manager Mike, Marketing-Assistent Don und persönlichen Assistenten Vito. Mit Telegram-Anbindung und Werkzeugen für Aufgaben und Workflows.

</td>
<td width="50%" valign="top">

### 04 / RL-KABot

**Workflows für den Ankauf.** Browser-Automation mit Playwright, n8n-Workflows, Bedienportal und Discord-Anbindung. Ergänzt um Bildvorbereitung für KI-Prüfungen und einen KI-Kostenwächter.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 05 / RL-Shopware

**Der Shop und seine Erweiterungen.** Shopware 6.7 mit eigenen Plugins für Storefront-Design, ERP-Synchronisation, Produktstatistik, Google-Anbindung und Widerrufsformular.

</td>
<td width="50%" valign="top">

### 06 / RL-Monitor

**Der Blick auf den Server.** CPU, Arbeitsspeicher, Netzwerkverkehr und Prozesse in Echtzeit. Ein eigenständiger Dienst, der auch ohne RL-Office und RL-ERP funktioniert.

</td>
</tr>
</table>

Die RL-Systeme liegen in **privaten Repositories**. Hier zeige ich ihren Zweck und ihr Zusammenspiel.

<p align="center">
  <img src="assets/rl-ecosystem.svg?v=20261113-monochrome" alt="RL-ERP, RL-Office, RL-KABot und RL-Shopware auf der gemeinsamen RL-Base. Zentrale Dienste: Datenbank, Backup, n8n und HTTPS. Ergänzt durch RL-Monitor." width="100%" />
</p>

## Womit ich arbeite

| Bereich | Technik in meinen Projekten |
| :--- | :--- |
| Backend & Schnittstellen | Python · Flask · FastAPI · Node.js |
| Oberflächen & Shop | JavaScript · HTML · CSS · PHP · Twig · Shopware |
| Automation & KI | n8n · Playwright · KI-APIs · Telegram- und Discord-Anbindungen |
| Betrieb & Daten | Linux · Docker Compose · MariaDB · Redis · restic · GitHub |

Die RL-Plugins folgen einem gemeinsamen Aufbau: dieselbe `./rl`-Kommandozeile, Docker Compose, eine einheitliche Anmeldung für die angebundenen Anwendungen und gemeinsame Basisdienste. So können die Komponenten einzeln laufen und sich auf demselben Server verbinden.

---

<p align="center">
  <strong>RL-Mobile — gebrauchte iPhones. Eigene Systeme dahinter.</strong><br />
  <a href="https://rl-mobile.de">rl-mobile.de ↗</a>
</p>

<details>
<summary>Zu den Projektangaben</summary>

Die Beschreibungen wurden mit den Projekt-READMEs und den vorhandenen Markenunterlagen abgeglichen. [Grundlage und Pflegehinweise](docs/profile-facts.md).

</details>
