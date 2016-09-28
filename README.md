# Guida pratica per venire pagati con l'open source.
*"Lavoro con l'open source, come posso venire pagato?"*

In questa guida verranno illustrati tutti i metodi che conosco per venire pagati per i propri lavori open source, grezzamente ordinati dal più piccolo al più grande. Ogni categoria contiene dei link ad esempi reali. (Dove possibile, ho provato a linkare ad articoli utili o pagine invece che a semplici homepage.).

Le categorie non si escludono mutualmente. Per esempio, un progetto potrebbe avere una fondazione ma comunque utilizzare il crowdfunding per ottenere fondi. Altri potrebbero fare consulenze ed allo stesso tempo avere un bottone di donazione e così via. L'obbiettivo di questa guida è fornire una lista esaustiva di tutti i metodi per ottenere fondi, in modo che ognuno possa individuare il migliore per il proprio progetto.

---


# Sommario dei contenuti
1. [Pulsante di donazione](#donation-button)
2. [Bounties](#bounties)
3. [Crowdfunding (una volta)](#crowdfunding-one-time)
4. [Crowdfunding (ricorrente)](#crowdfunding-recurring)
5. [Libri e merchandise](#books-and-merchandise)
6. [Pubblicità & sponsorizzazioni](#advertising--sponsorships)
7. [Farti assumere da un'azienda per lavorare al progetto](#get-hired-by-a-company-to-work-on-project)
8. [Iniziare un progetto mentre si è assunti in un'azienda](#start-a-project-while-currently-employed)
9. [Grant](#grants)
10. [Consulenza & servizi](#Svantaggiulting--services)
11. [SaaS](#saas)
12. [Licenza freemium](#freemium-license)
13. [Doppia licenza](#dual-license)
14. [Open core](#open-core)
15. [Fondazioni & consorzi](#foundations--consortiums)
16. [Venture capital](#venture-capital)

APPENDICE: [Contribuire a questa guida](#contributing-to-this-guide) // [Licenza & attribuzione](#license-and-attribution)  
TRADUZIONI: [Chinese(中文版)](https://github.com/wizicer/FinancialSupportForOpenSource // [Inglese(english)](https://github.com/nayafia/lemonade-stand)

**le note "sforzo personale" when a funding effort was led by an individual, not a project*

##Pulsante di donazione
*Inserisci un pulsante di donazione nel tuo sito. Stripe e PayPal sono alcuni esempi di servizi che ti permettono di accettare donazioni.*

####Vantaggi
* Poche righe di codice necessarie
* Comporta poco sforzo ed una sola volta

####Svantaggi
* Solitamente non raccimolano molti soldi, a meno che non venga dedicato del tempo a promuovere la raccolta
* Necessita di una terza parte per accettare le donazioni, questo comporta la presenza di fee sulle donazioni. Esempi sono Stripe e PayPal
* Per ottenere donazioni senza che il donatore venga tassato, in alcuni stati è necessario avere un'organizzazione no-profit per accettare donazioni, difficilmente gestibili da singole persone. [SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com), e [NumFOCUS](http://www.numfocus.org) sono alcuni esempi.
* Molte volte non è chiaro chi merita i soldi raccolti con le donazioni o come verranno distribuiti tra gli sviluppatori del progetto. Un servizio come [OpenCollective](http://opencollective.com) potrebbe aiutare a mitigare questo fatto.

####Casi di studio
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)

##Bounties
*Sometimes, projects or companies post bounties for open source work (ex. "fix this bug and collect $100"). There are several websites, listed below, that help facilitate the posting and collection of bounties.*

####Vantaggi
* Open to community participation
* Money is tied to doing specific work (more like paying for service than donations)
* Especially popular for security work

####Svantaggi
* Can create perverse incentives in a project (low quality PRs, distracting priorities)
* Usually not much money per bounty (~<$500)
* Doesn’t provide recurring revenue

####Casi di studio
* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)

##Crowdfunding (one-time)
*If you have a specific idea you'd like to implement (rather than ongoing project work), a one-time crowdfunding campaign can help raise the funds you need. Both individuals and companies might be willing to donate to your campaign.*

####Vantaggi
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Kickstarter](https://kickstarter.com/)

####Svantaggi
* Lots of work involved to market campaign
* Usually has to be tied to concrete outcome, perks
* Usually not that much money (~$50K for one time)
* Companies not always comfortable donating to campaigns

####Casi di studio
* [Michal Papis + Rvm (sforzo personale)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (sforzo personale)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (sforzo personale)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://poststatus.com/kickstarter-open-source-project/)

##Crowdfunding (recurring)
*If you'd like to fund ongoing project work, you can set up a recurring crowdfunding campaign, with a monthly or annual financial commitment that renews indefinitely (or until the donor cancels). Those who use your project regularly (including both individuals and companies) might be willing to fund your work.*

####Vantaggi
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/), [OpenCollective](https://opencollective.com)

####Svantaggi
* Harder to get commitments to recurring donations (often requires preexisting brand/reputation)
* Harder to explain concrete outcomes, perks that come with recurring donations
* Usually not that much money (~$1-4K monthly)
* Companies not always comfortable donating to campaigns

####Casi di studio
* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (sforzo personale)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)

##Books and merchandise
*If you are an expert in a domain that other people might find useful to learn about, you could write and sell a book or series of books. You can find a publisher (like O'Reilly) or self-publish. In addition to selling books, some projects sell merchandise (ex. shirts, hoodies) to support their work.*

####Vantaggi
* Outcome not tied to project work itself, so you retain creative freedom
* Can serve as marketing for the project itself
* Can be recurring source of revenue after initial development

####Svantaggi
* Often not a significant source of revenue
* Can distract from core development of project
* Merchandise can have upfront costs

####Casi di studio
* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (sforzo personale)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (sforzo personale)](http://www.poodr.com/)
* [Kyle Simpson + You Don't Know JS (sforzo personale)](https://github.com/getify/You-Dont-Know-JS)
* [CocoaPods (fundraising for charity)](https://cocoapods.org/socks)

##Advertising & sponsorships
*If your project has a large audience, you can sell sponsorships to advertisers who might want to reach them. You probably have a very targeted audience (ex. if you have a Python project, you can assume your audience is likely people who are technically familiar with Python), so use that to your advantage.*

####Vantaggi
* Business model aligned with something people are willing to pay for

####Svantaggi
* Need large enough audience to justify sponsorships
* Need to manage trust and transparency with user base (ex. no tracking)
* Can be a lot of work to find and manage clients

####Casi di studio
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)

##Get hired by a company to work on project
*Companies sometimes hire individuals to do open source work. Find a company that uses the project you want to work on. Often this is a split arrangement (ex. 50% company work, 50% open source work). Alternatively, if you have an idea for a new project, find a company that would be interested in using what you produce. In these situations, having demonstrated experience you can point to will be very helpful.*

####Vantaggi
* Taps into those who have resources (i.e. companies)
* Can be well-aligned with company needs
* Steady income

####Svantaggi
* Usually involves “getting lucky”: no clear, repeatable path to finding this arrangement
* Project already needs to be well-known and used
* Person not contributing to company’s bottom line, which makes them expendable
* Governance issues, company could have undue influence over project
* Can affect project dynamics + balance

####Casi di studio
* [Donald Stufft + Hewlett-Packard and Python packaging (sforzo personale)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (sforzo personale)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (sforzo personale)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

##Start a project while currently employed
*Many open source projects started as employee side projects. The project might eventually outgrow the company, but starting it as a side project can be a great way to incubate the idea.*

*If you pursue this path, make sure you understand your company's policy on open source work. Some companies encourage employees to contribute to open source during working hours. Some might treat your open source work as a company project. Don't assume anything; ask someone at your company before starting.*

####Vantaggi
* Freedom to test new ideas without worrying about salary
* Can be well-aligned with company needs
* Suitable for newer, experimental ideas

####Svantaggi
* Need to do it as a side project or be approved to work on it during salaried time
* Risk of undue company influence
* Can lead to complicated governance later down the line

####Casi di studio
* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)

##Grants
*Grants are effectively large donations that do not require repayment. Oftentimes the grantmaker receives other benefits from giving you the grant, such as access to you, demonstration of impact, a report of your work, or tax benefits.*

*Grants can come from many places, including companies, software foundations, philanthropic foundations, and the government. The technical and legal aspects of a grant vary greatly depending on where it comes from. For example, a company might give you a "grant" but legally treat it as a consulting invoice. A philanthropic foundation can only make grants to nonprofits, so you would need to be a nonprofit yourself, or (more commonly) find a nonprofit to sponsor you. If you're unfamiliar with grants, the best way to understand how grants work is to talk to someone who has received one before. Some examples of grant recipients are listed below.*

####Vantaggi
* Fewer strings attached
* Guaranteed money can help project focus for an unbroken period of time
* Gives project room to breathe and experiment

####Svantaggi
* There aren’t many software-related grantmakers (philanthropic, gov’t, corporate)
* Grants are finite. Still need to find sustainability beyond the life of a grant

####Casi di studio
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)

##Svantaggiulting & services
*Consulting can be a flexible way to fund open source work. You have more freedom to structure your time as you wish (for example, consulting 30 hrs of the week and spending 10 hrs of the week on open source work). Consultants can usually charge more for their time than salaried employees because the work is less steady, they don't receive benefits, etc. If you plan on doing this type of work regularly, you will probably want to set up an LLC (or equivalent outside of the US).*

*If your project is popular, you can also offer consulting & services around the project itself. For example, a client might pay you to implement the project for them, build something custom, or train them on how to use it.*

####Vantaggi
* Business model aligned with something people are willing to pay for

####Svantaggi
* Consulting requires human power, doesn’t scale well (except for rare outliers)
* Business needs can distract from writing code or other tasks related to the project itself
* Can be at odds with making software simple to use
* Project needs to be sufficiently popular that people are willing to pay for related services

####Casi di studio
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

##SaaS
*SaaS means [Software as a Service](https://en.wikipedia.org/wiki/Software_as_a_service). In this model, the codebase itself is open source, but you might offer additional paid services that make it easier for people to use your project. One common example of a paid service is charging for hosting.*

####Vantaggi
* Can build community around open project and make money off of services for hosting
* Allows open source project to focus on users and as needs grow to help enterprises adopt the project
* Can scale by number of users

####Svantaggi
* Often means the hosting needs to be cheaper than hiring a dev to run the project for you.
* “Two tiers” of product support can make free users unhappy

####Casi di studio
* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [GitLab](https://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)

##Freemium License
*"Freemium" licenses are not open source, because they do not meet all the [required freedoms](https://en.wikipedia.org/wiki/The_Open_Source_Definition) of an open source license simultaneously (ex. the source code is not both freely visible AND available to redistribute and modify). Still, they are tangentially related to open source work.*

*A freemium license restricts some open source freedoms to commercial terms. For example, they might make the source code visible, but require a commercial license to use the code.*

####Vantaggi
* Business model aligned with something people are willing to pay for
* Potential to scale well if successful
* Better for end user products

####Svantaggi
* Not actually open source
* Still a new area of exploration (though related to the [shareware](https://en.wikipedia.org/wiki/Shareware) movement), not well proven

####Casi di studio
* [Fair Source](https://fair.io/), used by [Sourcegraph](https://sourcegraph.com/)
* [BSL (Business Source License)](https://mariadb.com/bsl-faq-adopting), used by [MariaDB](https://mariadb.com/)


##Dual License
*Sometimes, projects offer an identical codebase with two different licenses: one that is commercially-friendly, and one that is less so (ex. GPL). The latter is free for anyone to use, but companies pay for the commercial license in order to have legal peace of mind.*

####Vantaggi
* Business model aligned with something people are willing to pay for
* Can scale well if successful

####Svantaggi
* Can be at odds with making software freely accessible
* Project needs to be big enough that customer need exists

####Casi di studio
* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)

##Open core
*Under an [open core](https://en.wikipedia.org/wiki/Open_core) model, some aspects of the project are free, but other features are proprietary and available only to paid users. Usually this works when there is enterprise demand for the project.*

####Vantaggi
* Business model aligned with something people are willing to pay for
* Can scale well if successful

####Svantaggi
* Need to have something you can charge for (which means making certain features exclusive)
* Can be at odds with making software freely accessible
* “Two tiers” of product support can make free users unhappy

####Casi di studio
* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)

##Foundations & consortiums
*A [foundation](https://en.wikipedia.org/wiki/Foundation_(nonprofit)) is a legal entity that can accept and/or disburse donations. Because their purpose is not to make profits, they can be a great choice to signal neutrality and steward a project. In the US, foundations are either 501(c)(3) (nonprofit) or 501(c)(6) (trade consortium). Many software foundations are 501(c)(6) because 501(c)(3) require demonstrating a charitable purpose, which can be more difficult in software.*

####Vantaggi
* Neutralità. Le fondazioni proteggono il codice ed aiutano lo svilupo della comunità attorno al software. 
* Influence distributed across multiple donors
* Can legitimize project, companies might feel more comfortable giving to foundations than individuals

####Svantaggi
* Vale la pena solo per grossi progetti
* Difficult to set up for IRS reasons (many do 501(c)(6) instead of 501(c)(3)), restrictions on what you can do
* Requires serious community effort and diverse skills (you still need to fundraise after setting up the entity!)

####Casi di studio
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)

##Venture capital
*Venture capital is a form of funding for high growth businesses. Unlike a bank loan or other forms of debt financing, venture capitaists take equity (a percent ownership in your business) in exchange for funding. The tradeoff is that unlike taking out a loan, you don't have to repay your creditors if your business tanks. If you do succeed, however, you should expect to return capital to your investor at a multiple.*

*Venture capital is "high risk high reward": VCs are more risk tolerant than, say, a bank, but they also expect a large payoff if you are successful. If you plan on raising venture capital, you should set up a business entity structured as a C Corp, preferably Delaware. If you're unfamiliar with the venture capital process, the best place to start is by reaching out to similar founders who have successfully raised venture.*

####Vantaggi
* Il supporto di un Venture capital può essere di aiuto per la creazione di un business
* Grande quantità di capitale disponibile

####Svantaggi
* I Venture capital comes with expectations of an exit (i.e. returning the money to investors at a multiple). L'esperienza suggerisce che questo è difficilmente attuabile con i business basati sull'opensource.
* I Venture capital possono cambiare prospettiva, distraendo lo sviluppo dalle priorità reali

####Casi di studio
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)

---

### Contribuire alla guida

Ho scritto questa guida per aggregare le mie conoscenze riguardo questo tema, ma non prevedo di aggiungere ulteriori contributi o cambiamenti. Riconosco che i vantaggi e svantaggi descritti sono soggettivi, dunque rispecchiano il mio punto di vista.

Se qualcosa fosse incorretta (specialmente riguardo i casi di studio), apprezzerò le vostre correzzioni. Inoltre, se conosci una categoria non presente in questa guida, apprezzerò eventuali aggiunte.


### Licenza e attribuzione
Questa guida è disponibile sotto licenza "Creative Commons CC0 1.0 License", sei libero di usarla per qualsiasi scopo, commerciale e non commerciale, senza dover citare l'autore originale (dominio pubblico). Se utilizzi questa guida, mi piacerebbe venirne a conoscenza! (Contattami a: [@nayafia](http://twitter.com/nayafia)) Ovviamente non sei obbligato a contattarmi.

La traduzione in lingua italiana è stata curata da Davide Gessa ([@dakk](http://github.com/dakk), [mail](mailto:gessadavide@gmail.com)); il documento tradotto mantiene la stessa licenza dell'originale. 
