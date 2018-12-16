---
title: "Come aprire il tuo sito web con soli 2 centesimi! "
date: 2018-12-16
tags:
- News
- Metodi
- Netlify
categories:
- Metodi
cover : "https://i.ibb.co/1sZKvX2/netlify-logo.png"
draft: false
---

Oggi andremo a scoprire come aprire il tuo sito web con soli 2 centesemi, hai capito bene.
Premessa: Il dominio vale 1 un anno dopo dovrai rinnovarlo al prezzo concordato, ma intanto per 1 anno avrai lo spazio web con il dominio che preferisci.

Se hai un'attività da lanciare o semplicemente vuoi aprire un blog, questa è la soluzione ideale, ma un pochino complessa.

Se non vuoi sporcarti le mani con codici HTML (Che spiegherò passo per passo) è meglio se apri un blog con Altervista.org oppure Wordpress.
Ma come ben saprai lo spazio che riceverai sarà sempre sotto controllo (ad es: con Altervista non puoi inserire spazi pubblicitari che non siano i loro oppure gestiti dagli stessi.)

Ad esempio, se vuoi sottoscrivere un contratto di affiliazione con Awin non potrai farlo perchè contro le politiche di Altrvista, rischierai addirittura il Ban per questo.

Ma torniamo a noi.

Per questo metodo ci servirà in primis un dominio.

Io consiglio Register.it

<img src="https://i.ibb.co/Yf9Tmmg/screenshot-www-register-it-2018-12-15-17-53-21.png" alt="screenshot-www-register-it-2018-12-15-17-53-21" border="0">

Come potrete notare c'è una fantastica promozione 3 domini per 1 anno praticamente gratis!
<strong> Dovrete pagare solo 0.2 centesimi per la verifica della carta di credito! </strong>

La prima parte è finita.
Ora passiamo alla parte pratica della creazione del nostro sito web.

Ora che abbiamo il nostro nome ci serve l'hosting.

<strong> Ma cos'è l'hosting? </strong>

In pratica è lo spazio dove andremo a caricare i nostri file: Posso essere di qualsiasi tipo, file testo, multimediali oppure script.

E' di vitale importanza, perchè senza questo servizio non sarà possibile mostrare al mondo intero i nostri contenuti.

Il servizio che consiglio (ce ne sono una marea) si chiama <strong> Netlify </strong>.

Netlify è un servizio hosting open source assolutamente gratuito (se vuoi aver collegato solo 1 dominio), è un progetto relativamente nuovo in continua evoluzione, in pratica
se hai una repostory (il sito web in se) con due click puoi andare a renderlo online.

I pro:

-Assolutamente gratuito se possiedi un dominio.

-Integra automaticamente il protocollo di sicurezza HTTPS anch'esso gratuito!

-Compatibile con repostory (Li dove andremo a inserire i contenuti del nostro sito web) del calibro di: GitHub, Bitbucket e GitLab

-Aggiornamento delle repostory in tempo reale (Se andiamo a modificare od aggiungere contenuti alla repostory, tempo 10 secondi e il sito web si aggiorna)

Leggi anche: Come creare 

Precisazione.
Se hai una repostory creata con GitHub, Bitbucke o GitLab basta andare su <a href="https://www.netlify.com/"> Netlify</a> e caricare il vostro sito web.

<img src="https://i.ibb.co/hXgMgRk/Untitled.png" alt="Untitled" border="0">

Una volta caricato dovrete cambiare il dominio da esempio.netlify.it a esempio.it
Andate su Add o register domain e seguite la procedura.

Poi andate su DNS settings per completare il cambio indirizzo.

<img src="https://i.ibb.co/wNvs9Rs/2.png" alt="2" border="0">

Adesso dobbiamo cambiare Nameservers da <a href="https://www.register.it"> Register<a/> (il nostro domain provider) a quello di Netlify.

Basta prendere i nameserver da Netlify come in foto ad es: dns1.p01.nsone.net

Andare su <a href="https://www.nexcess.net/resources/tools/global-dns-checker/">DNSchecker<a/> immettere il nostro DNS e vedere l'IP relativo.

<img src="https://i.ibb.co/WcDtYfC/3.png" alt="3" border="0">

Ora andiamo su <a href="https://www.register.it"> Register <a/> Nella sezione Area Clienti.

Facciamo clic sul nostro sito web appena registrato e poi su Dominio e DNS

<img src="https://i.ibb.co/jLCdxHP/4.png" alt="4" border="0">

Poi schiacciamo su Configurazione DNS.

Ora arriva la parte importante.

Schiacciamo su "Avvia l'operazione di cambio DNS"

Per ogni dns di Netlify ad es: dns1.p01.nsone.net dobbiamo associare l'IP che abbiamo trovato ad es: 198.51.44.1
Immetterli negli spazi appositi, infatti ce ne sono 4 diversi da mettere come vedete qui.

<img src="https://i.ibb.co/wNvs9Rs/2.png" alt="2" border="0">

Per tutti i dns dobbbiamo cercare l'IP corrispondete e metterlo nella sezione richiesta.

Di solito ci mette 24 ore prima che il tuo sito web esempio.netlify.com diventi esempio.it

Una volta fatta questa modifica il vostro sito web sarà pronto.





