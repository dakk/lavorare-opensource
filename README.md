# Come trasformare l'open-source in un lavoro
*Una guida pratica per sviluppatori squattrinati*

In questa guida verranno illustrati alcuni dei metodi e tecniche utilizzabili per venire pagati lavorando con l'open-source; i metodi sono stati elencati in ordine crescente a seconda di quanto è possibile guadagnare con ogni metodo. Ogni categoria inoltre, contiene dei link ad esempi reali con relativi link ad articoli utili piuttosto che a semplici homepage di progetti (dove è stato possibile).

Le categorie non si escludono mutualmente: per esempio, un progetto potrebbe avere una fondazione ed utilizzare una raccolta per ottenere fondi. Altri potrebbero fare consulenze ed allo stesso tempo avere un bottone di donazione e così via. L'obbiettivo di questa guida è fornire una lista esaustiva di tutti i metodi per ottenere fondi, in modo che ognuno possa individuare il migliore per il proprio progetto.

---

# Sommario dei contenuti
1. [Pulsante di donazione](#pulsante-di-donazione)
2. [Bounty](#bounty)
3. [Raccolta fondi iniziale](#raccolta-fondi-iniziale)
4. [Raccolta fondi ricorrente](#raccolta-fondi-ricorrente)
5. [Libri e merchandise](#libri-e-merchandise)
6. [Pubblicità e sponsorizzazioni](#pubblicità-e-sponsorizzazioni)
7. [Farti assumere da un'azienda per lavorare al progetto](#farti-assumere-da-un-azienda-per-lavorare-al-progetto)
8. [Iniziare un progetto mentre si è assunti in un'azienda](#iniziare-un-progetto-mentre-si-è-assunti-in-un-azienda)
9. [Grant](#grant)
10. [Consulenza e servizi](#consulenza-e-servizi)
11. [SaaS](#saas)
12. [Licenza freemium](#licenza-freemium)
13. [Doppia licenza](#doppia-licenza)
14. [Open core](#open-core)
15. [Fondazioni e consorzi](#fondazioni-e-consorzi)
16. [Venture capital](#venture-capital)

Appendice: [Contribuire alla guida](#contribuire-a-questa-guida) // [Licenza e attribuzione](#licenza-e-attribuzione)

Traduzioni: [Chinese (中文版)](https://github.com/wizicer/FinancialSupportForopen-source) // [Inglese (english)](https://github.com/nayafia/lemonade-stand)

**le note "sforzo personale" si riferiscono ad esempi di finanziamento dove è stato interessato un singolo utente


## Pulsante di donazione
Il metodo sicuramente più classico, è l'inserimento di un pulsante di donazione nel sito del progetto. Esistono alcuni servizi che ti permettono di aggiungere un pulsante di donazione in modo rapido e semplice, come ad esempio Stripe e PayPal. Un'altra possibilità è accettare donazioni tramite criptomonete come Bitcoin o Ethereum, in tal caso basta inserire l'immagine del QR code del proprio wallet.


#### Vantaggi
* Comporta poco sforzo per l'integrazione
* Il processo di integrazione del pulsante è da svolgere una sola volta

#### Svantaggi
* Solitamente i donatori sono pochi e donano poco, a meno che non venga dedicato del tempo a promuovere la raccolta fornendo dei vantaggi concreti ai donatori
* Necessita di una terza parte per accettare le donazioni, questo comporta la presenza di una percentuale trattenuta su ogni donazione. Questo non è però vero in caso di donazioni tramite criptomonete.
* Per ottenere donazioni senza che il donatore venga tassato, in alcuni stati è necessario avere un'organizzazione no-profit per accettare donazioni, difficilmente gestibili da singole persone. E' però possibile appoggiarsi ad entità già formate come [SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com), e [NumFOCUS](http://www.numfocus.org).
* Molte volte non è chiaro chi merita i soldi raccolti con le donazioni o come verranno distribuiti tra gli sviluppatori del progetto. Un servizio come [OpenCollective](http://opencollective.com) potrebbe aiutare a mitigare questo fatto.

#### Casi di studio
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)



## Bounty
Tavolta, progetti e aziende pubblicano dei cosidetti "bounty" per svolgere del lavoro su un progetto open-source (per esempio "risolvi il bug ed ottieni 100€", oppure "implementa questa feature e ricevi 400€"). Ci sono vari servizi, alcuni elencati più avanti, che facilitano l'inserimento e la ricerca di bounty.

#### Vantaggi
* Apre alla partecipazione l'intera community
* Il denaro è destinato al adempimento di uno specifico task (più simile ad un pagamento che ad una donazione)
* Molto popolare per i task relativi alla sicurezza

#### Svantaggi
* Potrebbe creare meccanismi perversi nel progetto; per esempio codice di bassa qualità per ricevere il bounty in breve tempo e distrazione dalle priorità del progetto
* Solitamente il compenso per un bounty non è molto alto (<=500€)
* Non fornisce un entrata costante

#### Casi di studio
* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)



## Raccolta fondi iniziale
Se hai un'idea specifica che ti piacerebbe implementare (piuttosto che un progetto già avviato), una campagna di raccolta fondi iniziale può aiutare a raccimolare il denaro necessario per finanziare lo sviluppo. Sia singoli utenti che aziende potrebbero essere interessate a donare per la tua campagna, in quanto interessati al software che andrai a sviluppare.

#### Vantaggi
* Lo sforzo per integrare la raccolta e per pubblicizzarla è da svolgere una sola volta
* Può essere semplice da gestire (legalmente) tramite servizi come [Kickstarter](https://kickstarter.com/)

#### Svantaggi
* Molto lavoro necessario per curare la campagna di raccolta
* I donatori si aspettano solitamente un risultato concreto dalla raccolta fondi, e quindi dei vantaggi
* Solitamente non raccolgono una quantità sigificativa di fondi (~50.000€)
* Le aziende spesso non sono a loro agio nel donare in una raccolta fondi

#### Casi di studio
* [Michal Papis + Rvm (sforzo personale)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (sforzo personale)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (sforzo personale)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://poststatus.com/kickstarter-open-source-project/)



## Raccolta fondi ricorrente
Se necessiti di un finanziamento per un progetto in corso, puoi creare una raccolta fondi ricorrente nel tempo, con cadenza mensile o annuale. Coloro che utilizzano il tuo progetto regolarmente (sia singoli che aziende) potrebbero essere interessati a finanziare il tuo lavoro periodicamente per aiutarlo a crescere.

#### Vantaggi
* Lo sforzo per integrare il sistema di raccolta è da svolgere una sola volta
* Può essere semplice da gestire (legalmente) tramite servizi come [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/) e [OpenCollective](https://opencollective.com)

#### Svantaggi
* Difficile trovare utenti disposti a donare per più di una volta (è necessario che il progetto sia già popolare ed utilizzato)
* I donatori si aspettano solitamente un risultato concreto dalla raccolta fondi, e quindi dei vantaggi; nelle raccolte ricorrenti questo aspetto è più accentuato
* Solitamente non raccolgono una quantità sigificativa di fondi (~1.000€-4.000€ mensili)
* Le aziende spesso non sono a loro agio nel donare in una raccolta fondi

#### Casi di studio
* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (sforzo personale)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)



## Libri e merchandise
Se sei un esperto in un determinato settore che altre persone reputano interessante o del quale vogliono acquisire maggiori conoscenze, puoi scrivere e vendere un libro o una serie di libri a riguardo. Per la pubblicazione, è possibile trovare un editore (come O'Reilly per esempio) oppure pubblicarlo autonomamente (anche utilizzando servizi di self-publishing come [Amazon KDP](https://kdp.amazon.com/). 

Oltre ai libri, alcuni progetti vendono anche merchandise (come magliette, portachiavi, adesivi, cd) per supportare il loro lavoro.

#### Vantaggi
* Il guadagno non deriva dal lavoro sul progetto, quindi hai una certa libertà creativa sul progetto stesso
* Può servire come metodo di marketing per pubblicizzare il progetto
* Può essere una fonte di guadagno ricorrente

#### Svantaggi
* Spesso non sono una fonte di fondi significativa
* Può distrarre dallo sviluppo del progetto
* Il merchandise può avere dei costi da anticipare

#### Casi di studio
* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (sforzo personale)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (sforzo personale)](http://www.poodr.com/)
* [Kyle Simpson + You Don't Know JS (sforzo personale)](https://github.com/getify/You-Dont-Know-JS)
* [CocoaPods (fundraising for charity)](https://cocoapods.org/socks)



## Pubblicità e sponsorizzazioni
Se il tuo progetto ha un vasto numero di utenti, puoi vendere delle sponsorizzazioni e affittare spazi pubblicitari alle aziende che sono interessate alla tipologia di utenti che utilizzano il tuo progetto. Il tuo progetto probabilmente avrà un pubblico dagli interessi ben definiti (per esempio in un progetto Python, puoi assumere che i tuoi utenti sono familiari con Python), quindi puoi utilizzare questa caratteristica a tuo vantaggio.


#### Vantaggi
* Nessuna influenza esterna sul progetto; i potenziali clienti per la sponsorizzazione sono già il linea con la tipologia di utenti attirati dal tuo progetto

#### Svantaggi
* E' necessario un gran numero di utenti per giustificare una sponsorizzazione
* Bisogna mantenere la fiducia e la trasparenza (per esempio, evitare di tracciare gli utenti)
* Può essere molto dispendioso in termini di tempo trovare nuovi clienti

#### Casi di studio
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)



## Farti assumere da un'azienda per lavorare al progetto
Le aziende a volte assumono nuovi dipendenti con lo scopo di farli lavorare allo sviluppo di software open-source. Puoi quindi trovare un'azienda che usa un progetto al quale vorresti lavorare e proporti come sviluppatore. 

A questa tipologia di dipendenti viene spesso proposto un contratto che prevede, per esempio, il 50% di lavoro per l'azienda ed il 50% di lavoro al progetto open-source. 

Alternativamente, se hai un'idea per un nuovo progetto, puoi trovare un'azienda che potrebbe essere interessata nell'utilizzarlo: in questi casi, avere dell'esperienza dimostrata nel campo dello sviluppo open-source può essere molto utile come referenza.


#### Vantaggi
* Vieni pagato direttamente da chi ha già dei soldi destinati per questo tipo di attività
* Lavorerai ad un progetto già in linea con le esigenze dell'azienda
* Entrate costanti

#### Svantaggi
* Bisogna essere fortunati e fare molti tentativi: non esiste un modo prestabilito per attuare questo tipo di soluzione
* Il progetto deve essere già conosciuto ed usato
* Un dipendente che lavora ad un progetto open-source non contribuisce direttamente al profitto dell'azienda, quindi questo tipo di dipendenti saranno potenzialmente i primi ad essere sacrificati in caso di riallineamento del bilancio aziendale
* Problemi di governance, l'azienda potrebbe influenzare le direzioni del progetto

#### Casi di studio
* [Donald Stufft + Hewlett-Packard and Python packaging (sforzo personale)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (sforzo personale)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (sforzo personale)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)



## Iniziare un progetto mentre si è assunti in un'azienda
Molti progetti open-source iniziano come side-project di un dipendente di un'azienda. Il progetto può poi svilupparsi anche al di fuori dell'azienda, ma iniziarlo come side-project è un ottimo modo per incubare ed iniziare nuove idee.

Se vuoi seguire questa strada, assicurati di aver capito le politiche dell'azienda riguardo la produzione di software open-source. Alcune aziende incoraggiano i dipendenti a contribuire all'open-source durante le ore lavorative, mentre altre potrebbero trattare il tuo lavoro open-source come un prodotto dell'azienda. Non dare nulla per scontato, chiedi ai tuoi datori di lavori prima di iniziare.

#### Vantaggi
* Libertà di dedicarsi a nuove idee senza la preoccupazione del salario
* Il progetto sarà già ben allineato con le necesità dell'azienda
* Ideale per nuove idee e sperimentazioni

#### Svantaggi
* Necessità di iniziare il lavoro come side-project e di essere approvato come lavoro durante le ore stipendiate
* Rischio di influenza sul progetto da parte della società
* Può portare a complicanze nella governance del progetto col passare del tempo

#### Casi di studio
* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open-source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)



## Grant
I Grant sono grosse donazioni che non richiedono una restituzione. Spesso chi emana i grant riceve altri benefici, come per esempio delle richieste di feature da integrare, un report del lavoro svolto o benefici riguardanti le tasse.

I grant possono arrivare da diverse fonti, incluse aziende, fondazioni software, fondazioni filantropiche o dal governo. L'aspetto tecnico e legale di un grant varia a seconda della fonte: per esempio, un'azienda potrebbe darti un grant ma trattarlo legalmente come una fattura di consulenza. Una fondazione filantropica può inviare grant solo a no-profit, quindi dovresti avere una no-profit anche tu, o (più comunemente) trovare una no-profit che ti sponsorizzi. 

Se non sei familiare coi grant, il miglior modo per capire come funzionano è parlare con qualcuno che ne ha ricevuto uno. Alcuni esempi di progetti che hanno ricevuto un grant li puoi trovare più avanti.

#### Vantaggi
* Dei fondi garantiti possono aiutarti a focalizzarti nel progetto per un certo periodo di tempo
* Da al progetto un certo periodo di tranquillità nel fronte economico e la possibilità di sperimentare

#### Svantaggi
* Non esistono molti donatori di grant per progetti relativi a software 
* I grant finiscono; devi comunque trovare un modo per sostenerti anche dopo aver terminato i soldi del grant

#### Casi di studio
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla open-source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)



## Consulenza e servizi
La consulenza è un ottimo modo per ricevere fondi per un progetto open-source. Hai più libertà nella gestione del tempo (per esempio, consulenze per 30 ore alla settimana e 10 ore per lo sviluppo). I consulenti sono pagati solitamente di più rispetto ad un dipendente salariato in quanto il loro lavoro è meno costante, non ricevono benefici, ecc. Se hai pianificato di fare questo tipo di attività regolarmente, può essere necessario essere titolari di partita IVA o istituire una SRL.

Se il tuo progetto è popolare, puoi anche offrire consulenza e servizi riguardanti il progetto stesso. Per esempio, un cliente potrebbe pagarti per implementare nuove feature per loro conto, modificare feature esistenti, o istruirli riguardo l'utilizzo del software.

#### Vantaggi
* Le aziende sono spesso disposte a pagare per attività di consulenza

#### Svantaggi
* Le consulenze richiedono tempo e risorse umane, è difficile scalare questo approccio
* Le necessità del business possono distrarre dalla scrittura del codice e da altre attività legate al progetto
* Può essere in contrasto con la realizzazione di un software semplice da utilizzare
* Per essere disposti a pagare per servizi correlati ad esso, il progetto necessità di avere sufficiente popolarità

#### Casi di studio
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)



## SaaS
SaaS è l'acronimo di [Software as a Service](https://en.wikipedia.org/wiki/Software_as_a_service). In questo modello, il codice principale è open-source, ma puoi offrire servizi aggiuntivi a pagamento che permettono ad altre persone di utilizzare il tuo progetto con facilità. Un esempio di servizio a pagamento potrebbe essere far pagare per l'hosting.

#### Vantaggi
* Può contribuire a creare una community di utilizzatori del tuo progetto
* Permette di focalizzarsi sui singoli utenti e col tempo, facilita l'adozione da parte di aziende
* Può scalare a seconda del numero di utenti

#### Svantaggi
* Se si sceglie la strada dell'hosting come servizio, i costi di hosting devono almeno essere inferiori rispetto al costo offerto agli utenti

#### Casi di studio
* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [GitLab](https://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)



## Licenze freemium
Le licenze "Freemium" non sono open-source, in quanto non offrono contemporaneamente tutte le [libertà richieste](https://en.wikipedia.org/wiki/The_Open_Source_Definition) da una licenza open-source (per esempio, il codice sorgente non è allo stesso tempo visibile liberamente e disponibile per la redistribuzione e modifica). 

Una licenza freemium restringe alcune libertà dell'open-source; per esempio il codice potrebbe essere visibile, ma viene richiesta una licenza commerciale per utilizzarlo.

#### Vantaggi
* Vieni pagato direttamente da chi ha necessità ad usare un prodotto come quello che offri
* Alto potenziale di scalabilità
* Adatto per prodotti end-user

#### Svantaggi
* Non propriamente definibile open-source
* Ancora un area in esplorazione (correlato al movimento [shareware](https://en.wikipedia.org/wiki/Shareware)) e non ancora ben collaudato

#### Casi di studio
* [Fair Source](https://fair.io/), used by [Sourcegraph](https://sourcegraph.com/)
* [BSL (Business Source License)](https://mariadb.com/bsl-faq-adopting), used by [MariaDB](https://mariadb.com/)



## Doppia license
A volte, un progetto può offrire lo stesso codice con due differenti licenze: una licenza commerciale ed una open-source (per esempio GPL). La seconda è gratuita per chiunque, ma le aziende pagano la prima per stare tranquille legalmente.

#### Vantaggi
* Vieni pagato direttamente da chi ha necessità ad usare il tuo progetto
* Alto potenziale di scalabilità

#### Svantaggi
* Può essere un impedimento per la diffusione del progetto tra utenti che non se lo possono permettere
* Il progetto deve essere abbastanza grande in modo da motivare la sua esistenza ed il pagamento di una licenza commerciale


#### Casi di studio
* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)



## Open core (Nucleo aperto)
In un modello [open core](https://en.wikipedia.org/wiki/Open_core), alcune parti del progetto sono open-source e gratuite, mentre altre funzionalità sono proprietarie e disponibili solo per utenti paganti. Solitamente questo modello funziona quando c'è una richiesta di funzionalità enterprise del prodotto.

#### Vantaggi
* Vieni pagato direttamente da chi ha necessità ad usare il tuo progetto e le sue funzionalità avanzate
* Alto potenziale di scalabilità

#### Svantaggi
* Il progetto deve possedere delle funzionalità che possono essere rese a pagamento (quindi avere delle funzionalità esclusive per le quali qualcuno pagherebbe)
* Può essere un impedimento per la diffusione del progetto tra utenti che non se lo possono permettere
* Alcuni utenti potrebbero non essere contenti di questa tua scelta a due livelli

#### Casi di studio
* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)



## Fondazioni e consorzi
Una [fondazione](https://it.wikipedia.org/wiki/Fondazione_(ente)) è un entità legale che può accettare o emanare donazioni. Dato che il suo scopo primario non è fare profitto, possono essere un ottima scelta per guidare un progetto in modo neutrale. In Italia, le fondazioni vengono classificate come organizzazioni non a scopo di lucro (anche note come no-profit).

#### Vantaggi
* Neutralità: le fondazioni proteggono il codice ed aiutano lo svilupo della comunità attorno al software
* L'influenza sul progetto è distribuita tra più donatori
* Può legittimare un progetto, nel senso che le aziende solitamente sono più a loro agio nel donare ad una fondazione piuttosto che ad un gruppo di individui non legalmente definito

#### Svantaggi
* Vale la pena solo per grossi progetti
* Spese legali e di gestione, il processo di costituzione può prendere molto tempo
* Limitazioni definite dalla legge
* Richiede un contributo cospicuo della community e la presenza di diverse figure (per esempio legali e commerciali)

#### Casi di studio
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)


## Venture capital
I Venture capital sono un metodo di finanziamento per business a crescita rapida. Al contrario di prestiti bancari o ad altre forme di finanziamento tramite debito, i venture capital acquisiscono una equity (una quota percentuale di possesso del business) in cambio di un finanziamento. Il vantaggio rispetto ad un prestito è che nel caso di fallimento del progetto non devi ripagare un debito con qualcuno. Se invece il progetto ha successo, devi aspettarti di rendere il capitale investito dai VC ad un multiplo.

I Venture capital sono fanno investimento ad "alto rischio" per una possibilità di un "alto profitto": sono quindi più tolleranti al rischio rispetto ad una banca, ma si aspettano un grande guadagno nel caso che il business abbia successo. Se pianifichi di ottenere dei fondi da un venture capital, è necessario creare una società legalmente riconosciuta: in Italia può essere una SRL. Se non sei familiare con il processo dei venture capital, il modo migliore per iniziare è contattare altri come te che hanno già ottenuto dei fondi da un venture.

#### Vantaggi
* Il supporto di un Venture capital può essere di aiuto per la creazione di un business
* Grande quantità di capitale disponibile

#### Svantaggi
* I Venture capital finanziano i progetti nella prospettiva di una futura exit (ovvero la vendita delle proprie quote per un valore superiore all'investimento iniziale). L'esperienza suggerisce che questo è difficilmente attuabile con i business basati sull'open-source
* I Venture capital possono cambiare prospettiva, distraendo lo sviluppo dalle priorità reali

#### Casi di studio
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)


---


### Contribuire alla guida
Chiunque voglia contribuire a questa guida con ulteriori integrazioni, modifiche, nuove categorie e suggerimenti, può farlo tramite una pull-request o inserendo una issue nel repository. I vantaggi e svantaggi descritti sono soggettivi, dunque rispecchiano il punto di vista dell'autore e di coloro che hanno apportato delle modifiche.



### Licenza e attribuzione
Questa guida è disponibile sotto licenza "Creative Commons CC-BY 3.0 License", sei libero di usarla per qualsiasi scopo, commerciale e non commerciale, con il solo obbligo di citare l'autore originale. 

La guida è stata realizzata da Davide Gessa ([@dakk](http://github.com/dakk), [mail](mailto:gessadavide@gmail.com)). Il documento si basa su un progetto in lingua inglese denominato [lemonade-stand](https://github.com/nayafia/lemonade-stand).


### Donazioni
Chi vuole può fare una donazione tramite Bitcoin all'indirizzo: 13gbybVyaYy5yA7Z7si2zJfo2Aat6d7c8z

![Donation QR code](https://raw.githubusercontent.com/dakk/lavorare-opensource/master/media/donateqr.png)


