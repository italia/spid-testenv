> ⚠️ Questo repository è **deprecato**. È ora disponibile il nuovo IdP di test: https://github.com/italia/spid-testenv2

# SPID Test Environment

SPID Test Environment è rivolto ai Service Provider che vogliono testare la propria integrazione con SPID senza avere a disposizione identità SPID reali.
Consiste in un Identity Provider da far girare in locale o su un proprio server, in cui si possono liberamente configurare delle identità di test.

L'ambiente si compone di due elementi:
* l'Identity Server vero e proprio, basato su [WSO2-is](https://github.com/wso2/product-is), [(repository)](https://github.com/italia/spid-testenv-identityserver);
* un backoffice web basato su Node.js che offre un'interfaccia semplificata per la configurazione del Service Provider sull'IS e la creazione delle identità [(repository)](https://github.com/italia/spid-testenv-backoffice).

## Installazione via Docker

È stato predisposto un Docker per l'installazione plug-and-play in locale; si veda il repository https://github.com/italia/spid-testenv-docker
