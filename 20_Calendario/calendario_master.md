```dataview
TABLE stagione AS "Stagione", mesi AS "Mesi", attivita_principale AS "Focus"
FROM "agricoltura"
WHERE stagione != null
SORT file.name ASC