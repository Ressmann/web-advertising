
W3C Improving Web Advertising Success Criteria
==============================================

Unofficial Draft 16th June 2020

Editor:

James Rosewell (james@51degrees.com)

Contributors:

Arnaud Blanchard (a.blanchard@criteo.com)

Brad Rodriguez (brodriguez@rubiconproject.com)

Daniel Sepulveda (dsepulveda@mediamath.com)

Hardeep Bindra (hbindra@gmail.com)

Jochen Schlosser (Jochen.Schlosser@adform.com)

John Sabella (john.sabella@pubmatic.com)

Joshua Koran (jkoran@zetaglobal.com)

Paul Bannister (paul@cafemedia.com)

Paul Chachko (pchachko@throtle.io)

Tom Kershaw (tkershaw@rubiconproject.com)

Wilfried Schobeiri (wschobeiri@mediamath.com)

Abstract
--------

Referencing prior W3C values and principles, GDPR, and a limited number of
external documents, this document defines success criteria to evaluate the
benefit and impact of changes to the web on the interests of societies, people,
publishers and their supply chains, marketers, and delivery access providers.
This document is primarily directed at these five stakeholders. Readers of this
document are expected to be familiar with Web advertising, but are not expected
to have deep familiarity with the technologies involved. The principal objective
is to improve web advertising. No one factor is assumed to be more or less
important than another.

The Improve Web Advertising working group has a shared goal of preserving the
web as an open platform for diverse and rich experiences provided by multiple
parties. Towards this end, our goal is to provide monetization opportunities
that support the open web while balancing the needs of publishers and the
advertisers that fund them with improvements to protect people from the
individual and societal impacts of tracking content consumption over time.

The recommendations refer to the data collection and processing required for
continued ad-funding of web content and services, and not to the processes by
which it is created, nor to the devices or user agents to which it is delivered.

Principles to Improve Web Advertising
-------------------------------------

The open web has become a critical global utility that supports the free flow of
communication, commerce, content and competition. The open web is increasingly
becoming the primary method used by citizens to access news, communicate with
each other, engage with governments, conduct commerce and consume entertainment.
Any individual, business, charity or government organization regardless of
background, geography or wealth can now cost effectively participate in this
global resource. A set of common technical and policy standards makes all this
possible.

The web is an open platform.
[Interoperability](https://www.w3.org/Promotion/WIP) is a fundamental principle
that supports all web technologies. Existing specifications and protocols for
encoding, transmitting and rendering information facilitate these exchanges.
Data portability also helps ensure that the web is interoperable ([GDPR, Recital
68](https://gdpr.eu/recital-68-right-of-data-portability/)).

The web underpins billions of dollars of commercial transactions. Accordingly,
any proposed change to the underpinning policy and technical standards could
have global ramifications. While no one individual is able to understand every
ecosystem dependency to ensure other participants are not unintentionally
undermined, a common set of principles can and should be used to review these
proposed changes.

People’s awareness and understanding of their rights is improving in
jurisdictions where legal frameworks such as GDPR have been introduced ([EDAA
Consumer Research Analysis June 2020](https://www.edaa.eu/wp-content/uploads/Consumer-Research-Analysis-June-2020.pdf)).
People now expect their consent choices to be respected.

This document provides a set of improved web advertising principles that ensure
proposed changes appropriately balance the benefits of a change against its
effect on the rights of individuals and the societies in which they live. When
describing how to balance these important interests in promoting openness and
fairness in the standards they develop, the Internet Engineering Task Force
(IEFT) emphasizes this point:

>   *the IETF is concerned with developing and maintaining the Internet to
>   promote the social good, and the society that the IETF is attempting to
>   enhance is composed of end users, along with groups of them forming
>   businesses, governments, clubs, civil society organizations, and other
>   institutions.* ([Draft - Internet Architecture Board for the End
>   Users](https://intarchboard.github.io/for-the-users/draft-iab-for-the-users.html)).

This does not mean that all stakeholders are unanimously agreed on how to
"improve" the web. Scholars describe diverging interests of stakeholders as a
"tussle."

>   The resulting tussles span a broad scope: the rights of the individual vs.
>   the state, the profit seeking of competitors, the resistance to those with
>   malicious intent, those with secrets vs. those who would reveal them, and
>   those who seek anonymity vs. those would identify them and hold them
>   accountable. ([Tussle in
>   Cyperspace](http://groups.csail.mit.edu/ana/Publications/PubPDFs/Tussle2002.pdf)).

Achieving a balance across the diverse interests of global stakeholders when
determining trade-offs among speed, fairness, security, public accountability,
diversity and quality is in accordance with [values of the
W3C](https://www.w3.org/standards/about.html). To resolve this tussle in the
interests of end users requires us to carefully examine what alternate means are
possible to reach the desired goals. If a negative effect on stakeholders is
unavoidable, then the reasoning behind this decision ought to be thoroughly
documented. Accordingly, this document describes the principles that support the
key interests of the stakeholders who enable people's access to
internet-connected information and services.

These principles are termed "principles" (rather than, for example, "guidelines"
or "requirements") because they attempt to capture important concepts and
aspirations that are [not specific to any particular
realization](https://www.w3.org/TR/2003/NOTE-di-princ-20030901). These
principles can be distinguished from bottoms up, granular "use cases," which
illustrate how an actor can conduct a process to achieve a goal. Like [other
working groups](https://www.w3.org/TR/wsa-reqs/#id2605084), the Improve Web
Advertising business group may choose to adopt the Critical Success Factor (CSF)
Analysis method to better communicate our work. These principles are examined
from three [perspectives](https://www.w3.org/Consortium/Points): that of
individual web users (both in aggregate and individually), publishers and their
partners (both authors and the business model that funds them) and the delivery
access mechanism (both connectivity and navigation).

Any technology can be abused. Open societies do not attempt to suppress
technology, but rather put [appropriate
regulations](https://iabeurope.eu/all-news/iab-europes-press-statement-openrtb-and-eu-data-protection-law)
in place to define acceptable and unacceptable uses of that technology. For
example, automobiles are not required to integrate functionality that
technically prevents them from exceeding the speed limit. Instead, drivers are
educated and trained in traffic rules, and drivers who violate speed limits are
subject to fines and/or deprived of their permits. However, documenting specific
criteria as to what constitutes a violation helps enable easier detection and
reporting of non-compliance with the regulations that govern technology.

By documenting the defined norms and principles behind appropriate and
inappropriate data collection and processing, we can better devise methods of
accountability. This accountability requires each participant that has access to
data collection and processing to abide by its responsibility not to abuse the
data under its control. This in turn requires definitions of legitimate data
collection and processing as well as transparency around whether the data
controller has fulfilled its obligations. One of the first assumptions we
document is that an advertising-funded business model supports the open web, and
hence any changes that degrade the efficacy of this business model negatively
impacts end users. While end users increasingly understand advertising funds
their free access to the open web, they desire improved transparency and control
over their personal data.

![Ethical Data Collection and Processing Protects Freedom](images/success-criteria-3.png)

### Privacy

Individual privacy is a critical issue that societies around the world must
address. Given the pervasiveness of internet-enabled content and services that
support modern societies, it is important we protect people's privacy while
ensuring we do not undermine important societal goals.

Tracking content consumption over time poses risks to people. The measures
required to protect people’s important privacy rights should account for and be
proportionate to the risk of harm. Privacy regulations have identified numerous
harms from these risks. Some of these harms impact society, including
manipulation of political elections by foreign parties, discrimination against
protected classes, and fraud. Some of these harms impact individuals, such as
using content consumption activity ("behavior") in a manner that causes a
negative substantive life impacts on people's access to healthcare, financial
resources or infliction of emotional distress, or is deceptive manipulation.
These harms pose risks not just to the individual but also to the larger society
in which people live.

The General Data Protection Regulation (the “GDPR”) in the EU is widely
recognized as offering a thorough evaluation of the myriad of interests
associated with privacy and data protection. Since May 2018, dozens of
jurisdictions worldwide have adopted all or part of the GDPR. Different regions
may impose different rules, the concepts outlined within the GDPR are helpful
input into the privacy considerations outlined.

As GDPR concisely states, data protection must be balanced with these other
fundamental rights:

>   *The processing of personal data should be designed to serve mankind. 2 The
>   right to the protection of personal data is not an absolute right; it must
>   be considered in relation to its function in society and be balanced against
>   other fundamental rights, in accordance with the principle of
>   proportionality. 3 This Regulation respects all fundamental rights and
>   observes the freedoms and principles recognized in the Charter as enshrined
>   in the Treaties, in particular the respect for private and family life, home
>   and communications, the protection of personal data, freedom of thought,
>   conscience and religion, freedom of expression and information, freedom to
>   conduct a business, the right to an effective remedy and to a fair trial,
>   and cultural, religious and linguistic diversity.* -- [GDPR, Recital
>   4](https://gdpr.eu/recital-4-data-protection-in-balance-with-other-fundamental-rights/)

In an effort to balance these interests, many privacy regulations describe the
privacy risks to people relative to the scale, sensitivity of the data collected
and potential of a significant economic or social impact from its inappropriate
processing. Accordingly, data minimization, purpose limitation, limited storage,
and reliance on pseudonymous identifiers are often recommended to minimize these
risks. (GDPR, Art. [5](https://gdpr.eu/article-5-how-to-process-personal-data/),
[25](https://gdpr.eu/article-25-data-protection-by-design/); [Recital
78](https://gdpr.eu/recital-78-appropriate-technical-and-organisational-measures/))
While data collection and processing should not be presumptively inappropriate,
organizations must account for their use of personal information and mitigate
potential harms.

Moreover, privacy regulations and national laws often provide specific and
appropriate remedies for violations of their codes of conduct. Ensuring improved
accountability is a chief principle of improving web advertising.

### Trust and Interoperability Among Decentralized Parties

[W3C mission](https://www.w3.org/Consortium/Points) is to provide "technologies
(specifications, guidelines, software, and tools) that will create a forum for
information, commerce, inspiration, independent thought, and collective
understanding." Trust and interoperability are two of the core goals in support
of W3C's mission.

Trust requires a system that supports "confidentiality, instils confidence, and
makes it possible for people to take responsibility for (or be accountable for)
what they publish on the Web." [W3C
mission](https://www.w3.org/Consortium/Points) By improving both transparency
and accountability we can ensure market actors earn trust while enhancing
efficiency, efficacy, and fairness in the matching of advertising content to
people.

Much of the web consists of embedded content and centralized services provided
to decentralized publishers (e.g., single sign on, web payments, advertising).
People trust many of the brands they purchase or interact with. Behind most of
these brands are numerous supply chain partners that enable people to benefit
from each brand's end product or service. Digital publishers are no different.
Independent publishers must rely on networks of direct partners and indirect
partners of the marketers that fund their operations. Whether the reliance on
these supply-chain vendors is for cross-publisher budget management services,
independent verification, and authentication services, their objectivity is
necessary for accountability, transparency and reconciliation purposes. This
interoperability is a goal in support of W3C's mission and the first principle
in support of improved web advertising. The trust in this interoperable network
requires transparency and improved documentation of acceptable and unacceptable
uses of data. Organizations must be transparent about the personal information
they collect and how they use it. Organizations must responsibly use this
personal information that is compatible with the interests of individuals and
benefits society, and be held accountable when they abuse this responsibility.

[Some
organizations](https://assets.publishing.service.gov.uk/media/5d78ba3540f0b61c7a66407c/190802_Google_-_Response_to_SoS__Non-confidential_.pdf)
have pointed out that transparency is advanced by vertical-integration. "Opacity
sometimes is a function of fragmentation.... Vertical integration can sometimes
resolve some of the concerns around a lack of transparency and complexity....
Vertical integration means there is a single point of contact for advertisers
and publishers and it eliminates concerns about the possibility of rent-seeking
by difficult-to-identify themselves intermediaries.... vertical integration in
the ad tech state creates efficiencies for users. Changes ought to benefit all
stakeholders, not just one set."

While vertical integration can simplify consumer transparency, it carries the
danger of limiting consumer choices by bundling services. By contrast, the final
sentence in the quote above emphasizes decentralization, which is a third goal
in support of [W3C's mission](https://www.w3.org/Consortium/Points).
"Decentralization is a principle of modern distributed systems, including
societies." Among the rationales supporting decentralization are choice and the
freedom of information. These rationales help keep the market innovative,
competitive and open to new entrants.

The common element among these rationales is the accessibility to a wide array
of diverse publishers. As U.S. Supreme Court Justice Brandeis
[wrote](http://www.columbia.edu/itc/journalism/j6075/edit/readings/brandeis_concurring1.html):
"Among free men, the deterrents ordinarily to be applied to prevent crime are
education and punishment for violations of the law, not abridgment of the rights
of free speech and assembly." Thus to exercise this freedom, people should have
digital access to publishers, which equates to both the right to assembly and
freedom of speech. Safeguarding and improving this accessibility and choice are
the third and fourth principles of improved web advertising.

The IETF's Internet Architecture Board (IAB) also expressed concerns as to
growing consolidation of power on the Internet.

>   *While the IAB, the Internet Society, and others are examining this
>   phenomenon to understand it better, it is nevertheless prudent to consider
>   whether proposals for changes to how the Internet works favors or counters
>   consolidation. Favoring entities with existing advantages - like resources,
>   size, or market share - is not necessarily a factor that disqualifies a new
>   proposal, but it needs to be considered as a cost of enabling that
>   technology.* ([Draft - IAB ESCAPE
>   Report](https://tools.ietf.org/html/draft-iab-escape-report-00)).

The 2019/20 UK [Competition and Market Authority (CMA) studied online platforms
supported by digital
advertising](https://www.gov.uk/cma-cases/online-platforms-and-digital-advertising-market-study).
The [CMA set out five
goals](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/814709/cma_digital_strategy_2019.pdf)
for supporting a trusted, decentralized, interoperable open web, whose operation
relies on web advertising:

1.  promoting "competition for the benefit of consumers";

2.  ensuring "the enormous innovation and benefits brought about through
    digitisation can continue";

3.  creating a "level playing field" for all businesses to compete on the
    merits;

4.  ensuring new competitors can enter digital markets; and

5.  enabling people "to feel trust in online markets.

The above principles for an interoperable web seek to help advance the mission
of the W3C as well as further the objectives outlined by the UK CMA "to promote
competition for the benefit of consumers, both within and outside the UK, to
make markets work well for consumers, businesses, and the economy." To ensure a
level playing field, it is particularly important that smaller organizations be
able to rely on supply chain vendors they require to operate and for the changes
in web technology to encourage new market entrants.

### Principles for Improving Interoperable Web Advertising

The key stakeholders involved in web advertising include individual and groups
of people, publishers, marketers, their supply chain vendors and delivery access
providers. We believe the majority of these interests are compatible with each
other in ensuring people have their rights protected and receive better
products, which is advanced through free market competition.

![Advertising Funds the Open Web](images/success-criteria-1.png)

The following sections outline the key interests and principal goals for each 
stakeholder group.

#### Interests of Society

-   Diversity of publishers that protects:

    -   Freedom of expression to represent minority voices

        -   Free elections protected against foreign manipulation

            -   While free speech requires allowing speech the majority does not
                approve of, we can label political speech by the author’s
                nationality and whether it is endorsed by one or more candidates

        -   Freedom of the press enables watch-dog reporting on important issues
            and combats fake news

    -   Freedom of information to provide fast, easy access to internet-enabled
        content for all

        -   Cost-free access enables access for all, regardless of economic
            means

        -   Freedom from having to self-censor for fear of content consumption
            being associated with directly-identifiable, offline identity

-   Free-market economies rely on competition, and competition benefits from:

    -   low barriers of entry for individuals to start new businesses and
        compete against existing incumbents

    -   market actors having choices regarding which organizations they can work
        with

    -   interoperable standards of communication and ease of data exchanges
        among market actors; and

    -   transparent pricing and fees to ensure markets are operating fairly.

-   Appropriate remedies for members of society harmed by other entities:

    -   Fines

    -   Injunctive action

    -   Antitrust intervention

#### Interests of Individual People

-   Same interests as society-level plus:

    -   Fast, frictionless and secure access to a wide array of internet-enabled
        content and services that make the Web so valuable

-   Appropriate risk mitigation and remedies

    -   Increased transparency on data collection and processing purposes:

        -   Easy access to understandable descriptions of data collection and
            processing purposes

        -   Right to data portability

        -   Right to data access

        -   Increased control over any stable ID with which content consumption
            activity is associated

    -   Increased control over legitimate data processing purposes:

        -   Right to object to marketing-related data processing

        -   Consent for:

            -   Use of interest-based advertising

            -   Use of precise geolocation data

            -   Use of sensitive health and financial data or information
                related to protected classes of individuals

            -   Association of a pseudonymous digital ID with
                directly-identifiable data

            -   Content consumption, communication or commercial activity tied
                to offline identity

            -   Access to adult content by an appropriate guardian to prevent
                unauthorized viewing by underage family members

    -   Remedy for the inappropriate use of personal data

        -   Right to be forgotten that benefits from:

            -   Ability to reset a pseudonymous digital ID

            -   Dissociation of previously associated devices

            -   Dissociation of previously collected data with a pseudonymous
                digital ID

            -   Correction/deletion of directly-identifiable data

            -   Right to be informed of high-risk data breaches

            -   Right to appropriate remedies for harm (e.g., compensation)

    -   Ability to understand the why an advert was displayed, and the identity
        of the parties involved including brand and intermediaries

#### Interests of Marketers

-   The publisher ad-funded business model is supported by addressing marketers
    needs and wants.

    -   [Impacting these marketer interests, reduces publishers' revenue
        earned](https://services.google.com/fh/files/misc/disabling_third-party_cookies_publisher_revenue.pdf)

    -   Negatively impacts the quantity and quality of publishers’ content

    -   Reducing quantity and quality of publishers’ content, conflicts with the
        interests of an open society

-   Marketers who invest in cross-publisher advertising need scaled,
    interoperable measurement and control:

    -   Pre-campaign media planning and forecasting

    -   Real-time feedback to improve content matching and cross-publisher
        budget reallocation to better engage with prospects and customers based
        upon advertising return on investment (ROI)

    -   Fraud and robot detection

    -   Independent verification of delivery and measurement

    -   Attribution of first-party engagement to prior third-party exposure

    -   Aggregate content consumption trends

-   Appropriate risk mitigation and remedies:

    -   Remedy for being charged for inaccurate delivery of content to the
        "right" individuals or the inaccurate measurement of total exposures or
        interactions

#### Interests of Publishers

-   Ad-funded business model to provide free access to all:

    -   Same as marketers' interests that maximize the value of advertising
        inventory

    -   Same as marketers' interests to attract new people to the publisher's
        own property

-   Freedom to provide internet-enabled content/services with the support of an
    open marketplace of vendors.

-   Appropriate risk mitigation and remedies:

    -   Remedy for publisher brand being misappropriated ("repurposing")

#### Interests of Supply Chain Vendors

-   Same interests as are desired by Marketers, Publishers, and Individuals,
    plus:

    -   Ability to support their customers reliance on their technology and
        services

        -   Pre-campaign planning

            -   Media planning and forecasting

            -   Data enrichment services (e.g., context, geographic,
                technographic, audience)

        -   Intra-campaign delivery

            -   Cross-publisher supply and/or marketer demand aggregation that
                improves the fluidity of the market

            -   Data enrichment services (e.g., context, geographic,
                technographic, audience)

            -   Fraud and robot detection

            -   Optimized content matching

            -   Cross-publisher budget reallocation for marketers

            -   Cross-marketer yield optimization for publishers

        -   Post-campaign delivery

            -   Impartial and objective verification of exposure, reach and
                performance

            -   Reporting, insights and recommendations to improve future
                business outcomes

#### Interests of Delivery Access Mechanisms or Gateway Apps (Browsers)

-   Same interests as are desired by society and individuals plus:

    -   The ability to facilitate publisher and marketer engagement with end
        users

        -   Interoperable standards to support the ease of navigation across
            publishers' internet-enabled content and services

-   The ability to differentiate on:

    -   speed of rendering content

    -   ease of navigating the open web

    -   customizability for each person

    -   efficiency in CPU (and hence power and battery consumption)

-   Browsers do not want to differentiate on:

    -   Which internet-enabled content and services (publishers) they are or are
        not compatible with

    -   Security (the internet should be equally secure across all browsers)

        -   Protection against malware

### Principles to Improve Web Advertising

![Choice Improves Value for Publishers, Marketers and People](images/success-criteria-2.png)

The following section outlines the principles to balance the benefits and 
impacts to stakeholders as we seek to improve web advertising.

#### IWAG01 Interoperable

Improved Web Advertising should facilitate data exchange among multiple,
separate services.

-   IWAR01.1 should consist of precisely defined standards for various forms of
    identity and data transfer

-   IWAR01.2 must enable data portability across services and service providers

-   IWAR01.3 should support secure point-to-point communication

-   IWAR01.4 should support ease of navigation

-   IWAR01.5 should provide consistent experiences

-   IWAR01.6 must provide people choice over how data is shared and with whom

#### IWAG02 Accountable

Improved Web Advertising participants must be responsible for their actions to
encourage trustworthy data collection and processing.

-   IWAR02.1 data exchanges and processing must be auditable

-   IWAR02.2 violations for inappropriate actions should be enforceable

-   IWAR02.3 must supply appropriate remedies for harm

-   IWAR02.4 must support freedom of the press to investigate and report on
    wrongdoing

-   IWAR02.5 must provide people the right to be forgotten

-   IWAR02.6 must provide people the right to correction or deletion

-   IWAR02.7 must aid organizations compliance with privacy regulations

-   IWAR02.8 must provide people the right to understand who processes their
    data

#### IWAG03 Accessible

Improved Web Advertising should not impose high costs to send or receive
internet-enabled data.

-   IWAR03.1 should provide frictionless access to a wide diversity of
    publishers

-   IWAR03.2 must be accessible regardless of economic means

-   IWAR03.3 should support freedom of expression

-   IWAR03.4 must keep people free from self-censorship

#### IWAG04 Choice

Improved Web Advertising should not impose high barriers to entry for new market
entrants.

-   IWAR04.1 must support decentralization or sufficient options for centralized
    alternatives

-   IWAR04.2 should support open market competition

-   IWAR04.3 should support freedom of information

-   IWAR04.4 should support diversity, especially minority opinions

#### Success criteria matrix

As described above, many stakeholders share identical interests. The table below
focuses on which interests relate primarily to individuals and which to
organizations of people (marketers, publishers, vendors, access providers,
society)

| **Criteria reference** | **Primary stakeholder interest**  | **Interest category (Functionality / Privacy / Interoperability /etc)** | **Interest priority (Must / Should)** | **Interest description**                                                                            |
|------------------------|-----------------------------------|-------------------------------------------------------------------------|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| IWAR01.1               | Organizations                     | Interoperability                                                        | Should                                | Organizations should communicate advertising-related data with precisely defined standards          |
| IWAR01.2               | Individual                        | Interoperability                                                        | Must                                  | Organizations must enable data portability of personal information across services                  |
| IWAR01.3               | Individual                        | Interoperability                                                        | Should                                | Organizations should support secure point-to-point communication                                    |
| IWAR01.4               | Individual                        | Interoperability                                                        | Should                                | Organizations should support ease of navigation for individuals                                     |
| IWAR01.5               | Individual                        | Interoperability                                                        | Should                                | An individual’s choices must persist across all individual\<\>business interactions                 |
| IWAR01.6               | Individual                        | Interoperability / Privacy                                              | Must                                  | An individual must have choice over how their data is shared and with whom.                         |
| IWAR02.1               | Individual                        | Accountability                                                          | Must                                  | Organizations must provide Individual data access rights and processing use-cases must be auditable |
| IWAR02.2               | Individual                        | Accountability                                                          | Should                                | Violations for inappropriate actions should be enforceable                                          |
| IWAR02.3               | Individual                        | Accountability                                                          | Must                                  | Organizations must supply people appropriate remedies for harm                                      |
| IWAR02.4               | Organizations                     | Accountability                                                          | Must                                  | Organizations must support freedom of the press to investigate and report on wrongdoing             |
| IWAR02.5               | Individual                        | Accountability                                                          | Must                                  | Organizations must provide people the right to be forgotten                                         |
| IWAR02.6               | Individual                        | Accountability                                                          | Must                                  | Organizations must provide people the right to correction or deletion                               |
| IWAR02.7               | Organizations                     | Accountability                                                          | Must                                  | Must aid organizations compliance with privacy regulations                                          |
| IWAR02.8               | Individual                        | Accountability                                                          | Must                                  | Must provide people the right to understand who processes their data                                |
| IWAR03.1               | Individual                        | Accessible                                                              | Should                                | Organizations should provide people frictionless access to a wide diversity of publishers           |
| IWAR03.2               | Individual                        | Accessible                                                              | Must                                  | Web must be accessible for all people regardless of economic means                                  |
| IWAR03.3               | Individual                        | Accessible                                                              | Should                                | Organizations should support freedom of expression for people                                       |
| IWAR03.4               | Individual                        | Accessible                                                              | Must                                  | Organizations must keep people free from self-censorship                                            |
| IWAR04.1               | Organizations                     | Choice                                                                  | Must                                  | Organizations must support decentralization or sufficient options for centralized alternatives      |
| IWAR04.2               | Organizations                     | Choice                                                                  | Should                                | Organizations should support open market competition                                                |
| IWAR04.3               | Individual                        | Choice                                                                  | Should                                | Organizations should support freedom of information                                                 |
| IWAR04.4               | Individual                        | Choice                                                                  | Should                                | Organizations should support diversity, especially minority opinions                                |