cvcvvvcvfcvfcvfvfdgfdggregregre# s13-delete-me-after
s13-delete-me-after
s13-delete-me-after
You want the teacher nav section header "CARNET DE NOTES" → "GESTION DES NOTES". Let me find the section's English title and check it's safe to retranslate.

Ran 2 commands
"Gradebook" is a unique key used only as the teacher nav section title (the two test refs assert the English name, which isn't changing). So I can safely change just the French value. Opening the fix:

Ran 4 commands (1 failed), edited messages.ts
PR #3195 — the teacher nav section header now reads "GESTION DES NOTES" in French (was "Carnet de notes").

Gradebook is a unique key used only for that section title, so nothing else is affected; English stays "Gradebook". Verified: i18n:check passes, full vitest 1760/1760.
