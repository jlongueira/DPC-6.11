![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.001.png)

**Descripció dels perfils de Certificats Consorci AOC![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.002.png)![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.003.png)![ref1]![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.005.png)![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.006.png)![ref1]**

![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.007.png)

Referència:  D1111\_E0650\_Perfils\_de\_Certificats Versió:   6.9 

Data:   15/11/2023 

La versió original en vigor d'aquest document es troba en format electrònic publicada en el  lloc  web  del  Consorci  AOC  i  pot  ser  accessible  a  través  de  la  següent  URL: [https://epscd.aoc.cat/regulacio/](https://epscd.aoc.cat/regulacio)

Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

**Historial de versions** 



|**Versió** |**Resum dels canvis** |**Data** |
| - | - | - |
|5\.0 |Adaptació a EIDAS |9/5/2018 |
|6\.0 |Unificació en un únic document del document de perfils emesos per EC-SECTORPUBLIC i EC-CIUTADANIA. |26/07/2018 |
|6\.1 |<p>- Revisió anual de la documentació, post auditoria eIDAS. </p><p>- “*4.4. Perfil dels Certificats de Servidor Segur (Dispositiu SSL)*”: eliminada opció de multidominio o wildcard. </p>|24/07/2019 |
|6\.2 |<p>- “2.6: Perfil dels certificats de signatura d'empleat públic amb pseudònim nivell alt":  Inclusió d'EKU   </p><p>- [“2.8. Perfil dels certificats de signatura d'empleat públic de nivell nivell alt": Inclusió d'EKU ](http://epscd.catcert.net/crl/ec-sectorpublic.crl?ts=5e7b4a82#heading=h.c8vt0ujae7bd)</p>|31/3/2020 |
|6\.3 |●  Inclusió de certificats d'autenticació i signatura de treballador públic de nivell mitjà i de nivell alt |03/08/2020 |
|6\.4 |●  Revisió del Document |27/01/2021 |
|6\.5 |●  Revisió del Document |20/07/2021 |
|6\.6 |●  “3.1.1 Certificat”: Alteració en descripció: C = “País d’expedició del document identificatiu del subscriptor.” |31/03/2022 |
|6\.7 |●  Revisió sense canvis. |29/03/2023 |
|6\.8 |<p>- Eliminades referències a QWAC y QTSA. </p><p>- Canvi URLs de regulació y CRL. </p><p>- Marcada extensió QCStatements com a no crítica.  </p>|10/05/2023 |
|6\.9 |<p>- Apartat 2.7: Inclusió de T-CATP pseudònim. </p><p>- Eliminació de la direcció i el NIF de les extensions dels perfils de certificat. </p><p>- Eliminació del email protection del Extended Key Usage (EKU) i Rfc822. Inclusió extensió Adobe Authentic Documents Trust.  </p>|15/11/2023 |

**Índex** 

1. [Introducció  5](#_page4_x97.00_y113.92)
1. [Descripció de Perfils de Certificats Personals del Sector Públic  6](#_page5_x97.00_y113.92)
1. [Perfil dels Certificats d’autenticació de empleat públic de nivell alt (T-CAT autenticació)  6](#_page5_x97.00_y163.92)
   1. [Certificat  6](#_page5_x97.00_y223.92)
   1. [Extensions  7](#_page6_x97.00_y113.92)
1. [Perfil dels Certificats qualificat d’autenticació i signatura de empleatpúblic de nivell mitjà (T-CATP)  8](#_page7_x97.00_y113.92)
   1. [Certificat  8](#_page7_x97.00_y154.92)
   1. [Extensions  9](#_page8_x97.00_y113.92)
3. [Perfil dels Certificats d'autenticació i signatura de persona vinculada de nivell mitjà (T- CATP persona vinculada)  10](#_page9_x97.00_y113.92)
1. [Certificat  10](#_page9_x97.00_y154.92)
1. [Extensions  11](#_page10_x97.00_y113.92)
4. [Perfil dels Certificats d'autenticació i signatura de persona vinculada de nivell alt (T-CAT persona vinculada)  12](#_page11_x97.00_y113.92)
1. [Certificat  12](#_page11_x97.00_y154.92)
1. [Extensions  13](#_page12_x97.00_y113.92)
5. [Perfil dels Certificats d'autenticació de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim autenticació)  14](#_page13_x97.00_y113.92)
1. [Certificat  14](#_page13_x97.00_y154.92)
1. [Extensions  15](#_page14_x97.00_y113.92)
6. [Perfil dels Certificats de signatura de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim signatura)  16](#_page15_x97.00_y113.92)
1. [Certificat  16](#_page15_x97.00_y154.92)
1. [Extensions  17](#_page16_x97.00_y113.92)
7. [Perfil dels Certificats qualificats d’autenticació i signatura d‘empleat públic amb pseudònim de nivell mig/substancial (T-CATP pseudònim)  18](#_page17_x97.00_y113.92)
1. [Certificat  18](#_page17_x97.00_y170.92)
1. [Extensions  19](#_page18_x97.00_y113.92)
8. [Perfil dels Certificats d’autenticació i signatura de representant davant les Administracions Públiques (T-CAT representant)  20](#_page19_x97.00_y113.92)
1. [Certificat  20](#_page19_x97.00_y170.92)
1. [Common name  21](#_page20_x97.00_y113.92)
1. [Extensions  22](#_page21_x97.00_y113.92)
9. [Perfil dels Certificats de signatura de empleat públic de nivell alt (T-CAT signatura)  23](#_page22_x97.00_y113.92)
   1. [Certificat  23](#_page22_x97.00_y154.92)
   1. [Extensions  24](#_page23_x97.00_y113.92)
9. [Perfil dels Certificats d'autenticació i signatura de treballador públic de nivell mitjà (T- CATP Treballador públic)  25](#_page24_x97.00_y113.92)
1. [Certificat  25](#_page24_x97.00_y154.92)
1. [Extensions  26](#_page25_x97.00_y113.92)
11. [Perfil dels Certificats d'autenticació i signatura de treballador públic de nivell alt (T-CAT Treballador públic)  27](#_page26_x97.00_y113.92)
    1. [Certificat  27](#_page26_x97.00_y154.92)
    1. [Extensions  28](#_page27_x97.00_y113.92)
3. [Descripció de Perfils de Certificats de Ciutadans  29](#_page28_x97.00_y113.92)

[3.1. Perfil dels Certificats de Ciutadà (idCAT certificat)  29](#_page28_x97.00_y143.92)

1. [Certificat  29](#_page28_x97.00_y211.92)
1. [Extensions dels certificats  30](#_page29_x97.00_y113.92)
4. [Descripció dels Perfils de Certificats de Dispositius i Infraestructura  31](#_page30_x97.00_y113.92)
1. [Perfil dels Certificats de Segell Electrònic Avançat (Segell nivell mig)  31](#_page30_x97.00_y163.92)
   1. [Certificat  31](#_page30_x97.00_y229.92)
   1. [Extensions dels certificats  32](#_page31_x97.00_y113.92)
   1. [Extensions de nivell mitjà  33](#_page32_x97.00_y113.92)
1. [Perfil dels Certificats d’Aplicació (Dispositiu aplicació)  34](#_page33_x97.00_y113.92)
1. [Certificat  34](#_page33_x97.00_y141.92)
1. [Extensions dels certificats  35](#_page34_x97.00_y113.92)
1. **Introducció<a name="_page4_x97.00_y113.92"></a>** 

Aquest  document  de  Descripció  dels  perfils  de  certificats  té  per  objecte  detallar  el contingut dels certificats emesos pel Consorci AOC, en virtut dels requisits establerts a aquests efectes pel Ministeri competent en serveis electrònics de confiança; és a dir, especifica quina és la configuració (principalment, Camp del DN, Nom i Descripció) i l’extensió (Extensió, Crítica –si/no-, i Valors) dels certificats personals de empleat públic, certificats de ciutadans i certificats de Dispositius i Infraestructura, cada un d’ells amb una Política de certificació pròpia (accessibles des de la URL https://epscd.aoc.cat /regulacio). També fa referència a la composició del camp Common Name (CN) en el cas d’aquells certificats que en disposin. 

La seva emissió s’ha efectuat tenint en compte les disposicions del Reglament (UE) 910/2014 del Parlament Europeu i del Consell de 23 de juliol de 2014, relatiu a la identificació electrònica i els serveis de confiança per a les transaccions electròniques al mercat interior i pel qual es deroga la Directiva 1999/93/CE (d’ara endavant, eIDAS). També s’ha seguit com a referència el document "*Perfiles de certificados electrónicos*", 1a  edició  electrònica  d'abril  de  2016  i  disponible  esta  publicación  en  el  Portal  de Administración Electrónica (PAe):[ http://administracionelectronica.gob.es/.](http://administracionelectronica.gob.es/) 

2. **Descripció<a name="_page5_x97.00_y113.92"></a> de Perfils de Certificats Personals del Sector Públic** 
1. **Perfil<a name="_page5_x97.00_y163.92"></a> dels Certificats d’autenticació de empleat públic de nivell alt (T-CAT autenticació)** 
1. **Certificat<a name="_page5_x97.00_y223.92"></a>** 



|**Camp del DN![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.012.png)**|**Nom![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.013.png)**|**Descripció![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.014.png)**|
| - | - | - |
|O, Organization|Organització|Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat l'empleat.|
|OU, Organization Unit|Unitat en la organització|“Empleat públic de nivell alt d'autenticació”|
|Title (opcional)|Càrrec |Ha d'incloure el càrrec de la persona física, que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number|NIF|<p></p><p>Número del document d'identitat del signatari amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page5_x97.00_y736.92)[^1]</p>|
|SN, Surname|Cognoms (persona física)|Primer i segon cognoms (d'acord amb el document d'identitat – DNI / Passaport, …) + ” - DNI” + NIF de l'empleat públic |
|Given name|Nom|Nom, d'acord amb el document d'identitat (DNI, passaport,...) |
|CN, Common Name|Nom, cognoms i  NIF|Nom i dos cognoms d'acord amb el document d'identitat (DNI / passaport) + “ – DNI” + NIF de l'empleat públic + “ (AUT)”|
|C, Country|País|C = “ES”|
|Organization Identifier||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat)|

Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

2. **Extensions<a name="_page6_x97.00_y113.92"></a>** 



|**Extensió**|**Crítica**|**Valors**|
| - | - | - |
|X509v3 Basic Constraints|Sí|CA:FALSE|
|X509v3 Subject Key Identifier|-|<id de la clau pública del certificat, obtingut a partir del hash de la mateixa>|
|X509v3 Authority Key Identifier|-|<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa>|
|X509v3 Authority Information Access|-|<p>Access Method: Id-ad-ocsp</p><p>Access Location: <URI d'accés al servei OCSP> Access Method: Id-ad-caIssuers</p><p>Access Location: <URI del certificat de l’EC emissora> </p>|
|X509v3 CRL Distribution Points|-|<URI de la CRL> |
|X509v3 Key Usage|Sí|Digital Signature Key encipherment |
|X509v3 Extended Key Usage|-|<p>Client Authentication SmartCardLogon </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies|-|<p><OID associat a la DPC> 1: 1.3.6.1.4.1.15096.1.3.2.7.1.2 </p><p><URI de la DPC> </p><p><User Notice></p><p>" Certificat electrònic d’empleat públic de nivell alt d'autenticació. </p><p><OID de la política de certificació d'empleat públic de nivell alt> 2.16.724.1.3.5.7.1 </p><p><OID de la política de certificació ETSI: NCP+> 0.4.0.2042.1.2 </p>|
|X509v3 Subject Alternative Name|-|<p>(opcional) otherName-userPrincipalName (UPN): Usuari en el domini Windows del posseïdor de claus </p><p>directoryName:</p><p>` `OID: 2.16.724.1.3.5.7.1.1 =</p><p>“Certificat electrònic d’empleat públic de nivell alt d'autenticació” </p><p>` `OID: 2.16.724.1.3.5.7.1.2 = <O del DN></p><p>` `OID: 2.16.724.1.3.5.7.1.3 = <CIF de l’entitat  subscriptora></p><p>` `OID: 2.16.724.1.3.5.7.1.4 = <serialNumber del DN></p><p>` `OID: 2.16.724.1.3.5.7.1.6 = <Given name></p><p>` `OID: 2.16.724.1.3.5.7.1.7 = <Primer cognom del empleat públic>  OID: 2.16.724.1.3.5.7.1.8 = <Segon cognom del empleat públic> </p>|


2. **Perfil<a name="_page7_x97.00_y113.92"></a> dels Certificats qualificat d’autenticació i signatura de empleatpúblic de nivell mitjà (T-CATP)** 
1. **Certificat<a name="_page7_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organització|<p>Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat l'empleat. </p><p>. </p>|
|OU, Organization Unit |Unitat en la organització|“Empleat  públic de nivell mig” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física, que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF|<p></p><p>Número del document d'identitat del signatari, amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page7_x97.00_y736.92)[^2]</p>|
|SN, Surname |Cognoms (persona física)|Primer i segon cognom (d'acord amb el document d'identitat – DNI  / Passaport, …) + ” - DNI ” + NIF de l’empleat públic |
|Given name |Nom|Nom, d’acord amb el document d’identitat (DNI, passaport, ...) |
|CN, Common Name |Nom, cognoms i  NIF|Nom i dos cognoms d’acord amb el document d’identitat (DNI / Passaport) + “ – DNI ” + NIF de l’empleat públic + “ (TCAT”)” |
|C, Country |País|C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l’entitat) |

Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

2. **Extensions<a name="_page8_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica** |**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI de acces al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’EC emissora>  </p>|
|X509v3 CRL Distribution Points |- |[ <U](http://epscd.catcert.net/crl/ec-sectorpublic.crl)RI de la CRL> |
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key Encipherment |
|X509v3 Extended Key Usage ||<p>Client Authentication </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies |- |<p><OID de la DPC> 1.3.6.1.4.1.15096.1.3.2.7.3.1 </p><p><URI de la DPC> </p><p><User Notice>  </p><p>Certificat electrònic de empleat públic de nivell mig.  </p><p><OID que indica certificat d'empleat públic de nivell mitjà> 2.16.724.1.3.5.7.2</p><p><OID de la política de certificació ETSI: QCP-n> 0.4.0.194112.1.0 </p>|
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> </p><p>Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1 </p>|
|X509v3 Subject Alternative Name |- |<p>directoryName: </p><p>` `OID: 2.16.724.1.3.5.7.2.1 = “Certificat electrònic d’empleat públic de nivell mitjà” </p><p>` `OID: 2.16.724.1.3.5.7.2.2 = <O del DN> </p><p>` `OID: 2.16.724.1.3.5.7.2.3 = <CIF de l'entitat subscriptora> </p><p>` `OID: 2.16.724.1.3.5.7.2.4 = <serialNumber del DN> </p><p>` `OID: 2.16.724.1.3.5.7.2.6 = <Given name> </p><p>` `OID: 2.16.724.1.3.5.7.2.7 = <Primer cognom de l'empleat públic>  OID: 2.16.724.1.3.5.7.2.8 = <Segon cognom de l'empleat públic>  OID: 2.16.724.1.3.5.7.2.9 = <correu electrònic de l'empleat públic> </p>|


3. **Perfil<a name="_page9_x97.00_y113.92"></a> dels Certificats d'autenticació i signatura de persona vinculada de nivell mitjà (T-CATP persona vinculada)** 
1. **Certificat<a name="_page9_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organització|Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat l'empleat. |
|OU, Organization Unit |Unitat en la organització|“Persona vinculada de nivell mig” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física, que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF|<p></p><p>Número del document d'identitat del signatari, amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page9_x97.00_y736.92)[^3]</p>|
|SN, Surname |Cognoms (persona física)|Primer i segon cognoms (d'acord amb el document d'identitat – DNI / Passaport, …) + ” - DNI ” + NIF de l'empleat públic. |
|Given name |Nom|Nom, d'acord amb el document d'identitat (DNI, passaport, ...) |
|CN, Common Name |Nom, cognoms i  NIF|Nom i dos cognoms, d'acord amb el document d'identitat (DNI / Passaport) + “ – DNI ” + NIF de l'empleat públic + “ (TCAT”)” |
|C, Country |País|C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat) |

Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

2. **Extensions<a name="_page10_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica** |**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtinguda a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d’acces al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’ EC emissora> </p>|
|X509v3 CRL Distribution Points |- |[<URI de la CRL>l ](http://epscd.catcert.net/crl/ec-sectorpublic.crl)|
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key encipherment |
|X509v3 Extended Key Usage |- |<p>Client Authentication </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies |- |<p><OID de la DPC> 1.3.6.1.4.1.15096.1.3.2.86.1 <URI de la DPC> </p><p><User Notice>  </p><p>" Certificat electrònic de persona vinculada de nivell mig.” </p><p><OID de la política de certificació ETSI: QCP-n> 0.4.0.194112.1.0 </p>|
|Qualified Certificate Statements ||<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> </p><p>Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1 </p>|


Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

4. **Perfil<a name="_page11_x97.00_y113.92"></a> dels Certificats d'autenticació i signatura de persona vinculada de nivell alt (T-CAT persona vinculada)** 
1. **Certificat<a name="_page11_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organtizació |Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculada la persona. |
|OU, Organization Unit |Unitat a l’organització |“Persona vinculada de nivell alt” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física, que ho vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF |<p><a name="_page11_x97.00_y736.92"></a> SerialNumber = p. ej: IDCES-00000000G. 3 caràcters per indicar el tipus de document (IDC= document nacional d'identitat) + 2 caràcters per identificar el país (ÉS) + Número d'identitat (Printable String) ) Size [RFC 5280] 64 </p><p>Número del document d'identitat del signatari, amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page11_x97.00_y736.92)[^4]</p>|
|SN, Surname |Cognoms (persona física)|Primer i segon cognoms (d'acord amb el document d'identitat – DNI, Passaport, …)+” - DNI ” + NIF de la persona vinculada |
|Given name |Nom |Nom de pila, d'acord amb el document d'identitat (DNI, passaport, ...) |
|CN, Common Name |Nom, cognoms i NIF |Nom i dos cognoms, d'acord amb el document d'identitat (DNI / Passaport) + “ – DNI ” + NIF de la persona vinculada + “ (TCAT)” |
|C, Country |País |C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat) |

2. **Extensions<a name="_page12_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica**|**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d’acces al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’EC emissora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcSSCD 0.4.0.1862.1.4 </p><p>Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> Id-etsi- qcs-QcType 0.4.0.1862.1.6.1 </p>|
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key encipherment|
|X509v3 Extended Key Usage|-|<p>Client Authentication SmartCardLogon </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies |- |<p>` `<OID associat a la DPC> 1.3.6.1.4.1.15096.1.3.2.82.1 </p><p><URI de la DPC> </p><p>User Notice: “Certificat electrònic de persona vinculada de nivell alt.” </p><p><OID de la política de certificació ETSI: QCP-n-qscd> 0.4.0.194112.1.2 </p>|
|X509v3 Subject Alternative Name |- |(opcional) otherName-userPrincipalName (UPN): Usuari en el domini Windows del posseïdor de claus  |

5. **Perfil<a name="_page13_x97.00_y113.92"></a> dels Certificats d'autenticació de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim autenticació)** 
1. **Certificat<a name="_page13_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat l'empleat. |
|OU, Organization Unit |Unitat en l’organització |“Empleat  públic amb pseudònim de nivell alt d'autenticació” |
|Pseudonym |Pseudònim  Obligatori segons ETSI EN 319 412-2 |Ex: NIP 111111111 |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física, que la vincula amb l'Administració, organisme o entitat de dret públic subscriptora del certificat. |
|CN, Common Name |Informar amb el pseudònim de l’organisme |Title/PSEUDONIM + “ - “ + NIP + “ - “ + Organization (AUT) Ex: SUBINSPECTOR - NIP 11111111 - ORGANITZACIÓ DE PROVES (AUT) |
|C, Country |País |C = “ES” |

2. **Extensions<a name="_page14_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica** |**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d'accés al servei OCSP> </p><p>Access Method: Id-ad-caIssuers </p><p>Access Location: < URL de localització del certificat de la CA.> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|X509v3 Key Usage |Sí |Digital Signature Key encipherment |
|X509v3 Extended Key Usage |- |<p>Client Authentication SmartCardLogon </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies |- |<p><OID associat a la DPC> 1.3.6.1.4.1.15096.1.3.2.4.1.2 <URI de la DPC> </p><p>User Notice: "Certificat electrònic d’empleat públic amb pseudònim de nivell alt d'autenticació.” </p><p><OID associat a certificat d'empleat públic amb pseudònim de nivell alt> 2.16.724.1.3.5.4.1 </p><p><OID de la política de certificació ETSI: NCP+> 0.4.0.2042.1.2 </p>|
|X509v3 Subject Alternative Name |- |<p>(opcional) otherName-userPrincipalName (UPN): Usuari en el domini Windows del posseïdor de claus </p><p>directoryName: </p><p>` `OID: 2.16.724.1.3.5.4.1.1 = “ Certificat electrònic d’empleat públic amb pseudònim de nivell alt d'autenticació” </p><p>` `OID: 2.16.724.1.3.5.4.1.2 = <O del DN> </p><p>` `OID: 2.16.724.1.3.5.4.1.3 = <CIF de l’entitat subscriptora> </p>|

6. **Perfil<a name="_page15_x97.00_y113.92"></a> dels Certificats de signatura de empleat públic amb pseudònim de nivell alt (T-CAT pseudònim signatura)** 
1. **Certificat<a name="_page15_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme, o entitat de dret públic, a la qual es troba vinculat l'empleat. |
|OU, Organization Unit |Unitat en la organització |“Empleat  públic amb pseudònim de nivell alt de signatura.” |
|Pseudonym |Pseudònim Obligatori segons ETSI EN 319 412-2 |Ex: NIP 111111111 |
|Title (opcional) |Càrrec  |Ha d'incloure el càrrec de la persona física, que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|CN, Common Name |Informar amb el pseudònim de l'organisme |Title/PSEUDONIM + “ - “ + NIP + “ - “ + Organization (SIG) Ex: SUBINSPECTOR - NIP 11111111 - ORGANITZACIÓ DE PROVES (SIG) |
|C, Country |País |C = “ES” |

2. **Extensions<a name="_page16_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica** |**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d’accés al servei OCSP> </p><p>Access Method: Id-ad-caIssuers </p><p>Access Location: < URL de localització del certificat de la CA.> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|X509v3 Certificate Policies |- |<p><OID de la DPC corresponent> 1.3.6.1.4.1.15096.1.3.2.4.1.1 <URI de la DPC> </p><p>User Notice: " Certificat qualificat de signatura de empleat públic amb pseudònim de nivell alt.’’ </p><p><OID associat a certificat d'empleat públic amb pseudònim de nivell alt> 2.16.724.1.3.5.4.1 </p><p><OID de la política de certificació ETSI: QCP-n-qscd> 0.4.0.194112.1.2 </p>|
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcSSCD 0.4.0.1862.1.4 </p><p>Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1 </p>|
|X509v3 Key Usage |Sí |Content Commitment |
|X509v3 Extended Key Usage |- |Adobe Authentic Documents Trust |
|X509v3 Subject Alternative Name |- |<p>directoryName: </p><p>` `OID: 2.16.724.1.3.5.4.1.1 = “Certificat qualificat de signatura d’empleat públic amb pseudònim de nivell alt” </p><p>` `OID: 2.16.724.1.3.5.4.1.2 = <O del DN> </p><p>` `OID: 2.16.724.1.3.5.4.1.3 = <CIF de l’entitat suscriptora> </p>|

7. **Perfil<a name="_page17_x97.00_y113.92"></a> dels Certificats qualificats d’autenticació i signatura d‘empleat públic amb pseudònim de nivell mig/substancial (T- CATP pseudònim)** 
1. **Certificat<a name="_page17_x97.00_y170.92"></a>** 



|**Camp del DN** ![ref9]|**Nom** ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.019.png)|**Descripció** ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.020.png)|
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme, o entitat de dret públic, a la qual es troba vinculat l'empleat. |
|OU, Organization Unit |Unitat en la organització |“Empleat  públic amb pseudònim de nivell mig.” |
|Pseudonym |Pseudònim Obligatori segons ETSI EN 319 412-2 |Ex: NIP 111111111 |
|Title (opcional) |Càrrec  |Ha d'incloure el càrrec de la persona física, que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|CN, Common Name |Informar amb el pseudònim de l'organisme |Title/PSEUDONIM + “ - “ + NIP + “ - “ + Organization (TCAT) Ex: SUBINSPECTOR - NIP 11111111 - ORGANITZACIÓ DE PROVES (TCAT) |
|C, Country |País |C = “ES” |

2. **Extensions<a name="_page18_x97.00_y113.92"></a>** 



|**Extensió ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.021.png)**|**Crític a** |**Valors ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.022.png)**|
| - | :-: | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d’accés al servei OCSP> </p><p>Access Method: Id-ad-caIssuers </p><p>Access Location: < URL de localització del certificat de la CA.> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|X509v3 Certificate Policies |- |<p><OID de la DPC corresponent> 1.3.6.1.4.1.15096.1.3.2.4.2 <URI de la DPC> </p><p>User Notice: “Certificat qualificat empleat públic amb pseudònim de nivell mig’’ </p><p><OID associat a certificat d'empleat públic amb pseudònim de nivell mig/substancial> 2.16.724.1.3.5.4.2 </p>|
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1 </p>|
|X509v3 Key Usage |Sí |Content Commitment |
|X509v3 Extended Key Usage |- |Adobe Authentic Documents Trust |
|X509v3 Subject Alternative Name |- |<p>directoryName: </p><p>` `OID: 2.16.724.1.3.5.4.1.1 = “Certificat electrònic empleat públic amb pseudònim de nivell mig” </p><p>` `OID: 2.16.724.1.3.5.4.1.2 = <O del DN> </p><p>` `OID: 2.16.724.1.3.5.4.1.3 = <CIF de l’entitat suscriptora> </p>|

8. **Perfil<a name="_page19_x97.00_y113.92"></a> dels Certificats d’autenticació i signatura de representant davant les Administracions Públiques (T-CAT representant)** 
1. **Certificat<a name="_page19_x97.00_y170.92"></a>** 



|**Camp del DN** ![ref9]|**Nom** ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.023.png)|**Descripció** ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.024.png)|
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat a la qual representa el representant. |
|OU, Organization Unit |Unitat en l’organització |“Representant davant les AAPP de nivell alt” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física, que la vincula amb l'Administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF |<p><a name="_page19_x97.00_y736.92"></a> SerialNumber = p. ej: IDCES-00000000G. 3 caràcters per indicar el tipus de document (IDC= document nacional d'identitat, PAS=passaport, ...) + 2 caràcters per identificar el país (ÉS) + Número d'identitat (Printable String) ) Size [RFC 5280] 64 </p><p>Número del document d'identitat de l'empleat públic amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page19_x97.00_y736.92)[^5]</p>|
|SN, Surname |Cognoms (persona física)|Primer i segon cognoms (d'acord amb el document d'identitat – DNI / Passaport, …) |
|Given name |Nom |Nom, d'acord amb el document d'identitat (DNI / Passaport, ...) |
|CN, Common Name |Nom , cognoms i NIF |<p>Veure taula específica. </p><p>Exemple: “12345678Z Pedro Antonio López (R: B0085974Z)” </p>|
|C, Country |País |C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat, p.e. VATES-B0085974Z) |
|Description (2.5.4.13) |Dades de representació |<p>Reg:XXX /Fulla:XXX /Tom:XXX /Secció:XXX /Llibre:XXX/ Foli:XXX  /Data: dd-mm-aaaa /Inscripció:XXX </p><p>Notari: Nom Cognom1 Cognom2 /Núm Protocol: XXX /Data Atorgament: dd-mm-aaaa </p><p>En Butlletins o Diaris Oficials: Butlletí: XXX /Data: dd-mm-aaaa /Número resolució: XXX </p>|

2. **Common<a name="_page20_x97.00_y113.92"></a> name** 



|**Camp ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.025.png)**|**Contingut ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.026.png)**|**Exemple  ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.027.png)**|**Grandària (\*) ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.028.png)**|
| - | - | - | - |
|NIF |Número DNI/NIE |12345678Z |10 |
|Nom |D'acord amb el document d'identitat |Pedro Antonio ||
|Cognom 1 |D'acord amb el document d'identitat |López ||
|Literal |(R: ||4 |
|NIF de l'entitat representada |NIF de l'entitat representada, tal i com figura en els registres oficials |Q0085974Z |9 |
|Literal |) ||2 |

(\*) tenint en compte espai en blanc posterior 

3. **Extensions<a name="_page21_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica**|**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la EC, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d'accés al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’EC emissora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|X509v3 Certificate Policies |- |<p><OID de la política de certificació corresponent al certificat> 1.3.6.1.4.1.15096.1.3.2.8.1.1 </p><p><URI de la DPC> </p><p>User Notice: “Certificat electrònic de representant davant les AAPP de nivell alt.’’ </p><p><OID de certificat de representant de persona jurídica> 2.16.724.1.3.5.8 <OID de la política de certificació ETSI QCP-n-qscd> 0.4.0.194112.1.2 </p>|
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcSSCD 0.4.0.1862.1.4 </p><p>Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1  </p>|
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key encipherment |
|X509v3 Extended Key Usage |- |<p>Client Authentication SmartCardLogon </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Subject Alternative Name |- |(opcional) otherName-userPrincipalName (UPN): Usuari en el domini Windows del posseïdor de claus |

Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

9. **Perfil<a name="_page22_x97.00_y113.92"></a> dels Certificats de signatura de empleat públic de nivell alt (T-CAT signatura)** 
1. **Certificat<a name="_page22_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat l'empleat. |
|OU, Organization Unit |Unitat en l'organització |“Empleat  públic de nivell alt de signatura” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF |<p></p><p>Número el document d'identitat de l'empleat públic amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page22_x97.00_y736.92)[^6]</p>|
|SN, Surname |Cognoms (persona física)|Primer i segon cognoms (d'acord amb el document d'identitat – DNI / Passaport, …) + ” - DNI ” + NIF de l'empleat públic |
|Given name |Nom |Nom, d'acord amb document d'identitat (DNI, passaport, ...) |
|CN, Common Name |Nom, cognoms i NIF |Nom i dos cognoms d'acord amb document d'identitat (DNI / Passaport) + “ – DNI ” + NIF de l'empleat públic + “ (SIG)” |
|C, Country |País |C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat) |

3<a name="_page22_x97.00_y736.92"></a> SerialNumber = p. ex: IDCES-00000000G. 3 caràcters per indicar el tipus de document (IDC= document nacional d'identitat, PAS=passaport, ...) + 2 caràcters per identificar el país (ÉS) + Nombre d'identitat (Printable String) ) Size [RFC 5280] 64 
Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

2. **Extensions<a name="_page23_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica**|**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la EC, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d'accés al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’EC emissora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcSSCD 0.4.0.1862.1.4 </p><p>Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1  </p>|
|X509v3 Key Usage |Sí |Content Commitment |
|X509v3 Extended Key Usage |- |Adobe Authentic Documents Trust |
|X509v3 Certificate Policies |- |<p>` `<OID associat a la DPC> 1.3.6.1.4.1.15096.1.3.2.7.1.1 </p><p><URI de la DPC> </p><p>User Notice: " Certificat qualificat de signatura de empleat públic de nivell alt.” </p><p><OID associat a certificat d'empleat públic de nivell alt> 2.16.724.1.3.5.7.1 <OID de la política de certificació ETSI: QCP-n-qscd> 0.4.0.194112.1.2 </p>|
|X509v3 Subject Alternative Name |- |<p>directoryName: </p><p>` `OID: 2.16.724.1.3.5.7.1.1 =“Certificat qualificat de signatura d’empleat públic de nivell alt ” </p><p>` `OID: 2.16.724.1.3.5.7.1.2 = <O del DN> </p><p>` `OID: 2.16.724.1.3.5.7.1.3 = <CIF de l'entitat subscriptora> </p><p>` `OID: 2.16.724.1.3.5.7.1.4 = <serialNumber del DN> </p><p>` `OID: 2.16.724.1.3.5.7.1.6 = <Given name> </p><p>` `OID: 2.16.724.1.3.5.7.1.7 = <Primer cognom de l'empleat públic> </p><p>` `OID: 2.16.724.1.3.5.7.1.8 = <Segon cognom de l'empleat públic> </p>|


Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

10. **Perfil<a name="_page24_x97.00_y113.92"></a> dels Certificats d'autenticació i signatura de treballador públic de nivell mitjà (T-CATP Treballador públic)** 
1. **Certificat<a name="_page24_x97.00_y154.92"></a>** 



|**Camp del DN** ![ref6]|**Nom** ![ref7]|**Descripció** ![ref8]|
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat el treballador. |
|OU, Organization Unit |Unitat en l'organització |“Treballador  públic de nivell mig” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF |<p></p><p>Número el document d'identitat del signant amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page24_x97.00_y736.92)[^7]</p>|
|SN, Surname |Cognoms (persona física)|Primer i segon cognoms (d'acord amb el document d'identitat – DNI / Passaport, …) + ” - DNI ” + NIF del treballador públic |
|Given name |Nom |Nom, d'acord amb document d'identitat (DNI, passaport, ...) |
|CN, Common Name |Nom, cognoms i NIF |Nom i dos cognoms d'acord amb document d'identitat (DNI / Passaport) + “ – DNI ” + NIF del treballador públic + “ (SIG)” |
|C, Country |País |C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat) |

3<a name="_page24_x97.00_y736.92"></a> SerialNumber = p. ex: IDCES-00000000G. 3 caràcters per indicar el tipus de document (IDC= document nacional d'identitat, PAS=passaport, ...) + 2 caràcters per identificar el país (ÉS) + Nombre d'identitat (Printable String) ) Size [RFC 5280] 64 
Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

2. **Extensions<a name="_page25_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica**|**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la EC, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d'accés al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’EC emissora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key encipherment |
|X509v3 Extended Key Usage ||<p>` `Client Authentication </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies |- |<p><OID associat a la DPC> 1.3.6.1.4.1.15096.1.3.2.86.3 <URI de la DPC> </p><p><User Notice>  </p><p>` `"Certificat electrònic de treballador públic de nivell mig.’’ </p><p><OID de la política de certificación ETSI: QCP-n> 0.4.0.194112.1.0 </p>|
|Qualified Certificate Statements ||<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> </p><p>Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1 </p>|


Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

11. **Perfil<a name="_page26_x97.00_y113.92"></a> dels Certificats d'autenticació i signatura de treballador públic de nivell alt (T-CAT Treballador públic)** 
1. **Certificat<a name="_page26_x97.00_y154.92"></a>** 



|**Camp del DN** |**Nom** |**Descripció** |
| - | - | - |
|O, Organization |Organització |Denominació (nom “oficial”) de l'Administració, organisme o entitat de dret públic subscriptora del certificat, a la qual es troba vinculat el treballador. |
|OU, Organization Unit |Unitat en l'organització |“Treballador  públic de nivell alt” |
|Title (opcional) |Càrrec |Ha d'incloure el càrrec de la persona física que la vincula amb l'administració, organisme o entitat de dret públic subscriptora del certificat. |
|Serial Number |NIF |<p></p><p>Número el document d'identitat del signant amb la semàntica proposta per la norma ETSI EN 319 412-[1 ](#_page26_x97.00_y736.92)[^8]</p>|
|SN, Surname |Cognoms (persona física) |Primer i segon cognoms (d'acord amb el document d'identitat – DNI / Passaport, …) + ” - DNI ” + NIF del treballador públic |
|Given name |Nom |Nom, d'acord amb document d'identitat (DNI, passaport, ...) |
|CN, Common Name |Nom, cognoms i NIF |Nom i dos cognoms d'acord amb document d'identitat (DNI / Passaport) + “ – DNI ” + NIF del treballador públic + “ (SIG)” |
|C, Country |País |C = “ES” |
|Organization Identifier ||Segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat) |

3<a name="_page26_x97.00_y736.92"></a> SerialNumber = p. ex: IDCES-00000000G. 3 caràcters per indicar el tipus de document (IDC= document nacional d'identitat, PAS=passaport, ...) + 2 caràcters per identificar el país (ÉS) + Nombre d'identitat (Printable String) ) Size [RFC 5280] 64 
Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

2. **Extensions<a name="_page27_x97.00_y113.92"></a>** 



|**Extensió** |**Crítica**|**Valors** |
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la EC, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI de acceso al servicio OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificado de la EC emisora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcSSCD 0.4.0.1862.1.4 </p><p>Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> Id-etsi- qcs-QcType 0.4.0.1862.1.6.1 </p>|
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key encipherment |
|X509v3 Extended Key Usage|- |<p>Client Authentication SmartCardLogon </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Certificate Policies |- |<p>` `<OID associat a la DPC> 1.3.6.1.4.1.15096.1.3.2.82.2 </p><p><URI de la DPC>  </p><p>User Notice: “Certificat electrònic de treballador públic de nivell alt.” <OID de la política de certificación ETSI: QCP-n-qscd> 0.4.0.194112.1.2 </p>|
|X509v3 Subject Alternative Name |- |(opcional) otherName-userPrincipalName (UPN):  Usuari en el domini Windows del posseïdor de claus |


Descripció dels perfils de Certificats ![ref2]![ref3]![ref4]![ref5]Consorci AOC  

3. **Descripció<a name="_page28_x97.00_y113.92"></a> de Perfils de Certificats de Ciutadans** 

<a name="_page28_x97.00_y143.92"></a>**3.1. Perfil dels Certificats de Ciutadà (idCAT certificat)** 

1. **Certificat<a name="_page28_x97.00_y211.92"></a>** 



|**Camp del DN ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.029.png)**|**Nom ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.030.png)**|**Descripció ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.031.png)**|
| - | - | - |
|CN, Common Name |Nom |<p>Cognoms i Nom del signant + “ - DNI “ + número del document d’identificació. </p><p>Ex: PEREZ MAS JOSE – DNI 123456789Z </p>|
|Serial Number |Número de sèrie |Número del document d'identitat del signatari, amb la semàntica proposta per la norma ETSI EN 319 412-1 |
|SN, Surname |Cognoms |Cognoms del signatari tal com apareixen en el document d'identitat utilitzat |
|GN, givenName |Nom de pila |Nom de pila del signatari, tal com apareix en el document d'identitat utilitzat |
|C, Country |País |“País d’expedició del document identificatiu del subscriptor.” |

2. **Extensions<a name="_page29_x97.00_y113.92"></a> dels certificats** 



|**Extensió ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.032.png)**|**Crítica** |**Valor ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.033.png)**|
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Key Usage |Sí |Digital Signature Non Repudiation Key Encipherment  |
|X509v3 Extended Key Usage |- |<p>TLS Web Client Authentication E-mail Protection </p><p>Adobe Authentic Documents Trust </p>|
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtinguda a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |-|<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|X509v3 Certificate Policies |- |<p><OID de la política de certificació corresponent al certificat> 1.3.6.1.4.1.15096.1.3.2.86.2 </p><p><URI de la DPC> </p><p>User Notice: “idCAT Certificat.” </p><p><OID de la política de certificació ETSI: 0.4.0.194112.1.0> (Corresponent a la política per a certificats EU qualificats emesos a persones físiques “QCP-n”, sense ús d'un DSCF) </p>|
|qcStatements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS[> ](https://www.aoc.cat/catcert/pds_en)Id-etsi- qcs-QcType-esign 0.4.0.1862.1.6.1 </p>|
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: </p><p><URI d’ accés al servei OCSP> Access Method: Id-ad-caIssuers Access Location: </p><p><URI del certificat de l’EC emissora> </p>|

4. **Descripció<a name="_page30_x97.00_y113.92"></a> dels Perfils de Certificats de Dispositius i Infraestructura** 
1. **Perfil<a name="_page30_x97.00_y163.92"></a> dels Certificats de Segell Electrònic Avançat (Segell nivell mig)** 
1. **Certificat<a name="_page30_x97.00_y229.92"></a>** 



|**Camp del DN** |**Nom** |**Descripció** |
| - | - | - |
|O, Organization |Organització |Contindrà  la  denominació  de  l'Administració  a  la  qual  pertany l'organisme. |
|Organization Identifier ||Identificador  de  la  organización  distinto  del  nombre  según  la norma técnica ETSI EN 319 412-1 (VATES + NIF de la entidad) |
|OU, Organization Unit |Unitat de l'organització |“Certificat de segell electrònic nivell mig” |
|Serial Number |CIF |CIF de l'Administració Pública, òrgan o entitat de dret públic |
|SN, Surname (Opcional) |Cognoms (persona física) |Primer  i  segon cognoms (d'acord amb el document d'identitat – DNI o NIE-) + “ - DNI ” + NIF del custodi de la clau privada |
|Given name (Opcional) |Nom (persona física) |<p>Nom, d’acord amb  el document d’identitat </p><p>(DNI, NIE) del responsable de la custòdia de la clau privada </p>|
|CN, Common Name |Denominació del sistema o aplicació |p.e. “PLATAFORMA DE VALIDACIÓ DE L’AJUNTAMENT DE xxx” |
|C, Country |País |C= ES. |

2. **Extensions<a name="_page31_x97.00_y113.92"></a> dels certificats** 



|**Extensió ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.034.png)**|**Crítica ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.035.png)**|**Valors ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.036.png)**|
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key Encipherment |
|X509v3 Extended Key Usage |- |TLS Web Client Authentication Adobe Authentic Documents Trust |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtinguda a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la EC, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI de acceso al servicio OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificado de la EC emisora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> </p><p>Id-etsi- qcs-QcType-eseal 0.4.0.1862.1.6.2 </p>|

3. **Extensions<a name="_page32_x97.00_y113.92"></a> de nivell mitjà** 



|**Extensió ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.037.png)**|**Crítica ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.038.png)**|**Valors ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.039.png)**|
| - | - | - |
|X509v3 Certificate Policies |- |<p><OID de la política de certificació corresponent al certificat> 1.3.6.1.4.1.15096.1.3.2.6.2 </p><p><URI de la DPC> </p><p>User Notice: "Certificat de segell electrònic nivell mig.” </p><p><OID associat als certificats de segell de nivell mitjà / substancial> 2.16.724.1.3.5.6.2 </p><p><OID “for EU qualified certificates issued to legal persons” segons ETSI EN 319 411-2: QCP-l> 0.4.0.194112.1.1 </p>|
|X509v3 Subject Alternative Name |- |<p>directoryName: </p><p>OID: 2.16.724.1.3.5.6.2.1 = “Certificat de segell electrònic nivell mig” OID: 2.16.724.1.3.5.6.2.2 = <O del DN> </p><p>OID: 2.16.724.1.3.5.6.2.3 = <serialNumber del DN> </p><p>OID: 2.16.724.1.3.5.6.2.4 = <NIF/NIE del custodi> </p><p>OID: 2.16.724.1.3.5.6.2.5 = <CN del DN> </p><p>OID: 2.16.724.1.3.5.6.2.6 = <Given name> </p><p>OID: 2.16.724.1.3.5.6.2.7 = <Primer cognom del custodi> (1) </p><p>OID: 2.16.724.1.3.5.6.2.8 = <Segon cognom del custodi> (2) </p><p>OID: 2.16.724.1.3.5.6.2.9 = <Correu electrònic del custodi>  </p>|



1. D'acord amb document d'identitat (DNI, NIE) 
1. D'acord amb document d'identitat (DNI, NIE) 
2. **Perfil<a name="_page33_x97.00_y113.92"></a> dels Certificats d’Aplicació (Dispositiu aplicació)** 
1. **Certificat<a name="_page33_x97.00_y141.92"></a>** 



|**Camp del DN** |**Nom** |**Descripció** |
| - | - | - |
|O, Organization |Organització |Contindrà la denominació de l'Administració a la qual pertany l'organisme |
|Organization Identifier ||Identificador de l'organització diferent del nom segons la norma tècnica ETSI EN 319 412-1 (VATES + NIF de l'entitat) |
|OU, Organization Unit |Unitat en l'organització |“Certificat d’aplicació” |
|Serial Number |CIF |CIF de l'Administració Pública, òrgan o entitat de dret públic |
|CN, Common Name |<p>Denominació del sistema </p><p>o aplicació </p>|p.e. “PLATAFORMA DE VALIDACIÓ DE L’AJUNTAMENT DE xxx” |
|C, Country |País |C= ES. |

2. **Extensions<a name="_page34_x97.00_y113.92"></a> dels certificats** 



|**Extensió ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.040.png)**|**Crítica ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.041.png)**|**Valors ![](Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.042.png)**|
| - | - | - |
|X509v3 Basic Constraints |Sí |CA:FALSE |
|X509v3 Key Usage |Sí |Digital Signature Content Commitment Key Encipherment |
|X509v3 Extended Key Usage |- |TLS Web Client Authentication Adobe Authentic Documents Trust |
|X509v3 Subject Key Identifier |- |<id de la clau pública del certificat, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Key Identifier |- |<id de la clau pública del certificat de la CA, obtingut a partir del hash de la mateixa> |
|X509v3 Authority Information Access |- |<p>Access Method: Id-ad-ocsp </p><p>Access Location: <URI d’accés al servei OCSP> Access Method: Id-ad-caIssuers </p><p>Access Location: <URI del certificat de l’EC emissora> </p>|
|X509v3 CRL Distribution Points |- |<URI de la CRL> |
|Qualified Certificate Statements |- |<p>Id-etsi- qcs-QcCompliance 0.4.0.1862.1.1 </p><p>Id-etsi- qcs-QcRetentionPeriod 0.4.0.1862.1.3: 15 anys Id-etsi- qcs-QcPDS 0.4.0.1862.1.5: <URI de la PDS> </p><p>Id-etsi- qcs-QcType-eseal 0.4.0.1862.1.6.2 </p>|
|X509v3 Certificate Policies |- |<p><OID de la política de certificació corresponent al certificat> 1.3.6.1.4.1.15096.1.3.2.91.1 </p><p><URI de la DPC> </p><p>User Notice: "Certificat d’aplicació.” </p><p>< OID “for EU qualified certificates issued to legal persons” según ETSI EN 319 411-2: QCP-l> 0.4.0.194112.1.1 </p>|


[^1]: 
[^2]: 
[^3]: 
[^4]: 
[^5]: 
[^6]: 
[^7]: 
[^8]: 
[ref1]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.004.png
[ref2]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.008.png
[ref3]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.009.png
[ref4]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.010.png
[ref5]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.011.png
[ref6]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.015.png
[ref7]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.016.png
[ref8]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.017.png
[ref9]: Aspose.Words.dd63d74e-179f-4e14-b6a5-596842fab5ce.018.png
