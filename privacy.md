---
---
# Informativa sulla privacy — Backup Gestionale

Ultimo aggiornamento: 23 ottobre 2026.

## Finalità

Backup Gestionale è un'integrazione privata per trasferire e conservare
copie cifrate dei backup del gestionale nell'account Google Drive
autorizzato dal proprietario.

## Accesso ai dati Google

L'integrazione utilizza rclone e l'API Google Drive per creare,
elencare, caricare, scaricare e, quando previsto dalla politica
di conservazione, eliminare i file di backup nella destinazione dedicata.

I permessi effettivamente concessi sono indicati nella schermata
di autorizzazione Google. L'integrazione viene configurata per utilizzare
i file e le cartelle necessari alla gestione dei backup.

## Credenziali e protezione

I token OAuth vengono conservati sul server utilizzato per i backup,
con accesso limitato all'utente che esegue il servizio.
Non vengono pubblicati su questo sito o nel repository GitHub.

La configurazione prevede la cifratura dei backup prima del caricamento.
Le credenziali di cifratura sono custodite dal proprietario.

## Condivisione e conservazione

L'integrazione non vende i dati e non li condivide con soggetti terzi
per finalità pubblicitarie. Google Drive è utilizzato come servizio
di archiviazione ed è soggetto alle condizioni e alle norme di Google.

I backup vengono conservati fino alla loro eliminazione da parte
del proprietario o secondo la politica di conservazione configurata.

## Revoca dell'accesso

Il proprietario può revocare l'autorizzazione dalle impostazioni
di sicurezza del proprio account Google e cancellare i file da Drive.
La revoca interrompe i successivi trasferimenti.

## Contatti

Responsabile dell'integrazione: FrancescoMont.
Per richieste, utilizzare il
[profilo GitHub](https://github.com/FrancescoMont).

[Torna alla homepage](./)
