---
type: slides
---

# SAVING DATAFRAME

Fantastico: hai curato le 9 colonne del df! Ora è tempo di salvare il df in un file TSV, in modo da caricarlo nel database SKIOME COLLECTION.

Facilissimo:

```python
df.to_csv("SKIOME_ERP020892_df.tsv", sep="\t", index=False)
```

Notes: Per salvare il `df` come TSV, dobbiamo usare la funzione `to_csv`. Questa funzione ha bisogno come argomenti: 
* il nome del file che vogliamo creare (`"SKIOME_ERP020892_df.tsv"`). Fai attenzione che per ogni progetto curato ti chiediamo di salvare il file che crei con il prefisso "SKIOME_", per indicare che i metadati di quel progetto sono stati curati. 
* il separatore, `sep = "\t"`
* l'opzione `index=False`, che serve per non fare salvare il numero degli indici (delle righe)

Ed è fatta!

---

# Let's code!
