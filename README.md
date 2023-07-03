# Analisi e valutazione dell’impatto della metilazione sulle pathway biologiche in pazienti affetti da cancro al colon
Repository contenente il progetto di tesi triennale in informatica.
In particolare:
* **pipeline.Rmd** contiene il codice della pipeline presentata nella tesi.
* **consider_covariates.Rmd** è un'estensione del lavoro fatto per la tesi, andando a considerare nei vari passi della pipeline gli effetti di alcune covariate (variabili cliniche).

L'intento del progetto è di studiare l’impatto della metilazione sul funzionamento delle pathway biologiche e come tali disregolazioni possano
condurre all’individuazione di casi in cui il tumore agisce in maniera
più (o meno) letale.
A tal fine, viene proposta una pipeline di analisi in cui, partendo
da dati clinici di pazienti affetti da cancro al colon e pazienti sani,
vengono effettuate una serie di fasi atte alla predizione di possibili
disfunzioni nelle pathway biologiche e alla ricerca di sottogruppi in
cui la sopravvivenza dei pazienti, intesa come il periodo di vita medio
dal momento della diagnosi, differisce particolarmente.

# 📃 Data
Il dataset usato nella pipeline può essere trovato al seguente link: https://portal.gdc.cancer.gov/projects/TCGA-COAD

