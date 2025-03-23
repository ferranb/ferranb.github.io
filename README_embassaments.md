# Embassaments de Catalunya

La informació dels embassaments de Catalunya està disponible ens aquestes xarxes socials:

- Bluesky:
  - https://bsky.app/profile/embassamentscat.bsky.social
  - Cada hora dia i nit.
- Twitter:
  - https://x.com/Embassamentscat
  - Cada hora entre les 8:00 i les 23:00 inclosses. Això és degut a la límitació de l'API de twitter que limita el número de piulades per dia. 
- Instagram:
  - https://www.instagram.com/embassaments
  - Cada dues hores dia i nit. Això es degut a que només el publiquen les imatges gràfiques.

Les dades s'obtenen de l'API de dades obertes de l'[Agència Catalana de l'Aigua (ACA)](https://aca.gencat.cat/ca/inici/index.html) i es publiquen automàticament a les xarxes socials anteriors ambn criteris diferents.També es publiquen alguns tuits manualment de manera puntual. 

La primera dada automàtitzada es va publicar el [22 de Maig del 2024](https://x.com/Embassamentscat/status/1793296839057301744).

# [Dades obertes](#dadesobertes)

Informe diari de l'estat dels embassaments:

- [Estat dels embassaments](https://aca.gencat.cat/ca/laigua/estat-del-medi-hidric/recursos-disponibles/estat-de-les-reserves-daigua-als-embassaments/). Aquí hi ha la xifra oficial de l'ACA de l'estat actual dels embassaments. Es publica cada dia per voltants de les 12 i es pot veure el detall a l'[Informe diari de l'estat de tots els embassaments a tot catalunya](https://info.aca.gencat.cat/ca/aca/informacio/informesdwh/dades_embassaments_ca.pdf).

Eines visuals amb dades a temps real:
  - [Dades a temps real de l'ACA](http://aca-web.gencat.cat/sdim2/visor/) amb la plataforma ([Sentilo](https://www.sentilo.io/)).
  - [Eina visual de l'ACA sobre l'estat dels embassaments](https://aca.gencat.cat/ca/laigua/consulta-de-dades/dades-obertes/visualitzacio-interactiva-dades/estat-embassaments/).
  - [Un altre visor](https://aplicacions.aca.gencat.cat/aetr/vishid/#ara).

Dades obertes per us d'aplicacions o analístes de dades:

- [Dades obertes a temps real](https://aca.gencat.cat/ca/laigua/consulta-de-dades/dades-obertes/dades-obertes-temps-real/) on trobareu els enllaços i també el [Manual d’ús del servei API-REST de l'ACA](https://aca.gencat.cat/web/.content/20_Aigua/08_consulta_de_dades/01_dades_obertes/02_dades_obertes_a_temps_real/us_serveis_dades_API_REST.pdf).
- [Catàleg de dades obertes](https://aca.gencat.cat/ca/laigua/consulta-de-dades/dades-obertes/cataleg-dades-obertes/).
- [Quantitat d’aigua als embassaments de les Conques Internes de Catalunya](https://analisi.transparenciacatalunya.cat/Medi-Ambient/Quantitat-d-aigua-als-embassaments-de-les-Conques-/gn9e-3qhr/about_data). Dades obertes dels embassaments de conques internes. La granularitat és diària.
- Pels més curiosos, les crides a l'API (Application Programming Interface) que es fan servir per actualitzar les dades que es publiquen:
  - [Catàleg de sensors](http://aca-web.gencat.cat/sdim2/apirest/catalog?componentType=embassament).
  - [Crida a les darreres dades dels sensors](http://aca-web.gencat.cat/sdim2/apirest/data/EMBASSAMENT-EST).

Altres enllaços:
- [Preses i embassaments de Catalunya](https://aca.gencat.cat/ca/laigua/infraestructures/preses-i-embassaments).
- [Informació hidrològica de l'Ebre](https://www.saihebro.com/homepage/estado-cuenca-ebro).
- [Informació d'embassaments del Departament d'Agricultura Ramaderia i Alimentació](https://agricultura.gencat.cat/ca/ambits/desenvolupament-rural/infraestructures-agraries/dar_regadius/estat-embassaments-catalunya/index.html).

# [Preguntes frequents](#preguntesfrequents)

**¿Per què només es publiquen dades de les conques internes?**

És una qüestió de dades obertes. Ara mateix les dades són de l'API de l'ACA que només té les conques internes. Quan tingui temps miro de posar la resta :-)

**¿Per què hi ha tanta diferència entre el percentatge total plublicat i les dades que publica l'ACA a la pàgina d'estat dels embassamnets?**

La dada que surt a [Estat dels embassaments](https://aca.gencat.cat/ca/laigua/estat-del-medi-hidric/recursos-disponibles/estat-de-les-reserves-daigua-als-embassaments/) és d'una actualització diària per voltants de les 12:00 però no són dades de les 12:00 sinó anterior. Les dades que publiquem són dades a temps real que també publica l'ACA.

**¿Per què tal embassament té més d'un 100%?**

Per cada embassament, s'estableix un volum màxim indicat per l'ACA. Quan una xifa supera el 100% és perquè el volum actual és superior a aquest valor. En alguns casos vol dir que pot estar sobreexint.

**¿Per què tal embassament està buit si tal altre està ple o tal riu no se què?**

No ho sé. Això s'ha de preguntar a l'[ACA](https://x.com/aigua_cat) directament ;-)

**¿Com pot ser que si ha plogut tant, tal embassament estigui buit?**

Perquè a més de ploure, ha de ploure bé. En concret, pels embassaments de conques internes ha de ploure on indica aquest mapa que va [publicar l'ACA]([https://x.com/Embassamentscat/](https://x.com/aigua_cat/status/1662007831199989760) en el seu dia

**¿Què volen dir les fases?**

En [aquesta pàgina](https://sequera.gencat.cat/ca/accions/el-semafor-de-la-sequera/index.html) de l'ACA s'expliquen els criteris.

**¿Per què no es publiquen les dades de capacitat màxima dels embassaments?**

Perquè un tuit té un limit de caràcters. Pels curiosos [aquí|https://x.com/Embassamentscat/status/1901755055088279741] hi ha les dades.

**¿Per què el radar no marca i si que està plovent?**

[Aquí](https://x.com/meteocat/status/1892876743951675486) ho expliquen molt bé els del meteocat.

**¿Ja em puc dutxar?**

I tant. Quan abans, millor, sisplau!
