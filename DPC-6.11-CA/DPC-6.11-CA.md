


![logo_CAOC](Aspose.Words.56f09d83-6f4f-4c66-82ba-6b1a5ebfec47.001.png)



<a name="_gjdgxs"></a><a name="_30j0zll"></a>**Declaració de Pràctiques de Certificació**

**Entitat de Certificació del Consorci AOC**


















Referència:	D1111\_E0650\_N-DPC  Consorci AOC

Versió:		6.11

Data:		10/01/2024

La versió original en vigor d'aquest document es troba en format electrònic publicada en el lloc web del Consorci AOC i pot ser accessible a través de la següent URL: https://epscd.aoc.cat/regulacio


|Versió|Resum dels canvis|Data|
| :-: | :- | :-: |
|5\.0|Adaptació a EIDAS|9/5/2018|
|6\.0|Creació de nova declaració de pràctiques de certificació unificada. Es numera com a versió 6.0 a l'efecte de gestió documental.|26/07/2018|
|6\.1|<p>- Revisió anual de la documentació, post auditoria eIDAS.</p><p>- Alineat document amb RFC 3647.</p><p>- “*1.1. Presentació*”: indicada prevalença de les guies del CA/Browser Forum sobre la propia DPC.</p><p>- “*1.5.5. Freqüència de revisió*”: creat apartat.</p><p>- “*4.4.3. Publicació del certificat*”: indicada possibilitat de publicació de certificats si es disposa del consentiment exprés.</p><p>- “*4.10.7. Freqüència d'emissió de llistes de revocació de certificats (LRCs)*”: afegida freqüència de publicació de la CRL.</p><p>- “*5.2.2. Número de persones per tasca*”: especificada la redundancia de rols per certes tasques.</p><p>- “*6.5.3. Freqüència de revisió de les configuracions dels sistemes de confiança*”: creat apartat.</p><p>- “*9.4. Protecció de dades personals*”: ajustades descripcions i actualitzada legislació aplicable, incloent RGPD i la LOPDGDD.</p><p>- “*9.12.1. Procediment per a les modificacions*”: reformulat apartat</p><p>- Eliminades referències a signatura de codi.</p><p>- Realitzats petits ajustos de congruència als textos.</p>|24/07/2019|
|6\.2|<p>- Adaptació a requeriments del CAB-Forum: alineat amb tots els apartats de la RFC 3647:</p><p>- Inclusió de 1.6 "Definicions i acrònims"</p><p>- Inclusió de 7.3: “Perfils d’OCSP”</p>|31/03/2020|
|6\.3|<p>- Introducció de la identificació per videoconferència en l'apartat 3.2.3</p><p>- Altres canvis menors</p>|21/05/2020|
|6\.4|<p>- Inclusió de certificats d'autenticació i signatura de treballador públic de nivell mitjà i de nivell alt.</p><p>- Procediment de generació de l'última CRL en cas de compromís de claus o finalització del servei. Secció 4.10.9</p>|03/08/2020|
|6\.5|- Adequació a la llei 6/2020, d'11 de novembre, reguladora de determinats aspectes dels serveis electrònics de confiança.|27/01/2021|
|6\.6 |<p>- Apartat 3.2.5: S’afegeix informació verificada per a certificats SSL.</p><p>- Apartat 4.10.1: noves causes de revocació.</p><p>- Apartat 4.10.12: adaptació dels requeriments per compromís de clau.</p><p>- Apartat 5.3.1: qualificació de l’especialista de validació.</p><p>- Apartat 5.7.3: adaptació compromís de clau privada </p><p>- Apartat 6.1.9: adaptació de propòsits d’ús clau </p><p>- Apartat 6.2.1.1: cas de pèrdua de qualificació del dispositu segur de creació de signatura. </p><p>- Apartat 7.1: perfil de certificat. Aclaració d’entropia mínima del número de sèrie  </p><p>- Apartat 9.5.2: Propietat intel·lectual de la DPC i PCs</p><p>- Apartat 9.14: es relaciona tota la normativa aplicable.</p>|20/07/2021|
|6\.7|<p>- Apartat 4.7.1: modificada numeració de 4.8 a 4.7.1 d’acord amb la RFC3647</p><p>- Apartat 4.9.7: periodicitat i temps d’emissions CRLs</p><p>- Apartat 4.10.1: consulta d’estat de revocació de certificats caducats</p><p>- Apartat 9.4.4: Modificat període màxim de notificació al APDCAT</p><p>- Apartat 9.6.4.1 : instruccions addicionals per verificació</p><p>- Apartat 9.14: actualització del marc normatiu i de seguretat</p>|08/06/2022|
|6\.8|- Apartat 1.5.2. Actualització de les dades de contacte de l'organització |29/03/2023|
|6\.9|<p>- Apartat 6.1.9: Aclaracions us de claus privades</p><p>- Apartat 9.6.3.1.1: Aclaracions referents a PC</p><p>- Eliminació de referències a QWAC i QTSA </p><p>- Canvi de URLs a web epscd.aoc.cat</p>|10/05/2023|
|6\.10|<p>- Apartats 4.9.13 a 4.9.18: eliminació de la referència a la suspensió de certificats.</p><p>- Apartats 1.1.1.2 i 1.2.2: inclusió del Certificat T-CATP pseudònim.</p><p>- Modificació de l'apartat 4.9.3: Inclusió de la revocació de certificats pel propi usuari via web.</p>|15/11/2023|
|6\.11|- Canvi d’adreça del prestador.|10/01/2024|
#

# <a name="_1fob9te"></a>**Índex**


[1. Introducció](#_toc150443510)

[1.1. Presentació](#_toc150443511)

[1.1.1. Tipus i classes de certificats](#_toc150443512)

[1.1.1.1. Certificats de ciutadania](#_toc150443513)

[1.1.1.2. Certificats Personals del Sector Públic](#_toc150443514)

[1.1.1.3. Certificats de Dispositius i Infraestructures](#_toc150443515)

[1.1.2. Jerarquies](#_toc150443516)

[1.1.3. Emissió de certificats de proves](#_toc150443517)

[1.2. Nom del document i identificació](#_toc150443518)

[1.2.1. Identificació d’aquest document](#_toc150443519)

[1.2.2. Identificació de polítiques de certificació cobertes per aquesta DPC](#_toc150443520)

[1.3. Entitats participants](#_toc150443521)

[1.3.1. Prestador de serveis de confiança](#_toc150443522)

[1.3.2. Entitat de Certificació Arrel](#_toc150443523)

[1.3.3. Entitats de Certificació subordinades](#_toc150443524)

[1.3.4. Entitats de Registre](#_toc150443525)

[1.3.5. Usuaris finals](#_toc150443526)

[1.3.5.1. Sol·licitants de certificats](#_toc150443527)

[1.3.5.2. Subscriptors de certificats](#_toc150443528)

[1.3.5.3. Posseïdors de claus o signatàries](#_toc150443529)

[1.3.5.4. Tercer que confia en els certificats](#_toc150443530)

[1.4. Ús dels certificats](#_toc150443531)

[1.4.1. Ús típic dels certificats](#_toc150443532)

[1.4.2. Usos prohibits](#_toc150443533)

[1.5. Administració de la Declaració de Pràctiques](#_toc150443534)

[1.5.1. Organització que administra l'especificació](#_toc150443535)

[1.5.2. Dades de contacte de l'organització](#_toc150443536)

[1.5.3. Persona que determina la conformitat d'una Declaració de Pràctiques de Certificació (DPC) amb la política](#_toc150443537)

[1.5.4. Procediment d’aprovació](#_toc150443538)

[1.5.5. Freqüència de revisió](#_toc150443539)

[1.6 DEFINICIONS i ACRÒNIMS](#_toc150443540)

[1.6.1 Definicions](#_toc150443541)

[1.6.2. Acrònims](#_toc150443542)

[2. Publicació d'informació i directori de certificats](#_toc150443543)

[2.1. Directori de certificats](#_toc150443544)

[2.2. Publicació d'informació de l'Entitat de Certificació](#_toc150443545)

[2.3. Freqüència de publicació](#_toc150443546)

[2.4. Control d'accés](#_toc150443547)

[3. Identificació i autenticació](#_toc150443548)

[3.1. Gestió de nom](#_toc150443549)

[3.1.1. Tipus de noms](#_toc150443550)

[3.1.1.1. Estructura sintàctica](#_toc150443551)

[3.1.1.2. Perfils dels certificats](#_toc150443552)

[3.1.2. Significat dels noms](#_toc150443553)

[3.1.3. Utilització de pseudònims](#_toc150443554)

[3.1.4. Interpretació de formats de noms](#_toc150443555)

[3.1.5. Unicitat dels noms](#_toc150443556)

[3.1.6. Seqüència i freqüència de rotació laboral](#_toc150443557)

[3.1.7. Resolució de conflictes relatius a noms](#_toc150443558)

[3.2. Validació inicial de la identitat](#_toc150443559)

[3.2.1. Prova de possessió de clau privada](#_toc150443560)

[3.2.2. Autenticació de la identitat d'una organització](#_toc150443561)

[3.2.2.1. Entitats de Registre](#_toc150443562)

[3.2.3. Autenticació de la identitat d’una persona física](#_toc150443563)

[3.2.3.1. Elements d’identificació](#_toc150443564)

[3.2.3.2. Validació dels elements d’identificació](#_toc150443565)

[3.2.3.3. Necessitat de presència personal](#_toc150443566)

[3.2.3.4. Vinculació de la persona física amb l’organització](#_toc150443567)

[3.2.4. Informació no verificada](#_toc150443568)

[3.2.5 Criteris d'interoperabilitat](#_toc150443569)

[3.3. Identificació i autenticació de sol·licituds de renovació](#_toc150443570)

[3.3.1. Validació per a la renovació de certificats](#_toc150443571)

[3.3.2. Validació per a la renovació de certificats després de la revocació](#_toc150443572)

[4. Característiques d'operació del cicle de vida dels certificats](#_toc150443573)

[4.1. Sol·licitud d'emissió de certificat](#_toc150443574)

[4.1.1. Legitimació per sol·licitar l'emissió](#_toc150443575)

[4.1.2. Procediment d'alta; Responsabilitats](#_toc150443576)

[4.2. Processament de la sol·licitud de certificació](#_toc150443577)

[4.3. Emissió de certificat](#_toc150443578)

[4.3.1. Accions de l'Entitat de Certificació durant el procés d'emissió](#_toc150443579)

[4.3.2. Comunicació de l'emissió al subscriptor](#_toc150443580)

[4.4. Acceptació del certificat](#_toc150443581)

[4.4.1. Responsabilitats del Prestador de Serveis de Confiança](#_toc150443582)

[4.4.2. Conducta que constitueix acceptació del certificat](#_toc150443583)

[4.4.3. Publicació del certificat](#_toc150443584)

[4.4.4. Notificació de l'emissió a tercers](#_toc150443585)

[4.5. Ús del parell de claus i del certificat](#_toc150443586)

[4.5.1. Ús per part dels posseïdors de claus](#_toc150443587)

[4.5.2. Ús pel tercer que confia en certificats](#_toc150443588)

[4.6. Renovació de certificats sense renovació de claus](#_toc150443589)

[4.7. Renovació de certificats amb renovació de claus](#_toc150443590)

[4.7.1. Renovació telemàtica](#_toc150443591)

[4.8. Modificació de certificats](#_toc150443592)

[4.9. Revocació de certificats](#_toc150443593)

[4.9.1. Causes de revocació de certificats](#_toc150443594)

[4.9.2. Legitimació per sol·licitar la revocació](#_toc150443595)

[4.9.3. Procediments de sol·licitud de revocació](#_toc150443596)

[4.9.4. Termini temporal de sol·licitud de revocació](#_toc150443597)

[4.9.5. Termini màxim de processament de la sol·licitud de revocació](#_toc150443598)

[4.9.6. Obligació de consulta d'informació de revocació de certificats](#_toc150443599)

[4.9.7. Freqüència d'emissió de llistes de revocació de certificats (LRCs)](#_toc150443600)

[4.9.8. Període màxim de publicació de LRCs](#_toc150443601)

[4.9.9. Disponibilitat de serveis de comprovació d'estat de certificats](#_toc150443602)

[4.9.10. Obligació de consulta de serveis de comprovació d'estat de certificats](#_toc150443603)

[4.9.11. Altres formes d'informació de revocació de certificats](#_toc150443604)

[4.9.12. Requeriments especials en cas de compromís de la clau privada](#_toc150443605)

[4.9.13. Període de validesa dels certificats](#_toc150443606)

[4.10. Serveis de comprovació d'estat de certificats](#_toc150443607)

[4.10.1. Característiques d'operació dels serveis](#_toc150443608)

[4.10.2. Disponibilitat dels serveis](#_toc150443609)

[4.10.3. Altres funcions dels serveis](#_toc150443610)

[4.11. Finalització de la subscripció](#_toc150443611)

[4.12. Dipòsit i recuperació de claus](#_toc150443612)

[4.12.1. Política i pràctiques de dipòsit i recuperació de claus](#_toc150443613)

[4.12.2. Política i pràctiques d'encapsulat i recuperació de claus de sessió](#_toc150443614)

[5. Controls de seguretat física, de gestió i d'operacions](#_toc150443615)

[5.1. Controls de seguretat física](#_toc150443616)

[5.1.1. Àrees segures](#_toc150443617)

[5.1.2. Controls de seguretat física](#_toc150443618)

[5.1.3. Localització i construcció de les instal·lacions](#_toc150443619)

[5.1.4. Accés físic](#_toc150443620)

[5.1.5. Electricitat i aire condicionat](#_toc150443621)

[5.1.6. Exposició a l'aigua](#_toc150443622)

[5.1.7. Advertiment i protecció d'incendis](#_toc150443623)

[5.1.8. Emmagatzematge de suports](#_toc150443624)

[5.1.9. Tractament de residus](#_toc150443625)

[5.1.10. Còpia de seguretat fora de les instal·lacions](#_toc150443626)

[5.2. Controls de procediments](#_toc150443627)

[5.2.1. Funcions fiables](#_toc150443628)

[5.2.2. Número de persones per tasca](#_toc150443629)

[5.2.3. Identificació i autenticació per a cada funció](#_toc150443630)

[5.2.4. Rols que requereixen separació de tasques](#_toc150443631)

[5.3. Controls de personal](#_toc150443632)

[5.3.1. Requisits d'historial, qualificacions, experiència i autorització](#_toc150443633)

[5.3.2. Requisits de formació](#_toc150443634)

[5.3.3. Requisits i freqüència d’actualització formativa](#_toc150443635)

[5.3.4. Sancions per accions no autoritzades](#_toc150443636)

[5.3.5. Requisits de contractació de professionals](#_toc150443637)

[5.3.6. Subministrament de documentació al personal](#_toc150443638)

[5.4. Procediments d’auditoria de seguretat](#_toc150443639)

[5.4.1. Tipus d'esdeveniments registrats](#_toc150443640)

[5.4.2. Freqüència de tractament de registres d'auditoria](#_toc150443641)

[5.4.3. Període de conservació de registres d'auditoria](#_toc150443642)

[5.4.4. Protecció dels registres d’auditoria](#_toc150443643)

[5.4.5. Procediments de còpia de seguretat](#_toc150443644)

[5.4.6. Localització del sistema d'acumulació de registres d'auditoria](#_toc150443645)

[5.4.7. Notificació de l'esdeveniment d'auditoria al causant](#_toc150443646)

[5.4.8. Anàlisi de vulnerabilitats](#_toc150443647)

[5.5. Arxiu d’informacions](#_toc150443648)

[5.5.1. Tipus d'esdeveniments registrats](#_toc150443649)

[5.5.2. Període de conservació de registres](#_toc150443650)

[5.5.3. Protecció de l’arxiu](#_toc150443651)

[5.5.4. Procediments de còpia de seguretat](#_toc150443652)

[5.5.5. Requisits de segell de cautela de data i hora](#_toc150443653)

[5.5.6. Localització del sistema d'arxiu](#_toc150443654)

[5.5.7. Procediments d'obtenció i verificació d'informació d'arxiu](#_toc150443655)

[5.6. Renovació de claus](#_toc150443656)

[5.7. Compromís de claus i recuperació de desastre](#_toc150443657)

[5.7.1. Procediment de gestió d'incidències i compromisos](#_toc150443658)

[5.7.2. Corrupció de recursos, aplicacions o dades](#_toc150443659)

[5.7.3. Compromís de la clau privada de l'Entitat](#_toc150443660)

[5.7.4. Desastre sobre les instal·lacions](#_toc150443661)

[5.8. Finalització del servei](#_toc150443662)

[5.8.1. L’Entitat de Certificació](#_toc150443663)

[5.8.2. Entitat de Registre](#_toc150443664)

[6. Controls de seguretat tècnica](#_toc150443665)

[6.1. Generació i instal·lació del parell de claus](#_toc150443666)

[6.1.1. Generació del parell de claus](#_toc150443667)

[6.1.1.1. Requisits per a tots els certificats](#_toc150443668)

[6.1.2. Enviament de la clau privada al subscriptor](#_toc150443669)

[6.1.3. Enviament de la clau pública a l'emissor del certificat](#_toc150443670)

[6.1.4. Distribució de la clau pública del Prestador de Serveis de Confiança](#_toc150443671)

[6.1.5. Mides de claus](#_toc150443672)

[6.1.6. Generació de paràmetres de clau pública](#_toc150443673)

[6.1.7. Comprovació de qualitat de paràmetres de clau pública](#_toc150443674)

[6.1.8. Generació de claus en aplicacions informàtiques o en béns d'equip](#_toc150443675)

[6.1.9. Propòsits d'ús de claus](#_toc150443676)

[6.2. Protecció de la clau privada](#_toc150443677)

[6.2.1. Mòduls de protecció de la clau privada](#_toc150443678)

[6.2.1.1. Estàndards dels mòduls criptogràfics](#_toc150443679)

[6.2.1.2. Cicle de vida de les targetes amb circuit integrat](#_toc150443680)

[6.2.2. Control per més d'una persona sobre la clau privada](#_toc150443681)

[6.2.3. Dipòsit de la clau privada](#_toc150443682)

[6.2.4. Còpia de seguretat de la clau privada](#_toc150443683)

[6.2.5. Arxiu de la clau privada](#_toc150443684)

[6.2.6. Introducció de la clau privada en el mòdul criptogràfic](#_toc150443685)

[6.2.7. Emmagatzematge de la clau privada en el mòdul criptogràfic](#_toc150443686)

[6.2.8. Mètode d'activació de la clau privada](#_toc150443687)

[6.2.9. Mètode de desactivació de la clau privada](#_toc150443688)

[6.2.10. Mètode de destrucció de la clau privada](#_toc150443689)

[6.2.11. Classificació dels mòduls criptogràfics](#_toc150443690)

[6.3. Altres aspectes de gestió del parell de claus](#_toc150443691)

[6.3.1. Arxiu de la clau pública](#_toc150443692)

[6.3.2. Períodes d'utilització de les claus públiques i privada](#_toc150443693)

[6.4. Dades d'activació](#_toc150443694)

[6.4.1. Generació i instal·lació de les claus d'activació](#_toc150443695)

[6.4.2. Protecció de les dades d'activació](#_toc150443696)

[6.4.3. Altres aspectes de les dades d'activació](#_toc150443697)

[6.5. Controls de seguretat informàtica](#_toc150443698)

[6.5.1. Requisits tècnics específics de seguretat informàtica](#_toc150443699)

[6.5.2. Avaluació del nivell de seguretat informàtica](#_toc150443700)

[6.5.3. Freqüència de revisió de les configuracions dels sistemes de confiança](#_toc150443701)

[6.6. Controls tècnics del cicle de vida](#_toc150443702)

[6.6.1. Controls de desenvolupament de sistemes](#_toc150443703)

[6.6.2. Controls de gestió de seguretat](#_toc150443704)

[6.6.3. Avaluació del nivell de seguretat del cicle de vida](#_toc150443705)

[6.7. Controls de seguretat de xarxa](#_toc150443706)

[7. Perfils de certificats i llistes de revocació de certificats](#_toc150443707)

[7.1. Perfil de certificat](#_toc150443708)

[7.1.1. Número de versió](#_toc150443709)

[7.1.2. Extensions de certificat](#_toc150443710)

[7.1.3. Identificadors d'objecte d'algorismes](#_toc150443711)

[7.1.4. Formats de nom](#_toc150443712)

[7.1.5. Restriccions de noms](#_toc150443713)

[7.1.6. Identificador d'objecte de política de certificat](#_toc150443714)

[7.1.7. Ús de l'extensió restriccions de política](#_toc150443715)

[7.1.8. Sintaxi i semàntica dels qualificadors de política](#_toc150443716)

[7.1.9. Semàntica del procés de l'extensió crítica de la política de certificat](#_toc150443717)

[7.1.10. Especificacions tècniques per a totes les Entitat de Certificació](#_toc150443718)

[7.2. Perfil de la llista de revocació de certificats](#_toc150443719)

[7.3 Perfil de OCSP](#_toc150443720)

[8. Auditoria de conformitat](#_toc150443721)

[8.1. Freqüència de l'auditoria de conformitat](#_toc150443722)

[8.2. Identificació i qualificació de l'auditor](#_toc150443723)

[8.3. Relació de l'auditor amb l'entitat auditada](#_toc150443724)

[8.4. Relació d'elements objecte d'auditoria](#_toc150443725)

[8.5. Accions a emprendre com a resultat d'una falta de conformitat](#_toc150443726)

[8.6. Tractament dels informes d'auditoria](#_toc150443727)

[9. Requisits comercials i legals](#_toc150443728)

[9.1. Imports](#_toc150443729)

[9.1.1. Import d'emissió i renovació de certificats](#_toc150443730)

[9.1.2. Import d'accés a certificats](#_toc150443731)

[9.1.3. Import d'accés a informació d'estat de certificat](#_toc150443732)

[9.1.4. Imports d'altres serveis](#_toc150443733)

[9.1.5. Política de reintegrament](#_toc150443734)

[9.2. Capacitat financera](#_toc150443735)

[9.2.1. Segur de responsabilitat civil](#_toc150443736)

[9.2.2. Altres actius](#_toc150443737)

[9.2.3. Cobertura d’assegurança per a subscriptors i tercers que confien en certificats](#_toc150443738)

[9.3. Confidencialitat](#_toc150443739)

[9.3.1. Informacions confidencials](#_toc150443740)

[9.3.2. Informacions no confidencials](#_toc150443741)

[9.3.3. Responsabilitat per a la protecció d'informació confidencial](#_toc150443742)

[9.4. Protecció de dades personals](#_toc150443743)

[9.4.1. Política de Protecció de Dades Personals](#_toc150443744)

[9.4.2. Dades de caràcter personal no disponibles a tercers](#_toc150443745)

[9.4.3. Dades de caràcter personal disponibles a tercers](#_toc150443746)

[9.4.4. Responsabilitat corresponent a la protecció de dades personals](#_toc150443747)

[9.4.5. Gestió d'incidències relacionades amb les dades de caràcter personal](#_toc150443748)

[9.4.6. Tractament de dades de caràcter personal](#_toc150443749)

[9.4.7. Comunicació de dades personals](#_toc150443750)

[9.5. Drets de propietat](#_toc150443751)

[9.5.1. Propietat dels certificats i informació de revocació](#_toc150443752)

[9.5.2. Propietat de la Declaració de Pràctiques de Certificació i les Polítiques de Certificació](#_toc150443753)

[9.5.3. Propietat de la informació relativa a noms](#_toc150443754)

[9.5.4. Propietat de claus](#_toc150443755)

[9.6. Obligacions i responsabilitat civil](#_toc150443756)

[9.6.1. L'Entitat de Certificació](#_toc150443757)

[9.6.1.1. Obligacions i altres compromisos](#_toc150443758)

[9.6.1.2. Garanties ofertes](#_toc150443759)

[9.6.1.2.1. Garanties ofertes als subscriptors](#_toc150443760)

[9.6.1.2.2. Garanties ofertes als verificadors](#_toc150443761)

[9.6.2. Entitats de Registre](#_toc150443762)

[9.6.2.1. Obligacions i altres compromisos](#_toc150443763)

[9.6.2.1.1. Obligacions de les Entitats de Registre Internes](#_toc150443764)

[9.6.2.1.2. Entitat de Registre Virtual](#_toc150443765)

[9.6.2.1.3. Entitat de Registre Col·laboradora](#_toc150443766)

[9.6.2.2. Garanties ofertes a subscriptor i verificadors](#_toc150443767)

[9.6.2.2.1. Garantia del Consorci AOC per als serveis de certificació digital](#_toc150443768)

[9.6.2.2.2. Exclusió de la garantia](#_toc150443769)

[9.6.3. Subscriptors](#_toc150443770)

[9.6.3.1. Obligacions i altres compromisos](#_toc150443771)

[9.6.3.1.1. Requisits per a tots els tipus de certificats](#_toc150443772)

[9.6.3.1.2. Requisits específics per als certificats de signatura electrònica qualificada](#_toc150443773)

[9.6.3.2. Garanties ofertes pel subscriptor](#_toc150443774)

[9.6.3.3. Protecció de la clau privada](#_toc150443775)

[9.6.4. Verificadors](#_toc150443776)

[9.6.4.1. Obligacions i altres compromisos](#_toc150443777)

[9.6.4.2. Garanties ofertes pel verificador](#_toc150443778)

[9.6.5. Consorci AOC](#_toc150443779)

[9.6.5.1. Obligacions i compromisos](#_toc150443780)

[9.6.5.2. Garanties ofertes als subscriptors](#_toc150443781)

[9.6.5.3. Garanties ofertes als verificadors](#_toc150443782)

[9.6.5.4. Exclusió de garanties](#_toc150443783)

[9.6.6. Directori](#_toc150443784)

[9.6.6.1. Obligacions i compromisos](#_toc150443785)

[9.6.6.2. Garanties](#_toc150443786)

[9.7. Renúncies de garanties](#_toc150443787)

[9.7.1. Rebuig de garanties de l'Entitat de Certificació](#_toc150443788)

[9.8. Limitacions de responsabilitat](#_toc150443789)

[9.8.1. Limitacions de responsabilitat de l'Entitat de Certificació](#_toc150443790)

[9.8.2. Cas fortuït i força major](#_toc150443791)

[9.9. Indemnitzacions](#_toc150443792)

[9.9.1. Clàusula d'indemnització de subscriptor](#_toc150443793)

[9.9.2. Clàusula d’indemnitat de verificador](#_toc150443794)

[9.10. Termini i finalització](#_toc150443795)

[9.10.1. Termini i finalització](#_toc150443796)

[9.10.2. Supervivència](#_toc150443797)

[9.11. Notificacions](#_toc150443798)

[9.12. Modificacions](#_toc150443799)

[9.12.1. Procediment per a les modificacions](#_toc150443800)

[9.12.2. Període i mecanismes per a notificacions](#_toc150443801)

[9.13. Resolució de conflictes](#_toc150443802)

[9.13.1. Resolució extrajudicial de conflictes](#_toc150443803)

[9.13.2. Jurisdicció competent](#_toc150443804)

[9.14. Llei aplicable](#_toc150443805)

[9.15. Conformitat amb la llei aplicable](#_toc150443806)

[9.16. Clàusules diverses](#_toc150443807)

[9.16.1. Acord íntegre](#_toc150443808)

[9.16.2. Subrogació](#_toc150443809)

[9.16.3. Divisibilitat](#_toc150443810)

[9.16.4. Aplicacions](#_toc150443811)

[9.16.5. Altres clàusules](#_toc150443812)



#



# <a name="_toc150443510"></a>**1. Introducció**

## <a name="_toc150443511"></a>**1.1. Presentació**
Aquest document és la Declaració de Pràctiques de Certificació (DPC) del Consorci Administració Oberta de Catalunya (Consorci AOC), Prestador dels serveis de confiança (PSC) o Trust Service Provider (TSP) que opera a l'empara del previst en el Reglament (UE) núm. 910/2014 del Parlament Europeu i del Consell de 23 de juliol de 2014, relatiu a la identificació electrònica i els serveis de confiança per a les transaccions electròniques al mercat interior i pel qual es deroga la Directiva 1999/93/CE (Reglament (UE) núm. 910/2014)

En aquesta DPC es detallen el conjunt de pràctiques adoptades pel Consorci AOC com a Prestador de Serveis de Confiança  per a l'emissió de certificats electrònics  i serveis de confiança basats en els següents estàndards:

- ETSI EN 319 401 (General Policy Requirements for Trust Service Providers).

- ETSI EN 319 411-1 (Policy and security requirements for Trust Service Providers issuing certificates; Part 1: General requirements)

- ETSI EN 319 411-2 (Policy and security requirements for Trust Service Providers issuing certificates; Part 2: Requirements for trust service providers issuing EU qualified certificates)

- ETSI EN 319 412-1 (Certificate Profiles; Part 1: Overview and common data structures)

- ETSI EN 319 412-2 (Certificate Profiles; Part 2: Certificate profile for certificates issued to natural persons)

- ETSI EN 319 412-3 (Certificate Profiles; Part 3: Certificate profile for certificates issued to legal persons)

- ETSI EN 319 412-5 (Certificate Profiles; Part 5: QCStatements)

L'estructura d'aquest document està basada en l'especificació de l'estàndard “RFC3647 - Internet X.509 Public Key Infrastructure: Certificate Policy and Certification Practices Framework “, creat pel grup de treball PKIX del IETF.

La present DPC es correlaciona amb les diferents Polítiques de Certificació (PC) desenvolupades per a cada tipologia de certificats electrònics emesos sota el control del Consorci AOC, els quals són descrits a l'apartat 1.1.1 del present document. En cas de contradicció entre la present DPC i correspondents  PC prevaldrà el que es disposa en aquest document.

<a name="_toc150443512"></a>
### **1.1.1. Tipus i classes de certificats**
El Consorci AOC presta els seus serveis de certificació amb la finalitat d'emetre certificats electrònics  per a diversos usos i diferents usuaris finals. Tots els certificats que emet el Consorci AOC s'adeqüen als requeriments del Reglament UE núm. 910/2014. 

#### <a name="_toc150443513"></a>**1.1.1.1. Certificats de ciutadania**
- **Certificat qualificat de ciutadà (idCAT):** El certificat idCAT és un certificat qualificat d'identificació i signatura electrònica avançada destinat a ciutadans i ciutadanes amb veïnatge administratiu català, i per a altres persones (col·lectivament denominats "subscriptors") que necessiten relacionar-se amb les Administracions públiques i altres institucions de Catalunya. 
####
#### <a name="_toc150443514"></a>**1.1.1.2. Certificats Personals del Sector Públic**
- **Certificat d’autenticació d’empleat públic de nivell alt (T-CAT autenticació).** Permet la identificació d'un empleat públic en l'exercici de les seves funcions, com a instrument per a l'actuació en l'àmbit electrònic d'una Administració Pública, òrgan, organisme públic o entitat de dret públic català conforme al previst en la regulació aplicable. Els certificats T-CAT d'Autenticació i T-CAT de Signatura s'emeten i emmagatzemen conjuntament en un únic dispositiu criptogràfic.

- **Certificat qualificat de signatura d’empleat  públic de nivell alt (T-CAT signatura).** Permet la signatura electrònica per part d'un empleat públic en l'exercici de les seves funcions, com a instrument per a l'actuació en l'àmbit electrònic d'una Administració Pública, òrgan, organisme públic o entitat de dret públic català conforme al previst en la regulació aplicable. Els certificats T-CAT d'Autenticació i T-CAT de Signatura s'emeten i emmagatzemen conjuntament en un únic dispositiu criptogràfic.
- **Certificat qualificat d’autenticació i signatura de empleat públic de nivell mig/substancial (T-CATP).** Aquest tipus de certificats d'autenticació i signatura s'emeten per al seu ús en format programari per part de empleats públics catalans en l'exercici de les seves funcions en actuacions que no requereixin un nivell alt de seguretat, segons la regulació aplicable.

- **Certificat d'autenticació de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim autenticació).** L'emissió d'aquests certificats es farà sota la valoració prèvia de l'acreditació legal del pseudònim que haurà d'acompanyar la sol·licitud. S'acceptaran molt específicament per a usos justificats dels quals no es puguin mostrar les dades del titular i per persones que, dins de la seva organització, ja disposin de pseudònim regulat, cas dels funcionaris de presons, Mossos d'esquadra, serveis socials, etc. Exceptuant allò que té a veure amb l'ús de pseudònim, les seves característiques són iguals a les del certificat T-CAT d'Autenticació. Els certificats T-CAT amb Pseudònim i d'Autenticació i T-CAT amb Pseudònim i de Signatura s'emeten i emmagatzemen conjuntament en un únic dispositiu criptogràfic.

- **Certificat qualificat de signatura de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim signatura).** Per a l'emissió d'aquests certificats es tindran en compte les mateixes circumstàncies que en el cas dels certificats T-CAT amb Pseudònim i d'Autenticació. Excepte en el que respecta a l'ús de pseudònim, les seves característiques són iguals a les del certificat T-CAT de Signatura. Els certificats T-CAT amb Pseudònim i d'Autenticació i T-CAT amb Pseudònim i de Signatura s'emeten i emmagatzemen conjuntament en un únic dispositiu criptogràfic.
- **Certificat qualificat d'autenticació i signatura d'empleat públic amb pseudònim de nivell mig/substancial (T-CATP pseudònim):** Per a l'emissió d'aquests certificats es tindran en compte les mateixes circumstàncies que en el cas dels certificats T-CAT amb Pseudònim i d'Autenticació. Aquest tipus de certificats d'autenticació i signatura s'emeten per al seu ús en programari per part d'empleats públics catalans en l'exercici de les seves funcions en actuacions que no requereixin un nivell alt de seguretat, conforme al que es preveu en la regulació aplicable.

- **Certificat qualificat d'autenticació i signatura de persona vinculada de nivell alt (T-CAT persona vinculada):** Certificat personal d'identificació i signatura electrònica qualificada, amb càrrec opcional. Aquests certificats s'emeten i emmagatzemen en un dispositiu criptogràfic. Aquests certificats estan destinats a aquelles persones amb relació funcional o de servei amb una institució pública, però sense relació laboral amb aquesta institució. Com per exemple externalització de serveis públics.
- **Certificat qualificat d'autenticació i signatura de persona vinculada de nivell mig/substancial (T-CATP Persona vinculada):** Certificat personal d'identificació i signatura electrònica qualificada, amb càrrec opcional. Aquests certificats s'emeten i emmagatzemen en programari.

- **Certificat qualificat d'autenticació i signatura de representant davant les Administracions Públiques (T-CAT Representant)**: Certificat personal d'identificació i signatura electrònica qualificada, amb càrrec opcional. Aquest certificat s'emet en dispositiu criptogràfic. Va dirigit a persones físiques, disposa d'informació referent al titular i permet la seva identificació i la de la seva organització. Se subministra als empleats públics d’ens del sector públic de Catalunya com a element identificatiu en les comunicacions electròniques, permetent signar documents en format electrònic per fer possible els tràmits i les consultes en línia. Aquest certificat permet identificar-se com persona posseïdora d'un determinat càrrec en la seva organització.

- **Certificat qualificat d'autenticació i signatura de treballador públic de nivell alt (T-CAT treballador públic)**. Certificat personal d'identificació i signatura electrònica qualificada, emesos i emmagatzemats en dispositiu criptogràfic. Aquests certificats estan destinats a aquelles persones que mantenen una relació laboral o d'alta direcció en una entitat que integra el sector públic de Catalunya.

- **Certificat qualificat d'autenticació i signatura de treballador públic de nivell mig/substancial (T-CATP treballador públic)**. Aquest tipus de certificats d'autenticació i signatura s'emeten per al seu ús en programari per part de treballadors públics d’ens del sector públic de Catalunya en l'exercici de les seves funcions en actuacions que no requereixin un nivell alt de seguretat, conforme al que es preveu en la regulació aplicable.
####
#### <a name="_toc150443515"></a>**1.1.1.3. Certificats de Dispositius i Infraestructures**

- **Certificat d'Aplicació (Dispositiu aplicació):** Aquest certificat s'emmagatzema en un servidor (preferiblement en un dispositiu criptogràfic) i és requerit per una aplicació per segellar documents, fitxers o missatges amb l'objectiu d'assegurar la seva autenticitat i integritat. Jurídicament opera com un segell electrònic avançat de l'ens o departament de l'Administració Pública a nom de qui s'emet, segons el que preveu el Reglament (UE) núm.910/2014, encara que el seu ús queda limitat a l'intercanvi de dades entre aplicacions.

- **Certificat de Segell Electrònic Avançat (Segell nivell mig/substancial)**: Serveix per a la identificació i l'autenticació de documents, fitxers o missatges en l'exercici de les competències en l'actuació administrativa automatitzada per a la prestació de serveis públics segons el que preveu l'article 37 del Reglament (UE) núm. 910/2014. Aquest certificat pot ser utilitzat per a l'intercanvi de dades (entre administracions, administracions i ciutadans i entre administracions i empreses), la identificació i autenticació d'un sistema, servei web o aplicació, l'arxiu electrònic automatitzat, les compulses i còpies electròniques, entre uns altres. Aquests certificats s'emeten i emmagatzemen en programari.


### <a name="_toc150443516"></a>**1.1.2. Jerarquies**

Segons es detalla en el gràfic següent, a partir de 2015, la jerarquia actual de certificació del Consorci AOC s'ha vist reduïda a dues Entitats de Certificació subordinades (marcades en verd) i una Entitat de Certificació arrel:

![](Aspose.Words.56f09d83-6f4f-4c66-82ba-6b1a5ebfec47.002.png)

**L’EC-SectorPúblic**: que concentra l'emissió de certificats per al Sector Públic de Catalunya, en substitució de les antigues EC-SAFP, EC-AL, EC-UR i EC-Parlament. Aquestes Entitats de Certificació han deixat d'emetre certificats però alguns d'ells encara es troben en vigor.

Els certificats emesos sota les antigues Entitats de Certificació EC-SAFP, EC-AL, EC-UR i EC-Parlament no es regeixen per aquesta versió de la DPC. Als mateixos els resultarà d'aplicació el previst en les DPC Al, GENCAT, SAFP, PARLAMENT, UR i URV en la seva versió 5.0, 2.0, 5.0, 2.0, 7.0, 4.0, corresponent a l'última actualització de l’esmentat document abans del cessament en l'emissió de certificats a l'empara de les citades Entitats de Certificació.

**L’EC-Ciutadania**: que emet certificats electrònics a ciutadans en substitució de l'antiga EC-idCAT, la qual també ha deixat d'emetre certificats encara que alguns d'ells es troben vigents. Els certificats emesos sota l'antiga Entitat de Certificació EC-idCAT no es regeixen tampoc per aquesta versió de la DPC. Als mateixos els resultarà d'aplicació el previst en la DPC [idCAT] en la seva versió [4.0], corresponent a l'última actualització del citat document abans del cessament en l'emissió de certificats a l'empara de la citada Entitat de Certificació.

### <a name="_toc150443517"></a>**1.1.3. Emissió de certificats de proves**
El Consorci AOC pot emetre certificats de proves signats per una EC real però amb contingut fictici perquè els organismes supervisors i les entitats de validació i els desenvolupadors d'aplicacions puguin dur a terme els seus processos d'integració i/o avaluació per a la seva acceptació. El Consorci AOC incorpora en aquests certificats la següent informació de manera que qualsevol usuari pugui conèixer clarament que es tracta d'un certificat de proves sense responsabilitat:




|**Nom de l’organització**|Organització de prova|
| :- | :- |
|**NIF de l’organització**|VATES-Q0000000J|
|**Domicili**|Barcelona|
|**Codi Postal**|08008|
|**Correu electrònic**|scd@aoc.cat|
|**Primer Cognom**|de la Peça|
|**Segon Cognom**|de Proves|
|**DNI/NIE**|00000000T|


## <a name="_toc150443518"></a>**1.2. Nom del document i identificació**
### <a name="_toc150443519"></a>**1.2.1. Identificació d’aquest document**


|<a name="_17dp8vu"></a>Nom:|Declaració de Pràctiques de Certificació (DPC)|
| :- | :- |
|Versió:|6\.11|
|Descripció |Declaració de Pràctiques de Certificació del Consorci AOC|
|Data d'emissió:|10/01/2024|
|OID:|1\.3.6.1.4.1.15096.1.2.2|
|Localització:|<https://epscd.aoc.cat/>[regulacio](https://www.aoc.cat/catcert/regulacio)|



### <a name="_toc150443520"></a>**1.2.2. Identificació de polítiques de certificació cobertes per aquesta DPC**


|Tipus de Certificat|OID|Política|
| :- | :- | :- |
|Certificats de ciutadania|||
|Certificat de ciutadà (idCAT)|1\.3.6.1.4.1.15096.1.3.2.86.2|PC Ciutadà|
|Certificats personals del sector públic|||
|Certificat d'autenticació de empleat públic de nivell alt (T-CAT autenticació)|1\.3.6.1.4.1.15096.1.3.2.7.1.2|PC Certificats Personals Sector Públic|
|Certificat qualificat de signatura de empleat públic de nivell alt (T-CAT signatura)|1\.3.6.1.4.1.15096.1.3.2.7.1.1|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de empleat públic de nivell mig/substancial (T-CATP)|1\.3.6.1.4.1.15096.1.3.2.7.3.1|PC Certificats Personals Sector Públic|
|Certificat d'autenticació de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim autenticació)|1\.3.6.1.4.1.15096.1.3.2.4.1.2|PC Certificats Personals Sector Públic|
|Certificat qualificat de signatura de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim signatura)|1\.3.6.1.4.1.15096.1.3.2.4.1.1|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de empleat públic amb pseudònim de nivell mig/substancial (T-CATP pseudònim)|1\.3.6.1.4.1.15096.1.3.2.4.2|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de persona vinculada de nivell alt (T-CAT persona vinculada)|1\.3.6.1.4.1.15096.1.3.2.82.1|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de persona vinculada de nivell mitjà (T-CATP persona vinculada)|1\.3.6.1.4.1.15096.1.3.2.86.1|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de representant davant les Administracions Públiques (T-CAT representant)|1\.3.6.1.4.1.15096.1.3.2.8.1.1|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de treballador públic de nivell alt  (T-CAT treballador públic)|1\.3.6.1.4.1.15096.1.3.2.82.2|PC Certificats Personals Sector Públic|
|Certificat qualificat d'autenticació i signatura de treballador públic de nivell mitjà (T-CATP treballador públic)|1\.3.6.1.4.1.15096.1.3.2.86.3|PC Certificats Personals Sector Públic|
|Certificats de Dispositius i Infraestructures|||
|Certificat d’Aplicació (Dispositiu aplicació)|1\.3.6.1.4.1.15096.1.3.2.91.1|PC Dispositius i Infraestructures|
|Certificat de Segell Electrònic Avançat (Segell nivell mig/substancial)|1\.3.6.1.4.1.15096.1.3.2.6.2|PC Dispositius i Infraestructures|

Els documents descriptius d'aquests perfils de certificats es publiquen al web del Consorci AOC.


## <a name="_toc150443521"></a>**1.3. Entitats participants**
###
### <a name="_k595mem16eyv"></a><a name="_toc150443522"></a>**1.3.1. Prestador de serveis de confiança**
D’acord amb la terminologia del Reglament 910/2014 (UE) núm. relatiu a la identificació electrònica i els serveis de confiança per a les transaccions electròniques al mercat interior, el Consorci AOC actua en el marc d'aquesta DPC com a prestador de serveis de confiança o TSP, sent responsable de l'emissió i gestió dels certificats electrònics  generats dins de la jerarquia de certificació (PKI) esmentada anteriorment en aquest document.

### <a name="_toc150443523"></a>**1.3.2. Entitat de Certificació Arrel**
L’Entitat de Certificació Arrel és l'entitat dins de l’esmentada jerarquia de certificació que emet certificats a altres entitats de certificació i la clau pública de la qual ha estat autofirmada. La seva funció és signar el certificat d'altres Entitats de Certificació pertanyents a aquesta jerarquia de certificació.

Les dades d'identificació del Certificat Arrel de la jerarquia de certificació del Consorci AOC són els següents:

Root CA EC-ACC

|<a name="_44sinio"></a>CN:|EC-ACC|
| :- | :- |
|Hash:|88:49:7F:01:60:2F:31:54:24:6A:E2:8C:4D:5A:EF:10:F1:D8:7E:BB:76:62:6F:4A:E0:B7:F9:5B:A7:96:87:99|
|Vigència:|07/01/2031|
|Tipus de clau:|RSA 2048|


### <a name="_toc150443524"></a>**1.3.3. Entitats de Certificació subordinades**
Es denominen Entitats de Certificació Delegades o Subordinades a les entitats dins la jerarquia de certificació que emeten certificats d'entitat final, el certificat de clau pública d’aquests ha estat signat digitalment per l’Entitat de Certificació Arrel.

Les dades d'identificació de les Entitats de Certificació subordinades operades pel Consorci AOC a l'empara d'aquesta DPC són els següents:

CA EC-CIUTADANIA

|CN:|EC-Ciutadania|
| :- | :- |
|Hash:|0F:D9:9A:AE:1F:FC:D5:D9:F0:AD:76:ED:DD:CB:EF:6B:88:4C:C8:5C:16:BF:CF:A4:B5:24:61:55:D6:59:7E:D6|
|Vigència:|18/9/2030|
|Tipus de clau:|RSA 2048|

CA EC-SECTORPUBLIC

|CN:|EC-SectorPublic|
| :- | :- |
|Hash:|35:6A:5F:4D:99:4E:9E:FA:7C:AE:FC:49:17:68:91:1D:65:EC:25:97:74:65:B6:10:E2:F2:9A:A4:47:26:31:C3|
|Vigència:|18/9/2030|
|Tipus de clau:|RSA 2048|


### <a name="_toc150443525"></a>**1.3.4. Entitats de Registre**
<a name="_3j2qqm3"></a>Les Entitats de Registre són les persones físiques o jurídiques que assisteixen a les Entitats de Certificació en determinats procediments i relacions amb els sol·licitants i subscriptors de certificats, especialment als tràmits d'identificació, registre i autenticació dels subscriptors dels certificats i dels posseïdors de claus.


### <a name="_toc150443526"></a>**1.3.5. Usuaris finals**
Els usuaris finals són les persones que obtenen i utilitzen els certificats electrònics. En concret, es poden distingir els usuaris finals següents:

- Els sol·licitants de certificats.
- Els subscriptors de certificats.
- Els signants o posseïdors de claus.
- Tercer que confia en els certificats.
####
####
#### <a name="_toc150443527"></a>**1.3.5.1. Sol·licitants de certificats**
Sol·licitant és la persona física que, en nom propi o en representació d'un tercer, sol·licita l'emissió d'un certificat electrònic. 

Els requisits que ha de reunir un sol·licitant dependran del tipus de certificat sol·licitat i estan recollits en la PC aplicable a cada tipus de certificat concret.
####
#### <a name="_toc150443528"></a>**1.3.5.2. Subscriptors de certificats**
El Subscriptor és la persona física o jurídica que contracta amb el Consorci AOC la prestació dels seus serveis.

En alguns casos, el Subscriptor podrà actuar com a Punt de Verificació Presencial, assumint part de les funcions de registre i responsabilitzant-se, en tal cas, enfront del Consorci AOC, a les seves Entitats de Registre i als Usuaris finals de:

- La correcta identificació dels Sol·licitants de certificats i Signataris respecte els quals actuï com a Punt de Verificació Presencial.
- La veracitat i exactitud de tota la documentació requerida formalment per a cada classe de certificat.
- La compulsa de còpies pel que fa a la presentació de documents originals.
- La custòdia d'aquesta documentació i el lliurament de la mateixa al Consorci AOC en cas de ser requerit per fer-ho.
- Del lliurament de certificats als signants o posseïdors de claus.
####

#### <a name="_toc150443529"></a>**1.3.5.3. Posseïdors de claus o signatàries**
Els posseïdors de claus o signatàries són les persones físiques que posseeixen de forma exclusiva les claus de signatura o autenticació electròniques dels certificats, ja sigui actuant en el seu propi nom i dret, o bé, en representació d'una organització o mitjançant algun altre tipus de vinculació.

Aquestes persones físiques hauran d'estar degudament identificades en el certificat mitjançant el seu nom i cognoms o mitjançant un pseudònim, havent de també identificar-se, si escau, l'organització corresponent de forma unívoca.

Correspon al signatari o posseïdor de claus la custòdia de les dades de creació de signatura associats al certificat electrònic.

#### <a name="_toc150443530"></a>**1.3.5.4. Tercer que confia en els certificats**
S'entén per tercer que confia en els certificats (en anglès, relying party) a tota persona o organització que voluntàriament confia en un certificat emès sota alguna de les jerarquies de certificació del Consorci AOC.

Les obligacions i responsabilitats del Consorci AOC amb tercers que voluntàriament confiïn en els certificats es limitaran a les recollides en aquesta DPC, en el Reglament (UE) núm. 910/2014 i en la resta de normativa que resulti d'aplicació.

Els tercers que confiïn en aquests certificats han de tenir present les limitacions en el seu ús.


## <a name="_toc150443531"></a>**1.4. Ús dels certificats**
Aquesta secció llista les aplicacions per les quals es pot utilitzar cada tipus de certificat, establint limitacions, i prohibeix algunes aplicacions dels certificats.

### <a name="_toc150443532"></a>**1.4.1. Ús típic dels certificats**
Els certificats del Consorci AOC podran usar-se en els termes establerts per les PC. 
### <a name="_toc150443533"></a>**1.4.2. Usos prohibits**
Els certificats només es podran utilitzar dins dels límits d'ús recollits d'una manera expressa en aquesta DPC i en la corresponent PC. Qualsevol altre ús fora dels descrits en els esmentats documents, queda exclòs expressament de l'àmbit contractual i prohibits formalment. Queda expressament prohibit qualsevol ús que sigui contrari a la Llei.

Els certificats no s'han dissenyat, no es poden destinar i no s'autoritza el seu ús o revenda com a equips de control de situacions perilloses o per a usos que requereixen actuacions a prova d'errors, com el funcionament d'instal·lacions nuclears, sistemes de navegació o comunicacions aèries, o sistemes de control d'armament, on un error podria directament comportar la mort, lesions personals o danys mediambientals severs.

Els certificats d'usuari final no poden emprar-se per signar certificats de clau pública de cap tipus, ni signar llistes de revocació de certificats.

## <a name="_toc150443534"></a>**1.5. Administració de la Declaració de Pràctiques**
### <a name="_toc150443535"></a>**1.5.1. Organització que administra l'especificació**

Consorci Administració Oberta de Catalunya – Consorci AOC 

### <a name="_toc150443536"></a>**1.5.2. Dades de contacte de l'organització**

Consorci Administració Oberta de Catalunya – Consorci AOC

Domicili social: C/Salvador Espriu 45, 08908 L'Hospitalet de Llobregat

Web del Consorci AOC: [www.aoc.cat](http://www.aoc.cat)[](http://www.aoc.cat)

[](http://www.aoc.cat)Web del servei de certificació digital del Consorci AOC: <https://epscd.aoc.cat>

Web per la sol·licitud de revocacions de certificats en horari 24x7 : https://epscd.aoc.cat/formularis

Servei d’Atenció a l’Usuari: 900 90 50 90, o +34 93 272 25 01 per trucades des de l’exterior de l’estat.

### <a name="_toc150443537"></a>**1.5.3. Persona que determina la conformitat d'una Declaració de Pràctiques de Certificació (DPC) amb la política**
La persona que determina la conformitat d'una PC amb la DPC és el Responsable del Servei de Certificació Digital del Consorci AOC, basant-se en els resultats d'una auditoria a aquest efecte, realitzada per un tercer, bianualment.
### <a name="_toc150443538"></a>**1.5.4. Procediment d’aprovació** 
El sistema documental i d'organització del Consorci AOC garanteix, mitjançant l'existència i l'aplicació dels corresponents procediments, el correcte manteniment de la DPC  i de les especificacions del procediment de publicació d'especificacions de servei.

La versió inicial d'aquesta DPC és aprovada per la Comissió Executiva del Consorci AOC, que és l'òrgan col·legiat de direcció executiva del Consorci AOC. El Director Gerent del Consorci AOC és competent per aprovar les successives modificacions d'aquesta DPC.

### <a name="_toc150443539"></a>**1.5.5. Freqüència de revisió**
La DPC, les diferents PC  i els textos divulgatius (en anglès PDS: PKI Disclosure Statements), seran revisades i, si escau, actualitzades anualment. Els documents esmentats seran revisats i modificats quan es produeixi qualsevol canvi que pugui afectar al seu contingut, com poden ser modificacions legislatives, canvis en infraestructura o canvis en l'operativa dels serveis, entre d'altres.

## <a name="_toc150443540"></a>**1.6 DEFINICIONS i ACRÒNIMS**
### <a name="_toc150443541"></a>**1.6.1 Definicions**
- Prestador de Serveis de Certificació: persona física o jurídica que expedeix certificats electrònics o presta altres serveis en relació amb la signatura electrònica.
- Prestador de Serveis de Confiança (PSC): una persona física o jurídica que presta un o més serveis de confiança, bé com a prestador qualificat o com a prestador no qualificat de serveis de confiança.
- Certificat Electrònic: un document signat electrònicament per un prestador de serveis de confiança que vincula unes dades de verificació de signatura a un signant i confirma la seva identitat.
- Certificat Qualificat: Certificat expedit per un PSC  i que compleix els requisits establerts en l'Annex I del RD (UE) núm. 910/2014 en l'article 7 de la llei 6/2020, d'11 de novembre, en quant a la comprovació de la identitat i altres circumstàncies dels sol·licitants i a la fiabilitat i les garanties dels serveis de confiança que presten, de conformitat amb el Títol III de l'esmentada Llei 6/2020 d'11 de novembre
- Clau Pública i Clau Privada: la criptografia asimètrica en la que es basa la PKI utilitza un parell de claus en la qual el que queda xifrat amb una d'elles només es pot desxifrar amb l'altra i viceversa. A una d'aquestes claus se la denomina pública i queda inclosa en el certificat electrònic, mentres que l'altra es denominada privada i únicament és coneguda pel titular del certificat.
- Conformity Assessment Body: Organismes acreditats pels estats membres per a poder emetre informes de conformitat segons requeriments del Reglament (UE) núm. 910/2014.
- Dades de Creació de Signatura (Clau Privada): Són dades úniques, com codis o claus criptogràfiques privades, que el signant utilitza per a crear la signatura electrònica.
- Dades de Verificació de Signatura (Clau Pública): són les dades, com codis o claus criptogràfiques públique, que s'utilitzen per a verificar la signatura electrònica
- Dispositiu Qualificat de Creació de Signatura / de Segell electrònic (DCCF): Dispositiu de creació de signatures electròniques que compleix els requisits enumerats en l'annex II del Reglament (UE) núm. 910/2014.
- Signatura Electrònica: les dades en format electrònic annexos a altres dades electròniques o associats de manera lògica amb ells que utilitza el signant per a signar.
- Signatura Electrònica Avançada: la signatura electrònica que compleix els requisits contemplats en l'article 26 del Reglament (UE) núm. 910/2014.
- Signatura Electrònica Qualificada: una signatura electrònica avançada que es crea mitjançant un dispositiu qualificat de creació de signatures electròniques i que es basa en un certificat qualificat de signatura electrònica.
- Funció Hash: és una operació que es realitza sobre un conjunt de dades de qualsevol mida, de manera que el resultat obtingut és altre conjunt de dades de mida fixa, independentment de la mida original i que té la propietat d'estar associat unívocament a les dades inicials.
- Llistes de Certificats Revocats (LCR o CRL): llista a on figuren les relacions de certificats revocats.
- Mòdul Criptogràfic Hardware (HSM): mòdul hardware utilitzat per a realitzar funcions criptogràfique i emmagatzemar claus d'un mode segur.
- Segell de Temps Electrònic: és un tipus especial de signatura electrònica emesa per un tercer de confiança que permet garantir la integritat d'un document en una data i hora determinades.
- Segell Qualificat de Temps Electrònic: és un segell de temps electrònic que compleix els requisits establerts en l'article 42 del Reglament (UE) núm. 910/2014.
- Autoritat de Segellat de Temps (TSA): Entitat de confiança que emet segells de temps.
- Autoritat de Validació (VA): Entitat de confiança de proporciona informació sobre la validesa dels certificats electrònics i de les signatures electròniques.


### <a name="_toc150443542"></a>**1.6.2. Acrònims**
AOC: 		Administració Oberta de Catalunya

CA:    		Autoritat de Certificació (Certification Authority)    	

PC :    		Política de Certificació (Certificate Policy)

DPC:  		Declaració de Pràctiques de Certificació (Certification Practices Statement)   

ETSI:  		European Telecommunications Standard Institute

HSM:		Mòdul de seguretat criptogràfic (Hardware Security Module)

IETF: 		Internet Engineering Task Force

LDAP:		Lightweight Directory Access Protocol

LRC:  		Llista de Certificats Revocats (Certificate Revocation List)

OCSP:   	Online Certificate Status Protocol

OID:  		Identificador d'objecte único (Object identifier)

PDS   		Text de Divulgació (PKI Disclosure Statement)

PKI:   		Infraestructura de Clau Pública (Public Key Infrastructure)

PSC: 		Prestador de Serveis de Confiança
# **<a name="_toc150443543"></a>2. Publicació d'informació i directori de certificats**
## <a name="_toc150443544"></a>**2.1. Directori de certificats**
<a name="_1hmsyys"></a>El servei de directori de certificats està disponible durant les 24 hores dels 7 dies de la setmana i, en cas d'error del sistema fora de control de l’Entitat de Certificació, aquesta última realitza els seus millors esforços per a que el servei es trobi disponible de nou en el termini establert a la secció 5.7.4 d'aquesta DPC.

## <a name="_toc150443545"></a>**2.2. Publicació d'informació de l'Entitat de Certificació**
<a name="_2grqrue"></a>L'Entitat de Certificació publica les informacions següents al seu web (https://epscd.aoc.cat/):

- Les llistes de revocació de certificats (LRC) i altres informacions d'estat de revocació dels certificats.
- Els perfils dels certificats i de les llistes de revocació dels certificats.
- La DPC.
- Les PC aplicables a cada tipus de certificat.
- El text divulgatiu per a certificats electrònics.

Qualsevol canvi en les especificacions o en les condicions del servei es comunica als usuaris per l’Entitat de Certificació a través del directori.

En tots els casos es fa una referència explícita als canvis a la pàgina principal del web del servei.

No es retira la versió anterior del document objecte del canvi, però s'indica que ha estat substituït per la versió nova.

## <a name="_toc150443546"></a>**2.3. Freqüència de publicació**
La informació de l'Entitat de Certificació es publica quan es troba disponible i especialment, de forma immediata quan s'emeten les mencions relatives a la vigència dels certificats.

Els canvis en aquest document es regeixen per l'establert en la secció 9.12.1.

Als 15 (quinze) dies des de la publicació de la nova versió, es retira la referència al canvi de la pàgina principal i s'insereix en el directori.

Les versions antigues de la documentació són conservades per un període de 15 (quinze) anys per l'Entitat de Certificació, poden ser consultades pels interessats.

La informació d'estat de revocació de certificats es publica d'acord amb l'establert en la secció 4.10.7.
## <a name="_toc150443547"></a>**2.4. Control d'accés**
La DPC, les PC, els Textos divulgatius (en anglès PDS: PKI Disclosure Statements), els certificats d’EC i les LRC es publiquen en repositoris d'accés públic sense control d'accés.


# <a name="_toc150443548"></a>**3. Identificació i autenticació**
## <a name="_toc150443549"></a>**3.1. Gestió de nom**
En aquesta secció s'estableixen requisits que s'utilitzen en els procediments d'identificació i autenticació durant les operacions de registre que realitzen, amb anterioritat a l'emissió i lliurament de certificats, les Entitats de Registre.

### <a name="_toc150443550"></a>**3.1.1. Tipus de noms**
#### <a name="_toc150443551"></a>**3.1.1.1. Estructura sintàctica**
Tots els certificats contenen un nom diferenciat X.501 en el camp Subject, incloent un component CommonName (CN=).

L'estructura sintàctica i el contingut dels camps de cada certificat, així com el seu significat semàntic, es troben descrits en el document “perfil de certificat” corresponent que el Consorci AOC publica al seu web (https://epscd.aoc.cat/regulacio). 
#### <a name="_toc150443552"></a>**3.1.1.2. Perfils dels certificats**
Els perfils dels certificats emesos es publiquen al web del Consorci AOC (https://epscd.aoc.cat/regulacio).

### <a name="_toc150443553"></a>**3.1.2. Significat dels noms**
Sense estipulació. 

### <a name="_toc150443554"></a>**3.1.3. Utilització de pseudònims**
El possible ús de pseudònims es regularà en la corresponent PC.

### <a name="_toc150443555"></a>**3.1.4. Interpretació de formats de noms**
El Consorci AOC aten en tot cas al marcat per l'estàndard X.500 de referència en la ISO/IEC 9594, així com per la RFC 5280.
### <a name="_1mrcu09"></a><a name="_toc150443556"></a>**3.1.5. Unicitat dels noms**
L'Entitat de Certificació emet diferents tipus de certificats. Els noms dels subscriptors de certificats són únics per a cada servei de generació de certificats operat per l'Entitat de Certificació i per a cada tipus de certificat, és a dir, una mateixa persona només pot tenir al seu nom certificats de tipus diferents emesos per l'Entitat de Certificació. L'atribut de CIF o NIF s'usa per distingir entre dues identitats quan existeixi algun problema de duplicitat de noms.

No es pot tornar a assignar un nom de subscriptor que ja hagi estat assignat a un subscriptor diferent.

Tot el personal vinculat a l'Entitat de Registre té com a requisit imprescindible l'assistència al curs de formació d'Entitats de Registre impartit per l'Entitat de Certificació.
### <a name="_toc150443557"></a>**3.1.6. Seqüència i freqüència de rotació laboral**
Sense estipulació.

### <a name="_toc150443558"></a>**3.1.7. Resolució de conflictes relatius a noms**
El Consorci AOC no arbitrarà davant possibles disputes de noms, ni tindrà responsabilitat sobre aquest tema. L'assignació de noms es realitzarà basant-se en l'ordre d'entrada.
Referent al tractament de marques registrades, veure l'apartat 9.5.3.

## <a name="_toc150443559"></a>**3.2. Validació inicial de la identitat**
### <a name="_toc150443560"></a>**3.2.1. Prova de possessió de clau privada**
Quan s'expedeix un certificat en un dispositiu hardware, la clau privada es crea en l'instant previ a la generació del certificat, mitjançant un procediment que garanteix la seva confidencialitat i la seva vinculació amb la identitat del sol·licitant.

Cada Entitat de Registre és responsable de garantir el lliurament o l'accés al dispositiu al sol·licitant de forma segura. En els altres casos, el mètode de prova de la possessió de la clau privada pel subscriptor serà el lliurament de PKCS#10 o una prova criptogràfica equivalent o un altre mètode aprovat pel Consorci AOC.

### <a name="_toc150443561"></a>**3.2.2. Autenticació de la identitat d'una organització**
L'Entitat de Registre haurà de verificar les següents dades per poder autenticar la identitat de l'organització:

- Les dades relatives a la denominació o raó social de l'organització.
- Les dades relatives a la constitució, i personalitat jurídica del subscriptor.
- Les dades relatives a l'extensió i vigència de les facultats de representació del sol·licitant.
- Les dades relatives al codi d'identificació fiscal de l'organització o codi equivalent.

El Consorci AOC es reserva el dret de no emetre el certificat si considera que la documentació aportada no és suficient o adequada per a la comprovació de les dades anteriorment citades.
#### <a name="_4k668n3"></a><a name="_toc150443562"></a>**3.2.2.1. Entitats de Registre**
L'Entitat de Certificació autentica, prèviament a l'emissió i al lliurament d'un certificat certificat, per a qualsevol dels components d'una Entitat de Registre, la identitat de l'Entitat de Registre i de l'operador conforme a la secció corresponent d'aquesta DPC.

### <a name="_toc150443563"></a>**3.2.3. Autenticació de la identitat d’una persona física**
Aquesta secció conté informacions per a la comprovació de la identitat d'una persona física identificada en un certificat.

#### <a name="_toc150443564"></a>**3.2.3.1. Elements d’identificació**
El número i tipus de documents necessaris per acreditar la identitat del posseïdor de claus són els que admet el Consorci AOC, tal com es recull en la seva normativa reguladora.

En tot cas, aquests documents identificatius contindran com a mínim:

- Nom i cognoms de la persona
- Número d'identitat qualificat legalment (DNI, NIF o NIE dels països signataris de l'Acord de Schengen; passaport en el cas dels certificats d'estranger)
- Data i lloc de naixement
- Qualsevol altra informació que pugui ser utilitzada per diferenciar a una persona d'una altra, dins de l'àmbit de la Institució (per exemple: fotografia, correu-e, categoria, càrrec, etc.)

#### <a name="_toc150443565"></a>**3.2.3.2. Validació dels elements d’identificació**
Sense estipulació addicional.

#### <a name="_toc150443566"></a>**3.2.3.3. Necessitat de presència personal**
La identificació de la persona física que hagi d'obtenir un certificat qualificat (del posseïdor de les claus) podrà realitzar-se:

- Mitjançant la seva presència davant els encarregats de verificar la seva identitat.
- Mitjançant el procediment que estableix la normativa administrativa, quan la personació es realitzi davant les Administracions Públiques.
- Es podrà emprar el mètode d'identificació per videoconferència només en aquells casos permesos per la legislació espanyola i conforme a l'article article 24.1.d) del Reglament (UE) núm. 910/2014 La vigència dels certificat emesos a través d'aquest mètode d'identificació i l'ús dels mateixos quedarà limitat segons el que s'estableix per la legislació vigent a cada moment.

Abans de l'emissió i lliurament d'un certificat qualificat, l'Entitat de Certificació - mitjançant la intervenció d'una Entitat de Registre - haurà de comprovar la identitat del posseïdor de claus mitjançant la personació d'aquest.

L'acte de personació pot diferir-se al moment de lliurament i acceptació del certificat, aprofitant per validar la identitat de la persona que serà posseïdora de la clau privada corresponent al certificat que es lliura.

Es podrà prescindir de la personació si la sol·licitud d'expedició d'un certificat ha estat autenticada mitjançant l'ús d'un certificat electrònic de signatura qualificada classificat pel Consorci AOC, sempre que es trobi vigent i no hagi transcorregut més de cinc anys des de la identificació amb presència personal.

En el cas dels certificats per a la ciutadania es pot prescindir de la personació si la signatura continguda en la sol·licitud d'expedició d'un certificat ha estat legitimada notarialment i en els casos previstos en l'article 24 del Reglament (UE) núm. 910/2014. Però aquesta DPC no dóna suport a aquest mecanisme a causa de  la inexistència d'un procediment a aquest efecte per part dels notaris.
#### <a name="_183oopgk0uo0"></a><a name="_toc150443567"></a>**3.2.3.4. Vinculació de la persona física amb l’organització**
Es regula de manera diferenciada en cadascuna de les Polítiques de Certificació vigents per a cada tipus de Certificat.

### <a name="_toc150443568"></a>**3.2.4. Informació no verificada**
L'Entitat de Certificació es responsabilitza que tota la informació inclosa en la sol·licitud del certificat sigui exacta i completa per a la finalitat del certificat; i que té dret al seu ús (per exemple, dret a utilitzar cert nom en l'adreça de correu electrònic).

No obstant això, els certificats poden incloure informació no verificada, com per exemple l'adreça de correu electrònic, sempre que s'indiqui als usuaris finals en el propi certificat o en els instruments jurídics corresponents.
###
### <a name="_toc150443569"></a>**3.2.5 Criteris d'interoperabilitat**
Sense estipulació.

## <a name="_toc150443570"></a>**3.3. Identificació i autenticació de sol·licituds de renovació**

### <a name="_toc150443571"></a>**3.3.1. Validació per a la renovació de certificats**
Tant si es tracta d'una renovació ordinària, com si és posterior a la revocació del certificat a renovar, el procés a seguir per a la renovació d'un certificat serà el mateix que per a l'emissió de certificats nous: L'Entitat de Certificació haurà de comprovar – mitjançant la intervenció d'una Entitat de Registre - que la informació utilitzada per verificar la identitat i la resta de dades del subscriptor i del posseïdor de la clau continuen sent vàlides.

Si qualsevol informació del subscriptor o del posseïdor de la clau ha canviat, es registrarà adequadament la nova informació, d'acord amb allò establert en la secció 3.2 Validació inicial de la identitat.

### <a name="_toc150443572"></a>**3.3.2. Validació per a la renovació de certificats després de la revocació**
La renovació de certificats després de la seva revocació no és possible.

# **<a name="_toc150443573"></a>4. Característiques d'operació del cicle de vida dels certificats**

## <a name="_toc150443574"></a>**4.1. Sol·licitud d'emissió de certificat**
### <a name="_toc150443575"></a>**4.1.1. Legitimació per sol·licitar l'emissió**
Els requisits que ha de reunir un sol·licitant dependran del tipus de certificat sol·licitat i es recolliran en la PC  de cada tipus de certificat concret.
### <a name="_toc150443576"></a>**4.1.2. Procediment d'alta; Responsabilitats**
L'Entitat de Certificació, amb caràcter previ a l'emissió d'un certificat, s'assegura que les sol·licituds de certificats estiguin completes, precises i degudament autoritzades.

Abans de l'emissió i lliurament d'un certificat, l'Entitat de Certificació informarà al subscriptor o, si escau, el posseïdor de claus dels termes i condicions aplicables al certificat. Aquest requisit es compleix mitjançant el lliurament de l'instrument jurídic que vincula a l'Entitat de Certificació amb el subscriptor o el full de lliurament al posseïdor de claus, en el qual s'inclourà l'esmentada informació. Aquesta informació es comunicarà en suport perdurable, en paper o electrònicament, i en llenguatge fàcilment comprensible.

## <a name="_toc150443577"></a>**4.2. Processament de la sol·licitud de certificació**
Els requisits que ha de reunir una sol·licitud de certificació dependran del tipus de certificat sol·licitat i es recolliran en la PC  de cada tipus de certificat concret.

## <a name="_toc150443578"></a>**4.3. Emissió de certificat**
### <a name="_toc150443579"></a>**4.3.1. Accions de l'Entitat de Certificació durant el procés d'emissió**
Per a cada sol·licitud de certificat tramitada, l'Entitat de Certificació:

- Utilitza un procediment de generació de certificats X.509 v3 que vincula de forma segura el certificat amb la informació de registre, incloent la clau pública certificada, mitjançant la signatura electrònica  de l'Entitat de Certificació.
- Protegeix la confidencialitat i la integritat de les dades de registre.
- Inclou als certificats personals les informacions establertes a la legislació aplicable que es descriu en 9.15 Conformitat amb la llei aplicable.
- Compleix les obligacions establertes a la legislació corresponent, en la generació de certificats qualificats.
- Compleix els controls establerts per aquesta DPC.

Nota: Els procediments establerts en aquesta secció també s'apliquen en cas de renovació de certificats, ja que la renovació implica l'emissió d'un certificat nou.
### <a name="_toc150443580"></a>**4.3.2. Comunicació de l'emissió al subscriptor**
L'Entitat de Certificació comunica al subscriptor l'emissió del certificat, o la incidència corresponent. Així mateix, s'indicarà la disponibilitat del certificat i la forma d'obtenir-lo.

## <a name="_toc150443581"></a>**4.4. Acceptació del certificat**
### <a name="_toc150443582"></a>**4.4.1. Responsabilitats del Prestador de Serveis de Confiança**
L’Entitat de Certificació (o PSC):

- Si no ho ha fet abans, i quan resulti necessari, acreditarà la identitat del subscriptor.
- Proporcionarà al subscriptor accés al certificat.
- Lliurarà, si escau, el dispositiu criptogràfic de signatura, verificació de signatura, xifrat i desxifrat.
- Proporcionarà la informació següent:
  - Informació bàsica sobre la política i l'ús del certificat, incloent especialment informació sobre l'Entitat de Certificació Vinculada i la DPC aplicable, així com les seves obligacions, facultats i responsabilitats.
  - Informació sobre el certificat i el dispositiu criptogràfic.
  - Reconeixement del posseïdor de rebre el certificat i, si escau, el dispositiu criptogràfic, i acceptació dels esmentats elements.
  - Obligacions del posseïdor de claus.
  - Responsabilitat de posseïdor de claus.
  - Mètode d'imputació exclusiva al posseïdor de la seva clau privada i de les seves dades d'activació del certificat i, si escau, del dispositiu criptogràfic, d'acord amb l'establert a les seccions corresponents d'aquesta política.
  - La data de l'acte de lliurament i acceptació.
### <a name="_toc150443583"></a>**4.4.2. Conducta que constitueix acceptació del certificat**
El certificat es pot acceptar mitjançant la signatura del full de posseïdor o responsable de la custòdia de claus.

També es pot acceptar el certificat mitjançant un mecanisme telemàtic d'activació del certificat.
### <a name="_toc150443584"></a>**4.4.3. Publicació del certificat**
Els certificats es poden publicar si es disposa del consentiment exprés de les persones físiques, les dades de les quals constin en els citats certificats.

### <a name="_toc150443585"></a>**4.4.4. Notificació de l'emissió a tercers**
Sense estipulació.

## <a name="_toc150443586"></a>**4.5. Ús del parell de claus i del certificat**
### <a name="_toc150443587"></a>**4.5.1. Ús per part dels posseïdors de claus**
Sense estipulació. 

### <a name="_toc150443588"></a>**4.5.2. Ús pel tercer que confia en certificats**
Sense estipulació.

## <a name="_toc150443589"></a>**4.6. Renovació de certificats sense renovació de claus**
No es permet la renovació de certificats sense renovació de claus.

## <a name="_toc150443590"></a>**4.7. Renovació de certificats amb renovació de claus**
La renovació d'un certificat s'inicia 2 (dos) mesos abans de la data d'expiració del certificat, quan el subscriptor rep un correu electrònic on se li informa dels passos a seguir per executar la renovació del certificat. Aquest correu es torna a enviar 30 (trenta) dies abans de l'expiració.

El procés per a la renovació d'un certificat és el mateix que se segueix per a l'emissió de nous certificats. Quan se sol·liciti la renovació d'un certificat, l'Entitat de Registre Interna haurà de verificar que les dades de registre continuïn sent vàlides i, si ha canviat alguna dada, aquest haurà de ser verificat, s'ha de guardar evidència d'aquesta comprovació i el subscriptor ha d'estar d'acord amb la modificació, tal com s'especifica en la secció corresponent d'aquesta DPC.

En qualsevol cas, si han passat més de cinc anys des de l'última vegada que el subscriptor es va identificar presencialment en una oficina d'Entitat de Registre, haurà de personar-se de nou per dur a terme la renovació.

L'Entitat de Certificació informarà al posseïdor de claus de les condicions jurídiques de prestació del servei, tal com es fa en el procés d'emissió de nous certificats.

Per a certificats individuals en suport clauer, el subscriptor haurà de personar-se en les oficines de l'Entitat de Registre, ja que les noves claus es generaran en aquest dispositiu.

### <a name="_toc150443591"></a>**4.7.1. Renovació telemàtica**
L'Entitat de Certificació permet la renovació telemàtica de certificats digitals - a partir d'una autenticació segura i la corresponent signatura electrònica del full de lliurament o de la sol·licitud d'emissió del nou certificat (mitjançant la qual s'accepta aquest), realitzada amb el certificat a renovar dins dels dos últims mesos de vigència - sempre que no hagin transcorregut més de cinc anys des de l'última vegada que el posseïdor de claus es va identificar presencialment en una oficina d'Entitat de Registre.

## <a name="_toc150443592"></a>**4.8. Modificació de certificats**
La modificació de les dades dels certificats comporta la revocació i l'emissió d'un nou certificat. Amb caràcter general, la modificació es considerarà renovació.

Quan el subscriptor d'un certificat tingui coneixement de canvis en la informació obligatòria o la relativa a càrrecs, límits d'ús o dispositius usuaris dels certificats (p.ej adreces IP o dades de servidors o aplicacions); o quan precisi la modificació de la resta de les dades incloses en el certificat (adreça de correu electrònic, etc) podrà gestionar la renovació del certificat vigent. En certs casos, en funció de la informació a modificar, aquesta revocació podrà fer-se en data posterior a l'emissió del certificat amb les dades actualitzades.

L'Entitat de Registre requerirà l'acreditació de les condicions justificatives de la modificació.

## <a name="_toc150443593"></a>**4.9. Revocació de certificats**
### <a name="_toc150443594"></a>**4.9.1. Causes de revocació de certificats**
L'Entitat de Certificació podrà revocar un certificat per la concurrència de les següents causes:

1. Circumstàncies que afecten la informació continguda en el certificat
   1. Modificació d'alguna de les dades contingudes en el certificat.
   1. Descobriment que alguna de les dades aportades en la sol·licitud del certificat és incorrecta, així com l'alteració o modificació de les circumstàncies verificades per a l'expedició del certificat.
   1. Descobriment que alguna de les dades contingudes en el certificat és incorrecte.
1. Circumstàncies que afecten a la seguretat de la clau o del certificat
   1. Compromís de la clau privada o de la infraestructura o sistema de l'Entitat de Certificació que va emetre el certificat, sempre que afecti a la fiabilitat dels certificats emesos a partir d'aquest incident.
   1. Infracció, per l'Entitat de Certificació, dels requisits previstos en els procediments de gestió de certificats establerts en la PC de l'Entitat de Certificació.
   1. Compromís o sospita de compromís de la seguretat de la clau o del certificat del posseïdor de claus.
   1. Accés o utilització no autoritzades per un tercer de la clau privada del posseïdor de claus.
   1. L'ús irregular del certificat pel posseïdor de claus, o falta de diligència en la custòdia de la clau privada.
   1. La CA coneix un mètode comprovat que pot calcular fàcilment la clau privada del subscriptor en funció de la clau pública en el certificat.
1. Circumstàncies que afectin a la seguretat del dispositiu criptogràfic
   1. Compromís o sospita de compromís de la seguretat del dispositiu criptogràfic.
   1. Pèrdua o inutilització per danys del dispositiu criptogràfic.
   1. Accés no autoritzat per un tercer a les dades d'activació del posseïdor de claus.
1. Circumstàncies que afecten al posseïdor de claus.
   1. Finalització de la relació entre l'Entitat de Certificació Vinculada al posseïdor de claus.
   1. Modificació o extinció de la relació jurídica subjacent o de la causa que va motivar l'emissió del certificat al posseïdor de claus.
   1. Infracció per part del sol·licitant del certificat, dels requisits preestablerts per a la seva sol·licitud.
   1. Infracció, per part del posseïdor de claus, de les seves obligacions, responsabilitat i garanties, establertes en l'instrument jurídic corresponent o a la Declaració de Pràctiques de Certificació de l'Entitat de Certificació Vinculada que li va emetre el certificat o a les seves Polítiques de Certificació associades.
   1. La incapacitat sobrevinguda o la mort del posseïdor de claus.
   1. En cas de certificats corporatius, l'extinció de la persona jurídica subscriptora del certificat, així com la finalització de l'autorització del subscriptor al posseïdor de claus, o la finalització de la relació entre el subscriptor i el posseïdor de claus.
   1. Sol·licitud del subscriptor de revocació del certificat, d'acord amb l'establert en la secció 3.4 d'aquesta declaració.
1. Altres circumstàncies
   1. La finalització del servei de l'Entitat de Certificació Vinculada.
   1. La finalització de la prestació de servei per part de l'Entitat de Certificació.
   1. Resolució judicial o administrativa que ho ordeni.
   1. Compliment del que es preveu en les disposicions legals vigents.


L'instrument jurídic que vincula a l'Entitat de Certificació Vinculada amb el subscriptor establirà que el subscriptor haurà de sol·licitar la revocació del certificat en cas de tenir coneixement d'alguna de les circumstàncies indicades anteriorment. 


### <a name="_toc150443595"></a>**4.9.2. Legitimació per sol·licitar la revocació**
Podran sol·licitar la revocació d'un certificat:

- En cas de certificats individuals, el subscriptor a nom de qui es va emetre el certificat.
- En cas de certificats corporatius, la persona autoritzada a aquest efecte per a l'entitat subscriptora; en ocasions, a instàncies del posseïdor de claus.
- L'Entitat de Registre que va sol·licitar l'emissió del certificat.

### <a name="_toc150443596"></a>**4.9.3. Procediments de sol·licitud de revocació**
La sol·licitud de revocació ha de ser enviada telemàticament. Excepcionalment, en cas d'indisponibilitat del canal telemàtic, es podrà enviar per correu certificat convencional. S'ha d'incloure la informació suficient per poder identificar raonablement, en criteri de l'Entitat de Certificació, d'una banda, el certificat que se sol·licita revocar i, per una altra, l'autenticitat i autoritat del sol·licitant. El procediment detallat es troba al web del Consorci AOC. 

Aquesta informació suficient ha d'estar formada per les dades de contacte del posseïdor de claus, inclòs el seu DNI o equivalent i de l'entitat que demana la revocació, la data i la raó de la petició, així com el nombre de sèrie del certificat. Qui faci la sol·licitud de revocació pot demanar a l'Entitat de Registre més informació sobre aquest procediment.

La petició de revocació amb la documentació necessària és recollida i registrada per l'Entitat de Registre. Les Entitats de Registre atenen les sol·licituds de revocació dins del seu horari d'oficina.

L'acció de revocació la duu a terme un dels operadors de l'Entitat de Registre, qui accedeix a l'aplicació web a aquest efecte, autenticant-se mitjançant un certificat digital emès per l'Entitat de Certificació.

Una vegada registrat el canvi d'estat del certificat en el sistema de l'Entitat de Certificació, de forma automàtica i com més aviat millor, es genera i publica una nova LRC en la qual constarà la referència d'aquest certificat. 

S'informa al subscriptor i, si escau, al posseïdor de claus, sobre el canvi d'estat del certificat, d'acord amb la legislació aplicable.

Quan sigui urgent deixar sense efecte un certificat, el propi titular del certificat pot sol·licitar la revocació del certificat mitjançant la pàgina web habilitada a aquest efecte a partir del codi de gestió associat al certificat en el moment de l'emissió d'aquest. Les dades de sol·licitud d'aquests serveis es troben en el punt “[1.5.2. Dades de contacte de l'organització](#_147n2zr)” d’aquest document. 

### <a name="_toc150443597"></a>**4.9.4. Termini temporal de sol·licitud de revocació**
<a name="_4du1wux"></a>Les sol·licituds de revocació s'han de remetre en la major brevetat possible, quan es tingui coneixement de la causa de revocació.

### <a name="_toc150443598"></a>**4.9.5. Termini màxim de processament de la sol·licitud de revocació**
Quan una Entitat de Registre o una Entitat de Certificació Vinculada rebin una sol·licitud de revocació, aquesta serà processada en el mínim termini possible, i sempre abans de 24 h des de la sol·licitud de la mateixa.

Abans de procedir a la revocació efectiva d'un certificat, el destinatari de la sol·licitud ha d'autenticar-la d'acord amb els requisits establerts en la secció corresponent d'aquesta DPC.

Quan la sol·licitud de revocació hagi estat remesa a una Entitat de Registre, aquesta podrà, una vegada autenticada la sol·licitud, revocar directament el certificat o remetre una sol·licitud en aquest sentit a l'Entitat de Certificació Vinculada.

S'haurà d'informar sobre el canvi d'estat del certificat que s'ha revocat al posseïdor de claus també. Quan es tracti de certificats corporatius, al subscriptor.

### <a name="_toc150443599"></a>**4.9.6. Obligació de consulta d'informació de revocació de certificats**
Els verificadors comproven l'estat d'aquells certificats en què desitgen confiar.

Per verificar l'estat dels certificats ha de consultar-se LRC vigent emesa per l'Entitat de Certificació que va emetre aquest certificat, o bé consultar un servei en línia que respongui sobre l'estat de certificats (Servei OCSP o altres serveis de validació de certificats) operat per un prestador de serveis de validació en el qual es confia.

Les Entitats de Certificació que integren la jerarquia de certificació operada pel Consorci AOC publiquen de manera gratuïta la informació sobre l'estat dels certificats emesos per elles. Les URLs en les quals es publica aquesta informació (llistes LRC i serveis OCSP) s'indiquen en el contingut dels certificats que emeten.

L'Entitat de Certificació subministra informació als verificadors sobre com i on trobar la LRC corresponent.

### <a name="_toc150443600"></a>**4.9.7. Freqüència d'emissió de llistes de revocació de certificats (LRCs)**
L’Entitat de Certificació Arrel emetrà una Llista d’Entitats de Certificació Revocades (en anglès Authority Revocation List, ARL) com a mínim cada sis mesos, o extraordinàriament, quan es produeixi la revocació d'un certificat d'autoritat.

Cada Entitat de Certificació Subordinada emetrà una LRC L diàriament, i de forma extraordinària, en els 30 minuts següents de cada vegada que es revoqui un certificat. La validesa d’aquesta CRL serà de 7 dies. La CRL no conté informació d’estat dels certificats caducats. 

### <a name="_toc150443601"></a>**4.9.8. Període màxim de publicació de LRCs**
Una vegada generades, les noves versions de les LRCs seran publicades immediatament a la web del Consorci AOC i a les URLs indicades entre el contingut dels certificats emesos.

### <a name="_toc150443602"></a>**4.9.9. Disponibilitat de serveis de comprovació d'estat de certificats**
Els verificadors de certificats electrònics  poden consultar el servei en línia que respongui sobre l'estat de certificats (servei *OCSP Responder*, de consulta d’estat de certificats en línia, o altres serveis de validació de certificats) operat per un prestador de serveis de validació en el qual es confia.

El Consorci AOC ofereix de manera gratuïta un servei OCSP respondre per a la comprovació en línia de l'estat dels certificats emesos per les Entitats de Certificació que integren la jerarquia pública de certificació de Catalunya.

La URL en la qual es troba disponible aquest servei s'indica entre el contingut dels certificats emesos. La informació relativa al perfil OCSP i, en general, al funcionament del servei es pot trobar a https://epscd.aoc.cat/.

En cas de cessament de l'activitat i/o compromís de claus de l’EC, es generarà una última LRC que es mantindrà íntegra i disponible per a la seva consulta garantint la disponibilitat del servei d'informació sobre l'estat dels certificats, durant almenys 15 anys des de la seva publicació. 

La provisió de la informació sobre l'estat de revocació dels Certificats, en cas de cessament d'activitat del Consorci AOC com a PSC, queda garantida mitjançant la transferència, a l'organisme supervisor o a un altre Prestador amb el qual s'arribi al corresponent acord, de tota la informació relativa als Certificats i, especialment, de les dades del seu estat de revocació.

### <a name="_toc150443603"></a>**4.9.10. Obligació de consulta de serveis de comprovació d'estat de certificats**
Els verificadors han de comprovar l'estat d'aquells certificats en els quals desitgin confiar, encara que no s'estipula obligació alguna referent al mecanisme utilitzat per a la comprovació d'aquest estat.

### <a name="_toc150443604"></a>**4.9.11. Altres formes d'informació de revocació de certificats**
<a name="_45jfvxd"></a>Sense estipulació.

### <a name="_toc150443605"></a>**4.9.12. Requeriments especials en cas de compromís de la clau privada**
El compromís de la clau privada d'una Entitat de Certificació Vinculada serà comunicat, el més aviat possible, a tots els participants en la jerarquia pública de certificació de Catalunya, com a mínim mitjançant la inclusió en la LRC corresponent de la referència al certificat electrònic d'aquesta Entitat de Certificació.

Addicionalment, les Terceres parts poden utilitzar els següents mètodes per a demostra un possible compromís de claus:

- Enviar un CSR signat, la clau privada que ha estat compromesa o altra resposta de desafiament signada per la Clau Privada esmentada i verificable per la clau pública.
- Proporcionar referències a fonts d'incidents de seguretat i o vulnerabilitat per les quals el compromís sigui verificable.
- Enviar binaris que contenen una clau privada compromesa, inclòs el mètode per a extraure la clau privada.

Les terceres parts notificaran l'esmentat compromís a la CA a través del correu electrònic per a notificació d'incidències: **incident\_pki@aoc.cat** 
### <a name="_toc150443606"></a>**4.9.13. Període de validesa dels certificats**
El període de validesa serà el que s'indiqui en el propi certificat, amb un màxim de 5 anys.
## <a name="_rjefff"></a><a name="_toc150443607"></a>**4.10. Serveis de comprovació d'estat de certificats**
### <a name="_toc150443608"></a>**4.10.1. Característiques d'operació dels serveis**
Les LRCs es publiquen a la web del Consorci AOC i en les URLs indicades en els certificats emesos.

De forma alternativa, els verificadors podran consultar els certificats publicats en el directori de l'Entitat de Certificació.

Les CRLs no contenen informació d’estat dels certificats caducats. Per tant, en el cas de consultar sobre l’estat d’un certificat caducat, la informació vàlida serà la que proporcioni el sistema de verificació en línia d’estat de certificats (OCSP). 

### <a name="_toc150443609"></a>**4.10.2. Disponibilitat dels serveis**
Els verificadors de certificats digitals poden consultar un servei en línia que respongui sobre l'estat de certificats (servei *OCSP Responder*, de consulta d’estat de certificats en línia, o altres serveis de validació de certificats) operat per un Prestador de serveis de validació en qui es confia.

El Consorci AOC ofereix de manera gratuïta un servei *OCSP Responder* per a la comprovació en línia de l'estat dels certificats emesos per les Entitats de Certificació que integren la jerarquia pública de certificació de Catalunya.

La URL en la qual es troba disponible l'esmentat servei s'indica en el contingut dels certificats emesos. La informació relativa al perfil OCSP i, en general, al funcionament del servei es pot trobar a https://epscd.aoc.cat/.

Els sistemes de distribució de LRCs i de consulta en línia de l'estat dels certificats hauran d'estar disponibles les 24 hores dels 7 dies de la setmana.

En cas de fallada dels sistemes de comprovació d'estat de certificats per causes fora del control de l'Entitat de Certificació, aquesta haurà de realitzar els seus millors esforços per assegurar que aquest servei es manté inactiu el mínim temps possible.

### <a name="_toc150443610"></a>**4.10.3. Altres funcions dels serveis**
Sense estipulació.

## <a name="_toc150443611"></a>**4.11. Finalització de la subscripció**
La finalització de la subscripció no implicarà la revocació dels certificats que hagin estat emesos, sinó que aquests podran utilitzar-se fins que expirin.

## <a name="_toc150443612"></a>**4.12. Dipòsit i recuperació de claus**
### <a name="_toc150443613"></a>**4.12.1. Política i pràctiques de dipòsit i recuperació de claus**
La possibilitat que l'Entitat de Certificació o PSC ofereixi el servei de dipòsit i recuperació de claus pel que fa a una o diverses categories de certificats haurà de constar, en cas que aquesta opció sigui possible, en la corresponent PC . En la mateixa serà necessari detallar, almenys, els següents aspectes:

1. Qui pot sol·licitar el dipòsit i la recuperació de claus
1. Com es tramitarà la sol·licitud
1. Els requisits de confirmació de sol·licituds
1. Els mecanismes utilitzats per dipositar i recuperar claus

### <a name="_toc150443614"></a>**4.12.2. Política i pràctiques d'encapsulat i recuperació de claus de sessió**
Sense estipulació.
# **<a name="_toc150443615"></a>5. Controls de seguretat física, de gestió i d'operacions**
<a name="_338fx5o"></a>L'Entitat de Certificació s'assegura de l'aplicació dels procediments administratius i de gestió adequats conformes amb els estàndards reconeguts i, en particular:

a.	Es realitza una anàlisi de gestió de risc per avaluar les mesures necessàries de seguretat.

b.	S'és responsable per la provisió dels serveis de forma segura, fins i tot quan una part dels mateixos sigui subcontractada. Les responsabilitats de tercers es defineixen i s'han d'implantar els controls jurídics necessaris per garantir que els tercers compleixen les seves obligacions amb un nivell de seguretat equivalent.

c.	S'estableixen les normes principals en matèria de seguretat mitjançant un òrgan d'alt nivell que defineix la política de seguretat de la informació de l'Entitat i dóna la publicitat necessària mitjançant accions de comunicació interna.

d.	Es manté a tot moment la infraestructura necessària per gestionar la seguretat de les operacions. Qualsevol canvi que tingui impacte en el nivell de seguretat ha de ser aprovat per l'òrgan referit al punt anterior.

e.	Es documenten, implanten i mantenen els controls de seguretat i procediments d'operació de les instal·lacions, els sistemes i els actius d'informació en què es sustenta la prestació dels serveis.

f.  En cas de subcontractació total dels serveis, es garanteix el manteniment del nivell necessari de seguretat de la informació.

## <a name="_toc150443616"></a>**5.1. Controls de seguretat física**
### <a name="_toc150443617"></a>**5.1.1. Àrees segures**
L'Entitat de Certificació disposa d'instal·lacions que protegeixen físicament la prestació, almenys, dels serveis de generació de certificats, de dispositius criptogràfics i de gestió de revocació, del compromís causat per accés no autoritzat als sistemes o a les dades.

La protecció física s'aconsegueix mitjançant la creació de perímetres de seguretat clarament definits entorn dels serveis de generació de certificats, de dispositius criptogràfics i de gestió de revocació. La part de les instal·lacions compartida amb altres organitzacions es troba fora d'aquests perímetres.
### <a name="_toc150443618"></a>**5.1.2. Controls de seguretat física**
L'Entitat de Certificació estableix controls de seguretat física i ambiental per protegir els recursos de les instal·lacions on es troben els sistemes, els mateixos sistemes i els equipaments utilitzats per a les operacions. La política de seguretat física i ambiental aplicable als serveis de generació de certificats, de dispositius criptogràfics i de gestió de revocació estableix prescripcions per a les contingències següents:

- Controls d'accés físic.
- Protecció davant desastres naturals.
- Mesures de protecció davant incendis.
- Error dels sistemes de suport (energia elèctrica, telecomunicacions, etc.).
- Demolició de l'estructura.
- Inundacions.
- Protecció antirobatori.
- Conformitat i entrada no autoritzada.
- Recuperació del desastre.
- Sortida no autoritzada d'equipaments, informacions, suports i aplicacions relatius a components utilitzats per als serveis de l'Entitat de Certificació
### <a name="_toc150443619"></a>**5.1.3. Localització i construcció de les instal·lacions**
La localització de les instal·lacions permet la presència de forces de seguretat en un termini de temps raonablement immediat des del moment en què els hi notifica una incidència.

La qualitat i solidesa dels materials de construcció de les instal·lacions garanteix uns nivells de protecció adequats davant intrusions per força bruta.
### <a name="_toc150443620"></a>**5.1.4. Accés físic**
L’Entitat de Certificació estableix nivells de seguretat amb restricció d'accés als diferents perímetres i barreres físiques definides.

Per a l'accés a les dependències de l'Entitat de Certificació on es duguin a terme processos relacionats amb el cicle de vida del certificat, és necessària l'autorització prèvia, la identificació al moment de l'accés i el registre del mateix, incloent filmació per circuit tancat de televisió i el seu arxiu.

Aquesta identificació, davant el sistema de control d'accessos, es realitza mitjançant reconeixement d'algun paràmetre biomètric de l'individu, excepte en cas de visites escortades.

La generació de claus criptogràfiques de l'Entitat de Certificació, així com el seu emmagatzematge, es realitza en dependències específiques per a aquestes finalitats i requereixen d'accés i de permanència dobles.
### <a name="_toc150443621"></a>**5.1.5. Electricitat i aire condicionat**
Els equips informàtics de l'Entitat de Certificació estan protegits convenientment davant fluctuacions o talls de subministrament elèctric que puguin danyar-los o interrompre el servei.
Les instal·lacions compten amb un sistema d'estabilització del corrent, així com d'un sistema de generació propi amb autonomia suficient per mantenir el subministrament durant el temps que requereixi el tancament ordenat i complet de tots els sistemes informàtics.
Els equips informàtics estan situats en un entorn on es garanteix una climatització (temperatura i humitat) adequada a les seves condicions òptimes de treball.
### <a name="_toc150443622"></a>**5.1.6. Exposició a l'aigua**
L'Entitat de Certificació disposa de sistemes de detecció d'inundacions adequats per protegir els equips i els actius davant aquesta eventualitat, en cas que les condicions d'ubicació de les instal·lacions ho fessin necessari.
### <a name="_toc150443623"></a>**5.1.7. Advertiment i protecció d'incendis**
Totes les instal·lacions i actius de l'Entitat de Certificació compten amb sistemes automàtics de detecció i extinció d'incendis. En concret, els dispositius criptogràfics i suports que emmagatzemen claus de les Entitats de Certificació hauran de comptar amb un sistema específic i addicional a la resta de la instal·lació per a la protecció davant el foc.
### <a name="_toc150443624"></a>**5.1.8. Emmagatzematge de suports**
L'ús de suports extraïbles està minimitzat i restringit únicament a moviment d'arxius entre sistemes mitjançant dispositius pendrive USB. Per garantir tant la integritat com la confidencialitat els suports extraïbles es guardaran en una caixa forta a la mateixa sala.
### <a name="_toc150443625"></a>**5.1.9. Tractament de residus**
L'eliminació de suports, tant paper com magnètics, es realitza mitjançant mecanismes que garanteixen la impossibilitat de recuperació de la informació. En el cas de suports magnètics, es procedeix al format, esborrat permanent o destrucció física del suport. En el cas de documentació en paper, aquest se sotmet a un tractament físic de destrucció.
### <a name="_toc150443626"></a>**5.1.10. Còpia de seguretat fora de les instal·lacions**
Es realitzen còpies de seguretat dels sistemes d'informació en dependències físicament separades d'aquelles en les quals es troben els equips. Les còpies de seguretat es faran online en el sistema de contingència, un CPD alternatiu, a través de comunicacions xifrades.

## <a name="_toc150443627"></a>**5.2. Controls de procediments**
L'Entitat de Certificació garanteix que els seus sistemes s'operen de forma segura i, per això, estableix i implanta procediments per a les funcions que afecten la provisió dels seus serveis.
El personal al servei de l'Entitat de Certificació realitza els procediments administratius i de gestió d'acord amb la política de seguretat de l'Entitat de Certificació.
### <a name="_toc150443628"></a>**5.2.1. Funcions fiables**
Les persones que ocupen aquests llocs són nomenades formalment per l'alta direcció de l'Entitat de Certificació.

Les funcions fiables inclouen:

- Personal responsable de la seguretat.
- Administradors del sistema.
- Operadors del sistema.
- Operadors de registre.
- Auditors del sistema.
- Qualsevol altra persona amb accés a dades de caràcter personal.

Segons l'especificat en les normes ETSI EN 319 401 i CEN/TS 419261, els rols mínims establerts són:

- Responsable de seguretat (Security Officer): Manté la responsabilitat global sobre l'administració i la implementació de les polítiques i procediments de seguretat.
- Operador de RA (Registration Officer): Responsables d'aprovar, emetre i revocar els certificats d'Entitat final, així com les oportunes verificacions en certificats d'autenticació web.
- Responsable de revocació (Revocation Officers): Responsable de realitzar els canvis en l'estat d'un certificat.
- Administradors del sistema de certificació (System Administrator): Autoritzat per realitzar canvis en la configuració del sistema, però sense accés a les dades del mateix.
- Operadors de sistemes (System Operators): Responsables de la gestió del dia a dia del sistema (Monitoreig, backup, recovery…)
- Auditor intern (System Auditors): Autoritzat a accedir als logs del sistema i verificar els procediments que es realitzen sobre el mateix.
- Operador d’EC - Operador de Certificació: Responsables d'activar les claus de l’EC en l'entorn Online, o dels processos de signatura de certificats i LRC’s en l'entorn Root Offline.
### <a name="_toc150443629"></a>**5.2.2. Número de persones per tasca**
L’Entitat de Certificació garanteix almenys dues persones per a fer les tasques que requereixen control multipersona i que es detallen a continuació:

- La generació de la clau de les EC’s.
- La recuperació i back-up de la clau privada de les EC’s.
- L'emissió de certificats de les EC’s.
- Activació de la clau privada de les EC’s.
- Qualsevol activitat realitzada sobre els recursos maquinari i programari que donen suport a la root EC.
### <a name="_toc150443630"></a>**5.2.3. Identificació i autenticació per a cada funció**
L'Entitat de Certificació identifica i autentica al personal abans d'accedir a la corresponent funció fiable.
### <a name="_toc150443631"></a>**5.2.4. Rols que requereixen separació de tasques**
L'Entitat de Certificació identifica, a la seva política de seguretat, funcions o rols fiables.

Les funcions fiables inclouen:

1. Oficial de Seguretat
1. Operador de registre
1. Administradors del sistema
1. Operadors del sistema
1. Auditors del sistema
1. Qualsevol altra persona amb accés a dades de caràcter personal

Les esmentades restriccions s'apliquen en tot cas a:	

1. La persona que actua com a oficial de seguretat o com a operador de registre que no pot ser auditor del sistema.
1. La persona que actua com a administrador del sistema que no pot ser oficial de seguretat ni auditor del sistema.

Les descripcions de rols hauran de realitzar-se tenint en compte que ha d'existir una separació de funcions sensibles, així com una concessió de mínim privilegi, quan sigui possible. Per determinar la sensibilitat de la funció, es tindran en compte els següents elements:

1. Deures associats a la funció
1. Nivell d'accés
1. Monitoratge de la funció
1. Formació i conscienciació
1. Habilitats requerides

Les esmentades restriccions s'apliquen en tot cas a:

- La persona que actua com a oficial de seguretat o com a operador de registre que no pot ser auditor del sistema.
- La persona que actua com a administrador del sistema que no pot ser oficial de seguretat ni auditor del sistema.

## <a name="_toc150443632"></a>**5.3. Controls de personal**
L'Entitat de Certificació té en compte els aspectes següents:

- Es manté confidencialitat de la informació, posant els mitjans necessaris i mantenint una actitud adequada en el desenvolupament de les seves funcions i, fora de l'àmbit laboral, en allò referent a la seguretat de les infraestructures.
- S'és diligent i responsable en el tractament, el manteniment i la custòdia dels actius de la infraestructura identificats en la política, en els plans de seguretat o en aquesta DPC.
- No es revela informació no pública fora de l'àmbit de la infraestructura, ni s'extreuen suports d'informació a nivells de seguretat inferiors.
- Es reporta al Responsable de Seguretat, el més aviat possible, qualsevol incident que es consideri que afecta la seguretat de la infraestructura o limita la qualitat del servei.
- S'utilitzen els actius de la infraestructura per a les finalitats per les quals han estat encomanades.
- S'exigeixen manuals o guies d'usuari dels sistemes que utilitza, que permetin desenvolupar la seva funció correctament.
- S'exigeix documentació escrita que marqui les seves funcions i les mesures de seguretat al fet que està sotmès.
- El responsable de seguretat vetlla perquè el punt anterior sigui executat i proveeix als responsables d'àrea de tota la informació que sigui necessària.
- No s'instal·la, en cap dels sistemes de la infraestructura, software o hardware que no sigui expressament autoritzat per escrit pel responsable de sistemes d'informació.
- No s'accedeix voluntàriament ni s'elimina o altera informació no destinada a la seva persona o perfil professional.

El personal afectat per aquesta normativa és:

- El Responsable del Servei.
- El Responsable de l’Entitat de Certificació.
- El Responsable de Seguretat.
- El Responsable d’Operacions.
- L’Equip tècnic d’administració, operació  explotació.
- Els Administradors de la Xarxa.
- Els Usuaris de l’Entitat de Certificació.

L’Entitat de Certificació, a més, es veu afectada pel següent personal:

- qui fa les peticions dels certificats.
- qui fa l'aprovació i la validació de les peticions de certificats.
- qui fa la generació / personalització de certificats.
- qui custodia les claus o els tokens criptogràfics.
- qui custodia les claus o les combinacions de seguretat d'accés a la sala d'operacions.
- qui accedeix a informació classificada.
- el personal de comunicacions i d'operacions.
- el personal de seguretat (física i lògica) involucrat en l'operació.
- el responsable del servei.

### <a name="_toc150443633"></a>**5.3.1. Requisits d'historial, qualificacions, experiència i autorització**
L'Entitat de Certificació és ocupada per personal qualificat i amb l'experiència necessària per a la prestació dels serveis oferts, en l'àmbit de la signatura electrònica i els procediments de seguretat i de gestió adequada.

Aquest requisit s'aplicarà al personal de gestió de l'Entitat de Certificació, especialment en relació amb procediments de personal de seguretat. 
La qualificació i l'experiència es poden suplir mitjançant una formació i un entrenament apropiats.
El personal en rols de confiança  es troba lliure d'interessos personals que entrin en conflicte amb el desenvolupament de la funció que tingui encomanada.
### <a name="_toc150443634"></a>**5.3.2. Requisits de formació**
L'Entitat de Certificació forma el personal en rols de confiança i de gestió fins que aconsegueixen la qualificació necessària.

La formació inclou els continguts següents:

- Principis i mecanismes de seguretat de la jerarquia pública de certificació de Catalunya, així com de l'entorn d'usuari de la persona que s'ha de formar.
- Versions de hardware i d'aplicacions en ús.
- Tasques que ha de realitzar la persona.
- Gestió i tramitació d'incidents i compromisos de seguretat.
- Procediments de continuïtat de negoci i emergència.
- Procediment de gestió i de seguretat en relació amb el tractament de les dades de caràcter personal.

L'Entitat de Certificació, a més, proporciona a tot el personal involucrat en les seves operacions com a Entitat de Registre una informació adequada, que inclou els procediments de treball i els de seguretat. També es realitza una instrucció periòdica en normes de seguretat, plans de contingència i gestió d'incidències.
### <a name="_toc150443635"></a>**5.3.3. Requisits i freqüència d’actualització formativa**
Tot el personal vinculat a les Entitats de Registre té com a requisit imprescindible l'assistència al curs de formació d'Entitats de Registre impartit pel Consorci AOC.

Es realitzaran actualitzacions amb una freqüència anual, excepte per modificacions en la DPC, que seran notificades a mesura que siguin aprovades.
### <a name="_toc150443636"></a>**5.3.4. Sancions per accions no autoritzades**
L'Entitat de Certificació disposa d'un sistema sancionador per depurar les responsabilitats derivades d'accions no autoritzades. 

Les accions disciplinàries inclouen la suspensió i l'acomiadament de la persona responsable de l'acció danyosa.
### <a name="_toc150443637"></a>**5.3.5. Requisits de contractació de professionals**
L'Entitat de Certificació contracta professionals per a qualsevol funció, fins i tot per a un rol de confiança. En aquest cas, se sotmet als mateixos controls que els empleats restants. En cas que el professional no hagi de sotmetre's a aquests controls, estarà constantment acompanyat per un empleat de confiança. 

En cas que tots o una part dels serveis de certificació siguin operats per un tercer, els controls i previsions realitzats en aquesta secció 5, o en altres parts de la política de certificat o d'aquesta DPC, són aplicats i completats pel tercer que realitza les funcions d'operació dels serveis de certificació. El Consorci AOC és responsable, en tot cas, de l'efectiva execució.

Aquests aspectes queden concretats en l'instrument jurídic utilitzat per acordar la prestació dels serveis de certificació pel tercer diferent del l’Entitat de Certificació.
### <a name="_toc150443638"></a>**5.3.6. Subministrament de documentació al personal**
L’Entitat de Certificació subministrarà la documentació que necessita estrictament el seu personal en cada moment, amb la finalitat que pugui desenvolupar de forma competent les seves funcions.

## <a name="_toc150443639"></a>**5.4. Procediments d’auditoria de seguretat**
### <a name="_toc150443640"></a>**5.4.1. Tipus d'esdeveniments registrats**
L'Entitat de Certificació guarda registre, com a mínim, dels esdeveniments següents relacionats amb la seguretat de l'Entitat:

- L'encesa i l'apagat dels sistemes.
- L'inici i la finalització de l'aplicació d'Entitat (tècnica) de certificació.
- Els intents de crear, esborrar, canviar contrasenyes o permisos dels usuaris dins del sistema.
- Els canvis en les claus de l'Entitat (tècnica) de certificat.
- Els canvis en les polítiques d'emissió de certificats.
- Els intents d'entrada i de sortida del sistema.
- Els intents no autoritzats d'entrada a la xarxa de l'Entitat de Certificació.
- Els intents no autoritzats d'accés als fitxers del sistema
- La generació de les claus de l'Entitat de Certificació.
- Els intents nuls de lectura i escriptura en un certificat i en el directori.
- Esdeveniments relacionats amb el cicle de vida del certificat, com una sol·licitud, una emissió, una revocació i una renovació d'un certificat.
- Esdeveniments relacionats amb el cicle de vida del mòdul criptogràfic, com a recepció, ús i desinstal·lació d'aquest.




L'Entitat de Certificació també guarda, ja sigui manualment o electrònicament, la informació següent:

- La cerimònia de generació de claus i les bases de dades de gestió de claus.
- Registres d’accés físic.
- Manteniments i canvis de configuració del sistema.
- Canvis en el personal.
- Informes de compromisos i discrepàncies.
- Registres de la destrucció de material que contingui informació de claus, dades d'activació o informació personal del subscriptor.
- Possessió de dades d'activació per a operacions amb la clau privada de l'Entitat de Certificació.
- Informes complets dels intents d'intrusió física a les infraestructures que recolzen a l'emissió i gestió de certificats.
### <a name="_toc150443641"></a>**5.4.2. Freqüència de tractament de registres d'auditoria**
Els registres d'auditoria s'examinen almenys una vegada a la setmana per buscar activitat sospitosa o no habitual. 

El processament dels registres d'auditoria consisteix en una revisió dels registres que inclou la verificació que aquests no han estat manipulats, una breu inspecció de totes les entrades de registre i una recerca més profunda de qualsevol alerta o irregularitat en els registres. Les accions realitzades a partir de la revisió d'auditoria també estan documentades.
### <a name="_toc150443642"></a>**5.4.3. Període de conservació de registres d'auditoria**
Els registres d'auditoria es retenen durant almenys 2 (dos) mesos després de processar-los i a partir d'aquell moment s'arxiven d'acord amb la secció 5.5 d'aquesta DPC.
### <a name="_toc150443643"></a>**5.4.4. Protecció dels registres d’auditoria**
Els fitxers de registres, tant manuals com electrònics, es protegeixen de lectures, modificacions, esborrats o qualsevol altre tipus de manipulació no autoritzada usant controls d'accés lògic i físic.
### <a name="_toc150443644"></a>**5.4.5. Procediments de còpia de seguretat**
Es generen còpies de suport incrementals de registre d'auditoria diàriament i còpies completes setmanalment.

Per conservar correctament les còpies de seguretat realitzades, l'Entitat de Certificació té adoptades, com a mínim, les mesures de seguretat següents:

- S'emmagatzemen en armaris ignífugs.
- Només persones autoritzades disposen d'accés a les còpies de seguretat.
- Les còpies estan identificades.
- Si un material ha contingut còpies de seguretat (disquets, DVD’s...) i es volen reutilitzar s'assegura que les dades que ha contingut estiguin completament esborrats fent impossible la seva recuperació.
- S'autoritza expressament l'extracció de les còpies de seguretat fora de l'Entitat de Registre, omplint una fitxa al respecte i anotant el corresponent detall en un llibre de registre.
- Es procura anar dipositant còpies de seguretat periòdicament fora de l'Entitat de Registre.
### <a name="_toc150443645"></a>**5.4.6. Localització del sistema d'acumulació de registres d'auditoria**
El sistema d'acumulació de registres d'auditoria és, almenys, un sistema intern de l'Entitat de Certificació, compost pels registres de l'aplicació, pels registres de xarxa, pels registres del sistema operatiu i per les dades manualment generades, que emmagatzemarà el personal degudament autoritzat.
### <a name="_toc150443646"></a>**5.4.7. Notificació de l'esdeveniment d'auditoria al causant**
Quan el sistema d'acumulació de registres d'auditoria registra un esdeveniment, no és necessari enviar una notificació a l'individu, organització, dispositiu o aplicació que va causar l'esdeveniment.
Es comunica si el resultat de la seva acció ha tingut èxit o no, però no que s'ha auditat l'acció.
### <a name="_toc150443647"></a>**5.4.8. Anàlisi de vulnerabilitats**
Els esdeveniments en el procés d'auditoria es guarden, entre d’altres raons, per monitoritzar les vulnerabilitats del sistema.

Es realitzen anàlisi de vulnerabilitats internes almenys trimestralment i externes almenys anualment.

## <a name="_toc150443648"></a>**5.5. Arxiu d’informacions** 
L'Entitat de Certificació garanteix que tota la informació relativa als certificats es guarda durant un període de temps apropiat, segons l'establert en la secció 5.5.2 d'aquesta DPC.
### <a name="_toc150443649"></a>**5.5.1. Tipus d'esdeveniments registrats**
L'Entitat de Certificació guarda tots els esdeveniments que tinguin lloc durant el cicle de vida d'un certificat, incloent la renovació d'aquest. 

L'Entitat de Certificació guarda un registre del següent:

- Tipus de document presentat en la sol·licitud del certificat
- Nombre d'identificació únic proporcionat per document anterior
- Identitat de l'Entitat de Registre que accepta la sol·licitud de certificat
- La ubicació de les còpies de sol·licituds de certificat i de l'Acord signat pel subscriptor, en cas de certificats individuals.

Així mateix, haurà de conservar els següents documents originals:

- Formulari de sol·licitud de certificats.
- Certificat de dades.
- Full de lliurament de subscriptor de certificats.
### <a name="_toc150443650"></a>**5.5.2. Període de conservació de registres**
L'Entitat de Certificació guardarà els registres especificats a la secció 5.5.1 d'aquesta DPC durant, almenys, 15 (quinze) anys, des de l'extinció del certificat o la finalització del servei prestat.

Tota la informació relativa als Certificats d'Infraestructura es guarda de forma permanent.
### <a name="_toc150443651"></a>**5.5.3. Protecció de l’arxiu**
L'Entitat de Certificació assegura la correcta protecció dels arxius mitjançant l'assignació de personal qualificat per al seu tractament i l'emmagatzematge en caixes de seguretat ignífugues i instal·lacions externes en els casos en què així es requereixi. L'Entitat de Certificació posarà tots els mitjans al seu abast per garantir la confidencialitat enfront de tercers, durant el procés de generació, de les claus privades de signatura digital que proporciona.
### <a name="_toc150443652"></a>**5.5.4. Procediments de còpia de seguretat**
Un tècnic de comunicacions de l'Entitat de Certificació s'encarrega de fer i de verificar la realització de les còpies de seguretat dels logs d'accés lògic al sistema operatiu de la Entitat de Registre.

Aquestes còpies de seguretat es realitzen amb una periodicitat mensual i es guarden en format CD, i aquests discos en una caixa forta present a la mateixa sala.

També es realitzen còpies de seguretat de l'aplicació KeyOne personalitzada per a l'Entitat de Certificació. Aquestes còpies les guarda l'Entitat de Certificació a les seves instal·lacions.
### <a name="_toc150443653"></a>**5.5.5. Requisits de segell de cautela de data i hora**
L’Entitat de Certificació emet els certificats i les LRC amb informació de temps i hora.
### <a name="_toc150443654"></a>**5.5.6. Localització del sistema d'arxiu**
L'Entitat de Certificació té un sistema de manteniment de dades d'arxiu fora de les seves pròpies instal·lacions.
### <a name="_toc150443655"></a>**5.5.7. Procediments d'obtenció i verificació d'informació d'arxiu**
Només les persones autoritzades per l'Entitat de Certificació tenen accés a les dades d'arxiu, ja sigui a les mateixes instal·lacions de l'Entitat de Certificació com als arxius de les Entitats de Registre.

## <a name="_toc150443656"></a>**5.6. Renovació de claus**
Els certificats de l'Entitat de Certificació que s'hagin renovat, es comuniquen als usuaris finals, mitjançant la seva publicació en el directori del Consorci AOC.

## <a name="_1c1lvlb"></a><a name="_toc150443657"></a>**5.7. Compromís de claus i recuperació de desastre**
### <a name="_toc150443658"></a>**5.7.1. Procediment de gestió d'incidències i compromisos**
L’Entitat de Certificació estableix els procediments que aplica a la gestió de les incidències que afecten les seves claus i, molt especialment, als compromisos de la seguretat de les claus.
### <a name="_toc150443659"></a>**5.7.2. Corrupció de recursos, aplicacions o dades**
Quan tingui lloc un esdeveniment de corrupció de recursos, aplicacions o dades, l'Entitat de Certificació inicia les gestions necessàries, segons els documents Pla de Seguretat, Pla d'Emergència i Pla d'Auditoria, per fer que el sistema torni al seu estat normal de funcionament.
### <a name="_toc150443660"></a>**5.7.3. Compromís de la clau privada de l'Entitat**
El pla de continuïtat de negoci de l'Entitat de Certificació (o pla de recuperació de desastres) considera el compromís o la sospita de compromís de la clau privada de l'Entitat de Certificació com un desastre.

En cas de compromís, l'Entitat de Certificació, com a mínim:

- Informar a tots els subscriptors i verificadors del compromís.
- Indicar que els certificats i la informació de l'estat de revocació lliurats usant la clau de l'Entitat de Certificació ja no són vàlids.
- Revocar, en el termini que es pacti amb el supervisor nacional, els certificats emesos per aquesta EC, aplicant, si escau, algun dels procediments previstos en el Pla de Cessament o en el Pla de Continuïtat.
- Notificar a l'Òrgan de Supervisió nacional en el termini màxim de 24 hores un cop s'hagi tingut coneixement del compromís de la clau privada.
- Notificar als fabricants de programari que confien en els certificats, en els terminis establerts en les seves respectives polítiques d'admissió de CAs
### <a name="_toc150443661"></a>**5.7.4. Desastre sobre les instal·lacions**
L'Entitat de Certificació desenvolupa, manté, prova i, si és necessari, executa un pla d'emergència en el cas de desastre, ja sigui per causes naturals o causat per l'home, sobre les instal·lacions, que indica com es restauren els serveis dels Sistemes d'Informació. La ubicació dels sistemes de recuperació de desastres disposa de les proteccions físiques de seguretat detallades en el Pla de Seguretat.
L'Entitat de Certificació és capaç de restaurar l'operació normal de la PKI durant les 24 hores següents al desastre i es poden executar, com a mínim, les accions següents:

- Revocació de certificats 
- Publicació d'informació de revocació

La base de dades de recuperació de desastres utilitzada per l'Entitat de Certificació està sincronitzada amb la base de dades de producció, dins dels límits temporals especificats en el Pla de Seguretat. Els equips de recuperació de desastres de l'Entitat de Certificació tenen les mesures de seguretat físiques especificades en el Pla de Seguretat.

## <a name="_toc150443662"></a>**5.8. Finalització del servei**
### <a name="_toc150443663"></a>**5.8.1. L’Entitat de Certificació**
L'Entitat de Certificació assegura que les possibles interrupcions als subscriptors i a terceres parts són mínimes com a conseqüència del cessament dels serveis de l'Entitat de Certificació i, en particular, assegura un manteniment continu dels registres requerits per proporcionar evidència de certificació en procediments legals.

Abans d'acabar els seus serveis l'Entitat de Certificació executa, com a mínim, els procediments següents:

- Informar tots els subscriptors i verificadors (no es requereix que l'Entitat de Certificació tingui alguna relació anterior amb terceres parts).
- Revocar les autoritzacions de subcontractacions que actuïn en nom de l'Entitat de Certificació en el procés d'emissió de certificats.
- Executar les tasques necessàries per transferir les obligacions de manteniment de la informació de registre i els arxius de registre d'esdeveniments durant els períodes de temps respectius indicats al subscriptor i als verificadors.
- Destruir les claus privades de l'Entitat de Certificació.

L'Entitat de Certificació declara en el seu Pla de Cessament les previsions que ha d'adoptar en cas de finalització del servei. Aquestes inclouen:

- Notificació a les entitats afectades amb una antelació mínima de 2 (dos) mesos a la finalització efectiva del servei.
- Com es tracta l'estat de revocació dels certificats emesos que encara no han expirat.

L'Entitat de Certificació transferirà els certificats, en els termes previstos en la legislació aplicable de signatura electrònica i serveis electrònics de confiança.
### <a name="_toc150443664"></a>**5.8.2. Entitat de Registre**
Sense estipulació.

# **<a name="_toc150443665"></a>6. Controls de seguretat tècnica**
L'Entitat de Certificació utilitza sistemes i productes fiables que estan protegits contra tota alteració i que garanteixen la seguretat tècnica i criptogràfica dels processos de certificació als quals serveixen de suport.

## <a name="_toc150443666"></a>**6.1. Generació i instal·lació del parell de claus**
### <a name="_toc150443667"></a>**6.1.1. Generació del parell de claus**
#### <a name="_toc150443668"></a>**6.1.1.1. Requisits per a tots els certificats**
Les claus pública i privada podran ser generades pel futur posseïdor de claus o per l'Entitat de Certificació.

### <a name="_toc150443669"></a>**6.1.2. Enviament de la clau privada al subscriptor**
Per als certificats de signatura qualificada i els certificats de nivell alt, la clau privada haurà de ser lliurada al posseïdor de claus, degudament protegida mitjançant una targeta intel·ligent, que compleixi l'establert en un perfil de protecció de dispositiu qualificat de creació de signatura electrònica, o bé, emmagatzemada segons els termes de la secció 3.2.1. de la present DPC. Addicionalment, s'hauran de lliurar al posseïdor de claus, els mecanismes d'accés a la mateixa.

### <a name="_toc150443670"></a>**6.1.3. Enviament de la clau pública a l'emissor del certificat**
El mètode d'enviament de la clau pública a l’Entitat de Certificació és PKCS #10, una altra prova equivalent o qualsevol un altre mètode aprovat pel Consorci AOC.

### <a name="_toc150443671"></a>**6.1.4. Distribució de la clau pública del Prestador de Serveis de Confiança**
La clau de l'Entitat de Certificació i les claus de les Entitats de Certificació anteriors en la jerarquia pública de certificació de Catalunya es comuniquen als verificadors, i així s'assegura la integritat de la clau i s'autentica l'origen.

La clau pública de l'Entitat de Certificació, que és l'arrel de la jerarquia, es publica en el directori de l'Entitat de Certificació en forma de certificat autosignat juntament amb una declaració que fa referència al fet que la clau permet autenticar a l'Entitat de Certificació.

S'estableixen mesures addicionals per confiar en el certificat autosignat, com per exemple la comprovació de l'empremta digital del certificat.

La clau pública de l’Entitat de Certificació es publica al seu web del Consorci AOC: [https://epscd.aoc.cat/](https://epscd.aoc.cat/regulacio).

Els usuaris accedeixen al directori per obtenir les claus públiques de l'Entitat de Certificació.

### <a name="_toc150443672"></a>**6.1.5. Mides de claus**
Les claus de l'Entitat de Certificació són de 2.048 bits.

Les claus de tots els certificats emesos per l'Entitat de Certificació són de 2.048 bits.

### <a name="_toc150443673"></a>**6.1.6. Generació de paràmetres de clau pública**
Sense estipulació.

### <a name="_toc150443674"></a>**6.1.7. Comprovació de qualitat de paràmetres de clau pública**
Es realitza d'acord amb l'especificació tècnica ETSI TS 102 176, que indica la qualitat dels algorismes de signatura electrònica.

### <a name="_toc150443675"></a>**6.1.8. Generació de claus en aplicacions informàtiques o en béns d'equip**
Els parells de claus de l'Entitat de Certificació són generats utilitzant hardware criptogràfic que compleix els requisits establerts per l'especificació tècnica CEN CWA 14167 o equivalent i d'acord amb ITSEC, Common Criteria EAL 4+o FIPS 140-2 Nivell 3 o superior nivell de seguretat.

Els parells de claus dels subscriptors de certificats T-CAT de signatura qualificada s'han de generar en targetes intel·ligents o en dispositius criptogràfics que compleixen els requisits establerts per les especificacions tècniques CEN CWA 14169 i CWA 14170 o equivalent.

El parell de claus dels subscriptors de certificats de signatura i de certificats de nivell alt hauran de generar-se en targetes intel·ligents o en dispositius criptogràfics que compleixin els requisits establerts en un perfil de protecció de dispositiu qualificat de creació de signatura electrònica.

La generació de claus per a la resta de certificats es pot realitzar mitjançant aplicacions informàtiques.

### <a name="_toc150443676"></a>**6.1.9. Propòsits d'ús de claus**
El Consorci AOC inclou l'extensió KeyUsage en tots els certificats, indicant els usos permesos de les corresponents claus privades i limitant tècnicament la funcionalitat del certificat en el software compatible amb X.509v3

Els usos admesos per a les claus privades de la CA arrel i intermèdies són la signatura de certificats i la signatura de CRL. No se signen respostes OCSP amb les claus de la CA arrel i intermèdies.

## <a name="_toc150443677"></a>**6.2. Protecció de la clau privada**
### <a name="_toc150443678"></a>**6.2.1. Mòduls de protecció de la clau privada**
#### <a name="_toc150443679"></a>**6.2.1.1. Estàndards dels mòduls criptogràfics**
Les claus privades de les Entitats de Certificació hauran de protegir-se utilitzant mòdul criptogràfic que compleixi els requisits establerts en un perfil de protecció, d'acord amb Common Criteria EAL 4+ o FIPS 140-2 Nivell 3 o superior nivell de seguretat. 

Els parells de claus dels subscriptors de certificats de signatura qualificada i de certificats de nivell alt seran protegits mitjançant targetes intel·ligents o en dispositius criptogràfics que compleixin els requisits establerts en un perfil de protecció de dispositiu qualificat de creació de signatura electrònica.

En el cas que s'hagi de produir una pèrdua de qualificació d'alguns dels dispositius utilitzats pel Consorci AOC com QSCD, es procedirà a la recerca de proveïdors substitutius dels esmentats dispositius, es deixarà d'utilitzar el dispositiu abans de la pèrdua de la qualificació i es notificarà als clients la futura pèrdua de qualificació per a poder prendre les mesures oportunes. En qualsevol cas, el Consorci AOC revocarà tots els certificats vigents que haguessin estat emesos en aquells dispositius que hagin perdut la qualificació.

La protecció de les claus privades de la resta de certificats podrà realitzar-se mitjançant aplicacions informàtiques.

#### <a name="_toc150443680"></a>**6.2.1.2. Cicle de vida de les targetes amb circuit integrat**
Les targetes amb circuit integrat (també targetes intel·ligents) es lliuren en cada emissió de nou certificat per l'Entitat de Registre Col·laboradora o Interna, o bé directament pel Consorci AOC quan actua com a Entitat de Registre Virtual. 

Per cada nova emissió o renovació dels certificats es lliura una targeta nova, és a dir, no es carreguen certificats en targetes usades.

Quan el Consorci AOC detecti errors o defectes en les targetes, podrà retirar d'ofici les targetes afectades. En cas de detectar defectes o errors en casos puntuals, es substituirà la targeta afectada, prèvia revocació del certificat i s'emetrà un nou certificat que es lliurarà en una targeta nova, sense cost addicional per al subscriptor.

### <a name="_toc150443681"></a>**6.2.2. Control per més d'una persona sobre la clau privada**
L'accés a les claus privades de les Entitats de Certificació off-line, haurà de requerir necessàriament del concurs simultani de tres (3) dispositius criptogràfics protegits per una clau d'accés, d'entre cinc (5) dispositius. 

Cadascun d'aquests dispositius és responsabilitat d'una persona concreta, única coneixedora de la clau d'accés al mateix. La clau d'accés és coneguda únicament per una persona responsable d'aquest dispositiu. Cap persona coneix més d'una de les claus d'accés. També es diposita davant Notari un sobre tancat en el que el responsable de cada dispositiu ha escrit la clau d'activació del dispositiu del qual és responsable. Aquests sobres només poden ser retirats de la custòdia del Notari pel propi responsable o per una altra persona degudament autoritzada per aquest (presentant autorització signada per ell).

Els dispositius criptogràfics queden emmagatzemats en les dependències de l'Entitat de Certificació i per al seu accés és necessària una persona addicional.
### <a name="_toc150443682"></a>**6.2.3. Dipòsit de la clau privada**
Les claus privades de l'Entitat de Certificació s'emmagatzemen en espais ignífugs i protegits per controls d'accés físic doble.

### <a name="_toc150443683"></a>**6.2.4. Còpia de seguretat de la clau privada**
Les claus privades de l'Entitat de Certificació s'emmagatzemen en espais ignífugs i protegits per controls d'accés físic doble.

### <a name="_toc150443684"></a>**6.2.5. Arxiu de la clau privada**
La clau privada de l'Entitat de Certificació haurà de comptar amb una còpia de seguretat realitzada, emmagatzemada i recuperada si escau per personal subjecte a la política de confiança del personal. Aquest personal ha d'estar expressament autoritzat per a aquestes finalitats.

Haurà de mantenir-se i utilitzar-se protegida per un dispositiu criptogràfic que compleixi els requisits establerts en un perfil de protecció, d'acord amb Common Criteria EAL 4+, o FIPS 140-2 Nivell 3 o superior nivell de seguretat.

Quan la clau privada de signatura abandoni aquests tipus de dispositius, haurà de fer-ho de forma xifrada.

Els controls de seguretat a aplicar en les còpies de suport de l'Entitat de Certificació hauran de ser d'igual o superior nivell a les quals s'apliquen a les claus habitualment en ús.

Quan les claus s'emmagatzemin en un mòdul criptogràfic de procés dedicat, hauran de proveir-se els controls oportuns perquè aquestes mai puguin abandonar el dispositiu.

No s'emmagatzemaran còpies de claus privades dels certificats, excepte en casos de certificats sobre els quals es prevegi aquesta possibilitat conforme a l'establert en la corresponent PC. Aquesta clau privada podrà estar emmagatzemada per garantir la recuperació de dades.

### <a name="_toc150443685"></a>**6.2.6. Introducció de la clau privada en el mòdul criptogràfic**
Les claus privades de l'Entitat de Certificació queden emmagatzemades en fitxers xifrats amb claus fragmentades i en targetes intel·ligents (de les quals no poden ser extretes).

Aquestes targetes són utilitzades per introduir la clau privada en el mòdul criptogràfic.

<a name="_toc150443686"></a>**6.2.7. Emmagatzematge de la clau privada en el mòdul criptogràfic**

-------------------------------------------------------------------------------------------------
Les claus privades es generen directament en els mòduls criptogràfics.

### <a name="_toc150443687"></a>**6.2.8. Mètode d'activació de la clau privada**
Es requereixen almenys dues persones per activar les claus privades de l'Entitat de Certificació.

Per a certificats T-CAT en targeta, la clau privada del subscriptor s'activa mitjançant la introducció del PIN en la targeta intel·ligent o dispositiu criptogràfic.

Per a certificats T-CAT en targeta, quan la targeta intel·ligent o dispositiu criptogràfic es retiri del dispositiu lector, serà necessària novament la introducció del PIN.

Per a certificats personals, la clau privada del subscriptor s'activarà mitjançant la introducció del PIN en la targeta intel·ligent o de les dades d'activació exigides per al dispositiu criptogràfic o sistema d'emmagatzematge.

### <a name="_toc150443688"></a>**6.2.9. Mètode de desactivació de la clau privada**
Per a certificats T-CAT en targeta, quan la targeta intel·ligent o dispositiu criptogràfic es retiri del dispositiu lector, serà necessària novament la introducció del PIN.

Per a certificats personals que incloguin la política bàsica de signatura qualificada, quan la targeta intel·ligent es retiri del dispositiu lector, o l'aplicació que la utilitzi finalitzi la sessió, serà necessari introduir novament les dades d'activació anteriorment indicades.

Per a certificats personals que incloguin la política bàsica de signatura avançada, quan l'aplicació que utilitzi el certificat finalitzi la sessió, serà necessari introduir novament les dades d'activació de signatura (PIN).

### <a name="_toc150443689"></a>**6.2.10. Mètode de destrucció de la clau privada**
Les claus privades són destruïdes de manera que impedeixi el seu robatori, modificació, divulgació o ús no autoritzat.

### <a name="_toc150443690"></a>**6.2.11. Classificació dels mòduls criptogràfics**
Els mòduls de l'Entitat de Certificació obtenen o superen el nivell EAL 4 de Common Criteria (ISO 15408) amb els augments que es determinen a l'especificació tècnica CEN CWA 14167.

Els mòduls de l'Entitat de Certificació Vinculada han de trobar-se certificats amb el nivell i els augments previstos en un perfil de protecció, d'acord amb Common Criteria EAL 4+, o FIPS 140-2 Nivell 3.

Els mòduls dels subscriptors de certificats T-CAT en targeta obtenen o superen el nivell EAL 4 de Common Criteria (ISO 15408) amb els augments que es determinen a l'especificació tècnica CEN CWA 14169.

Els mòduls dels subscriptors de certificats de signatura electrònica qualificada i de certificats de nivell alt han de trobar-se certificats amb el nivell i augments previstos en un perfil de protecció de dispositiu qualificat de creació de signatura electrònica.

## <a name="_toc150443691"></a>**6.3. Altres aspectes de gestió del parell de claus**
### <a name="_toc150443692"></a>**6.3.1. Arxiu de la clau pública**
L'Entitat de Certificació arxiva les seves claus públiques, d'acord amb l'establert a la secció 5.5.

### <a name="_toc150443693"></a>**6.3.2. Períodes d'utilització de les claus públiques i privada**
Els períodes d'utilització de les claus són els determinats per la durada del certificat i, una vegada transcorregut, no es poden continuar utilitzant.

Com a excepció, la clau privada de desxifrat es pot continuar utilitzant fins al cap de l'expiració del certificat.

## <a name="_toc150443694"></a>**6.4. Dades d'activació**
### <a name="_toc150443695"></a>**6.4.1. Generació i instal·lació de les claus d'activació**
Si l'Entitat de Certificació facilita al subscriptor un dispositiu qualificat de creació de signatura, les dades d'activació del dispositiu hauran de ser generades de forma segura per l'Entitat de Certificació.
### <a name="_toc150443696"></a>**6.4.2. Protecció de les dades d'activació**
<a name="_4bewzdj"></a>Per protegir al màxim les dades d'activació l'Entitat de Certificació s'encarrega de distribuir els elements dels certificats per dos canals diferents.

- En primer lloc, el responsable de l'Entitat de Registre lliura al posseïdor de claus el següent material:
  - Full de lliurament de posseïdor
  - Targeta amb els certificats
  - Software necessari per utilitzar la targeta
  - Carta de lliurament de certificats.
- Al mateix temps, i per correu electrònic, s'envien al posseïdor de claus les dades d'activació del certificat.

D'aquesta forma s'aconsegueix que les dades d'activació estiguin distribuïts separadament de la targeta i també en el temps.
### <a name="_toc150443697"></a>**6.4.3. Altres aspectes de les dades d'activació**
Sense estipulació.

## <a name="_toc150443698"></a>**6.5. Controls de seguretat informàtica**
### <a name="_toc150443699"></a>**6.5.1. Requisits tècnics específics de seguretat informàtica**
Es garanteix que l'accés als sistemes està limitat a individus degudament autoritzats. En particular:

- L'Entitat de Certificació garanteix una administració efectiva del nivell d'accés dels usuaris (operadors, administradors, així com de qualsevol usuari amb accés directe al sistema) per mantenir la seguretat del sistema, incloent la gestió de comptes d'usuari, auditoria i modificacions o denegacions d'accés oportunes.
- L'Entitat de Certificació garanteix que l'accés als sistemes d'informació i aplicacions es restringeix segons l'establert a la política de control d'accés, així com que els sistemes proporcionen els controls de seguretat suficients per implementar la segregació de funcions identificada a les pràctiques de l'Entitat de Certificació, incloent la separació de funcions d'administració dels sistemes de seguretat i dels operadors. En concret, l'ús de programes d'utilitats del sistema està restringit i estretament controlat.
- El personal de l'Entitat de Certificació s'identifica i reconeix abans d'utilitzar aplicacions crítiques relacionades amb el cicle de vida del certificat.
- El personal de l'Entitat de Certificació és responsable i ha de poder justificar les seves activitats, per exemple, mitjançant un arxiu d'esdeveniments.
- S'ha d'evitar la possibilitat de revelació de dades sensibles mitjançant la reutilització d'objectes d'emmagatzematge (per exemple, fitxers esborrats) que quedin accessibles a usuaris no autoritzats.
- Els sistemes de seguretat i monitoratge permeten una ràpida detecció, registre i actuació davant intents d'accessos irregulars o no autoritzats als seus recursos (per exemple, mitjançant un sistema de detecció d'intrusions, monitoratge i alarma).
- L'accés als directoris públics de la informació de l'Entitat de Certificació (per exemple, certificats o informació d'estat de revocació) compta amb un control d'accessos per a modificacions o esborrat de dades.

### <a name="_toc150443700"></a>**6.5.2. Avaluació del nivell de seguretat informàtica**
Les aplicacions informàtiques de l’Entitat de Certificació i de l’Entitat de Registre són fiables, d'acord amb les especificacions tècniques CEN CWA 14167-1 i EN 319 411-2., i s'avalua el grau de compliment mitjançant una auditoria de seguretat informàtica conforme a l'especificació tècnica CWA 14172-2 i un perfil de protecció adequada, d'acord amb la norma ISO 15408 o equivalent.

### <a name="_toc150443701"></a>**6.5.3. Freqüència de revisió de les configuracions dels sistemes de confiança**
El màxim interval de revisió interval màxim de revisió entre 2 versions de les configuracions dels sistemes de confiança serà d'1 (un) any.
## <a name="_toc150443702"></a>**6.6. Controls tècnics del cicle de vida**
### <a name="_toc150443703"></a>**6.6.1. Controls de desenvolupament de sistemes**
Es realitza una anàlisi de requisits de seguretat durant les fases de disseny i especificació de requisits de qualsevol component utilitzada en les aplicacions d'Entitat (tècnica) de certificació i d'Entitat (tècnica) de Registre, per garantir que els sistemes són segurs.

S'utilitzen procediments de control de canvis per a les noves versions, actualitzacions i pegats d'emergència dels esmentats components.


### <a name="_toc150443704"></a>**6.6.2. Controls de gestió de seguretat**
L'Entitat de Certificació garanteix que les seves funcions de gestió de les operacions dels mòduls criptogràfics són suficientment segures; en particular, existeixen instruccions per:

1. Operar els mòduls de forma correcta i segura
1. Instal·lar els mòduls minimitzant el risc de fallida dels sistemes
1. Protegir els mòduls contra virus i software maliciós per garantir la integritat i validesa de la informació que processen

L'Entitat de Certificació haurà de mantenir un inventari de tots els actius informàtics i realitzarà una classificació dels mateixos d'acord amb les seves necessitats de protecció, coherent amb l'anàlisi de riscos efectuat.

La configuració dels sistemes s'auditarà de forma periòdica, d'acord amb allò establert en la secció corresponent d'aquesta política.

Es realitzarà un seguiment de les necessitats de capacitat i es planificaran procediments per garantir suficient disponibilitat electrònica i d'emmagatzematge per als actius informatius.

### <a name="_toc150443705"></a>**6.6.3. Avaluació del nivell de seguretat del cicle de vida**
Sense estipulació addicional.

<a name="_toc150443706"></a>**6.7. Controls de seguretat de xarxa**

-------------------------------------------------------------------
Es garanteix que l'accés a les diferents xarxes de l'Entitat de Certificació està limitat a individus degudament autoritzats. En particular:

- S'implementen controls (com per exemple tallafocs) per protegir la xarxa interna de dominis externs accessibles per terceres parts. Els tallafocs es configuren de manera que s'impedeixin accessos i protocols que no siguin necessaris per a l'operació de les Entitats de Certificació. 
- Les dades sensibles (incloent les dades de registre del subscriptor) es protegeixen quan s'intercanvien a través de xarxes no segures.
- Es garanteix que els components locals de xarxa (com enrutadores/routers) es troben situats en entorns segurs; també es garanteix l'auditoria periòdica de les seves configuracions.

##
# <a name="_toc150443707"></a>**7. Perfils de certificats i llistes de revocació de certificats**
## <a name="_toc150443708"></a>**7.1. Perfil de certificat**
Els documents descriptius dels diferents perfils de certificats digitals que expedeix l'Entitat de Certificació es publiquen a la web del Consorci AOC.

Els certificats emesos pel Consorci AOC i les Entitats de Certificació adscrites a la jerarquia pública de certificació de Catalunya tindran el contingut i els camps descrits en el document “perfil de certificat” corresponent, que el Consorci AOC publica al seu web.

En tot cas, el perfil de cada certificat inclourà en la seva estructura, com a mínim, les següents dades:

1. Número de sèrie, que serà un codi únic respecte al nom distingit de l'emissor amb una entropia superior a 64 bits
1. Algorisme de signatura, amb algun dels algorismes identificats en la secció corresponent d'aquesta política
1. El nom distingit de l'emissor, d'acord amb la secció corresponent d'aquesta política
1. Inici de validesa del certificat, en Temps Coordinat Universal, codificat conforme al RFC 6818
1. Fi de validesa del certificat, en Temps Coordinat Universal, codificat conforme al RFC 6818
1. Nom distingit del subjecte, d'acord amb la secció corresponent d'aquesta política
1. Clau pública del subjecte, codificada d'acord amb el RFC 6818
1. Signatura generada i codificada, d'acord amb la RFC 6818

Els certificats seran conformes amb les següents normes:

1. RFC 6818: Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile, May 2008
1. ITU-T Recommendation X.509 (1997): Information Technology – Open Systems Interconnection - The Directory: Authentication Framework, June 1997
1. L’especificació “*Perfiles de Certificados Electrónicos*” elaborada per la *Direcció de Tecnologies de la Informació i les Comunicacions* (DTIC) del *Ministeri d’Hisenda i Administracions Públiques* (MINHAP)

Addicionalment, els certificats de signatura qualificada seran conformes amb les següents normes:

1. ETSI EN 319 412, parts 1, 2 i 5, a la seva versió vigent al moment de la publicació d'aquesta política.
1. L'especificació *“Perfiles de Certificados Electrónicos”* elaborada per la Direcció de Tecnologies de la Informació i les Comunicacions (DTIC) del Ministeri d'Hisenda i Administracions Públiques (MINHAP)
1. RFC 3739: Internet X.509 Public Key Infrastructure – Qualified Certificate Profile, 2001 (sempre que no entri en conflicte amb les anteriors TS 101 862)

Així mateix, els certificats qualificats hauran de contenir els següents camps:

1. La indicació que s'expedeixen com a certificats qualificats
1. El codi identificatiu únic del certificat
1. La identificació del prestador de serveis de certificació que expedeix el certificat, indicant el nom o raó social, domicili, adreça electrònica i nombre d'identificació fiscal
1. La signatura electrònica avançada del prestador de serveis de certificació que expedeix el certificat
1. La identificació del signatari (el subscriptor, en cas de certificats individuals, o del posseïdor de claus, en cas de certificats d'organització), pel seu nom i cognoms i DNI o equivalent, o a través d'un pseudònim que consti de manera inequívoca
1. Les dades de verificació de signatura que corresponguin a les dades de creació de signatura que es trobin sota el control del signatari
1. Els límits d'ús del certificat, si es preveuen
1. Els límits del valor de les transaccions per les quals pot utilitzar-se el certificat, si s'estableixen
### <a name="_toc150443709"></a>**7.1.1. Número de versió**
Tots els certificats contindran un camp amb el número de versió, indicant que es tracta de certificats de versió 3.
### <a name="_toc150443710"></a>**7.1.2. Extensions de certificat**
Les extensions de cada certificat, així com el seu significat semàntic,es troba descrit en el document “perfil de certificat” corresponent, que el Consorci AOC publica al seu web.
### <a name="_toc150443711"></a>**7.1.3. Identificadors d'objecte d'algorismes**
L'Entitat de Certificació podrà utilitzar el següent algorisme de signatura:

- sha256WithRSAEncryption OID = {iso(1) member-body(2) us(840) rsadsi(113549) pkcs(1) pkcs-1(1) 11}
### <a name="_toc150443712"></a>**7.1.4. Formats de nom**
L'Entitat de Certificació emplenarà els camps de noms dels certificats amb les informacions establertes en el perfil corresponent de certificat, publicat al web.
### <a name="_toc150443713"></a>**7.1.5. Restriccions de noms**
Sense estipulació.
### <a name="_toc150443714"></a>**7.1.6. Identificador d'objecte de política de certificat**
L'Entitat de Certificació emplenarà l'extensió política de certificat amb els identificadors d'objecte establerts en la secció corresponent d'aquesta política, quan s'adhereixen directament a ella mateixa.

En cas de crear la seva pròpia política, en els casos permesos per aquesta política de certificats, inclourà l'identificador d'objecte específicament definit a aquest efecte.
### <a name="_toc150443715"></a>**7.1.7. Ús de l'extensió restriccions de política**
Sense estipulació.
### <a name="_toc150443716"></a>**7.1.8. Sintaxi i semàntica dels qualificadors de política**
L'Entitat de Certificació inclourà en els certificats un qualificador de política, amb els següents elements:

- CPS Pointer
- Explicit Text

CPS Pointer haurà d'incloure una referència URI en les condicions generals de verificació dels certificats emesos per l'Entitat de Certificació.

Explicit Text haurà de contenir una declaració concisa relativa al certificat.
### <a name="_toc150443717"></a>**7.1.9. Semàntica del procés de l'extensió crítica de la política de certificat**
Sense estipulació.
### <a name="_toc150443718"></a>**7.1.10. Especificacions tècniques per a totes les Entitat de Certificació**
Les Entitats de Certificació han de respectar els usos tecnològics generalment acceptats i han d'adaptar-se a les bones pràctiques i als requisits tècnics més avançats.

Addicionalment, la renovació de les Entitats de Certificació immediatament posterior a la present versió de la DPC  respectarà les següents especificacions tècniques:

- L'algorisme utilitzat ha de ser renovat quan existeixi un risc de desencriptació advertit per la comunitat. Les Entitats de Certificació incorporaran, a partir de l'emissió d'aquesta DPC, l'algorisme SHA-256
- Els números de sèrie dels certificats sempre seran sencers i, en tot cas, positius
- S'utilitzarà la codificació UTF-8
- Es simplificarà l'extensió “authorityKeyIdentifier”
- Es restringiran els OIDs generats per les Entitats de Certificació intermèdies
## <a name="_4gjguf0"></a><a name="_toc150443719"></a>**7.2. Perfil de la llista de revocació de certificats**
L'accés a la informació relativa a la llista de revocació de certificats es publica al web del Consorci AOC  https://epscd.aoc.cat/regulacio.

## <a name="_toc150443720"></a>**7.3 Perfil de OCSP**
Els serveis d'OCSP compleixen amb la norma IETF RFC 6960.

# <a name="_toc150443721"></a>**8. Auditoria de conformitat**
L'Entitat de Certificació realitza periòdicament una auditoria de conformitat per provar que compleix els requisits de seguretat i d'operació necessaris per formar part de la jerarquia pública de certificació de Catalunya.

L'Entitat de Certificació pot delegar l'execució de les auditories en una tercera entitat contractada pel Consorci AOC. En aquests casos l'Entitat de Certificació coopera completament amb el personal que duu a terme la recerca.

L'Entitat de Certificació Vinculada ha de realitzar periòdicament una auditoria de conformitat per provar que compleix, una vegada ha començat a funcionar, els requisits de seguretat i d'operació necessaris per formar part de la jerarquia pública de certificació de Catalunya.

L'Entitat de Certificació Vinculada ha d'estar preparada per passar altres revisions, no periòdiques, que demostrin la seva confiança:

- Abans d'acceptar una nova Entitat de Certificació subordinada a la jerarquia, el Consorci AOC ha de realitzar una revisió dels seus documents de seguretat i DPC i PCs per assegurar que compleix els requisits de seguretat i d'operació necessaris per formar part de la Jerarquia d'Entitats de Certificació del Consorci AOC.
- Si en qualsevol moment se sospita que l'Entitat de Certificació Vinculada, una vegada ha començat a funcionar, no compleix algun dels requisits de seguretat, o si s'ha detectat un compromís de claus - ja sigui una sospita o compromís real - o qualsevol esdeveniment que pugui suposar un perill per a la seguretat o integritat de l'Entitat de Certificació Vinculada, es durà a terme una auditoria interna.


L'Entitat de Certificació Vinculada pot delegar l'execució de les auditories a una tercera entitat, i ha de cooperar completament amb el personal que dugui a terme la recerca

## <a name="_toc150443722"></a>**8.1. Freqüència de l'auditoria de conformitat**
L'Entitat de Certificació ha de dur a terme una auditoria de conformitat anualment, a més de les auditories internes que puguin dur a terme sota el seu propi criteri o a qualsevol moment, a causa d'una sospita d'incompliment d'alguna mesura de seguretat o per un compromís de claus.

## <a name="_toc150443723"></a>**8.2. Identificació i qualificació de l'auditor**
L'Entitat de Certificació haurà d'acudir a auditors independents externs per a la realització de les auditories anuals de conformitat. Aquests han de demostrar experiència en seguretat informàtica, en seguretat de sistemes d'informació i en auditories de conformitat d'Entitats de Certificació i dels elements relacionats.

## <a name="_toc150443724"></a>**8.3. Relació de l'auditor amb l'entitat auditada**
Les auditories externes de conformitat executades per tercers són realitzades per entitats independents de l'Entitat de Certificació.
## <a name="_toc150443725"></a>**8.4. Relació d'elements objecte d'auditoria**
Els elements objecte d'auditoria seran els següents:

- Procés d'Entitats de certificació i elements relacionats
- Sistemes d'informació
- Protecció del centre de procés
- Documents

## <a name="_toc150443726"></a>**8.5. Accions a emprendre com a resultat d'una falta de conformitat**
Una vegada rebut l'informe de l'auditoria de compliment dut a terme, l'Entitat de Certificació discuteix, amb l'entitat que ha executat l'auditoria i amb el Consorci AOC, les deficiències oposades i desenvolupa i executa un pla correctiu que les soluciona.

Si l'Entitat de Certificació, una vegada auditat, és incapaç de desenvolupar i/o executar l'esmentat pla o si les deficiències oposades suposen una amenaça immediata per a la seguretat o la integritat del sistema, s'ha de realitzar una de les accions següents:

- Revocar la clau de l’Entitat de Certificació, tal com es descriu en la secció 4.9 d'aquesta DPC.
- Acabar el servei de l’Entitat de Certificació, tal com es descriu en la secció 5.8 d'aquesta DPC.

## <a name="_toc150443727"></a>**8.6. Tractament dels informes d'auditoria**
Els informes de resultats de les auditories seran lliurats al Consorci AOC, en tant que és el PSC, en un termini màxim de 15 (quinze) dies després de l'execució de l'auditoria, per a la seva avaluació i gestió diligent.

# **<a name="_toc150443728"></a>9. Requisits comercials i legals**

## <a name="_toc150443729"></a>**9.1. Imports**
### <a name="_toc150443730"></a>**9.1.1. Import d'emissió i renovació de certificats**
El Consorci AOC estableix els imports que aplica l'Entitat de Certificació en la prestació dels seus serveis. Els imports es poden consultar a la web del servei de certificació digital del Consorci AOC.

### <a name="_toc150443731"></a>**9.1.2. Import d'accés a certificats**
No es pot establir un import per l'accés als certificats.

### <a name="_toc150443732"></a>**9.1.3. Import d'accés a informació d'estat de certificat**
No es pot establir un import per l'accés a la informació d'estat dels certificats.

### <a name="_toc150443733"></a>**9.1.4. Imports d'altres serveis**
Sense estipulació addicional.

### <a name="_toc150443734"></a>**9.1.5. Política de reintegrament**
El Consorci AOC no practicarà reemborsament. En cas de productes defectuosos, es procedirà a substituir el producte defectuós per un altre en bon estat.

## <a name="_toc150443735"></a>**9.2. Capacitat financera**
### <a name="_toc150443736"></a>**9.2.1. Segur de responsabilitat civil**
El Consorci AOC disposa d'una garantia de cobertura de la seva responsabilitat civil suficient, en els termes previstos en la normativa aplicable de signatura electrònica i serveis de confiança. Aquesta assegurança cobreix les actuacions del Consorci AOC com a PSC.

En cas d'ús incorrecte o no autoritzat dels certificats, el Consorci AOC (o l'Entitat de Certificació Vinculada corresponent) no actuarà com a agent fiduciari davant subscriptors i terceres persones, que hauran de dirigir-se contra l'infractor de les condicions d'ús dels certificats establertes pel Consorci AOC (o l'Entitat de Certificació Vinculada corresponent).

### <a name="_toc150443737"></a>**9.2.2. Altres actius**
Sense estipulació.

### <a name="_toc150443738"></a>**9.2.3. Cobertura d’assegurança per a subscriptors i tercers que confien en certificats** 
En cas d'ús incorrecte o no autoritzat dels certificats, l'Entitat de Certificació no actuarà com a agent fiduciari davant subscriptors i terceres persones, que hauran de dirigir-se contra l'infractor de les condicions d'ús dels certificats establertes pel Consorci AOC (o l'Entitat de Certificació).

## <a name="_toc150443739"></a>**9.3. Confidencialitat**
### <a name="_toc150443740"></a>**9.3.1. Informacions confidencials**
Les informacions següents es mantenen de forma confidencial per l'Entitat de Certificació:

1. Informació de negoci subministrada pels seus proveïdors i altres persones amb els qui el Consorci AOC o l'Entitat de Certificació tenen una obligació de guardar secret, establerta legalment o convencionalment.
1. Registres de transaccions, incloent els registres complets i els registres d'auditoria de les transaccions.
1. Registres d'auditoria interna i externa, creats i/o mantinguts per l'Entitat de Certificació i els seus auditors.
1. Plans de continuïtat de negoci i d'emergència.
1. Política i plans de seguretat.
1. Documentació d'operacions, com per exemple, l'arxiu, el monitoratge i altres operacions anàlogues.
1. Qualsevol altra informació identificada com a “Confidencial”.

### <a name="_toc150443741"></a>**9.3.2. Informacions no confidencials**
Les informacions següents no tenen caràcter confidencial:

- Aquesta DPC  i les PC del Consorci AOC. 
- La informació continguda en els certificats
- Qualsevol informació la publicitat de la qual sigui imposada normativament
- Qualsevol altra informació identificada com a “Pública”.

### <a name="_toc150443742"></a>**9.3.3. Responsabilitat per a la protecció d'informació confidencial**
L'Entitat de Certificació és responsable de l'establiment de les mesures apropiades de protecció de la informació confidencial.

Aquestes mesures inclouen les clàusules apropiades d'informació confidencial a les quals estaran sotmeses totes les persones involucrades en els processos de certificació que corresponguin.

## <a name="_toc150443743"></a>**9.4. Protecció de dades personals**
### <a name="_toc150443744"></a>**9.4.1. Política de Protecció de Dades Personals**
El Consorci AOC desenvolupa una política de protecció de les dades personals, d'acord amb la normativa aplicable de protecció de dades. 

En particular, i en compliment de les obligacions imposades pel Reglament (UE) 2016/679 del Parlament Europeu i del Consell,de 27 d'abril de 2016 relatiu a la protecció de les persones físiques en el que respecta al tractament de dades personals i la lliura circulació d'aquestes dades i pel que es deroga la Directiva 95/46/CE- Reglament general de protecció de dades-  (en endavant, RGPD) i la Llei orgànica 3/2018, de 5 de desembre, de protecció de dades personals i garantia dels drets digitals (en endavant, LOPDGDD), disposa d'un Registre d'Activitats de Tractament de dades de caràcter personal, en el qual estan recollits els següents fitxers:

- Subscriptors De Certificats:  <https://www.seu-e.cat/documents/31307/0/RAT_SubscriptorsColectiusCertificats/f70ee619-882e-40ab-b926-4e300d160da3>
- Persones Físiques Certificades: <https://www.seu-e.cat/documents/31307/0/RAT+-+Persones+f%C3%ADsiques+certificades/a943e588-6744-43e5-8ae4-1e87d570591f>

El Consorci AOC desenvolupa els procediments indicats en aquest document, que aplica en la prestació dels seus serveis, en els quals, en compliment dels requisits establerts per les polítiques de certificats que gestiona, es detallen els requisits i obligacions en relació amb l'obtenció i gestió de les dades personals.

El Consorci AOC estableix les mesures de seguretat de caire tècnic i organitzatiu necessàries per donar compliment a les mesures de seguretat aplicables a fitxers i tractaments automatitzats.

### <a name="_toc150443745"></a>**9.4.2. Dades de caràcter personal no disponibles a tercers**
De conformitat amb el que s'estableix en l'article 4 RGPD es consideren dades personals qualsevol informació relativa a persones físiques identificades o identificables.

La informació personal que no hagi de ser inclosa en els certificats i en el mecanisme indicat de comprovació de l'estat dels certificats, és considerada informació personal de caràcter privat.

Les següents dades són considerades en tot cas com a informació privada:

- Sol·licituds de certificats, aprovades o denegades, així com qualsevol altra informació personal obtinguda per a l'expedició i manteniment de certificats.
- Claus privades generades i/o emmagatzemades per l'Entitat de Certificació.
- Qualsevol altra dada de caràcter personal que no sigui susceptible de consulta, emmagatzematge o accés per tercers.

### <a name="_toc150443746"></a>**9.4.3. Dades de caràcter personal disponibles a tercers**
Aquesta informació es tracta d'informació personal que s'inclou en els certificats i el referit mecanisme de comprovació de l'estat dels certificats, d'acord amb la secció 3.1 d'aquest document.

L'esmentada informació, proporcionada durant la sol·licitud de certificats en els termes que es preveuen a la legislació aplicable, és inclosa en els seus certificats i el mecanisme de comprovació de l'estat dels certificats.

Aquestes dades de caràcter personal han d'estar disponibles per tercers per imperatiu legal ("dades públiques").

En tot cas, és considerada no confidencial la següent informació:

1. Els certificats emesos o en tràmit d'emissió.
1. La subjecció del subscriptor a un certificat emès per l'Entitat de Certificació.
1. El nom i els cognoms del subscriptor del certificat, així com qualsevol altra circumstància o dades personals del titular, en el supòsit que siguin significatives en funció de la finalitat del certificat, d'acord amb aquest document.
1. L'adreça electrònica del subscriptor del certificat.
1. Els usos i límits econòmics ressenyats al certificat.
1. El període de validesa del certificat, així com la data d'emissió del certificat i la data de caducitat.
1. El número de sèrie del certificat.
1. Els diferents estats o situacions del certificat i la data de l'inici de cadascun d'ells, en concret: pendent de generació i/o lliurament, vàlid, revocat o caducat i el motiu que va provocar el canvi d'estat.
1. Les LRCs, així com la resta d'informacions d'estat de revocació.
1. La informació continguda en la part pública del Registre de l'Entitat de Certificació.

### <a name="_toc150443747"></a>**9.4.4. Responsabilitat corresponent a la protecció de dades personals**
La informació confidencial és protegida, d'acord amb el RGPD, de la seva pèrdua, destrucció, mal, falsificació i processament il·lícit o no autoritzat.

Davant qualsevol violació de la seguretat o pèrdua de la integritat que tingui un impacte significatiu en el servei de confiança prestat o en les dades personals corresponents, el Consorci AOC notificarà al supervisor nacional competent en matèria de seguretat de la informació o a l'Autoritat de protecció de dades corresponent, en un termini màxim de 24 hores després de tenir coneixement dels fets, d’acord amb l’article 19.2 del Reglament eIDAS.


### <a name="_toc150443748"></a>**9.4.5. Gestió d'incidències relacionades amb les dades de caràcter personal**
El Consorci AOC inclou en aquest document el seu procediment de notificació, gestió i resposta davant les incidències relacionades amb les dades personals.

Aquest procediment de notificació s'inicia quan l'administrador dels sistemes de l'Entitat de Certificació, en les seves instal·lacions, comunica immediatament per telèfon amb el Responsable de l'Entitat de Certificació, descrivint el tipus d'incidència i els efectes que s'observen.

Si durant la gestió de la incidència fa falta fer modificacions del software o en la configuració dels sistemes, o cal restaurar còpies de seguretat o altres intervencions semblants, l'administrador s'espera a rebre la petició corresponent per correu electrònic signat digitalment, que ho envia el Responsable l'Entitat de Certificació o el responsable tècnic del projecte afectat (en aquest cas, amb còpia del missatge al Responsable de l'Entitat de Certificació).

Una vegada fetes les actuacions necessàries i restablit el normal funcionament dels sistemes, l'administrador dels sistemes envia per correu electrònic dirigit al Responsable de l'Entitat de Certificació un informe descriptiu, que en el cas de les incidències produïdes sobre fitxers que contenen dades de caràcter personal, no és més que el formulari tipus degudament emplenat.

El Responsable de l'Entitat de Certificació manté còpia dels formularis corresponents a les incidències registrades durant els 12 últims mesos sobre els fitxers que contenen dades de caràcter personal. Aquests es guarden en un directori dedicat dins del servidor que comparteixen els usuaris de l'Entitat de Certificació, protegit convenientment perquè només pot accedir el personal autoritzat; així queda garantit que es fan còpies de seguretat del seu contingut.

Al formulari de Registre d'Incidències es fan constar les següents dades:

- Quin recurs té la incidència
- El seu codi i descripció
- El dia i l'hora
- El tipus d'incidència
- Els efectes
- El comunicant i el destinatari
- La resposta
- Els procediments previstos a realitzar
- La persona que els realitzarà
- El procediment per a la recuperació
- La persona (i autorització) per a la recuperació
- Les dades restaurades.



### <a name="_toc150443749"></a>**9.4.6. Tractament de dades de caràcter personal**
Per a la prestació del servei, el Consorci AOC necessita recollir i emmagatzemar certes informacions que comporta tractament de dades personals.

El Consorci AOC informa als posseïdors de claus de l'obtenció de les seves dades personals.

La informació personal recollida dels usuaris registrats és emmagatzemada en la base de dades propietat de Consorci AOC que assumeix les mesures d'índole tècnica, organitzativa i de seguretat que garanteixin la confidencialitat i integritat de la informació d'acord amb el que s'estableix en el RGPD, i altra legislació aplicable.

L'usuari respondrà, en qualsevol cas, de la veracitat de les dades facilitades, reservant-se Consorci AOC el dret a excloure dels serveis registrats a tot usuari que hagi facilitat dades falses, sense perjudici de les altres accions legals.

Qualsevol usuari registrat pot en qualsevol moment exercir el dret d’accés, rectificació o supressió, oposició, limitació al tractament i portabilitat, mitjançant sol·licitud a l’adreça del Consorci AOC C/Salvador Espriu 45, 08908 L'Hospitalet de Llobregat o bé mitjançant formulari electrònic (<https://www.seu-e.cat/ca/web/consorciaoc/govern-obert-i-transparencia/informacio-institucional-i-organitzativa/proteccio-de-dades-personals/exercici-dels-drets-relatius-a-la-proteccio-de-dades-personals>) 

No obstant això, si l'usuari considera que el seu dret a la protecció de dades personals ha pogut ser vulnerat, pot reclamar davant l'Autoritat Catalana de Protecció de Dades.

### <a name="_toc150443750"></a>**9.4.7. Comunicació de dades personals**
El Consorci AOC només comunica les dades de caràcter personal a tercers en els casos legalment previstos.

En concret, el Consorci AOC està obligada a revelar la identitat dels signants quan ho sol·licitin els òrgans judicials en l'exercici de les funcions que tinguin atribuïdes i en la resta 

de supòsits previstos en la normativa aplicable de protecció de dades de caràcter personal.

El Consorci AOC dóna compliment a totes les prescripcions legals de conformitat amb el RGPD i la LOPDGDD.

Excepcionalment, en cas de cessament de la seva activitat per part de l'Entitat de Certificació, el Consorci AOC cedirà les dades personals per al supòsit de transferència de prestació del servei.

## <a name="_toc150443751"></a>**9.5. Drets de propietat** 

### <a name="_toc150443752"></a>**9.5.1. Propietat dels certificats i informació de revocació**

El Consorci AOC és l'única entitat que gaudeix dels drets de propietat sobre els certificats que emet.


El Consorci AOC concedeix llicència no exclusiva per reproduir, distribuir, verificar i utilitzar els certificats, sense cap cost, en relació a signatures digitals i/o sistemes de xifrat dins de l'àmbit d'aplicació d'aquesta DPC, d'acord amb el corresponent instrument vinculant entre el Consorci AOC i la part que reprodueixi i/o distribueixi el certificat.


Les normes anteriors figuren als instruments jurídics que existeixen entre el Consorci AOC i els subscriptors i els verificadors.


Addicionalment, els certificats emesos pel Consorci AOC contenen un avís legal relatiu a la propietat d'aquests certificats. Aquesta normativa resulta igualment d'aplicació en l'ús d'informació de revocació de certificats.

### <a name="_toc150443753"></a>**9.5.2. Propietat de la Declaració de Pràctiques de Certificació i les Polítiques de Certificació**
El Consorci AOC és l'única entitat que gaudeix dels drets de propietat sobre les PC de la jerarquia pública de certificació de Catalunya.

El Consorci AOC és propietària d'aquesta DPC. El Consorci AOC no cobra una tarifa per l'excés a aquesta DPC ni a les diferents PC. Qualsevol ús que es faci amb finalitats diferents a la visualització dels documents, com reproducció, redistribució, modificació o creació d'un derivat de les mateixes, estaran subjectes a un acord de llicència amb l'enitat titular dels drets d'autor del document.

### <a name="_toc150443754"></a>**9.5.3. Propietat de la informació relativa a noms**
El subscriptor (o el posseïdor de claus, si escau) conserva qualsevol dret, d'existir aquest, relatiu en la marca, producte o nom comercial contingut al certificat.

El subscriptor (o el posseïdor de claus, si escau) és el propietari del nom distingit del certificat, format per les informacions especificades a la secció 3.1 d'aquesta DPC.

### <a name="_toc150443755"></a>**9.5.4. Propietat de claus**
Els parells de claus són propietat dels subscriptors dels certificats.

Quan una clau es trobi fraccionada en parts, totes les parts de la clau són propietat del propietari de la clau.

## <a name="_toc150443756"></a>**9.6. Obligacions i responsabilitat civil**

### <a name="_toc150443757"></a>**9.6.1. L'Entitat de Certificació**
#### <a name="_toc150443758"></a>**9.6.1.1. Obligacions i altres compromisos**
L'Entitat de Certificació s'obliga a complir el següent:

- Determina la comunitat de subscriptors i verificadors de l'Entitat de Certificació.
- Aprova les polítiques de certificació i, si escau, les polítiques específiques de certificació.
- Aprova, si escau, la documentació contractual i reguladora dels serveis de certificació en la comunitat d'usuaris de l'Entitat de Certificació, d'acord amb el procediment previst en aquesta DPC.
- Informa puntualment al Consorci AOC de totes les informacions relatives als canvis a realitzar, incidències en el servei, reclamacions, denúncies i inspeccions del servei.
- Garanteix, sota la seva plena responsabilitat, que compleix amb tots els requisits establerts en aquesta DPC.
- És l'única entitat responsable del compliment dels procediments descrits en aquesta DPC, fins i tot quan una part o la totalitat de les operacions siguin subcontractades externament.
- Presta els seus serveis de certificació d'acord amb aquesta DPC, on es detallen, almenys, els continguts previstos en la legislació aplicable, descrita a 9.15
- De conformitat amb la llei aplicable, abans de l'emissió i lliurament del certificat, l'Entitat de Certificació informa dels aspectes previstos a la legislació aplicable, així com dels següents aspectes:
  - Indicació de la política aplicable, amb indicació que els certificats no s'expedeixen al públic i la necessitat d'utilització de dispositiu qualificat de creació de signatura.
  - Forma en què es garanteix la responsabilitat patrimonial de l'Entitat de Certificació.
  - L'Entitat de Certificació es declara d'acord amb la política de certificació, la certificació del Prestador de serveis de certificació i la certificació dels productes de signatura electrònica utilitzats.

Aquest requisit es compleix mitjançant un “Text divulgatiu de la política de certificat” aplicable que es transmet electrònicament utilitzant un mitjà de comunicació durador en el temps i en llenguatge comprensible.

- L'Entitat de Certificació obliga als subscriptors, posseïdors de claus i als verificadors mitjançant instruments jurídics apropiats en cada situació, els quals es transmeten electrònicament, en llenguatge escrit i comprensible, a tenir en compte els continguts mínims següents:
  - Prescripcions per donar compliment a l'establert en aquesta DPC.
  - Indicació de la política aplicable, amb indicació de si els certificats s'expedeixen al públic i de la necessitat d'ús del dispositiu qualificat de creació de signatura.
  - Manifestació que la informació continguda en el certificat és correcta, excepte notificació en contra pel subscriptor.
  - Consentiment per a la publicació del certificat al directori i accés per tercers al mateix.
  - Consentiment per a l'emmagatzematge de la informació utilitzada per al registre del subscriptor i del posseïdor de claus, per a la provisió del dispositiu qualificat de creació de signatura i per a la cessió de l'esmentada informació en tercers, en cas de final d'operacions de l'Entitat de Certificació sense revocació de certificats vàlids.
  - Límits d'ús del certificat, incloent els establerts en la secció 4.5 d'aquesta DPC.
  - Informació sobre com validar un certificat, incloent el requisit de comprovar l'estat del certificat, i les condicions en les quals es pot confiar raonablement en el certificat, que resulta aplicable quan el subscriptor actua com a verificador.
  - Limitacions de responsabilitat aplicables, incloent els usos pels quals l'Entitat de Certificació accepta o exclou la seva responsabilitat.
  - Procediments aplicables de resolució de disputes.
  - Llei aplicable i jurisdicció competent.

L'Entitat de Certificació identifica al posseïdor de claus, d'acord amb la legislació aplicable i aquesta DPC. Especialment, l'Entitat de Certificació, comprova per si mateixa la identitat i altres circumstàncies personals dels sol·licitants dels certificats.

#### <a name="_toc150443759"></a>**9.6.1.2. Garanties ofertes**
##### <a name="_toc150443760"></a>**9.6.1.2.1. Garanties ofertes als subscriptors**
L'Entitat de Certificació garanteix al subscriptor, com a mínim:

1. El compliment de les seves obligacions legals com a PSC, d'acord amb la legislació aplicable.
1. Que no hi ha errors en les informacions contingudes als certificats, coneguts o realitzats per aquesta, ni deguts a la manca de diligència en la gestió de la sol·licitud de certificat o en la creació d'aquest.
1. Que els certificats compleixen tots els requisits materials establerts en la DPC.
1. Que els serveis de revocació i l'ús del directori compleixen tots els requisits materials establerts en la DPC.
1. Que, en cas que hagi generat les claus privades, es manté la confidencialitat durant el procés.
1. La responsabilitat de l'Entitat de Certificació, amb els límits que s'estableixin.
##### <a name="_toc150443761"></a>**9.6.1.2.2. Garanties ofertes als verificadors**
L’Entitat de Certificació garanteix al verificador, com a mínim:

1. El compliment de les seves obligacions legals com a PSC d'acord amb la legislació aplicable.
1. Que la informació continguda o incorporada per referència al certificat és correcta, excepte quan indiqui expressament el contrari.
1. En cas de certificats publicats al directori, que el certificat ha estat emès al subscriptor identificat en aquest i que el certificat ha estat acceptat, d'acord amb la secció 4.4 d'aquesta DPC.
1. Que en l'aprovació de la sol·licitud de certificat i en l'emissió del certificat s'han complert tots els requisits materials establerts en aquesta DPC.
1. La rapidesa i seguretat en la prestació dels serveis, especialment dels serveis de revocació i de directori.
1. Que els certificats compleixin tots els requisits materials establerts en aquesta DPC.
1. Que, en cas que hagi generat les claus privades, es manté la confidencialitat durant el procés.
1. Que els serveis de revocació i l'ús del directori compleixen tots els requisits materials establerts en aquesta DPC.

La responsabilitat de l'Entitat de Certificació, amb els límits que s'estableixin.

### <a name="_toc150443762"></a>**9.6.2. Entitats de Registre**

#### <a name="_toc150443763"></a>**9.6.2.1. Obligacions i altres compromisos**
##### <a name="_toc150443764"></a>**9.6.2.1.1. Obligacions de les Entitats de Registre Internes**
L'Entitat de Registre Interna s'obligarà a complir el següent:

1. Nomenar com a operadors de l'entitat (tècnica) de registre a dos o més dels seus treballadors (depenent del EC, generalment quatre o més) i comunicar al Consorci AOC les dades corresponents a aquestes persones per a l'emissió dels certificats d'operador corresponents. Quan un operador deixi de tenir capacitat per actuar com el qual és, sota el control i l'autoritat de l'Entitat de Registre Interna, aquesta Entitat de Registre Interna ha de sol·licitar de forma immediata a l'Entitat de Certificació Vinculada la revocació del certificat d'operador corresponent.
1. Validar i aprovar les sol·licituds de certificats i generar els certificats per als posseïdors de claus, d'acord amb els procediments i instruments tècnics establerts per l'Entitat de Certificació Vinculada, d'acord amb la DPC i la documentació d'operacions de l'Entitat de Certificació Vinculada.
1. Si l'Entitat de Registre Interna no disposés d'informació actualitzada del posseïdor de claus, comprovar la identitat personalment o d'acord amb allò establert a la legislació aplicable, descrita a l'apartat 9.15 de conformitat amb la Llei aplicable, i registrar un justificant acreditatiu del nom complet, lloc i data de naixement, DNI i/o qualsevol altra informació que pogués ser utilitzada per diferenciar una persona respecte una altra en l'àmbit de l'Entitat de Registre Interna.
1. Verificar, quan sigui necessari, qualsevol atribut específic del posseïdor de claus i registrar un justificant acreditatiu de la informació.
1. Realitzar o tramitar les sol·licituds de revocació i renovació de certificats, d'acord amb els procediments i els instruments tècnics establerts per l'Entitat de Certificació Vinculada, d'acord amb la DPC i la documentació d'operacions de l'Entitat de Certificació Vinculada.
1. Emmagatzemar els registres, ja sigui en paper, ja sigui de forma electrònica, amb les adequades mesures de seguretat, autenticitat, integritat i conservació, relatius a la informació continguda en el certificat, durant un període de 15 (quinze) anys des de l’extinció del certificat o la finalització del servei prestat i en tot cas el període que estableix la legislació vigent. Aquests registres han d'estar a la disposició de l'Entitat de Certificació Vinculada.
1. Emmagatzemar els fulls de lliurament de certificat durant un període de 15 (quinze) anys a comptar des de la extinció del certificat o finalització del servei prestat. Aquests registres han d'estar a la disposició de l'Entitat de Certificació Vinculada.
##### <a name="_toc150443765"></a>**9.6.2.1.2. Entitat de Registre Virtual**
L'Entitat de Registre Virtual s'obligarà a complir el següent:

1. Aportar la justificació documental necessària per al registre d'usuaris i per a la posterior emissió de certificats per part de l'Entitat de Certificació Vinculada o l'Entitat de Registre Col·laboradora.
1. La justificació documental haurà de ser realitzada per una unitat orgànica de l'Entitat de Registre Virtual facultada legalment per donar fe de les dades a certificar, que s'indicarà al Consorci AOC.
##### <a name="_toc150443766"></a>**9.6.2.1.3. Entitat de Registre Col·laboradora**
L'Entitat de Certificació podrà delegar algunes funcions a Entitats de Registre Col·laboradores, que en aquest cas quedaran obligades al seu compliment, en les mateixes condicions que l'Entitat de Certificació.


L'Entitat de Registre Col·laboradora assistirà als subscriptors de certificats emesos a les institucions amb Entitat de Registre Virtual, i a tots els subscriptors de la resta de certificats.


L'Entitat de Registre Col·laboradora actuarà en el seu propi nom, sense perjudici de la responsabilitat de l'Entitat de Certificació Vinculada.


L'Entitat de Registre Col·laboradora queda obligada a registrar les dades del certificat i la seva aprovació en cas de ser correctes, així com al registre de les dades d'aquest certificat, pel qual es realitzaran les comprovacions que consideri necessàries referent a la identitat i la resta de dades personals i complementàries dels subscriptors i, si fos necessari, dels posseïdors de claus.


Aquestes comprovacions han d'incloure la justificació documental aportada pel sol·licitant i, si l'Entitat de Registre Col·laboradora ho considerés necessari, qualsevol un altre document i informació rellevant, facilitats pel subscriptor, pel posseïdor de claus o per terceres persones.


Si l'Entitat de Registre Col·laboradora detectés errors en les dades que han de ser incloses en els certificats, o en els documents que justifiquessin aquestes dades, estarà obligada a realitzar els canvis que consideri necessaris abans de l'emissió del certificat, o a la paralització del procés d'emissió i/o gestionar amb el subscriptor la incidència corresponent.


En el cas que l'Entitat de Registre Col·laboradora corregeixi les dades sense gestió prèvia de la incidència corresponent amb el subscriptor, quedarà obligada a notificar les dades que finalment se certifiquin al subscriptor al moment del lliurament.


L'Entitat de Registre Col·laboradora es reserva el dret a no aprovar la sol·licitud d'emissió del certificat, quan la justificació documental aportada pel sol·licitant sigui insuficient per a la correcta identificació i/o autenticació del subscriptor, i si fos necessari, del posseïdor de claus.
#### <a name="_toc150443767"></a>**9.6.2.2. Garanties ofertes a subscriptor i verificadors**
##### <a name="_toc150443768"></a>**9.6.2.2.1. Garantia del Consorci AOC per als serveis de certificació digital**
El Consorci AOC garanteix que la clau privada de l'Entitat de Certificació utilitzada per emetre certificats no ha estat compromesa, tret que el Consorci AOC hagués comunicat el contrari, de conformitat amb aquesta DPC.

El Consorci AOC únicament garanteix que:

1. Els certificats de signatura electrònica contenen tota la informació exigida per la Llei 6/2020 d'11 de novembre, el Reglament (UE) 910/2014 i altra normativa d'aplicació , que es descriu en la secció 9.15.
1. No ha originat ni ha introduït declaracions falses o errònies en la informació de cap certificat, ni ha deixat d'incloure informació necessària aportada pel subscriptor i validada pel Consorci AOC o per l'Entitat de Registre col·laboradora, al moment de l'emissió del certificat.
1. Tots els certificats compleixen els requisits formals i de contingut de la seva Política  de certificació i Perfil de Certificat corresponent.
1. Queda vinculada pels procediments operatius, de seguretat i d'arxiu descrits a la DPC.

##### <a name="_toc150443769"></a>**9.6.2.2.2. Exclusió de la garantia**
El Consorci AOC no garanteix cap software utilitzat pel subscriptor o per qualsevol altra persona, per generar, verificar o no utilitzar de forma diferent cap signatura digital o certificat electrònic  emès pel Consorci AOC, a excepció dels casos en què existeixi una declaració escrita del Consorci AOC en sentit contrari.
### <a name="_toc150443770"></a>**9.6.3. Subscriptors**

#### <a name="_toc150443771"></a>**9.6.3.1. Obligacions i altres compromisos**
##### <a name="_toc150443772"></a>**9.6.3.1.1. Requisits per a tots els tipus de certificats**
L'Entitat de Certificació obliga al subscriptor dels certificats a:

1. Facilitar a l'Entitat de Certificació la informació completa i adequada conforme als requisits d'aquesta DPC, especialment, en allò referent al procediment de registre.
1. Manifestar el seu consentiment previ a l'emissió i lliurament d'un certificat.
1. Complir les obligacions que s'estableixen per al subscriptor en aquesta DPC i amb la legislació vigent descrita en la secció 9.15 d'aquesta DPC.
1. Utilitzar el certificat d'acord amb l'establert en la secció 1.4 d'aquesta DPC 
   i la secció 2.3 de la corresponent Política de Certificació.
1. Notificar a l'Entitat de Certificació, sense retards injustificables, la pèrdua, l'alteració, l'ús no autoritzat, el robatori o el compromís del seu dispositiu qualificat de creació de signatura.
1. Notificar a l'Entitat de Certificació i a qualsevol persona que el subscriptor crea que pugui confiar en el certificat sense retards injustificables:
   1. La pèrdua, el robatori o el compromís potencial de la seva clau privada.
   1. La pèrdua de control sobre la seva clau privada, a causa del compromís de les dades d'activació (per exemple, el codi PIN del dispositiu qualificat de creació de signatura) o per qualsevol altra causa.
   1. Les inexactituds o canvis en el contingut del certificat que conegui o pogués conèixer el subscriptor.
1. Deixar d'utilitzar la clau privada una vegada transcorregut el període indicat a la secció corresponent.
1. Transferir als posseïdors de claus les obligacions específiques d'aquests.
1. No monitoritzar, manipular o realitzar actes d'enginyeria reversa sobre la implantació tècnica de la jerarquia pública de certificació de Catalunya sense permís previ per escrit.
1. No comprometre intencionadament la seguretat de la jerarquia pública de certificació de Catalunya.

##### <a name="_toc150443773"></a>**9.6.3.1.2. Requisits específics per als certificats de signatura electrònica qualificada**
L'Entitat de Certificació Vinculada obligarà al subscriptor a:

1. Utilitzar el parell de claus exclusivament per a signatures electròniques i conforme a qualsevol altra limitació que li sigui notificada
1. Ser especialment diligent en la custòdia de la seva clau privada i del seu dispositiu qualificat de creació de signatura, amb la finalitat d'evitar usos no autoritzats
1. Si el subscriptor genera les seves pròpies claus, s'obliga a:

1\. Generar les seves claus de subscriptor utilitzant un algorisme reconegut com a acceptable per a la signatura electrònica qualificada

2\. Crear les claus dins del dispositiu qualificat de creació de signatura

3\. Utilitzar longituds i algorismes de clau reconeguts com a acceptables per a la signatura electrònica qualificada

5. Notificar a l'Entitat de Certificació, sense retards injustificables, la pèrdua, l'alteració, l'ús no autoritzat, el robatori o el compromís del seu dispositiu qualificat de creació de signatura
#### <a name="_toc150443774"></a>**9.6.3.2. Garanties ofertes pel subscriptor**
L'Entitat de Certificació obliga, mitjançant el corresponent instrument jurídic, al subscriptor a garantir que:

1. Totes les manifestacions realitzades a la sol·licitud són correctes.
1. Totes les informacions subministrades pel subscriptor que es trobin contingudes al certificat són correctes.
1. El certificat s'utilitza exclusivament per a usos legals i autoritzats, d'acord amb aquesta DPC.
1. Cada signatura digital creada amb la clau privada corresponent a la clau pública inclosa en el certificat és la signatura digital del subscriptor i que el certificat ha estat acceptat i es troba operatiu (no ha expirat ni ha estat revocat) al moment de creació de la signatura.
1. El subscriptor és una entitat final i no una Entitat de Certificació i no utilitza la clau privada corresponent a la clau pública inclosa en el certificat per signar cap certificat (o qualsevol un altre format de clau pública certificada) ni LRC.
1. Cap persona no autoritzada no ha tingut mai accés a la clau privada del subscriptor.
#### <a name="_toc150443775"></a>**9.6.3.3. Protecció de la clau privada**
L'Entitat de Certificació s'obliga, mitjançant el corresponent instrument jurídic, a garantir que és l'únic responsable dels danys causats pel seu incompliment del deure protegir la clau privada.
### <a name="_toc150443776"></a>**9.6.4. Verificadors**
#### <a name="_toc150443777"></a>**9.6.4.1. Obligacions i altres compromisos**
L'Entitat de Certificació obliga a l'usuari de certificats a:

1. Assessorar-se sobre el fet que el certificat és apropiat per a l'ús que es pretén.
1. Verificar la validesa o revocació dels certificats emesos, per a això utilitzarà informació sobre l'estat dels certificats. 
1. Verificar tots els certificats de la jerarquia de certificats, abans de confiar en la signatura digital o en algun dels certificats de la jerarquia.
1. Tenir present qualsevol limitació en l'ús del certificat, amb independència que es trobi en el mateix certificat o en el contracte de verificador. 
1. Tenir present qualsevol precaució establerta en un contracte o en un altre instrument, amb independència de la seva naturalesa jurídica. 
1. No monitoritzar, manipular o realitzar actes d'enginyeria inversa sobre la implantació tècnica de la jerarquia pública de certificació de Catalunya, sense permís previ per escrit.
1. No comprometre intencionadament la seguretat de la jerarquia pública de certificació de Catalunya.
1. Reconèixer que les signatures electròniques produïdes per dispositius qualificats de signatura electrònica són signatures electròniques equivalents a signatures manuscrites, d'acord amb l'article 25.2 del Reglament (UE) 910/2014. 
1. Verificar la validesa dels certificats en el moment de realitzar qualsevol operació basada en els mateixos.

En aquest sentit, els tercer que confiïn, comprovaran que el certificat qualificat 		consultant a la llista de confiança de la Unió Europea (TSL). La norma ETSI TS 119 	615 proporciona orientació sobre com validar una certificació digital amb les llistes 	de confiança de la UE, amb la finalitat de determinar si pot ser considerat com un 	certificat qualificat.
#### <a name="_toc150443778"></a>**9.6.4.2. Garanties ofertes pel verificador**
L'Entitat de Certificació obliga al verificador, mitjançant el corresponent instrument jurídic, a manifestar que:

1. Disposa de suficient informació per prendre una decisió informada per confiar o no en el certificat.
1. És l'únic responsable de confiar o no en la informació continguda al certificat.
1. Serà l'únic responsable si incompleix les seves obligacions com a verificador.
### <a name="_toc150443779"></a>**9.6.5. Consorci AOC**
#### <a name="_toc150443780"></a>**9.6.5.1. Obligacions i compromisos**
El Consorci AOC s'obliga a operar les Entitats de Certificació al seu càrrec, incloent l'Entitat de Certificació arrel de la jerarquia pública de certificació de Catalunya, de manera diligent, de conformitat amb les polítiques, pràctiques i normativa de l'esmentada jerarquia.
#### <a name="_toc150443781"></a>**9.6.5.2. Garanties ofertes als subscriptors**
El Consorci AOC garanteix que la clau privada de les Entitats de Certificació al seu càrrec no ha estat compromesa, tret que així ho indiqui expressament mitjançant el directori del Consorci AOC.

El Consorci AOC únicament garanteix:

1. Que els certificats contenen tota la informació exigida per la legislació aplicable, descrita en la secció 9.15 d'aquesta DPC. Que no ha originat ni introduït declaracions falses o errònies en la informació dels certificats, ni tampoc ha deixat d'incloure informació necessària aportada per l'Entitat de Certificació i validada pel Consorci AOC o l'Entitat de Registre, al moment d'emissió dels certificats.
1. Que tots els certificats emesos compleixen els requisits formals i de contingut.

El Consorci AOC està vinculat als procediments operatius i de seguretat descrits en aquesta DPC.
#### <a name="_toc150443782"></a>**9.6.5.3. Garanties ofertes als verificadors**
La responsabilitat del Consorci AOC, que deriva d'una relació indirecta, és la prevista en la legislació aplicable, descrita a la secció 9.15 d'aquesta DPC.
#### <a name="_toc150443783"></a>**9.6.5.4. Exclusió de garanties**
El Consorci AOC no garanteix cap software utilitzat pel subscriptor o per qualsevol altra persona, per generar, verificar o no utilitzar de forma diferent cap signatura digital o certificat electrònic  emès pel Consorci AOC, a excepció dels casos en què hi hagi una declaració escrita del Consorci AOC en sentit contrari.
### <a name="_toc150443784"></a>**9.6.6. Directori**
#### <a name="_toc150443785"></a>**9.6.6.1. Obligacions i compromisos**
L'Entitat de Certificació pot delegar algunes funcions al directori, que en aquest cas està obligat al seu compliment, en les mateixes condicions que aquesta.


Les funcions, obligacions i deures del directori s'estableixen detalladament en aquesta DPC, així com en la documentació jurídica auxiliar, especialment la lliurada a subscriptors, posseïdors de claus i verificadors.
#### <a name="_toc150443786"></a>**9.6.6.2. Garanties**
L'Entitat de Certificació estableix en aquesta DPC la responsabilitat civil del directori quan sigui operat per una tercera entitat.

## <a name="_toc150443787"></a>**9.7. Renúncies de garanties**
### <a name="_toc150443788"></a>**9.7.1. Rebuig de garanties de l'Entitat de Certificació**
L'Entitat de Certificació pot rebutjar totes les garanties del servei que no es trobin vinculades a obligacions establertes per la legislació aplicable, descrita a la secció 9.15 d'aquesta DPC, incloent especialment la garantia d'adaptació per a un propòsit particular o garantia d'ús mercantil del certificat.

## <a name="_toc150443789"></a>**9.8. Limitacions de responsabilitat**
### <a name="_toc150443790"></a>**9.8.1. Limitacions de responsabilitat de l'Entitat de Certificació**
L'Entitat de Certificació limita la seva responsabilitat restringint el servei a l'emissió i gestió de certificats i, si escau, de parells de claus de subscriptors i dipòsits criptogràfics (de signatura i verificació de signatura, així com de xifrat o desxifrat) subministrats per aquesta.

L'Autoritat de Certificació pot limitar la seva responsabilitat mitjançant la inclusió de límits d'ús del certificat límits de valor de les transaccions per les quals es pot utilitzar el certificat.
### <a name="_toc150443791"></a>**9.8.2. Cas fortuït i força major**
L'Autoritat de Certificació inclou clàusules per limitar la seva responsabilitat en cas fortuït i en cas de força major, als instruments jurídics amb que vinculi subscriptors i verificadors.

## <a name="_toc150443792"></a>**9.9. Indemnitzacions**
### <a name="_toc150443793"></a>**9.9.1. Clàusula d'indemnització de subscriptor**
No s'establirà clàusula d'indemnització del subscriptor.
### <a name="_toc150443794"></a>**9.9.2. Clàusula d’indemnitat de verificador**
No s'establirà clàusula d'indemnització del verificador.

## <a name="_toc150443795"></a>**9.10. Termini i finalització**
### <a name="_toc150443796"></a>**9.10.1. Termini i finalització**
L'Entitat de Certificació estableix, en els seus instruments jurídics amb els subscriptors i els verificadors, una clàusula que determina el període de vigència de la relació jurídica en virtut de la qual subministra certificats als subscriptors.
### <a name="_toc150443797"></a>**9.10.2. Supervivència**
L'Entitat de Certificació estableix, en els seus instruments jurídics amb els subscriptors i els verificadors, clàusules de supervivència, en virtut de les quals s’estableix com certes obligacions continuen vigents després de la finalització de la relació jurídica reguladora del servei entre les parts.


A aquest efecte, l'Entitat de Certificació vetlla perquè, almenys els requisits continguts a les seccions Obligacions, Responsabilitat civil, Auditoria de conformitat i Confidencialitat, continuïn vigents després de la finalització de la política de certificació i dels instruments jurídics que vinculin l'Entitat de Certificació amb subscriptors i verificadors.


El Consorci AOC determinarà un Pla de Cessament de Negoci. Aquest Pla de Cessament de Negoci establirà les obligacions que assumeix el Consorci AOC en cas de cessament d'activitats, dirigides a mantenir en vigència dels certificats emesos fins a la seva expiració i l'ús i custòdia de tota la informació generada pel Consorci AOC en la seva activitat de Prestador de serveis de certificació, com per exemple, les còpies de seguretat, logs i documents de tot tipus, independentment del suport en que hagin estat generats o emmagatzemats. A aquest efecte, el Consorci AOC s'assegura que es genera una còpia de seguretat amb periodicitat, com a previsió complementària de l'activitat corrent i igualment de l'assegurament de la continuïtat de negoci.

## <a name="_toc150443798"></a>**9.11. Notificacions**
L'Entitat de Certificació estableix, en els seus instruments jurídics vinculants amb subscriptors i verificadors, clàusules de notificació, en les quals s'estableix el procediment pel qual les parts es notifiquen fets mútuament.

## <a name="_toc150443799"></a>**9.12. Modificacions**
### <a name="_toc150443800"></a>**9.12.1. Procediment per a les modificacions**
El Consorci AOC pot modificar, de forma unilateral, la documentació reguladora del servei, sempre que procedeixi segons el procediment següent:

- La modificació ha d'estar justificada des del punt de vista tècnic, legal o comercial.
- S'estableix un control de modificacions per garantir, en tot cas, que les especificacions resultants compleixen els requisits que s'intenten complir i que van donar motiu al canvi.
- S'estableixen les implicacions que el canvi d'especificacions té sobre l'usuari, i es preveu la necessitat de notificar-li les esmentades modificacions. 
- Els canvis han de ser aprovats pel Consorci AOC.
### <a name="_toc150443801"></a>**9.12.2. Període i mecanismes per a notificacions**
Les modificacions d'aquesta DPC es notifiquen al Consorci AOC, per a la seva posterior aprovació.

## <a name="_toc150443802"></a>**9.13. Resolució de conflictes**
### <a name="_toc150443803"></a>**9.13.1. Resolució extrajudicial de conflictes**
L'Entitat de Certificació estableix, en els seus instruments jurídics amb subscriptors i verificadors, els procediments de mediació i resolució de conflictes aplicables, amb aquesta finalitat, es té en compte la consideració com a Administració Pública de l'Entitat de Certificació.

Les situacions de discrepància que es derivin de l'ús dels certificats emesos per l'Entitat de Certificació es resolen aplicant els mateixos criteris de competència que en els casos dels documents signats per escrit.
### <a name="_toc150443804"></a>**9.13.2. Jurisdicció competent**
L'Entitat de Certificació estableix, en els seus instruments jurídics vinculants amb subscriptors i verificadors, una clàusula de jurisdicció competent, que indica que la competència judicial internacional correspon als jutges espanyols.


La competència territorial i funcional es determina en virtut de les regles de dret internacional privat i regles de dret processal que resultin d'aplicació.


Així mateix, es té en compte la legislació administrativa que resulti aplicable.

## <a name="_toc150443805"></a>**9.14. Llei aplicable**
L'Entitat de Certificació estableix, en els seus instruments jurídics amb subscriptors i verificadors, que la llei aplicable a la prestació dels serveis, incloent la DPC  i les PC , és la següent:

- Reglament (UE) núm. 910/2014 del Parlament Europeu i del Consell, de 23 de juliol de 2014, relatiu a la identificació electrònica y els serveis de confiança per a les transaccions electròniques en el mercat interior i por la qual es deroga la Directiva 1999/93/CE.
- Llei 6/2020, d’11 de novembre, reguladora de determinats aspectes dels serveis electrònics de confiança.
- Llei 39/2015, d’1 d’octubre, del Procediment Administratiu Comú de las Administracions Públiques.
- Llei 40/2015, d’1 d’octubre, de Règim Jurídic del Sector Públic.
- Reglament (UE) 2016/679 del Parlament Europeu i del Consell, de 27 d’abril de 2016, relatiu a la protecció de les persones físiques en el que respecta al tractament de dades personals i a la lliure circulació d’aquestes dades i pel qual es deroga la Directiva 95/46/CE (RGPD).
- Llei Orgànica 3/2018, de 5 de desembre, de Protecció de Dades Personals i garantia dels drets digitals (LOPDGDD).
- Directiva (UE) 2015/2366 del Parlament Europeu i del Consell de 25 de novembre de 2015 sobre serveis de pagament en el mercat interior i per la qual es modifiquen les Directives 2002/65/CE, 2009/110/CE y 2013/36/UE i el Reglament (UE) núm. 1093/2010 i es deroga la Directiva 2007/64/CE.
- Reglament d’Execució (UE) 2015/1502 de la Comissió de 8 de setembre de 2015 sobre la fixació d’especificacions i procediments tècnics mínims per als nivells de seguretat de mitjans d’identificació electrònica segons el disposat en l’article 8, apartat 3, del Reglament (UE) núm.910/2014 del Parlament Europeu i del Consell, relatiu a la identificació electrònica i els serveis de confiança per a les transaccions electròniques en el mercat interior. 
- Decisió d’Execució (UE) 2016/650 de la Comissió, de 25 d’abril de 2016, per la qual es fixen les normes per a l'avaluació de la seguretat dels dispositius qualificats de creació de firmes i  segells segons l'article 30, apartat 3, i a l’article  39, apartat 2, del Reglament (UE) núm. 910/2014 del Parlament Europeu i del Consell, relatiu a la identificació electrònica i els serveis de confiança per a les transaccions electròniques en el mercat interior.
- Reglament Delegat (UE) 2018/389 de la Comissió de 27 de novembre de 2017 pel qual es complementa la Directiva (UE) 2015/2366 del Parlament Europeu i del Consell en lo relatiu a les normes tècniques de regulació per l’autenticació reforçada de clients i uns estàndards de comunicació oberts comuns i segurs.
- Real Decreto 311/2022, de 3 de mayo, por el que se regula el Esquema Nacional de Seguridad
- El Marc Normatiu de Seguretat de la Informació de l’Agència de Ciberseguretat de Catalunya a l’àmbit de la Generalitat de Catalunya que determina les línies estratègiques, polítiques, estàndards i guies de seguretat pròpies de la Generalitat de Catalunya, amb caràcter supletori a manca d’un propi.
- Política de Seguretat del Consorci AOC.

## <a name="_toc150443806"></a>**9.15. Conformitat amb la llei aplicable**
El Consorci AOC serà responsable dels danys i perjudicis ocasionats als usuaris pels seus serveis i a altres tercers en els termes establerts en la legislació vigent i en la present DPC.

## <a name="_toc150443807"></a>**9.16. Clàusules diverses**
### <a name="_toc150443808"></a>**9.16.1. Acord íntegre**
L'Entitat de Certificació estableix, en els seus instruments jurídics vinculants amb subscriptors i verificadors, clàusules d'acord íntegre, en virtut de les quals s'entén que l'instrument jurídic regulador del servei conté la voluntat completa i tots els acords entre les parts.
### <a name="_toc150443809"></a>**9.16.2. Subrogació**
Els drets i els deures associats a la condició d'Entitat de Certificació no poden ser objecte de cessió a tercers de cap tipus, ni cap tercera entitat es pot subrogar en la posició jurídica d'una Entitat de Certificació.


En cas que es produeixi una cessió o subrogació, es procedeix a la finalització de l'esmentada Entitat de Certificació.


Els drets i els deures associats a la condició d'Entitat de Certificació Virtual podran ser objecte, de canvi, de cessió i subrogació, però aquestes incidències hauran de ser notificades al Consorci AOC.
### <a name="_toc150443810"></a>**9.16.3. Divisibilitat**
L'Entitat de Certificació estableix clàusules de divisibilitat, en els seus instruments jurídics vinculants amb subscriptors i verificadors, en virtut de les quals la invalidesa d'una clàusula no afecta la resta del contracte.

En cas que, com a causa als articles 7 i 8 de la Llei 7/1998  de 13 d’abril sobre condicions generals de la contractació, es considerarien no incorporades al contracte, o nul·les algunes o qualsevol de les clàusules indicades, la referida no incorporació o nul·litat no determina la ineficàcia total del contracte, si aquest pogués subsistir sense les clàusules indicades.
### <a name="_toc150443811"></a>**9.16.4. Aplicacions**
Sense estipulació.
### <a name="_toc150443812"></a>**9.16.5. Altres clàusules**
Sense estipulació.
