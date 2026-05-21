# Introduzione a SQL con il DBMS Firebird

➡️ Corso correlato: **[Introduzione a SQL con il DBMS Firebird](https://stahe.github.io/ar-sql-firebird-janv-2006/)**

## Panoramica

Questo documento è un'introduzione al linguaggio **SQL (Structured Query Language)** applicato al **DBMS Firebird**.
Esso rivede e adatta un vecchio documento didattico scritto nel **1991 per Oracle**, che a sua volta era in gran parte ispirato alla documentazione ufficiale di Oracle e al libro:

* *SQL – Introduzione, Programmazione e Padronanza*
  di **Christian Marée** e **Guy Ledant**, pubblicato da Eyrolles. 

SQL è un **linguaggio standard utilizzato per creare, gestire ed eseguire query su database relazionali**.
È in gran parte indipendente dal sistema di gestione di database (DBMS) utilizzato, anche se alcuni DBMS introducono estensioni proprietarie. 

## Perché Firebird?

Gli esempi in questo documento utilizzano il **DBMS Firebird**.
Questa scelta è motivata da una caratteristica particolarmente pratica in un contesto didattico: un database Firebird può essere **contenuto in un unico file**.

Ciò consente, ad esempio:

* di copiare facilmente un database su una **chiavetta USB**
* utilizzarlo su **computer diversi** (a casa, all'università, in laboratorio)
* lavorare senza infrastrutture complesse

## Compatibilità SQL

Sebbene gli esempi siano scritti per Firebird, la maggior parte può essere riprodotta con altri DBMS relazionali, ad esempio:

* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle

Tutti questi sistemi utilizzano SQL, a volte con **varianti o estensioni specifiche del prodotto**.

## Destinatari

Questo documento è destinato a:

* **principianti che vogliono imparare SQL**
* persone che vogliono **ripassare le basi del linguaggio**

Si concentra sull'apprendimento dell'**SQL fondamentale**.

## Esclusioni dall'ambito di applicazione

Alcuni argomenti sono stati intenzionalmente tralasciati:

* procedure memorizzate
* programmazione SQL avanzata
* API SQL
* amministrazione dei DBMS

L'obiettivo è fornire un'**introduzione chiara e graduale al linguaggio SQL**.

Serge Tahé, gennaio 2006