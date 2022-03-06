---
layout: post
title: "Solarwind. Atac a través de la cadena de subministrament de programari"
subtitle: "l'Altra Ràdio"

date:   2021-03-02 12:31:54 +0000
categories: altraradio
tag: Altra Ràdio
excerpt_separator: <!--more-->
---

Avui parlarem d’un concepte que no és nou però del que s’ha parlat força en els darrers mesos a causa del cas Solarwind (un programari de d’administració i control de servidors a gran escala, indispensable quan et cal gestionar molts servidors). Tot i que no és una estratègia nova, sí és un canvi de paradigma i d’escala.
<!--more-->

Van colar unes 4000 línies de codi que creaven una porta només accessible a qui la conegués. Al ser aquest un programari emprat a grans empreses i governs, a través d’aquest programari van poder accedir a molts altres servidors. 

Es calcula que va infectar com a mínim unes 18000 xarxes. I només Microsoft hi va posar uns 500 enginyers per a entendre l’atac, el seu abast i mirar de tapar el forat.

No és una cosa fàcil, sembla que darrera hi ha això que anomenen “State actors”, és a dir, serveis d’espionatge estatals.

Així doncs, van atacar un element de tota la cadena d’ús al que normalment es fa confiança doncs no és el que està en relació directa amb les dades, i els van colar un gran gol.
És que s’anomena atac a la cadena d’aprovisionament o de producció (supply-chain attack). 

El que normalment ens ve al cap és que els atacs es fan a les aplicacions que volem trencar. Sigui aquesta un sistema operatiu, un servidor de correu electrònic, un gestor de paraules de pas, etc.

Amb l’atac a la cadena de subministrament, no ens enfrontem doncs a aquestes aplicacions, sinó que mirem com estan fetes, quines llibreries de programari fan servir, etc, i s’implanta el programari maliciós o vulnerabilitats en aquestes eines, a priori no directament relacionades amb el programari al qui tothom mira de protegir,  que el nostre objectiu farà servir.

No és el primer cop que passa. Fa uns anys van colar programari maliciós de seguiment en llibreries emprada en el desenvolupament de vídeo jocs.

No que hi puguem fer gaire cosa com particulars, però està bé saber-ho, no saps mai per on vindrà la castanya, i com sempre, millor estar preparats.


