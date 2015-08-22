Liu, Alan et al. Born-Again Bits: A Framework for Migrating Electronic Literature. Electronic Literature Organization, 2005. <http://eliterature.org/pad/bab.html>


Preface: Born-Again Bits and the ELO PAD Project

"With the release of Born-Again Bits, ELO continues the argument by envisioning a technical framework that can not just keep e-lit alive but allow it to come back to life in new forms adapted to evolving technologies and social needs." (Liu et al)


1 Bringing Electronic Literature Back to Life: Preservation by Migration

"Though much can be done with existing technologies, standards, and practices to give electronic literature a longer life, there will inevitably come a time when changes in hardware, software, and other factors accumulate to the point that keeping the patient on life support is no longer feasible." (Liu et al)

"it is useful to think not just of keeping electronic literature alive, but of giving it new lives‚Äîof allowing "born-digital" literature to be reborn. The long-term preservation and dissemination of e-lit requires a strategy of hardware and software migration." (Liu et al)

1.1 What is the object of migration?

"From the point of view of long-term digital preservation, however, the entity of interest is not necessarily any discrete object but the working relationship among objects (each of which may mutate) that assures readability." (Liu et al)

1.2 Who will migrate digital literature?

"The migration of electronic literature must occur in a framework that accommodates not just swarming technical changes but equally complex, swarming social needs. The players in the game, after all, will not just be the original authors and readers but also future users with more diverse, autonomous needs‚Äîfor example, secondary authors or remixers (who might create, for example, works dynamically quoting or aggregating other works), publishers, editors, distributors, instructors, students, and collective users (as in the setting of a classroom or reading society). Indeed, even the burgeoning league of software agents, Web services, RSS readers, and other instances of what might be called machinic "users" (automated ways of distributing, parsing, and repackaging information) will need to be considered as virtual members of the society of e-lit." (Liu et al)

1.3 What are the specific challenges of electronic literature to migration?

"Many technical solutions are being developed by humanities computing scholars and information-science researchers to ensure that digital media will have a longer "shelf life." However, as the shelf metaphor might indicate, these solutions (for example, the Text Encoding Initiative's TEI schema or the library METS metadata standard) are often currently better suited for print, or print-like, static works that have been digitized than for born-digital artifacts of electronic literature with dynamic, interactive, or networked behaviors and other experimental features" (Liu et al)

1.4 What are the main strategies for migration?

"One strategy for migration is to interpret or emulate electronic literature so that works now difficult or impossible to read can be experienced once more in a form as functionally like the original as possible... The other strategy is to describe or represent works‚Äîfor example, in XML‚Äîso as to facilitate moving them into alternative formats and software..." (Liu et al)

"To imagine what a framework for the long-term preservation and migration of electronic literature might look like, ELO has sketched out a twofold plan that draws upon both the above strategies. The two branches of the plan are the Interpreter Initiative and X-Literature Initiative." (Liu et al)


2 Interpreter Initiative

"ELO proposes the development of open source interpreters to "run" important or populous categories of e-lit‚Äîfor example, Hypercard‚Äîso as speedily to restore large numbers of older works to readable status." (Liu et al)

2.1 Technical Analysis of Interpretation/Emulation

"per work" techniques: porting, reimplementation -- "'Per-work' techniques will no doubt continue to be used occasionally by those working in new media preservation, but because they are resource-intensive and only result in the preservation of one work at a time (that is, one work per each particular software development effort) they will likely not be the focus of long-term digital preservation efforts. Instead, such preservation will focus on software development that makes whole categories of work accessible." (Liu et al)

"per category" techniques: "One preservation approach that can be very effective is to develop new, open source interpreters for obsolete or near obsolete electronic literature systems." (Liu et al)

"Currently, HyperCard works can be accessed on Macintoshes in Classic mode, but it is clearly not a priority for Apple that HyperCard remain functional in future Mac OS releases. Apple has also recently refused permission to academics seeking to redistribute the HyperCard Player. *The development of a HyperCard interpreter would be a highly visible and effective way to make a large body of older electronic literature accessible and would have an immediate effect in the classroom, where substantially more works would be made available for study.*" (Liu et al)

"Developing an emulator is usually more difficult than developing an interpreter because a host of new issues (including timing issues) emerge when the hardware level must also be considered" (Liu et al)

2.2 Implementation Plans for Interpreter Initiative

2.2.1 Create an Interpreter for Hypercard
2.2.2 Create Interpreters for other candidate systems -- Storyspace, Director
2.2.3 Create Related Services -- distribution website, etc.


3 X-Literature Initiative

"it is clear that there are limitations to the purely reactive approach of building interpreters to keep up with the ceaseless mutation of technology. This is because any interpreters (and emulators) will restore to readability only a selected subset of older electronic literature; interpreters do not extend or enhance the usability of e-lit; and interpreters will themselves periodically need to be updated with little expectation of help from a broader or commercial development community." (Liu et al)

"Seen in a larger perspective, the problem is not the preservation of old or aging e-lit per se. It is the description and representation of electronic literature of any vintage in a neutral, open source, standards-based format‚Äîone capable of maintaining the essential experience of a work while allowing its presentation to adapt to evolving hardware and software channels through understood, regular, and automated methods of transformation. The problem of preserving electronic literature, in other words, takes its place within the general problem of the platform-neutral representation and transformation of digital media." (Liu et al)

"ELO proposes the creation of an integrated format for the representation and transformation of electronic literature. This format‚Äîto be called X-Literature (X-Lit, for short)‚Äîinvolves developing a rich, XML-based representation of electronic literature that will be human-readable and machine-playable (as well as machine-transformable) long into the future. Specifically, X-Lit will be a set of open source XML standards, metadata standards, XML applications, and related services designed to augment similar formats in the library or commercial worlds by providing specific extensions and implementations needed to handle electronic literature." (Liu et al)

3.1 Technical Analysis of XML and Metadata Standards to Facilitate the Migration of E-Lit

3.1.1 XML (Extensible Markup Language)

"XML is a markup language for the logical ("structured") representation of data that inherits much of the combined rigor and extensibility (or the ability to be adapted for various purposes) of its predecessor SGML. However, XML is especially adapted to distributed, networked environments. For example, XML is what allows so-called "Web services" and RSS readers to pull content out of one proprietary database or other application, send it through the Internet, and read or act upon it in another database or application not originally designed to talk to the content-source." (Liu et al)

available methods for processing XML documents: XML Style Language (XSL), XSL Transformation Language (XSLT), XML Query

graphical information addressed by Structured Vector Graphics (SVG) and Synchronized Multimedia Integration Language (SMIL) can deal with animations like those in Flash & Director

3.1.2 Metadata Standards (and Archival Reference Models)

OAIS (Open Archival Information System); METS (Metadata Encoding and Transmission Standard); RDF (Resource Description Framework)

3.1.3 Conclusions of Technical Analysis of XML and Metadata to Facilitate the Migration of E-Lit

"Given the momentum behind XML and metadata standards, it will be important for authors, publishers, and archivists of electronic literature to help educate their communities in the most important standards and to adapt those standards for their purposes." (Liu et al)

3.2 Technical Analysis of Types of Electronic Literature to Be Represented in X-Literature Format

"Whether or not a particular obsolete work can be restored to full function from its XML representation, the representation will still serve the purpose of enhancing the activities of archiving, searching, and studying. Such benefits would also accrue to new electronic literature created in conformance to X-Lit. In general, works represented in carefully designed XML are more amenable not just to preservation but to textual and critical analysis, propagation through multiple channels, adaptation to various uses and presentations, and so on." (Liu et al)

3.2.1 Static Works
3.2.2 State-Based Computational Works
3.2.3 More Intensively Computational Works
3.2.4 Conclusions of Technical Analysis of Types of Electronic Literature to Be Represented in X-Literature Format

3.3 Technical Analysis of Electronic Literature Tools for the X-Literature Format

3.3.1 Migration Tools: Applications for Migrating Existing Electronic Literature into X-Lit Format (X-Lit Migrator)
3.3.2 Reading and Editing Tools: Applications for Displaying, Querying, Annotating, Editing, and Teaching Electronic Literature in X-Lit Format (X-Lit Reader)
3.3.3 Authoring Tools: Applications for Creating Electronic Literature in X-Lit Format (X-Lit Muse)
3.3.4 Conclusions of Technical Analysis of Electronic Literature Tools for the X-Literature Format

3.4 Implementation Plans for X-Literature Initiative

3.4.1 Stage One: Conduct Detailed Studies
3.4.2 Stage Two: Create XML Schemas
3.4.3 Stage Three: Create Tools and Associated Services


4 Conclusion: Setting a Standard, Sharing the Labor

"The long-term preservation of digital works‚Äîand especially of complex or experimental e-lit works that test the limits of new media‚Äîwill require the labor of many stakeholder communities (authors, readers, editors, teachers, publishers, librarians, programmers) that presently do not have excellent means of coordinating with each other. Establishing a framework that can allow for the commitment of time and resources from distributed sources without everyone needing to reinvent the wheel is what the creation of standards‚Äîespecially open source standards‚Äîis all about." (Liu et al)

[1]:     http://eliterature.org/pad/bab.html 
