---
layout: post
title: "Robatori de credencials a Yahoo"
subtitle: "l'Altra Ràdio"

date:   2016-10-1q 22:11:55 +0000
categories: altraradio
tag: Altra Ràdio
excerpt_separator: <!--more-->
---

Fa uns dies s'ha fet públic l'immens robatori de credencials de 500 milions (sí, 500 milions) d'usuaris a Yahoo. Un tema que la direcció ha amagat durant quasi dos anys, sembla que va passar a finals del 2014, i ja n'havien tingut un altre a principis de 2014 que sí van acomunicar.
<!--more-->

La captura da credencials podria incloure, segons el (ex?)cap de seguretat, les dades dels perfils, noms, adreces, telèfons, usari i contrasenya, data de naixement i preguntes i respostes de recuperació de contrasenyes. 

Tot. 

Diuen que els passwords estaben protegits via un hash "bcrypt" (funció matemàtica unidireccional que donada una entrada de text dóna una sortida sempre diferent i que sembla aleatòria). Pero segurament una bona part de l'altra informació pot no estar-ho. I en qualsevol cas, si els passwords que els usuaris han posat són fàcils (paraules de diccionari o altres que es proven) si s'aplica el mateix  hash a les paraules i es comparan els hash resultants, si son iguals, ja t'han caçat la teva paraula de pas!

Què fer?
Si teniu un compte sa Yahoo o Flickr, fins i tot si fa temps que no el feu servir i està mig abandonat, cal canviar-los avui mateix. 

Evidentment cal canviar les paraules de pas i altres dades del perfil de Yahoo i Flickr. Però també cal que us assegureu i canvieu, si cal, qualsevol altre contrasenya o resposta a les preguntes de recuperació que poguessiu haver replicat en altres serveis.

I si això és un greu problema, no és el més gros. La seguretat va fallar perquè Yahoo va acceptar una petició del la NSA/FIB per a modificar el software dels servidors per a poder llegir els correus enviats i rebuts. Intencionadament van introduir una vulnerabilitat que va acabar sent aprofitada per un 3er (ells diuen que una *"potència estrangera"*). 

Lliço: les portes del darrera, en els serivors o en els algoritmes de xifrat, tard o d'hora acaben sent aprofitats per tercers. 


Recodem-ho un cop més. Les contrasenyes han de ser:
* secretes! 
* llargues, més de 15 caràcters
* úniques, una de diferent per a cada servei
* no les repetim. mai
* no deduïbles
* I respondrem una burrada a les preguntes de recuperació (eg. respondre per exemple, "sargantana" sigui quina sigui la pregunta de seguretat; és possible que la xarxa ja sàpiga com estiu la nostra mascota).

Si això us complica recordar-ho tot, res millor que un bon gestor de contrasenyes, com per exemple [KeePass](https://keepass.info). I feu còpies de seguretat de la base de dades de contraeenyes en un altre suport fora del vostre ordinador!  

Sort!


