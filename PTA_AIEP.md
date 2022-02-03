---
title: "Making and using digital (critical) editions of Christian texts from antiquity: The Patristic Text Archive (PTA)"
author: "Dr. Annette von Stockhausen (BBAW, Berlin)"
---

Hello, my name is Annette von Stockhausen. 

[s] I’m directing the long-term research project “Die alexandrinische und antiochenische Bibelexegese in der Spätantike” at the Berlin-Brandenburg Academy of Sciences and Humanities in Berlin, Germany. The main goal of this research project is to provide critical editions of important late antique Christian exegetical works in *Greek*, namely the *commentaries on the Psalms* by Eusebius of Caesarea, the *commentary on the book of Daniel* by Theodoret of Cyrus, the *Commentarius magnus in Psalterium* and the *De titulis Psalmorum/Scholia in Psalmos* of Hesychius of Jerusalem, *De adoratione in cultu et veritate* and *Glaphyra in Pentateuchum* of Cyril of Alexandria, and the *homilies* of Severian of Gabala.

In this presentation, I would like to talk to you about which *methods* we use, when we prepare our (critical) digital editions, how we *present* these (critical) digital editions in the “Patristic Text Archive” (besides print editions in the series of the *Griechische und christliche Schriftsteller – GCS*), and what this means for *you* as scholars of Patristic literature.

But before I start, I’d like to express my gratitude to our president, Professor Patricia Ciner, for the invitation to talk to you in this new series “Researching Patristic Studies in the 21st century: challenges, possibilities, and new methods” at the Youtube channel of the International Association of Patristic Studies.

[s] The “Patristic Text Archive” (abbreviated: PTA) is the repository, the toolbox, and the publication platform for the editions in our project “Die alexandrinische und antiochenische Bibelexegese in der Spätantike”. As this project is midway, the PTA is work-in-progress, too: Not all planned features are already implemented, and the editions are either completely missing or in active development. 

[s] [s] But the PTA is planned for more than that: it is conceived as an *open* archive for (annotated) *editions* (in *all languages* transmitting texts of Christian antiquity) and for *translations* (in all modern languages) of all kinds of sources. There are already ongoing efforts to retro-digitize editions published in the series of the “Griechischen christlichen Schriftsteller (GCS)” and the “Corpus scriptorum ecclesiasticorum latinorum (CSEL)”.

[s] The PTA aims at following the FAIR principles. I’d like to focus here on the *A* (for “accessible”), the *I* (for “interoperable”), and the *R* (for “reusable”).

As I already said, on the one hand, the PTA is a *website* intended for human users, but it also provides an *API* for machine users, and all data generated is published (and versioned) at a repository on [Github](https://github.com). 

Furthermore, the PTA is linking with other projects, like the Clavis Clavium database or the Pleiades Gazetteer, it's refering to norm data like the Diktyon-IDs for Greek manuscripts or to normalized vocabulary like the Dublin Core Metadata Initiative, and it is using established standards like the Text Encoding Initiative (TEI) or CapiTainS, the “suite of tools and guidelines for Citable Text APIs standards”.

And last, but not least: all data is published open access (using Creative Commons licenses). This means, all data in the PTA can be freely accessed and re-used – unlike the commercial text databases, you may know and use.

[s] Let’s take a closer look now. When speaking about digital editions in general and the PTA in special, probably the most important thing to keep in mind is a strong distinction between the *data* and the *presentation* of the data.

[s] First, I like to discuss the *data*. You could think of it as of “the XML files” or “the edition proper”. 

For quite some time there exists a standard data format and way of encoding information for texts, defined and maintained by the “Text Encoding Initiative”, abbreviated: “TEI”. In short: the TEI provides a fixed set of XML-based vocabulary (XML, the “Extensible Markup Language”, being a markup language and file format) to be used, which is then further restricted by the edition guidelines for the PTA.

All new critical editions in the PTA are build up from (more or less) diplomatic transcriptions of all manuscript witnesses, (from translations), and from the (“Lachmannian”) edition which tries to do its best to reconstruct the “original” text. You could say, that this digital approach tries to reconcile “Lachmannian” tradition with “new philology” – at least to some extant. In any case, in this approach the manuscript and the text transmitted by the manuscript gets more attention than only being seen as a witness of textual variants. We also try to strengthen this manuscript centered approach by providing manuscript descriptions – although I have to admit that extensive codicological information is missing; the focus is on the content of the manuscripts.

Being not constrained by conventions of printed critical editions (i.e. to keep everything as short as possible to best fit on a page and into a book), our critical digital editions also provide documentation of the textcritical decisions or the evaluation of textual variants, and of the editorial process as a whole (you could call it a textcritical “commentary”). 

And finally, the editions are enriched by annotations, for example by marking-up and referencing biblical (and other) quotes, persons, and places, but also by providing metadata on the works or manuscripts edited.

[s] Here, we have not enough time to go deeper into the file structure and the rules applied in encoding the transcription and the edition, but I'd like to at least give you some impression and show you an example of the source file of a transcription and of a critical edition. [s]

[s] The second part, and for the user the probably more interesting one, is the *presentation* of the data. You could think of it as “the website”, but also “the book”, as in our project we follow a hybrid publication scheme, publishing both online and in print (in our GCS series). That means, also the publication in print is based on the digital edition, but (among other information losses) without the manuscript transcriptions, which are only published online.

The PTA website provides multiple approaches to our data: You can access it via authors and works, via the manuscript descriptions, via indices (of biblical references, of persons, and of places), and via a search interface, which is unfortunately still only in *alpha* status, i.e. not yet very useable.

The “reader” interface provides the user with a visualisation of the metadata (like the sources used or identifiers like the CPG number) and with recommendations for reuse (how to cite, a permalink, versions – “editions”, and the license applicable for reuse).

It also visualises all annotations, first of all the variants (so to speak the “critical apparatus”) and quotes in the critical editions, but also corrections, initials, linebreaks and the like in the transcriptions.

Using and linking extant authority files (and here going beyond the plain information in the data files), the PTA website enriches the annotations, for example by providing additional information about the places and persons marked-up or by citing the biblical text quoted (according to modern standard editions like Rahlfs for the LXX or NTG for the NT).

Also going beyond the plain information in the data files and beyond print editions, the PTA website provides dictionary access (only for Greek at the moment) and links to the Voyant Tools for text analysis (not yet with lemmatized versions of the texts). In a future release of the website, it will also be possible to view digitized images of manuscripts (as far as they are available via the IIIF standard) alongside the transcription.

At the moment, it's possible to read two versions of the same text besides each other, for example edition and translation or edition and manuscript transcription or two different manuscript transcriptions. In a future release it will be possible to read any two texts besides each other; a future release will also provide access to earlier versions of the edition (which are now accessible only in the data repository), thus increasing the citability of the editions in the PTA.

Finally, it is important to note, that for the internet publication we link to and ingest a lot of data provided by other projects, like the already mentioned Pleiades Gazetteer, but we also use extant services for lemmatization and morphological analysis (like the one provided by the [CLTK](http://cltk.org)) or [CETEIcean](https://github.com/TEIC/CETEIcean), a javascript library for rendering the TEI-XML code.

For more information, you can refer to the documentation of our technical implementation at the PTA website. Mentioning the technical implementation, I'd like to take the opportunity and mention Dr. Martin Fechner (backend, API) and Jan Köster (frontend), my two colleagues at the BBAW responsible for the programming of the presentation mode of the PTA.

[s] I’d like to give you now a short live demonstration of the PTA. Doing that, I’d also like to encourage you to explore on your own later.

[s] Before coming to the end, I’d like to add one more aspect, which is connected to the openess of the PTA: Of course, you can use the tools I’ve just presented to you. We‘ve selected these tools and these ways of access, because we think that they are helpful for reading and using our editions and doing research on ancient Christian texts. Nevertheless, you probably have other research questions than us. By providing the data and by serving an API, we've enabled you to use your own tools or tools like AntConc or the CLTK for other kinds of analyses. We'd also like to invite you to use our data and add your own annotations (and best to feed back this further enhanced data into the PTA). And last, but not least, you could also write your own conversion script for our data to make a book, a reader for seminars, etcetera. 

[s] I’d like to conclude with an evaluation of the drawbacks and of the benefits of going digital in Patristic textual studies: 

[s] As may have become obvious in my presentation, it is to be recognized that making digital (critical) editions is paired with quite some effort and costs: first of all, we need special training both for the digital editorial techniques (i.e. TEI-XML) and for the development of presentation frameworks for the internet (i.e. web technologies). 

Digital editions actually provide more data and more information than “classical” print editions – just think about transcribing a text from a manuscript instead of only collating and pre-selecting relevant variants: as a matter of course, preparing that “more” information needs more time and eventually more money. And finally, going digital *and* securing long-time availability implies the permanent availability of an infrastructure (i.e. servers) that is kept on top of the technical development (i.e. impying the need to periodically rewrite web frontends and possibly also to convert the data formats now and then).

At the moment, citability is also a still to be solved problem, even if we may at least theoretically be close to a solution. 

At the Berlin-Brandenburg Academy of Sciences and Humanities, we’ve devised the PTA in the effort to overcome these obstacles by providing a framework into which other (smaller projects or individual researchers) can fit their editions without the need to cater for individual solutions – and by providing such a common framework for Patristic studies to steer clear of erecting silos with no or difficult to establish connections between each other.

At the same time, we hope that our plan to have a text archive for all languages of Patristic literature also facilitates new approaches beyond “Greek” or “Latin“ or “Coptic” or “Syriac” Patristics in the long run.

[s] This leeds me to the last slide in my presentation. Going digital also has its benefits, especially if “digital” is paired with “open access”, and if the Patristic scholar using digital ressources is a “digital literate user” – and I‘d like to mention only in passing that that of course has implications for the training of future generations of students.

Digital (critical and scholarly) editions are worldwide accessible (at least as long as there is an internet connection). Annotations and (more extensive) documentation of decisions in the editorial process improve the resulting critical editions. Providing not only textual variants, but also transcriptions (and possibly digitized photographs) of manuscripts enable users of digital critical editions in a superior way to verify or falsify the work done by the editor or in general to reconstruct the rationale of the editor by being provided with more information. So, it is to be hoped that we get more reliable editions, and at the same time are better equipped to make our own appraisal of the history of transmission of a text – if we want to.

Not being confined to print, it is much easier with digital editions to make a “second edition”, i.e. to amend editions, if new evidence arises, or to add new and other annotations to an extant edition – and at the same time keeping the “first edition” as citable object through versioning. (For the PTA we’ll achieve this with the next update of our web presentation.)

Finally, following the FAIR principles, digital editions enable multiple approaches and diverse analyses as well as your own additions to the data already extant. 
In this respect, you can contribute also to the PTA by providing (critical) editions, transcriptions of manuscripts, or translations as well as by reporting errors or omissions in the data already in the archive.

[s] Please don’t hesitate to contact me, if you like to contribute or if you like to know more about the PTA.

Thank you for your attention.