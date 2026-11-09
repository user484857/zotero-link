# zotero-link

Statische Weiterleitung von https auf `zotero://`-Links.

PDF-Reader auf pdf.js-Basis (Zotero, Firefox) machen `zotero://`-Links in PDFs nicht anklickbar. Ein Link der Form

```
https://user484857.github.io/zotero-link/#zotero://open-pdf/library/items/<KEY>?page=<SEITE>&annotation=<ANNOTATION>
```

ist dagegen anklickbar. Die Seite öffnet dann die Zotero-App an der markierten Stelle.

- Der Zotero-Link steht im Fragment hinter `#` und wird nicht an den Server übertragen.
- Weitergeleitet wird nur auf `zotero://open-pdf/…` und `zotero://select/…`.
