# Automatizovaný test kontaktního formuláře pomocí Playwrightu

## Spuštění testu na desktopu

Nainstalujte node modules pomocí příkazu:

```powershell
> npm install
```

### Spuštění testu jedenkrát

Pro prohlížeč chromium spustím test následovně:

```powershell
> npx playwright test --project chromium
```

### Spuštění testu vícekrát

Pro opakované spuštění testu slouží skript sur-contact.sh. Spustíte ho v terminálu Git Bash následovně:

```bash
$ bash run-contact.sh
```

:sparkles:
:bug::bug::bug::bug:

| Jméno | Věk | Město     |
|-------|-----|-----------|
| Jan   | 25  | Brno      |
| Eva   | 30  | Ostrava   |

1. První krok
2. Druhý krok