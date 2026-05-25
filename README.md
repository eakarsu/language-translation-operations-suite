# Language Translation Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AILanguageTranslationOperationsAssistant`
- `AILanguageTranslationOperationsOperations`
- `AILanguageTranslationOperationsAnalytics`
- `AILanguageTranslationOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/language-translation-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:5820`

Seeded users:
- `admin@language-translation-operations.local / admin123`
- `manager@language-translation-operations.local / manager123`
- `analyst@language-translation-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/language-translation-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:5820 npm run smoke
```
