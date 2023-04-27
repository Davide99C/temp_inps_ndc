# Asset per il catalogo nazionale della semantica dei dati
Questo è il repository INPS per l'alimentazione del National Data Catalog (NDC): https://www.schema.gov.it/.
Esso contiene l'ontologia di INPS che descrive il patrimonio informativo dell'ente relativamente al dominio di _riscatti ricongiunzioni e rendite_ e _lavoratore domestico_.

Il catalogo nazionale della semantica dei dati, o NDC, consente:
> "Ricerca e riuso di asset semantici, tra cui ontologie, schemi dati e vocabolari controllati per supportare lo sviluppo di API semanticamente e sintatticamente interoperabili"

## Organizzazione delle informazioni

I file presenti in questo repository sono organizzati secondo la seguente alberatura:

```bash
┌─ assets/controlled-vocabularies/
│  ├─ categorie-disabilita
│  │  └─ categorie-disabilita.ttl
│  ├─ categorie-temi
│  │  └─ categorie-temi.ttl
│  ├─ categorie-moduli
│  │  └─ categorie-moduli.ttl
│  ├─ categorie-utenza
│  │  └─ categorie-utenza.ttl
│  ├─ tipo_gestione_ricongiunzione
│  │  └─ tipo_gestione_ricongiunzione.ttl
│  ├─ tipo_gestione_riscatto
│  │  └─ tipo_gestione_riscatto.ttl
│  ├─ tipo_ricongiunzione
│  │  └─ tipo_ricongiunzione.ttl
│  ├─ tipo_riscatto_privato
│  │  └─ tipo_riscatto_privato.ttl
│  ├─ tipo_riscatto_pubblico
│  │  └─ tipo_riscatto_pubblico.ttl
│  └─ frame-short.yamlld
│  └─ notes.md
├─ assets/ontologies/
│  ├─ procedura21-30-12-2022
│  │  └─ procedura21-30-12-2022.ttl
│  ├─ procedura21-31-03-2023
│  │  └─ procedura21-31-03-2023.ttl
├─ assets/schemas/
│  ├─ contratto-di-lavoro
│  │  └─ contratto-di-lavoro.oas3.yaml
│  ├─ datore-di-lavoro-domestico
│  │  └─ datore-di-lavoro-domestico.oas3.yaml
│  ├─ esito-pagamento
│  │  └─ esito-pagamento.oas3.yaml
│  ├─ lavoratore-domestico
│  │  └─ lavoratore-domestico.oas3.yaml
│  ├─ mandato-sdd
│  │  └─ mandato-sdd.oas3.yaml
│  ├─ ordine-pagamento
│  │  └─ ordine-pagamento.oas3.yaml
│  ├─ pratica-rendita
│  │  └─ pratica-rendita.oas3.yaml
│  ├─ pratica-ricongiunzione
│  │  └─ pratica-ricongiunzione.oas3.yaml
│  ├─ pratica-riscatto
│  │  └─ pratica-riscatto.oas3.yaml
│  ├─ rapporto-lavoro-domestico
│  │  └─ rapporto-lavoro-domestico.oas3.yaml
│  └─ notes.md
├─ README.md
└─ publiccode.yaml
```

Ontologie e [vocabolari controllati](https://www.agid.gov.it/it/dati/vocabolari-controllati) sono documenti [RDF](https://www.w3.org/RDF/) serializzati in formato [TURTLE](https://www.w3.org/TR/turtle/) mentre gli schemi  [Open Api 3 (OAS3)](https://spec.openapis.org/oas/v3.1.0) sono serializzati in formato [YAML](https://yaml.org/).
