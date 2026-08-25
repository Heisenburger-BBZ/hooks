**Gewinn:**
Wir automatisieren die Einhaltung eines einheitlichen Commit-Standards (Conventional Commits) und stellen sicher, dass jede Änderung für das gesamte Team rückverfolgbar mit einer Ticketnummer verknüpft ist.

**Probleme:**
Der Hook kann von Entwicklern mit der Option `git commit --no-verify` umgangen werden und greift nur auf Entwickler-Rechnern, weshalb zwingend eine zusätzliche Validierung in der CI/CD-Pipeline erforderlich ist. Zudem benötigt diese Lösung eine Node.js-/npm-Umgebung im Projekt.